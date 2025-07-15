---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/runtimedyldmachoarm
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RuntimeDyldMachOARM` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::RuntimeDyldMachOARM { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoarm-h">ExecutionEngine/RuntimeDyld/Targets/RuntimeDyldMachOARM.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top">uint32_t <a href="#a719f0a1928932e9942031e460df96bb2">TargetPtrT</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachocrtpbase">RuntimeDyldMachOCRTPBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm">RuntimeDyldMachOARM</a> &gt; <a href="#a8f70ba13ffb9cad7060faecec1547c06">ParentT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1567da8c40ef25045b0c5d6777710256">RuntimeDyldMachOARM</a> (RuntimeDyld::MemoryManager &amp;MM, JITSymbolResolver &amp;Resolver)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7cced9dba460740451123177c754183">getMaxStubSize</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1206a01edf6bfe9b415a5d896d0184c">getStubAlignment</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5be127713fc8105efd1e4261f09b1097">getJITSymbolFlags</a> (const SymbolRef &amp;SR) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> from a libObject symbol. <a href="#a5be127713fc8105efd1e4261f09b1097">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03e9aa0b6ef0d729148177445c3c72ad">modifyAddressBasedOnFlags</a> (uint64_t Addr, JITSymbolFlags Flags) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Modify the given target address based on the given symbol flags. <a href="#a03e9aa0b6ef0d729148177445c3c72ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66ea8b31d8dedc659636270db9b37790">isAddrTargetThumb</a> (unsigned SectionID, uint64_t Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c19829e43ffe8064443b93c1946f9a2">decodeAddend</a> (const RelocationEntry &amp;RE) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0cc2b7a34912033f88c7169756683cb">processRelocationRef</a> (unsigned SectionID, relocation_iterator RelI, const ObjectFile &amp;BaseObjT, ObjSectionToIDMap &amp;ObjSectionToID, StubMap &amp;Stubs) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses one or more object file relocations (some object files use relocation pairs) and stores it to Relocations or SymbolRelocations (this depends on the object file type). <a href="#ad0cc2b7a34912033f88c7169756683cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42b1bc914cf22878c36dda7a8a31447e">resolveRelocation</a> (const RelocationEntry &amp;RE, uint64_t Value) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A object file specific relocation resolver. <a href="#a42b1bc914cf22878c36dda7a8a31447e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13b4460b917f0cf9c592c8e343c0a9a7">finalizeSection</a> (const ObjectFile &amp;Obj, unsigned SectionID, const SectionRef &amp;Section)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afae474a6318b038aba1ac48d10c04984">processBranchRelocation</a> (const RelocationEntry &amp;RE, const RelocationValueRef &amp;Value, StubMap &amp;Stubs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d299374c2a496c13c972b9c97df798a">processHALFSECTDIFFRelocation</a> (unsigned SectionID, relocation_iterator RelI, const ObjectFile &amp;BaseTObj, ObjSectionToIDMap &amp;ObjSectionToID)</td>
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


<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoarm-h">RuntimeDyldMachOARM.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### TargetPtrT {#a719f0a1928932e9942031e460df96bb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef uint32_t llvm::RuntimeDyldMachOARM::TargetPtrT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoarm-h">RuntimeDyldMachOARM.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### ParentT {#a8f70ba13ffb9cad7060faecec1547c06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef RuntimeDyldMachOCRTPBase&lt;RuntimeDyldMachOARM&gt; llvm::RuntimeDyldMachOARM::ParentT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoarm-h">RuntimeDyldMachOARM.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RuntimeDyldMachOARM() {#a1567da8c40ef25045b0c5d6777710256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RuntimeDyldMachOARM::RuntimeDyldMachOARM (<a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager">RuntimeDyld::MemoryManager</a> &amp; MM, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolresolver">JITSymbolResolver</a> &amp; Resolver)</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoarm-h">RuntimeDyldMachOARM.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachocrtpbase/#a4fd1220b5b8aa3aa6d20e7b79ec0f897">llvm::RuntimeDyldMachOCRTPBase&lt; RuntimeDyldMachOARM &gt;::RuntimeDyldMachOCRTPBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### decodeAddend() {#a4c19829e43ffe8064443b93c1946f9a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; int64_t &gt; llvm::RuntimeDyldMachOARM::decodeAddend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationentry">RelocationEntry</a> &amp; RE)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoarm-h">RuntimeDyldMachOARM.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa0f9c042e43bdf5138b1cb367b81c24c4">llvm::MachO::ARM_RELOC_BR24</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa191129bae4337ffd064cc19eeed66794">llvm::MachO::ARM_THUMB_RELOC_BR22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#a4ff8b7dc8dd3a4baddc147c6afd14c5e">llvm::RuntimeDyldMachO::memcpyAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a4c2824740d2fcf8bd1f44248bdcd4052">llvm::RelocationEntry::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#ad8a8e68671c17b1a8dde17365f897406">llvm::RuntimeDyldImpl::readBytesUnaligned</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a4b339d832145cb7ea79bbb90f5233897">llvm::RelocationEntry::RelType</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#aec2f9774e1098853d20912f579f501b9">llvm::RelocationEntry::SectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afce88102ca208741b470edac5342c4b3">llvm::RuntimeDyldImpl::Sections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd6925150e1774fabfaff17efd3f9b9e">llvm::SignExtend32</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>.</p>


<p>Referenced by <a href="#ad0cc2b7a34912033f88c7169756683cb">processRelocationRef</a>.</p>

</div>
</div>

### finalizeSection() {#a13b4460b917f0cf9c592c8e343c0a9a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::RuntimeDyldMachOARM::finalizeSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, unsigned SectionID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a> &amp; Section)</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoarm-h">RuntimeDyldMachOARM.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ab606ca40d5870295837712aa2056f90e">llvm::RuntimeDyldMachO::populateIndirectSymbolPointersSection</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### getJITSymbolFlags() {#a5be127713fc8105efd1e4261f09b1097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; JITSymbolFlags &gt; llvm::RuntimeDyldMachOARM::getJITSymbolFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/symbolref">SymbolRef</a> &amp; Sym)</td>
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

<p>Generate <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> from a libObject symbol.</p>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoarm-h">RuntimeDyldMachOARM.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/armjitsymbolflags/#a942d2281f1774d37e0225dfde4166ae4">llvm::ARMJITSymbolFlags::fromObjectSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afd8b5e95c65e3bb62ead0dd58732e382">llvm::RuntimeDyldImpl::getJITSymbolFlags</a>.</p>

</div>
</div>

### getMaxStubSize() {#ac7cced9dba460740451123177c754183}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RuntimeDyldMachOARM::getMaxStubSize ()</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoarm-h">RuntimeDyldMachOARM.h</a>.</p>

</div>
</div>

### getStubAlignment() {#aa1206a01edf6bfe9b415a5d896d0184c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::RuntimeDyldMachOARM::getStubAlignment ()</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoarm-h">RuntimeDyldMachOARM.h</a>.</p>

</div>
</div>

### isAddrTargetThumb() {#a66ea8b31d8dedc659636270db9b37790}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RuntimeDyldMachOARM::isAddrTargetThumb (unsigned SectionID, uint64_t Offset)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoarm-h">RuntimeDyldMachOARM.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#af95b57a597e7339755eeb2a4e0470943">llvm::RuntimeDyldImpl::GlobalSymbolTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afce88102ca208741b470edac5342c4b3">llvm::RuntimeDyldImpl::Sections</a> and <a href="/web-llvm/docs/api/classes/llvm/armjitsymbolflags/#a213d02a59bf1fd85318a706440ca169cabcaf88e63f6a97eb2b750bcaa8fc8d47">llvm::ARMJITSymbolFlags::Thumb</a>.</p>


<p>Referenced by <a href="#ad0cc2b7a34912033f88c7169756683cb">processRelocationRef</a>.</p>

</div>
</div>

### modifyAddressBasedOnFlags() {#a03e9aa0b6ef0d729148177445c3c72ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::RuntimeDyldMachOARM::modifyAddressBasedOnFlags (uint64_t Addr, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> Flags)</td>
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

<p>Modify the given target address based on the given symbol flags.</p>


<p>This can be used by subclasses to tweak addresses based on symbol flags, For example: the MachO/ARM target uses it to set the low bit if the target is a thumb symbol.</p>


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoarm-h">RuntimeDyldMachOARM.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/armjitsymbolflags/#a213d02a59bf1fd85318a706440ca169cabcaf88e63f6a97eb2b750bcaa8fc8d47">llvm::ARMJITSymbolFlags::Thumb</a>.</p>

</div>
</div>

### processRelocationRef() {#ad0cc2b7a34912033f88c7169756683cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; relocation_iterator &gt; llvm::RuntimeDyldMachOARM::processRelocationRef (unsigned SectionID, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a> RelI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a22b1a24bb422a0f0896dd84dff7933e2">ObjSectionToIDMap</a> &amp; ObjSectionToID, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a45d3097b94f4f98303ae36e6c6b7eee6">StubMap</a> &amp; Stubs)</td>
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


<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoarm-h">RuntimeDyldMachOARM.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a80213c5b59afecdd125a21b28b9637e9">llvm::RelocationEntry::Addend</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a9ee81c156267d67bed9008ed1a954214">llvm::RuntimeDyldImpl::addRelocationForSection</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a5db8c0beafbba922f1600e24fe6898bc">llvm::RuntimeDyldImpl::addRelocationForSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa0f9c042e43bdf5138b1cb367b81c24c4">llvm::MachO::ARM_RELOC_BR24</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfaf6e91ff8795152a02d4310c2debff044">llvm::MachO::ARM_RELOC_HALF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa7ddb841f45e7015c8cbb2694c78205d8">llvm::MachO::ARM_RELOC_HALF_SECTDIFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa280d7617c91ec05b4daf2c62202dc11f">llvm::MachO::ARM_RELOC_LOCAL_SECTDIFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa07e7b613f4b94b847079f1fc29db128b">llvm::MachO::ARM_RELOC_PAIR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa23dfa091acdb6c83ad85d8d54650bf9a">llvm::MachO::ARM_RELOC_PB_LA_PTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa94f9f6152db97d1fab522c2273d9e1d1">llvm::MachO::ARM_RELOC_SECTDIFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa7dcb46e83fcdbef07676ee5398501aa0">llvm::MachO::ARM_THUMB_32BIT_BRANCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa191129bae4337ffd064cc19eeed66794">llvm::MachO::ARM_THUMB_RELOC_BR22</a>, <a href="#a4c19829e43ffe8064443b93c1946f9a2">decodeAddend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa73b7678d1078f7640dc5c2d3c7de0fe3">llvm::MachO::GENERIC_RELOC_VANILLA</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a653a63105b842dd49a3a0921ce6a6d66">llvm::object::MachOObjectFile::getAnyRelocationType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a7bec3ca52f60d7ca088f0634a2e8f779">llvm::object::MachOObjectFile::getPlainRelocationExternal</a>, <a href="/web-llvm/docs/api/classes/llvm/object/relocationref/#acd93a9353f94b029cdfa295b88874b38">llvm::object::RelocationRef::getRawDataRefImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aaacf649b0759051f6c5327e44b82f8aa">llvm::object::MachOObjectFile::getRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#abaf648d88dc891045a7cd0e989789370">llvm::RuntimeDyldMachO::getRelocationEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ac01d9cc5d2d4a3b6662c7096e54bf8ad">llvm::RuntimeDyldMachO::getRelocationValueRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/relocationref/#a83bcab1a4f6a9aec56d6a40487f82a5e">llvm::object::RelocationRef::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#af95b57a597e7339755eeb2a4e0470943">llvm::RuntimeDyldImpl::GlobalSymbolTable</a>, <a href="#a66ea8b31d8dedc659636270db9b37790">isAddrTargetThumb</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a6fa763e1036861ba4581c5b3199b4fed">llvm::RelocationEntry::IsPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad07c873a9197ed022e779129f28ca028">llvm::object::MachOObjectFile::isRelocationScattered</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a22c888f22e370f437b1185af26ec21d3">llvm::RelocationEntry::IsTargetThumbFunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ab8281e64fb0c8b5bc71fdb5876df6c9d">llvm::RuntimeDyldMachO::makeValueAddendPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#acb7257d8eec274d18e7916a0d552a2d7">llvm::RuntimeDyldMachO::processScatteredVANILLA</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a4b339d832145cb7ea79bbb90f5233897">llvm::RelocationEntry::RelType</a>, <a href="/web-llvm/docs/api/classes/llvm/armjitsymbolflags/#a213d02a59bf1fd85318a706440ca169cabcaf88e63f6a97eb2b750bcaa8fc8d47">llvm::ARMJITSymbolFlags::Thumb</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h/#af4c1923d575768fb7d3dc8e15f49337c">UNIMPLEMENTED_RELOC</a>.</p>

</div>
</div>

### resolveRelocation() {#a42b1bc914cf22878c36dda7a8a31447e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldMachOARM::resolveRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationentry">RelocationEntry</a> &amp; RE, uint64_t Value)</td>
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

<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoarm-h">RuntimeDyldMachOARM.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a80213c5b59afecdd125a21b28b9637e9">llvm::RelocationEntry::Addend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa0f9c042e43bdf5138b1cb367b81c24c4">llvm::MachO::ARM_RELOC_BR24</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa7ddb841f45e7015c8cbb2694c78205d8">llvm::MachO::ARM_RELOC_HALF_SECTDIFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfafe908592b8ad4d11021be507dd0c2d72">llvm::MachO::ARM_RELOC_VANILLA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa191129bae4337ffd064cc19eeed66794">llvm::MachO::ARM_THUMB_RELOC_BR22</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#af2314475cd69d029c487927d58778a82">llvm::RuntimeDyldMachO::dumpRelocationToResolve</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a6fa763e1036861ba4581c5b3199b4fed">llvm::RelocationEntry::IsPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a22c888f22e370f437b1185af26ec21d3">llvm::RelocationEntry::IsTargetThumbFunc</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a4c2824740d2fcf8bd1f44248bdcd4052">llvm::RelocationEntry::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#ad8a8e68671c17b1a8dde17365f897406">llvm::RuntimeDyldImpl::readBytesUnaligned</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a4b339d832145cb7ea79bbb90f5233897">llvm::RelocationEntry::RelType</a>, <a href="/web-llvm/docs/api/structs/llvm/relocationentry/sectionpair/#ae8eb65258b27fa965c977f7e8e3d025d">llvm::RelocationEntry::SectionPair::SectionA</a>, <a href="/web-llvm/docs/api/structs/llvm/relocationentry/sectionpair/#abb7481bf753e95248d49ef2dda4ffb8d">llvm::RelocationEntry::SectionPair::SectionB</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#aec2f9774e1098853d20912f579f501b9">llvm::RelocationEntry::SectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#af42a708ce2732dc8b604b8d32384ee75">llvm::RelocationEntry::Sections</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afce88102ca208741b470edac5342c4b3">llvm::RuntimeDyldImpl::Sections</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a290c253a00603f2e0cde5f11c6db1372">llvm::RelocationEntry::Size</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#ac7b095afaba91cf9bf59313c8e94d2d9">llvm::RuntimeDyldImpl::writeBytesUnaligned</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### processBranchRelocation() {#afae474a6318b038aba1ac48d10c04984}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldMachOARM::processBranchRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationentry">RelocationEntry</a> &amp; RE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref">RelocationValueRef</a> &amp; Value, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a45d3097b94f4f98303ae36e6c6b7eee6">StubMap</a> &amp; Stubs)</td>
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



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoarm-h">RuntimeDyldMachOARM.h</a>.</p>

</div>
</div>

### processHALFSECTDIFFRelocation() {#a3d299374c2a496c13c972b9c97df798a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; relocation_iterator &gt; llvm::RuntimeDyldMachOARM::processHALFSECTDIFFRelocation (unsigned SectionID, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a> RelI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; BaseTObj, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a22b1a24bb422a0f0896dd84dff7933e2">ObjSectionToIDMap</a> &amp; ObjSectionToID)</td>
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



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoarm-h">RuntimeDyldMachOARM.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoarm-h">RuntimeDyldMachOARM.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
