---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcdecodedpseudoprobeinlinetree
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCDecodedPseudoProbeInlineTree` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MCDecodedPseudoProbeInlineTree { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">llvm/MC/MCPseudoProbe.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetreebase">MCPseudoProbeInlineTreeBase&lt;ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40adf67de4954350b60031fbee2ca684">MCDecodedPseudoProbeInlineTree</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab030f3d4010890197a5c8dacd2f517da">MCDecodedPseudoProbeInlineTree</a> (const InlineSite &amp;Site, MCDecodedPseudoProbeInlineTree *Parent)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa03d3ef48511098a044431ab6ba372de">hasInlineSite</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a36a7723e76924ffbe94c9e7e040b4c9c">InlineSite</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a044d551af39984b12bbaf11fa1275913">getInlineSite</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab76cb3f6b6cea02db1cc6ebf0704be34">setProbes</a> (MutableArrayRef&lt; MCDecodedPseudoProbe &gt; ProbesRef)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9b4648c216fc311c4308fd64843a19a">getProbes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c3cd6d22cbff068e7e1202d50441661">NumProbes</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a137c400812a639f8d3bbdaf4a535bda6">ProbeId</a> = 0</td>
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


<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCDecodedPseudoProbeInlineTree() {#a40adf67de4954350b60031fbee2ca684}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCDecodedPseudoProbeInlineTree::MCDecodedPseudoProbeInlineTree ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>Referenced by <a href="#ab030f3d4010890197a5c8dacd2f517da">MCDecodedPseudoProbeInlineTree</a>.</p>

</div>
</div>

### MCDecodedPseudoProbeInlineTree() {#ab030f3d4010890197a5c8dacd2f517da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCDecodedPseudoProbeInlineTree::MCDecodedPseudoProbeInlineTree (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a36a7723e76924ffbe94c9e7e040b4c9c">InlineSite</a> &amp; Site, <a href="/web-llvm/docs/api/classes/llvm/mcdecodedpseudoprobeinlinetree">MCDecodedPseudoProbeInlineTree</a> * Parent)</td>
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



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetreebase/#a1494be26ea72fa903ec2ac8b29dd1154">llvm::MCPseudoProbeInlineTreeBase&lt; MCDecodedPseudoProbe *, MCDecodedPseudoProbeInlineTree, MutableArrayRef&lt; MCDecodedPseudoProbeInlineTree &gt; &gt;::Guid</a>, <a href="#a40adf67de4954350b60031fbee2ca684">MCDecodedPseudoProbeInlineTree</a> and <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetreebase/#a9c92b781cf94c0942f59a231c1111988">llvm::MCPseudoProbeInlineTreeBase&lt; MCDecodedPseudoProbe *, MCDecodedPseudoProbeInlineTree, MutableArrayRef&lt; MCDecodedPseudoProbeInlineTree &gt; &gt;::Parent</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getInlineSite() {#a044d551af39984b12bbaf11fa1275913}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineSite llvm::MCDecodedPseudoProbeInlineTree::getInlineSite ()</td>
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



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetreebase/#a1494be26ea72fa903ec2ac8b29dd1154">llvm::MCPseudoProbeInlineTreeBase&lt; MCDecodedPseudoProbe *, MCDecodedPseudoProbeInlineTree, MutableArrayRef&lt; MCDecodedPseudoProbeInlineTree &gt; &gt;::Guid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdecodedpseudoprobe/#ae65fd4d6ca6b5107072abefc811a63b0">llvm::MCDecodedPseudoProbe::getInlineContext</a>.</p>

</div>
</div>

### getProbes() {#af9b4648c216fc311c4308fd64843a19a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto llvm::MCDecodedPseudoProbeInlineTree::getProbes ()</td>
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



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a99416758c13252bef45320a6ba6aa09c">llvm::MutableArrayRef</a> and <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetreebase/#a9082efdbacc9d8c31bcd10f0cc7766ee">llvm::MCPseudoProbeInlineTreeBase&lt; MCDecodedPseudoProbe *, MCDecodedPseudoProbeInlineTree, MutableArrayRef&lt; MCDecodedPseudoProbeInlineTree &gt; &gt;::Probes</a>.</p>

</div>
</div>

### hasInlineSite() {#aa03d3ef48511098a044431ab6ba372de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCDecodedPseudoProbeInlineTree::hasInlineSite ()</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetreebase/#a860c00c27d6bcd7c49fc067f03665e58">llvm::MCPseudoProbeInlineTreeBase&lt; MCDecodedPseudoProbe *, MCDecodedPseudoProbeInlineTree, MutableArrayRef&lt; MCDecodedPseudoProbeInlineTree &gt; &gt;::isRoot</a> and <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetreebase/#a9c92b781cf94c0942f59a231c1111988">llvm::MCPseudoProbeInlineTreeBase&lt; MCDecodedPseudoProbe *, MCDecodedPseudoProbeInlineTree, MutableArrayRef&lt; MCDecodedPseudoProbeInlineTree &gt; &gt;::Parent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdecodedpseudoprobe/#ae65fd4d6ca6b5107072abefc811a63b0">llvm::MCDecodedPseudoProbe::getInlineContext</a> and <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobedecoder/#ac10604339044d8e1bd1fa945734360d3">llvm::MCPseudoProbeDecoder::getInlinerDescForProbe</a>.</p>

</div>
</div>

### setProbes() {#ab76cb3f6b6cea02db1cc6ebf0704be34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCDecodedPseudoProbeInlineTree::setProbes (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcdecodedpseudoprobe">MCDecodedPseudoProbe</a> &gt; ProbesRef)</td>
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



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#a0bf5f8e45bfccb0805b5e12d44622271">llvm::MutableArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetreebase/#a9082efdbacc9d8c31bcd10f0cc7766ee">llvm::MCPseudoProbeInlineTreeBase&lt; MCDecodedPseudoProbe *, MCDecodedPseudoProbeInlineTree, MutableArrayRef&lt; MCDecodedPseudoProbeInlineTree &gt; &gt;::Probes</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### NumProbes {#a1c3cd6d22cbff068e7e1202d50441661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MCDecodedPseudoProbeInlineTree::NumProbes = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>

</div>
</div>

### ProbeId {#a137c400812a639f8d3bbdaf4a535bda6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MCDecodedPseudoProbeInlineTree::ProbeId = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
