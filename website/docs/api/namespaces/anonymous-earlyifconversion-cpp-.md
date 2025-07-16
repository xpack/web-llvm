---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-earlyifconversion-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{EarlyIfConversion.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{EarlyIfConversion.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/ssaifconv">SSAIfConv</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/earlyifconverter">EarlyIfConverter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/earlyifconverterlegacy">EarlyIfConverterLegacy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-earlyifconversion-cpp-/cycles">Cycles</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class to simplify emission of cycle counts into optimization remarks. <a href="/web-llvm/docs/api/structs/anonymous-earlyifconversion-cpp-/cycles/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/earlyifpredicator">EarlyIfPredicator</a></td>
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

## Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Remark&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Remark &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#affc165838cd53f7b0efd216a3026d1f5">operator&lt;&lt;</a> (Remark &amp;R, Cycles C)</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35766d8bc1206e4e88ebb72f397c0296">updateDomTree</a> (MachineDominatorTree *DomTree, const SSAIfConv &amp;IfConv, ArrayRef&lt; MachineBasicBlock * &gt; Removed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the dominator tree after if-conversion erased some blocks. <a href="#a35766d8bc1206e4e88ebb72f397c0296">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0832c20aba1c911bff1ec3780124fc7">updateLoops</a> (MachineLoopInfo *Loops, ArrayRef&lt; MachineBasicBlock * &gt; Removed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> after if-conversion. <a href="#ad0832c20aba1c911bff1ec3780124fc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Operators

### operator&lt;&lt;() {#affc165838cd53f7b0efd216a3026d1f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Remark&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Remark &amp; anonymous{EarlyIfConversion.cpp}::operator&lt;&lt; (Remark &amp; R, <a href="/web-llvm/docs/api/structs/anonymous-earlyifconversion-cpp-/cycles">Cycles</a> C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 873 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a91921ada405fd6ba65dff028df047cb6">llvm::Remark</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### updateDomTree() {#a35766d8bc1206e4e88ebb72f397c0296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{EarlyIfConversion.cpp}::updateDomTree (<a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * DomTree, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/ssaifconv">SSAIfConv</a> &amp; IfConv, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; Removed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the dominator tree after if-conversion erased some blocks.</p>

<p>Definition at line 823 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a2881c226e1c102190d54c3b664330aba">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::changeImmediateDominator</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#aa6ae6629458ff4ccac821618d1677af4">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::eraseNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#ad8295b9b507d1d847cd46856f8255eab">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::getNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/ssaifconv/#ad6bc8960aa2f6e095e5c0e5f94e5346f">anonymous{EarlyIfConversion.cpp}::SSAIfConv::Head</a> and <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/ssaifconv/#a4dd1e49b0b30ae3bb5c38830b7746c2d">anonymous{EarlyIfConversion.cpp}::SSAIfConv::Tail</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/earlyifpredicator/#a3ccfd6df3c9118dc2506cbc3833f4036">anonymous{EarlyIfConversion.cpp}::EarlyIfPredicator::tryConvertIf</a>.</p>

</div>
</div>

### updateLoops() {#ad0832c20aba1c911bff1ec3780124fc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{EarlyIfConversion.cpp}::updateLoops (<a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> * Loops, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; Removed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> after if-conversion.</p>

<p>Definition at line 841 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp/#ada7c1594a393ede3ce32602d64d7ddb2">Loops</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/earlyifpredicator/#a3ccfd6df3c9118dc2506cbc3833f4036">anonymous{EarlyIfConversion.cpp}::EarlyIfPredicator::tryConvertIf</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
