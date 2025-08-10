---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiffnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DotCfgDiffNode` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b11622cbfdd84c073ed4bd631deb508">DotCfgDiffNode</a> ()=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebf896e8acdd1dae7483b1e8c82159f2">DotCfgDiffNode</a> (DotCfgDiff &amp;G, unsigned N, const BlockDataT&lt; DCData &gt; &amp;BD, StringRef Colour)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f478494a1e9cef42039983e842fcb4e">DotCfgDiffNode</a> (const DotCfgDiffNode &amp;DN)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad15f1fab521f0e57798041331c538646">getIndex</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1bc3ce3dbeb0e50c24c90ea6698de59">getLabel</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87724670b5b0a68631a2a3c189c9e5ce">getColour</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17edd300e5a48f84af9ef4199f213389">setCommon</a> (const BlockDataT&lt; DCData &gt; &amp;Other)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69d25d607c028f6b92f7040591d02b53">addEdge</a> (unsigned E, StringRef Value, StringRef Colour)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b5f536a091709d579a56c80575c65ff">finalize</a> (DotCfgDiff &amp;G)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1400cb6de03d98841e31070c1f718866">getEdgeColour</a> (const unsigned S) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f6028cdd89adeb15d6755814af79718">getBodyContent</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82bbd4467dd3225e5b2ecf7a3a811d40">createDisplayEdges</a> (DotCfgDiffDisplayGraph &amp;Graph, unsigned DisplayNode, std::map&lt; const unsigned, unsigned &gt; &amp;NodeMap) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiff">DotCfgDiff</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12aac635a3ec74eaeaf4caef726f68c1">Graph</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a336903f98c4a03558d6bea472802e37c">N</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/blockdatat">BlockDataT</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dcdata">DCData</a> &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c374038ece107c6de1f2cd92e1a78cf">Data</a>[2]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a508bb82659f12d82a11c0803c67074ff">Colour</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned, std::pair&lt; std::string, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a027bae8740cec4d7d970f1a5e2ec2e12">EdgesMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb81afa0e32a1f965348e2359f670b33">Children</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50b8f9799f2e1110a07f7ceaa50ed537">Edges</a></td>
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


<p>Definition at line 1795 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DotCfgDiffNode() {#a9b11622cbfdd84c073ed4bd631deb508}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::DotCfgDiffNode ()</td>
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



<p>Definition at line 1797 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Referenced by <a href="#a82bbd4467dd3225e5b2ecf7a3a811d40">createDisplayEdges</a> and <a href="#a5f478494a1e9cef42039983e842fcb4e">DotCfgDiffNode</a>.</p>

</div>
</div>

### DotCfgDiffNode() {#aebf896e8acdd1dae7483b1e8c82159f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::DotCfgDiffNode (<a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiff">DotCfgDiff</a> &amp; G, unsigned N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/blockdatat">BlockDataT</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dcdata">DCData</a> &gt; &amp; BD, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Colour)</td>
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



<p>Definition at line 1801 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="#a508bb82659f12d82a11c0803c67074ff">Colour</a>, <a href="#a4c374038ece107c6de1f2cd92e1a78cf">Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a12aac635a3ec74eaeaf4caef726f68c1">Graph</a> and <a href="#a336903f98c4a03558d6bea472802e37c">N</a>.</p>

</div>
</div>

### DotCfgDiffNode() {#a5f478494a1e9cef42039983e842fcb4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::DotCfgDiffNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiffnode">DotCfgDiffNode</a> &amp; DN)</td>
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



<p>Definition at line 1804 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="#abb81afa0e32a1f965348e2359f670b33">Children</a>, <a href="#a508bb82659f12d82a11c0803c67074ff">Colour</a>, <a href="#a4c374038ece107c6de1f2cd92e1a78cf">Data</a>, <a href="#a9b11622cbfdd84c073ed4bd631deb508">DotCfgDiffNode</a>, <a href="#a50b8f9799f2e1110a07f7ceaa50ed537">Edges</a>, <a href="#a027bae8740cec4d7d970f1a5e2ec2e12">EdgesMap</a>, <a href="#a12aac635a3ec74eaeaf4caef726f68c1">Graph</a> and <a href="#a336903f98c4a03558d6bea472802e37c">N</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addEdge() {#a69d25d607c028f6b92f7040591d02b53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::addEdge (unsigned E, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Colour)</td>
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



<p>Definition at line 1826 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a508bb82659f12d82a11c0803c67074ff">Colour</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a545d681ebe57225ad716ad3ac129b400">CommonColour</a> and <a href="#a027bae8740cec4d7d970f1a5e2ec2e12">EdgesMap</a>.</p>

</div>
</div>

### createDisplayEdges() {#a82bbd4467dd3225e5b2ecf7a3a811d40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::createDisplayEdges (<a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiffdisplaygraph">DotCfgDiffDisplayGraph</a> &amp; Graph, unsigned DisplayNode, std::map&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned, unsigned &gt; &amp; NodeMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1844 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="#a508bb82659f12d82a11c0803c67074ff">Colour</a>, <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displaynode/#ac7d7eb6eeaba2175ccc393b72d2e0e8c">anonymous{StandardInstrumentations.cpp}::DisplayNode::createEdge</a>, <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displaynode/#ad51c8d825cd908586fca1d92294cddcf">anonymous{StandardInstrumentations.cpp}::DisplayNode::createEdgeMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ac93a817bcb1ef2549c8e737866b7a3">llvm::DisplayGraph</a>, <a href="#a9b11622cbfdd84c073ed4bd631deb508">DotCfgDiffNode</a>, <a href="#a50b8f9799f2e1110a07f7ceaa50ed537">Edges</a>, <a href="#a1400cb6de03d98841e31070c1f718866">getEdgeColour</a>, <a href="#ad15f1fab521f0e57798041331c538646">getIndex</a>, <a href="#a12aac635a3ec74eaeaf4caef726f68c1">Graph</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiff/#a3fa9750e84e933fde1239fbf5da2a81f">anonymous{StandardInstrumentations.cpp}::DotCfgDiff::createDisplayGraph</a>.</p>

</div>
</div>

### finalize() {#a5b5f536a091709d579a56c80575c65ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::finalize (<a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiff">DotCfgDiff</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1833 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="#abb81afa0e32a1f965348e2359f670b33">Children</a>, <a href="#a50b8f9799f2e1110a07f7ceaa50ed537">Edges</a>, <a href="#a027bae8740cec4d7d970f1a5e2ec2e12">EdgesMap</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>

</div>
</div>

### getBodyContent() {#a8f6028cdd89adeb15d6755814af79718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::getBodyContent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1842 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#ab1ae60edbb43834a65508930891e2569">AfterColour</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a00b94550118cead7009b5719454210a2">BeforeColour</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a508bb82659f12d82a11c0803c67074ff">Colour</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a545d681ebe57225ad716ad3ac129b400">CommonColour</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a>, <a href="#a4c374038ece107c6de1f2cd92e1a78cf">Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab3a01ed22efa91390e377a44b45087d8">llvm::doSystemDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a53315344f92e70843fb54b6b7769de67">llvm::StringRef::drop_until</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a61364ca3a5ff90fb2aa0d5a371fd43f7">llvm::StringRef::front</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-standardinstrumentations-cpp-/#a47366639c363a94f62304e26e09cfb18">anonymous{StandardInstrumentations.cpp}::makeHTMLReady</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#aa93bf2cc29b3a2ad5056bea30a373d52">llvm::StringRef::take_until</a>.</p>

</div>
</div>

### getColour() {#a87724670b5b0a68631a2a3c189c9e5ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::getColour ()</td>
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



<p>Definition at line 1817 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Reference <a href="#a508bb82659f12d82a11c0803c67074ff">Colour</a>.</p>

</div>
</div>

### getEdgeColour() {#a1400cb6de03d98841e31070c1f718866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::getEdgeColour (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned S)</td>
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



<p>Definition at line 1836 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a027bae8740cec4d7d970f1a5e2ec2e12">EdgesMap</a>.</p>


<p>Referenced by <a href="#a82bbd4467dd3225e5b2ecf7a3a811d40">createDisplayEdges</a>.</p>

</div>
</div>

### getIndex() {#ad15f1fab521f0e57798041331c538646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::getIndex ()</td>
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



<p>Definition at line 1809 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Reference <a href="#a336903f98c4a03558d6bea472802e37c">N</a>.</p>


<p>Referenced by <a href="#a82bbd4467dd3225e5b2ecf7a3a811d40">createDisplayEdges</a>.</p>

</div>
</div>

### getLabel() {#ae1bc3ce3dbeb0e50c24c90ea6698de59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::getLabel ()</td>
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



<p>Definition at line 1812 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4c374038ece107c6de1f2cd92e1a78cf">Data</a>.</p>

</div>
</div>

### setCommon() {#a17edd300e5a48f84af9ef4199f213389}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::setCommon (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/blockdatat">BlockDataT</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dcdata">DCData</a> &gt; &amp; Other)</td>
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



<p>Definition at line 1820 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a508bb82659f12d82a11c0803c67074ff">Colour</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a545d681ebe57225ad716ad3ac129b400">CommonColour</a>, <a href="#a4c374038ece107c6de1f2cd92e1a78cf">Data</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Children {#abb81afa0e32a1f965348e2359f670b33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::Children</td>
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



<p>Definition at line 1853 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Referenced by <a href="#a5f478494a1e9cef42039983e842fcb4e">DotCfgDiffNode</a> and <a href="#a5b5f536a091709d579a56c80575c65ff">finalize</a>.</p>

</div>
</div>

### Colour {#a508bb82659f12d82a11c0803c67074ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::Colour</td>
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



<p>Definition at line 1851 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Referenced by <a href="#a69d25d607c028f6b92f7040591d02b53">addEdge</a>, <a href="#a82bbd4467dd3225e5b2ecf7a3a811d40">createDisplayEdges</a>, <a href="#a5f478494a1e9cef42039983e842fcb4e">DotCfgDiffNode</a>, <a href="#aebf896e8acdd1dae7483b1e8c82159f2">DotCfgDiffNode</a>, <a href="#a8f6028cdd89adeb15d6755814af79718">getBodyContent</a>, <a href="#a87724670b5b0a68631a2a3c189c9e5ce">getColour</a> and <a href="#a17edd300e5a48f84af9ef4199f213389">setCommon</a>.</p>

</div>
</div>

### Data {#a4c374038ece107c6de1f2cd92e1a78cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BlockDataT&lt;DCData&gt;* anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::Data[2]</td>
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



<p>Definition at line 1850 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Referenced by <a href="#a5f478494a1e9cef42039983e842fcb4e">DotCfgDiffNode</a>, <a href="#aebf896e8acdd1dae7483b1e8c82159f2">DotCfgDiffNode</a>, <a href="#a8f6028cdd89adeb15d6755814af79718">getBodyContent</a>, <a href="#ae1bc3ce3dbeb0e50c24c90ea6698de59">getLabel</a> and <a href="#a17edd300e5a48f84af9ef4199f213389">setCommon</a>.</p>

</div>
</div>

### Edges {#a50b8f9799f2e1110a07f7ceaa50ed537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::Edges</td>
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



<p>Definition at line 1854 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Referenced by <a href="#a82bbd4467dd3225e5b2ecf7a3a811d40">createDisplayEdges</a>, <a href="#a5f478494a1e9cef42039983e842fcb4e">DotCfgDiffNode</a> and <a href="#a5b5f536a091709d579a56c80575c65ff">finalize</a>.</p>

</div>
</div>

### EdgesMap {#a027bae8740cec4d7d970f1a5e2ec2e12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;const unsigned, std::pair&lt;std::string, StringRef&gt; &gt; anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::EdgesMap</td>
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



<p>Definition at line 1852 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Referenced by <a href="#a69d25d607c028f6b92f7040591d02b53">addEdge</a>, <a href="#a5f478494a1e9cef42039983e842fcb4e">DotCfgDiffNode</a>, <a href="#a5b5f536a091709d579a56c80575c65ff">finalize</a> and <a href="#a1400cb6de03d98841e31070c1f718866">getEdgeColour</a>.</p>

</div>
</div>

### Graph {#a12aac635a3ec74eaeaf4caef726f68c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotCfgDiff&amp; anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::Graph</td>
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



<p>Definition at line 1848 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Referenced by <a href="#a82bbd4467dd3225e5b2ecf7a3a811d40">createDisplayEdges</a>, <a href="#a5f478494a1e9cef42039983e842fcb4e">DotCfgDiffNode</a> and <a href="#aebf896e8acdd1dae7483b1e8c82159f2">DotCfgDiffNode</a>.</p>

</div>
</div>

### N {#a336903f98c4a03558d6bea472802e37c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::N</td>
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



<p>Definition at line 1849 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Referenced by <a href="#a5f478494a1e9cef42039983e842fcb4e">DotCfgDiffNode</a>, <a href="#aebf896e8acdd1dae7483b1e8c82159f2">DotCfgDiffNode</a> and <a href="#ad15f1fab521f0e57798041331c538646">getIndex</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
