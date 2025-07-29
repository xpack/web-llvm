---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-peepholeoptimizer-cpp-/valuetracker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ValueTracker` Class

<p>Helper class to track the possible sources of a value defined by a (chain of) copy related instructions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{PeepholeOptimizer.cpp}::ValueTracker { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b6a1a42542bec9018068ce22e56f1eb">ValueTracker</a> (Register Reg, unsigned DefSubReg, const MachineRegisterInfo &amp;MRI, const TargetInstrInfo *TII=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/valuetracker">ValueTracker</a> instance for the value defined by <span class="doxyComputerOutput">Reg</span>. <a href="#a2b6a1a42542bec9018068ce22e56f1eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/valuetrackerresult">ValueTrackerResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71b7cfbae828b6dc34596c7019ab029f">getNextSource</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Following the use-def chain, get the next available source for the tracked value. <a href="#a71b7cfbae828b6dc34596c7019ab029f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/valuetrackerresult">ValueTrackerResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7707f1a359a5e0bb01b4fbbe2e30c5fa">getNextSourceImpl</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispatcher to the right underlying implementation of getNextSource. <a href="#a7707f1a359a5e0bb01b4fbbe2e30c5fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/valuetrackerresult">ValueTrackerResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8bb902ce1f23343cb503505a9607e60">getNextSourceFromCopy</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialized version of getNextSource for Copy instructions. <a href="#aa8bb902ce1f23343cb503505a9607e60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/valuetrackerresult">ValueTrackerResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeee4bcd237f8d97071714317b6bcbf34">getNextSourceFromBitcast</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialized version of getNextSource for Bitcast instructions. <a href="#aeee4bcd237f8d97071714317b6bcbf34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/valuetrackerresult">ValueTrackerResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c75ae2b47fa1bb13ec6b43006ba9652">getNextSourceFromRegSequence</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialized version of getNextSource for RegSequence instructions. <a href="#a8c75ae2b47fa1bb13ec6b43006ba9652">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/valuetrackerresult">ValueTrackerResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a706ad0761ae5f9af29e9eb065f82ced5">getNextSourceFromInsertSubreg</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialized version of getNextSource for InsertSubreg instructions. <a href="#a706ad0761ae5f9af29e9eb065f82ced5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/valuetrackerresult">ValueTrackerResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20b816ba163c06d2ff095300170a4fe4">getNextSourceFromExtractSubreg</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialized version of getNextSource for ExtractSubreg instructions. <a href="#a20b816ba163c06d2ff095300170a4fe4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/valuetrackerresult">ValueTrackerResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae79e90e9fef87cda3e4105442c39b141">getNextSourceFromSubregToReg</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialized version of getNextSource for SubregToReg instructions. <a href="#ae79e90e9fef87cda3e4105442c39b141">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/valuetrackerresult">ValueTrackerResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaee57a86cc392b89d8d504333b00edd6">getNextSourceFromPHI</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialized version of getNextSource for PHI instructions. <a href="#aaee57a86cc392b89d8d504333b00edd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b62585fe0ffd72b63a6a8603247c6c5">Def</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current point into the use-def chain. <a href="#a4b62585fe0ffd72b63a6a8603247c6c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f20281ecd070dd95a2846006ed63773">DefIdx</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The index of the definition in Def. <a href="#a0f20281ecd070dd95a2846006ed63773">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e9953ce80361b9f9575a586c3aea0b5">DefSubReg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The sub register index of the definition. <a href="#a1e9953ce80361b9f9575a586c3aea0b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af79ccbf65f7656fdee8d7994956a9f7a">Reg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The register where the value can be found. <a href="#af79ccbf65f7656fdee8d7994956a9f7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a452edf2a2696bd774021d366abeb5301">MRI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> used to perform tracking. <a href="#a452edf2a2696bd774021d366abeb5301">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a393f8c961feb234320d3dcf4e1ffae58">TII</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optional <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> used to perform some complex tracking. <a href="#a393f8c961feb234320d3dcf4e1ffae58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Helper class to track the possible sources of a value defined by a (chain of) copy related instructions.</p>


<p>Given a definition (instruction and definition index), this class follows the use-def chain to find successive suitable sources. The given source can be used to rewrite the definition into def = COPY src.</p>


<p>For instance, let us consider the following snippet: v0 = v2 = INSERT_SUBREG v1, v0, sub0 def = COPY v2.sub0</p>


<p>Using a <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/valuetracker">ValueTracker</a> for def = COPY v2.sub0 will give the following suitable sources: v2.sub0 and v0. Then, def can be rewritten into def = COPY v0.</p>


<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ValueTracker() {#a2b6a1a42542bec9018068ce22e56f1eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PeepholeOptimizer.cpp}::ValueTracker::ValueTracker (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, unsigned DefSubReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII=nullptr)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/valuetracker">ValueTracker</a> instance for the value defined by <span class="doxyComputerOutput">Reg</span>.</p>


<p><span class="doxyComputerOutput">DefSubReg</span> represents the sub register index the value tracker will track. It does not need to match the sub register index used in the definition of <span class="doxyComputerOutput">Reg</span>. If <span class="doxyComputerOutput">Reg</span> is a physical register, a value tracker constructed with this constructor will not find any alternative source. Indeed, when <span class="doxyComputerOutput">Reg</span> is a physical register that constructor does not know which definition of <span class="doxyComputerOutput">Reg</span> it should track. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the next constructor to track a physical register.</p>


<p>Definition at line 757 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getNextSource() {#a71b7cfbae828b6dc34596c7019ab029f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueTrackerResult ValueTracker::getNextSource ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Following the use-def chain, get the next available source for the tracked value.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/valuetrackerresult">ValueTrackerResult</a> containing a set of registers and sub registers with tracked values. A <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/valuetrackerresult">ValueTrackerResult</a> with an empty set of registers means no source was found.</p></dd>
</dl>


<p>Definition at line 771 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/valuetrackerresult/#a78616c6644f161437bedf8a8f1e7b640">anonymous{PeepholeOptimizer.cpp}::ValueTrackerResult::getNumSources</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/defusechain-iterator/#a58a1c3f21a96544fc062f9ec00ef808b">llvm::MachineRegisterInfo::defusechain_iterator&lt; ReturnUses, ReturnDefs, SkipDebug, ByOperand, ByInstr, ByBundle &gt;::getOperandNo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/valuetrackerresult/#a16bfe7efc8bd9e6edc7b71e1467adb0a">anonymous{PeepholeOptimizer.cpp}::ValueTrackerResult::getSrcReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/valuetrackerresult/#a039609763362c9e61ca9555f62bc0d6a">anonymous{PeepholeOptimizer.cpp}::ValueTrackerResult::getSrcSubReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/valuetrackerresult/#aebbbd9a3d61ede17954bbf25692a6b1b">anonymous{PeepholeOptimizer.cpp}::ValueTrackerResult::isValid</a> and <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/valuetrackerresult/#a466048350995ee1cbc70c2ec4a1f2df3">anonymous{PeepholeOptimizer.cpp}::ValueTrackerResult::setInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getNextSourceFromBitcast() {#aeee4bcd237f8d97071714317b6bcbf34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueTrackerResult ValueTracker::getNextSourceFromBitcast ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Specialized version of getNextSource for Bitcast instructions.</p>

<p>Definition at line 730 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>

</div>
</div>

### getNextSourceFromCopy() {#aa8bb902ce1f23343cb503505a9607e60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueTrackerResult ValueTracker::getNextSourceFromCopy ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Specialized version of getNextSource for Copy instructions.</p>

<p>Definition at line 727 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>

</div>
</div>

### getNextSourceFromExtractSubreg() {#a20b816ba163c06d2ff095300170a4fe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueTrackerResult ValueTracker::getNextSourceFromExtractSubreg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Specialized version of getNextSource for ExtractSubreg instructions.</p>

<p>Definition at line 739 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>

</div>
</div>

### getNextSourceFromInsertSubreg() {#a706ad0761ae5f9af29e9eb065f82ced5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueTrackerResult ValueTracker::getNextSourceFromInsertSubreg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Specialized version of getNextSource for InsertSubreg instructions.</p>

<p>Definition at line 736 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>

</div>
</div>

### getNextSourceFromPHI() {#aaee57a86cc392b89d8d504333b00edd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueTrackerResult ValueTracker::getNextSourceFromPHI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Specialized version of getNextSource for PHI instructions.</p>


<p>Explore each PHI incoming operand and return its sources.</p>


<p>Definition at line 745 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>

</div>
</div>

### getNextSourceFromRegSequence() {#a8c75ae2b47fa1bb13ec6b43006ba9652}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueTrackerResult ValueTracker::getNextSourceFromRegSequence ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Specialized version of getNextSource for RegSequence instructions.</p>

<p>Definition at line 733 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>

</div>
</div>

### getNextSourceFromSubregToReg() {#ae79e90e9fef87cda3e4105442c39b141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueTrackerResult ValueTracker::getNextSourceFromSubregToReg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Specialized version of getNextSource for SubregToReg instructions.</p>

<p>Definition at line 742 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>

</div>
</div>

### getNextSourceImpl() {#a7707f1a359a5e0bb01b4fbbe2e30c5fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueTrackerResult ValueTracker::getNextSourceImpl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dispatcher to the right underlying implementation of getNextSource.</p>

<p>Definition at line 724 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Def {#a4b62585fe0ffd72b63a6a8603247c6c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr* anonymous{PeepholeOptimizer.cpp}::ValueTracker::Def = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The current point into the use-def chain.</p>

<p>Definition at line 706 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>

</div>
</div>

### DefIdx {#a0f20281ecd070dd95a2846006ed63773}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PeepholeOptimizer.cpp}::ValueTracker::DefIdx = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The index of the definition in Def.</p>

<p>Definition at line 709 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>

</div>
</div>

### DefSubReg {#a1e9953ce80361b9f9575a586c3aea0b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PeepholeOptimizer.cpp}::ValueTracker::DefSubReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The sub register index of the definition.</p>

<p>Definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>

</div>
</div>

### MRI {#a452edf2a2696bd774021d366abeb5301}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineRegisterInfo&amp; anonymous{PeepholeOptimizer.cpp}::ValueTracker::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> used to perform tracking.</p>

<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>

</div>
</div>

### Reg {#af79ccbf65f7656fdee8d7994956a9f7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register anonymous{PeepholeOptimizer.cpp}::ValueTracker::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The register where the value can be found.</p>

<p>Definition at line 715 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>

</div>
</div>

### TII {#a393f8c961feb234320d3dcf4e1ffae58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* anonymous{PeepholeOptimizer.cpp}::ValueTracker::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optional <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> used to perform some complex tracking.</p>

<p>Definition at line 721 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
