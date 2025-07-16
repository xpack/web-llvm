---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/debugobject
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DebugObject` Class Reference

<p>The plugin creates a debug object from when JITLink starts processing the corresponding <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::DebugObject { ... }
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/elfdebugobject">ELFDebugObject</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current implementation of <a href="/web-llvm/docs/api/classes/llvm/orc/elfdebugobject">ELFDebugObject</a> replicates the approach used in <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a>: It patches executable and data section headers in the given object buffer with load-addresses of their corresponding sections in target memory. <a href="/web-llvm/docs/api/classes/llvm/orc/elfdebugobject/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f878e3f19fb20ceaf1ee25f9b254ba7">FinalizeContinuation</a> = std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/executoraddrrange">ExecutorAddrRange</a> &gt;)&gt;</td>
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

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0b53d4b50daf7ecdd7132d83c9f62a2">InFlightAlloc</a> = <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/inflightalloc">JITLinkMemoryManager::InFlightAlloc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeea3209fc0271ea8678f6289208ac5a5">FinalizedAlloc</a> = <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/finalizedalloc">JITLinkMemoryManager::FinalizedAlloc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afae9b010cfefc07e218ea8a5b1bad502">DebugObject</a> (JITLinkMemoryManager &amp;MemMgr, const JITLinkDylib *JD, ExecutionSession &amp;ES)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06c8db287aaac65313b87d4ac5fa18d8">~DebugObject</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34e2dc18068261d4f692c2b66648040a">hasFlags</a> (DebugObjectFlags F) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea21033a633306a00ae267e262e2fa24">setFlags</a> (DebugObjectFlags F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7de28b5b9db2250882391e8c875a706f">clearFlags</a> (DebugObjectFlags F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4849769b779f202a7e8c0f62d9c39c4e">finalizeAsync</a> (FinalizeContinuation OnFinalize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf578478148b09a5ce32995f4f72e7b3">reportSectionTargetMemoryRange</a> (StringRef Name, SectionRange TargetMem)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/simplesegmentalloc">SimpleSegmentAlloc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4971e3efa06adb898a28a56e7252b754">finalizeWorkingMemory</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">JITLinkMemoryManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f5b439546aec1304b7bfe04ac941370">MemMgr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkdylib">JITLinkDylib</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbdeefd844134e297b119ad528a3ebfb">JD</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dace59f371765386e5020bf92f24a00">ES</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#a559001955d0887af6200e615e38992e2">DebugObjectFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c04331915d75d09c8708085c89c3b04">Flags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aeea3209fc0271ea8678f6289208ac5a5">FinalizedAlloc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa181a05f95391ebe6487d5b485bf9340">Alloc</a></td>
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

<p>The plugin creates a debug object from when JITLink starts processing the corresponding <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a>.</p>


<p>It provides access to the pass configuration of the <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> and calls the finalization function, once the resulting link artifact was emitted.</p>


<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### FinalizeContinuation {#a5f878e3f19fb20ceaf1ee25f9b254ba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::DebugObject::FinalizeContinuation =  std::function&lt;void(Expected&lt;ExecutorAddrRange&gt;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Typedefs

### FinalizedAlloc {#aeea3209fc0271ea8678f6289208ac5a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::DebugObject::FinalizedAlloc =  JITLinkMemoryManager::FinalizedAlloc</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>

</div>
</div>

### InFlightAlloc {#af0b53d4b50daf7ecdd7132d83c9f62a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::DebugObject::InFlightAlloc =  JITLinkMemoryManager::InFlightAlloc</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DebugObject() {#afae9b010cfefc07e218ea8a5b1bad502}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::DebugObject::DebugObject (<a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">JITLinkMemoryManager</a> &amp; MemMgr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkdylib">JITLinkDylib</a> * JD, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES)</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>References <a href="#a2dace59f371765386e5020bf92f24a00">ES</a>, <a href="#adbdeefd844134e297b119ad528a3ebfb">JD</a> and <a href="#a1f5b439546aec1304b7bfe04ac941370">MemMgr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DebugObject() {#a06c8db287aaac65313b87d4ac5fa18d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::orc::DebugObject::~DebugObject ()</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>References <a href="#a2dace59f371765386e5020bf92f24a00">ES</a> and <a href="#a1f5b439546aec1304b7bfe04ac941370">MemMgr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clearFlags() {#a7de28b5b9db2250882391e8c875a706f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::DebugObject::clearFlags (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a559001955d0887af6200e615e38992e2">DebugObjectFlags</a> F)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### finalizeAsync() {#a4849769b779f202a7e8c0f62d9c39c4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::DebugObject::finalizeAsync (<a href="#a5f878e3f19fb20ceaf1ee25f9b254ba7">FinalizeContinuation</a> OnFinalize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4971e3efa06adb898a28a56e7252b754">finalizeWorkingMemory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2fbb59fad28934f72ede7ddc316dfc89a7a1a5f3e79fdc91edf2f5ead9d66abb4">llvm::orc::Read</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### hasFlags() {#a34e2dc18068261d4f692c2b66648040a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::DebugObject::hasFlags (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a559001955d0887af6200e615e38992e2">DebugObjectFlags</a> F)</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/debugobjectmanagerplugin/#abf15a05cfd44aa92db5db5251a6f3631">llvm::orc::DebugObjectManagerPlugin::modifyPassConfig</a>.</p>

</div>
</div>

### reportSectionTargetMemoryRange() {#acf578478148b09a5ce32995f4f72e7b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::orc::DebugObject::reportSectionTargetMemoryRange (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/jitlink/sectionrange">SectionRange</a> TargetMem)</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/debugobjectmanagerplugin/#abf15a05cfd44aa92db5db5251a6f3631">llvm::orc::DebugObjectManagerPlugin::modifyPassConfig</a>.</p>

</div>
</div>

### setFlags() {#aea21033a633306a00ae267e262e2fa24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::DebugObject::setFlags (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a559001955d0887af6200e615e38992e2">DebugObjectFlags</a> F)</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### finalizeWorkingMemory() {#a4971e3efa06adb898a28a56e7252b754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; SimpleSegmentAlloc &gt; llvm::orc::DebugObject::finalizeWorkingMemory ()</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>Referenced by <a href="#a4849769b779f202a7e8c0f62d9c39c4e">finalizeAsync</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ES {#a2dace59f371765386e5020bf92f24a00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession&amp; llvm::orc::DebugObject::ES</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/elfdebugobject/#acca206747ed9f9fef7a797ac03d25f17">llvm::orc::ELFDebugObject::Create</a>, <a href="#afae9b010cfefc07e218ea8a5b1bad502">DebugObject</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/elfdebugobject/#a54c6b5a386504b3dd5ef2eb0111102ad">llvm::orc::ELFDebugObject::finalizeWorkingMemory</a> and <a href="#a06c8db287aaac65313b87d4ac5fa18d8">~DebugObject</a>.</p>

</div>
</div>

### JD {#adbdeefd844134e297b119ad528a3ebfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const JITLinkDylib* llvm::orc::DebugObject::JD = nullptr</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>Referenced by <a href="#afae9b010cfefc07e218ea8a5b1bad502">DebugObject</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/elfdebugobject/#a54c6b5a386504b3dd5ef2eb0111102ad">llvm::orc::ELFDebugObject::finalizeWorkingMemory</a>.</p>

</div>
</div>

### MemMgr {#a1f5b439546aec1304b7bfe04ac941370}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITLinkMemoryManager&amp; llvm::orc::DebugObject::MemMgr</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>Referenced by <a href="#afae9b010cfefc07e218ea8a5b1bad502">DebugObject</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/elfdebugobject/#a54c6b5a386504b3dd5ef2eb0111102ad">llvm::orc::ELFDebugObject::finalizeWorkingMemory</a> and <a href="#a06c8db287aaac65313b87d4ac5fa18d8">~DebugObject</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Alloc {#aa181a05f95391ebe6487d5b485bf9340}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FinalizedAlloc llvm::orc::DebugObject::Alloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>

</div>
</div>

### Flags {#a4c04331915d75d09c8708085c89c3b04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugObjectFlags llvm::orc::DebugObject::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
