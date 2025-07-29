---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/x86legalizerinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `X86LegalizerInfo` Class



## Declaration

<div class="doxyDeclaration">
class llvm::X86LegalizerInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86legalizerinfo-h">Target/X86/GISel/X86LegalizerInfo.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfc562c1c7aebc23222627fa24d11df5">X86LegalizerInfo</a> (const X86Subtarget &amp;STI, const X86TargetMachine &amp;TM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a088615ef5bf315b474c43859307730ec">legalizeCustom</a> (LegalizerHelper &amp;Helper, MachineInstr &amp;MI, LostDebugLocObserver &amp;LocObserver) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called for instructions with the Custom LegalizationAction. <a href="#a088615ef5bf315b474c43859307730ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d2c4c47a7326cd903beda3b760d057a">legalizeIntrinsic</a> (LegalizerHelper &amp;Helper, MachineInstr &amp;MI) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a095181d71278ac793e6d1819fa7595ae">legalizeBuildVector</a> (MachineInstr &amp;MI, MachineRegisterInfo &amp;MRI, LegalizerHelper &amp;Helper) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85086789e4f81c2ff47c24a858a457a4">legalizeFPTOUI</a> (MachineInstr &amp;MI, MachineRegisterInfo &amp;MRI, LegalizerHelper &amp;Helper) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bde26186e79c6b50ff4bd0a5071dc4b">legalizeUITOFP</a> (MachineInstr &amp;MI, MachineRegisterInfo &amp;MRI, LegalizerHelper &amp;Helper) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afac22057da1c5adf4dfc0ba7c2864b09">Subtarget</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep a reference to the <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> around so that we can make the right decision when generating code for different targets. <a href="#afac22057da1c5adf4dfc0ba7c2864b09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86legalizerinfo-h">X86LegalizerInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86LegalizerInfo() {#abfc562c1c7aebc23222627fa24d11df5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86LegalizerInfo::X86LegalizerInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine">X86TargetMachine</a> &amp; TM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86legalizerinfo-h">X86LegalizerInfo.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86legalizerinfo-cpp">X86LegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a3b9d49f459b9596f73c60edab6e92673">llvm::LegalizeRuleSet::clampMaxNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a3da19f78bfc264962a18568ea4b8d6c7">llvm::LegalizeRuleSet::clampMinNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#ac56e6d7519b8f4f908174aa570bc5e61">llvm::LegalizeRuleSet::clampNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a7adc16cc9bc8db5fd3c8a6798a846ab0">llvm::LegalizeRuleSet::clampScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/legacylegalizerinfo/#a6b586580f1e35e04ae0f3186fadd6594">llvm::LegacyLegalizerInfo::computeTables</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#acda429561493e08ee5cef54f26a1224c">llvm::LegalizeRuleSet::customIf</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#a32539827696dafee94ee79c3321b4245">llvm::LegalizerInfo::getActionDefinitionsBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#a82994a7f16673e2aaf534c7d111ba3a8">llvm::X86Subtarget::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#a33b434e9218db992447f811551810394">llvm::LegalizerInfo::getLegacyLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a1c27c69ac65f9d4937858c10288a17f6">llvm::LegalizeRuleSet::legalFor</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#ae4c02bcf9d3bfdee70f097d0b6aeb9f3">llvm::LegalizeRuleSet::legalForCartesianProduct</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#af6dcfac5a30e4050e3ac204f27062fe6">llvm::LegalizeRuleSet::legalIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/hwaddresssanitizer-cpp/#aeaa43ab635ee98b9e2055d0f217558c2ad9dbfb96b7805fecf168bf553c423cce">libcall</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a31342428708a575fd8ed06209949d9dc">llvm::LegalizeRuleSet::libcall</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a6a836d4faf3f9f04f1f04cc5f6de3c03">llvm::LegalizeRuleSet::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a009564405d1037574152ee039cd04b9f">llvm::LegalizeRuleSet::minScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a592ea5db9394c272d8354d931134f16c">llvm::LegalizeRuleSet::moreElementsToNextPow2</a>, <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#afd4ab894cdbdc5888a2d10fa5e5f8333">llvm::LegalityQuery::Opcode</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7ff0361855acbbe71b15b8dc6003fbc5">llvm::LLT::pointer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#adf80c6b70ec078f749c51a5e64b4393d">llvm::LegalizeRuleSet::scalarize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#aff9e886f18a84258e4f794e31aad0bd9">llvm::LegalityPredicates::scalarNarrowerThan</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a236c4562fff94fbec23fd35c0b5257a1">llvm::LegalizeRuleSet::scalarSameSizeAs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#a3b65801c5b31890a1d1cd8a0038aee87">llvm::LegalityPredicates::typeInSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#ae56d6ae68f8659cfaa29fb7cb601f111">llvm::LegalityPredicates::typeIs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#a5d6273cfdaa9c2379ffe7205c2104776">llvm::LegalityPredicates::typePairInSet</a>, <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#ab28fca6f8145be28b70ad89bb0c741b0">llvm::LegalityQuery::Types</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp/#a593cc2f204f7b2edc16ee222c37c3196">verify</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#adef498f01eb5d7c19ac40cd3b302d09e">llvm::LegalizeRuleSet::widenScalarToNextPow2</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### legalizeCustom() {#a088615ef5bf315b474c43859307730ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86LegalizerInfo::legalizeCustom (<a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/lostdebuglocobserver">LostDebugLocObserver</a> &amp; LocObserver)</td>
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

<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86legalizerinfo-h">X86LegalizerInfo.h</a>, definition at line 639 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86legalizerinfo-cpp">X86LegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad7322f56c0659b8dc8e55567767b74d6">llvm::MachineIRBuilder::getMRI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae50d11fc026093629c27142780ff1405">llvm::LegalizerHelper::MIRBuilder</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### legalizeIntrinsic() {#a2d2c4c47a7326cd903beda3b760d057a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86LegalizerInfo::legalizeIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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


<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86legalizerinfo-h">X86LegalizerInfo.h</a>, definition at line 747 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86legalizerinfo-cpp">X86LegalizerInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### legalizeBuildVector() {#a095181d71278ac793e6d1819fa7595ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86LegalizerInfo::legalizeBuildVector (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86legalizerinfo-h">X86LegalizerInfo.h</a>, definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86legalizerinfo-cpp">X86LegalizerInfo.cpp</a>.</p>

</div>
</div>

### legalizeFPTOUI() {#a85086789e4f81c2ff47c24a858a457a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86LegalizerInfo::legalizeFPTOUI (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86legalizerinfo-h">X86LegalizerInfo.h</a>, definition at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86legalizerinfo-cpp">X86LegalizerInfo.cpp</a>.</p>

</div>
</div>

### legalizeUITOFP() {#a2bde26186e79c6b50ff4bd0a5071dc4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86LegalizerInfo::legalizeUITOFP (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86legalizerinfo-h">X86LegalizerInfo.h</a>, definition at line 728 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86legalizerinfo-cpp">X86LegalizerInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Subtarget {#afac22057da1c5adf4dfc0ba7c2864b09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86Subtarget&amp; llvm::X86LegalizerInfo::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep a reference to the <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> around so that we can make the right decision when generating code for different targets.</p>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86legalizerinfo-h">X86LegalizerInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86legalizerinfo-cpp">X86LegalizerInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86legalizerinfo-h">X86LegalizerInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
