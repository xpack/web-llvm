---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-epcindirectionutils-cpp-/epctrampolinepool
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `EPCTrampolinePool` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{EPCIndirectionUtils.cpp}::EPCTrampolinePool { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/trampolinepool">TrampolinePool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for pools of compiler re-entry trampolines. <a href="/web-llvm/docs/api/classes/llvm/orc/trampolinepool/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dffdcb9c7d546a451035d7d7c89776f">FinalizedAlloc</a> = <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/finalizedalloc">jitlink::JITLinkMemoryManager::FinalizedAlloc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54c94aaae3536bdb6268c18fe636cf58">EPCTrampolinePool</a> (EPCIndirectionUtils &amp;EPCIU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b22630ec318143fede9067eef972d5e">deallocatePool</a> ()</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4fec54475a3bf31eae752ec59f85ff1">grow</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutils">EPCIndirectionUtils</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52ba200905b253b6511e874d0c0fdb85">EPCIU</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad01de10ddda925a1644e9ff88af67a8a">TrampolineSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f3f0a1c2c56dc90959cf978ba097279">TrampolinesPerPage</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="#a4dffdcb9c7d546a451035d7d7c89776f">FinalizedAlloc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7c3c4a5cc47efd26aa7b2dfc6338261">TrampolineBlocks</a></td>
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


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### FinalizedAlloc {#a4dffdcb9c7d546a451035d7d7c89776f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{EPCIndirectionUtils.cpp}::EPCTrampolinePool::FinalizedAlloc =  jitlink::JITLinkMemoryManager::FinalizedAlloc</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### EPCTrampolinePool() {#a54c94aaae3536bdb6268c18fe636cf58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{EPCIndirectionUtils.cpp}::EPCTrampolinePool::EPCTrampolinePool (<a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutils">EPCIndirectionUtils</a> &amp; EPCIU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<p>References <a href="#a52ba200905b253b6511e874d0c0fdb85">EPCIU</a>, <a href="#ad01de10ddda925a1644e9ff88af67a8a">TrampolineSize</a> and <a href="#a8f3f0a1c2c56dc90959cf978ba097279">TrampolinesPerPage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### deallocatePool() {#a8b22630ec318143fede9067eef972d5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{EPCIndirectionUtils.cpp}::EPCTrampolinePool::deallocatePool ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<p>References <a href="#a52ba200905b253b6511e874d0c0fdb85">EPCIU</a> and <a href="#ab7c3c4a5cc47efd26aa7b2dfc6338261">TrampolineBlocks</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### grow() {#af4fec54475a3bf31eae752ec59f85ff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{EPCIndirectionUtils.cpp}::EPCTrampolinePool::grow ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/trampolinepool/#a21e470ebe990337ac5917986ae91c5a6">llvm::orc::TrampolinePool::AvailableTrampolines</a>, <a href="#a52ba200905b253b6511e874d0c0fdb85">EPCIU</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp/#a90146d35673da9e3e4a7f41f3b8c9b7e">PageSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### EPCIU {#a52ba200905b253b6511e874d0c0fdb85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EPCIndirectionUtils&amp; anonymous{EPCIndirectionUtils.cpp}::EPCTrampolinePool::EPCIU</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<p>Referenced by <a href="#a8b22630ec318143fede9067eef972d5e">deallocatePool</a>, <a href="#a54c94aaae3536bdb6268c18fe636cf58">EPCTrampolinePool</a> and <a href="#af4fec54475a3bf31eae752ec59f85ff1">grow</a>.</p>

</div>
</div>

### TrampolineBlocks {#ab7c3c4a5cc47efd26aa7b2dfc6338261}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;FinalizedAlloc&gt; anonymous{EPCIndirectionUtils.cpp}::EPCTrampolinePool::TrampolineBlocks</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<p>Referenced by <a href="#a8b22630ec318143fede9067eef972d5e">deallocatePool</a>.</p>

</div>
</div>

### TrampolineSize {#ad01de10ddda925a1644e9ff88af67a8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{EPCIndirectionUtils.cpp}::EPCTrampolinePool::TrampolineSize = 0</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<p>Referenced by <a href="#a54c94aaae3536bdb6268c18fe636cf58">EPCTrampolinePool</a>.</p>

</div>
</div>

### TrampolinesPerPage {#a8f3f0a1c2c56dc90959cf978ba097279}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{EPCIndirectionUtils.cpp}::EPCTrampolinePool::TrampolinesPerPage = 0</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<p>Referenced by <a href="#a54c94aaae3536bdb6268c18fe636cf58">EPCTrampolinePool</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
