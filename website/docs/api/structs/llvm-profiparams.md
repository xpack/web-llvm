---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/profiparams
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ProfiParams` Struct

<p>Various thresholds and options controlling the behavior of the profile inference algorithm. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::ProfiParams { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">llvm/Transforms/Utils/SampleProfileInference.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa5c8536542aef51080617f59b7a4756">EvenFlowDistribution</a> {false}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Evenly distribute flow when there are multiple equally likely options. <a href="#afa5c8536542aef51080617f59b7a4756">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a720bd9ea72871723cd4a8e413c40cf82">RebalanceUnknown</a> {false}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Evenly re-distribute flow among unknown subgraphs. <a href="#a720bd9ea72871723cd4a8e413c40cf82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97439d73a5716992c931f74c45485fda">JoinIslands</a> {false}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Join isolated components having positive flow. <a href="#a97439d73a5716992c931f74c45485fda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39401e9ddaa84e388f7114f9f3b77c7e">CostBlockInc</a> {0}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost of increasing a block's count by one. <a href="#a39401e9ddaa84e388f7114f9f3b77c7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcd8b45086bba7f4515e3e3d8fef41dc">CostBlockDec</a> {0}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost of decreasing a block's count by one. <a href="#adcd8b45086bba7f4515e3e3d8fef41dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e351546ca08436a0e7a7ccfa08f5495">CostBlockZeroInc</a> {0}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost of increasing a count of zero-weight block by one. <a href="#a9e351546ca08436a0e7a7ccfa08f5495">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af820f5e80ca4cd2a823d4dbd16714bc1">CostBlockEntryInc</a> {0}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost of increasing the entry block's count by one. <a href="#af820f5e80ca4cd2a823d4dbd16714bc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa7f2d292f152d77537be66c67cd2008">CostBlockEntryDec</a> {0}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost of decreasing the entry block's count by one. <a href="#aaa7f2d292f152d77537be66c67cd2008">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0fab235dca463ec9d48c5b6bfe9ccde">CostBlockUnknownInc</a> {0}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost of increasing an unknown block's count by one. <a href="#ad0fab235dca463ec9d48c5b6bfe9ccde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac04da42f4440b9ea85d4ae6400b4e8ce">CostJumpInc</a> {0}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost of increasing a jump's count by one. <a href="#ac04da42f4440b9ea85d4ae6400b4e8ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55e432c2b9b6e25f5a83f1d5ac7655b7">CostJumpFTInc</a> {0}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost of increasing a fall-through jump's count by one. <a href="#a55e432c2b9b6e25f5a83f1d5ac7655b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94bec6d7c1e0827854d72091aacf81f7">CostJumpDec</a> {0}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost of decreasing a jump's count by one. <a href="#a94bec6d7c1e0827854d72091aacf81f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb1dd7977642b5222b9fac44305f562e">CostJumpFTDec</a> {0}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost of decreasing a fall-through jump's count by one. <a href="#adb1dd7977642b5222b9fac44305f562e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acecc0d05ec41075cc30e0c9bbb0c20b9">CostJumpUnknownInc</a> {0}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost of increasing an unknown jump's count by one. <a href="#acecc0d05ec41075cc30e0c9bbb0c20b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aa4f0b714c6b54a55b97af255f6f62c">CostJumpUnknownFTInc</a> {0}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost of increasing an unknown fall-through jump's count by one. <a href="#a2aa4f0b714c6b54a55b97af255f6f62c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c360b59499f427030ac3969086b5cb8">CostUnlikely</a> = ((int64_t)1) &lt;&lt; 30</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost of taking an unlikely block/jump. <a href="#a8c360b59499f427030ac3969086b5cb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Various thresholds and options controlling the behavior of the profile inference algorithm.</p>


<p>Default values are tuned for several large-scale applications, and can be modified via corresponding command-line flags.</p>


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### CostBlockDec {#adcd8b45086bba7f4515e3e3d8fef41dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ProfiParams::CostBlockDec {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost of decreasing a block's count by one.</p>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a97df254bc8c63986dc57817f0f553de9">llvm::applyFlowInference</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#ad129e295efcd7c789b6c5d67124adef8">anonymous{SampleProfileInference.cpp}::assignBlockCosts</a>.</p>

</div>
</div>

### CostBlockEntryDec {#aaa7f2d292f152d77537be66c67cd2008}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ProfiParams::CostBlockEntryDec {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost of decreasing the entry block's count by one.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a97df254bc8c63986dc57817f0f553de9">llvm::applyFlowInference</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#ad129e295efcd7c789b6c5d67124adef8">anonymous{SampleProfileInference.cpp}::assignBlockCosts</a>.</p>

</div>
</div>

### CostBlockEntryInc {#af820f5e80ca4cd2a823d4dbd16714bc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ProfiParams::CostBlockEntryInc {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost of increasing the entry block's count by one.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a97df254bc8c63986dc57817f0f553de9">llvm::applyFlowInference</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#ad129e295efcd7c789b6c5d67124adef8">anonymous{SampleProfileInference.cpp}::assignBlockCosts</a>.</p>

</div>
</div>

### CostBlockInc {#a39401e9ddaa84e388f7114f9f3b77c7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ProfiParams::CostBlockInc {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost of increasing a block's count by one.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a97df254bc8c63986dc57817f0f553de9">llvm::applyFlowInference</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#ad129e295efcd7c789b6c5d67124adef8">anonymous{SampleProfileInference.cpp}::assignBlockCosts</a>.</p>

</div>
</div>

### CostBlockUnknownInc {#ad0fab235dca463ec9d48c5b6bfe9ccde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ProfiParams::CostBlockUnknownInc {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost of increasing an unknown block's count by one.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a97df254bc8c63986dc57817f0f553de9">llvm::applyFlowInference</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#ad129e295efcd7c789b6c5d67124adef8">anonymous{SampleProfileInference.cpp}::assignBlockCosts</a>.</p>

</div>
</div>

### CostBlockZeroInc {#a9e351546ca08436a0e7a7ccfa08f5495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ProfiParams::CostBlockZeroInc {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost of increasing a count of zero-weight block by one.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a97df254bc8c63986dc57817f0f553de9">llvm::applyFlowInference</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#ad129e295efcd7c789b6c5d67124adef8">anonymous{SampleProfileInference.cpp}::assignBlockCosts</a>.</p>

</div>
</div>

### CostJumpDec {#a94bec6d7c1e0827854d72091aacf81f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ProfiParams::CostJumpDec {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost of decreasing a jump's count by one.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a1ce5cbe1af8289db9c7121774c7ea192">anonymous{SampleProfileInference.cpp}::assignJumpCosts</a>.</p>

</div>
</div>

### CostJumpFTDec {#adb1dd7977642b5222b9fac44305f562e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ProfiParams::CostJumpFTDec {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost of decreasing a fall-through jump's count by one.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a1ce5cbe1af8289db9c7121774c7ea192">anonymous{SampleProfileInference.cpp}::assignJumpCosts</a>.</p>

</div>
</div>

### CostJumpFTInc {#a55e432c2b9b6e25f5a83f1d5ac7655b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ProfiParams::CostJumpFTInc {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost of increasing a fall-through jump's count by one.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a1ce5cbe1af8289db9c7121774c7ea192">anonymous{SampleProfileInference.cpp}::assignJumpCosts</a>.</p>

</div>
</div>

### CostJumpInc {#ac04da42f4440b9ea85d4ae6400b4e8ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ProfiParams::CostJumpInc {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost of increasing a jump's count by one.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a1ce5cbe1af8289db9c7121774c7ea192">anonymous{SampleProfileInference.cpp}::assignJumpCosts</a>.</p>

</div>
</div>

### CostJumpUnknownFTInc {#a2aa4f0b714c6b54a55b97af255f6f62c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ProfiParams::CostJumpUnknownFTInc {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost of increasing an unknown fall-through jump's count by one.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a1ce5cbe1af8289db9c7121774c7ea192">anonymous{SampleProfileInference.cpp}::assignJumpCosts</a>.</p>

</div>
</div>

### CostJumpUnknownInc {#acecc0d05ec41075cc30e0c9bbb0c20b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ProfiParams::CostJumpUnknownInc {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost of increasing an unknown jump's count by one.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a1ce5cbe1af8289db9c7121774c7ea192">anonymous{SampleProfileInference.cpp}::assignJumpCosts</a>.</p>

</div>
</div>

### CostUnlikely {#a8c360b59499f427030ac3969086b5cb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int64_t llvm::ProfiParams::CostUnlikely = ((int64_t)1) &lt;&lt; 30</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost of taking an unlikely block/jump.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#ad129e295efcd7c789b6c5d67124adef8">anonymous{SampleProfileInference.cpp}::assignBlockCosts</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a1ce5cbe1af8289db9c7121774c7ea192">anonymous{SampleProfileInference.cpp}::assignJumpCosts</a>.</p>

</div>
</div>

### EvenFlowDistribution {#afa5c8536542aef51080617f59b7a4756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfiParams::EvenFlowDistribution {false}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Evenly distribute flow when there are multiple equally likely options.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a97df254bc8c63986dc57817f0f553de9">llvm::applyFlowInference</a>.</p>

</div>
</div>

### JoinIslands {#a97439d73a5716992c931f74c45485fda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfiParams::JoinIslands {false}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Join isolated components having positive flow.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a97df254bc8c63986dc57817f0f553de9">llvm::applyFlowInference</a>.</p>

</div>
</div>

### RebalanceUnknown {#a720bd9ea72871723cd4a8e413c40cf82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfiParams::RebalanceUnknown {false}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Evenly re-distribute flow among unknown subgraphs.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a97df254bc8c63986dc57817f0f553de9">llvm::applyFlowInference</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileinference-h">SampleProfileInference.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
