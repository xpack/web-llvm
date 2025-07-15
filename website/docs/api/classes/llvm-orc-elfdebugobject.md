---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/elfdebugobject
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ELFDebugObject` Class Reference

<p>The current implementation of <a href="/web-llvm/docs/api/classes/llvm/orc/elfdebugobject">ELFDebugObject</a> replicates the approach used in <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a>: It patches executable and data section headers in the given object buffer with load-addresses of their corresponding sections in target memory. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::ELFDebugObject { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/debugobject">DebugObject</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The plugin creates a debug object from when JITLink starts processing the corresponding <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a>. <a href="/web-llvm/docs/api/classes/llvm/orc/debugobject/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53ef8f944ca8ed5d3ff1674623c90f3f">ELFDebugObject</a> (std::unique_ptr&lt; WritableMemoryBuffer &gt; Buffer, JITLinkMemoryManager &amp;MemMgr, const JITLinkDylib *JD, ExecutionSession &amp;ES)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3474e39e7735c3c5a1fef1fd1a1269f">reportSectionTargetMemoryRange</a> (StringRef Name, SectionRange TargetMem) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab06114150e1167476d6fe5dd24480c25">getBuffer</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54c6b5a386504b3dd5ef2eb0111102ad">finalizeWorkingMemory</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2bb25631b0620094ff871998ec28da02">recordSection</a> (StringRef Name, std::unique_ptr&lt; ELFDebugObjectSection&lt; ELFT &gt; &gt; Section)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/debugobjectsection">DebugObjectSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4253dd30b53933558ef1d7d65d006e54">getSection</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer">WritableMemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ed582f6579e1af768b7b2faf197353c">Buffer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/debugobjectsection">DebugObjectSection</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73a0feb3e3c3b0b3e61141dfdb227af7">Sections</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/debugobject">DebugObject</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acca206747ed9f9fef7a797ac03d25f17">Create</a> (MemoryBufferRef Buffer, JITLinkContext &amp;Ctx, ExecutionSession &amp;ES)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af0b9b03d56b15d54556884704c992281">CreateArchType</a> (MemoryBufferRef Buffer, JITLinkMemoryManager &amp;MemMgr, const JITLinkDylib *JD, ExecutionSession &amp;ES) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/elfdebugobject">ELFDebugObject</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer">WritableMemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72614075032c40c6d6fb8c37a1249a94">CopyBuffer</a> (MemoryBufferRef Buffer, Error &amp;Err)</td>
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

<p>The current implementation of <a href="/web-llvm/docs/api/classes/llvm/orc/elfdebugobject">ELFDebugObject</a> replicates the approach used in <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a>: It patches executable and data section headers in the given object buffer with load-addresses of their corresponding sections in target memory.</p>

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### ELFDebugObject() {#a53ef8f944ca8ed5d3ff1674623c90f3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ELFDebugObject::ELFDebugObject (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer">WritableMemoryBuffer</a> &gt; Buffer, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">JITLinkMemoryManager</a> &amp; MemMgr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkdylib">JITLinkDylib</a> * JD, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES)</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBuffer() {#ab06114150e1167476d6fe5dd24480c25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::orc::ELFDebugObject::getBuffer ()</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>

</div>
</div>

### reportSectionTargetMemoryRange() {#aa3474e39e7735c3c5a1fef1fd1a1269f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ELFDebugObject::reportSectionTargetMemoryRange (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/jitlink/sectionrange">SectionRange</a> TargetMem)</td>
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



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a> and <a href="#aa3474e39e7735c3c5a1fef1fd1a1269f">reportSectionTargetMemoryRange</a>.</p>


<p>Referenced by <a href="#aa3474e39e7735c3c5a1fef1fd1a1269f">reportSectionTargetMemoryRange</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### finalizeWorkingMemory() {#a54c6b5a386504b3dd5ef2eb0111102ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SimpleSegmentAlloc &gt; llvm::orc::ELFDebugObject::finalizeWorkingMemory ()</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/jitlink/simplesegmentalloc/#afd606b508cfbab129894d4b176cad942">llvm::jitlink::SimpleSegmentAlloc::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/debugobject/#a2dace59f371765386e5020bf92f24a00">llvm::orc::DebugObject::ES</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/process/#a774becf3d10728695b270703bca011ec">llvm::sys::Process::getPageSizeEstimate</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/debugobject/#adbdeefd844134e297b119ad528a3ebfb">llvm::orc::DebugObject::JD</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/debugobject/#a1f5b439546aec1304b7bfe04ac941370">llvm::orc::DebugObject::MemMgr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp/#a90146d35673da9e3e4a7f41f3b8c9b7e">PageSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### getSection() {#a4253dd30b53933558ef1d7d65d006e54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugObjectSection * llvm::orc::ELFDebugObject::getSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>Reference <a href="#a4253dd30b53933558ef1d7d65d006e54">getSection</a>.</p>


<p>Referenced by <a href="#a4253dd30b53933558ef1d7d65d006e54">getSection</a>.</p>

</div>
</div>

### recordSection() {#a2bb25631b0620094ff871998ec28da02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ELFDebugObject::recordSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/elfdebugobjectsection">ELFDebugObjectSection</a>&lt; ELFT &gt; &gt; Section)</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a2bb25631b0620094ff871998ec28da02">recordSection</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a2bb25631b0620094ff871998ec28da02">recordSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Buffer {#a2ed582f6579e1af768b7b2faf197353c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;WritableMemoryBuffer&gt; llvm::orc::ELFDebugObject::Buffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>

</div>
</div>

### Sections {#a73a0feb3e3c3b0b3e61141dfdb227af7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;std::unique_ptr&lt;DebugObjectSection&gt; &gt; llvm::orc::ELFDebugObject::Sections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Create() {#acca206747ed9f9fef7a797ac03d25f17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; DebugObject &gt; &gt; llvm::orc::ELFDebugObject::Create (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Buffer, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkcontext">JITLinkContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES)</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aa87228a0d135b2b897952fa11ff023c5ac700ff9a9a24f46587997e131502702c">llvm::ELF::ELFCLASS32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aa87228a0d135b2b897952fa11ff023c5a54b4da97cdda07031363b240c26c9794">llvm::ELF::ELFCLASS64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a868a39064cf90c55a5a8b267d8018c2bafedc8af0121f7104ef49a576b30865de">llvm::ELF::ELFDATA2LSB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a868a39064cf90c55a5a8b267d8018c2ba133a1bcc89f1dca304102b741ecbf299">llvm::ELF::ELFDATA2MSB</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/debugobject/#a2dace59f371765386e5020bf92f24a00">llvm::orc::DebugObject::ES</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6e5453100b9e598d90cae8bc9f6d45f4">llvm::object::getElfArchType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a415d8bb3bcda2c9129502a0852bb308a">llvm::orc::createDebugObjectFromBuffer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### CopyBuffer() {#a72614075032c40c6d6fb8c37a1249a94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; WritableMemoryBuffer &gt; llvm::orc::ELFDebugObject::CopyBuffer (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Buffer, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>

</div>
</div>

### CreateArchType() {#af0b9b03d56b15d54556884704c992281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; ELFDebugObject &gt; &gt; llvm::orc::ELFDebugObject::CreateArchType (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Buffer, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">JITLinkMemoryManager</a> &amp; MemMgr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkdylib">JITLinkDylib</a> * JD, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES)</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
