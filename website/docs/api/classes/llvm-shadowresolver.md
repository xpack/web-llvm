---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/shadowresolver
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ShadowResolver` Class Reference

<p>Delegate resolving to a sub-resolver, but shadow some variable names. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ShadowResolver { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">llvm/TableGen/Record.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/resolver">Resolver</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface for looking up the initializer for a variable name, used by <a href="/web-llvm/docs/api/classes/llvm/init/#a00581957c4bb1587a458c3fbf4326f7a">Init::resolveReferences</a>. <a href="/web-llvm/docs/api/classes/llvm/resolver/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25960891465ebfb19e04ac938bbab340">ShadowResolver</a> (Resolver &amp;R)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff7e7ac05aa89679256b9a2f74344871">addShadow</a> (const Init *Key)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d3888c4b2aecc13b2a0ce62451aad9f">resolve</a> (const Init *VarName) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the initializer for the given variable name (should normally be a <a href="/web-llvm/docs/api/classes/llvm/stringinit">StringInit</a>), or nullptr if the name could not be resolved. <a href="#a8d3888c4b2aecc13b2a0ce62451aad9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/resolver">Resolver</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f8bd2ec79c61479051ba1a079e10d45">R</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26371b2d99303de549e16d23d64fef7a">Shadowed</a></td>
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

<p>Delegate resolving to a sub-resolver, but shadow some variable names.</p>

<p>Definition at line 2218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ShadowResolver() {#a25960891465ebfb19e04ac938bbab340}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ShadowResolver::ShadowResolver (<a href="/web-llvm/docs/api/classes/llvm/resolver">Resolver</a> &amp; R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/resolver/#a85e1624d84b37e4691d676f3436ee53b">llvm::Resolver::getCurrentRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/resolver/#a443205c1c4ec8590c7527d5d9fdc96ab">llvm::Resolver::Resolver</a> and <a href="/web-llvm/docs/api/classes/llvm/resolver/#a9a6318086dfd641d141d786f29b37abd">llvm::Resolver::setFinal</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addShadow() {#aff7e7ac05aa89679256b9a2f74344871}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ShadowResolver::addShadow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * Key)</td>
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



<p>Definition at line 2228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/foldopinit/#abf5c6303f8771b4a93c937eea625e4a8">llvm::FoldOpInit::resolveReferences</a> and <a href="/web-llvm/docs/api/classes/llvm/ternopinit/#aee884b61ea9174997b34ece042bde0f8">llvm::TernOpInit::resolveReferences</a>.</p>

</div>
</div>

### resolve() {#a8d3888c4b2aecc13b2a0ce62451aad9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * llvm::ShadowResolver::resolve (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * VarName)</td>
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

<p>Return the initializer for the given variable name (should normally be a <a href="/web-llvm/docs/api/classes/llvm/stringinit">StringInit</a>), or nullptr if the name could not be resolved.</p>

<p>Definition at line 2230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### R {#a9f8bd2ec79c61479051ba1a079e10d45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Resolver&amp; llvm::ShadowResolver::R</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### Shadowed {#a26371b2d99303de549e16d23d64fef7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;const Init *&gt; llvm::ShadowResolver::Shadowed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
