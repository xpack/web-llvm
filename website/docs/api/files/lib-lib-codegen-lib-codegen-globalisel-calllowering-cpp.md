---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `CallLowering.cpp` File

<p>This file implements some simple delegations needed for call lowering. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">llvm/CodeGen/GlobalISel/CallLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/analysis-h">llvm/CodeGen/Analysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">llvm/CodeGen/CallingConvLower.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">llvm/CodeGen/GlobalISel/MachineIRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/utils-h">llvm/CodeGen/GlobalISel/Utils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">llvm/CodeGen/MachineOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14cd25d5ba35dce0ad4aeac7514b6dd7">addFlagsUsingAttrFn</a> (ISD::ArgFlagsTy &amp;Flags, const std::function&lt; bool(Attribute::AttrKind)&gt; &amp;AttrFn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function which updates <span class="doxyComputerOutput">Flags</span> when <span class="doxyComputerOutput">AttrFn</span> returns true. <a href="#a14cd25d5ba35dce0ad4aeac7514b6dd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a627f84abfceb75ffd72119423d0147a4">mergeVectorRegsToResultRegs</a> (MachineIRBuilder &amp;B, ArrayRef&lt; Register &gt; DstRegs, ArrayRef&lt; Register &gt; SrcRegs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pack values <span class="doxyComputerOutput">SrcRegs</span> to cover the vector type result <span class="doxyComputerOutput">DstRegs</span>. <a href="#a627f84abfceb75ffd72119423d0147a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae7d70f087262ba4f7657f564ce0ca38">buildCopyFromRegs</a> (MachineIRBuilder &amp;B, ArrayRef&lt; Register &gt; OrigRegs, ArrayRef&lt; Register &gt; Regs, LLT LLTy, LLT PartLLT, const ISD::ArgFlagsTy Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a sequence of instructions to combine pieces split into register typed values to the original IR value. <a href="#aae7d70f087262ba4f7657f564ce0ca38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e9d3565509fb5cd3e136c0fa68ad5b2">buildCopyToRegs</a> (MachineIRBuilder &amp;B, ArrayRef&lt; Register &gt; DstRegs, Register SrcReg, LLT SrcTy, LLT PartTy, unsigned ExtendOp=TargetOpcode::G_ANYEXT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a sequence of instructions to expand the value in <span class="doxyComputerOutput">SrcReg</span> (of type <span class="doxyComputerOutput">SrcTy</span>) to the types in <span class="doxyComputerOutput">DstRegs</span> (of type <span class="doxyComputerOutput">PartTy</span>). <a href="#a2e9d3565509fb5cd3e136c0fa68ad5b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5b91dbd22e5c216d8f1b53a37eaac3f">extendOpFromFlags</a> (llvm::ISD::ArgFlagsTy Flags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4d564b29ec78229d8d9ab0970db529d">isCopyCompatibleType</a> (LLT SrcTy, LLT DstTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if we can use a basic COPY instruction between the two types. <a href="#ad4d564b29ec78229d8d9ab0970db529d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"call-lowering"</td>
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

<p>This file implements some simple delegations needed for call lowering.</p>

<div class="doxySectionDef">

## Functions

### addFlagsUsingAttrFn() {#a14cd25d5ba35dce0ad4aeac7514b6dd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addFlagsUsingAttrFn (<a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp; Flags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">std::function</a>&lt; bool(Attribute::AttrKind)&gt; &amp; AttrFn)</td>
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

<p>Helper function which updates <span class="doxyComputerOutput">Flags</span> when <span class="doxyComputerOutput">AttrFn</span> returns true.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp">CallLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/calllowering/#aad70901f030f4d7f74ccec2e94ac5b16">llvm::CallLowering::addArgFlagsFromAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a810bee77e0c113a1d9e61269edd71d75">llvm::CallLowering::getAttributesForArgIdx</a> and <a href="/web-llvm/docs/api/classes/llvm/calllowering/#afa9e164d73690f62a2e8f984dd5f550c">llvm::CallLowering::getAttributesForReturn</a>.</p>

</div>
</div>

### buildCopyFromRegs() {#aae7d70f087262ba4f7657f564ce0ca38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void buildCopyFromRegs (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; OrigRegs, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; Regs, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> LLTy, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> PartLLT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> Flags)</td>
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

<p>Create a sequence of instructions to combine pieces split into register typed values to the original IR value.</p>


<p><span class="doxyComputerOutput">OrigRegs</span> contains the destination value registers of type <span class="doxyComputerOutput">LLTy</span>, and <span class="doxyComputerOutput">Regs</span> contains the legalized pieces with type <span class="doxyComputerOutput">PartLLT</span>. This is used for incoming values (physregs to vregs).</p>


<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp">CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#adabd45e67a1847750a117317b5ef8f9f">llvm::LLT::changeElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a4f404daab6050b7a8e95bb247d4aefb2">llvm::LLT::changeElementType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9dda4472ee0b7ea92ab49eedf6e13d50">llvm::divideCeil</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a55089293ebaccd683a82d97170041376">llvm::ArrayRef&lt; T &gt;::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa911a7e9e51b7ed20810fc819efe6a26">llvm::LLT::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb74ac5c2f2a45c7247a785f898d4833">llvm::getGCDType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae4165ca7bcbee300d5e9c065adcc1415">llvm::LLT::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#addaa86bfa4ca26b7f366cbdd868f99bf">llvm::details::FixedOrScalableQuantity&lt; TypeSize, uint64_t &gt;::isKnownGT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a9d825f5954d7bd527aea490668c624c6">llvm::LLT::isPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600clausemergepass-cpp/#aba99928790de45fa7aa12b47fbd828ff">Merge</a>, <a href="#a627f84abfceb75ffd72119423d0147a4">mergeVectorRegsToResultRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a33da2ddf6f447892591c86d9d3771b9c">llvm::ArrayRef&lt; T &gt;::take_front</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aae26f659b722d1d053b93b5f1735f52f">llvm::SmallVectorImpl&lt; T &gt;::truncate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>.</p>

</div>
</div>

### buildCopyToRegs() {#a2e9d3565509fb5cd3e136c0fa68ad5b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void buildCopyToRegs (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; DstRegs, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> SrcTy, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> PartTy, unsigned ExtendOp=TargetOpcode::G_ANYEXT)</td>
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

<p>Create a sequence of instructions to expand the value in <span class="doxyComputerOutput">SrcReg</span> (of type <span class="doxyComputerOutput">SrcTy</span>) to the types in <span class="doxyComputerOutput">DstRegs</span> (of type <span class="doxyComputerOutput">PartTy</span>).</p>


<p><span class="doxyComputerOutput">ExtendOp</span> should contain the type of scalar value extension if necessary.</p>


<p>This is used for outgoing values (vregs to physregs)</p>


<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp">CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa47ab206f485fe45e4d8a882ff00fd42">llvm::getCoverTy</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa911a7e9e51b7ed20810fc819efe6a26">llvm::LLT::getElementCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb74ac5c2f2a45c7247a785f898d4833">llvm::getGCDType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#addaa86bfa4ca26b7f366cbdd868f99bf">llvm::details::FixedOrScalableQuantity&lt; TypeSize, uint64_t &gt;::isKnownGT</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a83e6442f8ebefccdb5e089732fe397ac">llvm::details::FixedOrScalableQuantity&lt; ElementCount, unsigned &gt;::isKnownLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a5360139c6b31d85cf3e29e2e6b7cf873">llvm::LLT::vector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>.</p>

</div>
</div>

### extendOpFromFlags() {#ae5b91dbd22e5c216d8f1b53a37eaac3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned extendOpFromFlags (<a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">llvm::ISD::ArgFlagsTy</a> Flags)</td>
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



<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp">CallLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>.</p>

</div>
</div>

### isCopyCompatibleType() {#ad4d564b29ec78229d8d9ab0970db529d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isCopyCompatibleType (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> SrcTy, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> DstTy)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if we can use a basic COPY instruction between the two types.</p>


<p>We're currently building on top of the infrastructure using <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a>, which loses pointer information in the <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a>. We accept copies from physical registers that have been reported as integers if it's to an equivalent sized pointer <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>.</p>


<p>Definition at line 1369 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp">CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#ae4165ca7bcbee300d5e9c065adcc1415">llvm::LLT::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a9d825f5954d7bd527aea490668c624c6">llvm::LLT::isPointer</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvaluehandler/#a2d2d74818c4f4ba5fb41e8a4f2c9d152">llvm::CallLowering::IncomingValueHandler::assignValueToReg</a>.</p>

</div>
</div>

### mergeVectorRegsToResultRegs() {#a627f84abfceb75ffd72119423d0147a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder mergeVectorRegsToResultRegs (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; DstRegs, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; SrcRegs)</td>
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

<p>Pack values <span class="doxyComputerOutput">SrcRegs</span> to cover the vector type result <span class="doxyComputerOutput">DstRegs</span>.</p>

<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp">CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa47ab206f485fe45e4d8a882ff00fd42">llvm::getCoverTy</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#aae7d70f087262ba4f7657f564ce0ca38">buildCopyFromRegs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"call-lowering"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp">CallLowering.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
