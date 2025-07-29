---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jitlink/tablemanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TableManager` Class Template

<p>A CRTP base for tables that are built on demand, e.g. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename TableManagerImplT&gt;
class llvm::jitlink::TableManager&lt;TableManagerImplT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/tablemanager-h">llvm/ExecutionEngine/JITLink/TableManager.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename TableManagerImplT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa7e3f0047da154572ebef76ceee273d3">getEntryForTarget</a> (LinkGraph &amp;G, Symbol &amp;Target)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the constructed entry. <a href="#aa7e3f0047da154572ebef76ceee273d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename TableManagerImplT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ace7f4ad413507742c3a483f951e357cf">registerPreExistingEntry</a> (Symbol &amp;Target, Symbol &amp;Entry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a pre-existing entry. <a href="#ace7f4ad413507742c3a483f951e357cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename TableManagerImplT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">TableManagerImplT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aede4e77975dad7b8a65fe3ac715931e9">impl</a> ()</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename TableManagerImplT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">orc::SymbolStringPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> * &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3a5e0e815dbe1ec53efb446c174cf745">Entries</a></td>
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

<p>A CRTP base for tables that are built on demand, e.g.</p>


<p>Global Offset Tables and Procedure <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55f">Linkage</a> Tables. The getEntyrForTarget function returns the table entry corresponding to the given target, calling down to the implementation class to build an entry if one does not already exist.</p>


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/tablemanager-h">TableManager.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getEntryForTarget() {#aa7e3f0047da154572ebef76ceee273d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename TableManagerImplT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; llvm::jitlink::TableManager&lt; TableManagerImplT &gt;::getEntryForTarget (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; Target)</td>
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

<p>Return the constructed entry.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> parameter G to construct the entry for target symbol</p>


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/tablemanager-h">TableManager.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a3fcdc9f30e5e8b9ea4da99868a8ae4a9">DEBUG_WITH_TYPE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a30cdafd656830b62aa8070242810c405">llvm::Target::getName</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#abd1ccb1bf511e1965414eb1d2e137302">impl</a>.</p>

</div>
</div>

### registerPreExistingEntry() {#ace7f4ad413507742c3a483f951e357cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename TableManagerImplT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::TableManager&lt; TableManagerImplT &gt;::registerPreExistingEntry (<a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; Target, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; Entry)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a pre-existing entry.</p>


<p>Objects may include pre-existing table entries (e.g. for GOTs). This method can be used to register those entries so that they will not be duplicated by createEntry the first time that getEntryForTarget is called.</p>


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/tablemanager-h">TableManager.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/target/#a30cdafd656830b62aa8070242810c405">llvm::Target::getName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### impl() {#aede4e77975dad7b8a65fe3ac715931e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename TableManagerImplT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TableManagerImplT &amp; llvm::jitlink::TableManager&lt; TableManagerImplT &gt;::impl ()</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/tablemanager-h">TableManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Entries {#a3a5e0e815dbe1ec53efb446c174cf745}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename TableManagerImplT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;orc::SymbolStringPtr, Symbol *&gt; llvm::jitlink::TableManager&lt; TableManagerImplT &gt;::Entries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/tablemanager-h">TableManager.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/tablemanager-h">TableManager.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
