---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-rtdyldobjectlinkinglayer-cpp-/jitdylibsearchorderresolver
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `JITDylibSearchOrderResolver` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{RTDyldObjectLinkingLayer.cpp}::JITDylibSearchOrderResolver { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitsymbolresolver">JITSymbolResolver</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Symbol resolution interface. <a href="/web-llvm/docs/api/classes/llvm/jitsymbolresolver/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee8d7b22d1e7f5eb38487b6c7c74c3f">JITDylibSearchOrderResolver</a> (MaterializationResponsibility &amp;MR, SymbolDependenceMap &amp;Deps)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab649667397cd3a3ae6a5b4803c0eeb65">lookup</a> (const LookupSet &amp;Symbols, OnResolvedFunction OnResolved) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the fully resolved address and flags for each of the given symbols. <a href="#ab649667397cd3a3ae6a5b4803c0eeb65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/jitsymbolresolver/#a487abfdc466598f156d5398ae986c6f9">LookupSet</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bff67d8f1010e79d422184b4efc42ee">getResponsibilitySet</a> (const LookupSet &amp;Symbols) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the subset of the given symbols that should be materialized by the caller. <a href="#a8bff67d8f1010e79d422184b4efc42ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec1f6977110915c474735fd889ae426d">MR</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#ad4c600dd1184757dace1280e114f5b15">SymbolDependenceMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2f2e971a841b5aae7452cf1d6579f1a">Deps</a></td>
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


<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/rtdyldobjectlinkinglayer-cpp">RTDyldObjectLinkingLayer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### JITDylibSearchOrderResolver() {#a7ee8d7b22d1e7f5eb38487b6c7c74c3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RTDyldObjectLinkingLayer.cpp}::JITDylibSearchOrderResolver::JITDylibSearchOrderResolver (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ad4c600dd1184757dace1280e114f5b15">SymbolDependenceMap</a> &amp; Deps)</td>
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



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/rtdyldobjectlinkinglayer-cpp">RTDyldObjectLinkingLayer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getResponsibilitySet() {#a8bff67d8f1010e79d422184b4efc42ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; LookupSet &gt; anonymous{RTDyldObjectLinkingLayer.cpp}::JITDylibSearchOrderResolver::getResponsibilitySet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitsymbolresolver/#a487abfdc466598f156d5398ae986c6f9">LookupSet</a> &amp; Symbols)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the subset of the given symbols that should be materialized by the caller.</p>


<p>Only weak/common symbols should be looked up, as strong definitions are implicitly always part of the caller's responsibility.</p>


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/rtdyldobjectlinkinglayer-cpp">RTDyldObjectLinkingLayer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>.</p>

</div>
</div>

### lookup() {#ab649667397cd3a3ae6a5b4803c0eeb65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RTDyldObjectLinkingLayer.cpp}::JITDylibSearchOrderResolver::lookup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitsymbolresolver/#a487abfdc466598f156d5398ae986c6f9">LookupSet</a> &amp; Symbols, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolresolver/#a01f534cbe65344148ec2986691ff632a">OnResolvedFunction</a> OnResolved)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the fully resolved address and flags for each of the given symbols.</p>


<p>This method will return an error if any of the given symbols can not be resolved, or if the resolution process itself triggers an error.</p>


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/rtdyldobjectlinkinglayer-cpp">RTDyldObjectLinkingLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset/#a6542a1b1d7b2b32faca7cc49c8d167e0">llvm::orc::SymbolLookupSet::add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adac25fca9fb14b1defe43d18a81c16e8af691f042a559b1c1a4f89826c6f75760">llvm::orc::Resolved</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eba84a8921b25f505d0d2077aeb5db4bc16">llvm::orc::Static</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Deps {#aa2f2e971a841b5aae7452cf1d6579f1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolDependenceMap&amp; anonymous{RTDyldObjectLinkingLayer.cpp}::JITDylibSearchOrderResolver::Deps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/rtdyldobjectlinkinglayer-cpp">RTDyldObjectLinkingLayer.cpp</a>.</p>

</div>
</div>

### MR {#aec1f6977110915c474735fd889ae426d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaterializationResponsibility&amp; anonymous{RTDyldObjectLinkingLayer.cpp}::JITDylibSearchOrderResolver::MR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/rtdyldobjectlinkinglayer-cpp">RTDyldObjectLinkingLayer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/rtdyldobjectlinkinglayer-cpp">RTDyldObjectLinkingLayer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
