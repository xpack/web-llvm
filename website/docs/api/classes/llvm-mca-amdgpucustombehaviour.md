---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mca/amdgpucustombehaviour
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AMDGPUCustomBehaviour` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::mca::AMDGPUCustomBehaviour { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">Target/AMDGPU/MCA/AMDGPUCustomBehaviour.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/custombehaviour">CustomBehaviour</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class which can be overriden by targets to enforce instruction dependencies and behaviours that aren't expressed well enough within the scheduling model for mca to automatically simulate them properly. <a href="/web-llvm/docs/api/classes/llvm/mca/custombehaviour/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c616a0039f36b38c197da02e179797b">AMDGPUCustomBehaviour</a> (const MCSubtargetInfo &amp;STI, const mca::SourceMgr &amp;SrcMgr, const MCInstrInfo &amp;MCII)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a690f1af5fe823121581fc0f21e8dd21c">~AMDGPUCustomBehaviour</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17cb5a2e79bf568a343e0beb4176cbec">checkCustomHazard</a> (ArrayRef&lt; InstRef &gt; IssuedInst, const InstRef &amp;IR) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is used to determine if an instruction should be allowed to be dispatched. <a href="#a17cb5a2e79bf568a343e0beb4176cbec">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a352f54154e8ea1de0446e8243cdc5de6">generateWaitCntInfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method gets called from the constructor and is where we setup the InstrWaitCntInfo vector. <a href="#a352f54154e8ea1de0446e8243cdc5de6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a269f1cda7a5364e40c04934a1c204698">hasModifiersSet</a> (const std::unique_ptr&lt; Instruction &gt; &amp;Inst, unsigned OpName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function used in generateWaitCntInfo() <a href="#a269f1cda7a5364e40c04934a1c204698">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd92dbe010c60f6bfc6a550e9ed65158">isGWS</a> (uint16_t Opcode) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function used in generateWaitCntInfo() <a href="#afd92dbe010c60f6bfc6a550e9ed65158">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae82b59b7c08ecf264a4bafdc58d4c8b6">isAlwaysGDS</a> (uint16_t Opcode) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function used in generateWaitCntInfo() <a href="#ae82b59b7c08ecf264a4bafdc58d4c8b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af98df5fc6c2139bb5b3994083829afc7">isVMEM</a> (const MCInstrDesc &amp;MCID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function used in generateWaitCntInfo() <a href="#af98df5fc6c2139bb5b3994083829afc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb75f007353bc54d84736c92c3942a90">handleWaitCnt</a> (ArrayRef&lt; InstRef &gt; IssuedInst, const InstRef &amp;IR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method gets called from checkCustomHazard when mca is attempting to dispatch an s_waitcnt instruction (or one of its variants). <a href="#abb75f007353bc54d84736c92c3942a90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1bd15f9c19775ad86dfba4300357780">computeWaitCnt</a> (const InstRef &amp;IR, unsigned &amp;Vmcnt, unsigned &amp;Expcnt, unsigned &amp;Lgkmcnt, unsigned &amp;Vscnt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Based on the type of s_waitcnt instruction we are looking at, and what its operands are, this method will set the values for each of the cnt references provided as arguments. <a href="#aa1bd15f9c19775ad86dfba4300357780">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/mca/waitcntinfo">WaitCntInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac288f5f70c1a88169b7979f7d4e5b493">InstrWaitCntInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whenever MCA would like to dispatch an s_waitcnt instructions, we must check all the instruction that are still executing to see if they modify the same CNT as we need to wait for. <a href="#ac288f5f70c1a88169b7979f7d4e5b493">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">AMDGPUCustomBehaviour.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AMDGPUCustomBehaviour() {#a8c616a0039f36b38c197da02e179797b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::AMDGPUCustomBehaviour::AMDGPUCustomBehaviour (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr">mca::SourceMgr</a> &amp; SrcMgr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MCII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">AMDGPUCustomBehaviour.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-cpp">AMDGPUCustomBehaviour.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mca/custombehaviour/#ad9c2ca3f16c7d9d1c6cd4a20269ba729">llvm::mca::CustomBehaviour::CustomBehaviour</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/custombehaviour/#a15a50057bc7184990fc2b2885321821b">llvm::mca::CustomBehaviour::MCII</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/custombehaviour/#a818762e038ef7ffa0d5c2bc9822961c5">llvm::mca::CustomBehaviour::SrcMgr</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/custombehaviour/#a8f327d1084786084e10242b9868cdf74">llvm::mca::CustomBehaviour::STI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AMDGPUCustomBehaviour() {#a690f1af5fe823121581fc0f21e8dd21c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::AMDGPUCustomBehaviour::~AMDGPUCustomBehaviour ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">AMDGPUCustomBehaviour.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### checkCustomHazard() {#a17cb5a2e79bf568a343e0beb4176cbec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::AMDGPUCustomBehaviour::checkCustomHazard (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &gt; IssuedInst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
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

<p>This method is used to determine if an instruction should be allowed to be dispatched.</p>


<p>The return value is how many cycles until the instruction can be dispatched. This method is called after MCA has already checked for register and hardware dependencies so this method should only implement custom behaviour and dependencies that are not picked up by MCA naturally.</p>


<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">AMDGPUCustomBehaviour.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-cpp">AMDGPUCustomBehaviour.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a14ec88574d1b1b208bfe08b6e28d3f5d">llvm::mca::InstructionBase::getOpcode</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### computeWaitCnt() {#aa1bd15f9c19775ad86dfba4300357780}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::AMDGPUCustomBehaviour::computeWaitCnt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR, unsigned &amp; Vmcnt, unsigned &amp; Expcnt, unsigned &amp; Lgkmcnt, unsigned &amp; Vscnt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Based on the type of s_waitcnt instruction we are looking at, and what its operands are, this method will set the values for each of the cnt references provided as arguments.</p>

<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">AMDGPUCustomBehaviour.h</a>, definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-cpp">AMDGPUCustomBehaviour.cpp</a>.</p>

</div>
</div>

### generateWaitCntInfo() {#a352f54154e8ea1de0446e8243cdc5de6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::AMDGPUCustomBehaviour::generateWaitCntInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method gets called from the constructor and is where we setup the InstrWaitCntInfo vector.</p>


<p>The core logic for determining which CNTs an instruction interacts with is taken from <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a3f5e55facd89c7c4e29803a545e13716">SIInsertWaitcnts::updateEventWaitcntAfter()</a>. Unfortunately, some of the logic from that function is not available to us in this scope so we conservatively end up assuming that some instructions interact with more CNTs than they do in reality.</p>


<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">AMDGPUCustomBehaviour.h</a>, definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-cpp">AMDGPUCustomBehaviour.cpp</a>.</p>

</div>
</div>

### handleWaitCnt() {#abb75f007353bc54d84736c92c3942a90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::AMDGPUCustomBehaviour::handleWaitCnt (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &gt; IssuedInst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method gets called from checkCustomHazard when mca is attempting to dispatch an s_waitcnt instruction (or one of its variants).</p>


<p>The method looks at each of the instructions that are still executing in the pipeline to determine if the waitcnt should force a wait.</p>


<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">AMDGPUCustomBehaviour.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-cpp">AMDGPUCustomBehaviour.cpp</a>.</p>

</div>
</div>

### hasModifiersSet() {#a269f1cda7a5364e40c04934a1c204698}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::AMDGPUCustomBehaviour::hasModifiersSet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instruction">Instruction</a> &gt; &amp; Inst, unsigned OpName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function used in generateWaitCntInfo()</p>

<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">AMDGPUCustomBehaviour.h</a>, definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-cpp">AMDGPUCustomBehaviour.cpp</a>.</p>

</div>
</div>

### isAlwaysGDS() {#ae82b59b7c08ecf264a4bafdc58d4c8b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::AMDGPUCustomBehaviour::isAlwaysGDS (uint16_t Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function used in generateWaitCntInfo()</p>

<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">AMDGPUCustomBehaviour.h</a>, definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-cpp">AMDGPUCustomBehaviour.cpp</a>.</p>

</div>
</div>

### isGWS() {#afd92dbe010c60f6bfc6a550e9ed65158}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::AMDGPUCustomBehaviour::isGWS (uint16_t Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function used in generateWaitCntInfo()</p>

<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">AMDGPUCustomBehaviour.h</a>, definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-cpp">AMDGPUCustomBehaviour.cpp</a>.</p>

</div>
</div>

### isVMEM() {#af98df5fc6c2139bb5b3994083829afc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::AMDGPUCustomBehaviour::isVMEM (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; MCID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function used in generateWaitCntInfo()</p>

<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">AMDGPUCustomBehaviour.h</a>, definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-cpp">AMDGPUCustomBehaviour.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### InstrWaitCntInfo {#ac288f5f70c1a88169b7979f7d4e5b493}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;WaitCntInfo&gt; llvm::mca::AMDGPUCustomBehaviour::InstrWaitCntInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whenever MCA would like to dispatch an s_waitcnt instructions, we must check all the instruction that are still executing to see if they modify the same CNT as we need to wait for.</p>


<p>This vector gets built in the constructor and contains 1 <a href="/web-llvm/docs/api/structs/llvm/mca/waitcntinfo">WaitCntInfo</a> struct for each instruction within the SrcManager. Each element tells us which CNTs that instruction may interact with. We conservatively assume some instructions interact with more CNTs than they do in reality, so we will occasionally wait longer than necessary, but we shouldn't ever wait for shorter.</p>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">AMDGPUCustomBehaviour.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-cpp">AMDGPUCustomBehaviour.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-h">AMDGPUCustomBehaviour.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
