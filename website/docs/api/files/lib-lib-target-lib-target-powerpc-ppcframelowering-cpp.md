---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `PPCFrameLowering.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcpredicates-h">MCTargetDesc/PPCPredicates.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrbuilder-h">PPCInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-h">PPCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinefunctioninfo-h">PPCMachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargetmachine-h">PPCTargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">llvm/CodeGen/LivePhysRegs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">llvm/CodeGen/MachineModuleInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">llvm/CodeGen/RegisterScavenging.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">llvm/Target/TargetOptions.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1212d203266e63eb96b80838cabb224">STATISTIC</a> (NumPESpillVSR, "Number of spills to vector in prologue")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a134ba5a9e099b09236d17de1c831e373">STATISTIC</a> (NumPEReloadVSR, "Number of reloads from vector in epilogue")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a926d37ca3eca746f6f461cbe4606a0c6">STATISTIC</a> (NumPrologProbed, "Number of prologues probed")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fa3d40d2c434f1e70a98776e4922870">computeReturnSaveOffset</a> (const PPCSubtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedfad9d0242953049a125df37ac8daa3">computeTOCSaveOffset</a> (const PPCSubtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab24a042363e1e4863d84c337bd79cefd">computeFramePointerSaveOffset</a> (const PPCSubtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad761a684381fe97901b2ca83b112b9b">computeLinkageSize</a> (const PPCSubtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcf9c9efe452f11d4713cc9657c1c4cd">computeBasePointerSaveOffset</a> (const PPCSubtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2860a7b9656bf72a5002647efbb7a1f7">computeCRSaveOffset</a> (const PPCSubtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af515521ec01610e36ad4b3c5ece866f2">spillsCR</a> (const MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1daf48d0b1ef864308803fcaa8e4ad83">hasSpills</a> (const MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef2a1ee596539c697230ac5122d6584c">hasNonRISpills</a> (const MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69189b7d95c4b78145d9dc25a3de148b">MustSaveLR</a> (const MachineFunction &amp;MF, unsigned LR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MustSaveLR - Return true if this function requires that we save the LR register onto the stack in the prolog and restore it in the epilog of the function. <a href="#a69189b7d95c4b78145d9dc25a3de148b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f0f388c4bafdb925e326b829c3f92bd">restoreCRs</a> (bool is31, bool CR2Spilled, bool CR3Spilled, bool CR4Spilled, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, ArrayRef&lt; CalleeSavedInfo &gt; CSI, unsigned CSIIndex)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7ac9a830d8314a42e5b9d6d87168249">isCalleeSavedCR</a> (unsigned Reg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a857e86404872fc7de94000c1d10e5afb">EnablePEVectorSpills</a>("ppc-enable-pe-vector-spills", cl::desc("Enable spills in prologue to vector registers."), cl::init(false), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"framelowering"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a32ebac50dfb7de135fedcd704fabe4">CALLEE_SAVED_FPRS</a>&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a932dd3cdcf409995885720b9a5864951">CALLEE_SAVED_GPRS32</a>&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96d284acf9986fe6911aca50dd5000e1">CALLEE_SAVED_GPRS64</a>&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14b420b0bf00ca64a056b46fcc59090b">CALLEE_SAVED_VRS</a>&nbsp;&nbsp;&nbsp;...</td>
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

### computeBasePointerSaveOffset() {#afcf9c9efe452f11d4713cc9657c1c4cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned computeBasePointerSaveOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; STI)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#ae11f695a5e7b6ec5a3c360ecc426ba45">llvm::PPCSubtarget::getTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a137ee29e981a9a091e81b79888d8b4a6">llvm::PPCSubtarget::is32BitELFABI</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a0e5ffac7fd84af772a216629f8bd6da9">llvm::TargetMachine::isPositionIndependent</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6622b99b3c00a3938d969957312b1b52">llvm::PPCSubtarget::isPPC64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#acc927cacd0c354e0916debf44258dd5e">llvm::PPCFrameLowering::PPCFrameLowering</a>.</p>

</div>
</div>

### computeCRSaveOffset() {#a2860a7b9656bf72a5002647efbb7a1f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned computeCRSaveOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; STI)</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a3ff0ba05eddb8771ac2f2ff7e56aa054">llvm::PPCSubtarget::isAIXABI</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6622b99b3c00a3938d969957312b1b52">llvm::PPCSubtarget::isPPC64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#acc927cacd0c354e0916debf44258dd5e">llvm::PPCFrameLowering::PPCFrameLowering</a>.</p>

</div>
</div>

### computeFramePointerSaveOffset() {#ab24a042363e1e4863d84c337bd79cefd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned computeFramePointerSaveOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; STI)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6622b99b3c00a3938d969957312b1b52">llvm::PPCSubtarget::isPPC64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#acc927cacd0c354e0916debf44258dd5e">llvm::PPCFrameLowering::PPCFrameLowering</a>.</p>

</div>
</div>

### computeLinkageSize() {#aad761a684381fe97901b2ca83b112b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned computeLinkageSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; STI)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a3ff0ba05eddb8771ac2f2ff7e56aa054">llvm::PPCSubtarget::isAIXABI</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#ad49c3ce74dc865eec4728be0850a7697">llvm::PPCSubtarget::isELFv2ABI</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6622b99b3c00a3938d969957312b1b52">llvm::PPCSubtarget::isPPC64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#acc927cacd0c354e0916debf44258dd5e">llvm::PPCFrameLowering::PPCFrameLowering</a>.</p>

</div>
</div>

### computeReturnSaveOffset() {#a5fa3d40d2c434f1e70a98776e4922870}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned computeReturnSaveOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; STI)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a3ff0ba05eddb8771ac2f2ff7e56aa054">llvm::PPCSubtarget::isAIXABI</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6622b99b3c00a3938d969957312b1b52">llvm::PPCSubtarget::isPPC64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#acc927cacd0c354e0916debf44258dd5e">llvm::PPCFrameLowering::PPCFrameLowering</a>.</p>

</div>
</div>

### computeTOCSaveOffset() {#aedfad9d0242953049a125df37ac8daa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned computeTOCSaveOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; STI)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a3ff0ba05eddb8771ac2f2ff7e56aa054">llvm::PPCSubtarget::isAIXABI</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#ad49c3ce74dc865eec4728be0850a7697">llvm::PPCSubtarget::isELFv2ABI</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6622b99b3c00a3938d969957312b1b52">llvm::PPCSubtarget::isPPC64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#acc927cacd0c354e0916debf44258dd5e">llvm::PPCFrameLowering::PPCFrameLowering</a>.</p>

</div>
</div>

### hasNonRISpills() {#aef2a1ee596539c697230ac5122d6584c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasNonRISpills (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ac65455efc149d81b4d1418acae7596b3">llvm::PPCFrameLowering::addScavengingSpillSlot</a>.</p>

</div>
</div>

### hasSpills() {#a1daf48d0b1ef864308803fcaa8e4ad83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasSpills (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ac65455efc149d81b4d1418acae7596b3">llvm::PPCFrameLowering::addScavengingSpillSlot</a>.</p>

</div>
</div>

### isCalleeSavedCR() {#ad7ac9a830d8314a42e5b9d6d87168249}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isCalleeSavedCR (unsigned Reg)</td>
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



<p>Definition at line 2600 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aae5bad356a0c0583ebad92fbe899230c">llvm::PPCFrameLowering::restoreCalleeSavedRegisters</a>.</p>

</div>
</div>

### MustSaveLR() {#a69189b7d95c4b78145d9dc25a3de148b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MustSaveLR (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, unsigned LR)</td>
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

<p>MustSaveLR - Return true if this function requires that we save the LR register onto the stack in the prolog and restore it in the epilog of the function.</p>

<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a56c15f3294c62d7590bb98e4d08ddeef">llvm::MachineRegisterInfo::def_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#aa21b132afc12ed3cead7a879506f277a">llvm::MachineRegisterInfo::def_end</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a8b823ccfc4950a649fdac5ae54f63178">llvm::PPCFunctionInfo::isLRStoreRequired</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a88484d585ecc86920ebee6396946eae2">llvm::PPCFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ac2efa5f4dacdde70f912da43c1f8ffcf">llvm::PPCFrameLowering::determineFrameLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a14e6ca2286bfbfa6952e74370a9c563b">llvm::PPCFrameLowering::emitEpilogue</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>.</p>

</div>
</div>

### restoreCRs() {#a4f0f388c4bafdb925e326b829c3f92bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void restoreCRs (bool is31, bool CR2Spilled, bool CR3Spilled, bool CR4Spilled, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; CSI, unsigned CSIIndex)</td>
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



<p>Definition at line 2532 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e8b1da7820b3f19cfb702d4312410ce">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aae5bad356a0c0583ebad92fbe899230c">llvm::PPCFrameLowering::restoreCalleeSavedRegisters</a>.</p>

</div>
</div>

### spillsCR() {#af515521ec01610e36ad4b3c5ece866f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool spillsCR (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ac65455efc149d81b4d1418acae7596b3">llvm::PPCFrameLowering::addScavengingSpillSlot</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a3f176ff8abd35fbe2f043c22d088302e">llvm::PPCFrameLowering::processFunctionBeforeFrameFinalized</a>.</p>

</div>
</div>

### STATISTIC() {#ae1212d203266e63eb96b80838cabb224}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumPESpillVSR, "Number of spills to <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">vector</a> in prologue")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a134ba5a9e099b09236d17de1c831e373}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumPEReloadVSR, "Number of reloads from <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">vector</a> in epilogue")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a926d37ca3eca746f6f461cbe4606a0c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumPrologProbed, "Number of prologues probed")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### EnablePEVectorSpills {#a857e86404872fc7de94000c1d10e5afb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnablePEVectorSpills("ppc-enable-pe-vector-spills", cl::desc("Enable spills in prologue to vector registers."), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ace3b0eb52be3988997a7f6e4a5b59aab">llvm::PPCFrameLowering::assignCalleeSavedSpillSlots</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### CALLEE\_SAVED\_FPRS {#a6a32ebac50dfb7de135fedcd704fabe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CALLEE_SAVED_FPRS&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">      {PPC::F31, -8},     \
      {PPC::F30, -16},    \
      {PPC::F29, -24},    \
      {PPC::F28, -32},    \
      {PPC::F27, -40},    \
      {PPC::F26, -48},    \
      {PPC::F25, -56},    \
      {PPC::F24, -64},    \
      {PPC::F23, -72},    \
      {PPC::F22, -80},    \
      {PPC::F21, -88},    \
      {PPC::F20, -96},    \
      {PPC::F19, -104},   \
      {PPC::F18, -112},   \
      {PPC::F17, -120},   \
      {PPC::F16, -128},   \
      {PPC::F15, -136},   \
      {PPC::F14, -144}
</div>
</dd>
</dl>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a83a821743cb2c878d23ca01bb9b6c0ba">llvm::PPCFrameLowering::getCalleeSavedSpillSlots</a>.</p>

</div>
</div>

### CALLEE\_SAVED\_GPRS32 {#a932dd3cdcf409995885720b9a5864951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CALLEE_SAVED_GPRS32&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">      {PPC::R31, -4},       \
      {PPC::R30, -8},       \
      {PPC::R29, -12},      \
      {PPC::R28, -16},      \
      {PPC::R27, -20},      \
      {PPC::R26, -24},      \
      {PPC::R25, -28},      \
      {PPC::R24, -32},      \
      {PPC::R23, -36},      \
      {PPC::R22, -40},      \
      {PPC::R21, -44},      \
      {PPC::R20, -48},      \
      {PPC::R19, -52},      \
      {PPC::R18, -56},      \
      {PPC::R17, -60},      \
      {PPC::R16, -64},      \
      {PPC::R15, -68},      \
      {PPC::R14, -72}
</div>
</dd>
</dl>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a83a821743cb2c878d23ca01bb9b6c0ba">llvm::PPCFrameLowering::getCalleeSavedSpillSlots</a>.</p>

</div>
</div>

### CALLEE\_SAVED\_GPRS64 {#a96d284acf9986fe6911aca50dd5000e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CALLEE_SAVED_GPRS64&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">      {PPC::X31, -8},       \
      {PPC::X30, -16},      \
      {PPC::X29, -24},      \
      {PPC::X28, -32},      \
      {PPC::X27, -40},      \
      {PPC::X26, -48},      \
      {PPC::X25, -56},      \
      {PPC::X24, -64},      \
      {PPC::X23, -72},      \
      {PPC::X22, -80},      \
      {PPC::X21, -88},      \
      {PPC::X20, -96},      \
      {PPC::X19, -104},     \
      {PPC::X18, -112},     \
      {PPC::X17, -120},     \
      {PPC::X16, -128},     \
      {PPC::X15, -136},     \
      {PPC::X14, -144}
</div>
</dd>
</dl>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a83a821743cb2c878d23ca01bb9b6c0ba">llvm::PPCFrameLowering::getCalleeSavedSpillSlots</a>.</p>

</div>
</div>

### CALLEE\_SAVED\_VRS {#a14b420b0bf00ca64a056b46fcc59090b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CALLEE_SAVED_VRS&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">      {PPC::V31, -16},   \
      {PPC::V30, -32},   \
      {PPC::V29, -48},   \
      {PPC::V28, -64},   \
      {PPC::V27, -80},   \
      {PPC::V26, -96},   \
      {PPC::V25, -112},  \
      {PPC::V24, -128},  \
      {PPC::V23, -144},  \
      {PPC::V22, -160},  \
      {PPC::V21, -176},  \
      {PPC::V20, -192}
</div>
</dd>
</dl>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a83a821743cb2c878d23ca01bb9b6c0ba">llvm::PPCFrameLowering::getCalleeSavedSpillSlots</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"framelowering"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp">PPCFrameLowering.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
