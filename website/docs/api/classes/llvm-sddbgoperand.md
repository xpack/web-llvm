---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sddbgoperand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SDDbgOperand` Class Reference

<p>Holds the information for a single machine location through SDISel; either an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>, a constant, a stack location, or a virtual register. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SDDbgOperand { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">CodeGen/SelectionDAG/SDNodeDbgValue.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Kind { <a href="#aaca42b5103c6b7f2cb9a050b61fed709">...</a> }</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa24d9d4b6abe9e9df815253826a245ce">SDDbgOperand</a> (SDNode *N, unsigned R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor for non-constants. <a href="#aa24d9d4b6abe9e9df815253826a245ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdf3f975ce6b8687b3a2b9e35694eb3e">SDDbgOperand</a> (const Value *C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor for constants. <a href="#abdf3f975ce6b8687b3a2b9e35694eb3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6e5660e2eddf2c5c923e7860b014ae6">SDDbgOperand</a> (unsigned VRegOrFrameIdx, Kind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor for virtual registers and frame indices. <a href="#af6e5660e2eddf2c5c923e7860b014ae6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1780222ffdb1029d72bf012e58e48222">operator!=</a> (const SDDbgOperand &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1199158a0e8d77e989464ad6b7274f3">operator==</a> (const SDDbgOperand &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aaca42b5103c6b7f2cb9a050b61fed709">Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7673427faa10f98864b7e7b9b008ec8">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94d6e361d3359e291427734fcc364582">getSDNode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the SDNode* for a register ref. <a href="#a94d6e361d3359e291427734fcc364582">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a343fd12fb0de39a8f7bdfe6acbb9a1bb">getResNo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the ResNo for a register ref. <a href="#a343fd12fb0de39a8f7bdfe6acbb9a1bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba8e9cd16e177dd466270da4d046257b">getConst</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the Value* for a constant. <a href="#aba8e9cd16e177dd466270da4d046257b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a820e4a5c816227c2d55e767f1148d48c">getFrameIx</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the FrameIx for a stack object. <a href="#a820e4a5c816227c2d55e767f1148d48c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4639cbb2d8bdbb307d236cb2fc165011">getVReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the Virtual <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> for a VReg. <a href="#a4639cbb2d8bdbb307d236cb2fc165011">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeea131ba3ed6ae837d81c0a4fbdebef6">Node</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Valid for expressions. <a href="#aeea131ba3ed6ae837d81c0a4fbdebef6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5221233d4cec2351331406959c3a52e8">ResNo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Valid for expressions. <a href="#a5221233d4cec2351331406959c3a52e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64a8bd88a7b9d486d4d2786ae93f57cd">s</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0f10cd8a8fe2541dff0ac89af0e0bd5">Const</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Valid for constants. <a href="#aa0f10cd8a8fe2541dff0ac89af0e0bd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7db23494994080357ac7461ab7e278dc">FrameIx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Valid for stack objects. <a href="#a7db23494994080357ac7461ab7e278dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32648711fc7893749d02923c8d89fd81">VReg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Valid for registers. <a href="#a32648711fc7893749d02923c8d89fd81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aaca42b5103c6b7f2cb9a050b61fed709">Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a038d7fa68dbafe78da0f135e94cbac64">kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand">llvm::SDDbgOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd945494e31224b033cb7764b5cf9bf0">u</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand">SDDbgOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a064ee6a43b2dc34747bda1d194922773">fromNode</a> (SDNode *Node, unsigned ResNo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand">SDDbgOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ee3253416c1e239c9b70848aa4c4266">fromFrameIdx</a> (unsigned FrameIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand">SDDbgOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e8946c426e13b7a8eac5f89fe1e8aca">fromVReg</a> (unsigned VReg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand">SDDbgOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a839c3f734c6a978e745998e5d7904beb">fromConst</a> (const Value *Const)</td>
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

<p>Holds the information for a single machine location through SDISel; either an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>, a constant, a stack location, or a virtual register.</p>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Kind {#aaca42b5103c6b7f2cb9a050b61fed709}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::SDDbgOperand::Kind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SDNODE<a id="aaca42b5103c6b7f2cb9a050b61fed709aa35847085c9bc57f525640fa8ae5a15c"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is the result of an expression (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONST<a id="aaca42b5103c6b7f2cb9a050b61fed709aae386012326afbc26eeecc3701f36134"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is a constant (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FRAMEIX<a id="aaca42b5103c6b7f2cb9a050b61fed709a8c6e740c1259b720ed9f87a05baf593b"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is contents of a stack location (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VREG<a id="aaca42b5103c6b7f2cb9a050b61fed709a18402f81e9528c3cc41c781786e533b8"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is a virtual register (= 3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### SDDbgOperand() {#aa24d9d4b6abe9e9df815253826a245ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SDDbgOperand::SDDbgOperand (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned R)</td>
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

<p>Constructor for non-constants.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

### SDDbgOperand() {#abdf3f975ce6b8687b3a2b9e35694eb3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SDDbgOperand::SDDbgOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * C)</td>
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

<p>Constructor for constants.</p>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

### SDDbgOperand() {#af6e5660e2eddf2c5c923e7860b014ae6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SDDbgOperand::SDDbgOperand (unsigned VRegOrFrameIdx, <a href="#aaca42b5103c6b7f2cb9a050b61fed709">Kind</a> Kind)</td>
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

<p>Constructor for virtual registers and frame indices.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a1780222ffdb1029d72bf012e58e48222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDDbgOperand::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand">SDDbgOperand</a> &amp; Other)</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator==() {#ae1199158a0e8d77e989464ad6b7274f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDDbgOperand::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand">SDDbgOperand</a> &amp; Other)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>References <a href="#aaca42b5103c6b7f2cb9a050b61fed709aae386012326afbc26eeecc3701f36134">CONST</a>, <a href="#aaca42b5103c6b7f2cb9a050b61fed709a8c6e740c1259b720ed9f87a05baf593b">FRAMEIX</a>, <a href="#aba8e9cd16e177dd466270da4d046257b">getConst</a>, <a href="#a820e4a5c816227c2d55e767f1148d48c">getFrameIx</a>, <a href="#a343fd12fb0de39a8f7bdfe6acbb9a1bb">getResNo</a>, <a href="#a94d6e361d3359e291427734fcc364582">getSDNode</a>, <a href="#a4639cbb2d8bdbb307d236cb2fc165011">getVReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#aaca42b5103c6b7f2cb9a050b61fed709aa35847085c9bc57f525640fa8ae5a15c">SDNODE</a> and <a href="#aaca42b5103c6b7f2cb9a050b61fed709a18402f81e9528c3cc41c781786e533b8">VREG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getConst() {#aba8e9cd16e177dd466270da4d046257b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * llvm::SDDbgOperand::getConst ()</td>
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

<p>Returns the Value* for a constant.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aaca42b5103c6b7f2cb9a050b61fed709aae386012326afbc26eeecc3701f36134">CONST</a>.</p>


<p>Referenced by <a href="#ae1199158a0e8d77e989464ad6b7274f3">operator==</a>.</p>

</div>
</div>

### getFrameIx() {#a820e4a5c816227c2d55e767f1148d48c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDDbgOperand::getFrameIx ()</td>
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

<p>Returns the FrameIx for a stack object.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aaca42b5103c6b7f2cb9a050b61fed709a8c6e740c1259b720ed9f87a05baf593b">FRAMEIX</a>.</p>


<p>Referenced by <a href="#ae1199158a0e8d77e989464ad6b7274f3">operator==</a>.</p>

</div>
</div>

### getKind() {#af7673427faa10f98864b7e7b9b008ec8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Kind llvm::SDDbgOperand::getKind ()</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a1157b5306838143f5553c67c1c8489c5">llvm::InstrEmitter::EmitDbgInstrRef</a>.</p>

</div>
</div>

### getResNo() {#a343fd12fb0de39a8f7bdfe6acbb9a1bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDDbgOperand::getResNo ()</td>
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

<p>Returns the ResNo for a register ref.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aaca42b5103c6b7f2cb9a050b61fed709aa35847085c9bc57f525640fa8ae5a15c">SDNODE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a1157b5306838143f5553c67c1c8489c5">llvm::InstrEmitter::EmitDbgInstrRef</a> and <a href="#ae1199158a0e8d77e989464ad6b7274f3">operator==</a>.</p>

</div>
</div>

### getSDNode() {#a94d6e361d3359e291427734fcc364582}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode * llvm::SDDbgOperand::getSDNode ()</td>
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

<p>Returns the SDNode* for a register ref.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aaca42b5103c6b7f2cb9a050b61fed709aa35847085c9bc57f525640fa8ae5a15c">SDNODE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a1157b5306838143f5553c67c1c8489c5">llvm::InstrEmitter::EmitDbgInstrRef</a> and <a href="#ae1199158a0e8d77e989464ad6b7274f3">operator==</a>.</p>

</div>
</div>

### getVReg() {#a4639cbb2d8bdbb307d236cb2fc165011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDDbgOperand::getVReg ()</td>
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

<p>Returns the Virtual <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> for a VReg.</p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aaca42b5103c6b7f2cb9a050b61fed709a18402f81e9528c3cc41c781786e533b8">VREG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a1157b5306838143f5553c67c1c8489c5">llvm::InstrEmitter::EmitDbgInstrRef</a> and <a href="#ae1199158a0e8d77e989464ad6b7274f3">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Const {#aa0f10cd8a8fe2541dff0ac89af0e0bd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value* llvm::SDDbgOperand::Const</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Valid for constants.</p>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>Referenced by <a href="#a839c3f734c6a978e745998e5d7904beb">fromConst</a>.</p>

</div>
</div>

### FrameIx {#a7db23494994080357ac7461ab7e278dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDDbgOperand::FrameIx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Valid for stack objects.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

### Node {#aeea131ba3ed6ae837d81c0a4fbdebef6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode* llvm::SDDbgOperand::Node</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Valid for expressions.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>Referenced by <a href="#a064ee6a43b2dc34747bda1d194922773">fromNode</a>.</p>

</div>
</div>

### ResNo {#a5221233d4cec2351331406959c3a52e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDDbgOperand::ResNo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Valid for expressions.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>Referenced by <a href="#a064ee6a43b2dc34747bda1d194922773">fromNode</a>.</p>

</div>
</div>

### s {#a64a8bd88a7b9d486d4d2786ae93f57cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct llvm::SDDbgOperand llvm::SDDbgOperand::s</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

### VReg {#a32648711fc7893749d02923c8d89fd81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDDbgOperand::VReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Valid for registers.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>Referenced by <a href="#a6e8946c426e13b7a8eac5f89fe1e8aca">fromVReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### kind {#a038d7fa68dbafe78da0f135e94cbac64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Kind llvm::SDDbgOperand::kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

### u {#afd945494e31224b033cb7764b5cf9bf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::SDDbgOperand llvm::SDDbgOperand::u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### fromConst() {#a839c3f734c6a978e745998e5d7904beb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDDbgOperand llvm::SDDbgOperand::fromConst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Const)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>Reference <a href="#aa0f10cd8a8fe2541dff0ac89af0e0bd5">Const</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instremitter/#ae0fecac8378f609fa3740fe1fd51465e">llvm::InstrEmitter::EmitDbgValueFromSingleOp</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8acecf5e81dffdc87f3e4e53e3d4954">llvm::SelectionDAG::getConstantDbgValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a4e84a47e3ca9c1684a752533e2881cd7">handleDanglingVariadicDebugInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae9748fb2e4d41aaa8ac80d00b2becc52">llvm::SelectionDAGBuilder::handleDebugValue</a>.</p>

</div>
</div>

### fromFrameIdx() {#a1ee3253416c1e239c9b70848aa4c4266}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDDbgOperand llvm::SDDbgOperand::fromFrameIdx (unsigned FrameIdx)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>Reference <a href="#aaca42b5103c6b7f2cb9a050b61fed709a8c6e740c1259b720ed9f87a05baf593b">FRAMEIX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a51c780ad3ec274798d9a18789cb527fc">llvm::SelectionDAG::getFrameIndexDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae9748fb2e4d41aaa8ac80d00b2becc52">llvm::SelectionDAGBuilder::handleDebugValue</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a582354e8d5806847614742270d2ece1d">llvm::SelectionDAG::salvageDebugInfo</a>.</p>

</div>
</div>

### fromNode() {#a064ee6a43b2dc34747bda1d194922773}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDDbgOperand llvm::SDDbgOperand::fromNode (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, unsigned ResNo)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>References <a href="#aeea131ba3ed6ae837d81c0a4fbdebef6">Node</a> and <a href="#a5221233d4cec2351331406959c3a52e8">ResNo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af1b7de0f063606a3701944a0db6dab1e">llvm::SelectionDAG::getDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae9748fb2e4d41aaa8ac80d00b2becc52">llvm::SelectionDAGBuilder::handleDebugValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a582354e8d5806847614742270d2ece1d">llvm::SelectionDAG::salvageDebugInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afce558f34a90609d76e4c2f45ab5650c">llvm::SelectionDAG::transferDbgValues</a>.</p>

</div>
</div>

### fromVReg() {#a6e8946c426e13b7a8eac5f89fe1e8aca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDDbgOperand llvm::SDDbgOperand::fromVReg (unsigned VReg)</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>References <a href="#aaca42b5103c6b7f2cb9a050b61fed709a18402f81e9528c3cc41c781786e533b8">VREG</a> and <a href="#a32648711fc7893749d02923c8d89fd81">VReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a26d0a06b03a545aecebd72387d0ffef0">llvm::SelectionDAG::getVRegDbgValue</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae9748fb2e4d41aaa8ac80d00b2becc52">llvm::SelectionDAGBuilder::handleDebugValue</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
