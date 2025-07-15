---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/regbankselect/instrinsertpoint
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InstrInsertPoint` Class Reference

<p>Insertion point before or after an instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::RegBankSelect::InstrInsertPoint { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">llvm/CodeGen/GlobalISel/RegBankSelect.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regbankselect/insertpoint">InsertPoint</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract class used to represent an insertion point in a CFG. <a href="/web-llvm/docs/api/classes/llvm/regbankselect/insertpoint/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc84b9482ccab01341e9694c14933d7">InstrInsertPoint</a> (MachineInstr &amp;Instr, bool Before=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an insertion point before (<span class="doxyComputerOutput">Before=true</span>) or after <span class="doxyComputerOutput">Instr</span>. <a href="#a6cc84b9482ccab01341e9694c14933d7">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bf99289cea710aff85335a6cc7aefb6">isSplit</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does this point involve splitting an edge or block? <a href="#a8bf99289cea710aff85335a6cc7aefb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfe02f412f4221fbb6a31ca758ac297e">frequency</a> (const Pass &amp;P) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Frequency of the insertion point. <a href="#acfe02f412f4221fbb6a31ca758ac297e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62245784637a216888785f1517944d0e">canMaterialize</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this insertion point can be materialized. <a href="#a62245784637a216888785f1517944d0e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9fca3e14242c876cbb24f199eb947ca">materialize</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Materialize the insertion point. <a href="#af9fca3e14242c876cbb24f199eb947ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22cd58a1cdc6cb197f000d26e6de5a9c">getPointImpl</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the materialized insertion point. <a href="#a22cd58a1cdc6cb197f000d26e6de5a9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88065cc9f438702ad30cec934cf7aaac">getInsertMBBImpl</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the materialized insertion basic block. <a href="#a88065cc9f438702ad30cec934cf7aaac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf24086ba86b54bc4c21ca0888ca7b29">Instr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insertion point. <a href="#abf24086ba86b54bc4c21ca0888ca7b29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeff9d399ba6420ec1c5b2306de26f1fd">Before</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does the insertion point is before or after Instr. <a href="#aeff9d399ba6420ec1c5b2306de26f1fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Insertion point before or after an instruction.</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InstrInsertPoint() {#a6cc84b9482ccab01341e9694c14933d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegBankSelect::InstrInsertPoint::InstrInsertPoint (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Instr, bool Before=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an insertion point before (<span class="doxyComputerOutput">Before=true</span>) or after <span class="doxyComputerOutput">Instr</span>.</p>

<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 877 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### canMaterialize() {#a62245784637a216888785f1517944d0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegBankSelect::InstrInsertPoint::canMaterialize ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this insertion point can be materialized.</p>


<p>As soon as <a href="/web-llvm/docs/api/classes/llvm/regbankselect/insertpoint/#a7a0275cf0b23f61fed8b27a60dd950a5">getPoint</a> is called and thus, the point materialized calling this method does not make sense.</p>


<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

### frequency() {#acfe02f412f4221fbb6a31ca758ac297e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t RegBankSelect::InstrInsertPoint::frequency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> &amp; P)</td>
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

<p>Frequency of the insertion point.</p>


<p><span class="doxyComputerOutput">P</span> is used to access the various analysis that will help to get that information, like <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a>. If <span class="doxyComputerOutput">P</span> does not contain enough to return the actual frequency, this returns 1.</p>


<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 919 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo/#a7dd7fa8c0a91118934b08b516b6e9d37">llvm::MachineBlockFrequencyInfo::getBlockFreq</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency/#a8e9ed6b20c2503f66f1fd0725297aedc">llvm::BlockFrequency::getFrequency</a>, <a href="/web-llvm/docs/api/classes/llvm/mbfiwrapper/#afc8a10ff1df27bad8713e0d2b020f3e3">llvm::MBFIWrapper::getMBFI</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### isSplit() {#a8bf99289cea710aff85335a6cc7aefb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegBankSelect::InstrInsertPoint::isSplit ()</td>
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

<p>Does this point involve splitting an edge or block?</p>


<p>As soon as <a href="/web-llvm/docs/api/classes/llvm/regbankselect/insertpoint/#a7a0275cf0b23f61fed8b27a60dd950a5">getPoint</a> is called and thus, the point materialized, the point will not require splitting anymore, i.e., this will return false.</p>


<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 910 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getInsertMBBImpl() {#a88065cc9f438702ad30cec934cf7aaac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock &amp; llvm::RegBankSelect::InstrInsertPoint::getInsertMBBImpl ()</td>
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

<p>Return the materialized insertion basic block.</p>


<p>Code will be inserted into that basic block.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/regbankselect/insertpoint/#ad8275ad73d60d460541c51e9c11ddf7d">materialize</a> has been called.</p></dd>
</dl>


<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

### getPointImpl() {#a22cd58a1cdc6cb197f000d26e6de5a9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator llvm::RegBankSelect::InstrInsertPoint::getPointImpl ()</td>
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

<p>Return the materialized insertion point.</p>


<p>Code will be inserted before that point.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/regbankselect/insertpoint/#ad8275ad73d60d460541c51e9c11ddf7d">materialize</a> has been called.</p></dd>
</dl>


<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

### materialize() {#af9fca3e14242c876cbb24f199eb947ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegBankSelect::InstrInsertPoint::materialize ()</td>
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

<p>Materialize the insertion point.</p>


<p>If <a href="#a8bf99289cea710aff85335a6cc7aefb6">isSplit()</a> is true, this involves actually splitting the block or edge.</p>


<dl class="doxySectionUser">
<dt>Postcondition</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/regbankselect/insertpoint/#af81657c35d5dd8aea4fc76cf2566d6a0">getPointImpl()</a> returns a valid iterator.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Postcondition</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/regbankselect/insertpoint/#a4acd081c2e07b76bc2d5a5b5144ea937">getInsertMBBImpl()</a> returns a valid basic block.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Postcondition</dt>
<dd><p><a href="#a8bf99289cea710aff85335a6cc7aefb6">isSplit()</a> == false ; no more splitting should be required.</p></dd>
</dl>


<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 888 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Before {#aeff9d399ba6420ec1c5b2306de26f1fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegBankSelect::InstrInsertPoint::Before</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Does the insertion point is before or after Instr.</p>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

### Instr {#abf24086ba86b54bc4c21ca0888ca7b29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr&amp; llvm::RegBankSelect::InstrInsertPoint::Instr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insertion point.</p>

<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
