---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-hexagonvectorloopcarriedreuse-cpp-/hexagonvectorloopcarriedreuse
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HexagonVectorLoopCarriedReuse` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{HexagonVectorLoopCarriedReuse.cpp}::HexagonVectorLoopCarriedReuse { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ba607242f7d65239dced4700893c89e">HexagonVectorLoopCarriedReuse</a> (Loop *L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a331a8ed7a56e66f44815eabac5d19b">run</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e6a8683f4b91718204b1352446c58bd">doVLCR</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c0a7f743e69af844c4b58e71242ca87">findLoopCarriedDeps</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7a2e328465ef58c1cc16ee387e43209">findValueToReuse</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad982d3b68391733d935634774679f3db">findDepChainFromPHI</a> (Instruction *I, DepChain &amp;D)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecfbe55a6f989ccd9ad1a0a984e864c6">reuseValue</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3027f587425b9f3788036bceec0185f">findValueInBlock</a> (Value *Op, BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorloopcarriedreuse-cpp-/depchain">DepChain</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55e1fc5bba0d1cd3b5086020ada785c7">getDepChainBtwn</a> (Instruction *I1, Instruction *I2, int Iters)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf6f5e179179a3b6c2c2c6d13355eb59">isEquivalentOperation</a> (Instruction *I1, Instruction *I2)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaba841412c73466ff0327e70a52c6d76">canReplace</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a5f41b5b837b166344d5f2532a61549">isCallInstCommutative</a> (CallInst *C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorloopcarriedreuse-cpp-/depchain">DepChain</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6c185e6c74c0ed17f35ac61512cd92e">Dependences</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::set&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47fced8da51a2417f84296c0afacb966">ReplacedInsts</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67dd0e77bbaa7325d220a6f57d274e25">CurLoop</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-hexagonvectorloopcarriedreuse-cpp-/reusevalue">ReuseValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a0e6adeb0056b1f15f0ed58ca563ca3">ReuseCandidate</a></td>
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


<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HexagonVectorLoopCarriedReuse() {#a4ba607242f7d65239dced4700893c89e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HexagonVectorLoopCarriedReuse.cpp}::HexagonVectorLoopCarriedReuse::HexagonVectorLoopCarriedReuse (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonvectorloopcarriedreusepass/#a32948988705da5dd73dba608197477fc">llvm::HexagonVectorLoopCarriedReusePass::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a4a331a8ed7a56e66f44815eabac5d19b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonVectorLoopCarriedReuse::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorloopcarriedreuse-cpp-/hexagonvectorloopcarriedreuselegacypass/#aec85f9491314d7359909685dbc00fc3c">anonymous{HexagonVectorLoopCarriedReuse.cpp}::HexagonVectorLoopCarriedReuseLegacyPass::runOnLoop</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### canReplace() {#aaba841412c73466ff0327e70a52c6d76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonVectorLoopCarriedReuse::canReplace (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>

</div>
</div>

### doVLCR() {#a5e6a8683f4b91718204b1352446c58bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonVectorLoopCarriedReuse::doVLCR ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>

</div>
</div>

### findDepChainFromPHI() {#ad982d3b68391733d935634774679f3db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonVectorLoopCarriedReuse::findDepChainFromPHI (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorloopcarriedreuse-cpp-/depchain">DepChain</a> &amp; D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>

</div>
</div>

### findLoopCarriedDeps() {#a3c0a7f743e69af844c4b58e71242ca87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonVectorLoopCarriedReuse::findLoopCarriedDeps ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>

</div>
</div>

### findValueInBlock() {#af3027f587425b9f3788036bceec0185f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * HexagonVectorLoopCarriedReuse::findValueInBlock (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>

</div>
</div>

### findValueToReuse() {#ad7a2e328465ef58c1cc16ee387e43209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonVectorLoopCarriedReuse::findValueToReuse ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>

</div>
</div>

### getDepChainBtwn() {#a55e1fc5bba0d1cd3b5086020ada785c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DepChain * HexagonVectorLoopCarriedReuse::getDepChainBtwn (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I1, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I2, int Iters)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>

</div>
</div>

### isCallInstCommutative() {#a8a5f41b5b837b166344d5f2532a61549}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonVectorLoopCarriedReuse::isCallInstCommutative (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>

</div>
</div>

### isEquivalentOperation() {#aaf6f5e179179a3b6c2c2c6d13355eb59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonVectorLoopCarriedReuse::isEquivalentOperation (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I1, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>

</div>
</div>

### reuseValue() {#aecfbe55a6f989ccd9ad1a0a984e864c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonVectorLoopCarriedReuse::reuseValue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurLoop {#a67dd0e77bbaa7325d220a6f57d274e25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* anonymous{HexagonVectorLoopCarriedReuse.cpp}::HexagonVectorLoopCarriedReuse::CurLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>

</div>
</div>

### Dependences {#af6c185e6c74c0ed17f35ac61512cd92e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetVector&lt;DepChain *&gt; anonymous{HexagonVectorLoopCarriedReuse.cpp}::HexagonVectorLoopCarriedReuse::Dependences</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>

</div>
</div>

### ReplacedInsts {#a47fced8da51a2417f84296c0afacb966}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt;Instruction *&gt; anonymous{HexagonVectorLoopCarriedReuse.cpp}::HexagonVectorLoopCarriedReuse::ReplacedInsts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>

</div>
</div>

### ReuseCandidate {#a2a0e6adeb0056b1f15f0ed58ca563ca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReuseValue anonymous{HexagonVectorLoopCarriedReuse.cpp}::HexagonVectorLoopCarriedReuse::ReuseCandidate</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
