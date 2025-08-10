---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/false/chain
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Chain` Class

<p>A <a href="/web-llvm/docs/api/classes/false/chain">Chain</a> is a sequence of instructions that are linked together by an accumulation operand. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class false::Chain { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee9600292727f2fa4fde78d5a92dc236">Chain</a> (MachineInstr *MI, unsigned Idx, Color C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a436c1e15448cef4d991f2fe22d3192e3">add</a> (MachineInstr *MI, unsigned Idx, Color C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new instruction into the chain. <a href="#a436c1e15448cef4d991f2fe22d3192e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a437f5dea2d6a570302a25ad846d6269a">contains</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if MI is a member of the chain. <a href="#a437f5dea2d6a570302a25ad846d6269a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a948d2c7a31971eaa190d6d9947952e12">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of instructions in the chain. <a href="#a948d2c7a31971eaa190d6d9947952e12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab06c413e8426ec3278bf286096ad4d4">setKill</a> (MachineInstr *MI, unsigned Idx, bool Immutable)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inform the chain that its last active register (the dest register of LastInst) is killed by MI with no intervening uses or defs. <a href="#aab06c413e8426ec3278bf286096ad4d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93e45317f81c1f9b9fb3e11ff6024ce9">getStart</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the first instruction in the chain. <a href="#a93e45317f81c1f9b9fb3e11ff6024ce9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4da928086ab01a37cf8aa52486b76448">getLast</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the last instruction in the chain. <a href="#a4da928086ab01a37cf8aa52486b76448">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0806574a2e03fdb6f0d63cfb4510ca9">getKill</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the "kill" instruction (as set with <a href="#aab06c413e8426ec3278bf286096ad4d4">setKill()</a>) or NULL. <a href="#ac0806574a2e03fdb6f0d63cfb4510ca9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa69ba368f0dbf9d31baadcf8d2b8595b">end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an instruction that can be used as an iterator for the end of the chain. <a href="#aa69ba368f0dbf9d31baadcf8d2b8595b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a10ae10f793a1bb57c7e7f9d10e6204">begin</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a242ae2e003983f73e80229f9b520f27b">isKillImmutable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Can the Kill instruction (assuming one exists) be modified? <a href="#a242ae2e003983f73e80229f9b520f27b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Color</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbd6cc4352783c89ce67fc7d2fc77850">getPreferredColor</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the preferred color of this chain. <a href="#acbd6cc4352783c89ce67fc7d2fc77850">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76ad36ab0515ba53487d12e5df9e5625">rangeOverlapsWith</a> (const Chain &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this chain (StartInst..KillInst) overlaps with Other. <a href="#a76ad36ab0515ba53487d12e5df9e5625">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefe9b847a56424e9427788f1e3a3b6f7">startsBefore</a> (const Chain *Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this chain starts before Other. <a href="#aefe9b847a56424e9427788f1e3a3b6f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48f08cdb2b7e8a044b63f57aefad81ba">requiresFixup</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the group will require a fixup MOV at the end. <a href="#a48f08cdb2b7e8a044b63f57aefad81ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3bc2dfe7381ebca7db8684a3857dc70">str</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a simple string representation of the chain. <a href="#ad3bc2dfe7381ebca7db8684a3857dc70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1553bd6e78ea9177de190ce4addeb392">StartInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The important (marker) instructions. <a href="#a1553bd6e78ea9177de190ce4addeb392">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a565f98cf4f5f33af6233b9ffdc082fce">LastInst</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65144b49ba3235cb183af7fab18cef2d">KillInst</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6ffab478097165a127457308b62b26f">StartInstIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The index, from the start of the basic block, that each marker appears. <a href="#ac6ffab478097165a127457308b62b26f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a365681be653030e9a3d47d8acba5081e">LastInstIdx</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb3eab4006dc9a27eb3264b96d8bde25">KillInstIdx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::set&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfd85aee545d5d83b09a2738d10d6026">Insts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All instructions in the chain. <a href="#adfd85aee545d5d83b09a2738d10d6026">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7655b394cca735c1235fec4aabc732e1">KillIsImmutable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if KillInst cannot be modified. <a href="#a7655b394cca735c1235fec4aabc732e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Color</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47850ade96273e27edb80362e3757cee">LastColor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The "color" of LastInst. <a href="#a47850ade96273e27edb80362e3757cee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A <a href="/web-llvm/docs/api/classes/false/chain">Chain</a> is a sequence of instructions that are linked together by an accumulation operand.</p>


<p>For example:</p>


<p>fmul def d0, ? fmla def d1, ?, ?, killed d0 fmla def d2, ?, ?, killed d1</p>


<p>There may be other instructions interleaved in the sequence that do not belong to the chain. These other instructions must not use the "chain" register at any point.</p>


<p>We currently only support chains where the "chain" operand is killed at each link in the chain for simplicity. A chain has three important instructions - Start, Last and Kill.</p>


<ul class="doxyList ">
<li>The start instruction is the first instruction in the chain.</li>
<li>Last is the final instruction in the chain.</li>
<li>Kill may or may not be defined. If defined, Kill is the instruction where the outgoing value of the Last instruction is killed. This information is important as if we know the outgoing value is killed with no intervening uses, we can safely change its register.</li>
</ul>

<p>Without a kill instruction, we must assume the outgoing value escapes beyond our model and either must not change its register or must create a fixup FMOV to keep the old register value consistent.</p>


<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Chain() {#aee9600292727f2fa4fde78d5a92dc236}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">false::Chain::Chain (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned Idx, Color C)</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#adfd85aee545d5d83b09a2738d10d6026">Insts</a>, <a href="#a65144b49ba3235cb183af7fab18cef2d">KillInst</a>, <a href="#acb3eab4006dc9a27eb3264b96d8bde25">KillInstIdx</a>, <a href="#a47850ade96273e27edb80362e3757cee">LastColor</a>, <a href="#a565f98cf4f5f33af6233b9ffdc082fce">LastInst</a>, <a href="#a365681be653030e9a3d47d8acba5081e">LastInstIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a1553bd6e78ea9177de190ce4addeb392">StartInst</a> and <a href="#ac6ffab478097165a127457308b62b26f">StartInstIdx</a>.</p>


<p>Referenced by <a href="#a76ad36ab0515ba53487d12e5df9e5625">rangeOverlapsWith</a> and <a href="#aefe9b847a56424e9427788f1e3a3b6f7">startsBefore</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a436c1e15448cef4d991f2fe22d3192e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void false::Chain::add (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned Idx, Color C)</td>
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

<p>Add a new instruction into the chain.</p>


<p>The instruction's dest operand has the given color.</p>


<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#adfd85aee545d5d83b09a2738d10d6026">Insts</a>, <a href="#acb3eab4006dc9a27eb3264b96d8bde25">KillInstIdx</a>, <a href="#a47850ade96273e27edb80362e3757cee">LastColor</a>, <a href="#a565f98cf4f5f33af6233b9ffdc082fce">LastInst</a>, <a href="#a365681be653030e9a3d47d8acba5081e">LastInstIdx</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### begin() {#a1a10ae10f793a1bb57c7e7f9d10e6204}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator false::Chain::begin ()</td>
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



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>Reference <a href="#a93e45317f81c1f9b9fb3e11ff6024ce9">getStart</a>.</p>

</div>
</div>

### contains() {#a437f5dea2d6a570302a25ad846d6269a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool false::Chain::contains (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Return true if MI is a member of the chain.</p>

<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>References <a href="#adfd85aee545d5d83b09a2738d10d6026">Insts</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### end() {#aa69ba368f0dbf9d31baadcf8d2b8595b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator false::Chain::end ()</td>
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

<p>Return an instruction that can be used as an iterator for the end of the chain.</p>


<p>This is the maximum of KillInst (if set) and LastInst.</p>


<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>References <a href="#a65144b49ba3235cb183af7fab18cef2d">KillInst</a> and <a href="#a565f98cf4f5f33af6233b9ffdc082fce">LastInst</a>.</p>

</div>
</div>

### getKill() {#ac0806574a2e03fdb6f0d63cfb4510ca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * false::Chain::getKill ()</td>
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

<p>Return the "kill" instruction (as set with <a href="#aab06c413e8426ec3278bf286096ad4d4">setKill()</a>) or NULL.</p>

<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>Reference <a href="#a65144b49ba3235cb183af7fab18cef2d">KillInst</a>.</p>


<p>Referenced by <a href="#a48f08cdb2b7e8a044b63f57aefad81ba">requiresFixup</a>.</p>

</div>
</div>

### getLast() {#a4da928086ab01a37cf8aa52486b76448}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * false::Chain::getLast ()</td>
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

<p>Return the last instruction in the chain.</p>

<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>Reference <a href="#a565f98cf4f5f33af6233b9ffdc082fce">LastInst</a>.</p>

</div>
</div>

### getPreferredColor() {#acbd6cc4352783c89ce67fc7d2fc77850}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Color false::Chain::getPreferredColor ()</td>
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

<p>Return the preferred color of this chain.</p>

<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64a57fploadbalancing-cpp-/#afcb9ac67c90816f55d217d4f629e1047a35537fbc25d87ffe59e4f35fefcd34b7">anonymous{AArch64A57FPLoadBalancing.cpp}::Even</a>, <a href="#a47850ade96273e27edb80362e3757cee">LastColor</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64a57fploadbalancing-cpp-/#afcb9ac67c90816f55d217d4f629e1047a37b6bd7fe61d651735cec3d3b0356c66">anonymous{AArch64A57FPLoadBalancing.cpp}::Odd</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp/#a1befee98e40abcfb39882594311f6379">OverrideBalance</a>.</p>

</div>
</div>

### getStart() {#a93e45317f81c1f9b9fb3e11ff6024ce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * false::Chain::getStart ()</td>
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

<p>Return the first instruction in the chain.</p>

<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>Reference <a href="#a1553bd6e78ea9177de190ce4addeb392">StartInst</a>.</p>


<p>Referenced by <a href="#a1a10ae10f793a1bb57c7e7f9d10e6204">begin</a>.</p>

</div>
</div>

### isKillImmutable() {#a242ae2e003983f73e80229f9b520f27b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool false::Chain::isKillImmutable ()</td>
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

<p>Can the Kill instruction (assuming one exists) be modified?</p>

<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>Reference <a href="#a7655b394cca735c1235fec4aabc732e1">KillIsImmutable</a>.</p>


<p>Referenced by <a href="#a48f08cdb2b7e8a044b63f57aefad81ba">requiresFixup</a>.</p>

</div>
</div>

### rangeOverlapsWith() {#a76ad36ab0515ba53487d12e5df9e5625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool false::Chain::rangeOverlapsWith (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/false/chain">Chain</a> &amp; Other)</td>
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

<p>Return true if this chain (StartInst..KillInst) overlaps with Other.</p>

<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>References <a href="#aee9600292727f2fa4fde78d5a92dc236">Chain</a>, <a href="#a65144b49ba3235cb183af7fab18cef2d">KillInst</a>, <a href="#acb3eab4006dc9a27eb3264b96d8bde25">KillInstIdx</a>, <a href="#a365681be653030e9a3d47d8acba5081e">LastInstIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#ac6ffab478097165a127457308b62b26f">StartInstIdx</a>.</p>

</div>
</div>

### requiresFixup() {#a48f08cdb2b7e8a044b63f57aefad81ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool false::Chain::requiresFixup ()</td>
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

<p>Return true if the group will require a fixup MOV at the end.</p>

<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>References <a href="#ac0806574a2e03fdb6f0d63cfb4510ca9">getKill</a> and <a href="#a242ae2e003983f73e80229f9b520f27b">isKillImmutable</a>.</p>

</div>
</div>

### setKill() {#aab06c413e8426ec3278bf286096ad4d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void false::Chain::setKill (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned Idx, bool Immutable)</td>
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

<p>Inform the chain that its last active register (the dest register of LastInst) is killed by MI with no intervening uses or defs.</p>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a65144b49ba3235cb183af7fab18cef2d">KillInst</a>, <a href="#acb3eab4006dc9a27eb3264b96d8bde25">KillInstIdx</a>, <a href="#a7655b394cca735c1235fec4aabc732e1">KillIsImmutable</a>, <a href="#a365681be653030e9a3d47d8acba5081e">LastInstIdx</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### size() {#a948d2c7a31971eaa190d6d9947952e12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned false::Chain::size ()</td>
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

<p>Return the number of instructions in the chain.</p>

<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>Reference <a href="#adfd85aee545d5d83b09a2738d10d6026">Insts</a>.</p>

</div>
</div>

### startsBefore() {#aefe9b847a56424e9427788f1e3a3b6f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool false::Chain::startsBefore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/false/chain">Chain</a> * Other)</td>
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

<p>Return true if this chain starts before Other.</p>

<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>References <a href="#aee9600292727f2fa4fde78d5a92dc236">Chain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#ac6ffab478097165a127457308b62b26f">StartInstIdx</a>.</p>

</div>
</div>

### str() {#ad3bc2dfe7381ebca7db8684a3857dc70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string false::Chain::str ()</td>
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

<p>Return a simple string representation of the chain.</p>

<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>References <a href="#a65144b49ba3235cb183af7fab18cef2d">KillInst</a>, <a href="#a565f98cf4f5f33af6233b9ffdc082fce">LastInst</a>, <a href="#a1553bd6e78ea9177de190ce4addeb392">StartInst</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Insts {#adfd85aee545d5d83b09a2738d10d6026}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt;MachineInstr*&gt; false::Chain::Insts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All instructions in the chain.</p>

<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>Referenced by <a href="#a436c1e15448cef4d991f2fe22d3192e3">add</a>, <a href="#aee9600292727f2fa4fde78d5a92dc236">Chain</a>, <a href="#a437f5dea2d6a570302a25ad846d6269a">contains</a> and <a href="#a948d2c7a31971eaa190d6d9947952e12">size</a>.</p>

</div>
</div>

### KillInst {#a65144b49ba3235cb183af7fab18cef2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * false::Chain::KillInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>Referenced by <a href="#aee9600292727f2fa4fde78d5a92dc236">Chain</a>, <a href="#aa69ba368f0dbf9d31baadcf8d2b8595b">end</a>, <a href="#ac0806574a2e03fdb6f0d63cfb4510ca9">getKill</a>, <a href="#a76ad36ab0515ba53487d12e5df9e5625">rangeOverlapsWith</a>, <a href="#aab06c413e8426ec3278bf286096ad4d4">setKill</a> and <a href="#ad3bc2dfe7381ebca7db8684a3857dc70">str</a>.</p>

</div>
</div>

### KillInstIdx {#acb3eab4006dc9a27eb3264b96d8bde25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned false::Chain::KillInstIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>Referenced by <a href="#a436c1e15448cef4d991f2fe22d3192e3">add</a>, <a href="#aee9600292727f2fa4fde78d5a92dc236">Chain</a>, <a href="#a76ad36ab0515ba53487d12e5df9e5625">rangeOverlapsWith</a> and <a href="#aab06c413e8426ec3278bf286096ad4d4">setKill</a>.</p>

</div>
</div>

### KillIsImmutable {#a7655b394cca735c1235fec4aabc732e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool false::Chain::KillIsImmutable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if KillInst cannot be modified.</p>


<p>If this is true, we cannot change LastInst's outgoing register. This will be true for tied values and regmasks.</p>


<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>Referenced by <a href="#a242ae2e003983f73e80229f9b520f27b">isKillImmutable</a> and <a href="#aab06c413e8426ec3278bf286096ad4d4">setKill</a>.</p>

</div>
</div>

### LastColor {#a47850ade96273e27edb80362e3757cee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Color false::Chain::LastColor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The "color" of LastInst.</p>


<p>This will be the preferred chain color, as changing intermediate nodes is easy but changing the last instruction can be more tricky.</p>


<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>Referenced by <a href="#a436c1e15448cef4d991f2fe22d3192e3">add</a>, <a href="#aee9600292727f2fa4fde78d5a92dc236">Chain</a> and <a href="#acbd6cc4352783c89ce67fc7d2fc77850">getPreferredColor</a>.</p>

</div>
</div>

### LastInst {#a565f98cf4f5f33af6233b9ffdc082fce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * false::Chain::LastInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>Referenced by <a href="#a436c1e15448cef4d991f2fe22d3192e3">add</a>, <a href="#aee9600292727f2fa4fde78d5a92dc236">Chain</a>, <a href="#aa69ba368f0dbf9d31baadcf8d2b8595b">end</a>, <a href="#a4da928086ab01a37cf8aa52486b76448">getLast</a> and <a href="#ad3bc2dfe7381ebca7db8684a3857dc70">str</a>.</p>

</div>
</div>

### LastInstIdx {#a365681be653030e9a3d47d8acba5081e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned false::Chain::LastInstIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>Referenced by <a href="#a436c1e15448cef4d991f2fe22d3192e3">add</a>, <a href="#aee9600292727f2fa4fde78d5a92dc236">Chain</a>, <a href="#a76ad36ab0515ba53487d12e5df9e5625">rangeOverlapsWith</a> and <a href="#aab06c413e8426ec3278bf286096ad4d4">setKill</a>.</p>

</div>
</div>

### StartInst {#a1553bd6e78ea9177de190ce4addeb392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr* false::Chain::StartInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The important (marker) instructions.</p>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>Referenced by <a href="#aee9600292727f2fa4fde78d5a92dc236">Chain</a>, <a href="#a93e45317f81c1f9b9fb3e11ff6024ce9">getStart</a> and <a href="#ad3bc2dfe7381ebca7db8684a3857dc70">str</a>.</p>

</div>
</div>

### StartInstIdx {#ac6ffab478097165a127457308b62b26f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned false::Chain::StartInstIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The index, from the start of the basic block, that each marker appears.</p>


<p>These are stored so we can do quick interval tests.</p>


<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a>.</p>


<p>Referenced by <a href="#aee9600292727f2fa4fde78d5a92dc236">Chain</a>, <a href="#a76ad36ab0515ba53487d12e5df9e5625">rangeOverlapsWith</a> and <a href="#aefe9b847a56424e9427788f1e3a3b6f7">startsBefore</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a57fploadbalancing-cpp">AArch64A57FPLoadBalancing.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
