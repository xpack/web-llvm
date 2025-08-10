---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcpseudoprobeinlinetreebase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCPseudoProbeInlineTreeBase` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename ProbesType, typename DerivedProbeInlineTreeType, typename InlinedProbeTreeMap&gt;
class llvm::MCPseudoProbeInlineTreeBase&lt;ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">llvm/MC/MCPseudoProbe.h</a>"
</div>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a9cc2b2b20e27ed21e767f5c14480fb6a">MCPseudoProbeInlineTreeBase</a> ()</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a860c00c27d6bcd7c49fc067f03665e58">isRoot</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">InlinedProbeTreeMap &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad0e068749848f79650b26d27e3078e5b">getChildren</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> InlinedProbeTreeMap &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac02712ad0304a6c9cc06395a1ce6c7c6">getChildren</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ProbesType &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad50428db317645f902cffd9d31c75f8e">getProbes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">DerivedProbeInlineTreeType *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a51ca42102ea4b48abb9f061c7065aad6">getOrAddNode</a> (const InlineSite &amp;Site)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1494be26ea72fa903ec2ac8b29dd1154">Guid</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetreebase">MCPseudoProbeInlineTreeBase</a>&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt; *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9c92b781cf94c0942f59a231c1111988">Parent</a> = nullptr</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">InlinedProbeTreeMap</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3b56b39896707a38c4d1ecfef5131ba0">Children</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ProbesType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9082efdbacc9d8c31bcd10f0cc7766ee">Probes</a></td>
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


<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### MCPseudoProbeInlineTreeBase() {#a9cc2b2b20e27ed21e767f5c14480fb6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ProbesType, typename DerivedProbeInlineTreeType, typename InlinedProbeTreeMap&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::MCPseudoProbeInlineTreeBase ()</td>
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



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>Reference <a href="#a9cc2b2b20e27ed21e767f5c14480fb6a">llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::MCPseudoProbeInlineTreeBase</a>.</p>


<p>Referenced by <a href="#a9cc2b2b20e27ed21e767f5c14480fb6a">llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::MCPseudoProbeInlineTreeBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getChildren() {#ad0e068749848f79650b26d27e3078e5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ProbesType, typename DerivedProbeInlineTreeType, typename InlinedProbeTreeMap&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlinedProbeTreeMap &amp; llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::getChildren ()</td>
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



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>Reference <a href="#a3b56b39896707a38c4d1ecfef5131ba0">llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::Children</a>.</p>

</div>
</div>

### getChildren() {#ac02712ad0304a6c9cc06395a1ce6c7c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ProbesType, typename DerivedProbeInlineTreeType, typename InlinedProbeTreeMap&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InlinedProbeTreeMap &amp; llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::getChildren ()</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>Reference <a href="#a3b56b39896707a38c4d1ecfef5131ba0">llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::Children</a>.</p>

</div>
</div>

### getOrAddNode() {#a51ca42102ea4b48abb9f061c7065aad6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ProbesType, typename DerivedProbeInlineTreeType, typename InlinedProbeTreeMap&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DerivedProbeInlineTreeType * llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::getOrAddNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a36a7723e76924ffbe94c9e7e040b4c9c">InlineSite</a> &amp; Site)</td>
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



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>Reference <a href="#a3b56b39896707a38c4d1ecfef5131ba0">llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::Children</a>.</p>

</div>
</div>

### getProbes() {#ad50428db317645f902cffd9d31c75f8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ProbesType, typename DerivedProbeInlineTreeType, typename InlinedProbeTreeMap&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ProbesType &amp; llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::getProbes ()</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>Reference <a href="#a9082efdbacc9d8c31bcd10f0cc7766ee">llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::Probes</a>.</p>

</div>
</div>

### isRoot() {#a860c00c27d6bcd7c49fc067f03665e58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ProbesType, typename DerivedProbeInlineTreeType, typename InlinedProbeTreeMap&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::isRoot ()</td>
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



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>Reference <a href="#a1494be26ea72fa903ec2ac8b29dd1154">llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::Guid</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Guid {#a1494be26ea72fa903ec2ac8b29dd1154}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ProbesType, typename DerivedProbeInlineTreeType, typename InlinedProbeTreeMap&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::Guid = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdecodedpseudoprobe/#ae65fd4d6ca6b5107072abefc811a63b0">llvm::MCDecodedPseudoProbe::getInlineContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobedecoder/#ac10604339044d8e1bd1fa945734360d3">llvm::MCPseudoProbeDecoder::getInlinerDescForProbe</a> and <a href="#a860c00c27d6bcd7c49fc067f03665e58">llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::isRoot</a>.</p>

</div>
</div>

### Parent {#a9c92b781cf94c0942f59a231c1111988}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ProbesType, typename DerivedProbeInlineTreeType, typename InlinedProbeTreeMap&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCPseudoProbeInlineTreeBase&lt;ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap&gt;* llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::Parent = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdecodedpseudoprobe/#ae65fd4d6ca6b5107072abefc811a63b0">llvm::MCDecodedPseudoProbe::getInlineContext</a> and <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobedecoder/#ac10604339044d8e1bd1fa945734360d3">llvm::MCPseudoProbeDecoder::getInlinerDescForProbe</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Children {#a3b56b39896707a38c4d1ecfef5131ba0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ProbesType, typename DerivedProbeInlineTreeType, typename InlinedProbeTreeMap&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlinedProbeTreeMap llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::Children</td>
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



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>Referenced by <a href="#ad0e068749848f79650b26d27e3078e5b">llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::getChildren</a>, <a href="#ac02712ad0304a6c9cc06395a1ce6c7c6">llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::getChildren</a> and <a href="#a51ca42102ea4b48abb9f061c7065aad6">llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::getOrAddNode</a>.</p>

</div>
</div>

### Probes {#a9082efdbacc9d8c31bcd10f0cc7766ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ProbesType, typename DerivedProbeInlineTreeType, typename InlinedProbeTreeMap&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProbesType llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::Probes</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>Referenced by <a href="#ad50428db317645f902cffd9d31c75f8e">llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::getProbes</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
