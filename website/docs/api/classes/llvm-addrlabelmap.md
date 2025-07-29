---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/addrlabelmap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AddrLabelMap` Class



## Declaration

<div class="doxyDeclaration">
class llvm::AddrLabelMap { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e7125dc36f3bc3ffed2a7cf9eede088">AddrLabelMap</a> (MCContext &amp;context)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f18a638fb304c1641b88b56d0481c2e">~AddrLabelMap</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbb53aac904b80dad6df38f882e319f3">getAddrLabelSymbolToEmit</a> (BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0c9d3065597e04b863b7b0d659aef8f">takeDeletedSymbolsForFunction</a> (Function *F, std::vector&lt; MCSymbol * &gt; &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If we have any deleted symbols for F, return them. <a href="#ab0c9d3065597e04b863b7b0d659aef8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba3d880d5b4c6f123a2c50923e78c46a">UpdateForDeletedBlock</a> (BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92dddb4b181a5d60d12b88f7bfe994e0">UpdateForRAUWBlock</a> (BasicBlock *Old, BasicBlock *New)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af76528fc67fa1207ce1502b668e3b457">Context</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt;, AddrLabelSymEntry &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c5829419f50df80069b3033d942224b">AddrLabelSymbols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; AddrLabelMapCallbackPtr &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6726097447f29f9c780cd2781a08ecf7">BBCallbacks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callbacks for the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>'s that we have entries for. <a href="#a6726097447f29f9c780cd2781a08ecf7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &gt;, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5569c64e0b01ae64bf4328610c56ccd4">DeletedAddrLabelsNeedingEmission</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a per-function list of symbols whose corresponding <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> got deleted. <a href="#a5569c64e0b01ae64bf4328610c56ccd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp">AsmPrinter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AddrLabelMap() {#a8e7125dc36f3bc3ffed2a7cf9eede088}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AddrLabelMap::AddrLabelMap (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; context)</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp">AsmPrinter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AddrLabelMap() {#a8f18a638fb304c1641b88b56d0481c2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AddrLabelMap::~AddrLabelMap ()</td>
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



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp">AsmPrinter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAddrLabelSymbolToEmit() {#acbb53aac904b80dad6df38f882e319f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MCSymbol * &gt; AddrLabelMap::getAddrLabelSymbolToEmit (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp">AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a315f26c899f5ea8a780db4740ba95ef4">llvm::BasicBlock::hasAddressTaken</a>.</p>

</div>
</div>

### takeDeletedSymbolsForFunction() {#ab0c9d3065597e04b863b7b0d659aef8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AddrLabelMap::takeDeletedSymbolsForFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt; &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If we have any deleted symbols for F, return them.</p>

<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp">AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### UpdateForDeletedBlock() {#aba3d880d5b4c6f123a2c50923e78c46a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AddrLabelMap::UpdateForDeletedBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp">AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a2899e74730516967f04d81966bb4f881">llvm::MCSymbol::isDefined</a>.</p>

</div>
</div>

### UpdateForRAUWBlock() {#a92dddb4b181a5d60d12b88f7bfe994e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AddrLabelMap::UpdateForRAUWBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Old, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * New)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp">AsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AddrLabelSymbols {#a7c5829419f50df80069b3033d942224b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;AssertingVH&lt;BasicBlock&gt;, AddrLabelSymEntry&gt; llvm::AddrLabelMap::AddrLabelSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp">AsmPrinter.cpp</a>.</p>

</div>
</div>

### BBCallbacks {#a6726097447f29f9c780cd2781a08ecf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;AddrLabelMapCallbackPtr&gt; llvm::AddrLabelMap::BBCallbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callbacks for the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>'s that we have entries for.</p>


<p>We use this so we get notified if a block is deleted or RAUWd.</p>


<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp">AsmPrinter.cpp</a>.</p>

</div>
</div>

### Context {#af76528fc67fa1207ce1502b668e3b457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext&amp; llvm::AddrLabelMap::Context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp">AsmPrinter.cpp</a>.</p>

</div>
</div>

### DeletedAddrLabelsNeedingEmission {#a5569c64e0b01ae64bf4328610c56ccd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;AssertingVH&lt;Function&gt;, std::vector&lt;MCSymbol *&gt; &gt; llvm::AddrLabelMap::DeletedAddrLabelsNeedingEmission</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is a per-function list of symbols whose corresponding <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> got deleted.</p>


<p>These symbols need to be emitted at some point in the file, so <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> emits them after the function body.</p>


<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp">AsmPrinter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp">AsmPrinter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
