---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/aarch64legalizerinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AArch64LegalizerInfo` Class



## Declaration

<div class="doxyDeclaration">
class llvm::AArch64LegalizerInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">Target/AArch64/GISel/AArch64LegalizerInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae27667d7c3fbd41b18fd5838fc4f0553">AArch64LegalizerInfo</a> (const AArch64Subtarget &amp;ST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14251e7cc7c001be8b83a76caa7acd92">legalizeCustom</a> (LegalizerHelper &amp;Helper, MachineInstr &amp;MI, LostDebugLocObserver &amp;LocObserver) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called for instructions with the Custom LegalizationAction. <a href="#a14251e7cc7c001be8b83a76caa7acd92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa48b853fae2f40e3e483078a944ab8d1">legalizeIntrinsic</a> (LegalizerHelper &amp;Helper, MachineInstr &amp;MI) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca72ea9d7b9b6171cd21a3156fdeaad7">legalizeVaArg</a> (MachineInstr &amp;MI, MachineRegisterInfo &amp;MRI, MachineIRBuilder &amp;MIRBuilder) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57bf6db315e11b1b9ac841afa68c3d6c">legalizeLoadStore</a> (MachineInstr &amp;MI, MachineRegisterInfo &amp;MRI, MachineIRBuilder &amp;MIRBuilder, GISelChangeObserver &amp;Observer) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c901fc2f9b74527471cf958bd9ce40b">legalizeShlAshrLshr</a> (MachineInstr &amp;MI, MachineRegisterInfo &amp;MRI, MachineIRBuilder &amp;MIRBuilder, GISelChangeObserver &amp;Observer) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a0a832ac3733b8fa1e90bd5e43e8422">legalizeSmallCMGlobalValue</a> (MachineInstr &amp;MI, MachineRegisterInfo &amp;MRI, MachineIRBuilder &amp;MIRBuilder, GISelChangeObserver &amp;Observer) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07b6c3f7b7291f93744e1196e6e692a5">legalizeBitfieldExtract</a> (MachineInstr &amp;MI, MachineRegisterInfo &amp;MRI, LegalizerHelper &amp;Helper) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdf7229f03e7c541d3dbacaecf51b141">legalizeRotate</a> (MachineInstr &amp;MI, MachineRegisterInfo &amp;MRI, LegalizerHelper &amp;Helper) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5f82a8ca5dda956bcc9d2f9443e9ace">legalizeICMP</a> (MachineInstr &amp;MI, MachineRegisterInfo &amp;MRI, MachineIRBuilder &amp;MIRBuilder) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a218fff0a855414de6ff677f7a0cd080c">legalizeFunnelShift</a> (MachineInstr &amp;MI, MachineRegisterInfo &amp;MRI, MachineIRBuilder &amp;MIRBuilder, GISelChangeObserver &amp;Observer, LegalizerHelper &amp;Helper) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32587b78275ca6c43a5ea7d69da1cbd5">legalizeCTPOP</a> (MachineInstr &amp;MI, MachineRegisterInfo &amp;MRI, LegalizerHelper &amp;Helper) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99dddb190bdc5fdef47a221faf2d1193">legalizeAtomicCmpxchg128</a> (MachineInstr &amp;MI, MachineRegisterInfo &amp;MRI, LegalizerHelper &amp;Helper) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b54c71a5d44e29a3e1a339c7d8fd41d">legalizeCTTZ</a> (MachineInstr &amp;MI, LegalizerHelper &amp;Helper) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27bf22d9e2231619af90ec1e75cde64e">legalizeMemOps</a> (MachineInstr &amp;MI, LegalizerHelper &amp;Helper) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a938477beb9559cfc67a78ce2784c2e22">legalizeExtractVectorElt</a> (MachineInstr &amp;MI, MachineRegisterInfo &amp;MRI, LegalizerHelper &amp;Helper) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7b3644ab750765fda0aabaed484904c">legalizeDynStackAlloc</a> (MachineInstr &amp;MI, LegalizerHelper &amp;Helper) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48f750635e87f387a411d10adb3609d9">legalizePrefetch</a> (MachineInstr &amp;MI, LegalizerHelper &amp;Helper) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae376717ef2d417a7409cef78105246fd">legalizeBitcast</a> (MachineInstr &amp;MI, LegalizerHelper &amp;Helper) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget">AArch64Subtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21944c1bcf25997020bcdeb9383007d8">ST</a></td>
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


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AArch64LegalizerInfo() {#ae27667d7c3fbd41b18fd5838fc4f0553}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64LegalizerInfo::AArch64LegalizerInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget">AArch64Subtarget</a> &amp; ST)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-cpp">AArch64LegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a993ca650a85e8e69b8f7eaa4809c4862">llvm::Acquire</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a873403a2506ac332f62ad4c2d7dc1835">llvm::all</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#ab250f5144d04471b35f7fc229dc9da5c">llvm::LegalizeRuleSet::alwaysLegal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#a6fef38ab5d0c9c582fe6cae7d8badf5f">llvm::LegalityPredicates::any</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#a4d17100c5b9375e90f20d666f7615c56">llvm::LegalityPredicates::atomicOrderingAtLeastOrStrongerThan</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a3128e17013a7e7dd6a855d0b00ad60f9">llvm::LegalizeRuleSet::bitcastIf</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#adabd45e67a1847750a117317b5ef8f9f">llvm::LLT::changeElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aaa6f42b31892a929914872c879e4b365">llvm::LLT::changeElementSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#af1ee247ef88b451470210e27a2eefb44">llvm::LegalizeMutations::changeElementSizeTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#acd331b959990c033f8d612adf7701b05">llvm::LegalizeMutations::changeTo</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a3b9d49f459b9596f73c60edab6e92673">llvm::LegalizeRuleSet::clampMaxNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a3da19f78bfc264962a18568ea4b8d6c7">llvm::LegalizeRuleSet::clampMinNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#ac56e6d7519b8f4f908174aa570bc5e61">llvm::LegalizeRuleSet::clampNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a7adc16cc9bc8db5fd3c8a6798a846ab0">llvm::LegalizeRuleSet::clampScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/legacylegalizerinfo/#a6b586580f1e35e04ae0f3186fadd6594">llvm::LegacyLegalizerInfo::computeTables</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a80f41417117f537cd147aaee97aecb1e">llvm::LegalizeRuleSet::custom</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a4ad690ef8db6cd914cef1b3aa39bc15f">llvm::LegalizeRuleSet::customForCartesianProduct</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#acda429561493e08ee5cef54f26a1224c">llvm::LegalizeRuleSet::customIf</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ae7510a639ca53c1bfa1c90c6dfc7eb2e">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::divideCoefficientBy</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#a32539827696dafee94ee79c3321b4245">llvm::LegalizerInfo::getActionDefinitionsBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa911a7e9e51b7ed20810fc819efe6a26">llvm::LLT::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#a33b434e9218db992447f811551810394">llvm::LegalizerInfo::getLegacyLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#af1f70f6956b2338cfdc8e8316b104078">llvm::LegalizeRuleSet::immIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#a39ec5f3bcaf89f94246b4c4784ed4d10">llvm::LegalityPredicates::isPointerVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#ab8c6d0c31153197f492410b3c0a37248">llvm::LegalityPredicates::isVector</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a1c27c69ac65f9d4937858c10288a17f6">llvm::LegalizeRuleSet::legalFor</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#ae4c02bcf9d3bfdee70f097d0b6aeb9f3">llvm::LegalizeRuleSet::legalForCartesianProduct</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#aebb3b5876088ebfd2d003d68f7fb4b07">llvm::LegalizeRuleSet::legalForTypesWithMemDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#af6dcfac5a30e4050e3ac204f27062fe6">llvm::LegalizeRuleSet::legalIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/hwaddresssanitizer-cpp/#aeaa43ab635ee98b9e2055d0f217558c2ad9dbfb96b7805fecf168bf553c423cce">libcall</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a32e4ff098c95890246047dc1ddf5a065">llvm::LegalizeRuleSet::libcallFor</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a6a836d4faf3f9f04f1f04cc5f6de3c03">llvm::LegalizeRuleSet::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a6eec582df34bb1c63e8666b41ff561ec">llvm::LegalizeRuleSet::lowerFor</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a76a7807072af618c3ac80dd8d569deba">llvm::LegalizeRuleSet::lowerIf</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a5361d650c0e9459b1dc4c3afec8251ef">llvm::LegalizeRuleSet::lowerIfMemSizeNotByteSizePow2</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a479d3f2cd21c2250ae84ec2b06be816f">llvm::LegalizeRuleSet::lowerIfMemSizeNotPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a33e181da566d1ebb7556f172888c3b92">llvm::LegalizeRuleSet::maxScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a1d446dfaa94c6ec0729feaa73d5b6c88">llvm::LegalizeRuleSet::maxScalarEltSameAsIf</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#acd56c0d001ca90095d61c52099f90cd3">llvm::LegalizeRuleSet::maxScalarIf</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a009564405d1037574152ee039cd04b9f">llvm::LegalizeRuleSet::minScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a4aca13e5c1613b22b7c3c9411895fdae">llvm::LegalizeRuleSet::minScalarEltSameAsIf</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a3453ec1df80a077b489ea76fee965967">llvm::LegalizeRuleSet::minScalarOrElt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a9673f01ba4c77779f3361b426653d257">llvm::LegalizeRuleSet::minScalarOrEltIf</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a8abe7c10c8bfc8f9c308c89adc98330c">llvm::LegalizeRuleSet::minScalarSameAs</a>, <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#a9e26ab57991dfde2757e4790a626d6a3">llvm::LegalityQuery::MMODescrs</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a6baff39b32f5cec5ea417cba89f077ac">llvm::LegalizeRuleSet::moreElementsIf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#a039bb9a10ad812f936f4325facc13ab3">llvm::LegalizeMutations::moreElementsToNextPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a592ea5db9394c272d8354d931134f16c">llvm::LegalizeRuleSet::moreElementsToNextPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a6a80f26baa5258688f20cafc7efac05f">llvm::LegalizeRuleSet::narrowScalarIf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7ff0361855acbbe71b15b8dc6003fbc5">llvm::LLT::pointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ab8e7b465df7c5979dc731d06e84ce2cf">llvm::Release</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3c8d482078435a16e34c2cc13caa6f75">llvm::LLT::scalable_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#a5574ba0db2a42fa195db009f06f1d731">llvm::LegalizeMutations::scalarize</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#adf80c6b70ec078f749c51a5e64b4393d">llvm::LegalizeRuleSet::scalarize</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a7369e2b43abeda933406d7b9ed83500c">llvm::LegalizeRuleSet::scalarizeIf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#a0460dde35b7517637d8ac040900d42ba">llvm::LegalityPredicates::scalarOrEltWiderThan</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a236c4562fff94fbec23fd35c0b5257a1">llvm::LegalizeRuleSet::scalarSameSizeAs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#af80fd220e67295d05887d3f948695ab2">llvm::LegalityPredicates::scalarWiderThan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">llvm::CodeModel::Small</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#a45c9d1ec6a1b46697b0363f2c8a605c5">llvm::LegalityPredicates::smallerThan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#a3b65801c5b31890a1d1cd8a0038aee87">llvm::LegalityPredicates::typeInSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#ae56d6ae68f8659cfaa29fb7cb601f111">llvm::LegalityPredicates::typeIs</a>, <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#ab28fca6f8145be28b70ad89bb0c741b0">llvm::LegalityQuery::Types</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a288d468c5e0969f26a310773eda65603">llvm::Unordered</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a2034405f0aed7259ed9999053c3f591d">llvm::LegalizeRuleSet::unsupported</a>, <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/macho-cpp/#a1a923abcc65272bfe81c0e7081c32421">unsupported</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a916cd5bc69b2a149600ab1488c047bc7">llvm::LegalizeRuleSet::unsupportedIf</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a5360139c6b31d85cf3e29e2e6b7cf873">llvm::LLT::vector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp/#a593cc2f204f7b2edc16ee222c37c3196">verify</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a99e1a648bb3a1018aed19e77cae2203c">llvm::LegalizeRuleSet::widenScalarIf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#ac48512a9f1e26744de1b6940b4adb68f">llvm::LegalizeMutations::widenScalarOrEltToNextPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#af52cd47605369d735f4d6e6b24faf003">llvm::LegalizeRuleSet::widenScalarOrEltToNextPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a173a5c5c1e9992339faedc21b5954918">llvm::LegalizeRuleSet::widenScalarOrEltToNextPow2OrMinSize</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#adef498f01eb5d7c19ac40cd3b302d09e">llvm::LegalizeRuleSet::widenScalarToNextPow2</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a430225b2e66451c27e9f4e9462be7df1">llvm::LegalizeRuleSet::widenVectorEltsToVectorMinSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### legalizeCustom() {#a14251e7cc7c001be8b83a76caa7acd92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64LegalizerInfo::legalizeCustom (<a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/lostdebuglocobserver">LostDebugLocObserver</a> &amp; LocObserver)</td>
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

<p>Called for instructions with the Custom LegalizationAction.</p>

<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a>, definition at line 1371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-cpp">AArch64LegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad7322f56c0659b8dc8e55567767b74d6">llvm::MachineIRBuilder::getMRI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a41da6a2461e80e2d3b6b226281477bfa">llvm::LegalizerHelper::lowerAbsToCNeg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae50d11fc026093629c27142780ff1405">llvm::LegalizerHelper::MIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aa910c5e501ff9679cc81de15bf3b9c1d">llvm::LegalizerHelper::Observer</a>.</p>

</div>
</div>

### legalizeIntrinsic() {#aa48b853fae2f40e3e483078a944ab8d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64LegalizerInfo::legalizeIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if MI is either legal or has been legalized and false if not legal. Return true if MI is either legal or has been legalized and false if not legal.</p></dd>
</dl>


<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a>, definition at line 1602 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-cpp">AArch64LegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#acac15566596b1d588d87450ab77bf0d7">llvm::MachineIRBuilder::buildAnyExt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af751c28a69e1d07e19dad11e4e26a70d">llvm::MachineIRBuilder::buildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ae32b6e2213ad3119a124e6e0673a5898">llvm::MachineIRBuilder::buildCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ab8da4d08f2c0875e9623bb712aa64303">llvm::MachineIRBuilder::buildExtOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a7962eca94c9f77da448245745fb22f57">llvm::MachineIRBuilder::buildLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a87a7405685118d45876c996318829ceb">llvm::MachineIRBuilder::buildStore</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#abf1763199cd36c9253c6f062fa5e973e">llvm::MachineIRBuilder::buildTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver/#a45a05a932f80f51023592ff5131d56a5">llvm::GISelChangeObserver::changedInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver/#a1f637715070a99aa4140444e12697f9a">llvm::GISelChangeObserver::changingInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a9694f2906cfe1d6d35bbe6742c67dff0">llvm::MachineRegisterInfo::createGenericVirtualRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a430daa77692b7b25f93a72d83e51964f">llvm::MachineIRBuilder::getInsertPt</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ac8f6c5b9180bd630c92e1126877d0b08">llvm::MachineIRBuilder::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad7322f56c0659b8dc8e55567767b74d6">llvm::MachineIRBuilder::getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a1c5fadb14ff1d77faad0cb58a43252ab">llvm::MachineInstrBuilder::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae50d11fc026093629c27142780ff1405">llvm::LegalizerHelper::MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aa910c5e501ff9679cc81de15bf3b9c1d">llvm::LegalizerHelper::Observer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a0df93c0f752428162e14b54f8999172d">llvm::MachineIRBuilder::setInsertPt</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### legalizeAtomicCmpxchg128() {#a99dddb190bdc5fdef47a221faf2d1193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64LegalizerInfo::legalizeAtomicCmpxchg128 (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a>, definition at line 2109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-cpp">AArch64LegalizerInfo.cpp</a>.</p>

</div>
</div>

### legalizeBitcast() {#ae376717ef2d417a7409cef78105246fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64LegalizerInfo::legalizeBitcast (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a>, definition at line 1428 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-cpp">AArch64LegalizerInfo.cpp</a>.</p>

</div>
</div>

### legalizeBitfieldExtract() {#a07b6c3f7b7291f93744e1196e6e692a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64LegalizerInfo::legalizeBitfieldExtract (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a>, definition at line 1965 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-cpp">AArch64LegalizerInfo.cpp</a>.</p>

</div>
</div>

### legalizeCTPOP() {#a32587b78275ca6c43a5ea7d69da1cbd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64LegalizerInfo::legalizeCTPOP (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a>, definition at line 1973 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-cpp">AArch64LegalizerInfo.cpp</a>.</p>

</div>
</div>

### legalizeCTTZ() {#a4b54c71a5d44e29a3e1a339c7d8fd41d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64LegalizerInfo::legalizeCTTZ (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a>, definition at line 2206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-cpp">AArch64LegalizerInfo.cpp</a>.</p>

</div>
</div>

### legalizeDynStackAlloc() {#ad7b3644ab750765fda0aabaed484904c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64LegalizerInfo::legalizeDynStackAlloc (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a>, definition at line 2249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-cpp">AArch64LegalizerInfo.cpp</a>.</p>

</div>
</div>

### legalizeExtractVectorElt() {#a938477beb9559cfc67a78ce2784c2e22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64LegalizerInfo::legalizeExtractVectorElt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a>, definition at line 2235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-cpp">AArch64LegalizerInfo.cpp</a>.</p>

</div>
</div>

### legalizeFunnelShift() {#a218fff0a855414de6ff677f7a0cd080c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64LegalizerInfo::legalizeFunnelShift (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a> &amp; Observer, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a>, definition at line 1443 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-cpp">AArch64LegalizerInfo.cpp</a>.</p>

</div>
</div>

### legalizeICMP() {#ae5f82a8ca5dda956bcc9d2f9443e9ace}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64LegalizerInfo::legalizeICMP (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a>, definition at line 1496 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-cpp">AArch64LegalizerInfo.cpp</a>.</p>

</div>
</div>

### legalizeLoadStore() {#a57bf6db315e11b1b9ac841afa68c3d6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64LegalizerInfo::legalizeLoadStore (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a> &amp; Observer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a>, definition at line 1825 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-cpp">AArch64LegalizerInfo.cpp</a>.</p>

</div>
</div>

### legalizeMemOps() {#a27bf22d9e2231619af90ec1e75cde64e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64LegalizerInfo::legalizeMemOps (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a>, definition at line 2217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-cpp">AArch64LegalizerInfo.cpp</a>.</p>

</div>
</div>

### legalizePrefetch() {#a48f750635e87f387a411d10adb3609d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64LegalizerInfo::legalizePrefetch (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a>, definition at line 2288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-cpp">AArch64LegalizerInfo.cpp</a>.</p>

</div>
</div>

### legalizeRotate() {#abdf7229f03e7c541d3dbacaecf51b141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64LegalizerInfo::legalizeRotate (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a>, definition at line 1526 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-cpp">AArch64LegalizerInfo.cpp</a>.</p>

</div>
</div>

### legalizeShlAshrLshr() {#a3c901fc2f9b74527471cf958bd9ce40b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64LegalizerInfo::legalizeShlAshrLshr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a> &amp; Observer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a>, definition at line 1786 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-cpp">AArch64LegalizerInfo.cpp</a>.</p>

</div>
</div>

### legalizeSmallCMGlobalValue() {#a0a0a832ac3733b8fa1e90bd5e43e8422}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64LegalizerInfo::legalizeSmallCMGlobalValue (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a> &amp; Observer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a>, definition at line 1543 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-cpp">AArch64LegalizerInfo.cpp</a>.</p>

</div>
</div>

### legalizeVaArg() {#aca72ea9d7b9b6171cd21a3156fdeaad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64LegalizerInfo::legalizeVaArg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a>, definition at line 1917 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-cpp">AArch64LegalizerInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ST {#a21944c1bcf25997020bcdeb9383007d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AArch64Subtarget* llvm::AArch64LegalizerInfo::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-cpp">AArch64LegalizerInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">AArch64LegalizerInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
