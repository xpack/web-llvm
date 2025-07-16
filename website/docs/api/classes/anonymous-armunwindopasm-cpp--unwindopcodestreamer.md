---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-armunwindopasm-cpp-/unwindopcodestreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `UnwindOpcodeStreamer` Class Reference

<p><a href="/web-llvm/docs/api/classes/anonymous-armunwindopasm-cpp-/unwindopcodestreamer">UnwindOpcodeStreamer</a> - The simple wrapper over <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> to emit bytes with MSB to LSB per uint32_t ordering. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{ARMUnwindOpAsm.cpp}::UnwindOpcodeStreamer { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab98c35e408583b94c9f7ba4da8855bd7">UnwindOpcodeStreamer</a> (SmallVectorImpl&lt; uint8_t &gt; &amp;V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb904efda059a950a94d381eae33ac1d">EmitByte</a> (uint8_t elem)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the byte in MSB to LSB per uint32_t order. <a href="#adb904efda059a950a94d381eae33ac1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada6353da84cdd504978faa9d1fcfca40">EmitSize</a> (size_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the size prefix. <a href="#ada6353da84cdd504978faa9d1fcfca40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40e4a871996345ad6212b269297a4e84">EmitPersonalityIndex</a> (unsigned PI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the personality index prefix. <a href="#a40e4a871996345ad6212b269297a4e84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b8498e8dd9b577a7961bd5c33a975f5">FillFinishOpcode</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fill the rest of bytes with FINISH opcode. <a href="#a9b8498e8dd9b577a7961bd5c33a975f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint8_t &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42f77494d3ad1d3bf9bc0521630c3b4e">Vec</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ba8facbbe33ce233fe13b9077e0f463">Pos</a> = 3</td>
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

<p><a href="/web-llvm/docs/api/classes/anonymous-armunwindopasm-cpp-/unwindopcodestreamer">UnwindOpcodeStreamer</a> - The simple wrapper over <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> to emit bytes with MSB to LSB per uint32_t ordering.</p>


<p>For example, the first byte will be placed in Vec[3], and the following bytes will be placed in 2, 1, 0, 7, 6, 5, 4, 11, 10, 9, 8, and so on.</p>


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-cpp">ARMUnwindOpAsm.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### UnwindOpcodeStreamer() {#ab98c35e408583b94c9f7ba4da8855bd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ARMUnwindOpAsm.cpp}::UnwindOpcodeStreamer::UnwindOpcodeStreamer (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint8_t &gt; &amp; V)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-cpp">ARMUnwindOpAsm.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### EmitByte() {#adb904efda059a950a94d381eae33ac1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMUnwindOpAsm.cpp}::UnwindOpcodeStreamer::EmitByte (uint8_t elem)</td>
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

<p>Emit the byte in MSB to LSB per uint32_t order.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-cpp">ARMUnwindOpAsm.cpp</a>.</p>


<p>Referenced by <a href="#a40e4a871996345ad6212b269297a4e84">EmitPersonalityIndex</a>, <a href="#ada6353da84cdd504978faa9d1fcfca40">EmitSize</a> and <a href="#a9b8498e8dd9b577a7961bd5c33a975f5">FillFinishOpcode</a>.</p>

</div>
</div>

### EmitPersonalityIndex() {#a40e4a871996345ad6212b269297a4e84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMUnwindOpAsm.cpp}::UnwindOpcodeStreamer::EmitPersonalityIndex (unsigned PI)</td>
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

<p>Emit the personality index prefix.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-cpp">ARMUnwindOpAsm.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/ehabi/#afc1f04cd16158b4185cda78332876407aaefc75aa4a61986d09351560125d7e2f">llvm::ARM::EHABI::EHT_COMPACT</a>, <a href="#adb904efda059a950a94d381eae33ac1d">EmitByte</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm/ehabi/#a7b99cf0c7d83797700266fe3d55872e7a95314429fa79c010af353b0a2c8f75d6">llvm::ARM::EHABI::NUM_PERSONALITY_INDEX</a>.</p>

</div>
</div>

### EmitSize() {#ada6353da84cdd504978faa9d1fcfca40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMUnwindOpAsm.cpp}::UnwindOpcodeStreamer::EmitSize (size_t Size)</td>
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

<p>Emit the size prefix.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-cpp">ARMUnwindOpAsm.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#adb904efda059a950a94d381eae33ac1d">EmitByte</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### FillFinishOpcode() {#a9b8498e8dd9b577a7961bd5c33a975f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMUnwindOpAsm.cpp}::UnwindOpcodeStreamer::FillFinishOpcode ()</td>
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

<p>Fill the rest of bytes with FINISH opcode.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-cpp">ARMUnwindOpAsm.cpp</a>.</p>


<p>References <a href="#adb904efda059a950a94d381eae33ac1d">EmitByte</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm/ehabi/#a391979058f7394854c8e99446129c5aaa0aaf8dcf3c0ab164c43d61219444ea9f">llvm::ARM::EHABI::UNWIND_OPCODE_FINISH</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Pos {#a9ba8facbbe33ce233fe13b9077e0f463}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{ARMUnwindOpAsm.cpp}::UnwindOpcodeStreamer::Pos = 3</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-cpp">ARMUnwindOpAsm.cpp</a>.</p>

</div>
</div>

### Vec {#a42f77494d3ad1d3bf9bc0521630c3b4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt;uint8_t&gt;&amp; anonymous{ARMUnwindOpAsm.cpp}::UnwindOpcodeStreamer::Vec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-cpp">ARMUnwindOpAsm.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-cpp">ARMUnwindOpAsm.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
