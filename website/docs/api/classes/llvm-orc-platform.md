---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/platform
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Platform` Class Reference

<p>Platforms set up standard symbols and mediate interactions between dynamic initializers (e.g. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::Platform { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">llvm/ExecutionEngine/Orc/Core.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/genericllvmirplatform">GenericLLVMIRPlatform</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/orc/platform">orc::Platform</a> component of Generic LLVM IR <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> support. <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/genericllvmirplatform/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform">COFFPlatform</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mediates between <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> initialization and <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> state. <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform">ELFNixPlatform</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mediates between ELFNix initialization and <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> state. <a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/machoplatform">MachOPlatform</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mediates between <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> initialization and <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> state. <a href="/web-llvm/docs/api/classes/llvm/orc/machoplatform/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a286e7d55134fe69c2fe87e2da062bdd2">~Platform</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af83795e97281d33db2882a003b2c7545">setupJITDylib</a> (JITDylib &amp;JD)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be called outside the session lock each time a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> is created (unless it is created with EmptyJITDylib set) to allow the <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> to install any <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> specific standard symbols (e.g __dso_handle). <a href="#af83795e97281d33db2882a003b2c7545">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25b277d11a256288949d3f148177fe56">teardownJITDylib</a> (JITDylib &amp;JD)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be called outside the session lock each time a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> is removed to allow the <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> to remove any JITDylib-specific data. <a href="#a25b277d11a256288949d3f148177fe56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2d49fb91e31820cfe77c57771e604ef">notifyAdding</a> (ResourceTracker &amp;RT, const MaterializationUnit &amp;MU)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be called under the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> lock each time a <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> is added to a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#ae2d49fb91e31820cfe77c57771e604ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac65bbed2d0a758c928e12750885dbbd9">notifyRemoving</a> (ResourceTracker &amp;RT)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be called under the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> lock when a <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> is removed. <a href="#ac65bbed2d0a758c928e12750885dbbd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a8ab9a099de556e888c5f92a4fe49d2fa">SymbolMap</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aded9cbc2f7fa64fbbdf4f5ce8f826dd5">lookupInitSymbols</a> (ExecutionSession &amp;ES, const DenseMap&lt; JITDylib *, SymbolLookupSet &gt; &amp;InitSyms)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A utility function for looking up initializer symbols. <a href="#aded9cbc2f7fa64fbbdf4f5ce8f826dd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f5de33429dae751bbf618940ff67e01">lookupInitSymbolsAsync</a> (unique_function&lt; void(Error)&gt; OnComplete, ExecutionSession &amp;ES, const DenseMap&lt; JITDylib *, SymbolLookupSet &gt; &amp;InitSyms)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Performs an async lookup for the given symbols in each of the given JITDylibs, calling the given handler once all lookups have completed. <a href="#a5f5de33429dae751bbf618940ff67e01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Platforms set up standard symbols and mediate interactions between dynamic initializers (e.g.</p>


<p>C++ static constructors) and <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> state. Note that Platforms do not automatically run initializers: clients are still responsible for doing this.</p>


<p>Definition at line 1273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~Platform() {#a286e7d55134fe69c2fe87e2da062bdd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::Platform::~Platform ()</td>
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



<p>Definition at line 1275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### notifyAdding() {#ae2d49fb91e31820cfe77c57771e604ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::orc::Platform::notifyAdding (<a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp; RT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> &amp; MU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method will be called under the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> lock each time a <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> is added to a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>

<p>Definition at line 1289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### notifyRemoving() {#ac65bbed2d0a758c928e12750885dbbd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::orc::Platform::notifyRemoving (<a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp; RT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method will be called under the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> lock when a <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> is removed.</p>

<p>Definition at line 1294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### setupJITDylib() {#af83795e97281d33db2882a003b2c7545}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::orc::Platform::setupJITDylib (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method will be called outside the session lock each time a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> is created (unless it is created with EmptyJITDylib set) to allow the <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> to install any <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> specific standard symbols (e.g __dso_handle).</p>

<p>Definition at line 1281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

### teardownJITDylib() {#a25b277d11a256288949d3f148177fe56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::orc::Platform::teardownJITDylib (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method will be called outside the session lock each time a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> is removed to allow the <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> to remove any JITDylib-specific data.</p>

<p>Definition at line 1285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### lookupInitSymbols() {#aded9cbc2f7fa64fbbdf4f5ce8f826dd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DenseMap&lt; JITDylib *, SymbolMap &gt; &gt; llvm::orc::Platform::lookupInitSymbols (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> *, <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a> &gt; &amp; InitSyms)</td>
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

<p>A utility function for looking up initializer symbols.</p>


<p>Performs a blocking lookup for the given symbols in each of the given JITDylibs.</p>


<p>Note: This function is deprecated and will be removed in the near future.</p>


<p>Declaration at line 1301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1494 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a53408c95a7bfb5443b43fb2134c3eb23">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#a9260560ad3aaa612b92cff4bccd3c223">llvm::orc::ExecutionSession::lookup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81da5fa8627bea3ff4b720673b9a298caf2d">llvm::orc::MatchAllSymbols</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac8dd8c429957b970e617afb500775d99">llvm::orc::NoDependenciesToRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adac25fca9fb14b1defe43d18a81c16e8ae7d31fc0602fb2ede144d18cdffd816b">llvm::orc::Ready</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eba84a8921b25f505d0d2077aeb5db4bc16">llvm::orc::Static</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### lookupInitSymbolsAsync() {#a5f5de33429dae751bbf618940ff67e01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::Platform::lookupInitSymbolsAsync (<a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; OnComplete, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> *, <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a> &gt; &amp; InitSyms)</td>
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

<p>Performs an async lookup for the given symbols in each of the given JITDylibs, calling the given handler once all lookups have completed.</p>

<p>Declaration at line 1307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a>, definition at line 1543 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#a9260560ad3aaa612b92cff4bccd3c223">llvm::orc::ExecutionSession::lookup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81da5fa8627bea3ff4b720673b9a298caf2d">llvm::orc::MatchAllSymbols</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac8dd8c429957b970e617afb500775d99">llvm::orc::NoDependenciesToRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adac25fca9fb14b1defe43d18a81c16e8ae7d31fc0602fb2ede144d18cdffd816b">llvm::orc::Ready</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eba84a8921b25f505d0d2077aeb5db4bc16">llvm::orc::Static</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/core-h">Core.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
