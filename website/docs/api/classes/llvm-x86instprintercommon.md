---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/x86instprintercommon
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `X86InstPrinterCommon` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::X86InstPrinterCommon { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-h">Target/X86/MCTargetDesc/X86InstPrinterCommon.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an instance of a target assembly language printer that converts an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> to valid target assembly syntax. <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter">X86ATTInstPrinter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter">X86IntelInstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7852b33031235cd984796fd3bc8ff45a">printOperand</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a798ffe888be775bd7743ecef1a5ba48d">printCondCode</a> (const MCInst *MI, unsigned Op, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8357e5a2ff9e83794636dc9878659696">printCondFlags</a> (const MCInst *MI, unsigned Op, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e7a69055c9ef88d14e751cfa526f59e">printSSEAVXCC</a> (const MCInst *MI, unsigned Op, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30a73113a2c39001cdc62b6acff57543">printVPCOMMnemonic</a> (const MCInst *MI, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa9b3bf5010285a0253e8a2983257bed">printVPCMPMnemonic</a> (const MCInst *MI, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a902794cd9596644cb58a3b0e1c2c83e5">printCMPMnemonic</a> (const MCInst *MI, bool IsVCmp, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e3ba70919f875d25dfb09dd7f4b6ead">printRoundingControl</a> (const MCInst *MI, unsigned Op, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20c39b7993054629cfb4f77926f0f51c">printPCRelImm</a> (const MCInst *MI, uint64_t Address, unsigned OpNo, raw_ostream &amp;O)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>value (e.g. <a href="#a20c39b7993054629cfb4f77926f0f51c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0525fc87f3e2054109908599d21098d">MCInstPrinter</a> (const MCAsmInfo &amp;mai, const MCInstrInfo &amp;mii, const MCRegisterInfo &amp;mri)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e01cbc62f1eb3379712051ded643013">printInstFlags</a> (const MCInst *MI, raw_ostream &amp;O, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a292c9f3aa1e6836768480e9dd65b3f29">printOptionalSegReg</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f7ea952a6f77a70e64f2803c0824c44">printVKPair</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52148b72ea5562b0ec318da1b42314a3">printTILEPair</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;OS)</td>
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


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-h">X86InstPrinterCommon.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### MCInstPrinter() {#af0525fc87f3e2054109908599d21098d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCInstPrinter::MCInstPrinter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp; mai, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; mii, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; mri)</td>
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



<p>Declaration at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-h">X86InstPrinterCommon.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>

</div>
</div>

### printCMPMnemonic() {#a902794cd9596644cb58a3b0e1c2c83e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86InstPrinterCommon::printCMPMnemonic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, bool IsVCmp, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-h">X86InstPrinterCommon.h</a>, definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-cpp">X86InstPrinterCommon.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a5e7a69055c9ef88d14e751cfa526f59e">printSSEAVXCC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#a95c5146c0c6b3cca75af04e9494ffed9">llvm::X86ATTInstPrinter::printVecCompareInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#a173bb9d9d14eaa55322a702f85808a43">llvm::X86IntelInstPrinter::printVecCompareInstr</a>.</p>

</div>
</div>

### printCondCode() {#a798ffe888be775bd7743ecef1a5ba48d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86InstPrinterCommon::printCondCode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned Op, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-h">X86InstPrinterCommon.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-cpp">X86InstPrinterCommon.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### printCondFlags() {#a8357e5a2ff9e83794636dc9878659696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86InstPrinterCommon::printCondFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned Op, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-h">X86InstPrinterCommon.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-cpp">X86InstPrinterCommon.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a9b52404a8d2877d3b32ebb5d1f5c72ff">llvm::StringRef::rtrim</a>.</p>

</div>
</div>

### printOperand() {#a7852b33031235cd984796fd3bc8ff45a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::X86InstPrinterCommon::printOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-h">X86InstPrinterCommon.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a292c9f3aa1e6836768480e9dd65b3f29">printOptionalSegReg</a>.</p>

</div>
</div>

### printPCRelImm() {#a20c39b7993054629cfb4f77926f0f51c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86InstPrinterCommon::printPCRelImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, uint64_t Address, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>value (e.g.</p>


<p>for jumps and calls). In Intel-style these print slightly differently than normal immediates. For example, a $ is not emitted.</p>


<p><span class="doxyComputerOutput">Address</span> The address of the next instruction.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#ac297f3bc74269d7fe98eaf7300cba9fa">MCInstPrinter::printInst</a></p></dd>
</dl>


<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-h">X86InstPrinterCommon.h</a>, definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-cpp">X86InstPrinterCommon.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a152eff13caf242abc99d47f5a197a4d9">llvm::MCInstPrinter::formatHex</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#ab13fc5e3f3dc12bc75fe3d764b832812">llvm::MCInstPrinter::formatImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a4e0302b2f7a78c8741bc07ca7655b859a43f6615bbb2c40a5306ff804094420b1">llvm::MCInstPrinter::Immediate</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#aacb2bfbafa57a37e627bf1334d349bc6">llvm::MCInstPrinter::MAI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a00c158b4d63bb4b8cc91e6cfb0150341">llvm::MCInstPrinter::markup</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#acef595ffd1764f8c06f5347db94ee756">llvm::MCInstPrinter::PrintBranchImmAsAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a5151f8e39f6265b5528efed4b516bae7">llvm::MCInstPrinter::SymbolizeOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a4e0302b2f7a78c8741bc07ca7655b859ac41a31890959544c6523af684561abe5">llvm::MCInstPrinter::Target</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#ac2345780b2997c9882b808140bce11fa">llvm::X86ATTInstPrinter::printInst</a>.</p>

</div>
</div>

### printRoundingControl() {#a1e3ba70919f875d25dfb09dd7f4b6ead}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86InstPrinterCommon::printRoundingControl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned Op, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-h">X86InstPrinterCommon.h</a>, definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-cpp">X86InstPrinterCommon.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a2a6ba37884c11b538aa6ebb0a4a8fa08a1e511826050323db2b7a888c4eeb0977">llvm::X86::TO_NEAREST_INT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a2a6ba37884c11b538aa6ebb0a4a8fa08a861c571d263e3ba1627fb148ff60b7f4">llvm::X86::TO_NEG_INF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a2a6ba37884c11b538aa6ebb0a4a8fa08a026139d1dd4eaa48af322e2bb4198903">llvm::X86::TO_POS_INF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a2a6ba37884c11b538aa6ebb0a4a8fa08a76b73a77ab384ff5b8ffbb033da9575d">llvm::X86::TO_ZERO</a>.</p>

</div>
</div>

### printSSEAVXCC() {#a5e7a69055c9ef88d14e751cfa526f59e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86InstPrinterCommon::printSSEAVXCC (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned Op, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-h">X86InstPrinterCommon.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-cpp">X86InstPrinterCommon.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a902794cd9596644cb58a3b0e1c2c83e5">printCMPMnemonic</a> and <a href="#aaa9b3bf5010285a0253e8a2983257bed">printVPCMPMnemonic</a>.</p>

</div>
</div>

### printVPCMPMnemonic() {#aaa9b3bf5010285a0253e8a2983257bed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86InstPrinterCommon::printVPCMPMnemonic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-h">X86InstPrinterCommon.h</a>, definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-cpp">X86InstPrinterCommon.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a5e7a69055c9ef88d14e751cfa526f59e">printSSEAVXCC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#a95c5146c0c6b3cca75af04e9494ffed9">llvm::X86ATTInstPrinter::printVecCompareInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#a173bb9d9d14eaa55322a702f85808a43">llvm::X86IntelInstPrinter::printVecCompareInstr</a>.</p>

</div>
</div>

### printVPCOMMnemonic() {#a30a73113a2c39001cdc62b6acff57543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86InstPrinterCommon::printVPCOMMnemonic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-h">X86InstPrinterCommon.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-cpp">X86InstPrinterCommon.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#a95c5146c0c6b3cca75af04e9494ffed9">llvm::X86ATTInstPrinter::printVecCompareInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#a173bb9d9d14eaa55322a702f85808a43">llvm::X86IntelInstPrinter::printVecCompareInstr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### printInstFlags() {#a9e01cbc62f1eb3379712051ded643013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86InstPrinterCommon::printInstFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-h">X86InstPrinterCommon.h</a>, definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-cpp">X86InstPrinterCommon.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eac83eba50896a8cee3fb15a329b94a21d">llvm::X86II::EVEX_NF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea5d69ea5c6fb1fc1895b0097a1ecbca4b">llvm::X86II::ExplicitEVEXPrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eadf6510b84ecfe4989b28667e0260d2eb">llvm::X86II::ExplicitOpPrefixMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea9baef1fc0f1076e5ec80406f29befc7d">llvm::X86II::ExplicitVEXPrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#ad571a5a542b484586224d3a8df631646">llvm::X86II::getMemoryOperandNo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#af0baab1b1dfea49cbffeb8727aebd429">llvm::X86II::getOperandBias</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab45f29eafca4acc2a7240156af5ec350a67cfccc16f5e2e2e69d3f20804774ff9">llvm::X86::IP_HAS_AD_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab45f29eafca4acc2a7240156af5ec350a21f6d8d4fc6a58587a2b022eb048a3bc">llvm::X86::IP_HAS_LOCK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab45f29eafca4acc2a7240156af5ec350a2352c35cf1f63002a6e595d1d1700dee">llvm::X86::IP_HAS_NOTRACK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab45f29eafca4acc2a7240156af5ec350a6afdb4f34129d1756d5983acde2125ea">llvm::X86::IP_HAS_REPEAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab45f29eafca4acc2a7240156af5ec350aecd65b1d4484960a4b47c1ec3fbe5e75">llvm::X86::IP_HAS_REPEAT_NE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab45f29eafca4acc2a7240156af5ec350a79e1d8eec35d00c93ca8ae774d1c8fe7">llvm::X86::IP_USE_DISP32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab45f29eafca4acc2a7240156af5ec350a52397487434744d19d6d9f30a549c68e">llvm::X86::IP_USE_DISP8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab45f29eafca4acc2a7240156af5ec350a5b424e0d4678febe99aa9677d425bc23">llvm::X86::IP_USE_EVEX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab45f29eafca4acc2a7240156af5ec350af006bc8e41a4d11f85d5488509b7557f">llvm::X86::IP_USE_VEX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab45f29eafca4acc2a7240156af5ec350a70e8344da9bc21d69afa3dff5b8b7e0f">llvm::X86::IP_USE_VEX2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab45f29eafca4acc2a7240156af5ec350a309a39ffd8ae143f947c54ae406451b5">llvm::X86::IP_USE_VEX3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea7d42cf62fdc04de0252fec0978ca907c">llvm::X86II::LOCK</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a41acdb280262403252bc72f6d3f23f7a">llvm::MCInstPrinter::MII</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86-mc/#aa70e27203f31ce8fcdd19e77996a12f8">llvm::X86_MC::needsAddressSizeOverride</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea3521268aace1e693b0af19b0e4ab54e1">llvm::X86II::NOTRACK</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#ac2345780b2997c9882b808140bce11fa">llvm::X86ATTInstPrinter::printInst</a> and <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#ae9718621d043eee9b485afd90cd062b6">llvm::X86IntelInstPrinter::printInst</a>.</p>

</div>
</div>

### printOptionalSegReg() {#a292c9f3aa1e6836768480e9dd65b3f29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86InstPrinterCommon::printOptionalSegReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-h">X86InstPrinterCommon.h</a>, definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-cpp">X86InstPrinterCommon.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a7852b33031235cd984796fd3bc8ff45a">printOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#a75d3a2429c144498e74b899dbb33506e">llvm::X86ATTInstPrinter::printMemOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#a066020a10f4b28e5fd81783c3fa5b1de">llvm::X86IntelInstPrinter::printMemOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#ab7d33433deb752463cdbaa7a587eb969">llvm::X86ATTInstPrinter::printMemReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#af25f10e8eea4608eddac083e4117e41e">llvm::X86IntelInstPrinter::printMemReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#a39e74a473e64ff067645b5ecf62f8f48">llvm::X86ATTInstPrinter::printSrcIdx</a> and <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#aae867cd8d466a2caadce0091ae119c64">llvm::X86IntelInstPrinter::printSrcIdx</a>.</p>

</div>
</div>

### printTILEPair() {#a52148b72ea5562b0ec318da1b42314a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86InstPrinterCommon::printTILEPair (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-h">X86InstPrinterCommon.h</a>, definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-cpp">X86InstPrinterCommon.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#ad0ad5f0b1236badc25e0613d3b962997">llvm::MCInstPrinter::printRegName</a>.</p>

</div>
</div>

### printVKPair() {#a5f7ea952a6f77a70e64f2803c0824c44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86InstPrinterCommon::printVKPair (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-h">X86InstPrinterCommon.h</a>, definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-cpp">X86InstPrinterCommon.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#ad0ad5f0b1236badc25e0613d3b962997">llvm::MCInstPrinter::printRegName</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-cpp">X86InstPrinterCommon.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instprintercommon-h">X86InstPrinterCommon.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
