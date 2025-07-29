---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dielabel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DIELabel` Class

<p>A label <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DIELabel { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">llvm/CodeGen/DIE.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac74510346031d15ceff78263a8caa0a9">DIELabel</a> (const MCSymbol *L)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d41e0df87289fc2e7031bd46c7ce996">getValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a>. <a href="#a0d41e0df87289fc2e7031bd46c7ce996">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7449bea5953ed015a21a2de62080fadb">emitValue</a> (const AsmPrinter *AP, dwarf::Form Form) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitValue - Emit label value. <a href="#a7449bea5953ed015a21a2de62080fadb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab97161e774404eb79c753041676ee5fc">sizeOf</a> (const dwarf::FormParams &amp;FormParams, dwarf::Form Form) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>sizeOf - Determine size of label value in bytes. <a href="#ab97161e774404eb79c753041676ee5fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84b1bdf8e67e5c824edc012d9d746dbe">print</a> (raw_ostream &amp;O) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a55383c5823ba97b75af107d15e96e6">Label</a></td>
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

<p>A label <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DIELabel() {#ac74510346031d15ceff78263a8caa0a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DIELabel::DIELabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L)</td>
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



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitValue() {#a7449bea5953ed015a21a2de62080fadb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIELabel::emitValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * AP, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> Form)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EmitValue - Emit label value.</p>

<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>, definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/die-cpp">DIE.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac539bbd143ef2990cbecd2ad84692d5b">llvm::AsmPrinter::emitLabelReference</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aeba88c3eabd29e00e51c0db5b3a99ef9">llvm::AsmPrinter::getDwarfFormParams</a> and <a href="#ab97161e774404eb79c753041676ee5fc">sizeOf</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diestring/#a3f3c6f1cc283ec17fb31b0f3c84ccb4a">llvm::DIEString::emitValue</a>.</p>

</div>
</div>

### getValue() {#a0d41e0df87289fc2e7031bd46c7ce996}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol * llvm::DIELabel::getValue ()</td>
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

<p>Get <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a>.</p>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>

</div>
</div>

### print() {#a84b1bdf8e67e5c824edc012d9d746dbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void DIELabel::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>, definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/die-cpp">DIE.cpp</a>.</p>

</div>
</div>

### sizeOf() {#ab97161e774404eb79c753041676ee5fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DIELabel::sizeOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams">dwarf::FormParams</a> &amp; FormParams, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> Form)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>sizeOf - Determine size of label value in bytes.</p>

<p>Declaration at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>, definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/die-cpp">DIE.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams/#a6892519cfb3ec739ebd611d7bd82ea2e">llvm::dwarf::FormParams::AddrSize</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams/#a235a5f4eedbfa7b5583ba320309d408f">llvm::dwarf::FormParams::getDwarfOffsetByteSize</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a7449bea5953ed015a21a2de62080fadb">emitValue</a> and <a href="/web-llvm/docs/api/classes/llvm/diestring/#ab3e002a61d2a5203c2f67221b69172be">llvm::DIEString::sizeOf</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Label {#a9a55383c5823ba97b75af107d15e96e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol* llvm::DIELabel::Label</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/die-cpp">DIE.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
