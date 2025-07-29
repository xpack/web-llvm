---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/coalescerpair
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CoalescerPair` Class

<p>A helper class for register coalescers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CoalescerPair { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">CodeGen/RegisterCoalescer.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa013d67c62eb366965c005c68c40728">CoalescerPair</a> (const TargetRegisterInfo &amp;tri)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf17891df4552960f7cad19b8ca82b62">CoalescerPair</a> (Register VirtReg, MCRegister PhysReg, const TargetRegisterInfo &amp;tri)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/coalescerpair">CoalescerPair</a> representing a virtreg-to-physreg copy. <a href="#abf17891df4552960f7cad19b8ca82b62">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf12cb8b07d5443c8777257d1b9a1dc7">setRegisters</a> (const MachineInstr *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set registers to match the copy instruction MI. <a href="#acf12cb8b07d5443c8777257d1b9a1dc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46ebf2b548d5b38599073fe56b75bec0">flip</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Swap SrcReg and DstReg. <a href="#a46ebf2b548d5b38599073fe56b75bec0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa94992e6e4022b1175f8015cde4e60b9">isCoalescable</a> (const MachineInstr *) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if MI is a copy instruction that will become an identity copy after coalescing. <a href="#aa94992e6e4022b1175f8015cde4e60b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a482f72c011676e20369df64071b8ed78">isPhys</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if DstReg is a physical register. <a href="#a482f72c011676e20369df64071b8ed78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40c42cd26b1b685f9b48eb6ecc2292ca">isPartial</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the original copy instruction did not copy the full register, but was a subreg operation. <a href="#a40c42cd26b1b685f9b48eb6ecc2292ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51b0e53d4cf5d0e50a02e2db7a4f2d28">isCrossClass</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if DstReg is virtual and NewRC is a smaller register class than DstReg's. <a href="#a51b0e53d4cf5d0e50a02e2db7a4f2d28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3204a960879abea13e886095a0638127">isFlipped</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true when getSrcReg is the register being defined by the original copy instruction. <a href="#a3204a960879abea13e886095a0638127">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa72ddffcaae30a5d3a6dabbb56730af7">getDstReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the register (virtual or physical) that will remain after coalescing. <a href="#aa72ddffcaae30a5d3a6dabbb56730af7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfcfaf1c9119cdf3e897cf6beb8dbbab">getSrcReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the virtual register that will be coalesced away. <a href="#adfcfaf1c9119cdf3e897cf6beb8dbbab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f9ef77c6729d00fb212b2166aeca293">getDstIdx</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the subregister index that DstReg will be coalesced into, or 0. <a href="#a2f9ef77c6729d00fb212b2166aeca293">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad845a1a2a2239f0b62f818d88a875c89">getSrcIdx</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the subregister index that SrcReg will be coalesced into, or 0. <a href="#ad845a1a2a2239f0b62f818d88a875c89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9f260c963fc6dac4d8f4440bb17e5c7">getNewRC</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the register class of the coalesced register. <a href="#ac9f260c963fc6dac4d8f4440bb17e5c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67febc3d73e1c873915d20721f7ed83e">TRI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a734ffa360f7514e636b181b94804c869">DstReg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The register that will be left after coalescing. <a href="#a734ffa360f7514e636b181b94804c869">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a849c4ee7be104ab978da5c3781da6a16">SrcReg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The virtual register that will be coalesced into dstReg. <a href="#a849c4ee7be104ab978da5c3781da6a16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41ef5aced9c37d597c8ca0448a6a6153">DstIdx</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The sub-register index of the old DstReg in the new coalesced register. <a href="#a41ef5aced9c37d597c8ca0448a6a6153">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2287c7065b3d41e7c200ea57cb4257a8">SrcIdx</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The sub-register index of the old SrcReg in the new coalesced register. <a href="#a2287c7065b3d41e7c200ea57cb4257a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae02d6b077dd070ceba561cb21449b7eb">Partial</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True when the original copy was a partial subregister copy. <a href="#ae02d6b077dd070ceba561cb21449b7eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6b309ab4bf10b5c0698b0a310cd6713">CrossClass</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True when both regs are virtual and newRC is constrained. <a href="#ae6b309ab4bf10b5c0698b0a310cd6713">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1b52c8b96455a7caa7fbf62991e2436">Flipped</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True when DstReg and SrcReg are reversed from the original copy instruction. <a href="#ae1b52c8b96455a7caa7fbf62991e2436">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad747588bde4decbb98b226aff52e861f">NewRC</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The register class of the coalesced register, or NULL if DstReg is a physreg. <a href="#ad747588bde4decbb98b226aff52e861f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A helper class for register coalescers.</p>


<p>When deciding if two registers can be coalesced, <a href="/web-llvm/docs/api/classes/llvm/coalescerpair">CoalescerPair</a> can determine if a copy instruction would become an identity copy after coalescing.</p>


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CoalescerPair() {#aaa013d67c62eb366965c005c68c40728}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CoalescerPair::CoalescerPair (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; tri)</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>.</p>

</div>
</div>

### CoalescerPair() {#abf17891df4552960f7cad19b8ca82b62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CoalescerPair::CoalescerPair (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VirtReg, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; tri)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/coalescerpair">CoalescerPair</a> representing a virtreg-to-physreg copy.</p>


<p>No need to call <a href="#acf12cb8b07d5443c8777257d1b9a1dc7">setRegisters()</a>.</p>


<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### flip() {#a46ebf2b548d5b38599073fe56b75bec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CoalescerPair::flip ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Swap SrcReg and DstReg.</p>


<p>Return false if swapping is impossible because DstReg is a physical register, or SubIdx is set.</p>


<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>, definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### getDstIdx() {#a2f9ef77c6729d00fb212b2166aeca293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CoalescerPair::getDstIdx ()</td>
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

<p>Return the subregister index that DstReg will be coalesced into, or 0.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>.</p>

</div>
</div>

### getDstReg() {#aa72ddffcaae30a5d3a6dabbb56730af7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::CoalescerPair::getDstReg ()</td>
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

<p>Return the register (virtual or physical) that will remain after coalescing.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>.</p>

</div>
</div>

### getNewRC() {#ac9f260c963fc6dac4d8f4440bb17e5c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * llvm::CoalescerPair::getNewRC ()</td>
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

<p>Return the register class of the coalesced register.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>.</p>

</div>
</div>

### getSrcIdx() {#ad845a1a2a2239f0b62f818d88a875c89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CoalescerPair::getSrcIdx ()</td>
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

<p>Return the subregister index that SrcReg will be coalesced into, or 0.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>.</p>

</div>
</div>

### getSrcReg() {#adfcfaf1c9119cdf3e897cf6beb8dbbab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::CoalescerPair::getSrcReg ()</td>
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

<p>Return the virtual register that will be coalesced away.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>.</p>

</div>
</div>

### isCoalescable() {#aa94992e6e4022b1175f8015cde4e60b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CoalescerPair::isCoalescable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if MI is a copy instruction that will become an identity copy after coalescing.</p>

<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>, definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#aaeffdea43602557f6c520f6b9501a491">isMoveInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### isCrossClass() {#a51b0e53d4cf5d0e50a02e2db7a4f2d28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CoalescerPair::isCrossClass ()</td>
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

<p>Return true if DstReg is virtual and NewRC is a smaller register class than DstReg's.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>.</p>

</div>
</div>

### isFlipped() {#a3204a960879abea13e886095a0638127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CoalescerPair::isFlipped ()</td>
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

<p>Return true when getSrcReg is the register being defined by the original copy instruction.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>.</p>

</div>
</div>

### isPartial() {#a40c42cd26b1b685f9b48eb6ecc2292ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CoalescerPair::isPartial ()</td>
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

<p>Return true if the original copy instruction did not copy the full register, but was a subreg operation.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>.</p>

</div>
</div>

### isPhys() {#a482f72c011676e20369df64071b8ed78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CoalescerPair::isPhys ()</td>
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

<p>Return true if DstReg is a physical register.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>.</p>

</div>
</div>

### setRegisters() {#acf12cb8b07d5443c8777257d1b9a1dc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CoalescerPair::setRegisters (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set registers to match the copy instruction MI.</p>


<p>Return false if MI is not a coalescable copy instruction.</p>


<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>, definition at line 451 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#aaeffdea43602557f6c520f6b9501a491">isMoveInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CrossClass {#ae6b309ab4bf10b5c0698b0a310cd6713}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CoalescerPair::CrossClass = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True when both regs are virtual and newRC is constrained.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>.</p>

</div>
</div>

### DstIdx {#a41ef5aced9c37d597c8ca0448a6a6153}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CoalescerPair::DstIdx = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The sub-register index of the old DstReg in the new coalesced register.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>.</p>

</div>
</div>

### DstReg {#a734ffa360f7514e636b181b94804c869}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::CoalescerPair::DstReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The register that will be left after coalescing.</p>


<p>It can be a virtual or physical register.</p>


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>.</p>

</div>
</div>

### Flipped {#ae1b52c8b96455a7caa7fbf62991e2436}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CoalescerPair::Flipped = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True when DstReg and SrcReg are reversed from the original copy instruction.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>.</p>

</div>
</div>

### NewRC {#ad747588bde4decbb98b226aff52e861f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass* llvm::CoalescerPair::NewRC = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The register class of the coalesced register, or NULL if DstReg is a physreg.</p>


<p>This register class may be a super-register of both SrcReg and DstReg.</p>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>.</p>

</div>
</div>

### Partial {#ae02d6b077dd070ceba561cb21449b7eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CoalescerPair::Partial = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True when the original copy was a partial subregister copy.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>.</p>

</div>
</div>

### SrcIdx {#a2287c7065b3d41e7c200ea57cb4257a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CoalescerPair::SrcIdx = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The sub-register index of the old SrcReg in the new coalesced register.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>.</p>

</div>
</div>

### SrcReg {#a849c4ee7be104ab978da5c3781da6a16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::CoalescerPair::SrcReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The virtual register that will be coalesced into dstReg.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>.</p>

</div>
</div>

### TRI {#a67febc3d73e1c873915d20721f7ed83e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo&amp; llvm::CoalescerPair::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
