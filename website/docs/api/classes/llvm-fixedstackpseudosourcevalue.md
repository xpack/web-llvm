---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/fixedstackpseudosourcevalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FixedStackPseudoSourceValue` Class

<p>A specialized <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> for holding FixedStack values, which must include a frame index. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FixedStackPseudoSourceValue { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevalue-h">llvm/CodeGen/PseudoSourceValue.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Special value supplied for machine level alias analysis. <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a359f505f118a168dd2663f05099ab608">FixedStackPseudoSourceValue</a> (int FI, const TargetMachine &amp;TM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6363f984399088a8b068503783f3cf1">isConstant</a> (const MachineFrameInfo *MFI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the memory pointed to by this <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> has a constant value. <a href="#ae6363f984399088a8b068503783f3cf1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a310c11a3a05119a593927ad66b7aa0b8">isAliased</a> (const MachineFrameInfo *MFI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the memory pointed to by this <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> may also be pointed to by an LLVM IR <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#a310c11a3a05119a593927ad66b7aa0b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8d4b42ebb293145cc783cb738fe13b8">mayAlias</a> (const MachineFrameInfo *) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the memory pointed to by this <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> can ever alias an LLVM IR <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#aa8d4b42ebb293145cc783cb738fe13b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28ae6b5fb32112fa17c987e846e28ff9">printCustom</a> (raw_ostream &amp;OS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement printing for <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a>. <a href="#a28ae6b5fb32112fa17c987e846e28ff9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af48e5ca752aaf934e575bddd4549e18c">getFrameIndex</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a367fced77e1f40ff6223f2b9fc92b61f">FI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb97844c15e36591e73817dc645ed16a">classof</a> (const PseudoSourceValue *V)</td>
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

<p>A specialized <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> for holding FixedStack values, which must include a frame index.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevalue-h">PseudoSourceValue.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FixedStackPseudoSourceValue() {#a359f505f118a168dd2663f05099ab608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FixedStackPseudoSourceValue::FixedStackPseudoSourceValue (int FI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevalue-h">PseudoSourceValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue/#a9959ffdc41bc31cf2211b8824f79259eaf38d1857511c3f0404c95f65664b36ab">llvm::PseudoSourceValue::FixedStack</a> and <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue/#a832e664be9da8f911292708cf4674ce0">llvm::PseudoSourceValue::PseudoSourceValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFrameIndex() {#af48e5ca752aaf934e575bddd4549e18c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::FixedStackPseudoSourceValue::getFrameIndex ()</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevalue-h">PseudoSourceValue.h</a>.</p>

</div>
</div>

### isAliased() {#a310c11a3a05119a593927ad66b7aa0b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FixedStackPseudoSourceValue::isAliased (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> *)</td>
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

<p>Test whether the memory pointed to by this <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> may also be pointed to by an LLVM IR <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>

<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevalue-h">PseudoSourceValue.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/pseudosourcevalue-cpp">PseudoSourceValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#afe20684ee4170df6085d75ef85f0124a">llvm::MachineFrameInfo::isAliasedObjectIndex</a>.</p>

</div>
</div>

### isConstant() {#ae6363f984399088a8b068503783f3cf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FixedStackPseudoSourceValue::isConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> *)</td>
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

<p>Test whether the memory pointed to by this <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> has a constant value.</p>

<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevalue-h">PseudoSourceValue.h</a>, definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/pseudosourcevalue-cpp">PseudoSourceValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a5eab840dac82571e53cc5f1c05643e2a">llvm::MachineFrameInfo::isImmutableObjectIndex</a>.</p>

</div>
</div>

### mayAlias() {#aa8d4b42ebb293145cc783cb738fe13b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FixedStackPseudoSourceValue::mayAlias (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> *)</td>
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

<p>Return true if the memory pointed to by this <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> can ever alias an LLVM IR <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>

<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevalue-h">PseudoSourceValue.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/pseudosourcevalue-cpp">PseudoSourceValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a91b0115deec3489d7e082a4a13f022ff">llvm::MachineFrameInfo::isSpillSlotObjectIndex</a>.</p>

</div>
</div>

### printCustom() {#a28ae6b5fb32112fa17c987e846e28ff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FixedStackPseudoSourceValue::printCustom (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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

<p>Implement printing for <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a>.</p>


<p>This is called from <a href="/web-llvm/docs/api/classes/llvm/value/#a1e56c814d11206720cc23059b871128d">Value::print</a> or <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>'s operator&lt;&lt;.</p>


<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevalue-h">PseudoSourceValue.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/pseudosourcevalue-cpp">PseudoSourceValue.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FI {#a367fced77e1f40ff6223f2b9fc92b61f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int llvm::FixedStackPseudoSourceValue::FI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevalue-h">PseudoSourceValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#abb97844c15e36591e73817dc645ed16a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FixedStackPseudoSourceValue::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> * V)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevalue-h">PseudoSourceValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue/#a9959ffdc41bc31cf2211b8824f79259eaf38d1857511c3f0404c95f65664b36ab">llvm::PseudoSourceValue::FixedStack</a> and <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue/#a832e664be9da8f911292708cf4674ce0">llvm::PseudoSourceValue::PseudoSourceValue</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevalue-h">PseudoSourceValue.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/pseudosourcevalue-cpp">PseudoSourceValue.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
