---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-hexagonvectorloopcarriedreuse-cpp-/hexagonvectorloopcarriedreuselegacypass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HexagonVectorLoopCarriedReuseLegacyPass` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{HexagonVectorLoopCarriedReuse.cpp}::HexagonVectorLoopCarriedReuseLegacyPass { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/looppass">LoopPass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a353d40914ce6d9eb4da9ed6523f5671c">HexagonVectorLoopCarriedReuseLegacyPass</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0660fa7dee6876d754254e11289c8b6">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#ae0660fa7dee6876d754254e11289c8b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa01e8caee7e8d84bd3a0311252cbfba">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#aaa01e8caee7e8d84bd3a0311252cbfba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec85f9491314d7359909685dbc00fc3c">runOnLoop</a> (Loop *L, LPPassManager &amp;LPM) override</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2ffffeb82a99b6b9369d299f7c5b65b">ID</a> = 0</td>
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


<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HexagonVectorLoopCarriedReuseLegacyPass() {#a353d40914ce6d9eb4da9ed6523f5671c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HexagonVectorLoopCarriedReuse.cpp}::HexagonVectorLoopCarriedReuseLegacyPass::HexagonVectorLoopCarriedReuseLegacyPass ()</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#af2ffffeb82a99b6b9369d299f7c5b65b">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19ca59b4085f443d7cb8947c9bd3c25d">llvm::initializeHexagonVectorLoopCarriedReuseLegacyPassPass</a> and <a href="/web-llvm/docs/api/classes/llvm/looppass/#a4d5799624e630ba03cb9133168951e8a">llvm::LoopPass::LoopPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad76879187c6592ad72140c1f7de9b3e6">llvm::createHexagonVectorLoopCarriedReuseLegacyPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#aaa01e8caee7e8d84bd3a0311252cbfba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{HexagonVectorLoopCarriedReuse.cpp}::HexagonVectorLoopCarriedReuseLegacyPass::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#a573df5c9c3024ebb646e15cc7450bf91">llvm::AnalysisUsage::addPreservedID</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#a053677ebc731b47a534f841b11b5cf0c">llvm::AnalysisUsage::addRequiredID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e3d3c6d4e33a4f5ca579ee7939f0349">llvm::LCSSAID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a472515fc67a5fb572afeb00aa2609cca">llvm::LoopSimplifyID</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af11a6ebf7ab3c388234cb6d5378439a3">llvm::AnalysisUsage::setPreservesCFG</a>.</p>

</div>
</div>

### getPassName() {#ae0660fa7dee6876d754254e11289c8b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{HexagonVectorLoopCarriedReuse.cpp}::HexagonVectorLoopCarriedReuseLegacyPass::getPassName ()</td>
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

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>

</div>
</div>

### runOnLoop() {#aec85f9491314d7359909685dbc00fc3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonVectorLoopCarriedReuseLegacyPass::runOnLoop (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager">LPPassManager</a> &amp; LPM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorloopcarriedreuse-cpp-/hexagonvectorloopcarriedreuse/#a4a331a8ed7a56e66f44815eabac5d19b">anonymous{HexagonVectorLoopCarriedReuse.cpp}::HexagonVectorLoopCarriedReuse::run</a> and <a href="/web-llvm/docs/api/classes/llvm/looppass/#ac97db8f0e4f4a0946dddf617f45f6c8b">llvm::LoopPass::skipLoop</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#af2ffffeb82a99b6b9369d299f7c5b65b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char HexagonVectorLoopCarriedReuseLegacyPass::ID = 0</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>


<p>Referenced by <a href="#a353d40914ce6d9eb4da9ed6523f5671c">HexagonVectorLoopCarriedReuseLegacyPass</a>.</p>

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
