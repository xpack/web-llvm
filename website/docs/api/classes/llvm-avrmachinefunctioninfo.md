---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/avrmachinefunctioninfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AVRMachineFunctionInfo` Class

<p>Contains AVR-specific information for each <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AVRMachineFunctionInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">Target/AVR/AVRMachineFunctionInfo.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eeab133b80e9db8aa4b2a5db4f9ad92">AVRMachineFunctionInfo</a> (const Function &amp;F, const TargetSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafba9dcb90de37017f086a718e820f76">clone</a> (BumpPtrAllocator &amp;Allocator, MachineFunction &amp;DestMF, const DenseMap&lt; MachineBasicBlock *, MachineBasicBlock * &gt; &amp;Src2DstMBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make a functionally equivalent copy of this <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> in <span class="doxyComputerOutput">MF</span>. <a href="#aafba9dcb90de37017f086a718e820f76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cce480aa250dcf308c173b7c8acf7a8">getHasSpills</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d725f8a272613c6b7884c7ff433fe72">setHasSpills</a> (bool B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d9dcd099ea29cfa2e0308284eb30ae2">getHasAllocas</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa668a7f8ca452d31b3076e6a6d7eaa1">setHasAllocas</a> (bool B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57ec8517da64475011a3090fdec2ca4c">getHasStackArgs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa69944ffca269b40ba7ca9ac9f0c6d3c">setHasStackArgs</a> (bool B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac17732c18d13dab15850181bf0c6632b">isInterruptOrSignalHandler</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the function is some form of interrupt service routine. <a href="#ac17732c18d13dab15850181bf0c6632b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b39797933389c7a7f54508baf6e7b6f">isInterruptHandler</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9db02185b757087a3ca541277e540e28">isSignalHandler</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2141b3008df4f5b6361cc440ddad14bd">getCalleeSavedFrameSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11d0a45f25993f58314625d124b481c2">setCalleeSavedFrameSize</a> (unsigned Bytes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1415b4f33f6e69f97fd597afd614c87">getVarArgsFrameIndex</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a115018e47976b8f57cdfd1087bdb6b9e">setVarArgsFrameIndex</a> (int Idx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaedb7b31ebb552568abe0031d8e4453c">HasSpills</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicates if a register has been spilled by the register allocator. <a href="#aaedb7b31ebb552568abe0031d8e4453c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bdf2eb146d1bfd78d20bc2dd985eec4">HasAllocas</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicates if there are any fixed size allocas present. <a href="#a5bdf2eb146d1bfd78d20bc2dd985eec4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a868cc83f3cc2faf777255647e2f0ee92">HasStackArgs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicates if arguments passed using the stack are being used inside the function. <a href="#a868cc83f3cc2faf777255647e2f0ee92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1373ef2dbccc3eb7e8d87a81de0331cf">IsInterruptHandler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether or not the function is an interrupt handler. <a href="#a1373ef2dbccc3eb7e8d87a81de0331cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea7d5f4b5cd028beb4ad709322ae0b38">IsSignalHandler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether or not the function is an non-blocking interrupt handler. <a href="#aea7d5f4b5cd028beb4ad709322ae0b38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa9b36cae1397a64a1b096bfab6c461a">CalleeSavedFrameSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size of the callee-saved register portion of the stack frame in bytes. <a href="#aaa9b36cae1397a64a1b096bfab6c461a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbd3a57c718c3542ed1c7d1dc30e1625">VarArgsFrameIndex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FrameIndex for start of varargs area. <a href="#afbd3a57c718c3542ed1c7d1dc30e1625">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Contains AVR-specific information for each <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>.</p>

<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AVRMachineFunctionInfo() {#a3eeab133b80e9db8aa4b2a5db4f9ad92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AVRMachineFunctionInfo::AVRMachineFunctionInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> * STI)</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca44deee0b3babbda0be6f27856afaacf9">llvm::CallingConv::AVR_INTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca1e000300c2d50f08aa18761448d5860e">llvm::CallingConv::AVR_SIGNAL</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#aafba9dcb90de37017f086a718e820f76">clone</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#aafba9dcb90de37017f086a718e820f76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionInfo * llvm::AVRMachineFunctionInfo::clone (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; DestMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; Src2DstMBB)</td>
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

<p>Make a functionally equivalent copy of this <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> in <span class="doxyComputerOutput">MF</span>.</p>


<p>This requires remapping <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> references from the original parent to values in the new function. Targets may assume that virtual register and frame index values are preserved in the new function.</p>


<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp/#ad5d00e1d77644d95847b9bf8da12b759">Allocator</a>, <a href="#a3eeab133b80e9db8aa4b2a5db4f9ad92">AVRMachineFunctionInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac31b21febeefe69aaddea3541dae45e1">llvm::MachineFunction::cloneInfo</a>.</p>

</div>
</div>

### getCalleeSavedFrameSize() {#a2141b3008df4f5b6361cc440ddad14bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AVRMachineFunctionInfo::getCalleeSavedFrameSize ()</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a487d00503c99000990bb90458b08702c">llvm::AVRFrameLowering::emitEpilogue</a> and <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a2b9b845d1b6461c8c99fbeed9984f757">llvm::AVRFrameLowering::emitPrologue</a>.</p>

</div>
</div>

### getHasAllocas() {#a9d9dcd099ea29cfa2e0308284eb30ae2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVRMachineFunctionInfo::getHasAllocas ()</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>

</div>
</div>

### getHasSpills() {#a0cce480aa250dcf308c173b7c8acf7a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVRMachineFunctionInfo::getHasSpills ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>

</div>
</div>

### getHasStackArgs() {#a57ec8517da64475011a3090fdec2ca4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVRMachineFunctionInfo::getHasStackArgs ()</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>

</div>
</div>

### getVarArgsFrameIndex() {#af1415b4f33f6e69f97fd597afd614c87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AVRMachineFunctionInfo::getVarArgsFrameIndex ()</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>

</div>
</div>

### isInterruptHandler() {#a0b39797933389c7a7f54508baf6e7b6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVRMachineFunctionInfo::isInterruptHandler ()</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a2b9b845d1b6461c8c99fbeed9984f757">llvm::AVRFrameLowering::emitPrologue</a> and <a href="#ac17732c18d13dab15850181bf0c6632b">isInterruptOrSignalHandler</a>.</p>

</div>
</div>

### isInterruptOrSignalHandler() {#ac17732c18d13dab15850181bf0c6632b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVRMachineFunctionInfo::isInterruptOrSignalHandler ()</td>
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

<p>Checks if the function is some form of interrupt service routine.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>


<p>References <a href="#a0b39797933389c7a7f54508baf6e7b6f">isInterruptHandler</a> and <a href="#a9db02185b757087a3ca541277e540e28">isSignalHandler</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a487d00503c99000990bb90458b08702c">llvm::AVRFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a2b9b845d1b6461c8c99fbeed9984f757">llvm::AVRFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/avrregisterinfo/#a5fed817180c0a1204b7ef76df3803fd6">llvm::AVRRegisterInfo::getCalleeSavedRegs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab49c96f446ff54d9f4d51653b4542581">llvm::restoreStatusRegister</a>.</p>

</div>
</div>

### isSignalHandler() {#a9db02185b757087a3ca541277e540e28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVRMachineFunctionInfo::isSignalHandler ()</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="#ac17732c18d13dab15850181bf0c6632b">isInterruptOrSignalHandler</a>.</p>

</div>
</div>

### setCalleeSavedFrameSize() {#a11d0a45f25993f58314625d124b481c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRMachineFunctionInfo::setCalleeSavedFrameSize (unsigned Bytes)</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#af676cadcef1e3d4d159420f075a083da">llvm::AVRFrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### setHasAllocas() {#aaa668a7f8ca452d31b3076e6a6d7eaa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRMachineFunctionInfo::setHasAllocas (bool B)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/avrframeanalyzer/#a854b8ec11315be5c7771d9aca8762e51">llvm::AVRFrameAnalyzer::runOnMachineFunction</a>.</p>

</div>
</div>

### setHasSpills() {#a5d725f8a272613c6b7884c7ff433fe72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRMachineFunctionInfo::setHasSpills (bool B)</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#a90829bf41a9e8e4c4e4ad59eab490719">llvm::AVRInstrInfo::storeRegToStackSlot</a>.</p>

</div>
</div>

### setHasStackArgs() {#aa69944ffca269b40ba7ca9ac9f0c6d3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRMachineFunctionInfo::setHasStackArgs (bool B)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/avrframeanalyzer/#a854b8ec11315be5c7771d9aca8762e51">llvm::AVRFrameAnalyzer::runOnMachineFunction</a>.</p>

</div>
</div>

### setVarArgsFrameIndex() {#a115018e47976b8f57cdfd1087bdb6b9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRMachineFunctionInfo::setVarArgsFrameIndex (int Idx)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CalleeSavedFrameSize {#aaa9b36cae1397a64a1b096bfab6c461a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AVRMachineFunctionInfo::CalleeSavedFrameSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size of the callee-saved register portion of the stack frame in bytes.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>

</div>
</div>

### HasAllocas {#a5bdf2eb146d1bfd78d20bc2dd985eec4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVRMachineFunctionInfo::HasAllocas</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicates if there are any fixed size allocas present.</p>


<p>Note that if there are only variable sized allocas this is set to false.</p>


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>

</div>
</div>

### HasSpills {#aaedb7b31ebb552568abe0031d8e4453c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVRMachineFunctionInfo::HasSpills</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicates if a register has been spilled by the register allocator.</p>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>

</div>
</div>

### HasStackArgs {#a868cc83f3cc2faf777255647e2f0ee92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVRMachineFunctionInfo::HasStackArgs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicates if arguments passed using the stack are being used inside the function.</p>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>

</div>
</div>

### IsInterruptHandler {#a1373ef2dbccc3eb7e8d87a81de0331cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVRMachineFunctionInfo::IsInterruptHandler</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether or not the function is an interrupt handler.</p>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>

</div>
</div>

### IsSignalHandler {#aea7d5f4b5cd028beb4ad709322ae0b38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVRMachineFunctionInfo::IsSignalHandler</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether or not the function is an non-blocking interrupt handler.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>

</div>
</div>

### VarArgsFrameIndex {#afbd3a57c718c3542ed1c7d1dc30e1625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AVRMachineFunctionInfo::VarArgsFrameIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FrameIndex for start of varargs area.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmachinefunctioninfo-h">AVRMachineFunctionInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
