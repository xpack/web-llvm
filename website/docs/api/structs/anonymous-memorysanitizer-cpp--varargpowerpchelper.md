---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-memorysanitizer-cpp-/varargpowerpchelper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `VarArgPowerPCHelper` Struct Reference

<p>PowerPC-specific implementation of <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelper">VarArgHelper</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{MemorySanitizer.cpp}::VarArgPowerPCHelper { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase">VarArgHelperBase</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4588465e6b40112792c0e7fc6f8ae69a">VarArgPowerPCHelper</a> (Function &amp;F, MemorySanitizer &amp;MS, MemorySanitizerVisitor &amp;MSV, unsigned VAListTagSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e4ae572b54705c019d49eaed31ce04f">visitCallBase</a> (CallBase &amp;CB, IRBuilder&lt;&gt; &amp;IRB) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Visit a <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a>. <a href="#a8e4ae572b54705c019d49eaed31ce04f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a7c02af1eb9545e64bdf82e7f7d763e">finalizeInstrumentation</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize function instrumentation. <a href="#a6a7c02af1eb9545e64bdf82e7f7d763e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0c1bb48e148bc7fdbf5cf1a93fea2af">VAArgTLSCopy</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0de7fbff7ecdbca47fd90bf405cab0c5">VAArgSize</a> = nullptr</td>
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

<p>PowerPC-specific implementation of <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelper">VarArgHelper</a>.</p>

<p>Definition at line 5966 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VarArgPowerPCHelper() {#a4588465e6b40112792c0e7fc6f8ae69a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MemorySanitizer.cpp}::VarArgPowerPCHelper::VarArgPowerPCHelper (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/anonymous-memorysanitizer-cpp-/memorysanitizer">MemorySanitizer</a> &amp; MS, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor">MemorySanitizerVisitor</a> &amp; MSV, unsigned VAListTagSize)</td>
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



<p>Definition at line 5970 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#ac623eb128c5461605b2eade89195434a">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::F</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#afe3dd307fd5cf1bb35263184495a00f4">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MS</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a3ca4068a52ed23406c810243aea0daa8">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MSV</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a72c961dcb5984bc8d8d405a142f67ea7">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::VAListTagSize</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a45091e4338a16315424df2082d8e9275">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::VarArgHelperBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### finalizeInstrumentation() {#a6a7c02af1eb9545e64bdf82e7f7d763e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::VarArgPowerPCHelper::finalizeInstrumentation ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finalize function instrumentation.</p>


<p>This method is called after visiting all interesting (see above) instructions in a function.</p>


<p>Definition at line 6065 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1b30cd686a320a8e5cb4532fd3a552a8">llvm::IRBuilderBase::CreateAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a7e0a0c76340ba1fc52863f538f3e703d">llvm::IRBuilderBase::CreateBinaryIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae9f2730f66215fdb82f4e41e45124811">llvm::IRBuilderBase::CreateMemCpy</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4910aab8d7c5528c1a3ac747856c3186">llvm::IRBuilderBase::CreateMemSet</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aae2c1bf70058f3665edaec525457030c">llvm::IRBuilderBase::CreatePtrToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#ac623eb128c5461605b2eade89195434a">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::F</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a64748b5a9f8d8dd4499f84312e2c1336">llvm::IRBuilderBase::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7be2e1490f01c049d748436f03760c5">llvm::IRBuilderBase::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#ab61d338cbe7892ab484e97c9b0c8c8c9">llvm::Triple::isPPC64</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#adce9aed4162f58fbab5da93984822c3a">kParamTLSSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a58600da67d1e0fa57a2a70cd3be51d6e">kShadowTLSAlignment</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#afe3dd307fd5cf1bb35263184495a00f4">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MS</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a3ca4068a52ed23406c810243aea0daa8">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MSV</a>, <a href="#a0de7fbff7ecdbca47fd90bf405cab0c5">VAArgSize</a>, <a href="#af0c1bb48e148bc7fdbf5cf1a93fea2af">VAArgTLSCopy</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a72c6c644a0fd7b5f440affe2512f8213">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::VAStartInstrumentationList</a>.</p>

</div>
</div>

### visitCallBase() {#a8e4ae572b54705c019d49eaed31ce04f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::VarArgPowerPCHelper::visitCallBase (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Visit a <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a>.</p>

<p>Definition at line 5974 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ad027ea8803d83ee19b9a2e13aec6d655">llvm::CallBase::args</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad4e4b11a1bf18be51b28b7fadfaa97d6">llvm::IRBuilderBase::CreateAlignedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae9f2730f66215fdb82f4e41e45124811">llvm::IRBuilderBase::CreateMemCpy</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#ac623eb128c5461605b2eade89195434a">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::F</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac3c35bd078a268a207f607d0f57dadba">llvm::CallBase::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7be2e1490f01c049d748436f03760c5">llvm::IRBuilderBase::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a104d6154321899b53e40455e71d8e83a">llvm::FunctionType::getNumParams</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a7713a45c8983df00c3975444b94e69ae">llvm::CallBase::getParamAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a88cc5fa65ff17e62b49dc5fb4401f813">llvm::CallBase::getParamByValType</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#af8b287b4aad36e62604d98184648bc7e">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::getShadowPtrForVAArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#ab61d338cbe7892ab484e97c9b0c8c8c9">llvm::Triple::isPPC64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1ab21929777b807678f98c873cdd7c7c">llvm::Triple::isPPC64ELFv2ABI</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a670980c63f2e5ca39022baf96173eb9c">llvm::Type::isPPC_FP128Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a58600da67d1e0fa57a2a70cd3be51d6e">kShadowTLSAlignment</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#afe3dd307fd5cf1bb35263184495a00f4">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MS</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelperbase/#a3ca4068a52ed23406c810243aea0daa8">anonymous{MemorySanitizer.cpp}::VarArgHelperBase::MSV</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#a4cbb2344996abd4332716e76178ad4f4">llvm::CallBase::paramHasAttr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### VAArgSize {#a0de7fbff7ecdbca47fd90bf405cab0c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{MemorySanitizer.cpp}::VarArgPowerPCHelper::VAArgSize = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5968 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a6a7c02af1eb9545e64bdf82e7f7d763e">finalizeInstrumentation</a>.</p>

</div>
</div>

### VAArgTLSCopy {#af0c1bb48e148bc7fdbf5cf1a93fea2af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst* anonymous{MemorySanitizer.cpp}::VarArgPowerPCHelper::VAArgTLSCopy = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5967 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a6a7c02af1eb9545e64bdf82e7f7d763e">finalizeInstrumentation</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
