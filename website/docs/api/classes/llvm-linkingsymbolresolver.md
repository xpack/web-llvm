---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/linkingsymbolresolver
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LinkingSymbolResolver` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::LinkingSymbolResolver { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">ExecutionEngine/MCJIT/MCJIT.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legacyjitsymbolresolver">LegacyJITSymbolResolver</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legacy symbol resolution interface. <a href="/web-llvm/docs/api/classes/llvm/legacyjitsymbolresolver/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bb409bf96817ad9f3986efe65a74524">LinkingSymbolResolver</a> (MCJIT &amp;Parent, std::shared_ptr&lt; LegacyJITSymbolResolver &gt; Resolver)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitsymbol">JITSymbol</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3acbc4aeeddc8e52c6b69854432f211c">findSymbol</a> (const std::string &amp;Name) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method returns the address of the specified function or variable. <a href="#a3acbc4aeeddc8e52c6b69854432f211c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitsymbol">JITSymbol</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6902252429e09a9d391dd020f8d91e96">findSymbolInLogicalDylib</a> (const std::string &amp;Name) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method returns the address of the specified symbol if it exists within the logical dynamic library represented by this <a href="/web-llvm/docs/api/classes/llvm/jitsymbolresolver">JITSymbolResolver</a>. <a href="#a6902252429e09a9d391dd020f8d91e96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed415bd0788bee25eb78cc33069d698e">anchor</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ed92c16c4b6fb69009f2fb699ed9283">ParentEngine</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/legacyjitsymbolresolver">LegacyJITSymbolResolver</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84eb1f68f3f447c671a66d52848b0e0c">ClientResolver</a></td>
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


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LinkingSymbolResolver() {#a2bb409bf96817ad9f3986efe65a74524}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LinkingSymbolResolver::LinkingSymbolResolver (<a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> &amp; Parent, std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/legacyjitsymbolresolver">LegacyJITSymbolResolver</a> &gt; Resolver)</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### findSymbol() {#a3acbc4aeeddc8e52c6b69854432f211c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITSymbol LinkingSymbolResolver::findSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name)</td>
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

<p>This method returns the address of the specified function or variable.</p>


<p>It is used to resolve symbols during module linking.</p>


<p>If the returned symbol's address is equal to ~0ULL then <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> will skip all relocations for that symbol, and the client will be responsible for handling them manually.</p>


<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 672 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>

</div>
</div>

### findSymbolInLogicalDylib() {#a6902252429e09a9d391dd020f8d91e96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITSymbol llvm::LinkingSymbolResolver::findSymbolInLogicalDylib (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name)</td>
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

<p>This method returns the address of the specified symbol if it exists within the logical dynamic library represented by this <a href="/web-llvm/docs/api/classes/llvm/jitsymbolresolver">JITSymbolResolver</a>.</p>


<p>Unlike findSymbol, queries through this interface should return addresses for hidden symbols.</p>


<p>This is of particular importance for the Orc JIT APIs, which support lazy compilation by breaking up modules: Each of those broken out modules must be able to resolve hidden symbols provided by the others. Clients writing memory managers for <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> can usually ignore this method.</p>


<p>This method will be queried by <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> when checking for previous definitions of common symbols.</p>


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#aed415bd0788bee25eb78cc33069d698e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LinkingSymbolResolver::anchor ()</td>
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



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>, definition at line 681 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ClientResolver {#a84eb1f68f3f447c671a66d52848b0e0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;LegacyJITSymbolResolver&gt; llvm::LinkingSymbolResolver::ClientResolver</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>

</div>
</div>

### ParentEngine {#a3ed92c16c4b6fb69009f2fb699ed9283}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCJIT&amp; llvm::LinkingSymbolResolver::ParentEngine</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-cpp">MCJIT.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/mcjit/mcjit-h">MCJIT.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
