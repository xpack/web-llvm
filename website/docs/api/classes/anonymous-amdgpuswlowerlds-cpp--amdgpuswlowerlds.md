---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AMDGPUSwLowerLDS` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8aa3340974246e4e5e458129e1ecccd2">AMDGPUSwLowerLDS</a> (Module &amp;Mod, const AMDGPUTargetMachine &amp;TM, DomTreeCallback Callback)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0633351128ad7c6f0e5bf0522edeef79">run</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac17b99a95c0b634b1c5de85e77b42a7a">getUsesOfLDSByNonKernels</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acddb0d15dc6d53316188968e5acbefc7">getNonKernelsWithLDSArguments</a> (const CallGraph &amp;CG)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ca82cda5ae3b31efcb01ef3f9c1b68b">getOrderedIndirectLDSAccessingKernels</a> (SetVector&lt; Function * &gt; &amp;Kernels)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd6d1c196150a5d9b4e914f12ec91822">getOrderedNonKernelAllLDSGlobals</a> (SetVector&lt; GlobalVariable * &gt; &amp;Variables)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a531ccf4e0c3fa8eba4a36bd8ebaad93d">buildSwLDSGlobal</a> (Function *Func)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa77b090b37b4ec17f23bff77ba62ed47">buildSwDynLDSGlobal</a> (Function *Func)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bc472aa7f200453c2fb1d5fbc404b66">populateSwMetadataGlobal</a> (Function *Func)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27414aac7f6b0da5342d78c77c7d6135">populateSwLDSAttributeAndMetadata</a> (Function *Func)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb89eef3b84df5ec144f08fd0eb068a5">populateLDSToReplacementIndicesMap</a> (Function *Func)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8772f4b8c894d7ce9c53cb543a5e49b9">getLDSMemoryInstructions</a> (Function *Func, SetVector&lt; Instruction * &gt; &amp;LDSInstructions)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a547d3856bc525978c9c94694b2f8cb20">replaceKernelLDSAccesses</a> (Function *Func)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e2a2220c5be86abe862aacbcf5030f8">getTranslatedGlobalMemoryGEPOfLDSPointer</a> (Value *LoadMallocPtr, Value *LDSPtr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a132e2ed28fb57bfad40af5505d2db16a">translateLDSMemoryOperationsToGlobalMemory</a> (Function *Func, Value *LoadMallocPtr, SetVector&lt; Instruction * &gt; &amp;LDSInstructions)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a4ed9d0b5d054ee811d2d8fecb35626">poisonRedzones</a> (Function *Func, Value *MallocPtr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f68fd99d1f5c6c8326be57c2963306d">lowerKernelLDSAccesses</a> (Function *Func, DomTreeUpdater &amp;DTU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c3a71194fc12f9298575a42187928bd">buildNonKernelLDSOffsetTable</a> (NonKernelLDSParameters &amp;NKLDSParams)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae277c85704c17a21f772da0aee54fbaa">buildNonKernelLDSBaseTable</a> (NonKernelLDSParameters &amp;NKLDSParams)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d9ad0ef3d9122df6d6b4007c519c61e">getAddressesOfVariablesInKernel</a> (Function *Func, SetVector&lt; GlobalVariable * &gt; &amp;Variables)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11f3804d12832cad99941719e39a960d">lowerNonKernelLDSAccesses</a> (Function *Func, SetVector&lt; GlobalVariable * &gt; &amp;LDSGlobals, NonKernelLDSParameters &amp;NKLDSParams)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7706251a7f258b126499e2f50f9348b5">updateMallocSizeForDynamicLDS</a> (Function *Func, Value **CurrMallocSize, Value *HiddenDynLDSSize, SetVector&lt; GlobalVariable * &gt; &amp;DynamicLDSGlobals)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5f0b958dc382d16d63163627b998f47">initAsanInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2f18ce79c524408e673072fd40caf33">M</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine">AMDGPUTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e296d0e87f7ce928c11a9d2657328ed">AMDGPUTM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fd58cd7c2fb2865c7fdfeff41bf3fe1">IRB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuswlowerlds-cpp-/#a3e58f858b039f822327db7a3547656a5">DomTreeCallback</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a981784bf53e5f45088ac40e015633e">DTCallback</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-amdgpuswlowerlds-cpp-/functionsandldsaccess">FunctionsAndLDSAccess</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fe612d76dbd7febe7231f0e0d23dbd1">FuncLDSAccessInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-amdgpuswlowerlds-cpp-/asaninstrumentinfo">AsanInstrumentInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa73644dd1c91188c3c76c71cf9e8103">AsanInfo</a></td>
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


<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AMDGPUSwLowerLDS() {#a8aa3340974246e4e5e458129e1ecccd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::AMDGPUSwLowerLDS (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; Mod, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine">AMDGPUTargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuswlowerlds-cpp-/#a3e58f858b039f822327db7a3547656a5">DomTreeCallback</a> Callback)</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### buildNonKernelLDSBaseTable() {#ae277c85704c17a21f772da0aee54fbaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::buildNonKernelLDSBaseTable (<a href="/web-llvm/docs/api/structs/anonymous-amdgpuswlowerlds-cpp-/nonkernelldsparameters">NonKernelLDSParameters</a> &amp; NKLDSParams)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantarray/#a0900dacdc7ad8e3ea0cc92993c7fd422">llvm::ConstantArray::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae4d4490a35a575d97166684fb15f8662">llvm::ConstantExpr::getGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a913a5d4b2cddde762446bd494e81a3f2">llvm::GlobalValue::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1abf4559ef958a13c33f6ec7ed13fd44e5">llvm::AMDGPUAS::GLOBAL_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23f9ec4bb2576ca8738f3edc9c4f5cdf">llvm::Int32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuswlowerlds-cpp-/nonkernelldsparameters/#a02bddaaa7cb46259bb0eab1813d5b5a4">anonymous{AMDGPUSwLowerLDS.cpp}::NonKernelLDSParameters::LDSBaseTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a>, <a href="/web-llvm/docs/api/structs/llvm/globalvalue/sanitizermetadata/#af14cbae5c1ca7ff03eaa9c66d41e0940">llvm::GlobalValue::SanitizerMetadata::NoAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">llvm::GlobalValue::NotThreadLocal</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuswlowerlds-cpp-/nonkernelldsparameters/#acd8c439e2b7eb700f7b296f670f82957">anonymous{AMDGPUSwLowerLDS.cpp}::NonKernelLDSParameters::OrderedKernels</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#add48ed79a5cd63c7165f3f4da102b9fd">llvm::GlobalValue::setSanitizerMetadata</a>.</p>


<p>Referenced by <a href="#a0633351128ad7c6f0e5bf0522edeef79">run</a>.</p>

</div>
</div>

### buildNonKernelLDSOffsetTable() {#a3c3a71194fc12f9298575a42187928bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::buildNonKernelLDSOffsetTable (<a href="/web-llvm/docs/api/structs/anonymous-amdgpuswlowerlds-cpp-/nonkernelldsparameters">NonKernelLDSParameters</a> &amp; NKLDSParams)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantarray/#a0900dacdc7ad8e3ea0cc92993c7fd422">llvm::ConstantArray::get</a>, <a href="#a8d9ad0ef3d9122df6d6b4007c519c61e">getAddressesOfVariablesInKernel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1abf4559ef958a13c33f6ec7ed13fd44e5">llvm::AMDGPUAS::GLOBAL_ADDRESS</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuswlowerlds-cpp-/nonkernelldsparameters/#acd9e92a4d6d738b78afed6c7aa17a8e7">anonymous{AMDGPUSwLowerLDS.cpp}::NonKernelLDSParameters::LDSOffsetTable</a>, <a href="/web-llvm/docs/api/structs/llvm/globalvalue/sanitizermetadata/#af14cbae5c1ca7ff03eaa9c66d41e0940">llvm::GlobalValue::SanitizerMetadata::NoAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">llvm::GlobalValue::NotThreadLocal</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuswlowerlds-cpp-/nonkernelldsparameters/#acd8c439e2b7eb700f7b296f670f82957">anonymous{AMDGPUSwLowerLDS.cpp}::NonKernelLDSParameters::OrderedKernels</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuswlowerlds-cpp-/nonkernelldsparameters/#ad8b4729f88ab556396f1f9ba61a93475">anonymous{AMDGPUSwLowerLDS.cpp}::NonKernelLDSParameters::OrdereLDSGlobals</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#add48ed79a5cd63c7165f3f4da102b9fd">llvm::GlobalValue::setSanitizerMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a>.</p>


<p>Referenced by <a href="#a0633351128ad7c6f0e5bf0522edeef79">run</a>.</p>

</div>
</div>

### buildSwDynLDSGlobal() {#aa77b090b37b4ec17f23bff77ba62ed47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::buildSwDynLDSGlobal (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuswlowerlds-cpp-/#a58e10a8e8f7c27c724cd88a29f2739e5">anonymous{AMDGPUSwLowerLDS.cpp}::markUsedByKernel</a>, <a href="/web-llvm/docs/api/structs/llvm/globalvalue/sanitizermetadata/#af14cbae5c1ca7ff03eaa9c66d41e0940">llvm::GlobalValue::SanitizerMetadata::NoAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">llvm::GlobalValue::NotThreadLocal</a>.</p>


<p>Referenced by <a href="#a0633351128ad7c6f0e5bf0522edeef79">run</a>.</p>

</div>
</div>

### buildSwLDSGlobal() {#a531ccf4e0c3fa8eba4a36bd8ebaad93d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::buildSwLDSGlobal (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a>, <a href="/web-llvm/docs/api/structs/llvm/globalvalue/sanitizermetadata/#af14cbae5c1ca7ff03eaa9c66d41e0940">llvm::GlobalValue::SanitizerMetadata::NoAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">llvm::GlobalValue::NotThreadLocal</a>.</p>


<p>Referenced by <a href="#a0633351128ad7c6f0e5bf0522edeef79">run</a>.</p>

</div>
</div>

### getAddressesOfVariablesInKernel() {#a8d9ad0ef3d9122df6d6b4007c519c61e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::getAddressesOfVariablesInKernel (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Func, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt; &amp; Variables)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantarray/#a0900dacdc7ad8e3ea0cc92993c7fd422">llvm::ConstantArray::get</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae4d4490a35a575d97166684fb15f8662">llvm::ConstantExpr::getGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1abf4559ef958a13c33f6ec7ed13fd44e5">llvm::AMDGPUAS::GLOBAL_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23f9ec4bb2576ca8738f3edc9c4f5cdf">llvm::Int32Ty</a> and <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a>.</p>


<p>Referenced by <a href="#a3c3a71194fc12f9298575a42187928bd">buildNonKernelLDSOffsetTable</a>.</p>

</div>
</div>

### getLDSMemoryInstructions() {#a8772f4b8c894d7ce9c53cb543a5e49b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::getLDSMemoryInstructions (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Func, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; LDSInstructions)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a>.</p>


<p>Referenced by <a href="#a2f68fd99d1f5c6c8326be57c2963306d">lowerKernelLDSAccesses</a> and <a href="#a11f3804d12832cad99941719e39a960d">lowerNonKernelLDSAccesses</a>.</p>

</div>
</div>

### getNonKernelsWithLDSArguments() {#acddb0d15dc6d53316188968e5acbefc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::getNonKernelsWithLDSArguments (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callgraph">CallGraph</a> &amp; CG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a8bf193a781a92cae52d7f9216d0824f8">llvm::Function::arg_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a8300ac1ef141b8a7c63c13fa9369d976">llvm::Function::arg_end</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphnode/#aab57958df49938baa45ec4fb890cebac">llvm::CallGraphNode::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5ab2d0b0f0b8ceec3b907184e7567197">llvm::Type::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a32e606ac4c88f71f14212e42b808e7f4">llvm::GlobalValue::isDeclaration</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad45f913090dbe9b3ec236ae18d3560e4">llvm::AMDGPU::isKernelLDS</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a>.</p>


<p>Referenced by <a href="#a0633351128ad7c6f0e5bf0522edeef79">run</a>.</p>

</div>
</div>

### getOrderedIndirectLDSAccessingKernels() {#a0ca82cda5ae3b31efcb01ef3f9c1b68b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetVector&lt; Function * &gt; anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::getOrderedIndirectLDSAccessingKernels (<a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; &amp; Kernels)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuswlowerlds-cpp-/#aa98aa1dd6024159d0c7ffea33c2dfbb2">anonymous{AMDGPUSwLowerLDS.cpp}::sortByName</a>.</p>


<p>Referenced by <a href="#a0633351128ad7c6f0e5bf0522edeef79">run</a>.</p>

</div>
</div>

### getOrderedNonKernelAllLDSGlobals() {#afd6d1c196150a5d9b4e914f12ec91822}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetVector&lt; GlobalVariable * &gt; anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::getOrderedNonKernelAllLDSGlobals (<a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt; &amp; Variables)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/setvector/#ad0bf95396cec46a41371341460d14a1c">llvm::SetVector&lt; T, Vector, Set, N &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a889cc0df630d4b01e12d359517e26670">llvm::SetVector&lt; T, Vector, Set, N &gt;::end</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuswlowerlds-cpp-/#aa98aa1dd6024159d0c7ffea33c2dfbb2">anonymous{AMDGPUSwLowerLDS.cpp}::sortByName</a>.</p>


<p>Referenced by <a href="#a0633351128ad7c6f0e5bf0522edeef79">run</a>.</p>

</div>
</div>

### getTranslatedGlobalMemoryGEPOfLDSPointer() {#a9e2a2220c5be86abe862aacbcf5030f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::getTranslatedGlobalMemoryGEPOfLDSPointer (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LoadMallocPtr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LDSPtr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>.</p>


<p>Referenced by <a href="#a132e2ed28fb57bfad40af5505d2db16a">translateLDSMemoryOperationsToGlobalMemory</a>.</p>

</div>
</div>

### getUsesOfLDSByNonKernels() {#ac17b99a95c0b634b1c5de85e77b42a7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::getUsesOfLDSByNonKernels ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad45f913090dbe9b3ec236ae18d3560e4">llvm::AMDGPU::isKernelLDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a9a6f055381f5a946e37ab4d9e4a221d8">llvm::AMDGPU::isLDSVariableToLower</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>


<p>Referenced by <a href="#a0633351128ad7c6f0e5bf0522edeef79">run</a>.</p>

</div>
</div>

### initAsanInfo() {#ab5f0b958dc382d16d63163627b998f47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::initAsanInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aef7ea18a6637c39986a0da770872af6d">llvm::getAddressSanitizerParams</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1abf4559ef958a13c33f6ec7ed13fd44e5">llvm::AMDGPUAS::GLOBAL_ADDRESS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a0633351128ad7c6f0e5bf0522edeef79">run</a>.</p>

</div>
</div>

### lowerKernelLDSAccesses() {#a2f68fd99d1f5c6c8326be57c2963306d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::lowerKernelLDSAccesses (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Func, <a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a> &amp; DTU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a30475b065bebd7bc81d1112d9067d772abd2438b14a6a1a27fae653284aaa3cb4">llvm::AMDGPU::AMDHSA_COV5</a>, <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a363d442ff7f9a13eafaee275aad9f54c">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyUpdates</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a9c50882381abd28ec385bec769b8928b">llvm::SetVector&lt; T, Vector, Set, N &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5f9a0bcc6ecfeef7109258c6a8012978">llvm::AMDGPU::getAMDHSACodeObjectVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="#a8772f4b8c894d7ce9c53cb543a5e49b9">getLDSMemoryInstructions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuswlowerlds-cpp-/#ad29b8e5faa8d8977329b9bbc73867612">anonymous{AMDGPUSwLowerLDS.cpp}::getOrCreateDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1abf4559ef958a13c33f6ec7ed13fd44e5">llvm::AMDGPUAS::GLOBAL_ADDRESS</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a9aeeca2833810f01b20545a46fe22503">llvm::DominatorTreeBase&lt; BasicBlock, false &gt;::Insert</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23f9ec4bb2576ca8738f3edc9c4f5cdf">llvm::Int32Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a0a4ed9d0b5d054ee811d2d8fecb35626">poisonRedzones</a>, <a href="#a547d3856bc525978c9c94694b2f8cb20">replaceKernelLDSAccesses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a>, <a href="#a132e2ed28fb57bfad40af5505d2db16a">translateLDSMemoryOperationsToGlobalMemory</a> and <a href="#a7706251a7f258b126499e2f50f9348b5">updateMallocSizeForDynamicLDS</a>.</p>


<p>Referenced by <a href="#a0633351128ad7c6f0e5bf0522edeef79">run</a>.</p>

</div>
</div>

### lowerNonKernelLDSAccesses() {#a11f3804d12832cad99941719e39a960d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::lowerNonKernelLDSAccesses (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Func, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt; &amp; LDSGlobals, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuswlowerlds-cpp-/nonkernelldsparameters">NonKernelLDSParameters</a> &amp; NKLDSParams)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a8772f4b8c894d7ce9c53cb543a5e49b9">getLDSMemoryInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1abf4559ef958a13c33f6ec7ed13fd44e5">llvm::AMDGPUAS::GLOBAL_ADDRESS</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuswlowerlds-cpp-/nonkernelldsparameters/#a02bddaaa7cb46259bb0eab1813d5b5a4">anonymous{AMDGPUSwLowerLDS.cpp}::NonKernelLDSParameters::LDSBaseTable</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuswlowerlds-cpp-/nonkernelldsparameters/#acd9e92a4d6d738b78afed6c7aa17a8e7">anonymous{AMDGPUSwLowerLDS.cpp}::NonKernelLDSParameters::LDSOffsetTable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuswlowerlds-cpp-/nonkernelldsparameters/#ad8b4729f88ab556396f1f9ba61a93475">anonymous{AMDGPUSwLowerLDS.cpp}::NonKernelLDSParameters::OrdereLDSGlobals</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuswlowerlds-cpp-/#a79c3418f6abda9608f981c915c80e682">anonymous{AMDGPUSwLowerLDS.cpp}::replacesUsesOfGlobalInFunction</a> and <a href="#a132e2ed28fb57bfad40af5505d2db16a">translateLDSMemoryOperationsToGlobalMemory</a>.</p>


<p>Referenced by <a href="#a0633351128ad7c6f0e5bf0522edeef79">run</a>.</p>

</div>
</div>

### poisonRedzones() {#a0a4ed9d0b5d054ee811d2d8fecb35626}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::poisonRedzones (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Func, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * MallocPtr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>.</p>


<p>Referenced by <a href="#a2f68fd99d1f5c6c8326be57c2963306d">lowerKernelLDSAccesses</a>.</p>

</div>
</div>

### populateLDSToReplacementIndicesMap() {#acb89eef3b84df5ec144f08fd0eb068a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::populateLDSToReplacementIndicesMap (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>


<p>Referenced by <a href="#a0633351128ad7c6f0e5bf0522edeef79">run</a>.</p>

</div>
</div>

### populateSwLDSAttributeAndMetadata() {#a27414aac7f6b0da5342d78c77c7d6135}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::populateSwLDSAttributeAndMetadata (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuswlowerlds-cpp-/#a9d0d7af16954283c593bf787cb1d4875">anonymous{AMDGPUSwLowerLDS.cpp}::addLDSSizeAttribute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuswlowerlds-cpp-/#afd9e63b8a22ad3b90efbd3e5bd8b1b93">anonymous{AMDGPUSwLowerLDS.cpp}::recordLDSAbsoluteAddress</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="#a0633351128ad7c6f0e5bf0522edeef79">run</a>.</p>

</div>
</div>

### populateSwMetadataGlobal() {#a7bc472aa7f200453c2fb1d5fbc404b66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::populateSwMetadataGlobal (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a82648246c07eb8a33f628eea28cb988c">llvm::StructType::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/constantstruct/#a54fcfa620deb80373f489ba2fdad7643">llvm::ConstantStruct::get</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aaf7c3ea495e589d05c4e89f7c9dcc897">llvm::AMDGPU::getAlign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#afe65ef65468a7a89e95db0c4b32456f3">llvm::AMDGPU::getRedzoneSizeForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1abf4559ef958a13c33f6ec7ed13fd44e5">llvm::AMDGPUAS::GLOBAL_ADDRESS</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23f9ec4bb2576ca8738f3edc9c4f5cdf">llvm::Int32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4cacf18e8e9ecebd3f912ae0ad4e3817">llvm::AMDGPU::isDynamicLDS</a>, <a href="/web-llvm/docs/api/structs/llvm/globalvalue/sanitizermetadata/#af14cbae5c1ca7ff03eaa9c66d41e0940">llvm::GlobalValue::SanitizerMetadata::NoAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">llvm::GlobalValue::NotThreadLocal</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream/#a9c2cac84e46d3e744aeca03dd3d557d1">llvm::raw_svector_ostream::str</a>.</p>


<p>Referenced by <a href="#a0633351128ad7c6f0e5bf0522edeef79">run</a>.</p>

</div>
</div>

### replaceKernelLDSAccesses() {#a547d3856bc525978c9c94694b2f8cb20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::replaceKernelLDSAccesses (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae4d4490a35a575d97166684fb15f8662">llvm::ConstantExpr::getGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23f9ec4bb2576ca8738f3edc9c4f5cdf">llvm::Int32Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuswlowerlds-cpp-/#a79c3418f6abda9608f981c915c80e682">anonymous{AMDGPUSwLowerLDS.cpp}::replacesUsesOfGlobalInFunction</a>.</p>


<p>Referenced by <a href="#a2f68fd99d1f5c6c8326be57c2963306d">lowerKernelLDSAccesses</a>.</p>

</div>
</div>

### run() {#a0633351128ad7c6f0e5bf0522edeef79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuswlowerlds-cpp-/#ac7737519d77e202d9e1fc55521fbb430">anonymous{AMDGPUSwLowerLDS.cpp}::AsanInstrumentLDS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad7dc7318244359268414719e0959346e">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::begin</a>, <a href="#ae277c85704c17a21f772da0aee54fbaa">buildNonKernelLDSBaseTable</a>, <a href="#a3c3a71194fc12f9298575a42187928bd">buildNonKernelLDSOffsetTable</a>, <a href="#aa77b090b37b4ec17f23bff77ba62ed47">buildSwDynLDSGlobal</a>, <a href="#a531ccf4e0c3fa8eba4a36bd8ebaad93d">buildSwLDSGlobal</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/ldsusesinfoty/#a742870ecab7687d09d889034c6695ee8">llvm::AMDGPU::LDSUsesInfoTy::direct_access</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aac00cb920a9d9d61a45759a8e4314142">llvm::AMDGPU::eliminateConstantExprUsesOfLDSFromAllInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a8cd802dcaed35e1f28ea3cbe4af4eff5">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4988f54643e5c2613c9a0682ccccccbf">llvm::AMDGPU::getInterestingMemoryOperands</a>, <a href="#acddb0d15dc6d53316188968e5acbefc7">getNonKernelsWithLDSArguments</a>, <a href="#a0ca82cda5ae3b31efcb01ef3f9c1b68b">getOrderedIndirectLDSAccessingKernels</a>, <a href="#afd6d1c196150a5d9b4e914f12ec91822">getOrderedNonKernelAllLDSGlobals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8c1ff7e5e775cdba70261e34245db9e5">llvm::AMDGPU::getTransitiveUsesOfLDS</a>, <a href="#ac17b99a95c0b634b1c5de85e77b42a7a">getUsesOfLDSByNonKernels</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/ldsusesinfoty/#abbbf7703905ba9107c6b20bf87e4095a">llvm::AMDGPU::LDSUsesInfoTy::indirect_access</a>, <a href="#ab5f0b958dc382d16d63163627b998f47">initAsanInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af0b80ad51fe1f4372499e354b6f2e402">llvm::AMDGPU::instrumentAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4cacf18e8e9ecebd3f912ae0ad4e3817">llvm::AMDGPU::isDynamicLDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad45f913090dbe9b3ec236ae18d3560e4">llvm::AMDGPU::isKernelLDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a9a6f055381f5a946e37ab4d9e4a221d8">llvm::AMDGPU::isLDSVariableToLower</a>, <a href="#a2f68fd99d1f5c6c8326be57c2963306d">lowerKernelLDSAccesses</a>, <a href="#a11f3804d12832cad99941719e39a960d">lowerNonKernelLDSAccesses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuswlowerlds-cpp-/nonkernelldsparameters/#acd8c439e2b7eb700f7b296f670f82957">anonymous{AMDGPUSwLowerLDS.cpp}::NonKernelLDSParameters::OrderedKernels</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuswlowerlds-cpp-/nonkernelldsparameters/#ad8b4729f88ab556396f1f9ba61a93475">anonymous{AMDGPUSwLowerLDS.cpp}::NonKernelLDSParameters::OrdereLDSGlobals</a>, <a href="#acb89eef3b84df5ec144f08fd0eb068a5">populateLDSToReplacementIndicesMap</a>, <a href="#a27414aac7f6b0da5342d78c77c7d6135">populateSwLDSAttributeAndMetadata</a>, <a href="#a7bc472aa7f200453c2fb1d5fbc404b66">populateSwMetadataGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a6b42b6fca05063155c689008d30a2751">llvm::AMDGPU::removeFnAttrFromReachable</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuswlowerlds-cpp-/#af2953d3d94073adaadf0c9f88ab8fea9">anonymous{AMDGPUSwLowerLDS.cpp}::reorderStaticDynamicIndirectLDSSet</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuswlowerlds-cpp-/#aa98aa1dd6024159d0c7ffea33c2dfbb2">anonymous{AMDGPUSwLowerLDS.cpp}::sortByName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerldslegacy/#acfe402ed12ef3aa3f9b6b75a60baeb33">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDSLegacy::runOnModule</a>.</p>

</div>
</div>

### translateLDSMemoryOperationsToGlobalMemory() {#a132e2ed28fb57bfad40af5505d2db16a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::translateLDSMemoryOperationsToGlobalMemory (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Func, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LoadMallocPtr, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; LDSInstructions)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a9e2a2220c5be86abe862aacbcf5030f8">getTranslatedGlobalMemoryGEPOfLDSPointer</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a6ae88dc44b078c80ce3a25401fd4b05b">llvm::LoadInst::setAtomic</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#aff28bd42ac76fc3e1c0e4db7f9e06f2d">llvm::StoreInst::setAtomic</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#aad0a6acef46d026f2137af84d656decc">llvm::AtomicCmpXchgInst::setVolatile</a> and <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a361ca9304555f6c2e0dd2b3188439b33">llvm::AtomicRMWInst::setVolatile</a>.</p>


<p>Referenced by <a href="#a2f68fd99d1f5c6c8326be57c2963306d">lowerKernelLDSAccesses</a> and <a href="#a11f3804d12832cad99941719e39a960d">lowerNonKernelLDSAccesses</a>.</p>

</div>
</div>

### updateMallocSizeForDynamicLDS() {#a7706251a7f258b126499e2f50f9348b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::updateMallocSizeForDynamicLDS (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Func, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> ** CurrMallocSize, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * HiddenDynLDSSize, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt; &amp; DynamicLDSGlobals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a956dcf23a0d1926a5cbd98eebf191888">llvm::GlobalObject::getAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a23f9ec4bb2576ca8738f3edc9c4f5cdf">llvm::Int32Ty</a>.</p>


<p>Referenced by <a href="#a2f68fd99d1f5c6c8326be57c2963306d">lowerKernelLDSAccesses</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AMDGPUTM {#a1e296d0e87f7ce928c11a9d2657328ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AMDGPUTargetMachine&amp; anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::AMDGPUTM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>

</div>
</div>

### AsanInfo {#afa73644dd1c91188c3c76c71cf9e8103}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsanInstrumentInfo anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::AsanInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>

</div>
</div>

### DTCallback {#a4a981784bf53e5f45088ac40e015633e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeCallback anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::DTCallback</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>

</div>
</div>

### FuncLDSAccessInfo {#a0fe612d76dbd7febe7231f0e0d23dbd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionsAndLDSAccess anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::FuncLDSAccessInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>

</div>
</div>

### IRB {#a2fd58cd7c2fb2865c7fdfeff41bf3fe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRBuilder anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::IRB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>

</div>
</div>

### M {#ae2f18ce79c524408e673072fd40caf33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module&amp; anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuswlowerlds-cpp">AMDGPUSwLowerLDS.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
