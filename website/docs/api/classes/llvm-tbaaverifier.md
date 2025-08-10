---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/tbaaverifier
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TBAAVerifier` Class

<p>Verify that the TBAA Metadatas are valid. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::TBAAVerifier { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">llvm/IR/Verifier.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0c97388ec16c5e1085504cf2faee1a0">TBAABaseNodeSummary</a> = std::pair&lt; bool, unsigned &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache of TBAA base nodes that have already been visited. <a href="#ad0c97388ec16c5e1085504cf2faee1a0">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e328dc567f1efc23a13fd039b560e03">TBAAVerifier</a> (VerifierSupport *Diagnostic=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a673dcb43872b8c1bd019eff06545c746">visitTBAAMetadata</a> (Instruction &amp;I, const MDNode *MD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Visit an instruction and return true if it is valid, return false if an invalid TBAA is attached. <a href="#a673dcb43872b8c1bd019eff06545c746">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... Tys&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8c2c6afddd2e1f8b67771ff604b7c1f7">CheckFailed</a> (Tys &amp;&amp;... Args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to diagnose a failure. <a href="#a8c2c6afddd2e1f8b67771ff604b7c1f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/verifiersupport">VerifierSupport</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3d3a092dd26f18f848903a4d07531c4">Diagnostic</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *, TBAABaseNodeSummary &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a608b2af2c432aefebbcd4e2d79ed4050">TBAABaseNodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39819cad42bd4ba05956288ae8b699dc">TBAAScalarNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps an alleged scalar TBAA node to a boolean that is true if the said TBAA node is a valid scalar TBAA node or false otherwise. <a href="#a39819cad42bd4ba05956288ae8b699dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Helper functions used by \c visitTBAAMetadata. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a761c7aa6a0c33512e8eccee6fb5ca472">getFieldNodeFromTBAABaseNode</a> (Instruction &amp;I, const MDNode *BaseNode, APInt &amp;Offset, bool IsNewFormat)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the field node at the offset <span class="doxyComputerOutput">Offset</span> in <span class="doxyComputerOutput">BaseNode</span>. <a href="#a761c7aa6a0c33512e8eccee6fb5ca472">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">TBAAVerifier::TBAABaseNodeSummary</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83b2eb6f8379a16736577c5bfe052f7d">verifyTBAABaseNode</a> (Instruction &amp;I, const MDNode *BaseNode, bool IsNewFormat)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify that <span class="doxyComputerOutput">BaseNode</span> can be used as the "base type" in the struct-path TBAA scheme. <a href="#a83b2eb6f8379a16736577c5bfe052f7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">TBAABaseNodeSummary</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a241c02ae78229e0facd19dcccd040315">verifyTBAABaseNodeImpl</a> (Instruction &amp;I, const MDNode *BaseNode, bool IsNewFormat)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a958dac7df16a338e2d910947a319335d">isValidScalarTBAANode</a> (const MDNode *MD)</td>
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

<p>Verify that the TBAA Metadatas are valid.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">Verifier.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### TBAABaseNodeSummary {#ad0c97388ec16c5e1085504cf2faee1a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::TBAAVerifier::TBAABaseNodeSummary =  std::pair&lt;bool, unsigned&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cache of TBAA base nodes that have already been visited.</p>


<p>This cachce maps a node that has been visited to a pair (IsInvalid, BitWidth) where</p>


<p><span class="doxyComputerOutput">IsInvalid</span> is true iff the node is invalid. <span class="doxyComputerOutput">BitWidth</span>, if non-zero, is the bitwidth of the integer used to denoting the offset of the access. If zero, only a zero offset is allowed.</p>


<p><span class="doxyComputerOutput">BitWidth</span> has no meaning if <span class="doxyComputerOutput">IsInvalid</span> is true.</p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">Verifier.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### TBAAVerifier() {#a7e328dc567f1efc23a13fd039b560e03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TBAAVerifier::TBAAVerifier (<a href="/web-llvm/docs/api/structs/llvm/verifiersupport">VerifierSupport</a> * Diagnostic=nullptr)</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">Verifier.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### visitTBAAMetadata() {#a673dcb43872b8c1bd019eff06545c746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TBAAVerifier::visitTBAAMetadata (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * MD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Visit an instruction and return true if it is valid, return false if an invalid TBAA is attached.</p>

<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">Verifier.h</a>, definition at line 7619 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/verifier-cpp">Verifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/verifier-cpp/#a934b8d5c71f219800cd90a7290bc1395">CheckTBAA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#a2d40c0621205b0cbd5f642d970cbb896">llvm::mdconst::dyn_extract_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af59335be18fa802d111a646be658b7d0a68a576ae5bab85b26f5e5a947d3b41e8">llvm::Invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/verifier-cpp/#a40a20a7e0742e758b1b960df91c2a3c4">isNewFormatTBAATypeNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/verifier-cpp/#aabc105da5cddb4a47b777cec92ef8a6a">IsRootTBAANode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### CheckFailed() {#a8c2c6afddd2e1f8b67771ff604b7c1f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... Tys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TBAAVerifier::CheckFailed (Tys &amp;&amp;... Args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to diagnose a failure.</p>


<p>Helper to issue failure from the TBAA verification.</p>


<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">Verifier.h</a>, definition at line 7383 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/verifier-cpp">Verifier.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Diagnostic {#af3d3a092dd26f18f848903a4d07531c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VerifierSupport* llvm::TBAAVerifier::Diagnostic = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">Verifier.h</a>.</p>

</div>
</div>

### TBAABaseNodes {#a608b2af2c432aefebbcd4e2d79ed4050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MDNode *, TBAABaseNodeSummary&gt; llvm::TBAAVerifier::TBAABaseNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">Verifier.h</a>.</p>

</div>
</div>

### TBAAScalarNodes {#a39819cad42bd4ba05956288ae8b699dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MDNode *, bool&gt; llvm::TBAAVerifier::TBAAScalarNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps an alleged scalar TBAA node to a boolean that is true if the said TBAA node is a valid scalar TBAA node or false otherwise.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">Verifier.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Helper functions used by \c visitTBAAMetadata.

### getFieldNodeFromTBAABaseNode {#a761c7aa6a0c33512e8eccee6fb5ca472}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * TBAAVerifier::getFieldNodeFromTBAABaseNode (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * BaseNode, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Offset, bool IsNewFormat)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the field node at the offset <span class="doxyComputerOutput">Offset</span> in <span class="doxyComputerOutput">BaseNode</span>.</p>


<p>Update <span class="doxyComputerOutput">Offset</span> in place to be the offset within the field node returned.</p>


<p>We assume we've okayed <span class="doxyComputerOutput">BaseNode</span> via <span class="doxyComputerOutput">verifyTBAABaseNode</span>.</p>


<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">Verifier.h</a>, definition at line 7570 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/verifier-cpp">Verifier.cpp</a>.</p>

</div>
</div>

### isValidScalarTBAANode {#a958dac7df16a338e2d910947a319335d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TBAAVerifier::isValidScalarTBAANode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * MD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">Verifier.h</a>, definition at line 7552 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/verifier-cpp">Verifier.cpp</a>.</p>

</div>
</div>

### verifyTBAABaseNode {#a83b2eb6f8379a16736577c5bfe052f7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TBAAVerifier::TBAABaseNodeSummary TBAAVerifier::verifyTBAABaseNode (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * BaseNode, bool IsNewFormat)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify that <span class="doxyComputerOutput">BaseNode</span> can be used as the "base type" in the struct-path TBAA scheme.</p>


<p>This means <span class="doxyComputerOutput">BaseNode</span> is either a scalar node, or a struct-type node describing an aggregate data structure (like a struct).</p>


<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">Verifier.h</a>, definition at line 7400 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/verifier-cpp">Verifier.cpp</a>.</p>

</div>
</div>

### verifyTBAABaseNodeImpl {#a241c02ae78229e0facd19dcccd040315}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TBAAVerifier::TBAABaseNodeSummary TBAAVerifier::verifyTBAABaseNodeImpl (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * BaseNode, bool IsNewFormat)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">Verifier.h</a>, definition at line 7419 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/verifier-cpp">Verifier.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">Verifier.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/verifier-cpp">Verifier.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
