---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcdecodedpseudoprobe
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCDecodedPseudoProbe` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MCDecodedPseudoProbe { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">llvm/MC/MCPseudoProbe.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobebase">MCPseudoProbeBase</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa8ed6429036e98783b0572408c48795">MCDecodedPseudoProbe</a> (uint64_t Ad, uint32_t I, PseudoProbeType K, uint8_t At, uint32_t D, MCDecodedPseudoProbeInlineTree *Tree)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c0a8c7b8ed900da1f9faed8303610a1">getGuid</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed4be481e89d9617eb4185a779e12592">getAddress</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aca47e0214459de208e50ebe9e2bde8">setAddress</a> (uint64_t Addr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdecodedpseudoprobeinlinetree">MCDecodedPseudoProbeInlineTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae54664f60d521c7b775c37b54c3dcdb5">getInlineTreeNode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae65fd4d6ca6b5107072abefc811a63b0">getInlineContext</a> (SmallVectorImpl&lt; MCPseudoProbeFrameLocation &gt; &amp;ContextStack, const GUIDProbeFunctionMap &amp;GUID2FuncMAP) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8c0c28b1ef6e54ece2c016c91a55a66">getInlineContextStr</a> (const GUIDProbeFunctionMap &amp;GUID2FuncMAP) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34098ed74b8701fdd984122019830dfa">print</a> (raw_ostream &amp;OS, const GUIDProbeFunctionMap &amp;GUID2FuncMAP, bool ShowName) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7d62128b27b9c6c0289c7dff0ef7a81">Address</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdecodedpseudoprobeinlinetree">MCDecodedPseudoProbeInlineTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a296e9899c98007817885f5c34aec7acf">InlineTree</a></td>
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


<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCDecodedPseudoProbe() {#aaa8ed6429036e98783b0572408c48795}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCDecodedPseudoProbe::MCDecodedPseudoProbe (uint64_t Ad, uint32_t I, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024c">PseudoProbeType</a> K, uint8_t At, uint32_t D, <a href="/web-llvm/docs/api/classes/llvm/mcdecodedpseudoprobeinlinetree">MCDecodedPseudoProbeInlineTree</a> * Tree)</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobebase/#a862d55c2dffff38a8507d9bd8d443c36">llvm::MCPseudoProbeBase::MCPseudoProbeBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAddress() {#aed4be481e89d9617eb4185a779e12592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MCDecodedPseudoProbe::getAddress ()</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>

</div>
</div>

### getGuid() {#a8c0a8c7b8ed900da1f9faed8303610a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MCDecodedPseudoProbe::getGuid ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcpseudoprobe-cpp">MCPseudoProbe.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobedecoder/#ab638801b26cfe505f77e5111f55b344c">llvm::MCPseudoProbeDecoder::getInlineContextForProbe</a> and <a href="#a34098ed74b8701fdd984122019830dfa">print</a>.</p>

</div>
</div>

### getInlineContext() {#ae65fd4d6ca6b5107072abefc811a63b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCDecodedPseudoProbe::getInlineContext (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a696d3d24aa3e3d5a32a853ce25da09f7">MCPseudoProbeFrameLocation</a> &gt; &amp; ContextStack, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/guidprobefunctionmap">GUIDProbeFunctionMap</a> &amp; GUID2FuncMAP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>, definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcpseudoprobe-cpp">MCPseudoProbe.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdecodedpseudoprobeinlinetree/#a044d551af39984b12bbaf11fa1275913">llvm::MCDecodedPseudoProbeInlineTree::getInlineSite</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcpseudoprobe-cpp/#a66122b446b6d33a9d2b0cc985fd490b1">getProbeFNameForGUID</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetreebase/#a1494be26ea72fa903ec2ac8b29dd1154">llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::Guid</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdecodedpseudoprobeinlinetree/#aa03d3ef48511098a044431ab6ba372de">llvm::MCDecodedPseudoProbeInlineTree::hasInlineSite</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetreebase/#a9c92b781cf94c0942f59a231c1111988">llvm::MCPseudoProbeInlineTreeBase&lt; ProbesType, DerivedProbeInlineTreeType, InlinedProbeTreeMap &gt;::Parent</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobedecoder/#ab638801b26cfe505f77e5111f55b344c">llvm::MCPseudoProbeDecoder::getInlineContextForProbe</a> and <a href="#ab8c0c28b1ef6e54ece2c016c91a55a66">getInlineContextStr</a>.</p>

</div>
</div>

### getInlineContextStr() {#ab8c0c28b1ef6e54ece2c016c91a55a66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string MCDecodedPseudoProbe::getInlineContextStr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/guidprobefunctionmap">GUIDProbeFunctionMap</a> &amp; GUID2FuncMAP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>, definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcpseudoprobe-cpp">MCPseudoProbe.cpp</a>.</p>


<p>Reference <a href="#ae65fd4d6ca6b5107072abefc811a63b0">getInlineContext</a>.</p>


<p>Referenced by <a href="#a34098ed74b8701fdd984122019830dfa">print</a>.</p>

</div>
</div>

### getInlineTreeNode() {#ae54664f60d521c7b775c37b54c3dcdb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDecodedPseudoProbeInlineTree * llvm::MCDecodedPseudoProbe::getInlineTreeNode ()</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobedecoder/#ad226d8757d48e41bda85b17c7a88478f">llvm::MCPseudoProbeDecoder::addInjectedProbe</a> and <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobedecoder/#ac10604339044d8e1bd1fa945734360d3">llvm::MCPseudoProbeDecoder::getInlinerDescForProbe</a>.</p>

</div>
</div>

### print() {#a34098ed74b8701fdd984122019830dfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCDecodedPseudoProbe::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/guidprobefunctionmap">GUIDProbeFunctionMap</a> &amp; GUID2FuncMAP, bool ShowName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>, definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcpseudoprobe-cpp">MCPseudoProbe.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobebase/#ac2962e7b46982f2148b7f1743c1ac16b">llvm::MCPseudoProbeBase::Discriminator</a>, <a href="#a8c0a8c7b8ed900da1f9faed8303610a1">getGuid</a>, <a href="#ab8c0c28b1ef6e54ece2c016c91a55a66">getInlineContextStr</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcpseudoprobe-cpp/#a66122b446b6d33a9d2b0cc985fd490b1">getProbeFNameForGUID</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobebase/#a6e8d573f07368c01f32a8160e9ca4f2a">llvm::MCPseudoProbeBase::Index</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcpseudoprobe-cpp/#a0dcac7c06fb3e76f3476f82843c0d31d">PseudoProbeTypeStr</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a> and <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobebase/#a578a904af332f58d3a5a749936ddc40d">llvm::MCPseudoProbeBase::Type</a>.</p>

</div>
</div>

### setAddress() {#a4aca47e0214459de208e50ebe9e2bde8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCDecodedPseudoProbe::setAddress (uint64_t Addr)</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Address {#ae7d62128b27b9c6c0289c7dff0ef7a81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MCDecodedPseudoProbe::Address</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>

</div>
</div>

### InlineTree {#a296e9899c98007817885f5c34aec7acf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDecodedPseudoProbeInlineTree* llvm::MCDecodedPseudoProbe::InlineTree</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcpseudoprobe-cpp">MCPseudoProbe.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
