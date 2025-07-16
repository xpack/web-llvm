---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `AArch64CallingConvention.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-h">AArch64CallingConvention.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64-h">AArch64.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-h">AArch64InstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">llvm/CodeGen/CallingConvLower.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "AArch64GenCallingConv.inc"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d6af68066457ccc3a8ddcd68d142853">finishStackBlock</a> (SmallVectorImpl&lt; CCValAssign &gt; &amp;PendingMembers, MVT LocVT, ISD::ArgFlagsTy &amp;ArgFlags, CCState &amp;State, Align SlotAlign)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3f5f44efd30903d2316ec3e8f20cda3">CC_AArch64_Custom_Stack_Block</a> (unsigned &amp;ValNo, MVT &amp;ValVT, MVT &amp;LocVT, CCValAssign::LocInfo &amp;LocInfo, ISD::ArgFlagsTy &amp;ArgFlags, CCState &amp;State)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The Darwin variadic PCS places anonymous arguments in 8-byte stack slots. <a href="#af3f5f44efd30903d2316ec3e8f20cda3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a631b12e0c91c3249444afcf60f3f538c">CC_AArch64_Custom_Block</a> (unsigned &amp;ValNo, MVT &amp;ValVT, MVT &amp;LocVT, CCValAssign::LocInfo &amp;LocInfo, ISD::ArgFlagsTy &amp;ArgFlags, CCState &amp;State)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an [N x Ty] block, it should be passed in a consecutive sequence of registers. <a href="#a631b12e0c91c3249444afcf60f3f538c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a52bb93ebef29f32b7b50a6d22820cd">XRegList</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89f578c8a00e8791b49f67a4bbf31d75">HRegList</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e8ea691a96ed564d69d8484a2814f04">SRegList</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a747404a7467b628266a19d10fd43733e">DRegList</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad01ca71e7ac4d40890239c90f14d64cb">QRegList</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d9455506f62c6bdbe19e65352e6c700">ZRegList</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4288f0519b24a6a3e22b16b906668e3">PRegList</a>[] = ...</td>
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

### CC\_AArch64\_Custom\_Block() {#a631b12e0c91c3249444afcf60f3f538c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CC_AArch64_Custom_Block (unsigned &amp; ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> &amp; LocInfo, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp; ArgFlags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
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

<p>Given an [N x Ty] block, it should be passed in a consecutive sequence of registers.</p>


<p>If no such sequence is available, mark the rest of the registers of that type as used and place the argument on the stack.</p>


<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp">AArch64CallingConvention.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45aeada2602a598f9b877f1b75ed7dd9e4a">llvm::CCValAssign::AExtUpper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="#a747404a7467b628266a19d10fd43733e">DRegList</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="#a0d6af68066457ccc3a8ddcd68d142853">finishStackBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#ac619410078d3e34fcaeb34cb01cb3072">llvm::ISD::ArgFlagsTy::getNonZeroMemAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a1022d05ab2d1337a97addf0ea4678fed">llvm::CCValAssign::getPending</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a29708e79e029f1029d46d65e7631b778">llvm::CCValAssign::getReg</a>, <a href="#a89f578c8a00e8791b49f67a4bbf31d75">HRegList</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a0c1ae89f2c2765a979f999ecdc11304c">llvm::MVT::is128BitVector</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a4f3047f07ed3863b0b1ef4d5cb8c61e7">llvm::MVT::is32BitVector</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#af3624c7c6830c842d120434c17d1c846">llvm::MVT::is64BitVector</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#abb4b62c28d4a4aab9269cd62b1b3e094">llvm::ISD::ArgFlagsTy::isInConsecutiveRegsLast</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a447ebcc5de7a1d9bc163862bf2c78e41">llvm::MVT::isScalableVector</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a4d2e6b50d2d120966b45253b1ad825b4">llvm::AArch64Subtarget::isTargetDarwin</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a59137b132e07516767761d5decf7e252">llvm::AArch64Subtarget::isTargetILP32</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a6d2ea0d87e248160e202c25124c91fa9">llvm::AArch64Subtarget::isTargetMachO</a>, <a href="#ad4288f0519b24a6a3e22b16b906668e3">PRegList</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#ad01ca71e7ac4d40890239c90f14d64cb">QRegList</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="#a5e8ea691a96ed564d69d8484a2814f04">SRegList</a>, <a href="#a3a52bb93ebef29f32b7b50a6d22820cd">XRegList</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a807a4e133d7f743724d809a3f3875aa2">llvm::CCValAssign::ZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a06041e3bf4b0a9e8984809413ddd9506">llvm::zip</a> and <a href="#a6d9455506f62c6bdbe19e65352e6c700">ZRegList</a>.</p>

</div>
</div>

### CC\_AArch64\_Custom\_Stack\_Block() {#af3f5f44efd30903d2316ec3e8f20cda3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CC_AArch64_Custom_Stack_Block (unsigned &amp; ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> &amp; LocInfo, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp; ArgFlags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
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

<p>The Darwin variadic PCS places anonymous arguments in 8-byte stack slots.</p>


<p>An [N x Ty] type must still be contiguous in memory though.</p>


<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp">AArch64CallingConvention.cpp</a>.</p>


<p>References <a href="#a0d6af68066457ccc3a8ddcd68d142853">finishStackBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a1022d05ab2d1337a97addf0ea4678fed">llvm::CCValAssign::getPending</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#abb4b62c28d4a4aab9269cd62b1b3e094">llvm::ISD::ArgFlagsTy::isInConsecutiveRegsLast</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### finishStackBlock() {#a0d6af68066457ccc3a8ddcd68d142853}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool finishStackBlock (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &gt; &amp; PendingMembers, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> LocVT, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp; ArgFlags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> SlotAlign)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp">AArch64CallingConvention.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a52a3cbd48589c37855abca181342ccb7">llvm::AArch64TargetLowering::CCAssignFnForCall</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a8b73d77b9e54663c2e80a48d0917dce1">llvm::CCValAssign::Full</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a66b26e824dd1b4bb346cd20278651032">llvm::AArch64Subtarget::getTargetLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a447ebcc5de7a1d9bc163862bf2c78e41">llvm::MVT::isScalableVector</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ad4288f0519b24a6a3e22b16b906668e3">PRegList</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#a2004d6a7f4b9ac8d4e101eea3e52b33a">llvm::ISD::ArgFlagsTy::setInConsecutiveRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#adc87904b6600bb0300ec0e0c532c86c7">llvm::ISD::ArgFlagsTy::setInConsecutiveRegsLast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#a6d9455506f62c6bdbe19e65352e6c700">ZRegList</a>.</p>


<p>Referenced by <a href="#a631b12e0c91c3249444afcf60f3f538c">CC_AArch64_Custom_Block</a> and <a href="#af3f5f44efd30903d2316ec3e8f20cda3">CC_AArch64_Custom_Stack_Block</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DRegList {#a747404a7467b628266a19d10fd43733e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg DRegList[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {AArch64::D0, AArch64::D1, AArch64::D2,
                                     AArch64::D3, AArch64::D4, AArch64::D5,
                                     AArch64::D6, AArch64::D7}
</div>
</dd>
</dl>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp">AArch64CallingConvention.cpp</a>.</p>


<p>Referenced by <a href="#a631b12e0c91c3249444afcf60f3f538c">CC_AArch64_Custom_Block</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#a6790e830edd3f7940cc257f01a794604">CC_ARM_AAPCS_Custom_Aggregate</a>.</p>

</div>
</div>

### HRegList {#a89f578c8a00e8791b49f67a4bbf31d75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg HRegList[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {AArch64::H0, AArch64::H1, AArch64::H2,
                                     AArch64::H3, AArch64::H4, AArch64::H5,
                                     AArch64::H6, AArch64::H7}
</div>
</dd>
</dl>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp">AArch64CallingConvention.cpp</a>.</p>


<p>Referenced by <a href="#a631b12e0c91c3249444afcf60f3f538c">CC_AArch64_Custom_Block</a>.</p>

</div>
</div>

### PRegList {#ad4288f0519b24a6a3e22b16b906668e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg PRegList[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {AArch64::P0, AArch64::P1, AArch64::P2,
                                     AArch64::P3}
</div>
</dd>
</dl>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp">AArch64CallingConvention.cpp</a>.</p>


<p>Referenced by <a href="#a631b12e0c91c3249444afcf60f3f538c">CC_AArch64_Custom_Block</a> and <a href="#a0d6af68066457ccc3a8ddcd68d142853">finishStackBlock</a>.</p>

</div>
</div>

### QRegList {#ad01ca71e7ac4d40890239c90f14d64cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg QRegList[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {AArch64::Q0, AArch64::Q1, AArch64::Q2,
                                     AArch64::Q3, AArch64::Q4, AArch64::Q5,
                                     AArch64::Q6, AArch64::Q7}
</div>
</dd>
</dl>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp">AArch64CallingConvention.cpp</a>.</p>


<p>Referenced by <a href="#a631b12e0c91c3249444afcf60f3f538c">CC_AArch64_Custom_Block</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#a6790e830edd3f7940cc257f01a794604">CC_ARM_AAPCS_Custom_Aggregate</a>.</p>

</div>
</div>

### SRegList {#a5e8ea691a96ed564d69d8484a2814f04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg SRegList[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {AArch64::S0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">AArch64::S1</a>, AArch64::S2,
                                     AArch64::S3, AArch64::S4, AArch64::S5,
                                     AArch64::S6, AArch64::S7}
</div>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp">AArch64CallingConvention.cpp</a>.</p>


<p>Referenced by <a href="#a631b12e0c91c3249444afcf60f3f538c">CC_AArch64_Custom_Block</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#a6790e830edd3f7940cc257f01a794604">CC_ARM_AAPCS_Custom_Aggregate</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#a18f5c0dcfa9bed1a9c1e7fe9f226e841">CC_ARM_AAPCS_VFP_Custom_f16</a>.</p>

</div>
</div>

### XRegList {#a3a52bb93ebef29f32b7b50a6d22820cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg XRegList[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {AArch64::X0, AArch64::X1, AArch64::X2,
                                     AArch64::X3, AArch64::X4, AArch64::X5,
                                     AArch64::X6, AArch64::X7}
</div>
</dd>
</dl>

<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp">AArch64CallingConvention.cpp</a>.</p>


<p>Referenced by <a href="#a631b12e0c91c3249444afcf60f3f538c">CC_AArch64_Custom_Block</a>.</p>

</div>
</div>

### ZRegList {#a6d9455506f62c6bdbe19e65352e6c700}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg ZRegList[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {AArch64::Z0, AArch64::Z1, AArch64::Z2,
                                     AArch64::Z3, AArch64::Z4, AArch64::Z5,
                                     AArch64::Z6, AArch64::Z7}
</div>
</dd>
</dl>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp">AArch64CallingConvention.cpp</a>.</p>


<p>Referenced by <a href="#a631b12e0c91c3249444afcf60f3f538c">CC_AArch64_Custom_Block</a> and <a href="#a0d6af68066457ccc3a8ddcd68d142853">finishStackBlock</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
