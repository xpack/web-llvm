---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `AMDGPULibFunc.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpu-h">AMDGPU.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmap-h">llvm/ADT/StringMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">llvm/ADT/StringSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">llvm/IR/ValueSymbolTable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">llvm/Support/ModRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulibfunc-cpp-">anonymous{AMDGPULibFunc.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-amdgpulibfunc-cpp-/manglingrule">ManglingRule</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgpulibfunc-cpp-/unmangledfuncinfo">UnmangledFuncInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgpulibfunc-cpp-/paramiterator">ParamIterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-amdgpulibfunc-cpp-/itaniumparamparser">ItaniumParamParser</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgpulibfunc-cpp-/itaniummangler">ItaniumMangler</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7b4b404af5f382847f4d289c5579a39">parseVecSize</a> (StringRef &amp;mangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static AMDGPULibFunc::ENamePrefix</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56ec8af379a8cf1ff76e2171f0bbbbb3">parseNamePrefix</a> (StringRef &amp;mangledName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65ab7aab012d6fd0cde13082da730fa2">getItaniumTypeName</a> (AMDGPULibFunc::EType T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad618098d4191356253e5694fd90a4634">getIntrinsicParamType</a> (LLVMContext &amp;C, const AMDGPULibFunc::Param &amp;P, bool UseAddrSpace)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19a18bb15d7ea5107103d673df93abc9">EnableOCLManglingMismatchWA</a>("amdgpu-enable-ocl-mangling-mismatch-workaround", cl::init(true), cl::ReallyHidden, cl::desc("Enable the workaround for OCL name mangling mismatch."))</td>
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

### getIntrinsicParamType() {#ad618098d4191356253e5694fd90a4634}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * getIntrinsicParamType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> AMDGPULibFunc::Param &amp; P, bool UseAddrSpace)</td>
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



<p>Definition at line 932 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp">AMDGPULibFunc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#aac00986b9c47fed034287e1eeb01a141ab7955061b9da9115dc37f1baf7f3cbca">llvm::AMDGPULibFuncBase::ADDR_SPACE</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a530383443ddee974289016216d02d38e">llvm::AMDGPULibFuncBase::B16</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a27954da45df36722e84d4d7920c160a4">llvm::AMDGPULibFuncBase::B32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a8c7290400f7627e11246a1787a9b6a69">llvm::AMDGPULibFuncBase::B64</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8aef7f289d40cba38e952183b488e6745d">llvm::AMDGPULibFuncBase::B8</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#aac00986b9c47fed034287e1eeb01a141ace38fa4a412a5fe40cde9a544b2e64f3">llvm::AMDGPULibFuncBase::BYVALUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a3bcd722d2d045ca33574c1cd0a1ea34d">llvm::AMDGPULibFuncBase::DUMMY</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a3b58a8396e18962b04903105bb925fb4">llvm::AMDGPULibFuncBase::EVENT</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8af91b4c3fb5deff779fa5884c0d521278">llvm::AMDGPULibFuncBase::F16</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8af5e427970dc9c29ec50cb3f39fbcf774">llvm::AMDGPULibFuncBase::F32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a06c2414f8276b0025f4057efce9bc562">llvm::AMDGPULibFuncBase::F64</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8ab7c0bdf13a234a4771f7580b16fb617f">llvm::AMDGPULibFuncBase::FLOAT</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">llvm::PointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acb145f988329d1d621f73abcafea21d8">llvm::Type::getDoubleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ad5e0fe0efdd88f98a5b5eb512d5351c2">llvm::Type::getFloatTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ae550f2e9436b395b614b4377ba27007f">llvm::Type::getHalfTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a87f56db834c58ca630624956ecf6972f">llvm::Type::getInt16Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a3a5514459881fc9d2444d6ac8a18a8c2">llvm::AMDGPULibFuncBase::I16</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a8039c0339aea621d2589419bc0c7ffdf">llvm::AMDGPULibFuncBase::I32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8aaeb097d554a6e77e61dd1dc797ea062f">llvm::AMDGPULibFuncBase::I64</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8ad0af55ef4d18b5452d50afa947f2f150">llvm::AMDGPULibFuncBase::I8</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a2d2bd20792beb08e2871525ff0bd61bd">llvm::AMDGPULibFuncBase::IMG1D</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8aa4a0749682012c0c912a6c67faac089f">llvm::AMDGPULibFuncBase::IMG1DA</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8acdc53f4dbf399c54a795dcd836b085b4">llvm::AMDGPULibFuncBase::IMG1DB</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a678e88a9aa9bd4cecb5a9a75f11e0b2a">llvm::AMDGPULibFuncBase::IMG2D</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8acbd1cf99158a98160aeba7a1e350ed80">llvm::AMDGPULibFuncBase::IMG2DA</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8ad6ca04175915d03dee3f3d3d2669dfd7">llvm::AMDGPULibFuncBase::IMG3D</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a5e762edbd94c2c234a799ba2954e5845">llvm::AMDGPULibFuncBase::INT</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8aea0f57e5792d27177089744d2d67949c">llvm::AMDGPULibFuncBase::SAMPLER</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a2830c9fe1a1e162ab0ef8053d6917a7a">llvm::AMDGPULibFuncBase::SIZE_MASK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a76424308db519548eaeda3655a288bc4">llvm::AMDGPULibFuncBase::U16</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a3e402cd027c568fa43f4b554c0b348b6">llvm::AMDGPULibFuncBase::U32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a8c6c6342eca81ee6609a590cdc4fcad6">llvm::AMDGPULibFuncBase::U64</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8ae8baa7f9c7af35b4306f6d225214404e">llvm::AMDGPULibFuncBase::U8</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8aa58407df436b853385d7db02b81a8a22">llvm::AMDGPULibFuncBase::UINT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpumangledlibfunc/#aa6728197a535e01349675bcc721e56c3">llvm::AMDGPUMangledLibFunc::getFunctionType</a>.</p>

</div>
</div>

### getItaniumTypeName() {#a65ab7aab012d6fd0cde13082da730fa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getItaniumTypeName (AMDGPULibFunc::EType T)</td>
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



<p>Definition at line 741 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp">AMDGPULibFunc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a3b58a8396e18962b04903105bb925fb4">llvm::AMDGPULibFuncBase::EVENT</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8af91b4c3fb5deff779fa5884c0d521278">llvm::AMDGPULibFuncBase::F16</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8af5e427970dc9c29ec50cb3f39fbcf774">llvm::AMDGPULibFuncBase::F32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a06c2414f8276b0025f4057efce9bc562">llvm::AMDGPULibFuncBase::F64</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a3a5514459881fc9d2444d6ac8a18a8c2">llvm::AMDGPULibFuncBase::I16</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a8039c0339aea621d2589419bc0c7ffdf">llvm::AMDGPULibFuncBase::I32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8aaeb097d554a6e77e61dd1dc797ea062f">llvm::AMDGPULibFuncBase::I64</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8ad0af55ef4d18b5452d50afa947f2f150">llvm::AMDGPULibFuncBase::I8</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a2d2bd20792beb08e2871525ff0bd61bd">llvm::AMDGPULibFuncBase::IMG1D</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8aa4a0749682012c0c912a6c67faac089f">llvm::AMDGPULibFuncBase::IMG1DA</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8acdc53f4dbf399c54a795dcd836b085b4">llvm::AMDGPULibFuncBase::IMG1DB</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a678e88a9aa9bd4cecb5a9a75f11e0b2a">llvm::AMDGPULibFuncBase::IMG2D</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8acbd1cf99158a98160aeba7a1e350ed80">llvm::AMDGPULibFuncBase::IMG2DA</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8ad6ca04175915d03dee3f3d3d2669dfd7">llvm::AMDGPULibFuncBase::IMG3D</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8aea0f57e5792d27177089744d2d67949c">llvm::AMDGPULibFuncBase::SAMPLER</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a76424308db519548eaeda3655a288bc4">llvm::AMDGPULibFuncBase::U16</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a3e402cd027c568fa43f4b554c0b348b6">llvm::AMDGPULibFuncBase::U32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a8c6c6342eca81ee6609a590cdc4fcad6">llvm::AMDGPULibFuncBase::U64</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8ae8baa7f9c7af35b4306f6d225214404e">llvm::AMDGPULibFuncBase::U8</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpulibfunc-cpp-/itaniummangler/#a015004ddb6e6b4aa985ffe6d5663ff83">anonymous{AMDGPULibFunc.cpp}::ItaniumMangler::operator()</a>.</p>

</div>
</div>

### parseNamePrefix() {#a56ec8af379a8cf1ff76e2171f0bbbbb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPULibFunc::ENamePrefix parseNamePrefix (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; mangledName)</td>
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



<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp">AMDGPULibFunc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a5f1a1a785d3bea7522fda8651035c2f6ae221e1fe973e968bf19ac90f0cafa3a8">llvm::AMDGPULibFuncBase::HALF</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a5f1a1a785d3bea7522fda8651035c2f6a1df3c3e4573abf56929068a57e3f4963">llvm::AMDGPULibFuncBase::NATIVE</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a5f1a1a785d3bea7522fda8651035c2f6a4e02cec40ee27126cc5262e46bd59e03">llvm::AMDGPULibFuncBase::NOPFX</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpumangledlibfunc/#a753bb73906fd815420f857b61252aaad">llvm::AMDGPUMangledLibFunc::parseFuncName</a>.</p>

</div>
</div>

### parseVecSize() {#ac7b4b404af5f382847f4d289c5579a39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int parseVecSize (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; mangledName)</td>
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



<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp">AMDGPULibFunc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-amdgpulibfunc-cpp-/itaniumparamparser/#aa21569cfdba76deadeb40added273001">anonymous{AMDGPULibFunc.cpp}::ItaniumParamParser::parseItaniumParam</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### EnableOCLManglingMismatchWA {#a19a18bb15d7ea5107103d673df93abc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableOCLManglingMismatchWA("amdgpu-enable-ocl-mangling-mismatch-workaround", cl::init(true), cl::ReallyHidden, cl::desc("Enable the workaround for OCL name mangling mismatch."))</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp">AMDGPULibFunc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpulibfunc-cpp-/itaniummangler/#a015004ddb6e6b4aa985ffe6d5663ff83">anonymous{AMDGPULibFunc.cpp}::ItaniumMangler::operator()</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
