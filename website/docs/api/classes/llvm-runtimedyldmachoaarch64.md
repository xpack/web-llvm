---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/runtimedyldmachoaarch64
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RuntimeDyldMachOAArch64` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::RuntimeDyldMachOAArch64 { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoaarch64-h">ExecutionEngine/RuntimeDyld/Targets/RuntimeDyldMachOAArch64.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top">uint64_t <a href="#aae48105a6608b944e1f9d80bbc1a92cb">TargetPtrT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21285419539ea9fbe890f8b9ac4180af">RuntimeDyldMachOAArch64</a> (RuntimeDyld::MemoryManager &amp;MM, JITSymbolResolver &amp;Resolver)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af97edb530616462405baf24836d68bea">getMaxStubSize</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e50a27477e977f8e991e69e778326b0">getStubAlignment</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57a3ea47fdc3f7e2de2a3939ea4e5a49">decodeAddend</a> (const RelocationEntry &amp;RE) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the addend encoded in the instruction / memory location. <a href="#a57a3ea47fdc3f7e2de2a3939ea4e5a49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8e4dcf9d13d4fcdd1b5988473729635">encodeAddend</a> (uint8_t *LocalAddress, unsigned NumBytes, MachO::RelocationInfoType RelType, int64_t Addend) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the addend encoded in the instruction. <a href="#ab8e4dcf9d13d4fcdd1b5988473729635">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a731c45f6ccf4dde3198c1d5147c3cb37">processRelocationRef</a> (unsigned SectionID, relocation_iterator RelI, const ObjectFile &amp;BaseObjT, ObjSectionToIDMap &amp;ObjSectionToID, StubMap &amp;Stubs) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses one or more object file relocations (some object files use relocation pairs) and stores it to Relocations or SymbolRelocations (this depends on the object file type). <a href="#a731c45f6ccf4dde3198c1d5147c3cb37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afab03ddb5f92e76f5c7bc8960baf72fa">resolveRelocation</a> (const RelocationEntry &amp;RE, uint64_t Value) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A object file specific relocation resolver. <a href="#afab03ddb5f92e76f5c7bc8960baf72fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd0e216bdcc14ae5d7982a3426ee09ad">finalizeSection</a> (const ObjectFile &amp;Obj, unsigned SectionID, const SectionRef &amp;Section)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a469534a7105e0e509761347a1230e1c9">processGOTRelocation</a> (const RelocationEntry &amp;RE, RelocationValueRef &amp;Value, StubMap &amp;Stubs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a547b1e4b87061c3e95960f23161aaa40">processSubtractRelocation</a> (unsigned SectionID, relocation_iterator RelI, const ObjectFile &amp;BaseObjT, ObjSectionToIDMap &amp;ObjSectionToID)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f6c963999c8ece69fa01e3157aefdeb">getRelocName</a> (uint32_t RelocType)</td>
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


<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoaarch64-h">RuntimeDyldMachOAArch64.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### TargetPtrT {#aae48105a6608b944e1f9d80bbc1a92cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef uint64_t llvm::RuntimeDyldMachOAArch64::TargetPtrT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoaarch64-h">RuntimeDyldMachOAArch64.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RuntimeDyldMachOAArch64() {#a21285419539ea9fbe890f8b9ac4180af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RuntimeDyldMachOAArch64::RuntimeDyldMachOAArch64 (<a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager">RuntimeDyld::MemoryManager</a> &amp; MM, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolresolver">JITSymbolResolver</a> &amp; Resolver)</td>
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



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoaarch64-h">RuntimeDyldMachOAArch64.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachocrtpbase/#a4fd1220b5b8aa3aa6d20e7b79ec0f897">llvm::RuntimeDyldMachOCRTPBase&lt; RuntimeDyldMachOAArch64 &gt;::RuntimeDyldMachOCRTPBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### decodeAddend() {#a57a3ea47fdc3f7e2de2a3939ea4e5a49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; int64_t &gt; llvm::RuntimeDyldMachOAArch64::decodeAddend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationentry">RelocationEntry</a> &amp; RE)</td>
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

<p>Extract the addend encoded in the instruction / memory location.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoaarch64-h">RuntimeDyldMachOAArch64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfaffc9c125707f9893dde566edfc79d656">llvm::MachO::ARM64_RELOC_BRANCH26</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa9c2201976aec041d4a781ee05a790caa">llvm::MachO::ARM64_RELOC_GOT_LOAD_PAGE21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfae1415496266b3e1d8ccf02a8359514be">llvm::MachO::ARM64_RELOC_GOT_LOAD_PAGEOFF12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfad557674652722e3e339b58dc9895df5a">llvm::MachO::ARM64_RELOC_PAGE21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa2498a9e498c85f7eec3117d24c409ad3">llvm::MachO::ARM64_RELOC_PAGEOFF12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa2f0c5edc91e3359ff834e95607773f31">llvm::MachO::ARM64_RELOC_POINTER_TO_GOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa948650248b0f0c167e5effe9dd552f2c">llvm::MachO::ARM64_RELOC_UNSIGNED</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a4c2824740d2fcf8bd1f44248bdcd4052">llvm::RelocationEntry::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a4b339d832145cb7ea79bbb90f5233897">llvm::RelocationEntry::RelType</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#aec2f9774e1098853d20912f579f501b9">llvm::RelocationEntry::SectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afce88102ca208741b470edac5342c4b3">llvm::RuntimeDyldImpl::Sections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a> and <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a290c253a00603f2e0cde5f11c6db1372">llvm::RelocationEntry::Size</a>.</p>


<p>Referenced by <a href="#a731c45f6ccf4dde3198c1d5147c3cb37">processRelocationRef</a>.</p>

</div>
</div>

### encodeAddend() {#ab8e4dcf9d13d4fcdd1b5988473729635}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldMachOAArch64::encodeAddend (uint8_t * LocalAddress, unsigned NumBytes, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bf">MachO::RelocationInfoType</a> RelType, int64_t Addend)</td>
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

<p>Extract the addend encoded in the instruction.</p>

<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoaarch64-h">RuntimeDyldMachOAArch64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfaffc9c125707f9893dde566edfc79d656">llvm::MachO::ARM64_RELOC_BRANCH26</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa9c2201976aec041d4a781ee05a790caa">llvm::MachO::ARM64_RELOC_GOT_LOAD_PAGE21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfae1415496266b3e1d8ccf02a8359514be">llvm::MachO::ARM64_RELOC_GOT_LOAD_PAGEOFF12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfad557674652722e3e339b58dc9895df5a">llvm::MachO::ARM64_RELOC_PAGE21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa2498a9e498c85f7eec3117d24c409ad3">llvm::MachO::ARM64_RELOC_PAGEOFF12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa2f0c5edc91e3359ff834e95607773f31">llvm::MachO::ARM64_RELOC_POINTER_TO_GOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa948650248b0f0c167e5effe9dd552f2c">llvm::MachO::ARM64_RELOC_UNSIGNED</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#afab03ddb5f92e76f5c7bc8960baf72fa">resolveRelocation</a>.</p>

</div>
</div>

### finalizeSection() {#afd0e216bdcc14ae5d7982a3426ee09ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::RuntimeDyldMachOAArch64::finalizeSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, unsigned SectionID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a> &amp; Section)</td>
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



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoaarch64-h">RuntimeDyldMachOAArch64.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### getMaxStubSize() {#af97edb530616462405baf24836d68bea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RuntimeDyldMachOAArch64::getMaxStubSize ()</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoaarch64-h">RuntimeDyldMachOAArch64.h</a>.</p>

</div>
</div>

### getStubAlignment() {#a7e50a27477e977f8e991e69e778326b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::RuntimeDyldMachOAArch64::getStubAlignment ()</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoaarch64-h">RuntimeDyldMachOAArch64.h</a>.</p>

</div>
</div>

### processRelocationRef() {#a731c45f6ccf4dde3198c1d5147c3cb37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; relocation_iterator &gt; llvm::RuntimeDyldMachOAArch64::processRelocationRef (unsigned SectionID, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a> RelI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a22b1a24bb422a0f0896dd84dff7933e2">ObjSectionToIDMap</a> &amp; ObjSectionToID, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a45d3097b94f4f98303ae36e6c6b7eee6">StubMap</a> &amp; Stubs)</td>
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


<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoaarch64-h">RuntimeDyldMachOAArch64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a80213c5b59afecdd125a21b28b9637e9">llvm::RelocationEntry::Addend</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a9ee81c156267d67bed9008ed1a954214">llvm::RuntimeDyldImpl::addRelocationForSection</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a5db8c0beafbba922f1600e24fe6898bc">llvm::RuntimeDyldImpl::addRelocationForSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa91ead49defe15a5f34e4e0f4a2365d09">llvm::MachO::ARM64_RELOC_ADDEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa9c2201976aec041d4a781ee05a790caa">llvm::MachO::ARM64_RELOC_GOT_LOAD_PAGE21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfae1415496266b3e1d8ccf02a8359514be">llvm::MachO::ARM64_RELOC_GOT_LOAD_PAGEOFF12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa2f0c5edc91e3359ff834e95607773f31">llvm::MachO::ARM64_RELOC_POINTER_TO_GOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa78b1160279497250f62c414267853f1f">llvm::MachO::ARM64_RELOC_SUBTRACTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a57a3ea47fdc3f7e2de2a3939ea4e5a49">decodeAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a942691b0e7a01c33a7aa6b36b28472d2">llvm::object::MachOObjectFile::getAnyRelocationLength</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a86eeaa5626787e6a0c62d7fef9ea33e9">llvm::object::MachOObjectFile::getAnyRelocationPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a653a63105b842dd49a3a0921ce6a6d66">llvm::object::MachOObjectFile::getAnyRelocationType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a7bec3ca52f60d7ca088f0634a2e8f779">llvm::object::MachOObjectFile::getPlainRelocationExternal</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a99471e40aa719f7de1a81c38b8b129cc">llvm::object::MachOObjectFile::getPlainRelocationSymbolNum</a>, <a href="/web-llvm/docs/api/classes/llvm/object/relocationref/#acd93a9353f94b029cdfa295b88874b38">llvm::object::RelocationRef::getRawDataRefImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aaacf649b0759051f6c5327e44b82f8aa">llvm::object::MachOObjectFile::getRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#abaf648d88dc891045a7cd0e989789370">llvm::RuntimeDyldMachO::getRelocationEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ac01d9cc5d2d4a3b6662c7096e54bf8ad">llvm::RuntimeDyldMachO::getRelocationValueRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a6fa763e1036861ba4581c5b3199b4fed">llvm::RelocationEntry::IsPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad07c873a9197ed022e779129f28ca028">llvm::object::MachOObjectFile::isRelocationScattered</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ab8281e64fb0c8b5bc71fdb5876df6c9d">llvm::RuntimeDyldMachO::makeValueAddendPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a4b339d832145cb7ea79bbb90f5233897">llvm::RelocationEntry::RelType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a> and <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a290c253a00603f2e0cde5f11c6db1372">llvm::RelocationEntry::Size</a>.</p>

</div>
</div>

### resolveRelocation() {#afab03ddb5f92e76f5c7bc8960baf72fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldMachOAArch64::resolveRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationentry">RelocationEntry</a> &amp; RE, uint64_t Value)</td>
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

<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoaarch64-h">RuntimeDyldMachOAArch64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a80213c5b59afecdd125a21b28b9637e9">llvm::RelocationEntry::Addend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa91ead49defe15a5f34e4e0f4a2365d09">llvm::MachO::ARM64_RELOC_ADDEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfaffc9c125707f9893dde566edfc79d656">llvm::MachO::ARM64_RELOC_BRANCH26</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa9c2201976aec041d4a781ee05a790caa">llvm::MachO::ARM64_RELOC_GOT_LOAD_PAGE21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfae1415496266b3e1d8ccf02a8359514be">llvm::MachO::ARM64_RELOC_GOT_LOAD_PAGEOFF12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfad557674652722e3e339b58dc9895df5a">llvm::MachO::ARM64_RELOC_PAGE21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa2498a9e498c85f7eec3117d24c409ad3">llvm::MachO::ARM64_RELOC_PAGEOFF12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa2f0c5edc91e3359ff834e95607773f31">llvm::MachO::ARM64_RELOC_POINTER_TO_GOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa78b1160279497250f62c414267853f1f">llvm::MachO::ARM64_RELOC_SUBTRACTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfafe1a3fd5641250ed3fdeb7fd0af18e22">llvm::MachO::ARM64_RELOC_TLVP_LOAD_PAGE21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfac7d55fc8ce97acc45fdfbaebce10ff42">llvm::MachO::ARM64_RELOC_TLVP_LOAD_PAGEOFF12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa948650248b0f0c167e5effe9dd552f2c">llvm::MachO::ARM64_RELOC_UNSIGNED</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#af2314475cd69d029c487927d58778a82">llvm::RuntimeDyldMachO::dumpRelocationToResolve</a>, <a href="#ab8e4dcf9d13d4fcdd1b5988473729635">encodeAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a6fa763e1036861ba4581c5b3199b4fed">llvm::RelocationEntry::IsPCRel</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a4c2824740d2fcf8bd1f44248bdcd4052">llvm::RelocationEntry::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a4b339d832145cb7ea79bbb90f5233897">llvm::RelocationEntry::RelType</a>, <a href="/web-llvm/docs/api/structs/llvm/relocationentry/sectionpair/#ae8eb65258b27fa965c977f7e8e3d025d">llvm::RelocationEntry::SectionPair::SectionA</a>, <a href="/web-llvm/docs/api/structs/llvm/relocationentry/sectionpair/#abb7481bf753e95248d49ef2dda4ffb8d">llvm::RelocationEntry::SectionPair::SectionB</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#aec2f9774e1098853d20912f579f501b9">llvm::RelocationEntry::SectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#af42a708ce2732dc8b604b8d32384ee75">llvm::RelocationEntry::Sections</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afce88102ca208741b470edac5342c4b3">llvm::RuntimeDyldImpl::Sections</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a290c253a00603f2e0cde5f11c6db1372">llvm::RelocationEntry::Size</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#ac7b095afaba91cf9bf59313c8e94d2d9">llvm::RuntimeDyldImpl::writeBytesUnaligned</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### processGOTRelocation() {#a469534a7105e0e509761347a1230e1c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldMachOAArch64::processGOTRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationentry">RelocationEntry</a> &amp; RE, <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref">RelocationValueRef</a> &amp; Value, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a45d3097b94f4f98303ae36e6c6b7eee6">StubMap</a> &amp; Stubs)</td>
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



<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoaarch64-h">RuntimeDyldMachOAArch64.h</a>.</p>

</div>
</div>

### processSubtractRelocation() {#a547b1e4b87061c3e95960f23161aaa40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; relocation_iterator &gt; llvm::RuntimeDyldMachOAArch64::processSubtractRelocation (unsigned SectionID, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a> RelI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; BaseObjT, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a22b1a24bb422a0f0896dd84dff7933e2">ObjSectionToIDMap</a> &amp; ObjSectionToID)</td>
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



<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoaarch64-h">RuntimeDyldMachOAArch64.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getRelocName() {#a8f6c963999c8ece69fa01e3157aefdeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::RuntimeDyldMachOAArch64::getRelocName (uint32_t RelocType)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoaarch64-h">RuntimeDyldMachOAArch64.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldmachoaarch64-h">RuntimeDyldMachOAArch64.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
