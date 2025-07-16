---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-standardinstrumentations-cpp-/displaynode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DisplayNode` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{StandardInstrumentations.cpp}::DisplayNode { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displayelement">DisplayElement</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9c1e25da79f80276b15789c50f81e7a">ChildIterator</a> = std::unordered_set&lt; <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displaynode">DisplayNode</a> * &gt;<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">::const_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae74861a074f11bf9c158aa27d63487ec">EdgeIterator</a> = std::vector&lt; <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displayedge">DisplayEdge</a> * &gt;<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">::const_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff8a644d11d5d6b3b9a0a6d9368ff25b">DisplayNode</a> (std::string Content, StringRef Colour)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac9c1e25da79f80276b15789c50f81e7a">ChildIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07bae674a10b08a4bb1e583edf5a0d16">children_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac9c1e25da79f80276b15789c50f81e7a">ChildIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ec50b0bc7bac72ea598abbcfea6df28">children_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae74861a074f11bf9c158aa27d63487ec">EdgeIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa110892684db54f01dd0ae5a102b3217">edges_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae74861a074f11bf9c158aa27d63487ec">EdgeIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa107247640a79e839d563c2c3041f279">edges_end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7d7eb6eeaba2175ccc393b72d2e0e8c">createEdge</a> (StringRef Value, DisplayNode &amp;Node, StringRef Colour)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af07d0773c6835805196443b4d704b414">getContent</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displayedge">DisplayEdge</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa01347c6afeafcc3bc16b295b2996643">getEdge</a> (const DisplayNode &amp;To) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad53eb428d10a6700471f95a555f64ed4">getEdgeSourceLabel</a> (const DisplayNode &amp;Sink) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad51c8d825cd908586fca1d92294cddcf">createEdgeMap</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52923dbfa764aa5a06464bebfa63a7c9">Content</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displayedge">DisplayEdge</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23d04569d5169ae7e44115964d68f878">Edges</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displayedge">DisplayEdge</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e2bfdcdf12bab121ba3374bf8dcea91">EdgePtrs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_set&lt; <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displaynode">DisplayNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a605689dc72564cf8b5b1a3a6b9098607">Children</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displaynode">DisplayNode</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displayedge">DisplayEdge</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49acb9d619abc141460b18818dd4d9a4">EdgeMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98a46c3600cae8abc99ff3fa6970ba59">AllEdgesCreated</a> = false</td>
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


<p>Definition at line 1638 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ChildIterator {#ac9c1e25da79f80276b15789c50f81e7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{StandardInstrumentations.cpp}::DisplayNode::ChildIterator =  std::unordered_set&lt;DisplayNode *&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1646 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>

</div>
</div>

### EdgeIterator {#ae74861a074f11bf9c158aa27d63487ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{StandardInstrumentations.cpp}::DisplayNode::EdgeIterator =  std::vector&lt;DisplayEdge *&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1651 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DisplayNode() {#aff8a644d11d5d6b3b9a0a6d9368ff25b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{StandardInstrumentations.cpp}::DisplayNode::DisplayNode (std::string Content, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Colour)</td>
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



<p>Definition at line 1642 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displayelement/#a881f9d9e9dc677891ecd1df7f329fc01">anonymous{StandardInstrumentations.cpp}::DisplayElement::Colour</a>, <a href="#a52923dbfa764aa5a06464bebfa63a7c9">Content</a> and <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displayelement/#abee2c4c37c78cf77648f0bcffa03b3fb">anonymous{StandardInstrumentations.cpp}::DisplayElement::DisplayElement</a>.</p>


<p>Referenced by <a href="#ac7d7eb6eeaba2175ccc393b72d2e0e8c">createEdge</a>, <a href="#aa01347c6afeafcc3bc16b295b2996643">getEdge</a> and <a href="#ad53eb428d10a6700471f95a555f64ed4">getEdgeSourceLabel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### children\_begin() {#a07bae674a10b08a4bb1e583edf5a0d16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChildIterator anonymous{StandardInstrumentations.cpp}::DisplayNode::children_begin ()</td>
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



<p>Definition at line 1647 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Reference <a href="#a605689dc72564cf8b5b1a3a6b9098607">Children</a>.</p>

</div>
</div>

### children\_end() {#a2ec50b0bc7bac72ea598abbcfea6df28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChildIterator anonymous{StandardInstrumentations.cpp}::DisplayNode::children_end ()</td>
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



<p>Definition at line 1648 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Reference <a href="#a605689dc72564cf8b5b1a3a6b9098607">Children</a>.</p>

</div>
</div>

### createEdge() {#ac7d7eb6eeaba2175ccc393b72d2e0e8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{StandardInstrumentations.cpp}::DisplayNode::createEdge (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value, <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displaynode">DisplayNode</a> &amp; Node, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Colour)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1656 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="#a98a46c3600cae8abc99ff3fa6970ba59">AllEdgesCreated</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a605689dc72564cf8b5b1a3a6b9098607">Children</a>, <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displayelement/#a881f9d9e9dc677891ecd1df7f329fc01">anonymous{StandardInstrumentations.cpp}::DisplayElement::Colour</a>, <a href="#aff8a644d11d5d6b3b9a0a6d9368ff25b">DisplayNode</a> and <a href="#a23d04569d5169ae7e44115964d68f878">Edges</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiffnode/#a82bbd4467dd3225e5b2ecf7a3a811d40">anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::createDisplayEdges</a>.</p>

</div>
</div>

### createEdgeMap() {#ad51c8d825cd908586fca1d92294cddcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{StandardInstrumentations.cpp}::DisplayNode::createEdgeMap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1673 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="#a98a46c3600cae8abc99ff3fa6970ba59">AllEdgesCreated</a>, <a href="#a49acb9d619abc141460b18818dd4d9a4">EdgeMap</a> and <a href="#a23d04569d5169ae7e44115964d68f878">Edges</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiffnode/#a82bbd4467dd3225e5b2ecf7a3a811d40">anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::createDisplayEdges</a>.</p>

</div>
</div>

### edges\_begin() {#aa110892684db54f01dd0ae5a102b3217}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeIterator anonymous{StandardInstrumentations.cpp}::DisplayNode::edges_begin ()</td>
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



<p>Definition at line 1652 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Reference <a href="#a9e2bfdcdf12bab121ba3374bf8dcea91">EdgePtrs</a>.</p>

</div>
</div>

### edges\_end() {#aa107247640a79e839d563c2c3041f279}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeIterator anonymous{StandardInstrumentations.cpp}::DisplayNode::edges_end ()</td>
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



<p>Definition at line 1653 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Reference <a href="#a9e2bfdcdf12bab121ba3374bf8dcea91">EdgePtrs</a>.</p>

</div>
</div>

### getContent() {#af07d0773c6835805196443b4d704b414}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{StandardInstrumentations.cpp}::DisplayNode::getContent ()</td>
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



<p>Definition at line 1659 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Reference <a href="#a52923dbfa764aa5a06464bebfa63a7c9">Content</a>.</p>

</div>
</div>

### getEdge() {#aa01347c6afeafcc3bc16b295b2996643}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DisplayEdge &amp; anonymous{StandardInstrumentations.cpp}::DisplayNode::getEdge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displaynode">DisplayNode</a> &amp; To)</td>
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



<p>Definition at line 1662 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aff8a644d11d5d6b3b9a0a6d9368ff25b">DisplayNode</a> and <a href="#a49acb9d619abc141460b18818dd4d9a4">EdgeMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiffdisplaygraph/#a4ac4958713e9cfec2cc01d911c39d997">anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::getEdgeColorAttr</a> and <a href="#ad53eb428d10a6700471f95a555f64ed4">getEdgeSourceLabel</a>.</p>

</div>
</div>

### getEdgeSourceLabel() {#ad53eb428d10a6700471f95a555f64ed4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{StandardInstrumentations.cpp}::DisplayNode::getEdgeSourceLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/displaynode">DisplayNode</a> &amp; Sink)</td>
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



<p>Definition at line 1669 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>References <a href="#aff8a644d11d5d6b3b9a0a6d9368ff25b">DisplayNode</a> and <a href="#aa01347c6afeafcc3bc16b295b2996643">getEdge</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AllEdgesCreated {#a98a46c3600cae8abc99ff3fa6970ba59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{StandardInstrumentations.cpp}::DisplayNode::AllEdgesCreated = false</td>
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



<p>Definition at line 1688 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Referenced by <a href="#ac7d7eb6eeaba2175ccc393b72d2e0e8c">createEdge</a> and <a href="#ad51c8d825cd908586fca1d92294cddcf">createEdgeMap</a>.</p>

</div>
</div>

### Children {#a605689dc72564cf8b5b1a3a6b9098607}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_set&lt;DisplayNode *&gt; anonymous{StandardInstrumentations.cpp}::DisplayNode::Children</td>
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



<p>Definition at line 1684 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Referenced by <a href="#a07bae674a10b08a4bb1e583edf5a0d16">children_begin</a>, <a href="#a2ec50b0bc7bac72ea598abbcfea6df28">children_end</a> and <a href="#ac7d7eb6eeaba2175ccc393b72d2e0e8c">createEdge</a>.</p>

</div>
</div>

### Content {#a52923dbfa764aa5a06464bebfa63a7c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string anonymous{StandardInstrumentations.cpp}::DisplayNode::Content</td>
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



<p>Definition at line 1676 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Referenced by <a href="#aff8a644d11d5d6b3b9a0a6d9368ff25b">DisplayNode</a> and <a href="#af07d0773c6835805196443b4d704b414">getContent</a>.</p>

</div>
</div>

### EdgeMap {#a49acb9d619abc141460b18818dd4d9a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;const DisplayNode *, const DisplayEdge *&gt; anonymous{StandardInstrumentations.cpp}::DisplayNode::EdgeMap</td>
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



<p>Definition at line 1685 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Referenced by <a href="#ad51c8d825cd908586fca1d92294cddcf">createEdgeMap</a> and <a href="#aa01347c6afeafcc3bc16b295b2996643">getEdge</a>.</p>

</div>
</div>

### EdgePtrs {#a9e2bfdcdf12bab121ba3374bf8dcea91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;DisplayEdge *&gt; anonymous{StandardInstrumentations.cpp}::DisplayNode::EdgePtrs</td>
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



<p>Definition at line 1683 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Referenced by <a href="#aa110892684db54f01dd0ae5a102b3217">edges_begin</a> and <a href="#aa107247640a79e839d563c2c3041f279">edges_end</a>.</p>

</div>
</div>

### Edges {#a23d04569d5169ae7e44115964d68f878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;DisplayEdge&gt; anonymous{StandardInstrumentations.cpp}::DisplayNode::Edges</td>
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



<p>Definition at line 1681 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp">StandardInstrumentations.cpp</a>.</p>


<p>Referenced by <a href="#ac7d7eb6eeaba2175ccc393b72d2e0e8c">createEdge</a> and <a href="#ad51c8d825cd908586fca1d92294cddcf">createEdgeMap</a>.</p>

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
