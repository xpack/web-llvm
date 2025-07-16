---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/runtimedyldmachox86-64
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RuntimeDyldMachOX86_64` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::RuntimeDyldMachOX86_64 { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachox86-64-h">ExecutionEngine/RuntimeDyld/Targets/RuntimeDyldMachOX86_64.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachocrtpbase">RuntimeDyldMachOCRTPBase&lt;Impl&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RuntimeDyldMachOTarget - Templated base class for generic <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> linker algorithms and data structures. <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachocrtpbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">uint64_t <a href="#a0e8b398a34891759288f13935451f758">TargetPtrT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb9a058f4bdfcbbb437a0f6131950f86">RuntimeDyldMachOX86_64</a> (RuntimeDyld::MemoryManager &amp;MM, JITSymbolResolver &amp;Resolver)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eb372fb99a18a3a436b9a2bd80a711d">getMaxStubSize</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92124ce735e4095880efc5e699a04c99">getStubAlignment</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59ad91c5ccf9ed8867eab9cc5424b151">processRelocationRef</a> (unsigned SectionID, relocation_iterator RelI, const ObjectFile &amp;BaseObjT, ObjSectionToIDMap &amp;ObjSectionToID, StubMap &amp;Stubs) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses one or more object file relocations (some object files use relocation pairs) and stores it to Relocations or SymbolRelocations (this depends on the object file type). <a href="#a59ad91c5ccf9ed8867eab9cc5424b151">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9f0c0ad7d8a9a72b2b7b5601eb7cf77">resolveRelocation</a> (const RelocationEntry &amp;RE, uint64_t Value) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A object file specific relocation resolver. <a href="#ab9f0c0ad7d8a9a72b2b7b5601eb7cf77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9ff3905023451c6ec3c0ffbf0ca2d06">finalizeSection</a> (const ObjectFile &amp;Obj, unsigned SectionID, const SectionRef &amp;Section)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed51a23f0fe42ccb7519cb4093a19ec0">processGOTRelocation</a> (const RelocationEntry &amp;RE, RelocationValueRef &amp;Value, StubMap &amp;Stubs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac858063c464a3003a7228cc4a4626c6f">processSubtractRelocation</a> (unsigned SectionID, relocation_iterator RelI, const MachOObjectFile &amp;BaseObj, ObjSectionToIDMap &amp;ObjSectionToID)</td>
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


<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachox86-64-h">RuntimeDyldMachOX86_64.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### TargetPtrT {#a0e8b398a34891759288f13935451f758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef uint64_t llvm::RuntimeDyldMachOX86_64::TargetPtrT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachox86-64-h">RuntimeDyldMachOX86_64.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RuntimeDyldMachOX86\_64() {#afb9a058f4bdfcbbb437a0f6131950f86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RuntimeDyldMachOX86_64::RuntimeDyldMachOX86_64 (<a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager">RuntimeDyld::MemoryManager</a> &amp; MM, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolresolver">JITSymbolResolver</a> &amp; Resolver)</td>
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



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachox86-64-h">RuntimeDyldMachOX86_64.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachocrtpbase/#a4fd1220b5b8aa3aa6d20e7b79ec0f897">llvm::RuntimeDyldMachOCRTPBase&lt; RuntimeDyldMachOX86_64 &gt;::RuntimeDyldMachOCRTPBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### finalizeSection() {#af9ff3905023451c6ec3c0ffbf0ca2d06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::RuntimeDyldMachOX86_64::finalizeSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, unsigned SectionID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a> &amp; Section)</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachox86-64-h">RuntimeDyldMachOX86_64.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### getMaxStubSize() {#a5eb372fb99a18a3a436b9a2bd80a711d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RuntimeDyldMachOX86_64::getMaxStubSize ()</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachox86-64-h">RuntimeDyldMachOX86_64.h</a>.</p>

</div>
</div>

### getStubAlignment() {#a92124ce735e4095880efc5e699a04c99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::RuntimeDyldMachOX86_64::getStubAlignment ()</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachox86-64-h">RuntimeDyldMachOX86_64.h</a>.</p>

</div>
</div>

### processRelocationRef() {#a59ad91c5ccf9ed8867eab9cc5424b151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; relocation_iterator &gt; llvm::RuntimeDyldMachOX86_64::processRelocationRef (unsigned SectionID, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a> RelI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a22b1a24bb422a0f0896dd84dff7933e2">ObjSectionToIDMap</a> &amp; ObjSectionToID, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a45d3097b94f4f98303ae36e6c6b7eee6">StubMap</a> &amp; Stubs)</td>
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

<p>Parses one or more object file relocations (some object files use relocation pairs) and stores it to Relocations or SymbolRelocations (this depends on the object file type).</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Iterator to the next relocation that needs to be parsed.</p></dd>
</dl>


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachox86-64-h">RuntimeDyldMachOX86_64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a80213c5b59afecdd125a21b28b9637e9">llvm::RelocationEntry::Addend</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a9ee81c156267d67bed9008ed1a954214">llvm::RuntimeDyldImpl::addRelocationForSection</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a5db8c0beafbba922f1600e24fe6898bc">llvm::RuntimeDyldImpl::addRelocationForSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a653a63105b842dd49a3a0921ce6a6d66">llvm::object::MachOObjectFile::getAnyRelocationType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a7bec3ca52f60d7ca088f0634a2e8f779">llvm::object::MachOObjectFile::getPlainRelocationExternal</a>, <a href="/web-llvm/docs/api/classes/llvm/object/relocationref/#acd93a9353f94b029cdfa295b88874b38">llvm::object::RelocationRef::getRawDataRefImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aaacf649b0759051f6c5327e44b82f8aa">llvm::object::MachOObjectFile::getRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#abaf648d88dc891045a7cd0e989789370">llvm::RuntimeDyldMachO::getRelocationEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ac01d9cc5d2d4a3b6662c7096e54bf8ad">llvm::RuntimeDyldMachO::getRelocationValueRef</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a6fa763e1036861ba4581c5b3199b4fed">llvm::RelocationEntry::IsPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad07c873a9197ed022e779129f28ca028">llvm::object::MachOObjectFile::isRelocationScattered</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ab8281e64fb0c8b5bc71fdb5876df6c9d">llvm::RuntimeDyldMachO::makeValueAddendPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#a4ff8b7dc8dd3a4baddc147c6afd14c5e">llvm::RuntimeDyldMachO::memcpyAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a4b339d832145cb7ea79bbb90f5233897">llvm::RelocationEntry::RelType</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a290c253a00603f2e0cde5f11c6db1372">llvm::RelocationEntry::Size</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h/#af4c1923d575768fb7d3dc8e15f49337c">UNIMPLEMENTED_RELOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa0780f2a6ff9e575244e484bcb221abca">llvm::MachO::X86_64_RELOC_GOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa3be1c03bfdfb1a901470a70c7d55d715">llvm::MachO::X86_64_RELOC_GOT_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfac646834a5cf45e7b071d4d554ec653ed">llvm::MachO::X86_64_RELOC_SUBTRACTOR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa75544865ca16caaf6ebb768f93879546">llvm::MachO::X86_64_RELOC_TLV</a>.</p>

</div>
</div>

### resolveRelocation() {#ab9f0c0ad7d8a9a72b2b7b5601eb7cf77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldMachOX86_64::resolveRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationentry">RelocationEntry</a> &amp; RE, uint64_t Value)</td>
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

<p>A object file specific relocation resolver.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">RE</td>
<td class="doxyParamItemDescription"><p>The relocation to be resolved</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> symbol address to apply the relocation action</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachox86-64-h">RuntimeDyldMachOX86_64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a80213c5b59afecdd125a21b28b9637e9">llvm::RelocationEntry::Addend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#af2314475cd69d029c487927d58778a82">llvm::RuntimeDyldMachO::dumpRelocationToResolve</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a6fa763e1036861ba4581c5b3199b4fed">llvm::RelocationEntry::IsPCRel</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a4c2824740d2fcf8bd1f44248bdcd4052">llvm::RelocationEntry::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a4b339d832145cb7ea79bbb90f5233897">llvm::RelocationEntry::RelType</a>, <a href="/web-llvm/docs/api/structs/llvm/relocationentry/sectionpair/#ae8eb65258b27fa965c977f7e8e3d025d">llvm::RelocationEntry::SectionPair::SectionA</a>, <a href="/web-llvm/docs/api/structs/llvm/relocationentry/sectionpair/#abb7481bf753e95248d49ef2dda4ffb8d">llvm::RelocationEntry::SectionPair::SectionB</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#aec2f9774e1098853d20912f579f501b9">llvm::RelocationEntry::SectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#af42a708ce2732dc8b604b8d32384ee75">llvm::RelocationEntry::Sections</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afce88102ca208741b470edac5342c4b3">llvm::RuntimeDyldImpl::Sections</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a290c253a00603f2e0cde5f11c6db1372">llvm::RelocationEntry::Size</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#ac7b095afaba91cf9bf59313c8e94d2d9">llvm::RuntimeDyldImpl::writeBytesUnaligned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa539f53d610b7600a7b14a44cc15f7818">llvm::MachO::X86_64_RELOC_BRANCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa05c96d2e2f0dca08f6a8b0a0b1332e08">llvm::MachO::X86_64_RELOC_SIGNED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfad15086d725d94fff8a091bb1ac2c9bf0">llvm::MachO::X86_64_RELOC_SIGNED_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa5431aa0c9664547b30a94eb23eace74b">llvm::MachO::X86_64_RELOC_SIGNED_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfaa04e7abcc279e5e6323ec51cd15d3f5a">llvm::MachO::X86_64_RELOC_SIGNED_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfac646834a5cf45e7b071d4d554ec653ed">llvm::MachO::X86_64_RELOC_SUBTRACTOR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa036310823675c1b65bffda81f9e42ba2">llvm::MachO::X86_64_RELOC_UNSIGNED</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### processGOTRelocation() {#aed51a23f0fe42ccb7519cb4093a19ec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldMachOX86_64::processGOTRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationentry">RelocationEntry</a> &amp; RE, <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref">RelocationValueRef</a> &amp; Value, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a45d3097b94f4f98303ae36e6c6b7eee6">StubMap</a> &amp; Stubs)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachox86-64-h">RuntimeDyldMachOX86_64.h</a>.</p>

</div>
</div>

### processSubtractRelocation() {#ac858063c464a3003a7228cc4a4626c6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; relocation_iterator &gt; llvm::RuntimeDyldMachOX86_64::processSubtractRelocation (unsigned SectionID, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a> RelI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; BaseObj, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a22b1a24bb422a0f0896dd84dff7933e2">ObjSectionToIDMap</a> &amp; ObjSectionToID)</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachox86-64-h">RuntimeDyldMachOX86_64.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachox86-64-h">RuntimeDyldMachOX86_64.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
