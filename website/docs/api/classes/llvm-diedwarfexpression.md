---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/diedwarfexpression
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DIEDwarfExpression` Class

<p><a href="/web-llvm/docs/api/classes/llvm/dwarfexpression">DwarfExpression</a> implementation for singular DW_AT_location. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DIEDwarfExpression { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">CodeGen/AsmPrinter/DwarfExpression.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfexpression-2">DwarfExpression</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class containing the logic for constructing DWARF expressions independently of whether they are emitted into a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> or into a .debug_loc entry. <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression-2/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ef7ffd7796ad4423f7cd36c564cb5c0">DIEDwarfExpression</a> (const AsmPrinter &amp;AP, DwarfCompileUnit &amp;CU, DIELoc &amp;DIE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dieloc">DIELoc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24b5a14abc09026d9bf5b13f6fe0b2fa">finalize</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dieloc">DIELoc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ad4c7b069c674a1a4ba20fcee6a40b9">getActiveDIE</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> that currently is being emitted to. <a href="#a3ad4c7b069c674a1a4ba20fcee6a40b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a235de06467618084a0038913c4e4315b">emitOp</a> (uint8_t Op, const char *Comment=nullptr) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Output a dwarf operand and an optional assembler comment. <a href="#a235de06467618084a0038913c4e4315b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb2f75931c5fbbc7dbcd9d23d42a9393">emitSigned</a> (int64_t Value) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a raw signed value. <a href="#acb2f75931c5fbbc7dbcd9d23d42a9393">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb66965f65cb95594b0700b2e89dd2b7">emitUnsigned</a> (uint64_t Value) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a raw unsigned value. <a href="#adb66965f65cb95594b0700b2e89dd2b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14af173c9fcbff088be3b9ca06775744">emitData1</a> (uint8_t Value) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bb0a68ed0039fc7c268c3f75abe6898">emitBaseTypeRef</a> (uint64_t Idx) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab81c0fd4b103a0f7b18b186222784b7d">enableTemporaryBuffer</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Start emitting data to the temporary buffer. <a href="#ab81c0fd4b103a0f7b18b186222784b7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b12c610274030ddffb8f128ff962815">disableTemporaryBuffer</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disable emission to the temporary buffer. <a href="#a5b12c610274030ddffb8f128ff962815">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a325cf532553149934982f820650fd672">getTemporaryBufferSize</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the emitted size, in number of bytes, for the data stored in the temporary buffer. <a href="#a325cf532553149934982f820650fd672">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cfa327bbfadaa001b368298fd77bd02">commitTemporaryBuffer</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Commit the data stored in the temporary buffer to the main output. <a href="#a5cfa327bbfadaa001b368298fd77bd02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a549689791d8d99d00e0f78081381e675">isFrameRegister</a> (const TargetRegisterInfo &amp;TRI, llvm::Register MachineReg) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the given machine register is the frame register in the current function. <a href="#a549689791d8d99d00e0f78081381e675">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64d60d354d1ad0b5572aa95910344d76">AP</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dieloc">DIELoc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af543b865dd7cef80e472b6923dc56f05">OutDIE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dieloc">DIELoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1aed7331bd19f0b55b4211c3aadf4fa5">TmpDIE</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dbcf0a7af648b1d2640a5a369920c67">IsBuffering</a> = false</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/dwarfexpression">DwarfExpression</a> implementation for singular DW_AT_location.</p>

<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DIEDwarfExpression() {#a5ef7ffd7796ad4423f7cd36c564cb5c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIEDwarfExpression::DIEDwarfExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> &amp; AP, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; CU, <a href="/web-llvm/docs/api/classes/llvm/dieloc">DIELoc</a> &amp; DIE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af0f024a1be631b3865a2ac37210ad57c">llvm::DwarfExpression::DwarfExpression</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### finalize() {#a24b5a14abc09026d9bf5b13f6fe0b2fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIELoc * llvm::DIEDwarfExpression::finalize ()</td>
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



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2faa879061bc4989e0b78a0928d74e29">llvm::DwarfExpression::finalize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab71e26dc84728f514a94593242e6d931">llvm::DwarfCompileUnit::addAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aef8395275fb33cea31395023a1df1d54">llvm::DwarfCompileUnit::addComplexAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0284131decd7881e49a1dc2b82e4ac58">llvm::DwarfCompileUnit::constructCallSiteParmEntryDIEs</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">llvm::DwarfCompileUnit::updateSubprogramScopeDIE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### commitTemporaryBuffer() {#a5cfa327bbfadaa001b368298fd77bd02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEDwarfExpression::commitTemporaryBuffer ()</td>
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

<p>Commit the data stored in the temporary buffer to the main output.</p>

<p>Declaration at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### disableTemporaryBuffer() {#a5b12c610274030ddffb8f128ff962815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEDwarfExpression::disableTemporaryBuffer ()</td>
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

<p>Disable emission to the temporary buffer.</p>


<p>This does not commit data in the temporary buffer to the main output.</p>


<p>Declaration at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### emitBaseTypeRef() {#a8bb0a68ed0039fc7c268c3f75abe6898}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEDwarfExpression::emitBaseTypeRef (uint64_t Idx)</td>
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



<p>Declaration at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### emitData1() {#a14af173c9fcbff088be3b9ca06775744}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEDwarfExpression::emitData1 (uint8_t Value)</td>
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



<p>Declaration at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### emitOp() {#a235de06467618084a0038913c4e4315b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEDwarfExpression::emitOp (uint8_t Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Comment=nullptr)</td>
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

<p>Output a dwarf operand and an optional assembler comment.</p>

<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### emitSigned() {#acb2f75931c5fbbc7dbcd9d23d42a9393}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEDwarfExpression::emitSigned (int64_t Value)</td>
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

<p>Emit a raw signed value.</p>

<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### emitUnsigned() {#adb66965f65cb95594b0700b2e89dd2b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEDwarfExpression::emitUnsigned (uint64_t Value)</td>
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

<p>Emit a raw unsigned value.</p>

<p>Declaration at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### enableTemporaryBuffer() {#ab81c0fd4b103a0f7b18b186222784b7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEDwarfExpression::enableTemporaryBuffer ()</td>
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

<p>Start emitting data to the temporary buffer.</p>


<p>The data stored in the temporary buffer can be committed to the main output using <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ae9f7bf56f59e4092017760acc2cd2f6c">commitTemporaryBuffer()</a>.</p>


<p>Declaration at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### getActiveDIE() {#a3ad4c7b069c674a1a4ba20fcee6a40b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIELoc &amp; llvm::DIEDwarfExpression::getActiveDIE ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> that currently is being emitted to.</p>

<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>

</div>
</div>

### getTemporaryBufferSize() {#a325cf532553149934982f820650fd672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DIEDwarfExpression::getTemporaryBufferSize ()</td>
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

<p>Return the emitted size, in number of bytes, for the data stored in the temporary buffer.</p>

<p>Declaration at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

### isFrameRegister() {#a549689791d8d99d00e0f78081381e675}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DIEDwarfExpression::isFrameRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/classes/llvm/register">llvm::Register</a> MachineReg)</td>
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

<p>Return whether the given machine register is the frame register in the current function.</p>

<p>Declaration at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AP {#a64d60d354d1ad0b5572aa95910344d76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AsmPrinter&amp; llvm::DIEDwarfExpression::AP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>

</div>
</div>

### IsBuffering {#a2dbcf0a7af648b1d2640a5a369920c67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DIEDwarfExpression::IsBuffering = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>

</div>
</div>

### OutDIE {#af543b865dd7cef80e472b6923dc56f05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIELoc&amp; llvm::DIEDwarfExpression::OutDIE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>

</div>
</div>

### TmpDIE {#a1aed7331bd19f0b55b4211c3aadf4fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIELoc llvm::DIEDwarfExpression::TmpDIE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-cpp">DwarfUnit.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
