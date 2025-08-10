---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mipslegalizerinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MipsLegalizerInfo` Class

<p>This class provides legalization strategies. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MipsLegalizerInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-h">Target/Mips/MipsLegalizerInfo.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63e981ba0042fbfdd3857f66c82d8d28">MipsLegalizerInfo</a> (const MipsSubtarget &amp;ST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a867592b1a0963211ea415ea436a976e5">legalizeCustom</a> (LegalizerHelper &amp;Helper, MachineInstr &amp;MI, LostDebugLocObserver &amp;LocObserver) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called for instructions with the Custom LegalizationAction. <a href="#a867592b1a0963211ea415ea436a976e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabf8e09177e2ae41bc06eb1f2be342e8">legalizeIntrinsic</a> (LegalizerHelper &amp;Helper, MachineInstr &amp;MI) const override</td>
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

<p>This class provides legalization strategies.</p>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-h">MipsLegalizerInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MipsLegalizerInfo() {#a63e981ba0042fbfdd3857f66c82d8d28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsLegalizerInfo::MipsLegalizerInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget">MipsSubtarget</a> &amp; ST)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-h">MipsLegalizerInfo.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp">MipsLegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp/#a093c9466dbe02fe43ee439cda932a7f4">CheckTy0Ty1MemSizeAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp/#a3a0fb4a3768823cf9aaeff9fa81ec04e">CheckTyN</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a7adc16cc9bc8db5fd3c8a6798a846ab0">llvm::LegalizeRuleSet::clampScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/legacylegalizerinfo/#a6b586580f1e35e04ae0f3186fadd6594">llvm::LegacyLegalizerInfo::computeTables</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#a32539827696dafee94ee79c3321b4245">llvm::LegalizerInfo::getActionDefinitionsBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#a33b434e9218db992447f811551810394">llvm::LegalizerInfo::getLegacyLegalizerInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a434f6a0d80fb13e4326e848a6391f057">llvm::isPowerOf2_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp/#acc8ea22f5c74783a28d81a02e2d95e75">isUnalignedMemmoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a1c27c69ac65f9d4937858c10288a17f6">llvm::LegalizeRuleSet::legalFor</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#ae4c02bcf9d3bfdee70f097d0b6aeb9f3">llvm::LegalizeRuleSet::legalForCartesianProduct</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#af6dcfac5a30e4050e3ac204f27062fe6">llvm::LegalizeRuleSet::legalIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/hwaddresssanitizer-cpp/#aeaa43ab635ee98b9e2055d0f217558c2ad9dbfb96b7805fecf168bf553c423cce">libcall</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a32e4ff098c95890246047dc1ddf5a065">llvm::LegalizeRuleSet::libcallFor</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a40aebefc69962dcb020706b2829e0159">llvm::LegalizeRuleSet::libcallForCartesianProduct</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a6a836d4faf3f9f04f1f04cc5f6de3c03">llvm::LegalizeRuleSet::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a6eec582df34bb1c63e8666b41ff561ec">llvm::LegalizeRuleSet::lowerFor</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a33e181da566d1ebb7556f172888c3b92">llvm::LegalizeRuleSet::maxScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a009564405d1037574152ee039cd04b9f">llvm::LegalizeRuleSet::minScalar</a>, <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#a9e26ab57991dfde2757e4790a626d6a3">llvm::LegalityQuery::MMODescrs</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7ff0361855acbbe71b15b8dc6003fbc5">llvm::LLT::pointer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#ab28fca6f8145be28b70ad89bb0c741b0">llvm::LegalityQuery::Types</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp/#a593cc2f204f7b2edc16ee222c37c3196">verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### legalizeCustom() {#a867592b1a0963211ea415ea436a976e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsLegalizerInfo::legalizeCustom (<a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/lostdebuglocobserver">LostDebugLocObserver</a> &amp; LocObserver)</td>
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

<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-h">MipsLegalizerInfo.h</a>, definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp">MipsLegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#acac15566596b1d588d87450ab77bf0d7">llvm::MachineIRBuilder::buildAnyExt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af751c28a69e1d07e19dad11e4e26a70d">llvm::MachineIRBuilder::buildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a81a7959d3e7f624343ecdf6905e251dd">llvm::MachineIRBuilder::buildFConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad84b765997ad4d3bb1ca3e9393d70ab8">llvm::MachineIRBuilder::buildFPTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a02d0daf870f6458a98b61f4b82a399c3">llvm::MachineIRBuilder::buildFSub</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a7962eca94c9f77da448245745fb22f57">llvm::MachineIRBuilder::buildLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a3e17399c568f784acb8ebf8be9a558ec">llvm::MachineIRBuilder::buildLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a7075ef788cb3dea0ea239c1a6830734c">llvm::MachineIRBuilder::buildMergeLikeInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a7aae2634e3c0980c4f68983738b90ff7">llvm::MachineIRBuilder::buildPtrAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a87a7405685118d45876c996318829ceb">llvm::MachineIRBuilder::buildStore</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#abf1763199cd36c9253c6f062fa5e973e">llvm::MachineIRBuilder::buildTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a1e9e055fc19307bc3c7c1be6ccd36812">llvm::MachineIRBuilder::buildUnmerge</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad7322f56c0659b8dc8e55567767b74d6">llvm::MachineIRBuilder::getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a1c5fadb14ff1d77faad0cb58a43252ab">llvm::MachineInstrBuilder::getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a434f6a0d80fb13e4326e848a6391f057">llvm::isPowerOf2_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600clausemergepass-cpp/#aba99928790de45fa7aa12b47fbd828ff">Merge</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae50d11fc026093629c27142780ff1405">llvm::LegalizerHelper::MIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### legalizeIntrinsic() {#aabf8e09177e2ae41bc06eb1f2be342e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsLegalizerInfo::legalizeIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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


<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-h">MipsLegalizerInfo.h</a>, definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp">MipsLegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a7962eca94c9f77da448245745fb22f57">llvm::MachineIRBuilder::buildLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a87a7405685118d45876c996318829ceb">llvm::MachineIRBuilder::buildStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a62766c75f88612ffa652342472e755f6">getIntrinsicID</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae50d11fc026093629c27142780ff1405">llvm::LegalizerHelper::MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp/#a606d158739fd7cd13395bd7db9fc3e36">MSA2OpIntrinsicToGeneric</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp/#ad90722edae1f87193dcefae806cae4b8">MSA3OpIntrinsicToGeneric</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7ff0361855acbbe71b15b8dc6003fbc5">llvm::LLT::pointer</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp/#a8a476245face103d65c519250257e499">SelectMSA3OpIntrinsic</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp">MipsLegalizerInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-h">MipsLegalizerInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
