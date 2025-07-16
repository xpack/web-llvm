---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jitsymbol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `JITSymbol` Class Reference

<p>Represents a symbol in the JIT. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::JITSymbol { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">llvm/ExecutionEngine/JITSymbol.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcebe99ff32aee6ab6082e79b09ef503">GetAddressFtor</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a95dea244fa9847a9d69a5917797a9ceb">JITTargetAddress</a> &gt;()&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7b066c9159ac43c6332bc4f8a74037f">JITSymbol</a> (std::nullptr_t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a 'null' symbol, used to represent a "symbol not found" result from a successful (non-erroneous) lookup. <a href="#af7b066c9159ac43c6332bc4f8a74037f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe95de6281e0e491b15caff9bc15e2a8">JITSymbol</a> (Error Err)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/jitsymbol">JITSymbol</a> representing an error in the symbol lookup process (e.g. <a href="#abe95de6281e0e491b15caff9bc15e2a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a117c92a98be48c7ee9cd70604c60d4f3">JITSymbol</a> (JITTargetAddress Addr, JITSymbolFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a symbol for a definition with a known address. <a href="#a117c92a98be48c7ee9cd70604c60d4f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2754120943e26a78653437498341136">JITSymbol</a> (JITEvaluatedSymbol Sym)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/jitsymbol">JITSymbol</a> from a <a href="/web-llvm/docs/api/classes/llvm/jitevaluatedsymbol">JITEvaluatedSymbol</a>. <a href="#ad2754120943e26a78653437498341136">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e2004fd61cf36e9055255e0605ba2fd">JITSymbol</a> (GetAddressFtor GetAddress, JITSymbolFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a symbol for a definition that doesn't have a known address yet. <a href="#a5e2004fd61cf36e9055255e0605ba2fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac54cbe27208cf927d3168afdc129cc2a">JITSymbol</a> (const JITSymbol &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a904f94e1be71aaa16c0b450c05487903">JITSymbol</a> (JITSymbol &amp;&amp;Other)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab894be83e001cdb67ecba3f07b76576d">~JITSymbol</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitsymbol">JITSymbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbb6df1b619d66ac0fa9455f47eaae4b">operator=</a> (const JITSymbol &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitsymbol">JITSymbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a126c63d611f2f4f305ed7b98ef52aed0">operator=</a> (JITSymbol &amp;&amp;Other)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfb94b4cde61196cc7ed71a4f2537349">operator bool</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the symbol exists, false otherwise. <a href="#adfb94b4cde61196cc7ed71a4f2537349">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a356e8f8df07016fd4061857fb9df16d5">takeError</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move the error field value out of this <a href="/web-llvm/docs/api/classes/llvm/jitsymbol">JITSymbol</a>. <a href="#a356e8f8df07016fd4061857fb9df16d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a95dea244fa9847a9d69a5917797a9ceb">JITTargetAddress</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c6d9c97ac74fdb479a88a12165a5c13">getAddress</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the address of the symbol in the target address space. <a href="#a8c6d9c97ac74fdb479a88a12165a5c13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af180dbfc8ed65c6eed93deb3cb758c0e">getFlags</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a95dea244fa9847a9d69a5917797a9ceb">JITTargetAddress</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24112879f327c9483b9692b846bd1357">CachedAddr</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71fba3c1c73c57fffb196c738d457d47">Err</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adcebe99ff32aee6ab6082e79b09ef503">GetAddressFtor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04f4fc480477079fffd2913064fe0480">GetAddress</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/jitsymbol">llvm::JITSymbol</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a154ce1ae020e984a18bbc3851826b12b"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97cffa8c3f7dd2d26b6e9c5688c867ad">Flags</a></td>
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

<p>Represents a symbol in the JIT.</p>

<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### GetAddressFtor {#adcebe99ff32aee6ab6082e79b09ef503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::JITSymbol::GetAddressFtor =  unique_function&lt;Expected&lt;JITTargetAddress&gt;()&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### JITSymbol() {#af7b066c9159ac43c6332bc4f8a74037f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::JITSymbol::JITSymbol (std::nullptr_t)</td>
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

<p>Create a 'null' symbol, used to represent a "symbol not found" result from a successful (non-erroneous) lookup.</p>

<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>Reference <a href="#a24112879f327c9483b9692b846bd1357">CachedAddr</a>.</p>


<p>Referenced by <a href="#ac54cbe27208cf927d3168afdc129cc2a">JITSymbol</a>, <a href="#a904f94e1be71aaa16c0b450c05487903">JITSymbol</a>, <a href="#abbb6df1b619d66ac0fa9455f47eaae4b">operator=</a> and <a href="#a126c63d611f2f4f305ed7b98ef52aed0">operator=</a>.</p>

</div>
</div>

### JITSymbol() {#abe95de6281e0e491b15caff9bc15e2a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::JITSymbol::JITSymbol (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> Err)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/jitsymbol">JITSymbol</a> representing an error in the symbol lookup process (e.g.</p>


<p>a network failure during a remote lookup).</p>


<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>References <a href="#a71fba3c1c73c57fffb196c738d457d47">Err</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

### JITSymbol() {#a117c92a98be48c7ee9cd70604c60d4f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::JITSymbol::JITSymbol (<a href="/web-llvm/docs/api/namespaces/llvm/#a95dea244fa9847a9d69a5917797a9ceb">JITTargetAddress</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> Flags)</td>
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

<p>Create a symbol for a definition with a known address.</p>

<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>Reference <a href="#a24112879f327c9483b9692b846bd1357">CachedAddr</a>.</p>

</div>
</div>

### JITSymbol() {#ad2754120943e26a78653437498341136}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::JITSymbol::JITSymbol (<a href="/web-llvm/docs/api/classes/llvm/jitevaluatedsymbol">JITEvaluatedSymbol</a> Sym)</td>
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

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/jitsymbol">JITSymbol</a> from a <a href="/web-llvm/docs/api/classes/llvm/jitevaluatedsymbol">JITEvaluatedSymbol</a>.</p>

<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>References <a href="#a24112879f327c9483b9692b846bd1357">CachedAddr</a>, <a href="#a8c6d9c97ac74fdb479a88a12165a5c13">getAddress</a> and <a href="#af180dbfc8ed65c6eed93deb3cb758c0e">getFlags</a>.</p>

</div>
</div>

### JITSymbol() {#a5e2004fd61cf36e9055255e0605ba2fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::JITSymbol::JITSymbol (<a href="#adcebe99ff32aee6ab6082e79b09ef503">GetAddressFtor</a> GetAddress, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> Flags)</td>
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

<p>Create a symbol for a definition that doesn't have a known address yet.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">GetAddress</td>
<td class="doxyParamItemDescription"><p>A functor to materialize a definition (fixing the address) on demand.</p></td>
</tr>
</table>
</dd>
</dl>

<p>This constructor allows a JIT layer to provide a reference to a symbol definition without actually materializing the definition up front. The user can materialize the definition at any time by calling the getAddress method.</p>


<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>References <a href="#a24112879f327c9483b9692b846bd1357">CachedAddr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

### JITSymbol() {#ac54cbe27208cf927d3168afdc129cc2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::JITSymbol::JITSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitsymbol">JITSymbol</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>Reference <a href="#af7b066c9159ac43c6332bc4f8a74037f">JITSymbol</a>.</p>

</div>
</div>

### JITSymbol() {#a904f94e1be71aaa16c0b450c05487903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::JITSymbol::JITSymbol (<a href="/web-llvm/docs/api/classes/llvm/jitsymbol">JITSymbol</a> &amp;&amp; Other)</td>
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



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>References <a href="#a24112879f327c9483b9692b846bd1357">CachedAddr</a>, <a href="#a71fba3c1c73c57fffb196c738d457d47">Err</a>, <a href="#af7b066c9159ac43c6332bc4f8a74037f">JITSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~JITSymbol() {#ab894be83e001cdb67ecba3f07b76576d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::JITSymbol::~JITSymbol ()</td>
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



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>References <a href="#a24112879f327c9483b9692b846bd1357">CachedAddr</a> and <a href="#a71fba3c1c73c57fffb196c738d457d47">Err</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#adfb94b4cde61196cc7ed71a4f2537349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::JITSymbol::operator bool ()</td>
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

<p>Returns true if the symbol exists, false otherwise.</p>

<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>Reference <a href="#a24112879f327c9483b9692b846bd1357">CachedAddr</a>.</p>

</div>
</div>

### operator=() {#abbb6df1b619d66ac0fa9455f47eaae4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITSymbol &amp; llvm::JITSymbol::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitsymbol">JITSymbol</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>Reference <a href="#af7b066c9159ac43c6332bc4f8a74037f">JITSymbol</a>.</p>

</div>
</div>

### operator=() {#a126c63d611f2f4f305ed7b98ef52aed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITSymbol &amp; llvm::JITSymbol::operator= (<a href="/web-llvm/docs/api/classes/llvm/jitsymbol">JITSymbol</a> &amp;&amp; Other)</td>
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



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>References <a href="#a24112879f327c9483b9692b846bd1357">CachedAddr</a>, <a href="#a71fba3c1c73c57fffb196c738d457d47">Err</a>, <a href="#af7b066c9159ac43c6332bc4f8a74037f">JITSymbol</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAddress() {#a8c6d9c97ac74fdb479a88a12165a5c13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; JITTargetAddress &gt; llvm::JITSymbol::getAddress ()</td>
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

<p>Get the address of the symbol in the target address space.</p>


<p>Returns '0' if the symbol does not exist.</p>


<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a24112879f327c9483b9692b846bd1357">CachedAddr</a>.</p>


<p>Referenced by <a href="#ad2754120943e26a78653437498341136">JITSymbol</a>.</p>

</div>
</div>

### getFlags() {#af180dbfc8ed65c6eed93deb3cb758c0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITSymbolFlags llvm::JITSymbol::getFlags ()</td>
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



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>Referenced by <a href="#ad2754120943e26a78653437498341136">JITSymbol</a>.</p>

</div>
</div>

### takeError() {#a356e8f8df07016fd4061857fb9df16d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::JITSymbol::takeError ()</td>
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

<p>Move the error field value out of this <a href="/web-llvm/docs/api/classes/llvm/jitsymbol">JITSymbol</a>.</p>

<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>References <a href="#a71fba3c1c73c57fffb196c738d457d47">Err</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CachedAddr {#a24112879f327c9483b9692b846bd1357}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITTargetAddress llvm::JITSymbol::CachedAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>Referenced by <a href="#a8c6d9c97ac74fdb479a88a12165a5c13">getAddress</a>, <a href="#a5e2004fd61cf36e9055255e0605ba2fd">JITSymbol</a>, <a href="#ad2754120943e26a78653437498341136">JITSymbol</a>, <a href="#a904f94e1be71aaa16c0b450c05487903">JITSymbol</a>, <a href="#a117c92a98be48c7ee9cd70604c60d4f3">JITSymbol</a>, <a href="#af7b066c9159ac43c6332bc4f8a74037f">JITSymbol</a>, <a href="#adfb94b4cde61196cc7ed71a4f2537349">operator bool</a>, <a href="#a126c63d611f2f4f305ed7b98ef52aed0">operator=</a> and <a href="#ab894be83e001cdb67ecba3f07b76576d">~JITSymbol</a>.</p>

</div>
</div>

### Err {#a71fba3c1c73c57fffb196c738d457d47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::JITSymbol::Err</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>Referenced by <a href="#abe95de6281e0e491b15caff9bc15e2a8">JITSymbol</a>, <a href="#a904f94e1be71aaa16c0b450c05487903">JITSymbol</a>, <a href="#a126c63d611f2f4f305ed7b98ef52aed0">operator=</a>, <a href="#a356e8f8df07016fd4061857fb9df16d5">takeError</a> and <a href="#ab894be83e001cdb67ecba3f07b76576d">~JITSymbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#a154ce1ae020e984a18bbc3851826b12b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::JITSymbol llvm::JITSymbol</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>

</div>
</div>

### Flags {#a97cffa8c3f7dd2d26b6e9c5688c867ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITSymbolFlags llvm::JITSymbol::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>

</div>
</div>

### GetAddress {#a04f4fc480477079fffd2913064fe0480}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GetAddressFtor llvm::JITSymbol::GetAddress</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
