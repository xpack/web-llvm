---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/x86machinefunctioninfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `X86MachineFunctionInfo` Class

<p><a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo">X86MachineFunctionInfo</a> - This class is derived from <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> and contains private <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> target-specific information for each <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::X86MachineFunctionInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">Target/X86/X86MachineFunctionInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> - This class can be derived from and used by targets to hold private target-specific information for each <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>. <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aa0bba40f433a1986cd86ed9a1e41be">X86MachineFunctionInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66bd397f5908480d5e43217f35de4198">X86MachineFunctionInfo</a> (const Function &amp;F, const TargetSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f04cf9234fce5da584b1b69d9c74a56">X86MachineFunctionInfo</a> (const X86MachineFunctionInfo &amp;)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab50b863531b495788245f7c50d892787">clone</a> (BumpPtrAllocator &amp;Allocator, MachineFunction &amp;DestMF, const DenseMap&lt; MachineBasicBlock *, MachineBasicBlock * &gt; &amp;Src2DstMBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make a functionally equivalent copy of this <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> in <span class="doxyComputerOutput">MF</span>. <a href="#ab50b863531b495788245f7c50d892787">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab79468b25ca899d32a0a3ca51d79b53c">initializeBaseYamlFields</a> (const yaml::X86MachineFunctionInfo &amp;YamlMFI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a046dd28b46bd584d050eca36d081c372">getForceFramePointer</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4476158b5f74c2b5d8b0026bf79bc088">setForceFramePointer</a> (bool forceFP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae14195edab055f9809a0349de0be5cce">getHasPushSequences</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afede9cb492ac6d31c068703e1ce6dd08">setHasPushSequences</a> (bool HasPush)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad8e7e85710893cb7fa03109a108a070">getRestoreBasePointer</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8109e774fb19e0ec57444aa577358ef4">setRestoreBasePointer</a> (const MachineFunction *MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b94707a25ee2f2461ae795124bf8dfe">setRestoreBasePointer</a> (unsigned CalleeSavedFrameSize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e8edced8a4733e0f6d5d1f9a31f16a4">getRestoreBasePointerOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, unsigned &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bbe23d1b534d969ab8244ae95a15bf7">getWinEHXMMSlotInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, unsigned &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09a99ca77b5a7ca196d4b8abfcf81859">getWinEHXMMSlotInfo</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6e59a435273270b3ef84dc8a841c122">getCalleeSavedFrameSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3682a96148f7c1e534dfa7c2726ccec">setCalleeSavedFrameSize</a> (unsigned bytes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb936e5cc84f3ffb8a2c2e1af10db48e">getBytesToPopOnReturn</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01e75f465316bfd88118560b1a7b4fef">setBytesToPopOnReturn</a> (unsigned bytes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa60550c920daccfdd275d8d94ac355b7">getRAIndex</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af374ebd23b6ad78dfd8e67de6be4e8c1">setRAIndex</a> (int Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7024c419adc3f16454faa53af71fb515">getFAIndex</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b06a3713bc04dc6f86a093d0fd5376">setFAIndex</a> (int Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c7a3251bd6c1b0b89e5712c89aaa305">getTCReturnAddrDelta</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a795c9785c92d0955d2dbc730ab8bf6bb">setTCReturnAddrDelta</a> (int delta)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a402fe30361f5a997974c704866b693e0">getSRetReturnReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4993ab3188344f6e93211a1953869821">setSRetReturnReg</a> (Register Reg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4531db8f601b268808fc109d361c9df3">getGlobalBaseReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98f0a66a5debbefc23eff86baa986acf">setGlobalBaseReg</a> (Register Reg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c77ee8d62cb9070b99a1d51889f98f9">getVarArgsFrameIndex</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ba2ff483d55a9a69a08b923496845b5">setVarArgsFrameIndex</a> (int Idx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a311dc80790a10d2eb660b923ee3ec04d">getRegSaveFrameIndex</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4255c75919e16cf8ae078d175cc23354">setRegSaveFrameIndex</a> (int Idx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a9e99b1cec93338650f1884f30cbc71">getVarArgsGPOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4146a01b8bf8f5db1cdfa065b44ba733">setVarArgsGPOffset</a> (unsigned Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b2425297e47a1ae55b3433340d3aa6a">getVarArgsFPOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad032d7310d0987c77d67f25e2ea41473">setVarArgsFPOffset</a> (unsigned Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e51353f9cba613d53a5c85b94f224b1">getArgumentStackSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64824b2df7f718da84342953fb35230f">setArgumentStackSize</a> (unsigned size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99fe9b30db19b8c18b302ad523a38698">getNumLocalDynamicTLSAccesses</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a960b34278b37294542e0bc4493dddbaa">incNumLocalDynamicTLSAccesses</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ed3059d287792eb8e73780ac551e918">getHasSEHFramePtrSave</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa40c0068f7a88682bc61cd9c56fede4">setHasSEHFramePtrSave</a> (bool V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75b0fbc272791b1c8f9acaa3564abddb">getSEHFramePtrSaveIndex</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af98de3669b3b297736be7a9a77b5caf1">setSEHFramePtrSaveIndex</a> (int Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a7a24c2247bd546fc56e2de6cfd04a3d7">AMXProgModelEnum</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac794820144c3b6fd6caaa134ea23675e">getAMXProgModel</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ac98011f3ccfe7d6bcde125908df7e4">setAMXProgModel</a> (AMXProgModelEnum Model)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/forwardedregister">ForwardedRegister</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7866e2d0a52d753ab0d36abc43fe1459">getForwardedMustTailRegParms</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af75da620ce07dde1e7c8971e5ba473c8">isSplitCSR</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a411cb62dc6a63c893a680e6a2f3c013f">setIsSplitCSR</a> (bool s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2f0359e40743109c0db7eeebf23c2e9">getUsesRedZone</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0d5df8154c4118afbefc1b9e8c6ad02">setUsesRedZone</a> (bool V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a065b339231359d3e8f23ccd94dedcdcf">hasDynAlloca</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e23254c34ca12399445a61d1aff50c8">setHasDynAlloca</a> (bool v)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa136a47fd323997cfe9d1ac8419ede8f">hasPreallocatedCall</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a902babe97cb0fab51ae380bc8acec4a3">setHasPreallocatedCall</a> (bool v)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa92686e5bcf4b22006a54652f92254df">hasSwiftAsyncContext</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ebbd50a3f0f5dbb7ed54f32ea6271e3">setHasSwiftAsyncContext</a> (bool v)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae61044e0566a5eefd1fd0d2f1fd16805">padForPush2Pop2</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0920abec0037c0cd3eb296f505ffc187">setPadForPush2Pop2</a> (bool V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bfcb8851d30d4d3ac6b27a82e7f85f7">isCandidateForPush2Pop2</a> (Register Reg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0cd3133a28b196d900d4a2fb49f19e2">addCandidateForPush2Pop2</a> (Register Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab47b5e1f45cd8a0fbdd840547e6517af">getNumCandidatesForPush2Pop2</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7aec3b56c5a4ee2489363834a3b6ca99">hasCFIAdjustCfa</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0843700067cbfb5f451b2ee34a0a7451">setHasCFIAdjustCfa</a> (bool v)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefa6fd7c14db84eada72c79be21b2ad5">setStackPtrSaveMI</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab35a2bbb33b7a14cf05c24b429e2f593">getStackPtrSaveMI</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86a8ffb8f99e139bfd5a0ffebf5358dd">getSwiftAsyncContextFrameIdx</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a131f8e977bba7b61459b8d7591b7b43a">setSwiftAsyncContextFrameIdx</a> (int v)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdfb496f636dacb853a26c073874950f">getPreallocatedIdForCallSite</a> (const Value *CS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b060017584f3958c46ae6827fd31f54">setPreallocatedStackSize</a> (size_t Id, size_t StackSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98635a734a316564e14c3d8026dfd579">getPreallocatedStackSize</a> (const size_t Id)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ac158cfb39dae5f6514d2508e735115">setPreallocatedArgOffsets</a> (size_t Id, ArrayRef&lt; size_t &gt; AO)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c38584ad91b3e408fa867373ca63225">getPreallocatedArgOffsets</a> (const size_t Id)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43bece9f74d59569cf44bfa0cd162496">getFPClobberedByCall</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29055f03cc41c896678271ac13352280">setFPClobberedByCall</a> (bool C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f3bec55d4dcb107b606a8ff918f7567">getBPClobberedByCall</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12eb4c07e152157c27b40b546d16b4b0">setBPClobberedByCall</a> (bool C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab73ed321b7c79de10c15adacb52aee7c">getFPClobberedByInvoke</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa571bd8b74d2ea26ac1597e4f9628c07">setFPClobberedByInvoke</a> (bool C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c73ebf4fb8eabfaba6b01b4930970c2">getBPClobberedByInvoke</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0cb2246eca357479af72dcda21f0eaa">setBPClobberedByInvoke</a> (bool C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af720d505e9d0056d636effe50eeb080b">anchor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a8abb7996329d68fc0ffc514f97664c">ForceFramePointer</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ForceFramePointer - True if the function is required to use of frame pointer for reasons other than it containing dynamic allocation or that FP eliminatation is turned off. <a href="#a4a8abb7996329d68fc0ffc514f97664c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">signed char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbcea3d1f603e5a5c573c50c44a5f2d2">RestoreBasePointerOffset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RestoreBasePointerOffset - Non-zero if the function has base pointer and makes call to llvm.eh.sjlj.setjmp. <a href="#abbcea3d1f603e5a5c573c50c44a5f2d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6d14060115d122c0600db54b8aa0243">WinEHXMMSlotInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>WinEHXMMSlotInfo - Slot information of XMM registers in the stack frame in bytes. <a href="#aa6d14060115d122c0600db54b8aa0243">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac070989afea273b4fe1e819ab332fb73">CalleeSavedFrameSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CalleeSavedFrameSize - Size of the callee-saved register portion of the stack frame in bytes. <a href="#ac070989afea273b4fe1e819ab332fb73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a741f7d8703799095c2950f4d76928a99">BytesToPopOnReturn</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BytesToPopOnReturn - Number of bytes function pops on return (in addition to the space used by the return address). <a href="#a741f7d8703799095c2950f4d76928a99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a720a9c7611729a3089dc7bfffd58f5e9">ReturnAddrIndex</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReturnAddrIndex - FrameIndex for return slot. <a href="#a720a9c7611729a3089dc7bfffd58f5e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8933d1bdc541c5fe7f9075742cd4a5a2">FrameAddrIndex</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FrameIndex for return slot. <a href="#a8933d1bdc541c5fe7f9075742cd4a5a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a204cecc4af9e6312d98356db8552f101">TailCallReturnAddrDelta</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TailCallReturnAddrDelta - The number of bytes by which return address stack slot is moved as the result of tail call optimization. <a href="#a204cecc4af9e6312d98356db8552f101">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e39c9acb6241ee6bed0a1cd4cbaf28c">SRetReturnReg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SRetReturnReg - Some subtargets require that sret lowering includes returning the value of the returned struct in a register. <a href="#a6e39c9acb6241ee6bed0a1cd4cbaf28c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c5595c45141ac2503f4c214c47a16a1">GlobalBaseReg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GlobalBaseReg - keeps track of the virtual register initialized for use as the global base register. <a href="#a7c5595c45141ac2503f4c214c47a16a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40200f2c3ae494e0e9f7053a98419656">VarArgsFrameIndex</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>VarArgsFrameIndex - FrameIndex for start of varargs area. <a href="#a40200f2c3ae494e0e9f7053a98419656">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4918698f74f12f95abb410cf52054608">RegSaveFrameIndex</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RegSaveFrameIndex - X86-64 vararg func register save area. <a href="#a4918698f74f12f95abb410cf52054608">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8ffd27b6f47a5d94b77b9f047bf7560">VarArgsGPOffset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>VarArgsGPOffset - X86-64 vararg func int reg offset. <a href="#ab8ffd27b6f47a5d94b77b9f047bf7560">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03f61a472f712e81361b8f6d6ad74bdf">VarArgsFPOffset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>VarArgsFPOffset - X86-64 vararg func fp reg offset. <a href="#a03f61a472f712e81361b8f6d6ad74bdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c48a3a21de4d2f43c0f634b4c284eac">ArgumentStackSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ArgumentStackSize - The number of bytes on stack consumed by the arguments being passed on the stack. <a href="#a0c48a3a21de4d2f43c0f634b4c284eac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ba167e518f03bc0feb5a354aa781230">NumLocalDynamics</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NumLocalDynamics - Number of local-dynamic TLS accesses. <a href="#a4ba167e518f03bc0feb5a354aa781230">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c296071aacfb3ee797f23604adb6923">HasPushSequences</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HasPushSequences - Keeps track of whether this function uses sequences of pushes to pass function parameters. <a href="#a0c296071aacfb3ee797f23604adb6923">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4938c5769ef18a450d3bf012b8f560a">HasSEHFramePtrSave</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the function recovers from an SEH exception, and therefore needs to spill and restore the frame pointer. <a href="#ae4938c5769ef18a450d3bf012b8f560a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff188d779c2b8454ffd5167b9f6af753">SEHFramePtrSaveIndex</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The frame index of a stack object containing the original frame pointer used to address arguments in a function using a base pointer. <a href="#aff188d779c2b8454ffd5167b9f6af753">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a7a24c2247bd546fc56e2de6cfd04a3d7">AMXProgModelEnum</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0a97a4c461b99292f1fe5aa9025ae3b">AMXProgModel</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a7a24c2247bd546fc56e2de6cfd04a3d7a116ebf2078ffd98178ffbdd2f544ebb7">AMXProgModelEnum::None</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The AMX programing model used in the function. <a href="#aa0a97a4c461b99292f1fe5aa9025ae3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4d7024c36f7c34783c2e04e20e81821">IsSplitCSR</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this function has a subset of CSRs that is handled explicitly via copies. <a href="#ac4d7024c36f7c34783c2e04e20e81821">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a28bcea7f7b59415c3e961e03eca9bf">UsesRedZone</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this function uses the red zone. <a href="#a3a28bcea7f7b59415c3e961e03eca9bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac395d699c2344317cf6e11a483bd8aac">HasDynAlloca</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this function has DYN_ALLOCA instructions. <a href="#ac395d699c2344317cf6e11a483bd8aac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a693640cd6dd17a9bf912aec86e3a14a3">HasPreallocatedCall</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this function has any preallocated calls. <a href="#a693640cd6dd17a9bf912aec86e3a14a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9105eeb4f3add00c9c357ccf8788ce04">HasSwiftAsyncContext</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this function has an extended frame record [Ctx, RBP, Return addr]. <a href="#a9105eeb4f3add00c9c357ccf8788ce04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ecec15f41360c4bcf77998e4b1dd513">PadForPush2Pop2</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ajust stack for push2/pop2. <a href="#a6ecec15f41360c4bcf77998e4b1dd513">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::set&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaeb4270fc7477a86961e050a08b4b66">CandidatesForPush2Pop2</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Candidate registers for push2/pop2. <a href="#afaeb4270fc7477a86961e050a08b4b66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac08f877b63f7eadbfddcb01c47955834">HasCFIAdjustCfa</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this function has CFI directives that adjust the CFA. <a href="#ac08f877b63f7eadbfddcb01c47955834">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8509eb7f9bbc13c0f00edf30dcbf8822">StackPtrSaveMI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8433bc19fc5ea21148e6a8fb1083f8e0">SwiftAsyncContextFrameIdx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bcf5191ffbe7c4bcd3c164385df06be">PreallocatedIds</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; size_t, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3bf2ee9723120aa4d48083fc438151f">PreallocatedStackSizes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; size_t, 4 &gt;, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ad8c13fe9c0cfe00f3b7eb74e1c9e93">PreallocatedArgOffsets</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a321875825d6abdb3349022e1ba5b7f">FPClobberedByCall</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd50a2b718303296412ea88d6c7e8afb">BPClobberedByCall</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab05889dcba744e78cbf9ed7c02fd8904">FPClobberedByInvoke</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe4073d241b56c6257a5938daa0d91bd">BPClobberedByInvoke</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/forwardedregister">ForwardedRegister</a>, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92ff445903f35adf4d080b6dde9c018a">ForwardedMustTailRegParms</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ForwardedMustTailRegParms - A list of virtual and physical registers that must be forwarded to every musttail call. <a href="#a92ff445903f35adf4d080b6dde9c018a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo">X86MachineFunctionInfo</a> - This class is derived from <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> and contains private <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> target-specific information for each <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86MachineFunctionInfo() {#a6aa0bba40f433a1986cd86ed9a1e41be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::X86MachineFunctionInfo::X86MachineFunctionInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="#ab50b863531b495788245f7c50d892787">clone</a> and <a href="#a2f04cf9234fce5da584b1b69d9c74a56">X86MachineFunctionInfo</a>.</p>

</div>
</div>

### X86MachineFunctionInfo() {#a66bd397f5908480d5e43217f35de4198}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::X86MachineFunctionInfo::X86MachineFunctionInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> * STI)</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### X86MachineFunctionInfo() {#a2f04cf9234fce5da584b1b69d9c74a56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::X86MachineFunctionInfo::X86MachineFunctionInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo">X86MachineFunctionInfo</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp/#ad5d00e1d77644d95847b9bf8da12b759">Allocator</a> and <a href="#a6aa0bba40f433a1986cd86ed9a1e41be">X86MachineFunctionInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addCandidateForPush2Pop2() {#ad0cd3133a28b196d900d4a2fb49f19e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::addCandidateForPush2Pop2 (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7c6fdca5f3b44d406ff07e43b2f140f6">llvm::X86FrameLowering::assignCalleeSavedSpillSlots</a>.</p>

</div>
</div>

### clone() {#ab50b863531b495788245f7c50d892787}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionInfo * X86MachineFunctionInfo::clone (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; DestMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; Src2DstMBB)</td>
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

<p>Make a functionally equivalent copy of this <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> in <span class="doxyComputerOutput">MF</span>.</p>


<p>This requires remapping <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> references from the original parent to values in the new function. Targets may assume that virtual register and frame index values are preserved in the new function.</p>


<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-cpp">X86MachineFunctionInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac31b21febeefe69aaddea3541dae45e1">llvm::MachineFunction::cloneInfo</a> and <a href="#a6aa0bba40f433a1986cd86ed9a1e41be">X86MachineFunctionInfo</a>.</p>

</div>
</div>

### getAMXProgModel() {#ac794820144c3b6fd6caaa134ea23675e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMXProgModelEnum llvm::X86MachineFunctionInfo::getAMXProgModel ()</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a353d6967ff6cb7d22110de97773d65d8">llvm::X86FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86pretileconfig-cpp-/x86pretileconfig/#a5d1d05840235d52ee7fb4b0ce9a63b76">anonymous{X86PreTileConfig.cpp}::X86PreTileConfig::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86tileconfig-cpp-/x86tileconfig/#a963813efe9cac5e7b68def8df1713456">anonymous{X86TileConfig.cpp}::X86TileConfig::runOnMachineFunction</a>.</p>

</div>
</div>

### getArgumentStackSize() {#a2e51353f9cba613d53a5c85b94f224b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86MachineFunctionInfo::getArgumentStackSize ()</td>
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



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#ac8faf9a625064bfefafb7ace646815ff">llvm::X86FrameLowering::adjustForSegmentedStacks</a> and <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#aeaa3fe410733d28b0cbe36f481286996">llvm::X86AsmPrinter::emitFunctionBodyStart</a>.</p>

</div>
</div>

### getBPClobberedByCall() {#a9f3bec55d4dcb107b606a8ff918f7567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::getBPClobberedByCall ()</td>
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



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a068e9d1fd54621ae340f26c41d170a1a">llvm::X86FrameLowering::spillFPBP</a>.</p>

</div>
</div>

### getBPClobberedByInvoke() {#a2c73ebf4fb8eabfaba6b01b4930970c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::getBPClobberedByInvoke ()</td>
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



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a339d32ea1f7597a13e849615446a7d26">llvm::X86RegisterInfo::getReservedRegs</a>.</p>

</div>
</div>

### getBytesToPopOnReturn() {#abb936e5cc84f3ffb8a2c2e1af10db48e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86MachineFunctionInfo::getBytesToPopOnReturn ()</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getCalleeSavedFrameSize() {#ad6e59a435273270b3ef84dc8a841c122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86MachineFunctionInfo::getCalleeSavedFrameSize ()</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="#ae61044e0566a5eefd1fd0d2f1fd16805">padForPush2Pop2</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a353d6967ff6cb7d22110de97773d65d8">llvm::X86FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a84fbe17f451c957c67de546c98f2b79b">llvm::X86FrameLowering::getFrameIndexReference</a>.</p>

</div>
</div>

### getFAIndex() {#a7024c419adc3f16454faa53af71fb515}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::X86MachineFunctionInfo::getFAIndex ()</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a84fbe17f451c957c67de546c98f2b79b">llvm::X86FrameLowering::getFrameIndexReference</a>.</p>

</div>
</div>

### getForceFramePointer() {#a046dd28b46bd584d050eca36d081c372}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::getForceFramePointer ()</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a493d9a8215b5ec117b32762217d66f80">llvm::X86FrameLowering::hasFPImpl</a>.</p>

</div>
</div>

### getForwardedMustTailRegParms() {#a7866e2d0a52d753ab0d36abc43fe1459}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt; ForwardedRegister &gt; &amp; llvm::X86MachineFunctionInfo::getForwardedMustTailRegParms ()</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getFPClobberedByCall() {#a43bece9f74d59569cf44bfa0cd162496}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::getFPClobberedByCall ()</td>
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



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a068e9d1fd54621ae340f26c41d170a1a">llvm::X86FrameLowering::spillFPBP</a>.</p>

</div>
</div>

### getFPClobberedByInvoke() {#ab73ed321b7c79de10c15adacb52aee7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::getFPClobberedByInvoke ()</td>
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



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a339d32ea1f7597a13e849615446a7d26">llvm::X86RegisterInfo::getReservedRegs</a>.</p>

</div>
</div>

### getGlobalBaseReg() {#a4531db8f601b268808fc109d361c9df3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::X86MachineFunctionInfo::getGlobalBaseReg ()</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a22361ec9d8730e3f4b55ca39260e47f0">llvm::X86InstrInfo::getGlobalBaseReg</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86instrinfo-cpp-/cgbr/#ae7e54015b8e4160365d925c1bd46004f">anonymous{X86InstrInfo.cpp}::CGBR::runOnMachineFunction</a>.</p>

</div>
</div>

### getHasPushSequences() {#ae14195edab055f9809a0349de0be5cce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::getHasPushSequences ()</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#aa5f78769915f0742f77e73e45abab318">llvm::X86FrameLowering::eliminateCallFramePseudoInstr</a>.</p>

</div>
</div>

### getHasSEHFramePtrSave() {#a8ed3059d287792eb8e73780ac551e918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::getHasSEHFramePtrSave ()</td>
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



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a535388ac574e0f8d844662d315997b3d">llvm::X86FrameLowering::restoreWin32EHStackPointers</a>.</p>

</div>
</div>

### getNumCandidatesForPush2Pop2() {#ab47b5e1f45cd8a0fbdd840547e6517af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::X86MachineFunctionInfo::getNumCandidatesForPush2Pop2 ()</td>
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



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7c6fdca5f3b44d406ff07e43b2f140f6">llvm::X86FrameLowering::assignCalleeSavedSpillSlots</a>.</p>

</div>
</div>

### getNumLocalDynamicTLSAccesses() {#a99fe9b30db19b8c18b302ad523a38698}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86MachineFunctionInfo::getNumLocalDynamicTLSAccesses ()</td>
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



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-x86instrinfo-cpp-/ldtlscleanup/#a0f3b4e5e968c5ab89944989495e68799">anonymous{X86InstrInfo.cpp}::LDTLSCleanup::runOnMachineFunction</a>.</p>

</div>
</div>

### getPreallocatedArgOffsets() {#a3c38584ad91b3e408fa867373ca63225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; size_t &gt; llvm::X86MachineFunctionInfo::getPreallocatedArgOffsets (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> size_t Id)</td>
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



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5fd231b7f6dc1db67a2bb2f48bf5f342">llvm::X86TargetLowering::EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### getPreallocatedIdForCallSite() {#afdfb496f636dacb853a26c073874950f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::X86MachineFunctionInfo::getPreallocatedIdForCallSite (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * CS)</td>
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



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getPreallocatedStackSize() {#a98635a734a316564e14c3d8026dfd579}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::X86MachineFunctionInfo::getPreallocatedStackSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> size_t Id)</td>
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



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5fd231b7f6dc1db67a2bb2f48bf5f342">llvm::X86TargetLowering::EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### getRAIndex() {#aa60550c920daccfdd275d8d94ac355b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::X86MachineFunctionInfo::getRAIndex ()</td>
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



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getRegSaveFrameIndex() {#a311dc80790a10d2eb660b923ee3ec04d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::X86MachineFunctionInfo::getRegSaveFrameIndex ()</td>
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



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getRestoreBasePointer() {#aad8e7e85710893cb7fa03109a108a070}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::getRestoreBasePointer ()</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7c6fdca5f3b44d406ff07e43b2f140f6">llvm::X86FrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a84fbe17f451c957c67de546c98f2b79b">llvm::X86FrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a94ed22ca5dc3213bfb96e1ddbc41952e">llvm::X86FrameLowering::restoreCalleeSavedRegisters</a> and <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afc942a637e5d48a94d4033498b7479dd">llvm::X86FrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### getRestoreBasePointerOffset() {#a5e8edced8a4733e0f6d5d1f9a31f16a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::X86MachineFunctionInfo::getRestoreBasePointerOffset ()</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>.</p>

</div>
</div>

### getSEHFramePtrSaveIndex() {#a75b0fbc272791b1c8f9acaa3564abddb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::X86MachineFunctionInfo::getSEHFramePtrSaveIndex ()</td>
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



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a535388ac574e0f8d844662d315997b3d">llvm::X86FrameLowering::restoreWin32EHStackPointers</a>.</p>

</div>
</div>

### getSRetReturnReg() {#a402fe30361f5a997974c704866b693e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::X86MachineFunctionInfo::getSRetReturnReg ()</td>
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



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getStackPtrSaveMI() {#ab35a2bbb33b7a14cf05c24b429e2f593}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * llvm::X86MachineFunctionInfo::getStackPtrSaveMI ()</td>
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



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a6c1f3151b66ea2dfd6a8b9cef815d51c">llvm::X86FrameLowering::emitCalleeSavedFrameMoves</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a353d6967ff6cb7d22110de97773d65d8">llvm::X86FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a0d077eae4ce42bad55b66dbf9166113d">llvm::X86RegisterInfo::hasBasePointer</a> and <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af7d9e67f21b6a4968a6074b082944dc6">llvm::X86FrameLowering::processFunctionBeforeFrameIndicesReplaced</a>.</p>

</div>
</div>

### getSwiftAsyncContextFrameIdx() {#a86a8ffb8f99e139bfd5a0ffebf5358dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; int &gt; llvm::X86MachineFunctionInfo::getSwiftAsyncContextFrameIdx ()</td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getTCReturnAddrDelta() {#a7c7a3251bd6c1b0b89e5712c89aaa305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::X86MachineFunctionInfo::getTCReturnAddrDelta ()</td>
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



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7c6fdca5f3b44d406ff07e43b2f140f6">llvm::X86FrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a411b83001c7fb0aa941c0f6daef18f05">llvm::X86InstrInfo::canMakeTailCallConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a353d6967ff6cb7d22110de97773d65d8">llvm::X86FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a84fbe17f451c957c67de546c98f2b79b">llvm::X86FrameLowering::getFrameIndexReference</a> and <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afb20caf4eb8695705452f25d78a18a06">llvm::X86FrameLowering::getFrameIndexReferencePreferSP</a>.</p>

</div>
</div>

### getUsesRedZone() {#af2f0359e40743109c0db7eeebf23c2e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::getUsesRedZone ()</td>
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



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a0d585a5fdebc1deeffc750a2a3308d89">ExpandMOVImmSExti8</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a377e3edcd6fff2b8154c0b78e64f09e7">llvm::X86InstrInfo::isFunctionSafeToOutlineFrom</a>.</p>

</div>
</div>

### getVarArgsFPOffset() {#a4b2425297e47a1ae55b3433340d3aa6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86MachineFunctionInfo::getVarArgsFPOffset ()</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getVarArgsFrameIndex() {#a7c77ee8d62cb9070b99a1d51889f98f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::X86MachineFunctionInfo::getVarArgsFrameIndex ()</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getVarArgsGPOffset() {#a2a9e99b1cec93338650f1884f30cbc71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86MachineFunctionInfo::getVarArgsGPOffset ()</td>
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



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### getWinEHXMMSlotInfo() {#a9bbe23d1b534d969ab8244ae95a15bf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt; int, unsigned &gt; &amp; llvm::X86MachineFunctionInfo::getWinEHXMMSlotInfo ()</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7c6fdca5f3b44d406ff07e43b2f140f6">llvm::X86FrameLowering::assignCalleeSavedSpillSlots</a> and <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#acd3876e593314b23ed0679279ee31dfe">llvm::X86FrameLowering::getWin64EHFrameIndexRef</a>.</p>

</div>
</div>

### getWinEHXMMSlotInfo() {#a09a99ca77b5a7ca196d4b8abfcf81859}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DenseMap&lt; int, unsigned &gt; &amp; llvm::X86MachineFunctionInfo::getWinEHXMMSlotInfo ()</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### hasCFIAdjustCfa() {#a7aec3b56c5a4ee2489363834a3b6ca99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::hasCFIAdjustCfa ()</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#aca49f4bdff5eb8f32e4b650f33d6f98e">llvm::X86FrameLowering::getDwarfFrameBase</a>.</p>

</div>
</div>

### hasDynAlloca() {#a065b339231359d3e8f23ccd94dedcdcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::hasDynAlloca ()</td>
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



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86dynallocaexpander-cpp-/x86dynallocaexpander/#a8216d146c993c13133c29a28efdded4c">anonymous{X86DynAllocaExpander.cpp}::X86DynAllocaExpander::runOnMachineFunction</a>.</p>

</div>
</div>

### hasPreallocatedCall() {#aa136a47fd323997cfe9d1ac8419ede8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::hasPreallocatedCall ()</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a0d077eae4ce42bad55b66dbf9166113d">llvm::X86RegisterInfo::hasBasePointer</a> and <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a493d9a8215b5ec117b32762217d66f80">llvm::X86FrameLowering::hasFPImpl</a>.</p>

</div>
</div>

### hasSwiftAsyncContext() {#aa92686e5bcf4b22006a54652f92254df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::hasSwiftAsyncContext ()</td>
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



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7c6fdca5f3b44d406ff07e43b2f140f6">llvm::X86FrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#aae24f16623a7d1df7b850c55694e9d27">llvm::X86FrameLowering::canUseAsEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a652c5c131aaf585181fb0ff722781118">llvm::X86FrameLowering::canUseAsPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a353d6967ff6cb7d22110de97773d65d8">llvm::X86FrameLowering::emitEpilogue</a> and <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>.</p>

</div>
</div>

### incNumLocalDynamicTLSAccesses() {#a960b34278b37294542e0bc4493dddbaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::incNumLocalDynamicTLSAccesses ()</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afa38de8a6bc68bdfd3aea0e8900c7745">LowerToTLSLocalDynamicModel</a>.</p>

</div>
</div>

### initializeBaseYamlFields() {#ab79468b25ca899d32a0a3ca51d79b53c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86MachineFunctionInfo::initializeBaseYamlFields (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/x86machinefunctioninfo">yaml::X86MachineFunctionInfo</a> &amp; YamlMFI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-cpp">X86MachineFunctionInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/yaml/x86machinefunctioninfo/#a3423804ae217c30e9ccb28fda52be1f8">llvm::yaml::X86MachineFunctionInfo::AMXProgModel</a>.</p>

</div>
</div>

### isCandidateForPush2Pop2() {#a2bfcb8851d30d4d3ac6b27a82e7f85f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::isCandidateForPush2Pop2 (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a94ed22ca5dc3213bfb96e1ddbc41952e">llvm::X86FrameLowering::restoreCalleeSavedRegisters</a> and <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afc942a637e5d48a94d4033498b7479dd">llvm::X86FrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### isSplitCSR() {#af75da620ce07dde1e7c8971e5ba473c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::isSplitCSR ()</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a175455eaa3cecc21fcd21b029b65c0a9">llvm::X86RegisterInfo::getCalleeSavedRegsViaCopy</a>.</p>

</div>
</div>

### padForPush2Pop2() {#ae61044e0566a5eefd1fd0d2f1fd16805}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::padForPush2Pop2 ()</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7c6fdca5f3b44d406ff07e43b2f140f6">llvm::X86FrameLowering::assignCalleeSavedSpillSlots</a>, <a href="#ad6e59a435273270b3ef84dc8a841c122">getCalleeSavedFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a94ed22ca5dc3213bfb96e1ddbc41952e">llvm::X86FrameLowering::restoreCalleeSavedRegisters</a> and <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afc942a637e5d48a94d4033498b7479dd">llvm::X86FrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### setAMXProgModel() {#a0ac98011f3ccfe7d6bcde125908df7e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setAMXProgModel (<a href="/web-llvm/docs/api/namespaces/llvm/#a7a24c2247bd546fc56e2de6cfd04a3d7">AMXProgModelEnum</a> Model)</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7a24c2247bd546fc56e2de6cfd04a3d7a116ebf2078ffd98178ffbdd2f544ebb7">llvm::None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5fd231b7f6dc1db67a2bb2f48bf5f342">llvm::X86TargetLowering::EmitInstrWithCustomInserter</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a25a5e94166cf78354826b46e402ebcd9">LowerINTRINSIC_W_CHAIN</a>.</p>

</div>
</div>

### setArgumentStackSize() {#a64824b2df7f718da84342953fb35230f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setArgumentStackSize (unsigned size)</td>
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



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>

</div>
</div>

### setBPClobberedByCall() {#a12eb4c07e152157c27b40b546d16b4b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setBPClobberedByCall (bool C)</td>
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



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### setBPClobberedByInvoke() {#aa0cb2246eca357479af72dcda21f0eaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setBPClobberedByInvoke (bool C)</td>
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



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### setBytesToPopOnReturn() {#a01e75f465316bfd88118560b1a7b4fef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setBytesToPopOnReturn (unsigned bytes)</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setCalleeSavedFrameSize() {#af3682a96148f7c1e534dfa7c2726ccec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setCalleeSavedFrameSize (unsigned bytes)</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7c6fdca5f3b44d406ff07e43b2f140f6">llvm::X86FrameLowering::assignCalleeSavedSpillSlots</a>.</p>

</div>
</div>

### setFAIndex() {#a05b06a3713bc04dc6f86a093d0fd5376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setFAIndex (int Index)</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setForceFramePointer() {#a4476158b5f74c2b5d8b0026bf79bc088}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setForceFramePointer (bool forceFP)</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setFPClobberedByCall() {#a29055f03cc41c896678271ac13352280}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setFPClobberedByCall (bool C)</td>
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



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### setFPClobberedByInvoke() {#aa571bd8b74d2ea26ac1597e4f9628c07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setFPClobberedByInvoke (bool C)</td>
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



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### setGlobalBaseReg() {#a98f0a66a5debbefc23eff86baa986acf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setGlobalBaseReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a22361ec9d8730e3f4b55ca39260e47f0">llvm::X86InstrInfo::getGlobalBaseReg</a>.</p>

</div>
</div>

### setHasCFIAdjustCfa() {#a0843700067cbfb5f451b2ee34a0a7451}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setHasCFIAdjustCfa (bool v)</td>
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



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setHasDynAlloca() {#a4e23254c34ca12399445a61d1aff50c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setHasDynAlloca (bool v)</td>
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



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setHasPreallocatedCall() {#a902babe97cb0fab51ae380bc8acec4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setHasPreallocatedCall (bool v)</td>
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



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5fd231b7f6dc1db67a2bb2f48bf5f342">llvm::X86TargetLowering::EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### setHasPushSequences() {#afede9cb492ac6d31c068703e1ce6dd08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setHasPushSequences (bool HasPush)</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setHasSEHFramePtrSave() {#aaa40c0068f7a88682bc61cd9c56fede4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setHasSEHFramePtrSave (bool V)</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7c6fdca5f3b44d406ff07e43b2f140f6">llvm::X86FrameLowering::assignCalleeSavedSpillSlots</a>.</p>

</div>
</div>

### setHasSwiftAsyncContext() {#a3ebbd50a3f0f5dbb7ed54f32ea6271e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setHasSwiftAsyncContext (bool v)</td>
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



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setIsSplitCSR() {#a411cb62dc6a63c893a680e6a2f3c013f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setIsSplitCSR (bool s)</td>
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



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setPadForPush2Pop2() {#a0920abec0037c0cd3eb296f505ffc187}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setPadForPush2Pop2 (bool V)</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7c6fdca5f3b44d406ff07e43b2f140f6">llvm::X86FrameLowering::assignCalleeSavedSpillSlots</a>.</p>

</div>
</div>

### setPreallocatedArgOffsets() {#a6ac158cfb39dae5f6514d2508e735115}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setPreallocatedArgOffsets (size_t Id, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; size_t &gt; AO)</td>
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



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>.</p>

</div>
</div>

### setPreallocatedStackSize() {#a9b060017584f3958c46ae6827fd31f54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setPreallocatedStackSize (size_t Id, size_t StackSize)</td>
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



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setRAIndex() {#af374ebd23b6ad78dfd8e67de6be4e8c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setRAIndex (int Index)</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setRegSaveFrameIndex() {#a4255c75919e16cf8ae078d175cc23354}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setRegSaveFrameIndex (int Idx)</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setRestoreBasePointer() {#a8109e774fb19e0ec57444aa577358ef4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86MachineFunctionInfo::setRestoreBasePointer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-cpp">X86MachineFunctionInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a8ae9c5d17b40aa7be0189dd4f12dc315">llvm::MachineRegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7c6fdca5f3b44d406ff07e43b2f140f6">llvm::X86FrameLowering::assignCalleeSavedSpillSlots</a>.</p>

</div>
</div>

### setRestoreBasePointer() {#a6b94707a25ee2f2461ae795124bf8dfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setRestoreBasePointer (unsigned CalleeSavedFrameSize)</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setSEHFramePtrSaveIndex() {#af98de3669b3b297736be7a9a77b5caf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setSEHFramePtrSaveIndex (int Index)</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7c6fdca5f3b44d406ff07e43b2f140f6">llvm::X86FrameLowering::assignCalleeSavedSpillSlots</a>.</p>

</div>
</div>

### setSRetReturnReg() {#a4993ab3188344f6e93211a1953869821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setSRetReturnReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### setStackPtrSaveMI() {#aefa6fd7c14db84eada72c79be21b2ad5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setStackPtrSaveMI (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af7d9e67f21b6a4968a6074b082944dc6">llvm::X86FrameLowering::processFunctionBeforeFrameIndicesReplaced</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86argumentstackslotrebase-cpp-/x86argumentstackslotpass/#af787e4cab9e64467b9aa0a253171fa88">anonymous{X86ArgumentStackSlotRebase.cpp}::X86ArgumentStackSlotPass::runOnMachineFunction</a>.</p>

</div>
</div>

### setSwiftAsyncContextFrameIdx() {#a131f8e977bba7b61459b8d7591b7b43a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setSwiftAsyncContextFrameIdx (int v)</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setTCReturnAddrDelta() {#a795c9785c92d0955d2dbc730ab8bf6bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setTCReturnAddrDelta (int delta)</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setUsesRedZone() {#aa0d5df8154c4118afbefc1b9e8c6ad02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setUsesRedZone (bool V)</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>.</p>

</div>
</div>

### setVarArgsFPOffset() {#ad032d7310d0987c77d67f25e2ea41473}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setVarArgsFPOffset (unsigned Offset)</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### setVarArgsFrameIndex() {#a9ba2ff483d55a9a69a08b923496845b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setVarArgsFrameIndex (int Idx)</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### setVarArgsGPOffset() {#a4146a01b8bf8f5db1cdfa065b44ba733}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86MachineFunctionInfo::setVarArgsGPOffset (unsigned Offset)</td>
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



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#af720d505e9d0056d636effe50eeb080b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86MachineFunctionInfo::anchor ()</td>
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



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-cpp">X86MachineFunctionInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AMXProgModel {#aa0a97a4c461b99292f1fe5aa9025ae3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMXProgModelEnum llvm::X86MachineFunctionInfo::AMXProgModel = <a href="/web-llvm/docs/api/namespaces/llvm/#a7a24c2247bd546fc56e2de6cfd04a3d7a116ebf2078ffd98178ffbdd2f544ebb7">AMXProgModelEnum::None</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The AMX programing model used in the function.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### ArgumentStackSize {#a0c48a3a21de4d2f43c0f634b4c284eac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86MachineFunctionInfo::ArgumentStackSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ArgumentStackSize - The number of bytes on stack consumed by the arguments being passed on the stack.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### BPClobberedByCall {#abd50a2b718303296412ea88d6c7e8afb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::BPClobberedByCall = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### BPClobberedByInvoke {#afe4073d241b56c6257a5938daa0d91bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::BPClobberedByInvoke = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### BytesToPopOnReturn {#a741f7d8703799095c2950f4d76928a99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86MachineFunctionInfo::BytesToPopOnReturn = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>BytesToPopOnReturn - Number of bytes function pops on return (in addition to the space used by the return address).</p>


<p>Used on windows platform for stdcall &amp; fastcall name decoration</p>


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### CalleeSavedFrameSize {#ac070989afea273b4fe1e819ab332fb73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86MachineFunctionInfo::CalleeSavedFrameSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CalleeSavedFrameSize - Size of the callee-saved register portion of the stack frame in bytes.</p>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### CandidatesForPush2Pop2 {#afaeb4270fc7477a86961e050a08b4b66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt;Register&gt; llvm::X86MachineFunctionInfo::CandidatesForPush2Pop2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Candidate registers for push2/pop2.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### ForceFramePointer {#a4a8abb7996329d68fc0ffc514f97664c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::ForceFramePointer = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ForceFramePointer - True if the function is required to use of frame pointer for reasons other than it containing dynamic allocation or that FP eliminatation is turned off.</p>


<p>For example, Cygwin main function contains stack pointer re-alignment code which requires FP.</p>


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### ForwardedMustTailRegParms {#a92ff445903f35adf4d080b6dde9c018a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;ForwardedRegister, 1&gt; llvm::X86MachineFunctionInfo::ForwardedMustTailRegParms</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ForwardedMustTailRegParms - A list of virtual and physical registers that must be forwarded to every musttail call.</p>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### FPClobberedByCall {#a1a321875825d6abdb3349022e1ba5b7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::FPClobberedByCall = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### FPClobberedByInvoke {#ab05889dcba744e78cbf9ed7c02fd8904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::FPClobberedByInvoke = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### FrameAddrIndex {#a8933d1bdc541c5fe7f9075742cd4a5a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::X86MachineFunctionInfo::FrameAddrIndex = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FrameIndex for return slot.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### GlobalBaseReg {#a7c5595c45141ac2503f4c214c47a16a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::X86MachineFunctionInfo::GlobalBaseReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GlobalBaseReg - keeps track of the virtual register initialized for use as the global base register.</p>


<p>This is used for PIC in some PIC relocation models.</p>


<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### HasCFIAdjustCfa {#ac08f877b63f7eadbfddcb01c47955834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::HasCFIAdjustCfa = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this function has CFI directives that adjust the CFA.</p>


<p>This is used to determine if we should direct the debugger to use the CFA instead of the stack pointer.</p>


<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### HasDynAlloca {#ac395d699c2344317cf6e11a483bd8aac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::HasDynAlloca = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this function has DYN_ALLOCA instructions.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### HasPreallocatedCall {#a693640cd6dd17a9bf912aec86e3a14a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::HasPreallocatedCall = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this function has any preallocated calls.</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### HasPushSequences {#a0c296071aacfb3ee797f23604adb6923}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::HasPushSequences = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HasPushSequences - Keeps track of whether this function uses sequences of pushes to pass function parameters.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### HasSEHFramePtrSave {#ae4938c5769ef18a450d3bf012b8f560a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::HasSEHFramePtrSave = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the function recovers from an SEH exception, and therefore needs to spill and restore the frame pointer.</p>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### HasSwiftAsyncContext {#a9105eeb4f3add00c9c357ccf8788ce04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::HasSwiftAsyncContext = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether this function has an extended frame record [Ctx, RBP, Return addr].</p>


<p>If so, bit 60 of the in-memory frame pointer will be 1 to enable other tools to detect the extended record.</p>


<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### IsSplitCSR {#ac4d7024c36f7c34783c2e04e20e81821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::IsSplitCSR = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this function has a subset of CSRs that is handled explicitly via copies.</p>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### NumLocalDynamics {#a4ba167e518f03bc0feb5a354aa781230}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86MachineFunctionInfo::NumLocalDynamics = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>NumLocalDynamics - Number of local-dynamic TLS accesses.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### PadForPush2Pop2 {#a6ecec15f41360c4bcf77998e4b1dd513}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::PadForPush2Pop2 = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Ajust stack for push2/pop2.</p>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### PreallocatedArgOffsets {#a4ad8c13fe9c0cfe00f3b7eb74e1c9e93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SmallVector&lt;size_t, 4&gt;, 0&gt; llvm::X86MachineFunctionInfo::PreallocatedArgOffsets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### PreallocatedIds {#a3bcf5191ffbe7c4bcd3c164385df06be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Value *, size_t&gt; llvm::X86MachineFunctionInfo::PreallocatedIds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### PreallocatedStackSizes {#ae3bf2ee9723120aa4d48083fc438151f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;size_t, 0&gt; llvm::X86MachineFunctionInfo::PreallocatedStackSizes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### RegSaveFrameIndex {#a4918698f74f12f95abb410cf52054608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::X86MachineFunctionInfo::RegSaveFrameIndex = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RegSaveFrameIndex - X86-64 vararg func register save area.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### RestoreBasePointerOffset {#abbcea3d1f603e5a5c573c50c44a5f2d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">signed char llvm::X86MachineFunctionInfo::RestoreBasePointerOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RestoreBasePointerOffset - Non-zero if the function has base pointer and makes call to llvm.eh.sjlj.setjmp.</p>


<p>When non-zero, the value is a displacement from the frame pointer to a slot where the base pointer is stashed.</p>


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### ReturnAddrIndex {#a720a9c7611729a3089dc7bfffd58f5e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::X86MachineFunctionInfo::ReturnAddrIndex = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ReturnAddrIndex - FrameIndex for return slot.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### SEHFramePtrSaveIndex {#aff188d779c2b8454ffd5167b9f6af753}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::X86MachineFunctionInfo::SEHFramePtrSaveIndex = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The frame index of a stack object containing the original frame pointer used to address arguments in a function using a base pointer.</p>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### SRetReturnReg {#a6e39c9acb6241ee6bed0a1cd4cbaf28c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::X86MachineFunctionInfo::SRetReturnReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SRetReturnReg - Some subtargets require that sret lowering includes returning the value of the returned struct in a register.</p>


<p>This field holds the virtual register into which the sret argument is passed.</p>


<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### StackPtrSaveMI {#a8509eb7f9bbc13c0f00edf30dcbf8822}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr* llvm::X86MachineFunctionInfo::StackPtrSaveMI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### SwiftAsyncContextFrameIdx {#a8433bc19fc5ea21148e6a8fb1083f8e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;int&gt; llvm::X86MachineFunctionInfo::SwiftAsyncContextFrameIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### TailCallReturnAddrDelta {#a204cecc4af9e6312d98356db8552f101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::X86MachineFunctionInfo::TailCallReturnAddrDelta = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>TailCallReturnAddrDelta - The number of bytes by which return address stack slot is moved as the result of tail call optimization.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### UsesRedZone {#a3a28bcea7f7b59415c3e961e03eca9bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86MachineFunctionInfo::UsesRedZone = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this function uses the red zone.</p>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### VarArgsFPOffset {#a03f61a472f712e81361b8f6d6ad74bdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86MachineFunctionInfo::VarArgsFPOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>VarArgsFPOffset - X86-64 vararg func fp reg offset.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### VarArgsFrameIndex {#a40200f2c3ae494e0e9f7053a98419656}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::X86MachineFunctionInfo::VarArgsFrameIndex = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>VarArgsFrameIndex - FrameIndex for start of varargs area.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### VarArgsGPOffset {#ab8ffd27b6f47a5d94b77b9f047bf7560}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86MachineFunctionInfo::VarArgsGPOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>VarArgsGPOffset - X86-64 vararg func int reg offset.</p>

<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

### WinEHXMMSlotInfo {#aa6d14060115d122c0600db54b8aa0243}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;int, unsigned&gt; llvm::X86MachineFunctionInfo::WinEHXMMSlotInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>WinEHXMMSlotInfo - Slot information of XMM registers in the stack frame in bytes.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-cpp">X86MachineFunctionInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
