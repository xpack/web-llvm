---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-cskyiseldagtodag-cpp-/cskydagtodagisel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CSKYDAGToDAGISel` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{CSKYISelDAGToDAG.cpp}::CSKYDAGToDAGISel { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/selectiondagisel">SelectionDAGISel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/selectiondagisel">SelectionDAGISel</a> - This is the common base class used for SelectionDAG-based pattern-matching instruction selectors. <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f4ef6ecc569556e34e0c551da750b09">CSKYDAGToDAGISel</a> (CSKYTargetMachine &amp;TM, CodeGenOptLevel OptLevel)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8555a3ae5f7ef608c20969be516565b0">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a02f0891dd438323dc928dcef5081af">Select</a> (SDNode *N) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Main hook for targets to transform nodes into machine nodes. <a href="#a0a02f0891dd438323dc928dcef5081af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75b8d8ea2b3a98a9bae9ec623007b6a0">selectAddCarry</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc422f6987f0ad82fa646f7f9535fb0b">selectSubCarry</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bfa88a11c5200afad352e7881d20c6d">selectBITCAST_TO_LOHI</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0b3de3815c7ba67bd6b19ef08ac9f1c">selectInlineAsm</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29fd915dc7f0b0871a8cfb22987ac5f4">createGPRPairNode</a> (EVT VT, SDValue V0, SDValue V1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af27832a6378a032f0032df0b066bb55b">SelectInlineAsmMemoryOperand</a> (const SDValue &amp;Op, InlineAsm::ConstraintCode ConstraintID, std::vector&lt; SDValue &gt; &amp;OutOps) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectInlineAsmMemoryOperand - Select the specified address as a target addressing mode, according to the specified constraint. <a href="#af27832a6378a032f0032df0b066bb55b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cskysubtarget">CSKYSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9dd64fbeaee229d89b035350025c0a8">Subtarget</a></td>
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


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyiseldagtodag-cpp">CSKYISelDAGToDAG.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CSKYDAGToDAGISel() {#a3f4ef6ecc569556e34e0c551da750b09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CSKYISelDAGToDAG.cpp}::CSKYDAGToDAGISel::CSKYDAGToDAGISel (<a href="/web-llvm/docs/api/classes/llvm/cskytargetmachine">CSKYTargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OptLevel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyiseldagtodag-cpp">CSKYISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a5386ceeb71599848944185c0035e0e94">llvm::SelectionDAGISel::OptLevel</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#aeac54a65abd3a93279e58b0f474028fc">llvm::SelectionDAGISel::SelectionDAGISel</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a0ead78650333eefc4d5591ca3db9ed4b">llvm::SelectionDAGISel::TM</a>.</p>


<p>Referenced by <a href="#a0a02f0891dd438323dc928dcef5081af">Select</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createGPRPairNode() {#a29fd915dc7f0b0871a8cfb22987ac5f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode * CSKYDAGToDAGISel::createGPRPairNode (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> V0, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> V1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyiseldagtodag-cpp">CSKYISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a> and <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>.</p>


<p>Referenced by <a href="#aa0b3de3815c7ba67bd6b19ef08ac9f1c">selectInlineAsm</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a8555a3ae5f7ef608c20969be516565b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYISelDAGToDAG.cpp}::CSKYDAGToDAGISel::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyiseldagtodag-cpp">CSKYISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a23107e32342f5488a5edfa71aff54700">llvm::SelectionDAGISel::MF</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a>.</p>

</div>
</div>

### Select() {#a0a02f0891dd438323dc928dcef5081af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSKYDAGToDAGISel::Select (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>Main hook for targets to transform nodes into machine nodes.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyiseldagtodag-cpp">CSKYISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/cskyisd/#a21f8f5032143364eef7e557f383ca140aff2113c0522ec629cd8d711fdcc45497">llvm::CSKYISD::BITCAST_TO_LOHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a3f4ef6ecc569556e34e0c551da750b09">CSKYDAGToDAGISel</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4b437632fd9b97dd36010d85eb363efe">llvm::ISD::FrameIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaef4ead62e1835b863820f6c818c36ac">llvm::ISD::GLOBAL_OFFSET_TABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae35d57f3c020672748fcc95607348986">llvm::ISD::INLINEASM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab969e7d43eb37a0398b5ded23bccc136">llvm::ISD::INLINEASM_BR</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a23107e32342f5488a5edfa71aff54700">llvm::SelectionDAGISel::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#acd1bcf7bcbb18b94234b2bf5a505e925">llvm::SelectionDAGISel::ReplaceNode</a>, <a href="#a0a02f0891dd438323dc928dcef5081af">Select</a>, <a href="#a75b8d8ea2b3a98a9bae9ec623007b6a0">selectAddCarry</a>, <a href="#a5bfa88a11c5200afad352e7881d20c6d">selectBITCAST_TO_LOHI</a>, <a href="#aa0b3de3815c7ba67bd6b19ef08ac9f1c">selectInlineAsm</a>, <a href="#adc422f6987f0ad82fa646f7f9535fb0b">selectSubCarry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0f1e3ed26108fec69eb97209c0e39bf">llvm::ISD::UADDO_CARRY</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac81ebcd59d629d8680e50ffba9855255">llvm::ISD::USUBO_CARRY</a>.</p>


<p>Referenced by <a href="#a0a02f0891dd438323dc928dcef5081af">Select</a>.</p>

</div>
</div>

### selectAddCarry() {#a75b8d8ea2b3a98a9bae9ec623007b6a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYDAGToDAGISel::selectAddCarry (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyiseldagtodag-cpp">CSKYISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a86775f3d85d98a31b2751e1eb348ea">llvm::isNullConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac926ae0b6871c2207db3e787f6dbcb80">llvm::isOneConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#acd1bcf7bcbb18b94234b2bf5a505e925">llvm::SelectionDAGISel::ReplaceNode</a>.</p>


<p>Referenced by <a href="#a0a02f0891dd438323dc928dcef5081af">Select</a>.</p>

</div>
</div>

### selectBITCAST\_TO\_LOHI() {#a5bfa88a11c5200afad352e7881d20c6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYDAGToDAGISel::selectBITCAST_TO_LOHI (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyiseldagtodag-cpp">CSKYISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a84e771c0f56c984d8ee4a85c0cb46ed3">llvm::SelectionDAGISel::ReplaceUses</a>.</p>


<p>Referenced by <a href="#a0a02f0891dd438323dc928dcef5081af">Select</a>.</p>

</div>
</div>

### selectInlineAsm() {#aa0b3de3815c7ba67bd6b19ef08ac9f1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYDAGToDAGISel::selectInlineAsm (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyiseldagtodag-cpp">CSKYISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a29fd915dc7f0b0871a8cfb22987ac5f4">createGPRPairNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a23107e32342f5488a5edfa71aff54700">llvm::SelectionDAGISel::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#aee6bd1fd282469b3476efce4b707f09a">llvm::SDNode::op_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ae499cc99d4fe44d343ca9ac6a2ae8845">llvm::SDNode::op_end</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370afed51603ce2d64ec9af92ff0154913ca">llvm::InlineAsm::Op_FirstOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370a561c23f9fc6d8fe79f70cebf74937b30">llvm::InlineAsm::Op_InputChain</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#acd1bcf7bcbb18b94234b2bf5a505e925">llvm::SelectionDAGISel::ReplaceNode</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a0a02f0891dd438323dc928dcef5081af">Select</a>.</p>

</div>
</div>

### SelectInlineAsmMemoryOperand() {#af27832a6378a032f0032df0b066bb55b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYDAGToDAGISel::SelectInlineAsmMemoryOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Op, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0">InlineAsm::ConstraintCode</a> ConstraintID, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OutOps)</td>
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

<p>SelectInlineAsmMemoryOperand - Select the specified address as a target addressing mode, according to the specified constraint.</p>


<p>If this does not match or is not implemented, return true. The resultant operands (which will appear in the machine instruction) should be added to the OutOps vector.</p>


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyiseldagtodag-cpp">CSKYISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a6f8f57715090da2632453988d9a1501b">llvm::InlineAsm::m</a>.</p>

</div>
</div>

### selectSubCarry() {#adc422f6987f0ad82fa646f7f9535fb0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYDAGToDAGISel::selectSubCarry (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyiseldagtodag-cpp">CSKYISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyiseldagtodag-cpp/#a34d1480488caf025c0962892032d46cc">InvertCarryFlag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a86775f3d85d98a31b2751e1eb348ea">llvm::isNullConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac926ae0b6871c2207db3e787f6dbcb80">llvm::isOneConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a84e771c0f56c984d8ee4a85c0cb46ed3">llvm::SelectionDAGISel::ReplaceUses</a>.</p>


<p>Referenced by <a href="#a0a02f0891dd438323dc928dcef5081af">Select</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Subtarget {#ab9dd64fbeaee229d89b035350025c0a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CSKYSubtarget* anonymous{CSKYISelDAGToDAG.cpp}::CSKYDAGToDAGISel::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyiseldagtodag-cpp">CSKYISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyiseldagtodag-cpp">CSKYISelDAGToDAG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
