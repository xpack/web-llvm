---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86wincofftargetstreamer-cpp-/x86wincofftargetstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `X86WinCOFFTargetStreamer` Class Reference

<p>Implements Windows x86-only directives for object emission. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/x86targetstreamer">X86TargetStreamer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> target streamer implementing x86-only assembly directives. <a href="/web-llvm/docs/api/classes/llvm/x86targetstreamer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5df37d0bf3be012889a923767b32a06">X86WinCOFFTargetStreamer</a> (MCStreamer &amp;S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a304a3bb40bcd6c1ffb09fb0c692ac919">emitFPOProc</a> (const MCSymbol *ProcSym, unsigned ParamsSize, SMLoc L) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3403cf3c13ae8a56f804cfc3eafd540b">emitFPOEndPrologue</a> (SMLoc L) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a204642121e962c0e12c0e80d852e0a18">emitFPOEndProc</a> (SMLoc L) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00e4f812d3f229d47f31c41cfddadddc">emitFPOData</a> (const MCSymbol *ProcSym, SMLoc L) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute and emit the real CodeView <a href="/web-llvm/docs/api/structs/llvm/codeview/framedata">FrameData</a> subsection. <a href="#a00e4f812d3f229d47f31c41cfddadddc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a7d6ed9842f92c86f6f214157a6583d">emitFPOPushReg</a> (MCRegister Reg, SMLoc L) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac09a05b88c73d63a6a6a47131f6b65ae">emitFPOStackAlloc</a> (unsigned StackAlloc, SMLoc L) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a552d4fd6e11a0362170899e0a922a2db">emitFPOStackAlign</a> (unsigned Align, SMLoc L) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ecf0580185c7fa2c22f0a23ac988d64">emitFPOSetFrame</a> (MCRegister Reg, SMLoc L) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bf5b0b7ce8167a857eb08fe113c8f31">haveOpenFPOData</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8435dc1e2e3477ae04e5fdcbbdc51b6">checkInFPOPrologue</a> (SMLoc L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Diagnoses an error at L if we are not in an FPO prologue. <a href="#ab8435dc1e2e3477ae04e5fdcbbdc51b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afedc845ea8278b672fe2695ee6289c94">emitFPOLabel</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9d827b479cd3aa5014e86da257b199f">getContext</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpodata">FPOData</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a615a8ee4341ebd630be7ffd12fbca448">AllFPOData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from function symbol to its FPO data. <a href="#a615a8ee4341ebd630be7ffd12fbca448">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpodata">FPOData</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7d3b3afdb81f1512167c83a833a0a66">CurFPOData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current FPO data created by .cv_fpo_proc. <a href="#ad7d3b3afdb81f1512167c83a833a0a66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Implements Windows x86-only directives for object emission.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86WinCOFFTargetStreamer() {#ad5df37d0bf3be012889a923767b32a06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::X86WinCOFFTargetStreamer (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; S)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/x86targetstreamer/#aba974c4f23b58a529b41382b280c8354">llvm::X86TargetStreamer::X86TargetStreamer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a156c0ad16b9a22a06c6502f59f207f2a">llvm::createX86ObjectTargetStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitFPOData() {#a00e4f812d3f229d47f31c41cfddadddc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86WinCOFFTargetStreamer::emitFPOData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * ProcSym, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
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

<p>Compute and emit the real CodeView <a href="/web-llvm/docs/api/structs/llvm/codeview/framedata">FrameData</a> subsection.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpostatemachine/#a0a244d2d9c3584d900973eb02eff84da">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::CurOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a8061d1e593a8f095f0efe3ba0d793531">llvm::MCStreamer::emitAbsoluteSymbolDiff</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpostatemachine/#ac60cbf99d76cbbbbc3c094a7d78fb834">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::emitFrameDataRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acc3817979bc871dba942b87773da1cc0">llvm::MCStreamer::emitInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a822ae1a4f19b7b00a297a100749f9b8a">llvm::MCStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9488c32df3cb8819f6a07f8c88d72c66">llvm::MCStreamer::emitValueToAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afad6e408b692f1e72c58127dbaed95ebe4">llvm::codeview::FrameData</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpostatemachine/#a950edf9972376b96df88fb5f475342d1">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::FrameReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpostatemachine/#a24a77c5027c7394d44164dfa0c27e6c6">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::FrameRegOff</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#aae0550266742eb14bea527b1e6f6300a">llvm::MCTargetStreamer::getStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#a0c8e5eac2382ab2cf9e49e7946b3e7c7">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::Label</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpostatemachine/#a90a8fcd1158bc30a3e0b2964cd9b2e86">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::LocalSize</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#adc61df40235cc906841f9b43ab4af939">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::Op</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#a54085dee4b335356bb8f576330e0af43ade6b4a6ed45c15338a9fb2c18401bb7f">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::PushReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#a3535659a2de86af959106d793ddb9f31">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::RegOrOffset</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpostatemachine/#a4952082164de9bf939b7c0bb8a84be6e">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::RegSaveOffsets</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpostatemachine/#a22b748b0f3172f7f504ff3da87fd1e95">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::SavedRegSize</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#a54085dee4b335356bb8f576330e0af43ad3470b668ff00e72bd47e75d63522e48">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::SetFrame</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#a54085dee4b335356bb8f576330e0af43a4f0450e0f680e46d8cd608f4abdead9b">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::StackAlign</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpostatemachine/#a3aabce817e340fec45ba7828c82c0c72">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::StackAlign</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#a54085dee4b335356bb8f576330e0af43a889e7cd6e66d7980d313fa15f283b6e0">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::StackAlloc</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpostatemachine/#a604b633d7149d5e7990a3ab9e0d73867">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::StackOffsetBeforeAlign</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a61907d1fede3c9e9713b6b3a29d35b01">llvm::MCSymbolRefExpr::VK_COFF_IMGREL32</a>.</p>

</div>
</div>

### emitFPOEndProc() {#a204642121e962c0e12c0e80d852e0a18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86WinCOFFTargetStreamer::emitFPOEndProc (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitFPOEndPrologue() {#a3403cf3c13ae8a56f804cfc3eafd540b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86WinCOFFTargetStreamer::emitFPOEndPrologue (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitFPOProc() {#a304a3bb40bcd6c1ffb09fb0c692ac919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86WinCOFFTargetStreamer::emitFPOProc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * ProcSym, unsigned ParamsSize, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitFPOPushReg() {#a9a7d6ed9842f92c86f6f214157a6583d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86WinCOFFTargetStreamer::emitFPOPushReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#a0c8e5eac2382ab2cf9e49e7946b3e7c7">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::Label</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#adc61df40235cc906841f9b43ab4af939">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::Op</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#a54085dee4b335356bb8f576330e0af43ade6b4a6ed45c15338a9fb2c18401bb7f">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::PushReg</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#a3535659a2de86af959106d793ddb9f31">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::RegOrOffset</a>.</p>

</div>
</div>

### emitFPOSetFrame() {#a9ecf0580185c7fa2c22f0a23ac988d64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86WinCOFFTargetStreamer::emitFPOSetFrame (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#a0c8e5eac2382ab2cf9e49e7946b3e7c7">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::Label</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#adc61df40235cc906841f9b43ab4af939">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::Op</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#a3535659a2de86af959106d793ddb9f31">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::RegOrOffset</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#a54085dee4b335356bb8f576330e0af43ad3470b668ff00e72bd47e75d63522e48">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::SetFrame</a>.</p>

</div>
</div>

### emitFPOStackAlign() {#a552d4fd6e11a0362170899e0a922a2db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86WinCOFFTargetStreamer::emitFPOStackAlign (unsigned Align, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#a0c8e5eac2382ab2cf9e49e7946b3e7c7">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::Label</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#adc61df40235cc906841f9b43ab4af939">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::Op</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#a3535659a2de86af959106d793ddb9f31">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::RegOrOffset</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#a54085dee4b335356bb8f576330e0af43a4f0450e0f680e46d8cd608f4abdead9b">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::StackAlign</a>.</p>

</div>
</div>

### emitFPOStackAlloc() {#ac09a05b88c73d63a6a6a47131f6b65ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86WinCOFFTargetStreamer::emitFPOStackAlloc (unsigned StackAlloc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#a0c8e5eac2382ab2cf9e49e7946b3e7c7">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::Label</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#adc61df40235cc906841f9b43ab4af939">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::Op</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#a3535659a2de86af959106d793ddb9f31">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::RegOrOffset</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpoinstruction/#a54085dee4b335356bb8f576330e0af43a889e7cd6e66d7980d313fa15f283b6e0">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOInstruction::StackAlloc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### checkInFPOPrologue() {#ab8435dc1e2e3477ae04e5fdcbbdc51b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86WinCOFFTargetStreamer::checkInFPOPrologue (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Diagnoses an error at L if we are not in an FPO prologue.</p>


<p>Return true on error.</p>


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitFPOLabel() {#afedc845ea8278b672fe2695ee6289c94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * X86WinCOFFTargetStreamer::emitFPOLabel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>

</div>
</div>

### getContext() {#ad9d827b479cd3aa5014e86da257b199f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext &amp; anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::getContext ()</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>

</div>
</div>

### haveOpenFPOData() {#a7bf5b0b7ce8167a857eb08fe113c8f31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::haveOpenFPOData ()</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AllFPOData {#a615a8ee4341ebd630be7ffd12fbca448}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MCSymbol *, std::unique_ptr&lt;FPOData&gt; &gt; anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::AllFPOData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from function symbol to its FPO data.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>

</div>
</div>

### CurFPOData {#ad7d3b3afdb81f1512167c83a833a0a66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;FPOData&gt; anonymous{X86WinCOFFTargetStreamer.cpp}::X86WinCOFFTargetStreamer::CurFPOData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Current FPO data created by .cv_fpo_proc.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincofftargetstreamer-cpp">X86WinCOFFTargetStreamer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
