---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiffdisplaygraph
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DotCfgDiffDisplayGraph` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a951af86817df7ddb54544b04774309a5">NodeIterator</a> = std::vector&lt; <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displaynode">DisplayNode</a> * &gt;<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">::const_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac63a4cbbc86e0e7621fc3b71be19f113">DotCfgDiffDisplayGraph</a> (std::string Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af15f59a940b7e5ce205f671241664985">generateDotFile</a> (StringRef DotFile)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a951af86817df7ddb54544b04774309a5">NodeIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4521346fcf0b7fdbbc7948d0001ad405">nodes_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a951af86817df7ddb54544b04774309a5">NodeIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a706f27d5a35850b439b49ba10bfb70">nodes_end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59db9f0a5bbc2cf0d4187f5f50d97b7f">setEntryNode</a> (unsigned N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73186cee4a2fd91636bb4754c3373858">createNode</a> (std::string C, StringRef Colour)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displaynode">DisplayNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae785e172383d1db142d127c139969e9">getNode</a> (unsigned N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaf851c060a371c31fa65c28be067521">size</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c37eea28073ea41cc0a4ea9bed76c75">getGraphName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a455e6c94d4a8a9611992d58c8ec8ad29">getNodeLabel</a> (const DisplayNode &amp;Node) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16f5bde9f334f5116a9b0ae0fd210a34">getNodeAttributes</a> (const DisplayNode &amp;Node) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ac4958713e9cfec2cc01d911c39d997">getEdgeColorAttr</a> (const DisplayNode &amp;From, const DisplayNode &amp;To) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displaynode">DisplayNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff766a3753d20bb82ebb51ee3ac6f72c">getEntryNode</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6115bcaadb80250c0f7c81a715d68a2">attribute</a> (StringRef Colour) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8cdb080f19ac0cbaa2706fc155f142c">NodeGenerationComplete</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae757d100ce8a5100061a5ab2c92f7934">GraphName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displaynode">DisplayNode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41e1cb94f796b48daf618ae18ec93a40">Nodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displaynode">DisplayNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addb26e91501123d0fbd5e50b3eb1ab02">NodePtrs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displaynode">DisplayNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb961cbfee35c448c73051a98923f0bd">EntryNode</a> = nullptr</td>
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


<p>Definition at line 1692 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### NodeIterator {#a951af86817df7ddb54544b04774309a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::NodeIterator =  std::vector&lt;DisplayNode *&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1700 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DotCfgDiffDisplayGraph() {#ac63a4cbbc86e0e7621fc3b71be19f113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::DotCfgDiffDisplayGraph (std::string Name)</td>
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



<p>Definition at line 1694 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Reference <a href="#ae757d100ce8a5100061a5ab2c92f7934">GraphName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createNode() {#a73186cee4a2fd91636bb4754c3373858}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::createNode (std::string C, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Colour)</td>
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



<p>Definition at line 1723 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#ab8cdb080f19ac0cbaa2706fc155f142c">NodeGenerationComplete</a> and <a href="#a41e1cb94f796b48daf618ae18ec93a40">Nodes</a>.</p>

</div>
</div>

### generateDotFile() {#af15f59a940b7e5ce205f671241664985}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::generateDotFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> DotFile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1697 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a293545f9b5864a8e1b33e57becbc5b3a">llvm::raw_fd_ostream::close</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a45fc498e695e5b2061ab5e6ec8e604a1">llvm::WriteGraph</a>.</p>

</div>
</div>

### getEdgeColorAttr() {#a4ac4958713e9cfec2cc01d911c39d997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::getEdgeColorAttr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displaynode">DisplayNode</a> &amp; From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displaynode">DisplayNode</a> &amp; To)</td>
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



<p>Definition at line 1752 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="#ac6115bcaadb80250c0f7c81a715d68a2">attribute</a>, <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displayelement/#a9464be6c5aeee8346e386f5b86a47f63">anonymous{StandardInstrumentations.cpp}::DisplayElement::getColour</a> and <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displaynode/#aa01347c6afeafcc3bc16b295b2996643">anonymous{StandardInstrumentations.cpp}::DisplayNode::getEdge</a>.</p>

</div>
</div>

### getEntryNode() {#aff766a3753d20bb82ebb51ee3ac6f72c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DisplayNode * anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::getEntryNode ()</td>
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



<p>Definition at line 1758 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aeb961cbfee35c448c73051a98923f0bd">EntryNode</a> and <a href="#ab8cdb080f19ac0cbaa2706fc155f142c">NodeGenerationComplete</a>.</p>

</div>
</div>

### getGraphName() {#a7c37eea28073ea41cc0a4ea9bed76c75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::getGraphName ()</td>
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



<p>Definition at line 1738 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Reference <a href="#ae757d100ce8a5100061a5ab2c92f7934">GraphName</a>.</p>

</div>
</div>

### getNode() {#aae785e172383d1db142d127c139969e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DisplayNode &amp; anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::getNode (unsigned N)</td>
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



<p>Definition at line 1728 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a41e1cb94f796b48daf618ae18ec93a40">Nodes</a>.</p>

</div>
</div>

### getNodeAttributes() {#a16f5bde9f334f5116a9b0ae0fd210a34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::getNodeAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displaynode">DisplayNode</a> &amp; Node)</td>
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



<p>Definition at line 1747 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Reference <a href="#ac6115bcaadb80250c0f7c81a715d68a2">attribute</a>.</p>

</div>
</div>

### getNodeLabel() {#a455e6c94d4a8a9611992d58c8ec8ad29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::getNodeLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displaynode">DisplayNode</a> &amp; Node)</td>
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



<p>Definition at line 1742 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>

</div>
</div>

### nodes\_begin() {#a4521346fcf0b7fdbbc7948d0001ad405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeIterator anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::nodes_begin ()</td>
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



<p>Definition at line 1701 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab8cdb080f19ac0cbaa2706fc155f142c">NodeGenerationComplete</a> and <a href="#addb26e91501123d0fbd5e50b3eb1ab02">NodePtrs</a>.</p>

</div>
</div>

### nodes\_end() {#a8a706f27d5a35850b439b49ba10bfb70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeIterator anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::nodes_end ()</td>
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



<p>Definition at line 1705 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab8cdb080f19ac0cbaa2706fc155f142c">NodeGenerationComplete</a> and <a href="#addb26e91501123d0fbd5e50b3eb1ab02">NodePtrs</a>.</p>

</div>
</div>

### setEntryNode() {#a59db9f0a5bbc2cf0d4187f5f50d97b7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::setEntryNode (unsigned N)</td>
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



<p>Definition at line 1712 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aeb961cbfee35c448c73051a98923f0bd">EntryNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#ab8cdb080f19ac0cbaa2706fc155f142c">NodeGenerationComplete</a>, <a href="#addb26e91501123d0fbd5e50b3eb1ab02">NodePtrs</a> and <a href="#a41e1cb94f796b48daf618ae18ec93a40">Nodes</a>.</p>

</div>
</div>

### size() {#aaaf851c060a371c31fa65c28be067521}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::size ()</td>
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



<p>Definition at line 1732 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab8cdb080f19ac0cbaa2706fc155f142c">NodeGenerationComplete</a> and <a href="#a41e1cb94f796b48daf618ae18ec93a40">Nodes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### attribute() {#ac6115bcaadb80250c0f7c81a715d68a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::attribute (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Colour)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1765 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>.</p>


<p>Referenced by <a href="#a4ac4958713e9cfec2cc01d911c39d997">getEdgeColorAttr</a> and <a href="#a16f5bde9f334f5116a9b0ae0fd210a34">getNodeAttributes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### EntryNode {#aeb961cbfee35c448c73051a98923f0bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DisplayNode* anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::EntryNode = nullptr</td>
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



<p>Definition at line 1773 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Referenced by <a href="#aff766a3753d20bb82ebb51ee3ac6f72c">getEntryNode</a> and <a href="#a59db9f0a5bbc2cf0d4187f5f50d97b7f">setEntryNode</a>.</p>

</div>
</div>

### GraphName {#ae757d100ce8a5100061a5ab2c92f7934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::GraphName</td>
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



<p>Definition at line 1770 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Referenced by <a href="#ac63a4cbbc86e0e7621fc3b71be19f113">DotCfgDiffDisplayGraph</a> and <a href="#a7c37eea28073ea41cc0a4ea9bed76c75">getGraphName</a>.</p>

</div>
</div>

### NodeGenerationComplete {#ab8cdb080f19ac0cbaa2706fc155f142c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::NodeGenerationComplete = false</td>
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



<p>Definition at line 1769 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Referenced by <a href="#a73186cee4a2fd91636bb4754c3373858">createNode</a>, <a href="#aff766a3753d20bb82ebb51ee3ac6f72c">getEntryNode</a>, <a href="#a4521346fcf0b7fdbbc7948d0001ad405">nodes_begin</a>, <a href="#a8a706f27d5a35850b439b49ba10bfb70">nodes_end</a>, <a href="#a59db9f0a5bbc2cf0d4187f5f50d97b7f">setEntryNode</a> and <a href="#aaaf851c060a371c31fa65c28be067521">size</a>.</p>

</div>
</div>

### NodePtrs {#addb26e91501123d0fbd5e50b3eb1ab02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;DisplayNode *&gt; anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::NodePtrs</td>
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



<p>Definition at line 1772 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Referenced by <a href="#a4521346fcf0b7fdbbc7948d0001ad405">nodes_begin</a>, <a href="#a8a706f27d5a35850b439b49ba10bfb70">nodes_end</a> and <a href="#a59db9f0a5bbc2cf0d4187f5f50d97b7f">setEntryNode</a>.</p>

</div>
</div>

### Nodes {#a41e1cb94f796b48daf618ae18ec93a40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;DisplayNode&gt; anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::Nodes</td>
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



<p>Definition at line 1771 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Referenced by <a href="#a73186cee4a2fd91636bb4754c3373858">createNode</a>, <a href="#aae785e172383d1db142d127c139969e9">getNode</a>, <a href="#a59db9f0a5bbc2cf0d4187f5f50d97b7f">setEntryNode</a> and <a href="#aaaf851c060a371c31fa65c28be067521">size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
