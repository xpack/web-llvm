---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jitlink/ehframecfiblockinspector
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `EHFrameCFIBlockInspector` Class

<p>Inspect an eh-frame CFI record. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::jitlink::EHFrameCFIBlockInspector { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ehframesupport-h">llvm/ExecutionEngine/JITLink/EHFrameSupport.h</a>"
</div>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac50f75bb2aa61afc786de8c7f44acd04">EHFrameCFIBlockInspector</a> (Edge *PersonalityEdge)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a264795a8e9a34f8589b0ed3316167ca5">EHFrameCFIBlockInspector</a> (Edge &amp;CIEEdge, Edge &amp;PCBeginEdge, Edge *LSDAEdge)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac10e058969be40f8f634bd1783e5b1e5">isFDE</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this frame is an FDE, false for a CIE. <a href="#ac10e058969be40f8f634bd1783e5b1e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5209b3defc29c58a86d0f6731d3f20b7">isCIE</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this frame is a CIE, false for an FDE. <a href="#a5209b3defc29c58a86d0f6731d3f20b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a9aed8bcac31d30ce314b92154192c6">getPersonalityEdge</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a CIE record, returns the <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> pointing at the personality function, if any. <a href="#a6a9aed8bcac31d30ce314b92154192c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0050eb40337a9d7bd84bcf7f406af89a">getCIEEdge</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is an FDE record, returns the <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> pointing to the CIE. <a href="#a0050eb40337a9d7bd84bcf7f406af89a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06ca0b76a20d6fb25263443f0c2a4392">getPCBeginEdge</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is an FDE record, returns the <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> pointing at the PC-begin symbol. <a href="#a06ca0b76a20d6fb25263443f0c2a4392">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a115cfbeeb2139bc55cd63ee477504486">getLSDAEdge</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is an FDE record, returns the <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> pointing at the LSDA, if any. <a href="#a115cfbeeb2139bc55cd63ee477504486">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a607339cf573f4f14cfd193b6348e7325">PersonalityEdge</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43833981f76107df58ae297315a093c0">LSDAEdge</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a662315363b8da7aa71b07661ed9e5b73">CIEEdge</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea36ffbe482f4cd022f2383bbeabad4b">PCBeginEdge</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/jitlink/ehframecfiblockinspector">llvm::jitlink::EHFrameCFIBlockInspector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb32716ded440478757a1fa4adcc559f"></a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/jitlink/ehframecfiblockinspector">EHFrameCFIBlockInspector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad58e7c9140c2bee787d0e5f8f253af89">FromEdgeScan</a> (Block &amp;B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identify CFI record type and edges based on number and order of edges in the given block only. <a href="#ad58e7c9140c2bee787d0e5f8f253af89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Inspect an eh-frame CFI record.</p>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ehframesupport-h">EHFrameSupport.h</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### EHFrameCFIBlockInspector() {#ac50f75bb2aa61afc786de8c7f44acd04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::EHFrameCFIBlockInspector::EHFrameCFIBlockInspector (<a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> * PersonalityEdge)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ehframesupport-h">EHFrameSupport.h</a>, definition at line 673 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupport-cpp">EHFrameSupport.cpp</a>.</p>

</div>
</div>

### EHFrameCFIBlockInspector() {#a264795a8e9a34f8589b0ed3316167ca5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::EHFrameCFIBlockInspector::EHFrameCFIBlockInspector (<a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; CIEEdge, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; PCBeginEdge, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> * LSDAEdge)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ehframesupport-h">EHFrameSupport.h</a>, definition at line 676 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupport-cpp">EHFrameSupport.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCIEEdge() {#a0050eb40337a9d7bd84bcf7f406af89a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Edge * llvm::jitlink::EHFrameCFIBlockInspector::getCIEEdge ()</td>
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

<p>If this is an FDE record, returns the <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> pointing to the CIE.</p>


<p>If this is a CIE record, returns null.</p>


<p>The result is not valid if any modification has been made to the block after parsing.</p>


<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ehframesupport-h">EHFrameSupport.h</a>.</p>

</div>
</div>

### getLSDAEdge() {#a115cfbeeb2139bc55cd63ee477504486}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Edge * llvm::jitlink::EHFrameCFIBlockInspector::getLSDAEdge ()</td>
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

<p>If this is an FDE record, returns the <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> pointing at the LSDA, if any.</p>


<p>It is illegal to call this method on CIE records.</p>


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ehframesupport-h">EHFrameSupport.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac10e058969be40f8f634bd1783e5b1e5">isFDE</a> and <a href="#a43833981f76107df58ae297315a093c0">LSDAEdge</a>.</p>

</div>
</div>

### getPCBeginEdge() {#a06ca0b76a20d6fb25263443f0c2a4392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Edge * llvm::jitlink::EHFrameCFIBlockInspector::getPCBeginEdge ()</td>
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

<p>If this is an FDE record, returns the <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> pointing at the PC-begin symbol.</p>


<p>If this a CIE record, returns null.</p>


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ehframesupport-h">EHFrameSupport.h</a>.</p>

</div>
</div>

### getPersonalityEdge() {#a6a9aed8bcac31d30ce314b92154192c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Edge * llvm::jitlink::EHFrameCFIBlockInspector::getPersonalityEdge ()</td>
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

<p>If this is a CIE record, returns the <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> pointing at the personality function, if any.</p>


<p>It is illegal to call this method on FDE records.</p>


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ehframesupport-h">EHFrameSupport.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5209b3defc29c58a86d0f6731d3f20b7">isCIE</a> and <a href="#a607339cf573f4f14cfd193b6348e7325">PersonalityEdge</a>.</p>

</div>
</div>

### isCIE() {#a5209b3defc29c58a86d0f6731d3f20b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::EHFrameCFIBlockInspector::isCIE ()</td>
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

<p>Returns true if this frame is a CIE, false for an FDE.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ehframesupport-h">EHFrameSupport.h</a>.</p>


<p>Referenced by <a href="#a6a9aed8bcac31d30ce314b92154192c6">getPersonalityEdge</a>.</p>

</div>
</div>

### isFDE() {#ac10e058969be40f8f634bd1783e5b1e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::EHFrameCFIBlockInspector::isFDE ()</td>
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

<p>Returns true if this frame is an FDE, false for a CIE.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ehframesupport-h">EHFrameSupport.h</a>.</p>


<p>Referenced by <a href="#a115cfbeeb2139bc55cd63ee477504486">getLSDAEdge</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### LSDAEdge {#a43833981f76107df58ae297315a093c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Edge* llvm::jitlink::EHFrameCFIBlockInspector::LSDAEdge</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ehframesupport-h">EHFrameSupport.h</a>.</p>


<p>Referenced by <a href="#a115cfbeeb2139bc55cd63ee477504486">getLSDAEdge</a>.</p>

</div>
</div>

### PersonalityEdge {#a607339cf573f4f14cfd193b6348e7325}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Edge* llvm::jitlink::EHFrameCFIBlockInspector::PersonalityEdge</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ehframesupport-h">EHFrameSupport.h</a>.</p>


<p>Referenced by <a href="#a6a9aed8bcac31d30ce314b92154192c6">getPersonalityEdge</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#afb32716ded440478757a1fa4adcc559f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::jitlink::EHFrameCFIBlockInspector llvm::jitlink::EHFrameCFIBlockInspector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ehframesupport-h">EHFrameSupport.h</a>.</p>

</div>
</div>

### CIEEdge {#a662315363b8da7aa71b07661ed9e5b73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Edge* llvm::jitlink::EHFrameCFIBlockInspector::CIEEdge = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ehframesupport-h">EHFrameSupport.h</a>.</p>

</div>
</div>

### PCBeginEdge {#aea36ffbe482f4cd022f2383bbeabad4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Edge* llvm::jitlink::EHFrameCFIBlockInspector::PCBeginEdge = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ehframesupport-h">EHFrameSupport.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### FromEdgeScan() {#ad58e7c9140c2bee787d0e5f8f253af89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EHFrameCFIBlockInspector llvm::jitlink::EHFrameCFIBlockInspector::FromEdgeScan (<a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B)</td>
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

<p>Identify CFI record type and edges based on number and order of edges in the given block only.</p>


<p>This assumes that the block contains one CFI record that has already been split out and fixed by the DWARFRecordSplitter and <a href="/web-llvm/docs/api/classes/llvm/jitlink/ehframeedgefixer">EHFrameEdgeFixer</a> passes.</p>


<p>Zero or one outgoing edges: <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> is CIE. If present, edge points to personality.</p>


<p>Two or three outgoing edges: <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> is an FDE. First edge points to CIE, second to PC-begin, third (if present) to LSDA.</p>


<p>It is illegal to call this function on a block with four or more edges.</p>


<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ehframesupport-h">EHFrameSupport.h</a>, definition at line 656 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupport-cpp">EHFrameSupport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ehframesupport-h">EHFrameSupport.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupport-cpp">EHFrameSupport.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
