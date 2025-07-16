---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `NodeExtensionHelper` Struct Reference

<p>Helper class for folding sign/zero extensions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56e164413eb91dcfa3d8c54944f12f30">CombineToTry</a> = std::function&lt; std::optional&lt; <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/combineresult">CombineResult</a> &gt;( <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4ff30a063f91465787152121a63d6ce">NodeExtensionHelper</a> (SDNode *Root, unsigned OperandIdx, SelectionDAG &amp;DAG, const RISCVSubtarget &amp;Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> for <span class="doxyComputerOutput">Root.getOperand</span>(<span class="doxyComputerOutput">OperandIdx</span>). <a href="#ae4ff30a063f91465787152121a63d6ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f821522a146539779da82fbc446ba92">getSource</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the value feeding the extension or the value itself. <a href="#a9f821522a146539779da82fbc446ba92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79bf8795fd84a5dd16f87452fab2a4d8">isSplat</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if this instance represents a splat. <a href="#a79bf8795fd84a5dd16f87452fab2a4d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30ce469fe7992cf76c09d36b0f754a78">getExtOpc</a> (ExtKind SupportsExt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the extended opcode. <a href="#a30ce469fe7992cf76c09d36b0f754a78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa89bad4ae6c9667571ba16df07adf70">getOrCreateExtendedOp</a> (SDNode *Root, SelectionDAG &amp;DAG, const RISCVSubtarget &amp;Subtarget, std::optional&lt; ExtKind &gt; SupportsExt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get or create a value that can feed <span class="doxyComputerOutput">Root</span> with the given extension <span class="doxyComputerOutput">SupportsExt</span>. <a href="#afa89bad4ae6c9667571ba16df07adf70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c37690b8c2becfadc5ab481d439d171">needToPromoteOtherUsers</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if this node needs to be fully folded or extended for all users. <a href="#a6c37690b8c2becfadc5ab481d439d171">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbd64fe331cf0d150d28e127653d700c">fillUpExtensionSupportForSplat</a> (SDNode *Root, SelectionDAG &amp;DAG, const RISCVSubtarget &amp;Subtarget)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb5a1dc721c95f38cb7951e826d9e646">isSupportedFPExtend</a> (SDNode *Root, MVT NarrowEltVT, const RISCVSubtarget &amp;Subtarget)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15ae520d95e5a8d3948541ed82c2d1c2">fillUpExtensionSupport</a> (SDNode *Root, SelectionDAG &amp;DAG, const RISCVSubtarget &amp;Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper method to set the various fields of this struct based on the type of <span class="doxyComputerOutput">Root</span>. <a href="#a15ae520d95e5a8d3948541ed82c2d1c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eb5f106f60ce51740eccdac5043fa98">SupportsZExt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Records if this operand is like being zero extended. <a href="#a1eb5f106f60ce51740eccdac5043fa98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef5712bcffad0c20ca18f9126b04814f">SupportsSExt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Records if this operand is like being sign extended. <a href="#aef5712bcffad0c20ca18f9126b04814f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addb1d96f5ae5d43830ed396f0c7020ad">SupportsFPExt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Records if this operand is like being floating-Point extended. <a href="#addb1d96f5ae5d43830ed396f0c7020ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7c6793b2e0dc9e478faaabd0cf177b3">EnforceOneUse</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This boolean captures whether we care if this operand would still be around after the folding happens. <a href="#aa7c6793b2e0dc9e478faaabd0cf177b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a5fc677082fff97536173c0e867a8d6">OrigOperand</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Original value that this <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> represents. <a href="#a9a5fc677082fff97536173c0e867a8d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2ca64c9af2f0f7716b503640706d362">getNarrowType</a> (const SDNode *Root, ExtKind SupportsExt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to get the narrow type for <span class="doxyComputerOutput">Root</span>. <a href="#ab2ca64c9af2f0f7716b503640706d362">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b72126752644e5cfe2680d909b3ff5a">getSExtOpcode</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the opcode to materialize: Opcode(sext(a), sext(b)) -&gt; newOpcode(a, b) <a href="#a4b72126752644e5cfe2680d909b3ff5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2203a81e4da51a9da50c08965f2bf917">getZExtOpcode</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the opcode to materialize: Opcode(zext(a), zext(b)) -&gt; newOpcode(a, b) <a href="#a2203a81e4da51a9da50c08965f2bf917">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43dc5ea17cf1ee5d8069c6d9de119109">getFPExtOpcode</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the opcode to materialize: Opcode(fpext(a), fpext(b)) -&gt; newOpcode(a, b) <a href="#a43dc5ea17cf1ee5d8069c6d9de119109">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a95502e159b8ac43cdfca93752306eb">getSUOpcode</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the opcode to materialize <span class="doxyComputerOutput">Opcode</span>(sext(a), zext(b)) -&gt; newOpcode(a, b). <a href="#a5a95502e159b8ac43cdfca93752306eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a378f0c17215c7767060ad8ac7edc9a12">getWOpcode</a> (unsigned Opcode, ExtKind SupportsExt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the opcode to materialize <span class="doxyComputerOutput">Opcode</span>(a, s|z|fpext(b)) -&gt; newOpcode(a, b). <a href="#a378f0c17215c7767060ad8ac7edc9a12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95c8b57eb11e8d25decddd3c86c9703c">isSupportedRoot</a> (const SDNode *Root, const RISCVSubtarget &amp;Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if <span class="doxyComputerOutput">Root</span> supports any extension folding combines. <a href="#a95c8b57eb11e8d25decddd3c86c9703c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aaa2e30b965ca8584badc25c324958d">getMaskAndVL</a> (const SDNode *Root, SelectionDAG &amp;DAG, const RISCVSubtarget &amp;Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to get the Mask and VL from <span class="doxyComputerOutput">Root</span>. <a href="#a0aaa2e30b965ca8584badc25c324958d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a608b96d77b2ddf406d79e2716eb1ac47">isCommutative</a> (const SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to check if <span class="doxyComputerOutput">N</span> is commutative with respect to the foldings that are supported by this class. <a href="#a608b96d77b2ddf406d79e2716eb1ac47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a56e164413eb91dcfa3d8c54944f12f30">CombineToTry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a776c5a5c2c4c9c913f9b44e5b0437f69">getSupportedFoldings</a> (const SDNode *Root)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a list of combine to try for folding extensions in <span class="doxyComputerOutput">Root</span>. <a href="#a776c5a5c2c4c9c913f9b44e5b0437f69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Helper class for folding sign/zero extensions.</p>


<p>In particular, this class is used for the following combines: add | add_vl | or disjoint -&gt; vwadd(u) | vwadd(u)_w sub | sub_vl -&gt; vwsub(u) | vwsub(u)_w mul | mul_vl -&gt; vwmul(u) | vwmul_su shl | shl_vl -&gt; vwsll fadd -&gt; vfwadd | vfwadd_w fsub -&gt; vfwsub | vfwsub_w fmul -&gt; vfwmul An object of this class represents an operand of the operation we want to combine. E.g., when trying to combine <span class="doxyComputerOutput">mul_vl a, b</span>, we will have one instance of <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> for <span class="doxyComputerOutput">a</span> and one for <span class="doxyComputerOutput">b</span>.</p>


<p>This class abstracts away how the extension is materialized and how its number of users affect the combines.</p>


<p>In particular:</p>


<ul class="doxyList ">
<li>VWADD_W is conceptually == add(op0, sext(op1))</li>
<li>VWADDU_W == add(op0, zext(op1))</li>
<li>VWSUB_W == sub(op0, sext(op1))</li>
<li>VWSUBU_W == sub(op0, zext(op1))</li>
<li>VFWADD_W == fadd(op0, fpext(op1))</li>
<li>VFWSUB_W == fsub(op0, fpext(op1)) And VMV_V_X_VL, depending on the value, is conceptually equivalent to zext|sext(smaller_value).</li>
</ul>

<p>Definition at line 15009 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### CombineToTry {#a56e164413eb91dcfa3d8c54944f12f30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::CombineToTry =  std::function&lt;std::optional&lt;CombineResult&gt;(
      SDNode * , const NodeExtensionHelper &amp; ,
      const NodeExtensionHelper &amp; , SelectionDAG &amp;,
      const RISCVSubtarget &amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 15238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### NodeExtensionHelper() {#ae4ff30a063f91465787152121a63d6ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::NodeExtensionHelper (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root, unsigned OperandIdx, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp; Subtarget)</td>
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

<p>Build a <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> for <span class="doxyComputerOutput">Root.getOperand</span>(<span class="doxyComputerOutput">OperandIdx</span>).</p>

<p>Definition at line 15429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa7c6793b2e0dc9e478faaabd0cf177b3">EnforceOneUse</a>, <a href="#a15ae520d95e5a8d3948541ed82c2d1c2">fillUpExtensionSupport</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a23f2f5947fc429aff1270651c6d019ea">llvm::SDNode::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4c20c587f89ae2926f9e8a99093e8419">llvm::SelectionDAG::getTargetLoweringInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ac0a534d63ac5c5b87f36acdade953fbe">llvm::SDNode::getValueType</a>, <a href="#a95c8b57eb11e8d25decddd3c86c9703c">isSupportedRoot</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>, <a href="#a9a5fc677082fff97536173c0e867a8d6">OrigOperand</a>, <a href="#addb1d96f5ae5d43830ed396f0c7020ad">SupportsFPExt</a>, <a href="#aef5712bcffad0c20ca18f9126b04814f">SupportsSExt</a>, <a href="#a1eb5f106f60ce51740eccdac5043fa98">SupportsZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882afbb33522f428f63e33c30ea89d6d2864">llvm::RISCVISD::VFWADD_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a6ede6deabb2a6174ec742114d79041dd">llvm::RISCVISD::VFWSUB_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a50f274b26dbe5d22c120a51113541af6">llvm::RISCVISD::VWADD_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ad4d7b0fd6ff5d187cd6af51af7f44f0e">llvm::RISCVISD::VWADDU_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a147a1fead91935ddd20bff698a5f7e06">llvm::RISCVISD::VWSUB_W_VL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a6bd80026dd613fdb2f48b7234da832ce">llvm::RISCVISD::VWSUBU_W_VL</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### fillUpExtensionSupport() {#a15ae520d95e5a8d3948541ed82c2d1c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::fillUpExtensionSupport (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp; Subtarget)</td>
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

<p>Helper method to set the various fields of this struct based on the type of <span class="doxyComputerOutput">Root</span>.</p>

<p>Definition at line 15313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="#aa7c6793b2e0dc9e478faaabd0cf177b3">EnforceOneUse</a>, <a href="#abbd64fe331cf0d150d28e127653d700c">fillUpExtensionSupportForSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">llvm::ISD::FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a2d9e7f8f372064f120c7102fbc7fdbed">llvm::RISCVISD::FP_EXTEND_VL</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a2e101ce5736aa0643639fd3adae18088">llvm::MVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#acbcc973a299b6f8733774668210b5227">llvm::SDValue::getSimpleValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ad3ff408f213bef998f49952c6c3711fb">llvm::MVT::getVectorElementType</a>, <a href="#adb5a1dc721c95f38cb7951e826d9e646">isSupportedFPExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a425636b56fa037ed7b19ef7f9de30df9">llvm::MVT::isVector</a>, <a href="#a9a5fc677082fff97536173c0e867a8d6">OrigOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7f864031b6fb691b1525cbea92542ef1">llvm::ISD::SPLAT_VECTOR</a>, <a href="#addb1d96f5ae5d43830ed396f0c7020ad">SupportsFPExt</a>, <a href="#aef5712bcffad0c20ca18f9126b04814f">SupportsSExt</a>, <a href="#a1eb5f106f60ce51740eccdac5043fa98">SupportsZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a3d046b0b663cacd2116c6d35498ab5ab">llvm::RISCVISD::VFMV_V_F_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a127afe58529ef366a343a51786dcc3d4">llvm::RISCVISD::VMV_V_X_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a2be5d0001da98e7c524aa9d212419f7d">llvm::RISCVISD::VSEXT_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882aab563d8b09e3a65dbc2bd73051b074cc">llvm::RISCVISD::VZEXT_VL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>


<p>Referenced by <a href="#ae4ff30a063f91465787152121a63d6ce">NodeExtensionHelper</a>.</p>

</div>
</div>

### fillUpExtensionSupportForSplat() {#abbd64fe331cf0d150d28e127653d700c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::fillUpExtensionSupportForSplat (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp; Subtarget)</td>
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



<p>Definition at line 15246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0a2081911053ceb07370842200df3e7c">llvm::SelectionDAG::ComputeMaxSignificantBits</a>, <a href="#aa7c6793b2e0dc9e478faaabd0cf177b3">EnforceOneUse</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aeaf22e8d92fd978a5eca9ab031994399">llvm::APInt::getBitsSetFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a2e101ce5736aa0643639fd3adae18088">llvm::MVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget/#afd9fbb2a5a666589b2843c496f3ae479">llvm::RISCVSubtarget::is64Bit</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad5386f4196a9eab5701c451469f2e20e">llvm::SelectionDAG::MaskedValueIsZero</a>, <a href="#a9a5fc677082fff97536173c0e867a8d6">OrigOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a923b1af8c1e485549410eda36702a5ac">llvm::SelectionDAG::SignBitIsZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7f864031b6fb691b1525cbea92542ef1">llvm::ISD::SPLAT_VECTOR</a>, <a href="#aef5712bcffad0c20ca18f9126b04814f">SupportsSExt</a>, <a href="#a1eb5f106f60ce51740eccdac5043fa98">SupportsZExt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a127afe58529ef366a343a51786dcc3d4">llvm::RISCVISD::VMV_V_X_VL</a>.</p>


<p>Referenced by <a href="#a15ae520d95e5a8d3948541ed82c2d1c2">fillUpExtensionSupport</a>.</p>

</div>
</div>

### getExtOpc() {#a30ce469fe7992cf76c09d36b0f754a78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getExtOpc (<a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#a0fb45dddfe1615e320ac9ad137d634e7">ExtKind</a> SupportsExt)</td>
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

<p>Get the extended opcode.</p>

<p>Definition at line 15047 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a2d9e7f8f372064f120c7102fbc7fdbed">llvm::RISCVISD::FP_EXTEND_VL</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#a0fb45dddfe1615e320ac9ad137d634e7a2e8f4f487902ef68689d6a02548cf8af">anonymous{RISCVISelLowering.cpp}::FPExt</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#a0fb45dddfe1615e320ac9ad137d634e7a6d82f5a74a3f08ddcbb81036603b1f7c">anonymous{RISCVISelLowering.cpp}::SExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a2be5d0001da98e7c524aa9d212419f7d">llvm::RISCVISD::VSEXT_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882aab563d8b09e3a65dbc2bd73051b074cc">llvm::RISCVISD::VZEXT_VL</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#a0fb45dddfe1615e320ac9ad137d634e7aa2f0622a02fc4af2ec7bd22803523662">anonymous{RISCVISelLowering.cpp}::ZExt</a>.</p>


<p>Referenced by <a href="#afa89bad4ae6c9667571ba16df07adf70">getOrCreateExtendedOp</a>.</p>

</div>
</div>

### getOrCreateExtendedOp() {#afa89bad4ae6c9667571ba16df07adf70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getOrCreateExtendedOp (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp; Subtarget, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#a0fb45dddfe1615e320ac9ad137d634e7">ExtKind</a> &gt; SupportsExt)</td>
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

<p>Get or create a value that can feed <span class="doxyComputerOutput">Root</span> with the given extension <span class="doxyComputerOutput">SupportsExt</span>.</p>


<p>If <span class="doxyComputerOutput">SExt</span> is std::nullopt, this returns the source of this operand.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a9f821522a146539779da82fbc446ba92">getSource()</a>.</p></dd>
</dl>


<p>Definition at line 15062 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">llvm::ISD::FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a2d9e7f8f372064f120c7102fbc7fdbed">llvm::RISCVISD::FP_EXTEND_VL</a>, <a href="#a30ce469fe7992cf76c09d36b0f754a78">getExtOpc</a>, <a href="#a0aaa2e30b965ca8584badc25c324958d">getMaskAndVL</a>, <a href="#ab2ca64c9af2f0f7716b503640706d362">getNarrowType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a23f2f5947fc429aff1270651c6d019ea">llvm::SDNode::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7a6096cff14db41b299758115c6e261c">llvm::SDNode::getSimpleValueType</a>, <a href="#a9f821522a146539779da82fbc446ba92">getSource</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af3da6f92909b5cf14f30953a302edd34">llvm::SelectionDAG::getSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget/#ae2af8cfe3fcf89cb957885bfc303e8ae">llvm::RISCVSubtarget::getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5b0e59823444a55c295af279611a9d24">llvm::SelectionDAG::getUNDEF</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ad3ff408f213bef998f49952c6c3711fb">llvm::MVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a9a5fc677082fff97536173c0e867a8d6">OrigOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7f864031b6fb691b1525cbea92542ef1">llvm::ISD::SPLAT_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a5157c18d075bbbc3b6ce91de07edcc7f">llvm::RISCVISD::VFMADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a3d046b0b663cacd2116c6d35498ab5ab">llvm::RISCVISD::VFMV_V_F_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a127afe58529ef366a343a51786dcc3d4">llvm::RISCVISD::VMV_V_X_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a2be5d0001da98e7c524aa9d212419f7d">llvm::RISCVISD::VSEXT_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882aab563d8b09e3a65dbc2bd73051b074cc">llvm::RISCVISD::VZEXT_VL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>

</div>
</div>

### getSource() {#a9f821522a146539779da82fbc446ba92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getSource ()</td>
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

<p>Get the value feeding the extension or the value itself.</p>


<p>E.g., for zext(a), this would return a.</p>


<p>Definition at line 15027 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a2d9e7f8f372064f120c7102fbc7fdbed">llvm::RISCVISD::FP_EXTEND_VL</a>, <a href="#a9a5fc677082fff97536173c0e867a8d6">OrigOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a2be5d0001da98e7c524aa9d212419f7d">llvm::RISCVISD::VSEXT_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882aab563d8b09e3a65dbc2bd73051b074cc">llvm::RISCVISD::VZEXT_VL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>


<p>Referenced by <a href="#afa89bad4ae6c9667571ba16df07adf70">getOrCreateExtendedOp</a>.</p>

</div>
</div>

### isSplat() {#a79bf8795fd84a5dd16f87452fab2a4d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::isSplat ()</td>
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

<p>Check if this instance represents a splat.</p>

<p>Definition at line 15041 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="#a9a5fc677082fff97536173c0e867a8d6">OrigOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7f864031b6fb691b1525cbea92542ef1">llvm::ISD::SPLAT_VECTOR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a127afe58529ef366a343a51786dcc3d4">llvm::RISCVISD::VMV_V_X_VL</a>.</p>

</div>
</div>

### isSupportedFPExtend() {#adb5a1dc721c95f38cb7951e826d9e646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::isSupportedFPExtend (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> NarrowEltVT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp; Subtarget)</td>
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



<p>Definition at line 15298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a23f2f5947fc429aff1270651c6d019ea">llvm::SDNode::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget/#a7f216bb52e836a9222288ad723e4a8c2">llvm::RISCVSubtarget::hasVInstructionsF16</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a5157c18d075bbbc3b6ce91de07edcc7f">llvm::RISCVISD::VFMADD_VL</a>.</p>


<p>Referenced by <a href="#a15ae520d95e5a8d3948541ed82c2d1c2">fillUpExtensionSupport</a>.</p>

</div>
</div>

### needToPromoteOtherUsers() {#a6c37690b8c2becfadc5ab481d439d171}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::needToPromoteOtherUsers ()</td>
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

<p>Check if this node needs to be fully folded or extended for all users.</p>

<p>Definition at line 15244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>Reference <a href="#aa7c6793b2e0dc9e478faaabd0cf177b3">EnforceOneUse</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### EnforceOneUse {#aa7c6793b2e0dc9e478faaabd0cf177b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::EnforceOneUse</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This boolean captures whether we care if this operand would still be around after the folding happens.</p>

<p>Definition at line 15021 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>Referenced by <a href="#a15ae520d95e5a8d3948541ed82c2d1c2">fillUpExtensionSupport</a>, <a href="#abbd64fe331cf0d150d28e127653d700c">fillUpExtensionSupportForSplat</a>, <a href="#a6c37690b8c2becfadc5ab481d439d171">needToPromoteOtherUsers</a> and <a href="#ae4ff30a063f91465787152121a63d6ce">NodeExtensionHelper</a>.</p>

</div>
</div>

### OrigOperand {#a9a5fc677082fff97536173c0e867a8d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::OrigOperand</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Original value that this <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> represents.</p>

<p>Definition at line 15023 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>Referenced by <a href="#a15ae520d95e5a8d3948541ed82c2d1c2">fillUpExtensionSupport</a>, <a href="#abbd64fe331cf0d150d28e127653d700c">fillUpExtensionSupportForSplat</a>, <a href="#afa89bad4ae6c9667571ba16df07adf70">getOrCreateExtendedOp</a>, <a href="#a9f821522a146539779da82fbc446ba92">getSource</a>, <a href="#a79bf8795fd84a5dd16f87452fab2a4d8">isSplat</a> and <a href="#ae4ff30a063f91465787152121a63d6ce">NodeExtensionHelper</a>.</p>

</div>
</div>

### SupportsFPExt {#addb1d96f5ae5d43830ed396f0c7020ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::SupportsFPExt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Records if this operand is like being floating-Point extended.</p>

<p>Definition at line 15018 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>Referenced by <a href="#a15ae520d95e5a8d3948541ed82c2d1c2">fillUpExtensionSupport</a> and <a href="#ae4ff30a063f91465787152121a63d6ce">NodeExtensionHelper</a>.</p>

</div>
</div>

### SupportsSExt {#aef5712bcffad0c20ca18f9126b04814f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::SupportsSExt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Records if this operand is like being sign extended.</p>


<p>Note: SupportsZExt and SupportsSExt are not mutually exclusive. For instance, a splat constant (e.g., 3), would support being both sign and zero extended.</p>


<p>Definition at line 15016 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>Referenced by <a href="#a15ae520d95e5a8d3948541ed82c2d1c2">fillUpExtensionSupport</a>, <a href="#abbd64fe331cf0d150d28e127653d700c">fillUpExtensionSupportForSplat</a> and <a href="#ae4ff30a063f91465787152121a63d6ce">NodeExtensionHelper</a>.</p>

</div>
</div>

### SupportsZExt {#a1eb5f106f60ce51740eccdac5043fa98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::SupportsZExt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Records if this operand is like being zero extended.</p>

<p>Definition at line 15011 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>Referenced by <a href="#a15ae520d95e5a8d3948541ed82c2d1c2">fillUpExtensionSupport</a>, <a href="#abbd64fe331cf0d150d28e127653d700c">fillUpExtensionSupportForSplat</a> and <a href="#ae4ff30a063f91465787152121a63d6ce">NodeExtensionHelper</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getFPExtOpcode() {#a43dc5ea17cf1ee5d8069c6d9de119109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getFPExtOpcode (unsigned Opcode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the opcode to materialize: Opcode(fpext(a), fpext(b)) -&gt; newOpcode(a, b)</p>

<p>Definition at line 15185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882acca75875c0af2b5d293e0d1cfd2075e7">llvm::RISCVISD::FADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a2214f5316d8e125ed7d4d20b1cefb182">llvm::RISCVISD::FMUL_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ab47e9a22d871e8c10e5be7c837d2c698">llvm::RISCVISD::FSUB_VL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a5157c18d075bbbc3b6ce91de07edcc7f">llvm::RISCVISD::VFMADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ac0ebb4a665039e56d0ae06e6cc83ca9e">llvm::RISCVISD::VFMSUB_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ae73310d12703d3bc8aa5ec0ba9b87d6c">llvm::RISCVISD::VFNMADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882abc29e48c549a16883a67a05fc0754f40">llvm::RISCVISD::VFNMSUB_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ac59f2ed64c2111f79237a4f1ed969988">llvm::RISCVISD::VFWADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882afbb33522f428f63e33c30ea89d6d2864">llvm::RISCVISD::VFWADD_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ad2c9653aae605a17bc689418fa22ee57">llvm::RISCVISD::VFWMADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a912c2473049956164b2789fb9186932d">llvm::RISCVISD::VFWMSUB_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a84337401b270768506507b7753d102a7">llvm::RISCVISD::VFWMUL_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882af6c5203fba9bad8b65e2392faee102b1">llvm::RISCVISD::VFWNMADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a85f255c876e7fbea9e885bd2cd22a8a5">llvm::RISCVISD::VFWNMSUB_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882adfdbbbc6eaecf2917ed49a7aeeb5a2a0">llvm::RISCVISD::VFWSUB_VL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a6ede6deabb2a6174ec742114d79041dd">llvm::RISCVISD::VFWSUB_W_VL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#adec3c0687a05bd66a2a9937f4a374d34">anonymous{RISCVISelLowering.cpp}::canFoldToVWWithSameExtensionImpl</a>.</p>

</div>
</div>

### getMaskAndVL() {#a0aaa2e30b965ca8584badc25c324958d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; SDValue, SDValue &gt; anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getMaskAndVL (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp; Subtarget)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function to get the Mask and VL from <span class="doxyComputerOutput">Root</span>.</p>

<p>Definition at line 15471 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a8985b59d609a1b923fce5c512026b7e8">getDefaultScalableVLOps</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a23f2f5947fc429aff1270651c6d019ea">llvm::SDNode::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7a6096cff14db41b299758115c6e261c">llvm::SDNode::getSimpleValueType</a>, <a href="#a95c8b57eb11e8d25decddd3c86c9703c">isSupportedRoot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>.</p>


<p>Referenced by <a href="#afa89bad4ae6c9667571ba16df07adf70">getOrCreateExtendedOp</a> and <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/combineresult/#a6a29551e352719a5e4d927f1a5e0871b">anonymous{RISCVISelLowering.cpp}::CombineResult::materialize</a>.</p>

</div>
</div>

### getNarrowType() {#ab2ca64c9af2f0f7716b503640706d362}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getNarrowType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#a0fb45dddfe1615e320ac9ad137d634e7">ExtKind</a> SupportsExt)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function to get the narrow type for <span class="doxyComputerOutput">Root</span>.</p>


<p>The narrow type is the type of <span class="doxyComputerOutput">Root</span> where we divided the size of each element by 2. E.g., if Root's type &lt;2xi16&gt; -&gt; narrow type &lt;2xi8&gt;.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>Both the narrow type and the original type should be legal.</p></dd>
</dl>


<p>Definition at line 15118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#a0fb45dddfe1615e320ac9ad137d634e7a2e8f4f487902ef68689d6a02548cf8af">anonymous{RISCVISelLowering.cpp}::FPExt</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a063563f5f87a96c0cd15403eeacf458e">llvm::MVT::getFloatingPointVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#aded931e298cfa08b5038ca2b63c06bb8">llvm::MVT::getIntegerVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a2e101ce5736aa0643639fd3adae18088">llvm::MVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7a6096cff14db41b299758115c6e261c">llvm::SDNode::getSimpleValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#aa1abe2e0d36a43d780ce54ea3b197217">llvm::MVT::getVectorElementCount</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#abf8d0055af4879a302268d3f834b2be5">llvm::MVT::getVectorVT</a>.</p>


<p>Referenced by <a href="#afa89bad4ae6c9667571ba16df07adf70">getOrCreateExtendedOp</a>.</p>

</div>
</div>

### getSExtOpcode() {#a4b72126752644e5cfe2680d909b3ff5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getSExtOpcode (unsigned Opcode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the opcode to materialize: Opcode(sext(a), sext(b)) -&gt; newOpcode(a, b)</p>

<p>Definition at line 15136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ae31415e16e999fc747eb81e9e48689b1">llvm::RISCVISD::ADD_VL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a386e45450adba2e23952cd9b61c99387">llvm::RISCVISD::MUL_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a14a2c20051cd4652b3ab86b25e931525">llvm::RISCVISD::SUB_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a62edacb6d4d52e4d3206ecffbecd7db3">llvm::RISCVISD::VWADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a50f274b26dbe5d22c120a51113541af6">llvm::RISCVISD::VWADD_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ad4d7b0fd6ff5d187cd6af51af7f44f0e">llvm::RISCVISD::VWADDU_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a74afd07429ec343a7cbe1b58790a0d41">llvm::RISCVISD::VWMUL_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a852d0a6914208c69c08937b87f1564be">llvm::RISCVISD::VWSUB_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a147a1fead91935ddd20bff698a5f7e06">llvm::RISCVISD::VWSUB_W_VL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a6bd80026dd613fdb2f48b7234da832ce">llvm::RISCVISD::VWSUBU_W_VL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#adec3c0687a05bd66a2a9937f4a374d34">anonymous{RISCVISelLowering.cpp}::canFoldToVWWithSameExtensionImpl</a>.</p>

</div>
</div>

### getSUOpcode() {#a5a95502e159b8ac43cdfca93752306eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getSUOpcode (unsigned Opcode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the opcode to materialize <span class="doxyComputerOutput">Opcode</span>(sext(a), zext(b)) -&gt; newOpcode(a, b).</p>

<p>Definition at line 15210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a386e45450adba2e23952cd9b61c99387">llvm::RISCVISD::MUL_VL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a84f25091f4381de64087f9bf5906113e">llvm::RISCVISD::VWMULSU_VL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#affe8145f52cae856369a22fa52019397">anonymous{RISCVISelLowering.cpp}::canFoldToVW_SU</a>.</p>

</div>
</div>

### getSupportedFoldings() {#a776c5a5c2c4c9c913f9b44e5b0437f69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; NodeExtensionHelper::CombineToTry &gt; anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getSupportedFoldings (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root)</td>
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

<p>Get a list of combine to try for folding extensions in <span class="doxyComputerOutput">Root</span>.</p>


<p>Note that each returned <a href="#a56e164413eb91dcfa3d8c54944f12f30">CombineToTry</a> function doesn't actually modify anything. Instead they produce an optional <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/combineresult">CombineResult</a> that if not None, need to be materialized for the combine to be applied.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/combineresult/#a6a29551e352719a5e4d927f1a5e0871b">CombineResult::materialize</a>. If the related <a href="#a56e164413eb91dcfa3d8c54944f12f30">CombineToTry</a> <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> returns std::nullopt, that means the combine didn't <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">match</a>.</p></dd>
</dl>


<p>Definition at line 15529 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ae31415e16e999fc747eb81e9e48689b1">llvm::RISCVISD::ADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#affe8145f52cae856369a22fa52019397">anonymous{RISCVISelLowering.cpp}::canFoldToVW_SU</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#a8b2154a7e9a794c5b363a5c2c1e489bd">anonymous{RISCVISelLowering.cpp}::canFoldToVW_W</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#abf060deb455eb2c66d75fb603fa24794">anonymous{RISCVISelLowering.cpp}::canFoldToVWWithFPEXT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#a866d5dd0b3838b0751d25c237dd9b8b6">anonymous{RISCVISelLowering.cpp}::canFoldToVWWithSameExtension</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#a7c43a9fe0538ec36fd98a4415b58c14a">anonymous{RISCVISelLowering.cpp}::canFoldToVWWithSEXT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#aa60899790b80d7bba8a4f76ca19ea699">anonymous{RISCVISelLowering.cpp}::canFoldToVWWithZEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882acca75875c0af2b5d293e0d1cfd2075e7">llvm::RISCVISD::FADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a2214f5316d8e125ed7d4d20b1cefb182">llvm::RISCVISD::FMUL_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ab47e9a22d871e8c10e5be7c837d2c698">llvm::RISCVISD::FSUB_VL</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a23f2f5947fc429aff1270651c6d019ea">llvm::SDNode::getOpcode</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a386e45450adba2e23952cd9b61c99387">llvm::RISCVISD::MUL_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a7e7efe8f44a6631a42aaaf19a3448d9b">llvm::RISCVISD::SHL_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a14a2c20051cd4652b3ab86b25e931525">llvm::RISCVISD::SUB_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a5157c18d075bbbc3b6ce91de07edcc7f">llvm::RISCVISD::VFMADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ac0ebb4a665039e56d0ae06e6cc83ca9e">llvm::RISCVISD::VFMSUB_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ae73310d12703d3bc8aa5ec0ba9b87d6c">llvm::RISCVISD::VFNMADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882abc29e48c549a16883a67a05fc0754f40">llvm::RISCVISD::VFNMSUB_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882afbb33522f428f63e33c30ea89d6d2864">llvm::RISCVISD::VFWADD_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a6ede6deabb2a6174ec742114d79041dd">llvm::RISCVISD::VFWSUB_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a50f274b26dbe5d22c120a51113541af6">llvm::RISCVISD::VWADD_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ad4d7b0fd6ff5d187cd6af51af7f44f0e">llvm::RISCVISD::VWADDU_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a147a1fead91935ddd20bff698a5f7e06">llvm::RISCVISD::VWSUB_W_VL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a6bd80026dd613fdb2f48b7234da832ce">llvm::RISCVISD::VWSUBU_W_VL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3ff4156c9862c64e6d354f5413c3da5e">combineOp_VLToVWOp_VL</a>.</p>

</div>
</div>

### getWOpcode() {#a378f0c17215c7767060ad8ac7edc9a12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getWOpcode (unsigned Opcode, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#a0fb45dddfe1615e320ac9ad137d634e7">ExtKind</a> SupportsExt)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the opcode to materialize <span class="doxyComputerOutput">Opcode</span>(a, s|z|fpext(b)) -&gt; newOpcode(a, b).</p>

<p>Definition at line 15218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ae31415e16e999fc747eb81e9e48689b1">llvm::RISCVISD::ADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882acca75875c0af2b5d293e0d1cfd2075e7">llvm::RISCVISD::FADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ab47e9a22d871e8c10e5be7c837d2c698">llvm::RISCVISD::FSUB_VL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#a0fb45dddfe1615e320ac9ad137d634e7a6d82f5a74a3f08ddcbb81036603b1f7c">anonymous{RISCVISelLowering.cpp}::SExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a14a2c20051cd4652b3ab86b25e931525">llvm::RISCVISD::SUB_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882afbb33522f428f63e33c30ea89d6d2864">llvm::RISCVISD::VFWADD_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a6ede6deabb2a6174ec742114d79041dd">llvm::RISCVISD::VFWSUB_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a50f274b26dbe5d22c120a51113541af6">llvm::RISCVISD::VWADD_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ad4d7b0fd6ff5d187cd6af51af7f44f0e">llvm::RISCVISD::VWADDU_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a147a1fead91935ddd20bff698a5f7e06">llvm::RISCVISD::VWSUB_W_VL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a6bd80026dd613fdb2f48b7234da832ce">llvm::RISCVISD::VWSUBU_W_VL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#a8b2154a7e9a794c5b363a5c2c1e489bd">anonymous{RISCVISelLowering.cpp}::canFoldToVW_W</a>.</p>

</div>
</div>

### getZExtOpcode() {#a2203a81e4da51a9da50c08965f2bf917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getZExtOpcode (unsigned Opcode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the opcode to materialize: Opcode(zext(a), zext(b)) -&gt; newOpcode(a, b)</p>

<p>Definition at line 15159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ae31415e16e999fc747eb81e9e48689b1">llvm::RISCVISD::ADD_VL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a386e45450adba2e23952cd9b61c99387">llvm::RISCVISD::MUL_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a7e7efe8f44a6631a42aaaf19a3448d9b">llvm::RISCVISD::SHL_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a14a2c20051cd4652b3ab86b25e931525">llvm::RISCVISD::SUB_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a50f274b26dbe5d22c120a51113541af6">llvm::RISCVISD::VWADD_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a15f31bbcbb2d8da15abfc71db97eb870">llvm::RISCVISD::VWADDU_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ad4d7b0fd6ff5d187cd6af51af7f44f0e">llvm::RISCVISD::VWADDU_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a0e872ddbd914219b650c1c5856e195e9">llvm::RISCVISD::VWMULU_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a2a577eae33a27da1292c6faf1b9573f7">llvm::RISCVISD::VWSLL_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a147a1fead91935ddd20bff698a5f7e06">llvm::RISCVISD::VWSUB_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a440b50009035fc04b55074c1417ef2f7">llvm::RISCVISD::VWSUBU_VL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a6bd80026dd613fdb2f48b7234da832ce">llvm::RISCVISD::VWSUBU_W_VL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#adec3c0687a05bd66a2a9937f4a374d34">anonymous{RISCVISelLowering.cpp}::canFoldToVWWithSameExtensionImpl</a>.</p>

</div>
</div>

### isCommutative() {#a608b96d77b2ddf406d79e2716eb1ac47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::isCommutative (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function to check if <span class="doxyComputerOutput">N</span> is commutative with respect to the foldings that are supported by this class.</p>

<p>Definition at line 15491 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ae31415e16e999fc747eb81e9e48689b1">llvm::RISCVISD::ADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882acca75875c0af2b5d293e0d1cfd2075e7">llvm::RISCVISD::FADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a2214f5316d8e125ed7d4d20b1cefb182">llvm::RISCVISD::FMUL_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ab47e9a22d871e8c10e5be7c837d2c698">llvm::RISCVISD::FSUB_VL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a386e45450adba2e23952cd9b61c99387">llvm::RISCVISD::MUL_VL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a7e7efe8f44a6631a42aaaf19a3448d9b">llvm::RISCVISD::SHL_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a14a2c20051cd4652b3ab86b25e931525">llvm::RISCVISD::SUB_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a5157c18d075bbbc3b6ce91de07edcc7f">llvm::RISCVISD::VFMADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ac0ebb4a665039e56d0ae06e6cc83ca9e">llvm::RISCVISD::VFMSUB_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ae73310d12703d3bc8aa5ec0ba9b87d6c">llvm::RISCVISD::VFNMADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882abc29e48c549a16883a67a05fc0754f40">llvm::RISCVISD::VFNMSUB_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882afbb33522f428f63e33c30ea89d6d2864">llvm::RISCVISD::VFWADD_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a6ede6deabb2a6174ec742114d79041dd">llvm::RISCVISD::VFWSUB_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a50f274b26dbe5d22c120a51113541af6">llvm::RISCVISD::VWADD_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ad4d7b0fd6ff5d187cd6af51af7f44f0e">llvm::RISCVISD::VWADDU_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a147a1fead91935ddd20bff698a5f7e06">llvm::RISCVISD::VWSUB_W_VL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a6bd80026dd613fdb2f48b7234da832ce">llvm::RISCVISD::VWSUBU_W_VL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3ff4156c9862c64e6d354f5413c3da5e">combineOp_VLToVWOp_VL</a>.</p>

</div>
</div>

### isSupportedRoot() {#a95c8b57eb11e8d25decddd3c86c9703c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::isSupportedRoot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp; Subtarget)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if <span class="doxyComputerOutput">Root</span> supports any extension folding combines.</p>

<p>Definition at line 15386 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ae31415e16e999fc747eb81e9e48689b1">llvm::RISCVISD::ADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882acca75875c0af2b5d293e0d1cfd2075e7">llvm::RISCVISD::FADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a2214f5316d8e125ed7d4d20b1cefb182">llvm::RISCVISD::FMUL_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ab47e9a22d871e8c10e5be7c837d2c698">llvm::RISCVISD::FSUB_VL</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a5023bb0687db0b35d3b2d19327217ce5">llvm::SDNode::getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a23f2f5947fc429aff1270651c6d019ea">llvm::SDNode::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ac0a534d63ac5c5b87f36acdade953fbe">llvm::SDNode::getValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags/#ab04271fd14f03c03efaa34fe96b8daf5">llvm::SDNodeFlags::hasDisjoint</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ab8967b7214f38cdea9c0158dbe2ffa31">llvm::EVT::isScalableVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a386e45450adba2e23952cd9b61c99387">llvm::RISCVISD::MUL_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a7e7efe8f44a6631a42aaaf19a3448d9b">llvm::RISCVISD::SHL_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a14a2c20051cd4652b3ab86b25e931525">llvm::RISCVISD::SUB_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a5157c18d075bbbc3b6ce91de07edcc7f">llvm::RISCVISD::VFMADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ac0ebb4a665039e56d0ae06e6cc83ca9e">llvm::RISCVISD::VFMSUB_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ae73310d12703d3bc8aa5ec0ba9b87d6c">llvm::RISCVISD::VFNMADD_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882abc29e48c549a16883a67a05fc0754f40">llvm::RISCVISD::VFNMSUB_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882afbb33522f428f63e33c30ea89d6d2864">llvm::RISCVISD::VFWADD_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a6ede6deabb2a6174ec742114d79041dd">llvm::RISCVISD::VFWSUB_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a50f274b26dbe5d22c120a51113541af6">llvm::RISCVISD::VWADD_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882ad4d7b0fd6ff5d187cd6af51af7f44f0e">llvm::RISCVISD::VWADDU_W_VL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a147a1fead91935ddd20bff698a5f7e06">llvm::RISCVISD::VWSUB_W_VL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a6bd80026dd613fdb2f48b7234da832ce">llvm::RISCVISD::VWSUBU_W_VL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3ff4156c9862c64e6d354f5413c3da5e">combineOp_VLToVWOp_VL</a>, <a href="#a0aaa2e30b965ca8584badc25c324958d">getMaskAndVL</a> and <a href="#ae4ff30a063f91465787152121a63d6ce">NodeExtensionHelper</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
