---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/livephysregs
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LivePhysRegs` Class

<p>A set of physical registers with utility functions to track liveness when walking backward/forward through a basic block. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LivePhysRegs { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">llvm/CodeGen/LivePhysRegs.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1912d31185cc61ee9ba2fa62b5ccaf5f">const_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/sparseset/#adcffed9f9e28c03e4b254b733dd9a9d1">RegisterSet::const_iterator</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a774f231ee87df8264c49a8d5f88a7c">RegisterSet</a> = <a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a>, <a href="/web-llvm/docs/api/structs/llvm/identity">identity</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt; &gt;</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbe6939e3bddd71f4a12a6528d1abb78">LivePhysRegs</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs an unitialized set. <a href="#a8b52495cd160fff98521b57a4479f2da">init()</a> needs to be called to initialize it. <a href="#abbe6939e3bddd71f4a12a6528d1abb78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab60ebf245879fc2c1a9299329d343081">LivePhysRegs</a> (const TargetRegisterInfo &amp;TRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs and initializes an empty set. <a href="#ab60ebf245879fc2c1a9299329d343081">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c680bb9900ecd38fd9cfa94c024911f">LivePhysRegs</a> (const LivePhysRegs &amp;)=delete</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/livephysregs">LivePhysRegs</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0013c439ff8a7df2974b9b6930d03c8">operator=</a> (const LivePhysRegs &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b52495cd160fff98521b57a4479f2da">init</a> (const TargetRegisterInfo &amp;TRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>(re-)initializes and clears the set. <a href="#a8b52495cd160fff98521b57a4479f2da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30e045ff918c93beb68e7db808287d7a">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clears the set. <a href="#a30e045ff918c93beb68e7db808287d7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9dd17c81890dfa50eceb32282809600">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the set is empty. <a href="#ae9dd17c81890dfa50eceb32282809600">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbf2afbb346e40106f344191309324fc">addReg</a> (MCPhysReg Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a physical register and all its sub-registers to the set. <a href="#adbf2afbb346e40106f344191309324fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b644203b542cf4091b1ff74bafe78ac">removeReg</a> (MCPhysReg Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes a physical register, all its sub-registers, and all its super-registers from the set. <a href="#a7b644203b542cf4091b1ff74bafe78ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfee5cf71110ecb406e359e538fc3cf9">removeRegsInMask</a> (const MachineOperand &amp;MO, SmallVectorImpl&lt; std::pair&lt; MCPhysReg, const MachineOperand * &gt; &gt; *Clobbers=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes physical registers clobbered by the regmask operand <span class="doxyComputerOutput">MO</span>. <a href="#adfee5cf71110ecb406e359e538fc3cf9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05ce2aec67d9c398ce268ac0c33c5c7b">contains</a> (MCPhysReg Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if register <span class="doxyComputerOutput">Reg</span> is contained in the set. <a href="#a05ce2aec67d9c398ce268ac0c33c5c7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c249924553aa84c5927b2335c490583">available</a> (const MachineRegisterInfo &amp;MRI, MCPhysReg Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if register <span class="doxyComputerOutput">Reg</span> and no aliasing register is in the set. <a href="#a5c249924553aa84c5927b2335c490583">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9eb9ea8517269ca82f836b915fa94ca">removeDefs</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove defined registers and regmask kills from the set. <a href="#aa9eb9ea8517269ca82f836b915fa94ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa64a4c432876fe5615cab79fd5650f7a">addUses</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add uses to the set. <a href="#aa64a4c432876fe5615cab79fd5650f7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a683d33b7b0ca1cf29e61a3dc4614a046">stepBackward</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simulates liveness when stepping backwards over an instruction(bundle). <a href="#a683d33b7b0ca1cf29e61a3dc4614a046">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f06df57fdd66d54f952c1c60e5048c3">stepForward</a> (const MachineInstr &amp;MI, SmallVectorImpl&lt; std::pair&lt; MCPhysReg, const MachineOperand * &gt; &gt; &amp;Clobbers)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simulates liveness when stepping forward over an instruction(bundle). <a href="#a3f06df57fdd66d54f952c1c60e5048c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a972dc07ee343dfa21fc84131ada0e688">addLiveIns</a> (const MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds all live-in registers of basic block <span class="doxyComputerOutput">MBB</span>. <a href="#a972dc07ee343dfa21fc84131ada0e688">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceb9a8356104b139deb7cec444f8361c">addLiveInsNoPristines</a> (const MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds all live-in registers of basic block <span class="doxyComputerOutput">MBB</span> but skips pristine registers. <a href="#aceb9a8356104b139deb7cec444f8361c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb67d4b6f48395a5aca25fc32e042928">addLiveOuts</a> (const MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds all live-out registers of basic block <span class="doxyComputerOutput">MBB</span>. <a href="#abb67d4b6f48395a5aca25fc32e042928">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab22bacf399a5964155b56e9be835a6b3">addLiveOutsNoPristines</a> (const MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds all live-out registers of basic block <span class="doxyComputerOutput">MBB</span> but skips pristine registers. <a href="#ab22bacf399a5964155b56e9be835a6b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1912d31185cc61ee9ba2fa62b5ccaf5f">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc2dfac325582d82eb5782973d8e3ded">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1912d31185cc61ee9ba2fa62b5ccaf5f">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2312b1101c183ac421957b4aab3c4c68">end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60cf8009004efc869b27da93e796c2ec">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prints the currently live registers to <span class="doxyComputerOutput">OS</span>. <a href="#a60cf8009004efc869b27da93e796c2ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af68fa50d948afb8a15aaa9f2bea1f1d0">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dumps the currently live registers to the debug output. <a href="#af68fa50d948afb8a15aaa9f2bea1f1d0">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a9032757586eb299a302e90af9bd310">addBlockLiveIns</a> (const MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds live-in registers from basic block <span class="doxyComputerOutput">MBB</span>, taking associated lane masks into consideration. <a href="#a0a9032757586eb299a302e90af9bd310">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88e5899cd5e85e1b9888746a999121ef">addPristines</a> (const MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds pristine registers. <a href="#a88e5899cd5e85e1b9888746a999121ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87e00f9a9edb9135e4ec75bcca5fd69d">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sparseset">RegisterSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9319161c15969c5a0feab80bf27100e">LiveRegs</a></td>
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

<p>A set of physical registers with utility functions to track liveness when walking backward/forward through a basic block.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#a1912d31185cc61ee9ba2fa62b5ccaf5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LivePhysRegs::const_iterator =  RegisterSet::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### RegisterSet {#a3a774f231ee87df8264c49a8d5f88a7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LivePhysRegs::RegisterSet =  SparseSet&lt;MCPhysReg, identity&lt;MCPhysReg&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LivePhysRegs() {#abbe6939e3bddd71f4a12a6528d1abb78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LivePhysRegs::LivePhysRegs ()</td>
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

<p>Constructs an unitialized set. <a href="#a8b52495cd160fff98521b57a4479f2da">init()</a> needs to be called to initialize it.</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>.</p>


<p>Referenced by <a href="#a5c680bb9900ecd38fd9cfa94c024911f">LivePhysRegs</a> and <a href="#ad0013c439ff8a7df2974b9b6930d03c8">operator=</a>.</p>

</div>
</div>

### LivePhysRegs() {#ab60ebf245879fc2c1a9299329d343081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LivePhysRegs::LivePhysRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
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

<p>Constructs and initializes an empty set.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>.</p>

</div>
</div>

### LivePhysRegs() {#a5c680bb9900ecd38fd9cfa94c024911f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LivePhysRegs::LivePhysRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/livephysregs">LivePhysRegs</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>.</p>


<p>Reference <a href="#abbe6939e3bddd71f4a12a6528d1abb78">LivePhysRegs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ad0013c439ff8a7df2974b9b6930d03c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LivePhysRegs &amp; llvm::LivePhysRegs::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/livephysregs">LivePhysRegs</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>.</p>


<p>Reference <a href="#abbe6939e3bddd71f4a12a6528d1abb78">LivePhysRegs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addLiveIns() {#a972dc07ee343dfa21fc84131ada0e688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LivePhysRegs::addLiveIns (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds all live-in registers of basic block <span class="doxyComputerOutput">MBB</span>.</p>


<p>Live in registers are the registers in the blocks live-in list and the pristine registers.</p>


<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>, definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livephysregs-cpp">LivePhysRegs.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoninstrinfo-cpp/#a94fa9128eb5d4a9b32df7efd29b9d544">getLiveInRegsAt</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a03593d957e11a83c25fbe9aeddacf19c">getLiveRegsForEntryMBB</a>.</p>

</div>
</div>

### addLiveInsNoPristines() {#aceb9a8356104b139deb7cec444f8361c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LivePhysRegs::addLiveInsNoPristines (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds all live-in registers of basic block <span class="doxyComputerOutput">MBB</span> but skips pristine registers.</p>

<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livephysregs-cpp">LivePhysRegs.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### addLiveOuts() {#abb67d4b6f48395a5aca25fc32e042928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LivePhysRegs::addLiveOuts (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds all live-out registers of basic block <span class="doxyComputerOutput">MBB</span>.</p>


<p>Live out registers are the union of the live-in registers of the successor blocks and pristine registers. Live out registers of the end block are the callee saved registers. If a register is not added by this method, it is guaranteed to not be live out from MBB, although a sub-register may be. This is true both before and after regalloc.</p>


<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>, definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livephysregs-cpp">LivePhysRegs.cpp</a>.</p>


<p>References <a href="#ab22bacf399a5964155b56e9be835a6b3">addLiveOutsNoPristines</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-bpfmipeephole-cpp-/#ab0827bed6547378efa61b05fc7958a13">anonymous{BPFMIPeephole.cpp}::collectBPFFastCalls</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoninstrinfo-cpp/#ae0cf604b1d0c6fc73db6ed16d4cc3e98">getLiveOutRegsAt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a8c086c133d633e899103bcc88ec14442">getLivePhysRegsUpTo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a20d1f65e3dcb870550c1c8340fc7a286">llvm::X86InstrInfo::replaceBranchWithTailCall</a>, <a href="/web-llvm/docs/api/classes/removeloadsintofakeuses/#a207cce78de7e84e6885684960f5c4f50">RemoveLoadsIntoFakeUses::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ac0bfa894f538166cb476b439a2cb0aea">llvm::MachineBasicBlock::splitAt</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64framelowering-cpp-/#ab1cb1e5a0ad356f946b7001f0f133cf9">anonymous{AArch64FrameLowering.cpp}::tryMergeAdjacentSTG</a>.</p>

</div>
</div>

### addLiveOutsNoPristines() {#ab22bacf399a5964155b56e9be835a6b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LivePhysRegs::addLiveOutsNoPristines (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds all live-out registers of basic block <span class="doxyComputerOutput">MBB</span> but skips pristine registers.</p>

<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livephysregs-cpp">LivePhysRegs.cpp</a>.</p>


<p>References <a href="#adbf2afbb346e40106f344191309324fc">addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aad474502cac7b22b83e74de089f8c81d">llvm::MachineFrameInfo::getCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a81504f733d0491a446a16ef1ba0a5c2a">llvm::MachineFrameInfo::isCalleeSavedInfoValid</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#abb67d4b6f48395a5aca25fc32e042928">addLiveOuts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf741b422c5f449eb83144c3c2fe9730">llvm::computeLiveIns</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa323e6c0586d706279d7e764fc18d1ba">llvm::recomputeLivenessFlags</a>.</p>

</div>
</div>

### addReg() {#adbf2afbb346e40106f344191309324fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LivePhysRegs::addReg (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> Reg)</td>
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

<p>Adds a physical register and all its sub-registers to the set.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/livephysregs-cpp/#a9934551ee94fac64bda9c5a9452a3040">addCalleeSavedRegs</a>, <a href="#ab22bacf399a5964155b56e9be835a6b3">addLiveOutsNoPristines</a>, <a href="#aa64a4c432876fe5615cab79fd5650f7a">addUses</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a03593d957e11a83c25fbe9aeddacf19c">getLiveRegsForEntryMBB</a> and <a href="#a3f06df57fdd66d54f952c1c60e5048c3">stepForward</a>.</p>

</div>
</div>

### addUses() {#aa64a4c432876fe5615cab79fd5650f7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LivePhysRegs::addUses (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add uses to the set.</p>

<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livephysregs-cpp">LivePhysRegs.cpp</a>.</p>


<p>References <a href="#adbf2afbb346e40106f344191309324fc">addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a394561d6eda5e5b3e28fb2955823cf27">llvm::phys_regs_and_masks</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa323e6c0586d706279d7e764fc18d1ba">llvm::recomputeLivenessFlags</a> and <a href="#a683d33b7b0ca1cf29e61a3dc4614a046">stepBackward</a>.</p>

</div>
</div>

### available() {#a5c249924553aa84c5927b2335c490583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LivePhysRegs::available (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if register <span class="doxyComputerOutput">Reg</span> and no aliasing register is in the set.</p>

<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livephysregs-cpp">LivePhysRegs.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a2be9d35aaace9716441da5714f048af9">llvm::AArch64FrameLowering::canUseAsPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ab2790230883e599a288a12ded77463bc">llvm::HexagonInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a8705d5d3c895b6ddc6502220cbe3a965">findScratchNonCalleeSaveRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#abb834744243c11cb677261382ac15bea">llvm::MachineInstr::isDead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa323e6c0586d706279d7e764fc18d1ba">llvm::recomputeLivenessFlags</a> and <a href="/web-llvm/docs/api/classes/removeloadsintofakeuses/#a207cce78de7e84e6885684960f5c4f50">RemoveLoadsIntoFakeUses::runOnMachineFunction</a>.</p>

</div>
</div>

### begin() {#acc2dfac325582d82eb5782973d8e3ded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::LivePhysRegs::begin ()</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>.</p>

</div>
</div>

### clear() {#a30e045ff918c93beb68e7db808287d7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LivePhysRegs::clear ()</td>
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

<p>Clears the set.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>.</p>

</div>
</div>

### contains() {#a05ce2aec67d9c398ce268ac0c33c5c7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LivePhysRegs::contains (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> Reg)</td>
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

<p>Returns true if register <span class="doxyComputerOutput">Reg</span> is contained in the set.</p>


<p>This also works if only the super register of <span class="doxyComputerOutput">Reg</span> has been defined, because <a href="#adbf2afbb346e40106f344191309324fc">addReg()</a> always adds all sub-registers to the set as well. Note: Returns false if just some sub registers are live, use <a href="#a5c249924553aa84c5927b2335c490583">available()</a> when searching a free register.</p>


<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#ada53f9e75a087c02dcea98064c69900b">CMSEPushCalleeSaves</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-bpfmipeephole-cpp-/#ab0827bed6547378efa61b05fc7958a13">anonymous{BPFMIPeephole.cpp}::collectBPFFastCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ac6fc9913b21716cfbd41b6616e8aef4d">llvm::HexagonInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64framelowering-cpp-/#ab1cb1e5a0ad356f946b7001f0f133cf9">anonymous{AArch64FrameLowering.cpp}::tryMergeAdjacentSTG</a>.</p>

</div>
</div>

### dump() {#af68fa50d948afb8a15aaa9f2bea1f1d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void LivePhysRegs::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dumps the currently live registers to the debug output.</p>

<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>, definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livephysregs-cpp">LivePhysRegs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>

</div>
</div>

### empty() {#ae9dd17c81890dfa50eceb32282809600}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LivePhysRegs::empty ()</td>
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

<p>Returns true if the set is empty.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>.</p>


<p>Referenced by <a href="#a60cf8009004efc869b27da93e796c2ec">print</a>.</p>

</div>
</div>

### end() {#a2312b1101c183ac421957b4aab3c4c68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::LivePhysRegs::end ()</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>.</p>

</div>
</div>

### init() {#a8b52495cd160fff98521b57a4479f2da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LivePhysRegs::init (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
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

<p>(re-)initializes and clears the set.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-bpfmipeephole-cpp-/#ab0827bed6547378efa61b05fc7958a13">anonymous{BPFMIPeephole.cpp}::collectBPFFastCalls</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf741b422c5f449eb83144c3c2fe9730">llvm::computeLiveIns</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/deadmachineinstructionelim-cpp/#a3f2d2aa9085b12e4b3136f6e64ea3030">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa323e6c0586d706279d7e764fc18d1ba">llvm::recomputeLivenessFlags</a>, <a href="/web-llvm/docs/api/classes/removeloadsintofakeuses/#a207cce78de7e84e6885684960f5c4f50">RemoveLoadsIntoFakeUses::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ac0bfa894f538166cb476b439a2cb0aea">llvm::MachineBasicBlock::splitAt</a>.</p>

</div>
</div>

### print() {#a60cf8009004efc869b27da93e796c2ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LivePhysRegs::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prints the currently live registers to <span class="doxyComputerOutput">OS</span>.</p>


<p>Print the currently live registers to OS.</p>


<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>, definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livephysregs-cpp">LivePhysRegs.cpp</a>.</p>


<p>References <a href="#ae9dd17c81890dfa50eceb32282809600">empty</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a25b95f61221dcd3dfda8165527c77163">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### removeDefs() {#aa9eb9ea8517269ca82f836b915fa94ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LivePhysRegs::removeDefs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove defined registers and regmask kills from the set.</p>

<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livephysregs-cpp">LivePhysRegs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a394561d6eda5e5b3e28fb2955823cf27">llvm::phys_regs_and_masks</a>, <a href="#a7b644203b542cf4091b1ff74bafe78ac">removeReg</a> and <a href="#adfee5cf71110ecb406e359e538fc3cf9">removeRegsInMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa323e6c0586d706279d7e764fc18d1ba">llvm::recomputeLivenessFlags</a> and <a href="#a683d33b7b0ca1cf29e61a3dc4614a046">stepBackward</a>.</p>

</div>
</div>

### removeReg() {#a7b644203b542cf4091b1ff74bafe78ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LivePhysRegs::removeReg (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> Reg)</td>
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

<p>Removes a physical register, all its sub-registers, and all its super-registers from the set.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="#aa9eb9ea8517269ca82f836b915fa94ca">removeDefs</a> and <a href="#a3f06df57fdd66d54f952c1c60e5048c3">stepForward</a>.</p>

</div>
</div>

### removeRegsInMask() {#adfee5cf71110ecb406e359e538fc3cf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LivePhysRegs::removeRegsInMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * &gt; &gt; * Clobbers=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Removes physical registers clobbered by the regmask operand <span class="doxyComputerOutput">MO</span>.</p>


<p>Remove all registers from the set that get clobbered by the register mask.</p>


<p>The clobbers set will be the list of live registers clobbered by the regmask.</p>


<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livephysregs-cpp">LivePhysRegs.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ae4ecf5483b94e2bb72967b80cc2008d2">llvm::MachineOperand::clobbersPhysReg</a>.</p>


<p>Referenced by <a href="#aa9eb9ea8517269ca82f836b915fa94ca">removeDefs</a> and <a href="#a3f06df57fdd66d54f952c1c60e5048c3">stepForward</a>.</p>

</div>
</div>

### stepBackward() {#a683d33b7b0ca1cf29e61a3dc4614a046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LivePhysRegs::stepBackward (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Simulates liveness when stepping backwards over an instruction(bundle).</p>


<p>Simulates liveness when stepping backwards over an instruction(bundle): Remove Defs, add uses.</p>


<p>Remove Defs, add uses. This is the recommended way of calculating liveness.</p>


<p>This is the recommended way of calculating liveness.</p>


<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livephysregs-cpp">LivePhysRegs.cpp</a>.</p>


<p>References <a href="#aa64a4c432876fe5615cab79fd5650f7a">addUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#aa9eb9ea8517269ca82f836b915fa94ca">removeDefs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-bpfmipeephole-cpp-/#ab0827bed6547378efa61b05fc7958a13">anonymous{BPFMIPeephole.cpp}::collectBPFFastCalls</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf741b422c5f449eb83144c3c2fe9730">llvm::computeLiveIns</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoninstrinfo-cpp/#ae0cf604b1d0c6fc73db6ed16d4cc3e98">getLiveOutRegsAt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a8c086c133d633e899103bcc88ec14442">getLivePhysRegsUpTo</a>, <a href="/web-llvm/docs/api/classes/removeloadsintofakeuses/#a207cce78de7e84e6885684960f5c4f50">RemoveLoadsIntoFakeUses::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ac0bfa894f538166cb476b439a2cb0aea">llvm::MachineBasicBlock::splitAt</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64framelowering-cpp-/#ab1cb1e5a0ad356f946b7001f0f133cf9">anonymous{AArch64FrameLowering.cpp}::tryMergeAdjacentSTG</a>.</p>

</div>
</div>

### stepForward() {#a3f06df57fdd66d54f952c1c60e5048c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LivePhysRegs::stepForward (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * &gt; &gt; &amp; Clobbers)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Simulates liveness when stepping forward over an instruction(bundle).</p>


<p>Simulates liveness when stepping forward over an instruction(bundle): Remove killed-uses, add defs.</p>


<p>Remove killed-uses, add defs. This is the not recommended way, because it depends on accurate kill flags. If possible use <a href="#a683d33b7b0ca1cf29e61a3dc4614a046">stepBackward()</a> instead of this function. The clobbers set will be the list of registers either defined or clobbered by a regmask. The operand will identify whether this is a regmask or register operand.</p>


<p>This is the not recommended way, because it depends on accurate kill flags. If possible use <a href="#a683d33b7b0ca1cf29e61a3dc4614a046">stepBackward()</a> instead of this function.</p>


<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livephysregs-cpp">LivePhysRegs.cpp</a>.</p>


<p>References <a href="#adbf2afbb346e40106f344191309324fc">addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ae4ecf5483b94e2bb72967b80cc2008d2">llvm::MachineOperand::clobbersPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a7b644203b542cf4091b1ff74bafe78ac">removeReg</a> and <a href="#adfee5cf71110ecb406e359e538fc3cf9">removeRegsInMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoninstrinfo-cpp/#a94fa9128eb5d4a9b32df7efd29b9d544">getLiveInRegsAt</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a20d1f65e3dcb870550c1c8340fc7a286">llvm::X86InstrInfo::replaceBranchWithTailCall</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#a9a5c05172bf1b5e36b42f412c4a176cf">UpdatePredRedefs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addBlockLiveIns() {#a0a9032757586eb299a302e90af9bd310}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LivePhysRegs::addBlockLiveIns (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds live-in registers from basic block <span class="doxyComputerOutput">MBB</span>, taking associated lane masks into consideration.</p>


<p>Add live-in registers of basic block <span class="doxyComputerOutput">MBB</span> to <span class="doxyComputerOutput">LiveRegs</span>.</p>


<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>, definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livephysregs-cpp">LivePhysRegs.cpp</a>.</p>

</div>
</div>

### addPristines() {#a88e5899cd5e85e1b9888746a999121ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LivePhysRegs::addPristines (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds pristine registers.</p>


<p>Pristine registers are callee saved registers that are unused in the function.</p>


<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>, definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livephysregs-cpp">LivePhysRegs.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LiveRegs {#af9319161c15969c5a0feab80bf27100e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterSet llvm::LivePhysRegs::LiveRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>.</p>

</div>
</div>

### TRI {#a87e00f9a9edb9135e4ec75bcca5fd69d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::LivePhysRegs::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">LivePhysRegs.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/livephysregs-cpp">LivePhysRegs.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
