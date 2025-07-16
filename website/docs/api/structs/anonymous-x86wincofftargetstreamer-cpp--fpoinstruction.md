---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FPOInstruction` Struct Reference

<p>Represents a single FPO directive. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Operation { <a href="#a54085dee4b335356bb8f576330e0af43">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c8e5eac2382ab2cf9e49e7946b3e7c7">Label</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum anonymous_namespace{X86WinCOFFTargetStreamer.cpp}<a href="#a54085dee4b335356bb8f576330e0af43">::FPOInstruction::Operation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc61df40235cc906841f9b43ab4af939">Op</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3535659a2de86af959106d793ddb9f31">RegOrOffset</a></td>
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

<p>Represents a single FPO directive.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Operation {#a54085dee4b335356bb8f576330e0af43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::Operation </td>
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
<td class="doxyEnumItemName">PushReg<a id="a54085dee4b335356bb8f576330e0af43ade6b4a6ed45c15338a9fb2c18401bb7f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StackAlloc<a id="a54085dee4b335356bb8f576330e0af43a889e7cd6e66d7980d313fa15f283b6e0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StackAlign<a id="a54085dee4b335356bb8f576330e0af43a4f0450e0f680e46d8cd608f4abdead9b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SetFrame<a id="a54085dee4b335356bb8f576330e0af43ad3470b668ff00e72bd47e75d63522e48"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Label {#a0c8e5eac2382ab2cf9e49e7946b3e7c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::Label</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a00e4f812d3f229d47f31c41cfddadddc">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOData</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a9a7d6ed9842f92c86f6f214157a6583d">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOPushReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a9ecf0580185c7fa2c22f0a23ac988d64">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOSetFrame</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a552d4fd6e11a0362170899e0a922a2db">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOStackAlign</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#ac09a05b88c73d63a6a6a47131f6b65ae">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOStackAlloc</a>.</p>

</div>
</div>

### Op {#adc61df40235cc906841f9b43ab4af939}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::Operation anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::Op</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a00e4f812d3f229d47f31c41cfddadddc">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOData</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a9a7d6ed9842f92c86f6f214157a6583d">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOPushReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a9ecf0580185c7fa2c22f0a23ac988d64">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOSetFrame</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a552d4fd6e11a0362170899e0a922a2db">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOStackAlign</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#ac09a05b88c73d63a6a6a47131f6b65ae">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOStackAlloc</a>.</p>

</div>
</div>

### RegOrOffset {#a3535659a2de86af959106d793ddb9f31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::RegOrOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a00e4f812d3f229d47f31c41cfddadddc">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOData</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a9a7d6ed9842f92c86f6f214157a6583d">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOPushReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a9ecf0580185c7fa2c22f0a23ac988d64">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOSetFrame</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a552d4fd6e11a0362170899e0a922a2db">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOStackAlign</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#ac09a05b88c73d63a6a6a47131f6b65ae">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOStackAlloc</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
