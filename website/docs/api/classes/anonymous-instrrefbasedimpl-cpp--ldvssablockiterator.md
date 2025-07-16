---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssablockiterator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LDVSSABlockIterator` Class Reference

<p>Thin wrapper around a block predecessor iterator. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{InstrRefBasedImpl.cpp}::LDVSSABlockIterator { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cb3323fa2b3b2abb6bd3fcf128ee7a2">LDVSSABlockIterator</a> (MachineBasicBlock::pred_iterator PredIt, LDVSSAUpdater &amp;Updater)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7842f5deb6d697238863b6cd4ccc8aa5">operator!=</a> (const LDVSSABlockIterator &amp;OtherIt) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssablockiterator">LDVSSABlockIterator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69d4b9194c4510cf2c2d5286061d0bac">operator++</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssablock">LDVSSABlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a279dffdd489fe0fb2f1559453621b70c">operator*</a> ()</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa3e6549a5c552971ce60013e2e7c6154">MachineBasicBlock::pred_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31af0a5cb9b734578738655611d5eb9b">PredIt</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssaupdater">LDVSSAUpdater</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fd5939940a95797c33957bff1f24e1f">Updater</a></td>
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

<p>Thin wrapper around a block predecessor iterator.</p>


<p>Only difference from a normal block iterator is that it dereferences to an <a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssablock">LDVSSABlock</a>.</p>


<p>Definition at line 3895 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LDVSSABlockIterator() {#a1cb3323fa2b3b2abb6bd3fcf128ee7a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InstrRefBasedImpl.cpp}::LDVSSABlockIterator::LDVSSABlockIterator (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa3e6549a5c552971ce60013e2e7c6154">MachineBasicBlock::pred_iterator</a> PredIt, <a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssaupdater">LDVSSAUpdater</a> &amp; Updater)</td>
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



<p>Definition at line 3900 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#a31af0a5cb9b734578738655611d5eb9b">PredIt</a> and <a href="#a2fd5939940a95797c33957bff1f24e1f">Updater</a>.</p>


<p>Referenced by <a href="#a7842f5deb6d697238863b6cd4ccc8aa5">operator!=</a> and <a href="#a69d4b9194c4510cf2c2d5286061d0bac">operator++</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a7842f5deb6d697238863b6cd4ccc8aa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InstrRefBasedImpl.cpp}::LDVSSABlockIterator::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssablockiterator">LDVSSABlockIterator</a> &amp; OtherIt)</td>
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



<p>Definition at line 3904 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#a1cb3323fa2b3b2abb6bd3fcf128ee7a2">LDVSSABlockIterator</a> and <a href="#a31af0a5cb9b734578738655611d5eb9b">PredIt</a>.</p>

</div>
</div>

### operator\*() {#a279dffdd489fe0fb2f1559453621b70c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LDVSSABlock * anonymous{InstrRefBasedImpl.cpp}::LDVSSABlockIterator::operator* ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3913 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#a31af0a5cb9b734578738655611d5eb9b">PredIt</a> and <a href="#a2fd5939940a95797c33957bff1f24e1f">Updater</a>.</p>

</div>
</div>

### operator++() {#a69d4b9194c4510cf2c2d5286061d0bac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LDVSSABlockIterator &amp; anonymous{InstrRefBasedImpl.cpp}::LDVSSABlockIterator::operator++ ()</td>
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



<p>Definition at line 3908 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#a1cb3323fa2b3b2abb6bd3fcf128ee7a2">LDVSSABlockIterator</a> and <a href="#a31af0a5cb9b734578738655611d5eb9b">PredIt</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### PredIt {#a31af0a5cb9b734578738655611d5eb9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::pred_iterator anonymous{InstrRefBasedImpl.cpp}::LDVSSABlockIterator::PredIt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3897 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#a1cb3323fa2b3b2abb6bd3fcf128ee7a2">LDVSSABlockIterator</a>, <a href="#a7842f5deb6d697238863b6cd4ccc8aa5">operator!=</a>, <a href="#a279dffdd489fe0fb2f1559453621b70c">operator*</a> and <a href="#a69d4b9194c4510cf2c2d5286061d0bac">operator++</a>.</p>

</div>
</div>

### Updater {#a2fd5939940a95797c33957bff1f24e1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LDVSSAUpdater&amp; anonymous{InstrRefBasedImpl.cpp}::LDVSSABlockIterator::Updater</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3898 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#a1cb3323fa2b3b2abb6bd3fcf128ee7a2">LDVSSABlockIterator</a> and <a href="#a279dffdd489fe0fb2f1559453621b70c">operator*</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
