---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/aarch64/aarch64slshardening-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `AArch64SLSHardening.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-h">AArch64InstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">llvm/ADT/StringSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/indirectthunks-h">llvm/CodeGen/IndirectThunks.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">llvm/CodeGen/MachineOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">llvm/CodeGen/RegisterScavenging.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">llvm/IR/DebugLoc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">llvm/Support/FormatVariadic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include &lt;cassert&gt;
#include &lt;climits&gt;
#include &lt;tuple&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-aarch64slshardening-cpp-">anonymous{AArch64SLSHardening.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/thunkkind">ThunkKind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-aarch64slshardening-cpp-/thunksset">ThunksSet</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/slshardeninginserter">SLSHardeningInserter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-aarch64slshardening-cpp-/aarch64slshardening">AArch64SLSHardening</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ThunkKind *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fa9002d6d047a1ba5fbbe40a9a24f72">getThunkKind</a> (unsigned OriginalOpcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73f5b0a09c12feda5ce2b94040926867">isBLR</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0de04595fffef880650e2dff13eaf11c">insertSpeculationBarrier</a> (const AArch64Subtarget *ST, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, DebugLoc DL, bool AlwaysUseISBDSB=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2daa71efe924e3772ea89ce14dc55f83">createThunkName</a> (const ThunkKind &amp;Kind, Register Xn, Register Xm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::tuple&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ThunkKind &amp;, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a407041f5d2ea26309c1f9071a724314e">parseThunkName</a> (StringRef ThunkName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cfc112e3f71c9b1cdda2febf3b1fcb5">INITIALIZE_PASS</a> (AArch64SLSHardening, "aarch64-sls-hardening", AARCH64_SLS_HARDENING_NAME, false, false) FunctionPass *llvm</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2343d10ba2202a8ded1778215dd50706">CommonNamePrefix</a> = "__llvm_slsblr_thunk_"</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"aarch64-sls-hardening"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a0e9d9aaca9f2bd4a0ebac7f968dc35">AARCH64_SLS_HARDENING_NAME</a>&nbsp;&nbsp;&nbsp;"AArch64 sls <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp/#a56f9335fd17e0a12f1b3df757d9287f8">hardening</a> pass"</td>
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


<div class="doxySectionDef">

## Functions

### createThunkName() {#a2daa71efe924e3772ea89ce14dc55f83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt; 32 &gt; createThunkName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ThunkKind &amp; Kind, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Xn, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Xm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64slshardening-cpp">AArch64SLSHardening.cpp</a>.</p>


<p>References <a href="#a2343d10ba2202a8ded1778215dd50706">CommonNamePrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64slshardening-cpp-/thunksset/#a671ca925709006ec7352344969e09f0a">anonymous{AArch64SLSHardening.cpp}::ThunksSet::indexOfXReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getThunkKind() {#a5fa9002d6d047a1ba5fbbe40a9a24f72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ThunkKind * getThunkKind (unsigned OriginalOpcode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64slshardening-cpp">AArch64SLSHardening.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/thunkkind/#aac978b8731cbd328241645a0909d23a2">anonymous{AArch64SLSHardening.cpp}::ThunkKind::BR</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/thunkkind/#ac6bfd6c4c5602a4c0fa41a81ec505a80">anonymous{AArch64SLSHardening.cpp}::ThunkKind::BRAA</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/thunkkind/#a1acf7124b755747301e00b16db06bfc8">anonymous{AArch64SLSHardening.cpp}::ThunkKind::BRAAZ</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/thunkkind/#ab316e0d524e27cfb2674042c2fc3777e">anonymous{AArch64SLSHardening.cpp}::ThunkKind::BRAB</a> and <a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/thunkkind/#ab594384db3cfa59ec4828837200e75c9">anonymous{AArch64SLSHardening.cpp}::ThunkKind::BRABZ</a>.</p>


<p>Referenced by <a href="#a73f5b0a09c12feda5ce2b94040926867">isBLR</a>.</p>

</div>
</div>

### INITIALIZE\_PASS() {#a1cfc112e3f71c9b1cdda2febf3b1fcb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (AArch64SLSHardening, "aarch64-sls-hardening", <a href="#a0a0e9d9aaca9f2bd4a0ebac7f968dc35">AARCH64_SLS_HARDENING_NAME</a>, false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64slshardening-cpp">AArch64SLSHardening.cpp</a>.</p>


<p>References <a href="#a0a0e9d9aaca9f2bd4a0ebac7f968dc35">AARCH64_SLS_HARDENING_NAME</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64slshardening-cpp-/aarch64slshardening/#a2029a3c71050921945c8e3dfff39cd1e">anonymous{AArch64SLSHardening.cpp}::AArch64SLSHardening::AArch64SLSHardening</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aaecbd2f3b063158048f985b41f36c596">llvm::createAArch64SLSHardeningPass</a>.</p>

</div>
</div>

### insertSpeculationBarrier() {#a0de04595fffef880650e2dff13eaf11c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void insertSpeculationBarrier (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget">AArch64Subtarget</a> * ST, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, bool AlwaysUseISBDSB=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64slshardening-cpp">AArch64SLSHardening.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a7c364859e431648e7afe64769263d5f4">AlwaysUseISBDSB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a2a1cbb86e54ced362532165285bfd094">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/slshardeninginserter/#aa0294873aedbdc7244e1ca9aa115889e">anonymous{AArch64SLSHardening.cpp}::SLSHardeningInserter::populateThunk</a> and <a href="/web-llvm/docs/api/structs/anonymous-armslshardening-cpp-/slsblrthunkinserter/#a4c1c2b4d7e1a18edf5b0fb0c26a1bb71">anonymous{ARMSLSHardening.cpp}::SLSBLRThunkInserter::populateThunk</a>.</p>

</div>
</div>

### isBLR() {#a73f5b0a09c12feda5ce2b94040926867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isBLR (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64slshardening-cpp">AArch64SLSHardening.cpp</a>.</p>


<p>References <a href="#a5fa9002d6d047a1ba5fbbe40a9a24f72">getThunkKind</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### parseThunkName() {#a407041f5d2ea26309c1f9071a724314e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; const ThunkKind &amp;, Register, Register &gt; parseThunkName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ThunkName)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64slshardening-cpp">AArch64SLSHardening.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/thunkkind/#aac978b8731cbd328241645a0909d23a2">anonymous{AArch64SLSHardening.cpp}::ThunkKind::BR</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/thunkkind/#ac6bfd6c4c5602a4c0fa41a81ec505a80">anonymous{AArch64SLSHardening.cpp}::ThunkKind::BRAA</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/thunkkind/#a1acf7124b755747301e00b16db06bfc8">anonymous{AArch64SLSHardening.cpp}::ThunkKind::BRAAZ</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/thunkkind/#ab316e0d524e27cfb2674042c2fc3777e">anonymous{AArch64SLSHardening.cpp}::ThunkKind::BRAB</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/thunkkind/#ab594384db3cfa59ec4828837200e75c9">anonymous{AArch64SLSHardening.cpp}::ThunkKind::BRABZ</a>, <a href="#a2343d10ba2202a8ded1778215dd50706">CommonNamePrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#aae15979c93f7f0929116b975b5c46cd6">Fail</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64slshardening-cpp-/thunksset/#a9191ddc806dd9a7ea610b031617ed757">anonymous{AArch64SLSHardening.cpp}::ThunksSet::NumXRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a88e653a89d15149cc7a68f88be360303">llvm::StringSwitch&lt; T, R &gt;::StartsWith</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64slshardening-cpp-/thunksset/#ab71b039b6a508980dee2fd8084d9453b">anonymous{AArch64SLSHardening.cpp}::ThunksSet::xRegByIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/slshardeninginserter/#aa0294873aedbdc7244e1ca9aa115889e">anonymous{AArch64SLSHardening.cpp}::SLSHardeningInserter::populateThunk</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### CommonNamePrefix {#a2343d10ba2202a8ded1778215dd50706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef CommonNamePrefix = "__llvm_slsblr_thunk_"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64slshardening-cpp">AArch64SLSHardening.cpp</a>.</p>


<p>Referenced by <a href="#a2daa71efe924e3772ea89ce14dc55f83">createThunkName</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/slshardeninginserter/#a202dabbfe67236f51333cde46d883c51">anonymous{AArch64SLSHardening.cpp}::SLSHardeningInserter::getThunkPrefix</a> and <a href="#a407041f5d2ea26309c1f9071a724314e">parseThunkName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### AARCH64\_SLS\_HARDENING\_NAME {#a0a0e9d9aaca9f2bd4a0ebac7f968dc35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define AARCH64_SLS_HARDENING_NAME&nbsp;&nbsp;&nbsp;"AArch64 sls <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionloadhardening-cpp/#a56f9335fd17e0a12f1b3df757d9287f8">hardening</a> pass"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64slshardening-cpp">AArch64SLSHardening.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64slshardening-cpp-/aarch64slshardening/#ab62f58d2552918d53a3b0b608c022805">anonymous{AArch64SLSHardening.cpp}::AArch64SLSHardening::getPassName</a> and <a href="#a1cfc112e3f71c9b1cdda2febf3b1fcb5">INITIALIZE_PASS</a>.</p>

</div>
</div>

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"aarch64-sls-hardening"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64slshardening-cpp">AArch64SLSHardening.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
