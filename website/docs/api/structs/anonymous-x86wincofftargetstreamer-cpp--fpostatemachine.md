---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpostatemachine
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FPOStateMachine` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30ae0d101b1a306c9c6689704a629edb">FPOStateMachine</a> (const FPOData *FPO)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac60cbf99d76cbbbbc3c094a7d78fb834">emitFrameDataRecord</a> (MCStreamer &amp;OS, MCSymbol *Label)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpodata">FPOData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf0732bfb861f60697cbc6396ae09edf">FPO</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a950edf9972376b96df88fb5f475342d1">FrameReg</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24a77c5027c7394d44164dfa0c27e6c6">FrameRegOff</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a244d2d9c3584d900973eb02eff84da">CurOffset</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90a8fcd1158bc30a3e0b2964cd9b2e86">LocalSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22b748b0f3172f7f504ff3da87fd1e95">SavedRegSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a604b633d7149d5e7990a3ab9e0d73867">StackOffsetBeforeAlign</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aabce817e340fec45ba7828c82c0c72">StackAlign</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51e43d9e262263f851ba05c3e8839dde">Flags</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 128 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaebe10152de9d4dffe1254e8edab533">FrameFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/regsaveoffset">RegSaveOffset</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4952082164de9bf939b7c0bb8a84be6e">RegSaveOffsets</a></td>
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


<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FPOStateMachine() {#a30ae0d101b1a306c9c6689704a629edb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::FPOStateMachine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpodata">FPOData</a> * FPO)</td>
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



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>Reference <a href="#adf0732bfb861f60697cbc6396ae09edf">FPO</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitFrameDataRecord() {#ac60cbf99d76cbbbbc3c094a7d78fb834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FPOStateMachine::emitFrameDataRecord (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Label)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#af677ac4a1dd3fc158ef8e23a8811bc54">llvm::CodeViewContext::addToStringTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a8061d1e593a8f095f0efe3ba0d793531">llvm::MCStreamer::emitAbsoluteSymbolDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9d412a2cef594fc0f45de176d51fee3b">llvm::MCStreamer::emitInt16</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acc3817979bc871dba942b87773da1cc0">llvm::MCStreamer::emitInt32</a>, <a href="#a51e43d9e262263f851ba05c3e8839dde">Flags</a>, <a href="#adf0732bfb861f60697cbc6396ae09edf">FPO</a>, <a href="#abaebe10152de9d4dffe1254e8edab533">FrameFunc</a>, <a href="#a950edf9972376b96df88fb5f475342d1">FrameReg</a>, <a href="#a24a77c5027c7394d44164dfa0c27e6c6">FrameRegOff</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a7bdf9164b69f96821c0c0269dde3ebf7">llvm::MCContext::getCVContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a7eff7fcbe27aa063e7dced4042ca3416">llvm::MCContext::getRegisterInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/framedata/#a9cfeb5927571acd463f3c84810d5439aa848e1413adc8e63b12c558ebf40260d3">llvm::codeview::FrameData::IsFunctionStart</a>, <a href="#a90a8fcd1158bc30a3e0b2964cd9b2e86">LocalSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp/#abb4bb04436126cad5201054c2b11631e">printFPOReg</a>, <a href="#a4952082164de9bf939b7c0bb8a84be6e">RegSaveOffsets</a>, <a href="#a22b748b0f3172f7f504ff3da87fd1e95">SavedRegSize</a>, <a href="#a3aabce817e340fec45ba7828c82c0c72">StackAlign</a>, <a href="#a604b633d7149d5e7990a3ab9e0d73867">StackOffsetBeforeAlign</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream/#a9c2cac84e46d3e744aeca03dd3d557d1">llvm::raw_svector_ostream::str</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a00e4f812d3f229d47f31c41cfddadddc">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CurOffset {#a0a244d2d9c3584d900973eb02eff84da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::CurOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a00e4f812d3f229d47f31c41cfddadddc">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOData</a>.</p>

</div>
</div>

### Flags {#a51e43d9e262263f851ba05c3e8839dde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::Flags = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="#ac60cbf99d76cbbbbc3c094a7d78fb834">emitFrameDataRecord</a>.</p>

</div>
</div>

### FPO {#adf0732bfb861f60697cbc6396ae09edf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FPOData* anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::FPO = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="#ac60cbf99d76cbbbbc3c094a7d78fb834">emitFrameDataRecord</a> and <a href="#a30ae0d101b1a306c9c6689704a629edb">FPOStateMachine</a>.</p>

</div>
</div>

### FrameFunc {#abaebe10152de9d4dffe1254e8edab533}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt;128&gt; anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::FrameFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="#ac60cbf99d76cbbbbc3c094a7d78fb834">emitFrameDataRecord</a>.</p>

</div>
</div>

### FrameReg {#a950edf9972376b96df88fb5f475342d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::FrameReg = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a00e4f812d3f229d47f31c41cfddadddc">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOData</a> and <a href="#ac60cbf99d76cbbbbc3c094a7d78fb834">emitFrameDataRecord</a>.</p>

</div>
</div>

### FrameRegOff {#a24a77c5027c7394d44164dfa0c27e6c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::FrameRegOff = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a00e4f812d3f229d47f31c41cfddadddc">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOData</a> and <a href="#ac60cbf99d76cbbbbc3c094a7d78fb834">emitFrameDataRecord</a>.</p>

</div>
</div>

### LocalSize {#a90a8fcd1158bc30a3e0b2964cd9b2e86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::LocalSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a00e4f812d3f229d47f31c41cfddadddc">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOData</a> and <a href="#ac60cbf99d76cbbbbc3c094a7d78fb834">emitFrameDataRecord</a>.</p>

</div>
</div>

### RegSaveOffsets {#a4952082164de9bf939b7c0bb8a84be6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;RegSaveOffset, 4&gt; anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::RegSaveOffsets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a00e4f812d3f229d47f31c41cfddadddc">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOData</a> and <a href="#ac60cbf99d76cbbbbc3c094a7d78fb834">emitFrameDataRecord</a>.</p>

</div>
</div>

### SavedRegSize {#a22b748b0f3172f7f504ff3da87fd1e95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::SavedRegSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a00e4f812d3f229d47f31c41cfddadddc">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOData</a> and <a href="#ac60cbf99d76cbbbbc3c094a7d78fb834">emitFrameDataRecord</a>.</p>

</div>
</div>

### StackAlign {#a3aabce817e340fec45ba7828c82c0c72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::StackAlign = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a00e4f812d3f229d47f31c41cfddadddc">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOData</a> and <a href="#ac60cbf99d76cbbbbc3c094a7d78fb834">emitFrameDataRecord</a>.</p>

</div>
</div>

### StackOffsetBeforeAlign {#a604b633d7149d5e7990a3ab9e0d73867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::StackOffsetBeforeAlign = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer/#a00e4f812d3f229d47f31c41cfddadddc">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::emitFPOData</a> and <a href="#ac60cbf99d76cbbbbc3c094a7d78fb834">emitFrameDataRecord</a>.</p>

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
