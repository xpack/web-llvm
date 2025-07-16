---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-webassemblyiseldagtodag-cpp-/webassemblydagtodagisel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `WebAssemblyDAGToDAGISel` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{WebAssemblyISelDAGToDAG.cpp}::WebAssemblyDAGToDAGISel { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96830a75c41084a1257da3cdae458e09">WebAssemblyDAGToDAGISel</a> ()=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefce218d3fcd5c41523bb9bb08a80052">WebAssemblyDAGToDAGISel</a> (WebAssemblyTargetMachine &amp;TM, CodeGenOptLevel OptLevel)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b2becea8a0e760c0962e7de08fa21ce">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5fa9366605849c974443a41c63accb5">PreprocessISelDAG</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PreprocessISelDAG - This hook allows targets to hack on the graph before instruction selection starts. <a href="#aa5fa9366605849c974443a41c63accb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab80c137e562add63a0b2c3afbed31be2">Select</a> (SDNode *Node) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Main hook for targets to transform nodes into machine nodes. <a href="#ab80c137e562add63a0b2c3afbed31be2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b1e6812d642d08655090704015c44e3">SelectInlineAsmMemoryOperand</a> (const SDValue &amp;Op, InlineAsm::ConstraintCode ConstraintID, std::vector&lt; SDValue &gt; &amp;OutOps) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectInlineAsmMemoryOperand - Select the specified address as a target addressing mode, according to the specified constraint. <a href="#a4b1e6812d642d08655090704015c44e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb1e58f0477a6c9da390006b0b503006">SelectAddrOperands32</a> (SDValue Op, SDValue &amp;Offset, SDValue &amp;Addr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a684ad82e262538c7de4050ff192189af">SelectAddrOperands64</a> (SDValue Op, SDValue &amp;Offset, SDValue &amp;Addr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c614713aad4f831bd6f12ee3365ac82">SelectAddrOperands</a> (MVT AddrType, unsigned ConstOpc, SDValue Op, SDValue &amp;Offset, SDValue &amp;Addr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae39f0c24e5181ecbacf0122d9fc42d09">SelectAddrAddOperands</a> (MVT OffsetType, SDValue N, SDValue &amp;Offset, SDValue &amp;Addr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget">WebAssemblySubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b38f10ae948ecd4e8267fcac3284520">Subtarget</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep a pointer to the <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget">WebAssemblySubtarget</a> around so that we can make the right decision when generating code for different targets. <a href="#a3b38f10ae948ecd4e8267fcac3284520">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyiseldagtodag-cpp">WebAssemblyISelDAGToDAG.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WebAssemblyDAGToDAGISel() {#a96830a75c41084a1257da3cdae458e09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{WebAssemblyISelDAGToDAG.cpp}::WebAssemblyDAGToDAGISel::WebAssemblyDAGToDAGISel ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyiseldagtodag-cpp">WebAssemblyISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### WebAssemblyDAGToDAGISel() {#aefce218d3fcd5c41523bb9bb08a80052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{WebAssemblyISelDAGToDAG.cpp}::WebAssemblyDAGToDAGISel::WebAssemblyDAGToDAGISel (<a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine">WebAssemblyTargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OptLevel)</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyiseldagtodag-cpp">WebAssemblyISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a5386ceeb71599848944185c0035e0e94">llvm::SelectionDAGISel::OptLevel</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#aeac54a65abd3a93279e58b0f474028fc">llvm::SelectionDAGISel::SelectionDAGISel</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a0ead78650333eefc4d5591ca3db9ed4b">llvm::SelectionDAGISel::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### PreprocessISelDAG() {#aa5fa9366605849c974443a41c63accb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{WebAssemblyISelDAGToDAG.cpp}::WebAssemblyDAGToDAGISel::PreprocessISelDAG ()</td>
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

<p>PreprocessISelDAG - This hook allows targets to hack on the graph before instruction selection starts.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyiseldagtodag-cpp">WebAssemblyISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#acb1e58f0477a6c9da390006b0b503006">SelectAddrOperands32</a>, <a href="#a684ad82e262538c7de4050ff192189af">SelectAddrOperands64</a> and <a href="#a4b1e6812d642d08655090704015c44e3">SelectInlineAsmMemoryOperand</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a9b2becea8a0e760c0962e7de08fa21ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{WebAssemblyISelDAGToDAG.cpp}::WebAssemblyDAGToDAGISel::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyiseldagtodag-cpp">WebAssemblyISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a23107e32342f5488a5edfa71aff54700">llvm::SelectionDAGISel::MF</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a>.</p>

</div>
</div>

### Select() {#ab80c137e562add63a0b2c3afbed31be2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WebAssemblyDAGToDAGISel::Select (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyiseldagtodag-cpp">WebAssemblyISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a385d7f9c63f921a2b28e8426e4101de8">llvm::ISD::ATOMIC_FENCE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaee5189b9c4db9ad666a88abaf1ee0c4ac5d59568835d0760e318829b800ee06d">llvm::Catch</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/node/#a3a50a546aa28bc9ebd20afd6aff7588d">Node::dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyiseldagtodag-cpp/#ac0d0b0350394d4cc32430ad1061f0ce4">getTagSymNode</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget/#a62c2b5b1c74db441e813cc56793dabd4">llvm::WebAssemblySubtarget::hasAtomics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a23107e32342f5488a5edfa71aff54700">llvm::SelectionDAGISel::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#acd1bcf7bcbb18b94234b2bf5a505e925">llvm::SelectionDAGISel::ReplaceNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a7e344cff0feadf0b02223fee63cc7475">Results</a>, <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a15caddcf5c9b41f2f15c2ec363589f6ca6ee3fb8ea1d8946ee1f96ab1947b294a">llvm::SyncScope::SingleThread</a>, <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a15caddcf5c9b41f2f15c2ec363589f6caf9706a2e196638078e8323bfd9ba17de">llvm::SyncScope::System</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a1ed864be04c93653277b0f5112a4f305">llvm::SelectionDAGISel::TLI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a66b0b93d22f984ea3f11e3fc04dbe744">llvm::WebAssembly::WasmUseLegacyEH</a>.</p>

</div>
</div>

### SelectAddrOperands32() {#acb1e58f0477a6c9da390006b0b503006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WebAssemblyDAGToDAGISel::SelectAddrOperands32 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyiseldagtodag-cpp">WebAssemblyISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#aa5fa9366605849c974443a41c63accb5">PreprocessISelDAG</a>.</p>

</div>
</div>

### SelectAddrOperands64() {#a684ad82e262538c7de4050ff192189af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WebAssemblyDAGToDAGISel::SelectAddrOperands64 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyiseldagtodag-cpp">WebAssemblyISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#aa5fa9366605849c974443a41c63accb5">PreprocessISelDAG</a>.</p>

</div>
</div>

### SelectInlineAsmMemoryOperand() {#a4b1e6812d642d08655090704015c44e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WebAssemblyDAGToDAGISel::SelectInlineAsmMemoryOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Op, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0">InlineAsm::ConstraintCode</a> ConstraintID, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OutOps)</td>
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


<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyiseldagtodag-cpp">WebAssemblyISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a6f8f57715090da2632453988d9a1501b">llvm::InlineAsm::m</a>.</p>


<p>Referenced by <a href="#aa5fa9366605849c974443a41c63accb5">PreprocessISelDAG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### SelectAddrAddOperands() {#ae39f0c24e5181ecbacf0122d9fc42d09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WebAssemblyDAGToDAGISel::SelectAddrAddOperands (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> OffsetType, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyiseldagtodag-cpp">WebAssemblyISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectAddrOperands() {#a4c614713aad4f831bd6f12ee3365ac82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WebAssemblyDAGToDAGISel::SelectAddrOperands (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> AddrType, unsigned ConstOpc, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyiseldagtodag-cpp">WebAssemblyISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Subtarget {#a3b38f10ae948ecd4e8267fcac3284520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const WebAssemblySubtarget* anonymous{WebAssemblyISelDAGToDAG.cpp}::WebAssemblyDAGToDAGISel::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep a pointer to the <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget">WebAssemblySubtarget</a> around so that we can make the right decision when generating code for different targets.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyiseldagtodag-cpp">WebAssemblyISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyiseldagtodag-cpp">WebAssemblyISelDAGToDAG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
