---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jitlink/ehframeedgefixer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `EHFrameEdgeFixer` Class Reference

<p>A <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> pass that adds missing FDE-to-CIE, FDE-to-PC and FDE-to-LSDA edges. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::jitlink::EHFrameEdgeFixer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupportimpl-h">ExecutionEngine/JITLink/EHFrameSupportImpl.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accefeee46f154819e460051b2b7f314e">CIEInfosMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">orc::ExecutorAddr</a>, CIEInformation &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac454f1b37ee399349874df2e004fbce3">EHFrameEdgeFixer</a> (StringRef EHFrameSectionName, unsigned PointerSize, Edge::Kind Pointer32, Edge::Kind Pointer64, Edge::Kind Delta32, Edge::Kind Delta64, Edge::Kind NegDelta32)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an eh-frame edge fixer. <a href="#ac454f1b37ee399349874df2e004fbce3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2125616450a5d6ec41ab7f8f66abe40e">operator()</a> (LinkGraph &amp;G)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae31c4e10945c2e57f8d81ea0bb078229">processBlock</a> (ParseContext &amp;PC, Block &amp;B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad856d03139ee1eb0f6fe5002de5ca178">processCIE</a> (ParseContext &amp;PC, Block &amp;B, size_t CIEDeltaFieldOffset, const BlockEdgesInfo &amp;BlockEdges)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae40c020fa1bfed9f53ce79c8fb71c453">processFDE</a> (ParseContext &amp;PC, Block &amp;B, size_t CIEDeltaFieldOffset, uint32_t CIEDelta, const BlockEdgesInfo &amp;BlockEdges)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; AugmentationInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c91e5f67e600b6bed3e2f0bb909963c">parseAugmentationString</a> (BinaryStreamReader &amp;RecordReader)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba4b173fb17dc3a0dc2669ab621b917d">readPointerEncoding</a> (BinaryStreamReader &amp;RecordReader, Block &amp;InBlock, const char *FieldName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa94e4f358989fc6131c29c2ee2c8f497">skipEncodedPointer</a> (uint8_t PointerEncoding, BinaryStreamReader &amp;RecordReader)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada83eb8dfd777eb22ba0cdc7f38ca25e">getOrCreateEncodedPointerEdge</a> (ParseContext &amp;PC, const BlockEdgesInfo &amp;BlockEdges, uint8_t PointerEncoding, BinaryStreamReader &amp;RecordReader, Block &amp;BlockToFix, size_t PointerFieldOffset, const char *FieldName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a146f3d72267a3803c69bdf9dc9109cfe">getOrCreateSymbol</a> (ParseContext &amp;PC, orc::ExecutorAddr Addr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47db16f990100a10e267729c8f119799">EHFrameSectionName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd947a4ca896323d74cf4cbfec6a7735">PointerSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab04bffbf273dc61b415087cea684f00">Pointer32</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ce869a284af07d243dae79847c2b9a1">Pointer64</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dd297cad8bcc30fce52e018cd7c7f6a">Delta32</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b30e4395439c9277a95b65aae8c6bf3">Delta64</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a756511ef0b4924bbae66b8b73f96bae0">NegDelta32</a></td>
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

## Description {#details}

<p>A <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> pass that adds missing FDE-to-CIE, FDE-to-PC and FDE-to-LSDA edges.</p>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupportimpl-h">EHFrameSupportImpl.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### CIEInfosMap {#accefeee46f154819e460051b2b7f314e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::jitlink::EHFrameEdgeFixer::CIEInfosMap =  DenseMap&lt;orc::ExecutorAddr, CIEInformation&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupportimpl-h">EHFrameSupportImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### EHFrameEdgeFixer() {#ac454f1b37ee399349874df2e004fbce3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::EHFrameEdgeFixer::EHFrameEdgeFixer (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> EHFrameSectionName, unsigned PointerSize, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> Pointer32, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> Pointer64, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> Delta32, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> Delta64, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> NegDelta32)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an eh-frame edge fixer.</p>


<p>Adds edges for implicit relocations on platforms where these are used (e.g. MachO/x86-64).</p>


<p>If a given edge-kind is not supported on the target architecture then <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#aa21629cef4aed37ffc47ef8681c46a99a5ac566a913119de4e29b016756ce6e9f">Edge::Invalid</a> should be used.</p>


<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupportimpl-h">EHFrameSupportImpl.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupport-cpp">EHFrameSupport.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator()() {#a2125616450a5d6ec41ab7f8f66abe40e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::EHFrameEdgeFixer::operator() (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupportimpl-h">EHFrameSupportImpl.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupport-cpp">EHFrameSupport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/blockaddressmap/#aff214877c0358ef38320cffd1dc7dce2">llvm::jitlink::BlockAddressMap::includeNonNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getOrCreateEncodedPointerEdge() {#ada83eb8dfd777eb22ba0cdc7f38ca25e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; Symbol * &gt; llvm::jitlink::EHFrameEdgeFixer::getOrCreateEncodedPointerEdge (ParseContext &amp; PC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BlockEdgesInfo &amp; BlockEdges, uint8_t PointerEncoding, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader">BinaryStreamReader</a> &amp; RecordReader, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; BlockToFix, size_t PointerFieldOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * FieldName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupportimpl-h">EHFrameSupportImpl.h</a>, definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupport-cpp">EHFrameSupport.cpp</a>.</p>

</div>
</div>

### getOrCreateSymbol() {#a146f3d72267a3803c69bdf9dc9109cfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; Symbol &amp; &gt; llvm::jitlink::EHFrameEdgeFixer::getOrCreateSymbol (ParseContext &amp; PC, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">orc::ExecutorAddr</a> Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupportimpl-h">EHFrameSupportImpl.h</a>, definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupport-cpp">EHFrameSupport.cpp</a>.</p>

</div>
</div>

### parseAugmentationString() {#a3c91e5f67e600b6bed3e2f0bb909963c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; EHFrameEdgeFixer::AugmentationInfo &gt; llvm::jitlink::EHFrameEdgeFixer::parseAugmentationString (<a href="/web-llvm/docs/api/classes/llvm/binarystreamreader">BinaryStreamReader</a> &amp; RecordReader)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupportimpl-h">EHFrameSupportImpl.h</a>, definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupport-cpp">EHFrameSupport.cpp</a>.</p>

</div>
</div>

### processBlock() {#ae31c4e10945c2e57f8d81ea0bb078229}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::EHFrameEdgeFixer::processBlock (ParseContext &amp; PC, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupportimpl-h">EHFrameSupportImpl.h</a>, definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupport-cpp">EHFrameSupport.cpp</a>.</p>

</div>
</div>

### processCIE() {#ad856d03139ee1eb0f6fe5002de5ca178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::EHFrameEdgeFixer::processCIE (ParseContext &amp; PC, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B, size_t CIEDeltaFieldOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BlockEdgesInfo &amp; BlockEdges)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupportimpl-h">EHFrameSupportImpl.h</a>, definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupport-cpp">EHFrameSupport.cpp</a>.</p>

</div>
</div>

### processFDE() {#ae40c020fa1bfed9f53ce79c8fb71c453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::EHFrameEdgeFixer::processFDE (ParseContext &amp; PC, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B, size_t CIEDeltaFieldOffset, uint32_t CIEDelta, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BlockEdgesInfo &amp; BlockEdges)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupportimpl-h">EHFrameSupportImpl.h</a>, definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupport-cpp">EHFrameSupport.cpp</a>.</p>

</div>
</div>

### readPointerEncoding() {#aba4b173fb17dc3a0dc2669ab621b917d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint8_t &gt; llvm::jitlink::EHFrameEdgeFixer::readPointerEncoding (<a href="/web-llvm/docs/api/classes/llvm/binarystreamreader">BinaryStreamReader</a> &amp; RecordReader, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; InBlock, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * FieldName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupportimpl-h">EHFrameSupportImpl.h</a>, definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupport-cpp">EHFrameSupport.cpp</a>.</p>

</div>
</div>

### skipEncodedPointer() {#aa94e4f358989fc6131c29c2ee2c8f497}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::EHFrameEdgeFixer::skipEncodedPointer (uint8_t PointerEncoding, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader">BinaryStreamReader</a> &amp; RecordReader)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupportimpl-h">EHFrameSupportImpl.h</a>, definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupport-cpp">EHFrameSupport.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Delta32 {#a7dd297cad8bcc30fce52e018cd7c7f6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Edge::Kind llvm::jitlink::EHFrameEdgeFixer::Delta32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupportimpl-h">EHFrameSupportImpl.h</a>.</p>

</div>
</div>

### Delta64 {#a6b30e4395439c9277a95b65aae8c6bf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Edge::Kind llvm::jitlink::EHFrameEdgeFixer::Delta64</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupportimpl-h">EHFrameSupportImpl.h</a>.</p>

</div>
</div>

### EHFrameSectionName {#a47db16f990100a10e267729c8f119799}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::jitlink::EHFrameEdgeFixer::EHFrameSectionName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupportimpl-h">EHFrameSupportImpl.h</a>.</p>

</div>
</div>

### NegDelta32 {#a756511ef0b4924bbae66b8b73f96bae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Edge::Kind llvm::jitlink::EHFrameEdgeFixer::NegDelta32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupportimpl-h">EHFrameSupportImpl.h</a>.</p>

</div>
</div>

### Pointer32 {#aab04bffbf273dc61b415087cea684f00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Edge::Kind llvm::jitlink::EHFrameEdgeFixer::Pointer32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupportimpl-h">EHFrameSupportImpl.h</a>.</p>

</div>
</div>

### Pointer64 {#a8ce869a284af07d243dae79847c2b9a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Edge::Kind llvm::jitlink::EHFrameEdgeFixer::Pointer64</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupportimpl-h">EHFrameSupportImpl.h</a>.</p>

</div>
</div>

### PointerSize {#acd947a4ca896323d74cf4cbfec6a7735}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::jitlink::EHFrameEdgeFixer::PointerSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupportimpl-h">EHFrameSupportImpl.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupport-cpp">EHFrameSupport.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupportimpl-h">EHFrameSupportImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
