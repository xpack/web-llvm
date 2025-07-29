---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/combiner/worklistmaintainer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `WorkListMaintainer` Class

<p>This class acts as the glue that joins the <a href="/web-llvm/docs/api/classes/llvm/combinerhelper">CombinerHelper</a> to the overall Combine algorithm. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class Combiner::WorkListMaintainer { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract class that contains various methods for clients to notify about changes. <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/combiner/worklistmaintainerimpl">WorkListMaintainerImpl&lt;Lvl&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A configurable <a href="/web-llvm/docs/api/classes/combiner/worklistmaintainer">WorkListMaintainer</a> implementation. <a href="/web-llvm/docs/api/classes/combiner/worklistmaintainerimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefb1805bbc53689bd74b3aaba33713ab">Level</a> = <a href="/web-llvm/docs/api/structs/llvm/combinerinfo/#af06305b83dbec881b832db7259d81257">CombinerInfo::ObserverLevel</a></td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5882d3d2a1f92de84900dd744e9d96f3">~WorkListMaintainer</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68f2f30d93695bab78ad878ef084fc03">reportFullyCreatedInstrs</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d9e6c5aaa9e9f100263c1307982afec">reset</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a746b6b04dc89f657479f03bd1c0ed48f">appliedCombine</a> ()=0</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac744210ae14ee41a9d85da218f3f4039">CreatedInstrs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instructions that have been created but we want to report once they have their operands. <a href="#ac744210ae14ee41a9d85da218f3f4039">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/combiner/worklistmaintainer">WorkListMaintainer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc346d3a92bf74c9516501088f9506c8">create</a> (Level Lvl, WorkListTy &amp;WorkList, MachineRegisterInfo &amp;MRI)</td>
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

<p>This class acts as the glue that joins the <a href="/web-llvm/docs/api/classes/llvm/combinerhelper">CombinerHelper</a> to the overall Combine algorithm.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/combinerhelper">CombinerHelper</a> is intended to report the modifications it makes to the MIR to the <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a> and the observer subclass will act on these events.</p>


<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combiner-cpp">Combiner.cpp</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### Level {#aefb1805bbc53689bd74b3aaba33713ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Combiner::WorkListMaintainer::Level =  CombinerInfo::ObserverLevel</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combiner-cpp">Combiner.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~WorkListMaintainer() {#a5882d3d2a1f92de84900dd744e9d96f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::Combiner::WorkListMaintainer::~WorkListMaintainer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combiner-cpp">Combiner.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### appliedCombine() {#a746b6b04dc89f657479f03bd1c0ed48f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::Combiner::WorkListMaintainer::appliedCombine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combiner-cpp">Combiner.cpp</a>.</p>

</div>
</div>

### reportFullyCreatedInstrs() {#a68f2f30d93695bab78ad878ef084fc03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Combiner::WorkListMaintainer::reportFullyCreatedInstrs ()</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combiner-cpp">Combiner.cpp</a>.</p>


<p>References <a href="#ac744210ae14ee41a9d85da218f3f4039">llvm::Combiner::WorkListMaintainer::CreatedInstrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### reset() {#a8d9e6c5aaa9e9f100263c1307982afec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::Combiner::WorkListMaintainer::reset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combiner-cpp">Combiner.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CreatedInstrs {#ac744210ae14ee41a9d85da218f3f4039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetVector&lt;const MachineInstr *, 32&gt; llvm::Combiner::WorkListMaintainer::CreatedInstrs</td>
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

<p>The instructions that have been created but we want to report once they have their operands.</p>


<p>This is only maintained if debug output is requested.</p>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combiner-cpp">Combiner.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/combiner/worklistmaintainerimpl/#ae67875ea42c44e3773f2d7f7611b548b">llvm::Combiner::WorkListMaintainerImpl&lt; Lvl &gt;::createdInstr</a>, <a href="/web-llvm/docs/api/classes/combiner/worklistmaintainerimpl/#a535384a514e7d0c141d1be3d39055d95">llvm::Combiner::WorkListMaintainerImpl&lt; Lvl &gt;::erasingInstr</a> and <a href="#a68f2f30d93695bab78ad878ef084fc03">llvm::Combiner::WorkListMaintainer::reportFullyCreatedInstrs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#adc346d3a92bf74c9516501088f9506c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; Combiner::WorkListMaintainer &gt; llvm::Combiner::WorkListMaintainer::create (<a href="/web-llvm/docs/api/structs/llvm/combinerinfo/#af06305b83dbec881b832db7259d81257">Level</a> Lvl, <a href="/web-llvm/docs/api/classes/llvm/giselworklist">WorkListTy</a> &amp; WorkList, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combiner-cpp">Combiner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/combiner/#a7a958b8bb74d0caea2ede8d80ecf8753">llvm::Combiner::MRI</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combiner-cpp">Combiner.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
