---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcpseudoprobeinlinetree
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCPseudoProbeInlineTree` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MCPseudoProbeInlineTree { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1efecc4f89f53911ceae157dadf57568">MCPseudoProbeInlineTree</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa69d08d99d1621b6f5401a95613c2d6b">MCPseudoProbeInlineTree</a> (uint64_t Guid)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfe858010c4d5f07ba1ddc8e35f18650">MCPseudoProbeInlineTree</a> (const InlineSite &amp;Site)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1246639c464dee99101df3e7c1c4dc8">addPseudoProbe</a> (const MCPseudoProbe &amp;Probe, const MCPseudoProbeInlineStack &amp;InlineStack)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a803da0fccbb98b7ceaf9240f55fa69b6">emit</a> (MCObjectStreamer *MCOS, const MCPseudoProbe *&amp;LastProbe)</td>
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


<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCPseudoProbeInlineTree() {#a1efecc4f89f53911ceae157dadf57568}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCPseudoProbeInlineTree::MCPseudoProbeInlineTree ()</td>
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



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>

</div>
</div>

### MCPseudoProbeInlineTree() {#aa69d08d99d1621b6f5401a95613c2d6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCPseudoProbeInlineTree::MCPseudoProbeInlineTree (uint64_t Guid)</td>
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



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetreebase/#a1494be26ea72fa903ec2ac8b29dd1154">llvm::MCPseudoProbeInlineTreeBase&lt; std::vector&lt; MCPseudoProbe &gt;, MCPseudoProbeInlineTree, std::unordered_map&lt; InlineSite, std::unique_ptr&lt; MCPseudoProbeInlineTree &gt;, InlineSiteHash &gt; &gt;::Guid</a>.</p>

</div>
</div>

### MCPseudoProbeInlineTree() {#adfe858010c4d5f07ba1ddc8e35f18650}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCPseudoProbeInlineTree::MCPseudoProbeInlineTree (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a36a7723e76924ffbe94c9e7e040b4c9c">InlineSite</a> &amp; Site)</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetreebase/#a1494be26ea72fa903ec2ac8b29dd1154">llvm::MCPseudoProbeInlineTreeBase&lt; std::vector&lt; MCPseudoProbe &gt;, MCPseudoProbeInlineTree, std::unordered_map&lt; InlineSite, std::unique_ptr&lt; MCPseudoProbeInlineTree &gt;, InlineSiteHash &gt; &gt;::Guid</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addPseudoProbe() {#ad1246639c464dee99101df3e7c1c4dc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCPseudoProbeInlineTree::addPseudoProbe (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobe">MCPseudoProbe</a> &amp; Probe, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a79515c0650a49e9a7ae8ed6e228b8816">MCPseudoProbeInlineStack</a> &amp; InlineStack)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcpseudoprobe-cpp">MCPseudoProbe.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a58dc840fc84420b7f0b773794b8101c1">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobe/#a80938ec88b3fed6ea902e4dbfc27b3f0">llvm::MCPseudoProbe::getGuid</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetreebase/#a51ca42102ea4b48abb9f061c7065aad6">llvm::MCPseudoProbeInlineTreeBase&lt; std::vector&lt; MCPseudoProbe &gt;, MCPseudoProbeInlineTree, std::unordered_map&lt; InlineSite, std::unique_ptr&lt; MCPseudoProbeInlineTree &gt;, InlineSiteHash &gt; &gt;::getOrAddNode</a> and <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetreebase/#a860c00c27d6bcd7c49fc067f03665e58">llvm::MCPseudoProbeInlineTreeBase&lt; std::vector&lt; MCPseudoProbe &gt;, MCPseudoProbeInlineTree, std::unordered_map&lt; InlineSite, std::unique_ptr&lt; MCPseudoProbeInlineTree &gt;, InlineSiteHash &gt; &gt;::isRoot</a>.</p>

</div>
</div>

### emit() {#a803da0fccbb98b7ceaf9240f55fa69b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCPseudoProbeInlineTree::emit (<a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer">MCObjectStreamer</a> * MCOS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobe">MCPseudoProbe</a> *&amp; LastProbe)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcpseudoprobe-cpp">MCPseudoProbe.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetreebase/#a3b56b39896707a38c4d1ecfef5131ba0">llvm::MCPseudoProbeInlineTreeBase&lt; std::vector&lt; MCPseudoProbe &gt;, MCPseudoProbeInlineTree, std::unordered_map&lt; InlineSite, std::unique_ptr&lt; MCPseudoProbeInlineTree &gt;, InlineSiteHash &gt; &gt;::Children</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobetable/#ad089579699154832e852448b566c2704">llvm::MCPseudoProbeTable::DdgPrintIndent</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobe/#a4fbe96db8448f1711fd51c4f4601c063">llvm::MCPseudoProbe::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac46413fa6b39176f78fc9621a08af7a5">llvm::MCStreamer::emitInt64</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#abc5f738b9471c3ed31b8f1fc7dc8e914">llvm::MCStreamer::emitULEB128IntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobebase/#a7406e132355fb05ec16185d804e04b73">llvm::MCPseudoProbeBase::getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobe/#a80938ec88b3fed6ea902e4dbfc27b3f0">llvm::MCPseudoProbe::getGuid</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetreebase/#a1494be26ea72fa903ec2ac8b29dd1154">llvm::MCPseudoProbeInlineTreeBase&lt; std::vector&lt; MCPseudoProbe &gt;, MCPseudoProbeInlineTree, std::unordered_map&lt; InlineSite, std::unique_ptr&lt; MCPseudoProbeInlineTree &gt;, InlineSiteHash &gt; &gt;::Guid</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetreebase/#a860c00c27d6bcd7c49fc067f03665e58">llvm::MCPseudoProbeInlineTreeBase&lt; std::vector&lt; MCPseudoProbe &gt;, MCPseudoProbeInlineTree, std::unordered_map&lt; InlineSite, std::unique_ptr&lt; MCPseudoProbeInlineTree &gt;, InlineSiteHash &gt; &gt;::isRoot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a192529d3a199cfe369f7428545340e76">llvm::isSentinelProbe</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetreebase/#a9c92b781cf94c0942f59a231c1111988">llvm::MCPseudoProbeInlineTreeBase&lt; std::vector&lt; MCPseudoProbe &gt;, MCPseudoProbeInlineTree, std::unordered_map&lt; InlineSite, std::unique_ptr&lt; MCPseudoProbeInlineTree &gt;, InlineSiteHash &gt; &gt;::Parent</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetreebase/#a9082efdbacc9d8c31bcd10f0cc7766ee">llvm::MCPseudoProbeInlineTreeBase&lt; std::vector&lt; MCPseudoProbe &gt;, MCPseudoProbeInlineTree, std::unordered_map&lt; InlineSite, std::unique_ptr&lt; MCPseudoProbeInlineTree &gt;, InlineSiteHash &gt; &gt;::Probes</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>

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
