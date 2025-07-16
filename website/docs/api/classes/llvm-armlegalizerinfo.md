---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/armlegalizerinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ARMLegalizerInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::ARMLegalizerInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlegalizerinfo-h">Target/ARM/ARMLegalizerInfo.h</a>"
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa67704ba0630b91c0b5151a880015ea6">FCmpLibcallsList</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; FCmpLibcallInfo, 2 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3675ceb077be1a33d41f3fea633e96eb">FCmpLibcallsMapTy</a> = <a href="/web-llvm/docs/api/classes/llvm/indexedmap">IndexedMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">FCmpLibcallsList</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c94d0f4f62bd71d26a8020faf70b9f0">ARMLegalizerInfo</a> (const ARMSubtarget &amp;ST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aeed55e4456de4086b3592eb92dc2e2">legalizeCustom</a> (LegalizerHelper &amp;Helper, MachineInstr &amp;MI, LostDebugLocObserver &amp;LocObserver) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called for instructions with the Custom LegalizationAction. <a href="#a2aeed55e4456de4086b3592eb92dc2e2">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab15da55431d9f3bfb4761c1ae274c0db">setFCmpLibcallsGNU</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5975e36e05ec7415b45ffe7b6fe762b">setFCmpLibcallsAEABI</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">FCmpLibcallsList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee742fbbc7d1357ed2b7176e3983aeb8">getFCmpLibcalls</a> (CmpInst::Predicate, unsigned Size) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/indexedmap">FCmpLibcallsMapTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4265751d61428d075c0519d23173df39">FCmp32Libcalls</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/indexedmap">FCmpLibcallsMapTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a796be13bcbc94a5318222129691fe8fd">FCmp64Libcalls</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d51822b33b5ab724d57fc313bc649af">ST</a></td>
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


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlegalizerinfo-h">ARMLegalizerInfo.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### FCmpLibcallsList {#aa67704ba0630b91c0b5151a880015ea6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ARMLegalizerInfo::FCmpLibcallsList =  SmallVector&lt;FCmpLibcallInfo, 2&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlegalizerinfo-h">ARMLegalizerInfo.h</a>.</p>

</div>
</div>

### FCmpLibcallsMapTy {#a3675ceb077be1a33d41f3fea633e96eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ARMLegalizerInfo::FCmpLibcallsMapTy =  IndexedMap&lt;FCmpLibcallsList&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlegalizerinfo-h">ARMLegalizerInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ARMLegalizerInfo() {#a0c94d0f4f62bd71d26a8020faf70b9f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMLegalizerInfo::ARMLegalizerInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> &amp; ST)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlegalizerinfo-h">ARMLegalizerInfo.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlegalizerinfo-cpp">ARMLegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlegalizerinfo-cpp/#ac46ca27d7fa69cdd70bfffee2d1ef422">AEABI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#ab250f5144d04471b35f7fc229dc9da5c">llvm::LegalizeRuleSet::alwaysLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a7adc16cc9bc8db5fd3c8a6798a846ab0">llvm::LegalizeRuleSet::clampScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a80f41417117f537cd147aaee97aecb1e">llvm::LegalizeRuleSet::custom</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#afc001d042e6a7093a6954b2d9ff18029">llvm::LegalizeRuleSet::customFor</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a4ad690ef8db6cd914cef1b3aa39bc15f">llvm::LegalizeRuleSet::customForCartesianProduct</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#a32539827696dafee94ee79c3321b4245">llvm::LegalizerInfo::getActionDefinitionsBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#a33b434e9218db992447f811551810394">llvm::LegalizerInfo::getLegacyLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a1c27c69ac65f9d4937858c10288a17f6">llvm::LegalizeRuleSet::legalFor</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#ae4c02bcf9d3bfdee70f097d0b6aeb9f3">llvm::LegalizeRuleSet::legalForCartesianProduct</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#aebb3b5876088ebfd2d003d68f7fb4b07">llvm::LegalizeRuleSet::legalForTypesWithMemDesc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/hwaddresssanitizer-cpp/#aeaa43ab635ee98b9e2055d0f217558c2ad9dbfb96b7805fecf168bf553c423cce">libcall</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a32e4ff098c95890246047dc1ddf5a065">llvm::LegalizeRuleSet::libcallFor</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a6a836d4faf3f9f04f1f04cc5f6de3c03">llvm::LegalizeRuleSet::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a6eec582df34bb1c63e8666b41ff561ec">llvm::LegalizeRuleSet::lowerFor</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a33e181da566d1ebb7556f172888c3b92">llvm::LegalizeRuleSet::maxScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7ff0361855acbbe71b15b8dc6003fbc5">llvm::LLT::pointer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp/#a593cc2f204f7b2edc16ee222c37c3196">verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### legalizeCustom() {#a2aeed55e4456de4086b3592eb92dc2e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMLegalizerInfo::legalizeCustom (<a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/lostdebuglocobserver">LostDebugLocObserver</a> &amp; LocObserver)</td>
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

<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlegalizerinfo-h">ARMLegalizerInfo.h</a>, definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlegalizerinfo-cpp">ARMLegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba07aee43ffb66908a25c55c77ce4c0d05">llvm::CmpInst::BAD_ICMP_PREDICATE</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a33eb6083767372c564ea4bcf6c06eaf1">llvm::MachineIRBuilder::buildAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af751c28a69e1d07e19dad11e4e26a70d">llvm::MachineIRBuilder::buildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ac69ef19d33fd455e8684cb53be2e46bb">llvm::MachineIRBuilder::buildGetFPEnv</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a3a618c7b84d45b5e188f6a7e4305ee39">llvm::MachineIRBuilder::buildICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad93e8a9d68a578f6a53c70d39aef0dbe">llvm::MachineIRBuilder::buildOr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#afc7eb07b74fdeb50e151b325880fd51d">llvm::MachineIRBuilder::buildSetFPEnv</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#abf1763199cd36c9253c6f062fa5e973e">llvm::MachineIRBuilder::buildTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aabff304f51525ece8028bf8e9b1c3614">llvm::ConstantMaterializationCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8829536a23c01dcd3a6017dccb148c90">llvm::createLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bae9c013750fff3023001d7e3af8df2d6d">llvm::CmpInst::FCMP_FALSE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba0a33c71e3c5e8f128ca47539a85962f5">llvm::CmpInst::FCMP_TRUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a877b4068130202e03dc283f3a6b70096">llvm::ARM::FPReservedBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a4715574e6e313707f118a156314bcb41">llvm::ARM::FPStatusBits</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a18fc4545474c6ebb6f7c547f64f4fb31">llvm::StructType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acb145f988329d1d621f73abcafea21d8">llvm::Type::getDoubleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ad5e0fe0efdd88f98a5b5eb512d5351c2">llvm::Type::getFloatTy</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad7322f56c0659b8dc8e55567767b74d6">llvm::MachineIRBuilder::getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#ac09a21c371a9c535cbc13e8f82503aec">llvm::ConstantInt::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#ad8c2100cae3093d71e65a48908158e22">llvm::CmpInst::isIntPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">llvm::LegalizerHelper::Legalized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654a1e5ed9cc15d3744694855efcdf0b948e">llvm::LegalizeActions::Libcall</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aefeacc46707017018d95faf6751da717">llvm::LegalizerHelper::lowerConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae50d11fc026093629c27142780ff1405">llvm::LegalizerHelper::MIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a7e344cff0feadf0b02223fee63cc7475">Results</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getFCmpLibcalls() {#aee742fbbc7d1357ed2b7176e3983aeb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMLegalizerInfo::FCmpLibcallsList ARMLegalizerInfo::getFCmpLibcalls (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Predicate, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlegalizerinfo-h">ARMLegalizerInfo.h</a>, definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlegalizerinfo-cpp">ARMLegalizerInfo.cpp</a>.</p>

</div>
</div>

### setFCmpLibcallsAEABI() {#ad5975e36e05ec7415b45ffe7b6fe762b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMLegalizerInfo::setFCmpLibcallsAEABI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlegalizerinfo-h">ARMLegalizerInfo.h</a>, definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlegalizerinfo-cpp">ARMLegalizerInfo.cpp</a>.</p>

</div>
</div>

### setFCmpLibcallsGNU() {#ab15da55431d9f3bfb4761c1ae274c0db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMLegalizerInfo::setFCmpLibcallsGNU ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlegalizerinfo-h">ARMLegalizerInfo.h</a>, definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlegalizerinfo-cpp">ARMLegalizerInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FCmp32Libcalls {#a4265751d61428d075c0519d23173df39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FCmpLibcallsMapTy llvm::ARMLegalizerInfo::FCmp32Libcalls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlegalizerinfo-h">ARMLegalizerInfo.h</a>.</p>

</div>
</div>

### FCmp64Libcalls {#a796be13bcbc94a5318222129691fe8fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FCmpLibcallsMapTy llvm::ARMLegalizerInfo::FCmp64Libcalls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlegalizerinfo-h">ARMLegalizerInfo.h</a>.</p>

</div>
</div>

### ST {#a8d51822b33b5ab724d57fc313bc649af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ARMSubtarget&amp; llvm::ARMLegalizerInfo::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlegalizerinfo-h">ARMLegalizerInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlegalizerinfo-cpp">ARMLegalizerInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlegalizerinfo-h">ARMLegalizerInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
