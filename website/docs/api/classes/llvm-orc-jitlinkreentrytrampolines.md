---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/jitlinkreentrytrampolines
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `JITLinkReentryTrampolines` Class Reference

<p>Produces trampolines on request using JITLink. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::JITLinkReentryTrampolines { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jitlinkreentrytrampolines-h">llvm/ExecutionEngine/Orc/JITLinkReentryTrampolines.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae70565c75d7ba26ace7d79c0edd0e5a4">EmitTrampolineFn</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">jitlink::Symbol</a> &amp;( <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">jitlink::Section</a> &amp;Sec, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">jitlink::Symbol</a> &amp;ReentrySym)&gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24d30f839c0b541471266858dffcc81c">OnTrampolinesReadyFn</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void( <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a> &gt; &gt; EntryAddrs)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3126b06e80371aecc0c0047367db8a9d">JITLinkReentryTrampolines</a> (ObjectLinkingLayer &amp;ObjLinkingLayer, EmitTrampolineFn EmitTrampoline)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a785d4678ba769470bf89b63a0a22c20d">JITLinkReentryTrampolines</a> (JITLinkReentryTrampolines &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jitlinkreentrytrampolines">JITLinkReentryTrampolines</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e6d48330de9370a2cb16d2944f07abf">operator=</a> (JITLinkReentryTrampolines &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b7516126f534d941a4115b01a8f57c9">emit</a> (ResourceTrackerSP RT, size_t NumTrampolines, OnTrampolinesReadyFn OnTrampolinesReady)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeaf22c7946a0f19e29bd83367d4b06c">ObjLinkingLayer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jitlinkreentrytrampolines/trampolineaddrscraperplugin">TrampolineAddrScraperPlugin</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa257e0642c449fea6db99b51b22c82b8">TrampolineAddrScraper</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae70565c75d7ba26ace7d79c0edd0e5a4">EmitTrampolineFn</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebba0a23ba4d8f05f3b0d4aec84c9cfe">EmitTrampoline</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ada79a0c767524d9dde3f1a815a5ac6">ReentryGraphIdx</a> {0}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/jitlinkreentrytrampolines">JITLinkReentryTrampolines</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65b27dfd43dad3af09bd244752f7eadf">Create</a> (ObjectLinkingLayer &amp;ObjLinkingLayer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create trampolines using the default reentry trampoline function for the session triple. <a href="#a65b27dfd43dad3af09bd244752f7eadf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Produces trampolines on request using JITLink.</p>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jitlinkreentrytrampolines-h">JITLinkReentryTrampolines.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### EmitTrampolineFn {#ae70565c75d7ba26ace7d79c0edd0e5a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::JITLinkReentryTrampolines::EmitTrampolineFn =  unique_function&lt;jitlink::Symbol &amp;(
      jitlink::LinkGraph &amp;G, jitlink::Section &amp;Sec,
      jitlink::Symbol &amp;ReentrySym)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jitlinkreentrytrampolines-h">JITLinkReentryTrampolines.h</a>.</p>

</div>
</div>

### OnTrampolinesReadyFn {#a24d30f839c0b541471266858dffcc81c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::JITLinkReentryTrampolines::OnTrampolinesReadyFn =  unique_function&lt;void(
      Expected&lt;std::vector&lt;ExecutorSymbolDef&gt;&gt; EntryAddrs)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jitlinkreentrytrampolines-h">JITLinkReentryTrampolines.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### JITLinkReentryTrampolines() {#a3126b06e80371aecc0c0047367db8a9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::JITLinkReentryTrampolines::JITLinkReentryTrampolines (<a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> &amp; ObjLinkingLayer, <a href="#ae70565c75d7ba26ace7d79c0edd0e5a4">EmitTrampolineFn</a> EmitTrampoline)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jitlinkreentrytrampolines-h">JITLinkReentryTrampolines.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/jitlinkreentrytrampolines-cpp">JITLinkReentryTrampolines.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="#a785d4678ba769470bf89b63a0a22c20d">JITLinkReentryTrampolines</a> and <a href="#a9e6d48330de9370a2cb16d2944f07abf">operator=</a>.</p>

</div>
</div>

### JITLinkReentryTrampolines() {#a785d4678ba769470bf89b63a0a22c20d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::JITLinkReentryTrampolines::JITLinkReentryTrampolines (<a href="/web-llvm/docs/api/classes/llvm/orc/jitlinkreentrytrampolines">JITLinkReentryTrampolines</a> &amp;&amp;)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jitlinkreentrytrampolines-h">JITLinkReentryTrampolines.h</a>.</p>


<p>Reference <a href="#a3126b06e80371aecc0c0047367db8a9d">JITLinkReentryTrampolines</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a9e6d48330de9370a2cb16d2944f07abf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITLinkReentryTrampolines &amp; llvm::orc::JITLinkReentryTrampolines::operator= (<a href="/web-llvm/docs/api/classes/llvm/orc/jitlinkreentrytrampolines">JITLinkReentryTrampolines</a> &amp;&amp;)</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jitlinkreentrytrampolines-h">JITLinkReentryTrampolines.h</a>.</p>


<p>Reference <a href="#a3126b06e80371aecc0c0047367db8a9d">JITLinkReentryTrampolines</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#a3b7516126f534d941a4115b01a8f57c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::JITLinkReentryTrampolines::emit (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a25b487d71ccd2a8f38131e2b21c5d612">ResourceTrackerSP</a> RT, size_t NumTrampolines, <a href="#a24d30f839c0b541471266858dffcc81c">OnTrampolinesReadyFn</a> OnTrampolinesReady)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jitlinkreentrytrampolines-h">JITLinkReentryTrampolines.h</a>, definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/jitlinkreentrytrampolines-cpp">JITLinkReentryTrampolines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2fbb59fad28934f72ede7ddc316dfc89a953feeff1e20f40677fb7f77c073b3be">llvm::orc::Exec</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr/#ab7e9ba9766156c2b9877ba451e7e9a64">llvm::IntrusiveRefCntPtr&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a06eee57acde48953ffd29ae8d337202e">llvm::jitlink::getGenericEdgeKindName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81da5fa8627bea3ff4b720673b9a298caf2d">llvm::orc::MatchAllSymbols</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac8dd8c429957b970e617afb500775d99">llvm::orc::NoDependenciesToRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2fbb59fad28934f72ede7ddc316dfc89a7a1a5f3e79fdc91edf2f5ead9d66abb4">llvm::orc::Read</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adac25fca9fb14b1defe43d18a81c16e8ae7d31fc0602fb2ede144d18cdffd816b">llvm::orc::Ready</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#adb322dc6826cf005531ccfdf666260fda1fee46ed8695ca5c28a7c177dae57a8a">llvm::jitlink::SideEffectsOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eba84a8921b25f505d0d2077aeb5db4bc16">llvm::orc::Static</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55fac43e0fd449c758dab8f891d8e19eb1a9">llvm::jitlink::Strong</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a69e9511c04540297d2cff38f4645a9aba26a03cdefe35519715a4b6d564c9c9c7">llvm::orc::WeaklyReferencedSymbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EmitTrampoline {#aebba0a23ba4d8f05f3b0d4aec84c9cfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EmitTrampolineFn llvm::orc::JITLinkReentryTrampolines::EmitTrampoline</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jitlinkreentrytrampolines-h">JITLinkReentryTrampolines.h</a>.</p>

</div>
</div>

### ObjLinkingLayer {#abeaf22c7946a0f19e29bd83367d4b06c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectLinkingLayer&amp; llvm::orc::JITLinkReentryTrampolines::ObjLinkingLayer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jitlinkreentrytrampolines-h">JITLinkReentryTrampolines.h</a>.</p>

</div>
</div>

### ReentryGraphIdx {#a9ada79a0c767524d9dde3f1a815a5ac6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;size_t&gt; llvm::orc::JITLinkReentryTrampolines::ReentryGraphIdx {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jitlinkreentrytrampolines-h">JITLinkReentryTrampolines.h</a>.</p>

</div>
</div>

### TrampolineAddrScraper {#aa257e0642c449fea6db99b51b22c82b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TrampolineAddrScraperPlugin* llvm::orc::JITLinkReentryTrampolines::TrampolineAddrScraper = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jitlinkreentrytrampolines-h">JITLinkReentryTrampolines.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Create() {#a65b27dfd43dad3af09bd244752f7eadf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; JITLinkReentryTrampolines &gt; &gt; llvm::orc::JITLinkReentryTrampolines::Create (<a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> &amp; ObjLinkingLayer)</td>
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

<p>Create trampolines using the default reentry trampoline function for the session triple.</p>

<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jitlinkreentrytrampolines-h">JITLinkReentryTrampolines.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/jitlinkreentrytrampolines-cpp">JITLinkReentryTrampolines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#ad63469562c129c2c06c6e71f82ea37d5">llvm::jitlink::aarch64::createAnonymousReentryTrampoline</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64/#a53467f0fe1d815298a88cb6c0d7b8420">llvm::jitlink::x86_64::createAnonymousReentryTrampoline</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a6a7f84934d8f3975d6d33c72bdea69c7">llvm::orc::createJITLinkLazyReexportsManager</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jitlinkreentrytrampolines-h">JITLinkReentryTrampolines.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/jitlinkreentrytrampolines-cpp">JITLinkReentryTrampolines.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
