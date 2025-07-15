---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jitlink/inprocessehframeregistrar
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InProcessEHFrameRegistrar` Class Reference

<p>Registers / Deregisters EH-frames in the current process. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::jitlink::InProcessEHFrameRegistrar { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ehframesupport-h">llvm/ExecutionEngine/JITLink/EHFrameSupport.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/ehframeregistrar">EHFrameRegistrar</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Supports registration/deregistration of EH-frames in a target process. <a href="/web-llvm/docs/api/classes/llvm/jitlink/ehframeregistrar/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dcccb2fcb683beab5ac825632b53438">registerEHFrames</a> (orc::ExecutorAddrRange EHFrameSection) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68566ad4088e1e9c966c4ed85fcd92d0">deregisterEHFrames</a> (orc::ExecutorAddrRange EHFrameSection) override</td>
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

<p>Registers / Deregisters EH-frames in the current process.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ehframesupport-h">EHFrameSupport.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### deregisterEHFrames() {#a68566ad4088e1e9c966c4ed85fcd92d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::InProcessEHFrameRegistrar::deregisterEHFrames (<a href="/web-llvm/docs/api/structs/llvm/orc/executoraddrrange">orc::ExecutorAddrRange</a> EHFrameSection)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ehframesupport-h">EHFrameSupport.h</a>, definition at line 650 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupport-cpp">EHFrameSupport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a47b18dc034063799b5233506f3345f1e">llvm::orc::deregisterEHFrameSection</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/executoraddrrange/#aad27b268dbe68646bb2fd5e46a4527ba">llvm::orc::ExecutorAddrRange::size</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/executoraddrrange/#a3bdf4fc0018782943ace850c8aeaaa69">llvm::orc::ExecutorAddrRange::Start</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#af5df5d5fa49d180d3ca3de567f60de79">llvm::orc::ExecutorAddr::toPtr</a>.</p>

</div>
</div>

### registerEHFrames() {#a3dcccb2fcb683beab5ac825632b53438}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::InProcessEHFrameRegistrar::registerEHFrames (<a href="/web-llvm/docs/api/structs/llvm/orc/executoraddrrange">orc::ExecutorAddrRange</a> EHFrameSection)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/ehframesupport-h">EHFrameSupport.h</a>, definition at line 644 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/ehframesupport-cpp">EHFrameSupport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a52ae7001a942738095c0a5e25d45d386">llvm::orc::registerEHFrameSection</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/executoraddrrange/#aad27b268dbe68646bb2fd5e46a4527ba">llvm::orc::ExecutorAddrRange::size</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/executoraddrrange/#a3bdf4fc0018782943ace850c8aeaaa69">llvm::orc::ExecutorAddrRange::Start</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#af5df5d5fa49d180d3ca3de567f60de79">llvm::orc::ExecutorAddr::toPtr</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
