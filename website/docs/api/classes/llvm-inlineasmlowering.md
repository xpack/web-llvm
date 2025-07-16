---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/inlineasmlowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InlineAsmLowering` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::InlineAsmLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/inlineasmlowering-h">llvm/CodeGen/GlobalISel/InlineAsmLowering.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/spirvinlineasmlowering">SPIRVInlineAsmLowering</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cfd4dc7278effd0cb32a67eccbdb209">InlineAsmLowering</a> (const TargetLowering *TLI)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a0fe38a8e54a1493431280a57c5ada7">~InlineAsmLowering</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c9cd272afbe2a9aaca46369f9e61b79">lowerInlineAsm</a> (MachineIRBuilder &amp;MIRBuilder, const CallBase &amp;CB, std::function&lt; ArrayRef&lt; Register &gt;(const Value &amp;Val)&gt; GetOrCreateVRegs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower the given inline asm call instruction <span class="doxyComputerOutput">GetOrCreateVRegs</span> is a callback to materialize a register for the input and output operands of the inline asm. <a href="#a1c9cd272afbe2a9aaca46369f9e61b79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaff9002688c9185afc9e8b0e2a46f88">lowerAsmOperandForConstraint</a> (Value *Val, StringRef Constraint, std::vector&lt; MachineOperand &gt; &amp;Ops, MachineIRBuilder &amp;MIRBuilder) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower the specified operand into the Ops vector. <a href="#adaff9002688c9185afc9e8b0e2a46f88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17ad589f929523164d12cf6a30b02b52">getTLI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Getter for generic <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> class. <a href="#a17ad589f929523164d12cf6a30b02b52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class XXXTargetLowering&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> XXXTargetLowering *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6bd0333cf865a06c6e95f51e8d093ff9">getTLI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Getter for target specific <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> class. <a href="#a6bd0333cf865a06c6e95f51e8d093ff9">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51b787edc3410c94eaeb1bad2f32d336">anchor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a422d61af7a6b96e0e427bcf54cb834e7">TLI</a></td>
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


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/inlineasmlowering-h">InlineAsmLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InlineAsmLowering() {#a1cfd4dc7278effd0cb32a67eccbdb209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InlineAsmLowering::InlineAsmLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> * TLI)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/inlineasmlowering-h">InlineAsmLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvinlineasmlowering/#a7bff83f3bdee4b93241fd27cf15d3c1c">llvm::SPIRVInlineAsmLowering::SPIRVInlineAsmLowering</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~InlineAsmLowering() {#a4a0fe38a8e54a1493431280a57c5ada7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::InlineAsmLowering::~InlineAsmLowering ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/inlineasmlowering-h">InlineAsmLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### lowerAsmOperandForConstraint() {#adaff9002688c9185afc9e8b0e2a46f88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InlineAsmLowering::lowerAsmOperandForConstraint (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Ops, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
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

<p>Lower the specified operand into the Ops vector.</p>


<p><span class="doxyComputerOutput">Val</span> is the IR input value to be lowered <span class="doxyComputerOutput">Constraint</span> is the user supplied constraint string <span class="doxyComputerOutput">Ops</span> is the vector to be filled with the lowered operands</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the lowering succeeds, false otherwise.</p></dd>
</dl>


<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/inlineasmlowering-h">InlineAsmLowering.h</a>, definition at line 623 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp">InlineAsmLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvinlineasmlowering/#ad76d409865bd147da020b46aa7525013">llvm::SPIRVInlineAsmLowering::lowerAsmOperandForConstraint</a> and <a href="#a1c9cd272afbe2a9aaca46369f9e61b79">lowerInlineAsm</a>.</p>

</div>
</div>

### lowerInlineAsm() {#a1c9cd272afbe2a9aaca46369f9e61b79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InlineAsmLowering::lowerInlineAsm (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp;Val)&gt; GetOrCreateVRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower the given inline asm call instruction <span class="doxyComputerOutput">GetOrCreateVRegs</span> is a callback to materialize a register for the input and output operands of the inline asm.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the lowering succeeds, false otherwise.</p></dd>
</dl>


<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/inlineasmlowering-h">InlineAsmLowering.h</a>, definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp">InlineAsmLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a30a1feca92679c24a46b0b824a6de269">llvm::MachineInstrBuilder::addExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#af5f0f04b137494bbf8fb56286dea2762">buildAnyextOrCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ae32b6e2213ad3119a124e6e0673a5898">llvm::MachineIRBuilder::buildCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ae04499daa8807ddb4d00e7ed18b1698f">llvm::MachineIRBuilder::buildInstrNoInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#abf1763199cd36c9253c6f062fa5e973e">llvm::MachineIRBuilder::buildTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116abd588753884964e239e61d80ebc2f039">llvm::TargetLowering::C_Address</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116a7bc0fe0fa6be5eaabb77e46c8d9ab2c8">llvm::TargetLowering::C_Immediate</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116a420d729d2e7d056ec884c094ccdc4467">llvm::TargetLowering::C_Memory</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116abc9c279d343d2f957ab51b37ff39e88e">llvm::TargetLowering::C_Other</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116a85f9b8131f0608c03c58e4e23d875dfc">llvm::TargetLowering::C_Register</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116a1d7718fd43ac0a5c715686a76f9cfd89">llvm::TargetLowering::C_RegisterClass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116ad4cd486b7360ed34c9553b6c9056b764">llvm::TargetLowering::C_Unknown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94ac50132234eb8c934e71b7f2f0fa5099c">llvm::InlineAsm::Clobber</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#ace43e7f4b3e0e3d46309ffaf8eb07208">computeConstraintToUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5acf55f329675ba5045a4863c7a018209b">llvm::RegState::EarlyClobber</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a32a8b65536822d50171455a6baa81da7">llvm::TargetRegisterClass::getID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a664166c0f38130d62cc5de72934946ae">llvm::getImplRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad7322f56c0659b8dc8e55567767b74d6">llvm::MachineIRBuilder::getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a432824f0975bb863478bf4ef3a5df258">llvm::MachineInstr::getNumOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#a3fc2ba502a3f669f32b52c06c2bae498">getNumOpRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#a43762e6a22fd0e7b98b8115946fc87b6">getRegistersForValue</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94ada9470e1aa5be1858e667318254dcb4b">llvm::InlineAsm::Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a833922eca2ad0eab70573ba1f5fba9af">llvm::RegState::ImplicitDefine</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a06dc2f24e1f4dea357bf6c646f5b2607">llvm::MachineIRBuilder::insertInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a511f48809ad14f13e50b957a137a9d34adf39e7f7e158f2ccacae6d4446197322">llvm::InlineAsm::isClobber</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a511f48809ad14f13e50b957a137a9d34a79ca3881430605a6c7da5227cfb115d6">llvm::InlineAsm::isInput</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a511f48809ad14f13e50b957a137a9d34a2903cfed1fe44719f76b46abcac40955">llvm::InlineAsm::isLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/flag/#a637e8098e756e55d2aba0a6f41adbd2f">llvm::InlineAsm::Flag::isMemKind</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a511f48809ad14f13e50b957a137a9d34aabfa616f81b4833fdf462b07aabfa53f">llvm::InlineAsm::isOutput</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/flag/#ade52bc57cc65e30baccebb56b76ec13a">llvm::InlineAsm::Flag::isRegDefEarlyClobberKind</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/flag/#afcdcd14f56fb520a400bc05c39078384">llvm::InlineAsm::Flag::isRegDefKind</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5f6edc5246188225b3f49bd5c974c759">llvm::Type::isSingleValueType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#adaff9002688c9185afc9e8b0e2a46f88">lowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94adba5553473d129a7985fb532dc249ff4">llvm::InlineAsm::Mem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9cacdf8ff962c6163eb5fae1f9b2fb5142a">llvm::LLVMContext::OB_convergencectrl</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94a1fbd4693daf9a506101ec4cd36caa8dd">llvm::InlineAsm::RegDef</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94adda36cdb69635bdfb9f3d925753dc2d3">llvm::InlineAsm::RegDefEarlyClobber</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94a4ac13b7b2bba42947e897ffdf8797788">llvm::InlineAsm::RegUse</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/flag/#a8a3a4a2d14c39019e5cd648081a33419">llvm::InlineAsm::Flag::setMatchingOp</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/flag/#a8de6bf65ca1443186731a3391c02d1f9">llvm::InlineAsm::Flag::setMemConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a88183b946cc5f0e8c96b2e66e1c74a7e">llvm::InlineAsm::Unknown</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getTLI() {#a17ad589f929523164d12cf6a30b02b52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLowering * llvm::InlineAsmLowering::getTLI ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Getter for generic <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> class.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/inlineasmlowering-h">InlineAsmLowering.h</a>.</p>

</div>
</div>

### getTLI() {#a6bd0333cf865a06c6e95f51e8d093ff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class XXXTargetLowering&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const XXXTargetLowering * llvm::InlineAsmLowering::getTLI ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Getter for target specific <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> class.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/inlineasmlowering-h">InlineAsmLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a51b787edc3410c94eaeb1bad2f32d336}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InlineAsmLowering::anchor ()</td>
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



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/inlineasmlowering-h">InlineAsmLowering.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp">InlineAsmLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### TLI {#a422d61af7a6b96e0e427bcf54cb834e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLowering* llvm::InlineAsmLowering::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/inlineasmlowering-h">InlineAsmLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/inlineasmlowering-h">InlineAsmLowering.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp">InlineAsmLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
