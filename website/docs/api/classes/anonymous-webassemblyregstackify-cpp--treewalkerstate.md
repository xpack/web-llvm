---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-webassemblyregstackify-cpp-/treewalkerstate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TreeWalkerState` Class

<p>A stack for walking the tree of instructions being built, visiting the MachineOperands in DFS order. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{WebAssemblyRegStackify.cpp}::TreeWalkerState { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28267e9e866076ad67c43291acfee0d8">mop_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab5b1fcfd0e1eddba786fefcdf28f1689">MachineInstr::mop_iterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a663a518fc963e29a6967d67d040bbc66">mop_reverse_iterator</a> = std::reverse_iterator&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">mop_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8d0a236f9a56329d66b83dfc1090079">RangeTy</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; mop_reverse_iterator &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5077270f37bddebce043db803090ae54">TreeWalkerState</a> (MachineInstr *Insert)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89bcfa3122c175ebd7fffb45ae4bd933">done</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa145e54376cac3b0ba6aa6485da7cae2">pop</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79be7811bbf7f5945e17c62effcc9a49">pushOperands</a> (MachineInstr *Instr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Push Instr's operands onto the stack to be visited. <a href="#a79be7811bbf7f5945e17c62effcc9a49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a356eb98932f2179db61f9027ab50cce6">resetTopOperands</a> (MachineInstr *Instr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some of Instr's operands are on the top of the stack; remove them and re-insert them starting from the beginning (because we've commuted them). <a href="#a356eb98932f2179db61f9027ab50cce6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5edebfea044309a470310fb2b20128e">hasRemainingOperands</a> (const MachineInstr *Instr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether Instr has operands remaining to be visited at the top of the stack. <a href="#aa5edebfea044309a470310fb2b20128e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47b912a3657177ec72821a3697631934">isOnStack</a> (unsigned Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the given register is present on the stack, indicating an operand in the tree that we haven't visited yet. <a href="#a47b912a3657177ec72821a3697631934">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/iterator-range">RangeTy</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23265eaa53ce3268123e0089e3ab5632">Worklist</a></td>
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

<p>A stack for walking the tree of instructions being built, visiting the MachineOperands in DFS order.</p>

<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp">WebAssemblyRegStackify.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### mop\_iterator {#a28267e9e866076ad67c43291acfee0d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{WebAssemblyRegStackify.cpp}::TreeWalkerState::mop_iterator =  MachineInstr::mop_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 690 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp">WebAssemblyRegStackify.cpp</a>.</p>

</div>
</div>

### mop\_reverse\_iterator {#a663a518fc963e29a6967d67d040bbc66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{WebAssemblyRegStackify.cpp}::TreeWalkerState::mop_reverse_iterator =  std::reverse_iterator&lt;mop_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 691 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp">WebAssemblyRegStackify.cpp</a>.</p>

</div>
</div>

### RangeTy {#ae8d0a236f9a56329d66b83dfc1090079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{WebAssemblyRegStackify.cpp}::TreeWalkerState::RangeTy =  iterator_range&lt;mop_reverse_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 692 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp">WebAssemblyRegStackify.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### TreeWalkerState() {#a5077270f37bddebce043db803090ae54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{WebAssemblyRegStackify.cpp}::TreeWalkerState::TreeWalkerState (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * Insert)</td>
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



<p>Definition at line 696 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp">WebAssemblyRegStackify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### done() {#a89bcfa3122c175ebd7fffb45ae4bd933}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{WebAssemblyRegStackify.cpp}::TreeWalkerState::done ()</td>
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



<p>Definition at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp">WebAssemblyRegStackify.cpp</a>.</p>

</div>
</div>

### hasRemainingOperands() {#aa5edebfea044309a470310fb2b20128e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{WebAssemblyRegStackify.cpp}::TreeWalkerState::hasRemainingOperands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * Instr)</td>
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

<p>Test whether Instr has operands remaining to be visited at the top of the stack.</p>

<p>Definition at line 733 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp">WebAssemblyRegStackify.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregstackify-cpp-/commutingstate/#a4ea15ac34bc701369f48c52d1c9a3adf">anonymous{WebAssemblyRegStackify.cpp}::CommutingState::maybeCommute</a> and <a href="#a356eb98932f2179db61f9027ab50cce6">resetTopOperands</a>.</p>

</div>
</div>

### isOnStack() {#a47b912a3657177ec72821a3697631934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{WebAssemblyRegStackify.cpp}::TreeWalkerState::isOnStack (unsigned Reg)</td>
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

<p>Test whether the given register is present on the stack, indicating an operand in the tree that we haven't visited yet.</p>


<p>Moving a definition of Reg to a point in the tree after that would change its value.</p>


<p>This is needed as a consequence of using implicit local.gets for uses and implicit local.sets for defs.</p>


<p>Definition at line 746 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp">WebAssemblyRegStackify.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>

</div>
</div>

### pop() {#aa145e54376cac3b0ba6aa6485da7cae2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand &amp; anonymous{WebAssemblyRegStackify.cpp}::TreeWalkerState::pop ()</td>
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



<p>Definition at line 704 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp">WebAssemblyRegStackify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>

</div>
</div>

### pushOperands() {#a79be7811bbf7f5945e17c62effcc9a49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{WebAssemblyRegStackify.cpp}::TreeWalkerState::pushOperands (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * Instr)</td>
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

<p>Push Instr's operands onto the stack to be visited.</p>

<p>Definition at line 716 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp">WebAssemblyRegStackify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>

</div>
</div>

### resetTopOperands() {#a356eb98932f2179db61f9027ab50cce6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{WebAssemblyRegStackify.cpp}::TreeWalkerState::resetTopOperands (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * Instr)</td>
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

<p>Some of Instr's operands are on the top of the stack; remove them and re-insert them starting from the beginning (because we've commuted them).</p>

<p>Definition at line 724 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp">WebAssemblyRegStackify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa5edebfea044309a470310fb2b20128e">hasRemainingOperands</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregstackify-cpp-/commutingstate/#a4ea15ac34bc701369f48c52d1c9a3adf">anonymous{WebAssemblyRegStackify.cpp}::CommutingState::maybeCommute</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Worklist {#a23265eaa53ce3268123e0089e3ab5632}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;RangeTy, 4&gt; anonymous{WebAssemblyRegStackify.cpp}::TreeWalkerState::Worklist</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 693 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp">WebAssemblyRegStackify.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp">WebAssemblyRegStackify.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
