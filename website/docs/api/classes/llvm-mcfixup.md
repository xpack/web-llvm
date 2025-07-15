---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcfixup
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCFixup` Class Reference

<p>Encode information on a single operation to perform on a byte sequence (e.g., an encoded instruction) which requires assemble- or run- time patching. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCFixup { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixup-h">llvm/MC/MCFixup.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe6bd9f0a68df78d2b0bfc4dc4f944a2">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac48c4d70cf3d66358cfdaf19f0de4c10">getTargetKind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d15eb9e5fcc1aefad18f4f9f7dcbc66">getOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac63cc432cdbc99aa9dc409c090408101">setOffset</a> (uint32_t Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1766447693abfb2e612a4d394f8b4cd0">getValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb9af7b67ece52d00b79892e70df8ef0">getLoc</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf2bbab77a111bcea35e0b15ea5d64e3">Value</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The value to put into the fixup location. <a href="#aaf2bbab77a111bcea35e0b15ea5d64e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0f2e7d44e1d7d35dbd66fb8ffa88f77">Offset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The byte index of start of the relocation inside the <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a>. <a href="#ae0f2e7d44e1d7d35dbd66fb8ffa88f77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a637222d56cf8158c53eed969881a9497">Kind</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a845a63cbed041d42d8c3452991d629c4">FK_NONE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The target dependent kind of fixup item this is. <a href="#a637222d56cf8158c53eed969881a9497">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5db88fe3e571e508d691b24405f6d18a">Loc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The source location which gave rise to the fixup, if any. <a href="#a5db88fe3e571e508d691b24405f6d18a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdf37854fa6eb68017b96486df443a32">create</a> (uint32_t Offset, const MCExpr *Value, MCFixupKind Kind, SMLoc Loc=SMLoc())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a027f3fd5c51a6c8a23501952450f489b">getKindForSize</a> (unsigned Size, bool IsPCRel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the generic fixup kind for a value with the given size. <a href="#a027f3fd5c51a6c8a23501952450f489b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Encode information on a single operation to perform on a byte sequence (e.g., an encoded instruction) which requires assemble- or run- time patching.</p>


<p>Fixups are used any time the target instruction encoder needs to represent some value in an instruction which is not yet concrete. The encoder will encode the instruction assuming the value is 0, and emit a fixup which communicates to the assembler backend how it should rewrite the encoded value.</p>


<p>During the process of relaxation, the assembler will apply fixups as symbolic values become concrete. When relaxation is complete, any remaining fixups become relocations in the object file (or errors, if the fixup cannot be encoded on the target).</p>


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixup-h">MCFixup.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getKind() {#afe6bd9f0a68df78d2b0bfc4dc4f944a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFixupKind llvm::MCFixup::getKind ()</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixup-h">MCFixup.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3370dd99cc932848c8d138025137ad6a">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### getLoc() {#aeb9af7b67ece52d00b79892e70df8ef0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::MCFixup::getLoc ()</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixup-h">MCFixup.h</a>.</p>

</div>
</div>

### getOffset() {#a6d15eb9e5fcc1aefad18f4f9f7dcbc66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MCFixup::getOffset ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixup-h">MCFixup.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a5461102b304d92530e9a6e3afcd47b30">llvm::RISCVAsmBackend::evaluateTargetFixup</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3370dd99cc932848c8d138025137ad6a">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### getTargetKind() {#ac48c4d70cf3d66358cfdaf19f0de4c10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCFixup::getTargetKind ()</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixup-h">MCFixup.h</a>.</p>

</div>
</div>

### getValue() {#a1766447693abfb2e612a4d394f8b4cd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * llvm::MCFixup::getValue ()</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixup-h">MCFixup.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a5461102b304d92530e9a6e3afcd47b30">llvm::RISCVAsmBackend::evaluateTargetFixup</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3370dd99cc932848c8d138025137ad6a">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### setOffset() {#ac63cc432cdbc99aa9dc409c090408101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCFixup::setOffset (uint32_t Value)</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixup-h">MCFixup.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Kind {#a637222d56cf8158c53eed969881a9497}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFixupKind llvm::MCFixup::Kind = <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a845a63cbed041d42d8c3452991d629c4">FK_NONE</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The target dependent kind of fixup item this is.</p>


<p>The kind is used to determine how the operand value should be encoded into the instruction.</p>


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixup-h">MCFixup.h</a>.</p>

</div>
</div>

### Loc {#a5db88fe3e571e508d691b24405f6d18a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::MCFixup::Loc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The source location which gave rise to the fixup, if any.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixup-h">MCFixup.h</a>.</p>

</div>
</div>

### Offset {#ae0f2e7d44e1d7d35dbd66fb8ffa88f77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MCFixup::Offset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The byte index of start of the relocation inside the <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a>.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixup-h">MCFixup.h</a>.</p>

</div>
</div>

### Value {#aaf2bbab77a111bcea35e0b15ea5d64e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::MCFixup::Value = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The value to put into the fixup location.</p>


<p>The exact interpretation of the expression is target dependent, usually it will be one of the operands to an instruction or an assembler directive.</p>


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixup-h">MCFixup.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#abdf37854fa6eb68017b96486df443a32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFixup llvm::MCFixup::create (uint32_t Offset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixup-h">MCFixup.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a59a8b044cb17aa6a16dd766e02308afe">llvm::MaxFixupKind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a1b7e117c34782423f4cab2396b42b059">llvm::MCWinCOFFStreamer::emitCOFFImgRel32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#ab111e0970f34dbb0c62ace14e515819c">llvm::MCWinCOFFStreamer::emitCOFFSecNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a4231cebc046e4dba7b742b6d31bd1d01">llvm::MCWinCOFFStreamer::emitCOFFSecOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a6dbbe16f1a57144b250b2b3ba1243e93">llvm::MCWinCOFFStreamer::emitCOFFSecRel32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a0cce678ce28a97e39af6a60a52daac7f">llvm::MCWinCOFFStreamer::emitCOFFSectionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a64117626e72c6d42f4c970c4a8419fad">llvm::MCObjectStreamer::emitDTPRel32Value</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#af9ffc6b71a4df398a73b14eb57013b99">llvm::MCObjectStreamer::emitDTPRel64Value</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a941d139388690bb273865a4a89eb6841">llvm::MCObjectStreamer::emitGPRel32Value</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a83a13ea025b64786cb5e900f7a97af71">llvm::MCObjectStreamer::emitGPRel64Value</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a8dfc15625ed04fb03d221eaebf38fd56">llvm::MCObjectStreamer::emitRelocDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#ae04524e366e748f2f9cd204cbb3f7805">llvm::MCObjectStreamer::emitTPRel32Value</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#adae79862b47707b93f6d3af0eec9e633">llvm::MCObjectStreamer::emitTPRel64Value</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9ef24f653b777a160537ee3e1d824663">llvm::MCObjectStreamer::emitValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcxcoffstreamer/#a74f3eb9157be6847f5bf0f9cd228ad01">llvm::MCXCOFFStreamer::emitXCOFFRefDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#aea53ea050c3442abffd1c991f4c7213a">llvm::CodeViewContext::encodeDefRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mccodeemitter-cpp-/aarch64mccodeemitter/#a339bb20fead6005cd1cc37f479650617">anonymous{AArch64MCCodeEmitter.cpp}::AArch64MCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kmccodeemitter-cpp-/m68kmccodeemitter/#ae9def4fef17a8e66265e30f687158adf">anonymous{M68kMCCodeEmitter.cpp}::M68kMCCodeEmitter::encodePCRelImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kmccodeemitter-cpp-/m68kmccodeemitter/#a642ca54e0f1605190dcf5a216d2b10b6">anonymous{M68kMCCodeEmitter.cpp}::M68kMCCodeEmitter::encodeRelocImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmccodeemitter-cpp-/loongarchmccodeemitter/#ac6740cbf8bbdd52574f85db63500cd25">anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::expandAddTPRel</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#afa2b2e58e0859c0608b6f10a8ad1c79f">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::expandAddTPRel</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#aa9f55bb589105b8751fa61098690db0b">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::expandLongCondBr</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#a949f92840302b18bc451d406ddeb09a9">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::expandTLSDESCCall</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#a8cc7b966523b32a8fdafed49d3493257">llvm::PPCMCCodeEmitter::getAbsCondBrEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#a19648643b2a3316cc1fa4d2bc61fd50f">llvm::PPCMCCodeEmitter::getAbsDirectBrEncoding</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a2d0dda09f20d0ebce689e4a66fb95336">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getAddrMode3OpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#ad8e82a3b2fdfbba528962f3c010088ac">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getAddrMode5FP16OpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#ac5de66a883970fc59be6f0673634a0f8">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getAddrMode5OpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#ae59e2396e8599842bb67dc2851e9b87c">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getAddrModeImm12OpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mccodeemitter-cpp-/aarch64mccodeemitter/#a902e7f80ee2b8750ee2be2fdbafffdba">anonymous{AArch64MCCodeEmitter.cpp}::AArch64MCCodeEmitter::getAddSubImmOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mccodeemitter-cpp-/aarch64mccodeemitter/#a52c57b55877964bca8f9690fd4ab336e">anonymous{AArch64MCCodeEmitter.cpp}::AArch64MCCodeEmitter::getAdrLabelOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymccodeemitter/#ad639f513acb55b87a86bfc216cff9052">llvm::CSKYMCCodeEmitter::getBareSymbolOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a0eb22c22d4dc362aa5e15bb7cd1a4edb">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getBFAfterTargetOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcmccodeemitter-cpp-/sparcmccodeemitter/#a7892e0c38b91e8b5abc65fed9615ce36">anonymous{SparcMCCodeEmitter.cpp}::SparcMCCodeEmitter::getBranchOnRegTargetOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcmccodeemitter-cpp-/sparcmccodeemitter/#a6ec698a5a0582d691b94118488dfc991">anonymous{SparcMCCodeEmitter.cpp}::SparcMCCodeEmitter::getBranchPredTargetOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymccodeemitter/#ae0d5413e8969be7638d03ff8c9e65353">llvm::CSKYMCCodeEmitter::getBranchSymbolOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#a1a53bd2f56709e4b8ec00e8ae0447e4f">llvm::MipsMCCodeEmitter::getBranchTarget21OpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#add4d66dd8382e6b4fe7fa789844f1e27">llvm::MipsMCCodeEmitter::getBranchTarget21OpValueMM</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#a9332e7f86488ac03e792fde668bac68e">llvm::MipsMCCodeEmitter::getBranchTarget26OpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#a93c2d268f594d31d146df08d1c0e007e">llvm::MipsMCCodeEmitter::getBranchTarget26OpValueMM</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#af5247a7a6102eac959399f11a6e34acf">llvm::MipsMCCodeEmitter::getBranchTarget7OpValueMM</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mccodeemitter-cpp-/aarch64mccodeemitter/#a46bc568601e10733c35b0060e7e5ed4c">anonymous{AArch64MCCodeEmitter.cpp}::AArch64MCCodeEmitter::getBranchTargetOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcmccodeemitter-cpp-/sparcmccodeemitter/#a8bf6ae54e9126935f6b208325e10f0d9">anonymous{SparcMCCodeEmitter.cpp}::SparcMCCodeEmitter::getBranchTargetOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-vemccodeemitter-cpp-/vemccodeemitter/#af3ce5b31f39b940d7baf95da2630290f">anonymous{VEMCCodeEmitter.cpp}::VEMCCodeEmitter::getBranchTargetOpValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmccodeemitter-cpp/#ac71adedf5a7e045a327f230a16a3984d">getBranchTargetOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-lanaimccodeemitter-cpp-/lanaimccodeemitter/#a6e49231451b0b2b51a7e033254ccb415">llvm::anonymous{LanaiMCCodeEmitter.cpp}::LanaiMCCodeEmitter::getBranchTargetOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#a6b63701360781e817473a4818ce94912">llvm::MipsMCCodeEmitter::getBranchTargetOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#aa1dfb38c5dc5e51389464d20e369678f">llvm::MipsMCCodeEmitter::getBranchTargetOpValue1SImm16</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#a07ecbb2c17eb03d8c4755dc5cfd88a5a">llvm::MipsMCCodeEmitter::getBranchTargetOpValueLsl2MMR6</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#acfb54999283e22ee0b67ff582f4d2c66">llvm::MipsMCCodeEmitter::getBranchTargetOpValueMM</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#abbdc431653da80629c9b3e495cd09477">llvm::MipsMCCodeEmitter::getBranchTargetOpValueMMPC10</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#a6928f0f796b63f34abf586618d0ebba7">llvm::MipsMCCodeEmitter::getBranchTargetOpValueMMR6</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymccodeemitter/#a08ac76217df04bb70d79e961194d3d26">llvm::CSKYMCCodeEmitter::getCallSymbolOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcmccodeemitter-cpp-/sparcmccodeemitter/#a1d086ef68afbc813e0403f73866b1cdb">anonymous{SparcMCCodeEmitter.cpp}::SparcMCCodeEmitter::getCallTargetOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mccodeemitter-cpp-/aarch64mccodeemitter/#a736ddf8abfb81cfb3db83edb54e7a237">anonymous{AArch64MCCodeEmitter.cpp}::AArch64MCCodeEmitter::getCondBranchTargetOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#ae6515e760279b2f6a636da48d69bb1e1">llvm::PPCMCCodeEmitter::getCondBrEncoding</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mccodeemitter-cpp-/aarch64mccodeemitter/#a931246f347ac852c74a6b063ce98723e">anonymous{AArch64MCCodeEmitter.cpp}::AArch64MCCodeEmitter::getCondCompBranchTargetOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymccodeemitter/#a4b28c7cecddbd6c9aae7628ac71f365b">llvm::CSKYMCCodeEmitter::getConstpoolSymbolOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymccodeemitter/#a5a26e3bd1555734e7aa5a82457ddc0e1">llvm::CSKYMCCodeEmitter::getDataSymbolOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#a62af4354feb24bedc02c1c2f1f7fdd11">llvm::PPCMCCodeEmitter::getDirectBrEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#a889d08bf85a0f9f722a635fc75dbf655">llvm::PPCMCCodeEmitter::getDispRI34PCRelEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#a8d1529cc5d19fd99123fdf53493d0ccf">llvm::PPCMCCodeEmitter::getDispRIEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#a86dfc50cf507aaaa3f2d660057c66490">llvm::PPCMCCodeEmitter::getDispRIX16Encoding</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#a65a983b3c19bd68b7f0cf26767ffa8a8">llvm::PPCMCCodeEmitter::getDispRIXEncoding</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmccodeemitter-cpp-/loongarchmccodeemitter/#a496a589a4ca89aafae1db05782b62cde">anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::getExprOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#acf7d45b48b59184a87282440d441609b">llvm::MipsMCCodeEmitter::getExprOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a074988b040a84697d348ccce68db0f11">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getHiLoImmOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#ab479efba6d5a4d364aef9c816ea8b4df">llvm::PPCMCCodeEmitter::getImm16Encoding</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#ad6d3a088c61bdd49d330e0847cc53203">llvm::PPCMCCodeEmitter::getImm34Encoding</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#a847e5bb4507e49e9af8582df2cb12f50">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::getImmOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzmccodeemitter-cpp-/systemzmccodeemitter/#a52a49374d3b99fe9ff49126a83e41af5">anonymous{SystemZMCCodeEmitter.cpp}::SystemZMCCodeEmitter::getImmOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymccodeemitter/#a147f7ed39465e029fa4ac16137fee7c4">llvm::CSKYMCCodeEmitter::getImmOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#ab855c610a96ab5a941e04fb256f26b86">llvm::MipsMCCodeEmitter::getJumpOffset16OpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#abc521544e887817d3216cc4a9ff8728d">llvm::MipsMCCodeEmitter::getJumpTargetOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#a2763682cbcdfe2574b86f793a7c21113">llvm::MipsMCCodeEmitter::getJumpTargetOpValueMM</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mccodeemitter-cpp-/aarch64mccodeemitter/#a8d69eee932663089db6b828b70a58e33">anonymous{AArch64MCCodeEmitter.cpp}::AArch64MCCodeEmitter::getLdStUImm12OpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mccodeemitter-cpp-/aarch64mccodeemitter/#a0ae8afd095d1cecd6814b8b41533b644">anonymous{AArch64MCCodeEmitter.cpp}::AArch64MCCodeEmitter::getLoadLiteralOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfmccodeemitter-cpp-/bpfmccodeemitter/#a955c8163dbb18d99c96c57d1c4b273f0">anonymous{BPFMCCodeEmitter.cpp}::BPFMCCodeEmitter::getMachineOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600mccodeemitter-cpp-/r600mccodeemitter/#a23872fe93b592c366eda32fde4753000">anonymous{R600MCCodeEmitter.cpp}::R600MCCodeEmitter::getMachineOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcmccodeemitter-cpp-/sparcmccodeemitter/#aa978700d5b14950870512c1cf663ea29">anonymous{SparcMCCodeEmitter.cpp}::SparcMCCodeEmitter::getMachineOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-vemccodeemitter-cpp-/vemccodeemitter/#a5d67d6276a93134bb4545dae3669fba3">anonymous{VEMCCodeEmitter.cpp}::VEMCCodeEmitter::getMachineOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-lanaimccodeemitter-cpp-/lanaimccodeemitter/#a0e3a46287a3ec80268b6629a7298532b">llvm::anonymous{LanaiMCCodeEmitter.cpp}::LanaiMCCodeEmitter::getMachineOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a77957bdbfbac5aedc5c0ad3bd28bd2ee">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getModImmOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mccodeemitter-cpp-/aarch64mccodeemitter/#ae6e243f515fb6b4c69457c0867592d63">anonymous{AArch64MCCodeEmitter.cpp}::AArch64MCCodeEmitter::getMoveWideImmOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mccodeemitter-cpp-/aarch64mccodeemitter/#adf6604468a31afb49af2c88252d4e360">anonymous{AArch64MCCodeEmitter.cpp}::AArch64MCCodeEmitter::getPAuthPCRelOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcmccodeemitter-cpp-/sparcmccodeemitter/#a0070c42d3968ffb347c090fa0cd5d0ea">anonymous{SparcMCCodeEmitter.cpp}::SparcMCCodeEmitter::getSImm13OpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#aa5becc8cd122d129322781eea44bc0ec">llvm::MipsMCCodeEmitter::getSimm18Lsl3Encoding</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#a24ca4877399866d480d4db5f3a9df4ee">llvm::MipsMCCodeEmitter::getSimm19Lsl2Encoding</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpumccodeemitter-cpp-/amdgpumccodeemitter/#a71b68f9cbc43e59ed1e8689245ecb0d3">anonymous{AMDGPUMCCodeEmitter.cpp}::AMDGPUMCCodeEmitter::getSOPPBrEncoding</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a452a3401f1c632e0aa8f7761dcb80511">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getT2AddrModeImm8s4OpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#ab73e06d0bd809df774a1c115ccf6bb74">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getT2SOImmOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mccodeemitter-cpp-/aarch64mccodeemitter/#a4f69cf496ca3871e7c496029a2cf29ce">anonymous{AArch64MCCodeEmitter.cpp}::AArch64MCCodeEmitter::getTestBranchTargetOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#ae86b5ecb43dc109bc0648fe697e8599a">llvm::PPCMCCodeEmitter::getTLSCallEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#a7759c46e30fcf1d9af690f2788cac998">llvm::PPCMCCodeEmitter::getTLSRegEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#ad8e9bd47b27dc42d0fc9b49ca743ba8d">llvm::LoongArchAsmBackend::handleAddSubRelocations</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a9f4b22b2ab12c7d26784790f13aeb273">llvm::RISCVAsmBackend::handleAddSubRelocations</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#abd062e69c3b1b4a76b873edc1127443a">llvm::LoongArchAsmBackend::relaxDwarfCFA</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a172850f33ba1afc4850ad347040d02a7">llvm::RISCVAsmBackend::relaxDwarfCFA</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a09963de4b3b90f89cf9f9b6f154af6bd">llvm::LoongArchAsmBackend::relaxDwarfLineAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a056a7266fa88806c3f88ab217fac6e4e">llvm::RISCVAsmBackend::relaxDwarfLineAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a6ffd2d1f64a9104fc1a62c1387fca16e">llvm::LoongArchAsmBackend::relaxLEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a0b10511c4a52fc282850610c648ba455">llvm::RISCVAsmBackend::relaxLEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a36a4b135a95576724f4b520be6063ef1">llvm::LoongArchAsmBackend::shouldInsertFixupForCodeAlign</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a9f78db3a67945349cd7bcee045f65b1b">llvm::RISCVAsmBackend::shouldInsertFixupForCodeAlign</a>.</p>

</div>
</div>

### getKindForSize() {#a027f3fd5c51a6c8a23501952450f489b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCFixupKind llvm::MCFixup::getKindForSize (unsigned Size, bool IsPCRel)</td>
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

<p>Return the generic fixup kind for a value with the given size.</p>


<p>It is an error to pass an unsupported size.</p>


<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixup-h">MCFixup.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58ac6095ed6f2c30887aef8adc449b1efa5">llvm::FK_PCRel_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a11803cd0814af72a9d078ac0f7a33137">llvm::FK_PCRel_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a0f7a8485c2c761bc5e870fe2b6466372">llvm::FK_PCRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a7fa4d5bb1573ffbf54e99ae1fe36ad6e">llvm::FK_PCRel_8</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9ef24f653b777a160537ee3e1d824663">llvm::MCObjectStreamer::emitValueImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp/#a2f19df74000cc1d12eb853e57c867afb">getImmFixupKind</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixup-h">MCFixup.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
