---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/spirvcalllowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SPIRVCallLowering` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::SPIRVCallLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-h">Target/SPIRV/SPIRVCallLowering.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/calllowering">CallLowering</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc3a753ecc18a9e82d48a0f28bae8860">SPIRVCallLowering</a> (const SPIRVTargetLowering &amp;TLI, SPIRVGlobalRegistry *GR)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8dc1642db124c4da34fbec06040a0c4">lowerReturn</a> (MachineIRBuilder &amp;MIRBuiler, const Value *Val, ArrayRef&lt; Register &gt; VRegs, FunctionLoweringInfo &amp;FLI, Register SwiftErrorVReg) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower outgoing return values, described by <span class="doxyComputerOutput">Val</span>, into the specified virtual registers <span class="doxyComputerOutput">VRegs</span>. <a href="#ac8dc1642db124c4da34fbec06040a0c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4911ff1c4fabd84b05d4529da80021e">lowerFormalArguments</a> (MachineIRBuilder &amp;MIRBuilder, const Function &amp;F, ArrayRef&lt; ArrayRef&lt; Register &gt; &gt; VRegs, FunctionLoweringInfo &amp;FLI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower the incoming (formal) arguments, described by <span class="doxyComputerOutput">VRegs</span>, for GlobalISel. <a href="#af4911ff1c4fabd84b05d4529da80021e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab055c9ed89ccbcf823971615232941d1">lowerCall</a> (MachineIRBuilder &amp;MIRBuilder, CallLoweringInfo &amp;Info) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower the given call instruction, including argument and return value marshalling. <a href="#ab055c9ed89ccbcf823971615232941d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eaf16719722045794ff00231fe73734">produceIndirectPtrTypes</a> (MachineIRBuilder &amp;MIRBuilder) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry">SPIRVGlobalRegistry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b590fa58a0ef21e2b8969b44966959b">GR</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; SPIRVIndirectCall &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2353fa1150d063aa8b7c29fa7aa4b240">IndirectCalls</a></td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-h">SPIRVCallLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SPIRVCallLowering() {#adc3a753ecc18a9e82d48a0f28bae8860}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVCallLowering::SPIRVCallLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering">SPIRVTargetLowering</a> &amp; TLI, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry">SPIRVGlobalRegistry</a> * GR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-h">SPIRVCallLowering.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp">SPIRVCallLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/calllowering/#aceb7a26daf1242d77d983191579009db">llvm::CallLowering::CallLowering</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### lowerCall() {#ab055c9ed89ccbcf823971615232941d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SPIRVCallLowering::lowerCall (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/structs/llvm/calllowering/callloweringinfo">CallLoweringInfo</a> &amp; Info)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This hook must be implemented to lower the given call instruction, including argument and return value marshalling.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the lowering succeeded, false otherwise.</p></dd>
</dl>


<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-h">SPIRVCallLowering.h</a>, definition at line 510 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp">SPIRVCallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a49e6c89ce42a55a93ddf38d21bbd198e">llvm::Function::args</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad5732a98562641ab5536b451ec72c5d4">llvm::MachineIRBuilder::buildTrap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#aa238cd5a6fee2e66e4b5bd3fc2040c19">llvm::MachineInstrBuilder::constrainAllUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c02a62be344861d8a7598e08d1021b6">llvm::createVirtualRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a5c77792a06583e0fe7a0379ad94a2809">llvm::MachineRegisterInfo::createVirtualRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/typedpointertype/#ad0b317acb44e242226165a34d550702d">llvm::TypedPointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a81e8ccd82f750cdfb7488a3197401f7e">llvm::MachineFunction::getBlockNumbered</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aeb6d0a9254bc3183046873436fc7c12e">llvm::MachineIRBuilder::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4c319db4fe05c27cfe55bd133a87414d">llvm::Function::getFnAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad7322f56c0659b8dc8e55567767b74d6">llvm::MachineIRBuilder::getMRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d026110da5d125d1cc738acc2de3761">llvm::getOclOrSpirvBuiltinDemangledName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#a3d3f9a7f2fef13c8261fa2d3175a4cca">getOriginalFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a35384c47e5ca9690216b1aa8fed5a8c9">llvm::MachineIRBuilder::getTII</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#acfcd22eb38dbfe1acbf138754297437a">llvm::DataLayout::getTypeStoreSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024ca9c73278820c265864adec96a189ba744">llvm::IndirectCall</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a32e606ac4c88f71f14212e42b808e7f4">llvm::GlobalValue::isDeclaration</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed8d0406be2132424f2c8e74decde75e">llvm::isUntypedPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#adf4d22686e85732b2fef71e3c45531c6">llvm::Attribute::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a7407603b3efcdc8d4c2b76697be34528">llvm::Register::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ad96fee81c3174ef427bf779d73fb1ef2">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#aa4175e495404e2fa9c8236262d7aae09">llvm::SPIRV::lowerBuiltin</a>, <a href="#af4911ff1c4fabd84b05d4529da80021e">lowerFormalArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7ff0361855acbbe71b15b8dc6003fbc5">llvm::LLT::pointer</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#acd5c75a12ec8c12c35de46c60d18c699">llvm::MachineIRBuilder::setMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af0d9669bbadd4d5e1d75c3c833c8d5ac">llvm::MachineIRBuilder::setMF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d3f9bac9bdd3f5fc36a5f5e13480d4a">llvm::setRegClassType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvutils-h/#a2803bd4e0ee3046106eef7903037ba0d">SPIRV_BACKEND_SERVICE_FUN_NAME</a>.</p>

</div>
</div>

### lowerFormalArguments() {#af4911ff1c4fabd84b05d4529da80021e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SPIRVCallLowering::lowerFormalArguments (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &gt; VRegs, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; FLI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This hook must be implemented to lower the incoming (formal) arguments, described by <span class="doxyComputerOutput">VRegs</span>, for GlobalISel.</p>


<p>Each argument must end up in the related virtual registers described by <span class="doxyComputerOutput">VRegs</span>. In other words, the first argument should end up in <span class="doxyComputerOutput">VRegs</span>[0], the second in <span class="doxyComputerOutput">VRegs</span>[1], and so on. For each argument, there will be one register for each non-aggregate type, as returned by <span class="doxyComputerOutput">computeValueLLTs</span>. <span class="doxyComputerOutput">MIRBuilder</span> is set to the proper insertion for the argument lowering. <span class="doxyComputerOutput">FLI</span> is required for sret demotion.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the lowering succeeded, false otherwise.</p></dd>
</dl>


<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-h">SPIRVCallLowering.h</a>, definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp">SPIRVCallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7695a0e4d476e4df011486af1bb63e8">llvm::addStringImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a686587ed0b5b8437aa621630cf56d147">llvm::buildOpDecorate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a01f1b2c1fbaec02e4f0d0af133830ca6">llvm::buildOpName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#ad57fd622877d2a50e1a312be6b4a409d">fixFunctionTypeIfPtrArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/typedpointertype/#ad0b317acb44e242226165a34d550702d">llvm::TypedPointerType::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#ab5e88a19352e7dce1b0115f5e6b37b47">getArgSPIRVType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#a0652fb126dc7bb267410275a2a0864d4">getConstInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#a2820d4a68a586ccef2011a7eaa431aad">getExecutionModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#a52100ca4ffaf0494489db89087b1f48a">getFunctionControl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#af66ee86d05581a75015e5b8d032c711a">getKernelArgTypeQual</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad7322f56c0659b8dc8e55567767b74d6">llvm::MachineIRBuilder::getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#a3d3f9a7f2fef13c8261fa2d3175a4cca">getOriginalFunctionType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21b1f2d0effa0506f01cb146823de6a2">llvm::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#ad65790aa94dd4678a1d339d8304e1965">llvm::FunctionType::getReturnType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9457afaedec0cec9eec46986b6e20fdb">llvm::isEntryPoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0e326091dd1d965427566c44952ca16">llvm::isPointerTyOrWrapper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed8d0406be2132424f2c8e74decde75e">llvm::isUntypedPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caf2b592edf18170e7aff4e8f3bae3360c">llvm::GlobalValue::LinkOnceODRLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a571612461ea4af620bc4c441d61579a3">llvm::MDNode::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca04ed141708c0fd16723d212502b046ae">llvm::GlobalValue::PrivateLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca9b5e79699935bf721647d44339701860">llvm::CallingConv::SPIR_KERNEL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvutils-h/#a2803bd4e0ee3046106eef7903037ba0d">SPIRV_BACKEND_SERVICE_FUN_NAME</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a79a682a8e3ef1ba361fb668ce902b6c3">llvm::toTypedPointer</a>.</p>


<p>Referenced by <a href="#ab055c9ed89ccbcf823971615232941d1">lowerCall</a>.</p>

</div>
</div>

### lowerReturn() {#ac8dc1642db124c4da34fbec06040a0c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SPIRVCallLowering::lowerReturn (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; VRegs, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; FLI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SwiftErrorVReg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This hook must be implemented to lower outgoing return values, described by <span class="doxyComputerOutput">Val</span>, into the specified virtual registers <span class="doxyComputerOutput">VRegs</span>.</p>


<p>This hook is used by GlobalISel.</p>


<p><span class="doxyComputerOutput">FLI</span> is required for sret demotion.</p>


<p><span class="doxyComputerOutput">SwiftErrorVReg</span> is non-zero if the function has a swifterror parameter that needs to be implicitly returned.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the lowering succeeds, false otherwise.</p></dd>
</dl>


<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-h">SPIRVCallLowering.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp">SPIRVCallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#aa238cd5a6fee2e66e4b5bd3fc2040c19">llvm::MachineInstrBuilder::constrainAllUses</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4c319db4fe05c27cfe55bd133a87414d">llvm::Function::getFnAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a35384c47e5ca9690216b1aa8fed5a8c9">llvm::MachineIRBuilder::getTII</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#adf4d22686e85732b2fef71e3c45531c6">llvm::Attribute::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvutils-h/#a2803bd4e0ee3046106eef7903037ba0d">SPIRV_BACKEND_SERVICE_FUN_NAME</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### produceIndirectPtrTypes() {#a4eaf16719722045794ff00231fe73734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVCallLowering::produceIndirectPtrTypes (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-h">SPIRVCallLowering.h</a>, definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp">SPIRVCallLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### GR {#a4b590fa58a0ef21e2b8969b44966959b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVGlobalRegistry* llvm::SPIRVCallLowering::GR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-h">SPIRVCallLowering.h</a>.</p>

</div>
</div>

### IndirectCalls {#a2353fa1150d063aa8b7c29fa7aa4b240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SPIRVIndirectCall&gt; llvm::SPIRVCallLowering::IndirectCalls</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-h">SPIRVCallLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp">SPIRVCallLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-h">SPIRVCallLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
