---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/debuginfodserver
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DebuginfodServer` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::DebuginfodServer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">llvm/Debuginfod/Debuginfod.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a146c3973caa3e8f160a781b1fa91b248">DebuginfodServer</a> (DebuginfodLog &amp;Log, DebuginfodCollection &amp;Collection)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/httpserver">HTTPServer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97ffd636d8a6f0ab272d3f6dca95c8e4">Server</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debuginfodlog">DebuginfodLog</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a083908fd874987f211ff7f59b522a468">Log</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debuginfodcollection">DebuginfodCollection</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bd6b45a05358a6be5bb3f0a5f2adc62">Collection</a></td>
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


<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DebuginfodServer() {#a146c3973caa3e8f160a781b1fa91b248}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DebuginfodServer::DebuginfodServer (<a href="/web-llvm/docs/api/classes/llvm/debuginfodlog">DebuginfodLog</a> &amp; Log, <a href="/web-llvm/docs/api/classes/llvm/debuginfodcollection">DebuginfodCollection</a> &amp; Collection)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>, definition at line 558 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfod/debuginfod-cpp">Debuginfod.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="#a8bd6b45a05358a6be5bb3f0a5f2adc62">Collection</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="#a083908fd874987f211ff7f59b522a468">Log</a> and <a href="#a97ffd636d8a6f0ab272d3f6dca95c8e4">Server</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Collection {#a8bd6b45a05358a6be5bb3f0a5f2adc62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebuginfodCollection&amp; llvm::DebuginfodServer::Collection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>.</p>


<p>Referenced by <a href="#a146c3973caa3e8f160a781b1fa91b248">DebuginfodServer</a>.</p>

</div>
</div>

### Log {#a083908fd874987f211ff7f59b522a468}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebuginfodLog&amp; llvm::DebuginfodServer::Log</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>.</p>


<p>Referenced by <a href="#a146c3973caa3e8f160a781b1fa91b248">DebuginfodServer</a>.</p>

</div>
</div>

### Server {#a97ffd636d8a6f0ab272d3f6dca95c8e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HTTPServer llvm::DebuginfodServer::Server</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a>.</p>


<p>Referenced by <a href="#a146c3973caa3e8f160a781b1fa91b248">DebuginfodServer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfod/debuginfod-h">Debuginfod.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfod/debuginfod-cpp">Debuginfod.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
