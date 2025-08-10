---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `X86CallingConv.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-h">X86CallingConv.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86subtarget-h">X86Subtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">llvm/CodeGen/CallingConvLower.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "X86GenCallingConv.inc"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4634e79ad97015aa93f2379f619cc6ae">CC_X86_32_RegCall_Assign2Regs</a> (unsigned &amp;ValNo, MVT &amp;ValVT, MVT &amp;LocVT, CCValAssign::LocInfo &amp;LocInfo, ISD::ArgFlagsTy &amp;ArgFlags, CCState &amp;State)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When regcall calling convention compiled to 32 bit arch, special treatment is required for 64 bit masks. <a href="#a4634e79ad97015aa93f2379f619cc6ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d888b71dc30a3b4c69c0a3ae5a4012a">CC_X86_VectorCallGetSSEs</a> (const MVT &amp;ValVT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ada49322917ad754a7d0a16fa2c59de">CC_X86_64_VectorCallGetGPRs</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14a88401fe6f00ed3b943fa7f0132d46">CC_X86_VectorCallAssignRegister</a> (unsigned &amp;ValNo, MVT &amp;ValVT, MVT &amp;LocVT, CCValAssign::LocInfo &amp;LocInfo, ISD::ArgFlagsTy &amp;ArgFlags, CCState &amp;State)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa1494436b6de4729389856e59276c98">CC_X86_64_VectorCall</a> (unsigned &amp;ValNo, MVT &amp;ValVT, MVT &amp;LocVT, CCValAssign::LocInfo &amp;LocInfo, ISD::ArgFlagsTy &amp;ArgFlags, CCState &amp;State)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vectorcall calling convention has special handling for vector types or HVA for 64 bit arch. <a href="#aaa1494436b6de4729389856e59276c98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8687e6a4188d6843aebb24bf2944804">CC_X86_32_VectorCall</a> (unsigned &amp;ValNo, MVT &amp;ValVT, MVT &amp;LocVT, CCValAssign::LocInfo &amp;LocInfo, ISD::ArgFlagsTy &amp;ArgFlags, CCState &amp;State)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vectorcall calling convention has special handling for vector types or HVA for 32 bit arch. <a href="#af8687e6a4188d6843aebb24bf2944804">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a107306c599b9c4abdf871f39f8f9f425">CC_X86_AnyReg_Error</a> (unsigned &amp;, MVT &amp;, MVT &amp;, CCValAssign::LocInfo &amp;, ISD::ArgFlagsTy &amp;, CCState &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41dd5c8db0f0898d613b138097515474">CC_X86_32_MCUInReg</a> (unsigned &amp;ValNo, MVT &amp;ValVT, MVT &amp;LocVT, CCValAssign::LocInfo &amp;LocInfo, ISD::ArgFlagsTy &amp;ArgFlags, CCState &amp;State)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee234a7eddb790513041e995ed66158">CC_X86_Intr</a> (unsigned &amp;ValNo, MVT &amp;ValVT, MVT &amp;LocVT, CCValAssign::LocInfo &amp;LocInfo, ISD::ArgFlagsTy &amp;ArgFlags, CCState &amp;State)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> interrupt handlers can only take one or two stack arguments, but if there are two arguments, they are in the opposite order from the standard convention. <a href="#a7ee234a7eddb790513041e995ed66158">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8ad73c4b93e0c3caec975ea9d6e999c">CC_X86_64_Pointer</a> (unsigned &amp;ValNo, MVT &amp;ValVT, MVT &amp;LocVT, CCValAssign::LocInfo &amp;LocInfo, ISD::ArgFlagsTy &amp;ArgFlags, CCState &amp;State)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61009b749b466b57d30ec5134bf613bb">CC_X86_64_I128</a> (unsigned &amp;ValNo, MVT &amp;ValVT, MVT &amp;LocVT, CCValAssign::LocInfo &amp;LocInfo, ISD::ArgFlagsTy &amp;ArgFlags, CCState &amp;State)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Special handling for i128: Either allocate the value to two consecutive i64 registers, or to the stack. <a href="#a61009b749b466b57d30ec5134bf613bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### CC\_X86\_32\_MCUInReg() {#a41dd5c8db0f0898d613b138097515474}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CC_X86_32_MCUInReg (unsigned &amp; ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> &amp; LocInfo, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp; ArgFlags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp">X86CallingConv.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a1022d05ab2d1337a97addf0ea4678fed">llvm::CCValAssign::getPending</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a29708e79e029f1029d46d65e7631b778">llvm::CCValAssign::getReg</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#a989f6c0917729b4622f413f629239420">llvm::ISD::ArgFlagsTy::isSplit</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#a0343079be1a948f58f37c97559973b90">llvm::ISD::ArgFlagsTy::isSplitEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### CC\_X86\_32\_RegCall\_Assign2Regs() {#a4634e79ad97015aa93f2379f619cc6ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CC_X86_32_RegCall_Assign2Regs (unsigned &amp; ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> &amp; LocInfo, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp; ArgFlags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
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

<p>When regcall calling convention compiled to 32 bit arch, special treatment is required for 64 bit masks.</p>


<p>The value should be assigned to two GPRs.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if registers were allocated and false otherwise.</p></dd>
</dl>


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp">X86CallingConv.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a3213a94802bb4f87a3e388af6cdd9d7f">llvm::CCValAssign::getCustomReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### CC\_X86\_32\_VectorCall() {#af8687e6a4188d6843aebb24bf2944804}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CC_X86_32_VectorCall (unsigned &amp; ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> &amp; LocInfo, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp; ArgFlags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
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

<p>Vectorcall calling convention has special handling for vector types or HVA for 32 bit arch.</p>


<p>For HVAs actual XMM registers are allocated on the second pass. For vector types, actual XMM registers are allocated on the first pass.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if registers were allocated and false otherwise.</p></dd>
</dl>


<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp">X86CallingConv.cpp</a>.</p>


<p>References <a href="#a14a88401fe6f00ed3b943fa7f0132d46">CC_X86_VectorCallAssignRegister</a>, <a href="#a7d888b71dc30a3b4c69c0a3ae5a4012a">CC_X86_VectorCallGetSSEs</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a29708e79e029f1029d46d65e7631b778">llvm::CCValAssign::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45aacf7e7d80f766b55b2bbdaf3d354c39e">llvm::CCValAssign::Indirect</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#adc90e34882c97d5a86dd883d3d23b4ca">llvm::MVT::isFloatingPoint</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#a818a4ff7f8a1e73e623e74ffd0fdc95f">llvm::ISD::ArgFlagsTy::isHva</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#a5af59a7db5f3b01138d11a3dc7da10db">llvm::ISD::ArgFlagsTy::isSecArgPass</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a425636b56fa037ed7b19ef7f9de30df9">llvm::MVT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#ac8683d314a90a316cb67a685d42a8c28">llvm::ISD::ArgFlagsTy::setInReg</a>.</p>

</div>
</div>

### CC\_X86\_64\_I128() {#a61009b749b466b57d30ec5134bf613bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CC_X86_64_I128 (unsigned &amp; ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> &amp; LocInfo, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp; ArgFlags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
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

<p>Special handling for i128: Either allocate the value to two consecutive i64 registers, or to the stack.</p>


<p>Do not partially allocate in registers, and do not reserve any registers when allocating to the stack.</p>


<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp">X86CallingConv.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a1022d05ab2d1337a97addf0ea4678fed">llvm::CCValAssign::getPending</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#abb4b62c28d4a4aab9269cd62b1b3e094">llvm::ISD::ArgFlagsTy::isInConsecutiveRegsLast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### CC\_X86\_64\_Pointer() {#af8ad73c4b93e0c3caec975ea9d6e999c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CC_X86_64_Pointer (unsigned &amp; ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> &amp; LocInfo, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp; ArgFlags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
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



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp">X86CallingConv.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a807a4e133d7f743724d809a3f3875aa2">llvm::CCValAssign::ZExt</a>.</p>

</div>
</div>

### CC\_X86\_64\_VectorCall() {#aaa1494436b6de4729389856e59276c98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CC_X86_64_VectorCall (unsigned &amp; ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> &amp; LocInfo, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp; ArgFlags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
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

<p>Vectorcall calling convention has special handling for vector types or HVA for 64 bit arch.</p>


<p>For HVAs shadow registers might be allocated on the first pass and actual XMM registers are allocated on the second pass. For vector types, actual XMM registers are allocated on the first pass.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if registers were allocated and false otherwise.</p></dd>
</dl>


<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp">X86CallingConv.cpp</a>.</p>


<p>References <a href="#a8ada49322917ad754a7d0a16fa2c59de">CC_X86_64_VectorCallGetGPRs</a>, <a href="#a14a88401fe6f00ed3b943fa7f0132d46">CC_X86_VectorCallAssignRegister</a>, <a href="#a7d888b71dc30a3b4c69c0a3ae5a4012a">CC_X86_VectorCallGetSSEs</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a29708e79e029f1029d46d65e7631b778">llvm::CCValAssign::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#adc90e34882c97d5a86dd883d3d23b4ca">llvm::MVT::isFloatingPoint</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#a818a4ff7f8a1e73e623e74ffd0fdc95f">llvm::ISD::ArgFlagsTy::isHva</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#a048fbfd76ffc6c50232e51e944eec532">llvm::ISD::ArgFlagsTy::isHvaStart</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#a5af59a7db5f3b01138d11a3dc7da10db">llvm::ISD::ArgFlagsTy::isSecArgPass</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a425636b56fa037ed7b19ef7f9de30df9">llvm::MVT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### CC\_X86\_64\_VectorCallGetGPRs() {#a8ada49322917ad754a7d0a16fa2c59de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MCPhysReg &gt; CC_X86_64_VectorCallGetGPRs ()</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp">X86CallingConv.cpp</a>.</p>


<p>Referenced by <a href="#aaa1494436b6de4729389856e59276c98">CC_X86_64_VectorCall</a>.</p>

</div>
</div>

### CC\_X86\_AnyReg\_Error() {#a107306c599b9c4abdf871f39f8f9f425}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CC_X86_AnyReg_Error (unsigned &amp;, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> &amp;, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp;)</td>
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



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp">X86CallingConv.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### CC\_X86\_Intr() {#a7ee234a7eddb790513041e995ed66158}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CC_X86_Intr (unsigned &amp; ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> &amp; LocInfo, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp; ArgFlags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> interrupt handlers can only take one or two stack arguments, but if there are two arguments, they are in the opposite order from the standard convention.</p>


<p>Therefore, we have to look at the argument count up front before allocating stack for each argument.</p>


<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp">X86CallingConv.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#ac6baa801e4aea800984e760d5460662f">llvm::Function::arg_size</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a36d9dd26dea75ebba5b55516b52e0752">llvm::CCValAssign::getMem</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a652270ec0bdb03b5a7f934524412aa7f">is64Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### CC\_X86\_VectorCallAssignRegister() {#a14a88401fe6f00ed3b943fa7f0132d46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CC_X86_VectorCallAssignRegister (unsigned &amp; ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> &amp; LocInfo, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp; ArgFlags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp">X86CallingConv.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7d888b71dc30a3b4c69c0a3ae5a4012a">CC_X86_VectorCallGetSSEs</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a29708e79e029f1029d46d65e7631b778">llvm::CCValAssign::getReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#af8687e6a4188d6843aebb24bf2944804">CC_X86_32_VectorCall</a> and <a href="#aaa1494436b6de4729389856e59276c98">CC_X86_64_VectorCall</a>.</p>

</div>
</div>

### CC\_X86\_VectorCallGetSSEs() {#a7d888b71dc30a3b4c69c0a3ae5a4012a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MCPhysReg &gt; CC_X86_VectorCallGetSSEs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; ValVT)</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp">X86CallingConv.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mvt/#a9e3e2c5a531a6ff555d5302ba1745357">llvm::MVT::is256BitVector</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a776c0f4551869d18e571ae4e87583d86">llvm::MVT::is512BitVector</a>.</p>


<p>Referenced by <a href="#af8687e6a4188d6843aebb24bf2944804">CC_X86_32_VectorCall</a>, <a href="#aaa1494436b6de4729389856e59276c98">CC_X86_64_VectorCall</a> and <a href="#a14a88401fe6f00ed3b943fa7f0132d46">CC_X86_VectorCallAssignRegister</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
