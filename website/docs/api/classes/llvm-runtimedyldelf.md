---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/runtimedyldelf
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RuntimeDyldELF` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::RuntimeDyldELF { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">ExecutionEngine/RuntimeDyld/RuntimeDyldELF.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl">RuntimeDyldImpl</a></td>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/runtimedyldelfmips">RuntimeDyldELFMips</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acff5ec4cbde9c943ffd383afdf1e0bb1">RuntimeDyldELF</a> (RuntimeDyld::MemoryManager &amp;MemMgr, JITSymbolResolver &amp;Resolver)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19bde166e1cf015f0a9e5a2786274299">~RuntimeDyldELF</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/loadedobjectinfo">RuntimeDyld::LoadedObjectInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eaeb3bf0be2e6f9ffce10bab1dcb5f2">loadObject</a> (const object::ObjectFile &amp;O) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66fd1d01cea1089f326652a523d4049a">resolveRelocation</a> (const RelocationEntry &amp;RE, uint64_t Value) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A object file specific relocation resolver. <a href="#a66fd1d01cea1089f326652a523d4049a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9cec5473cec6044442bceccc2fcee96">processRelocationRef</a> (unsigned SectionID, relocation_iterator RelI, const ObjectFile &amp;Obj, ObjSectionToIDMap &amp;ObjSectionToID, StubMap &amp;Stubs) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses one or more object file relocations (some object files use relocation pairs) and stores it to Relocations or SymbolRelocations (this depends on the object file type). <a href="#ad9cec5473cec6044442bceccc2fcee96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dd9538877dad99321dc7babf35d9e17">isCompatibleFile</a> (const object::ObjectFile &amp;Obj) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02aac305b3611765b79dd39adb8dea9c">registerEHFrames</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34d452366da541e62d1f37b1f284800d">finalizeLoad</a> (const ObjectFile &amp;Obj, ObjSectionToIDMap &amp;SectionMap) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1881f42b5c49ba8ed8d1056ee2ff90d8">getGOTEntrySize</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d240a4c8aece0e073b6f44d2391f630">resolveRelocation</a> (const SectionEntry &amp;Section, uint64_t Offset, uint64_t Value, uint32_t Type, int64_t Addend, uint64_t SymOffset=0, SID SectionID=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17f15f20ced65596361b435a3a3228a4">resolveX86_64Relocation</a> (const SectionEntry &amp;Section, uint64_t Offset, uint64_t Value, uint32_t Type, int64_t Addend, uint64_t SymOffset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdae956d3e40802d798ac9cb10e3ccdb">resolveX86Relocation</a> (const SectionEntry &amp;Section, uint64_t Offset, uint32_t Value, uint32_t Type, int32_t Addend)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab298b9fefcf46e29e206c740533798c8">resolveAArch64Relocation</a> (const SectionEntry &amp;Section, uint64_t Offset, uint64_t Value, uint32_t Type, int64_t Addend)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6fba3fe82f003fec8c741cb2cd3196c">resolveAArch64ShortBranch</a> (unsigned SectionID, relocation_iterator RelI, const RelocationValueRef &amp;Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae85005c988a5dd5abaa38ea3a7ef7780">resolveAArch64Branch</a> (unsigned SectionID, const RelocationValueRef &amp;Value, relocation_iterator RelI, StubMap &amp;Stubs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bb6eb84bfbc12012604010e7a615fc2">resolveARMRelocation</a> (const SectionEntry &amp;Section, uint64_t Offset, uint32_t Value, uint32_t Type, int32_t Addend)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1896d71d1aff41f1f34d7196385efce1">resolveLoongArch64Relocation</a> (const SectionEntry &amp;Section, uint64_t Offset, uint64_t Value, uint32_t Type, int64_t Addend)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54e89f410dcdf87b323de78d9ed60a4b">resolveLoongArch64ShortBranch</a> (unsigned SectionID, relocation_iterator RelI, const RelocationValueRef &amp;Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a640a07eed1fadc89947e957abf2246e9">resolveLoongArch64Branch</a> (unsigned SectionID, const RelocationValueRef &amp;Value, relocation_iterator RelI, StubMap &amp;Stubs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48bf5d629d177ec40293610f7a2636fa">resolvePPC32Relocation</a> (const SectionEntry &amp;Section, uint64_t Offset, uint64_t Value, uint32_t Type, int64_t Addend)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49bcf0947ada129ba1cb1b4295b869fa">resolvePPC64Relocation</a> (const SectionEntry &amp;Section, uint64_t Offset, uint64_t Value, uint32_t Type, int64_t Addend)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af054f6b6a2d7b0cc4222763dd8330070">resolveSystemZRelocation</a> (const SectionEntry &amp;Section, uint64_t Offset, uint64_t Value, uint32_t Type, int64_t Addend)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cf83cfa0a8085c11c05ff1fb6c44f98">resolveBPFRelocation</a> (const SectionEntry &amp;Section, uint64_t Offset, uint64_t Value, uint32_t Type, int64_t Addend)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a912f2ec871e6617b38c99d8f347b0690">resolveRISCVRelocation</a> (const SectionEntry &amp;Section, uint64_t Offset, uint64_t Value, uint32_t Type, int64_t Addend, SID SectionID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac45eee80e2c3d53afab5af51e21a95e2">getMaxStubSize</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f4278e151742ba4b371319aa4f431df">getStubAlignment</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a593a587513a43905825c890ea0a18508">setMipsABI</a> (const ObjectFile &amp;Obj) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6a3add2b8fb55829a867d0b842b78c2">findPPC64TOCSection</a> (const object::ELFObjectFileBase &amp;Obj, ObjSectionToIDMap &amp;LocalSections, RelocationValueRef &amp;Rel)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace5627b647f9be2b4950d433c3d05fb5">findOPDEntrySection</a> (const object::ELFObjectFileBase &amp;Obj, ObjSectionToIDMap &amp;LocalSections, RelocationValueRef &amp;Rel)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sectionentry">SectionEntry</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bfe55c4d3026dcbca4270d97058d19f">getSection</a> (unsigned SectionID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1b4d51473386094e1c52a8a47ecfdc5">allocateGOTEntries</a> (unsigned no)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc1bb9c0360106a2715f1aa2b0c94c59">findOrAllocGOTEntry</a> (const RelocationValueRef &amp;Value, unsigned GOTRelType)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38ebdcdd0245e27457fd09c265bf2bd5">resolveGOTOffsetRelocation</a> (unsigned SectionID, uint64_t Offset, uint64_t GOTOffset, uint32_t Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/relocationentry">RelocationEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4576e8a5663a39643a3622a736e83e4">computeGOTOffsetRE</a> (uint64_t GOTOffset, uint64_t SymbolOffset, unsigned Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f76c7870e4738e285c0645edb69472a">computePlaceholderAddress</a> (unsigned SectionID, uint64_t Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae81b1be82c013b381b3e109097fa33b7">processSimpleRelocation</a> (unsigned SectionID, uint64_t Offset, unsigned RelType, RelocationValueRef Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1af3fb770bca9c6996a8035c9a89676">getMatchingLoRelocation</a> (uint32_t RelType, bool IsLocal=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc70b638ff469e6d9074ba3128ebaaa6">createIFuncResolver</a> (uint8_t *Addr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the code for the IFunc resolver at the given address. <a href="#afc70b638ff469e6d9074ba3128ebaaa6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86913a878170b563f12b160635d68379">createIFuncStub</a> (unsigned IFuncStubSectionID, uint64_t IFuncResolverOffset, uint64_t IFuncStubOffset, unsigned IFuncSectionID, uint64_t IFuncOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the code for an IFunc stub for the IFunc that is defined in section IFuncSectionID at offset IFuncOffset. <a href="#a86913a878170b563f12b160635d68379">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02af7f1f06530a468085fc57b027fea9">getMaxIFuncStubSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the maximum size of a stub created by createIFuncStub() <a href="#a02af7f1f06530a468085fc57b027fea9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2657d26ba19f02f5ce80b504a70e5d0">processNewSymbol</a> (const SymbolRef &amp;ObjSymbol, SymbolTableEntry &amp;Entry) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cd1b30a6e28245bbac1cdc4acad3764">relocationNeedsGot</a> (const RelocationRef &amp;R) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6c81668bdd2938476b5489e6ff95863">relocationNeedsStub</a> (const RelocationRef &amp;R) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae8b68599cc13956decf8d1755670cb8">processX86_64GOTTPOFFRelocation</a> (unsigned SectionID, uint64_t Offset, RelocationValueRef Value, int64_t Addend)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedf426a271c1835cf3793dfa3b2c1384">processX86_64TLSRelocation</a> (unsigned SectionID, uint64_t Offset, uint64_t RelType, RelocationValueRef Value, int64_t Addend, const RelocationRef &amp;GetAddrRelocation)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a8ad6e355243eab1c1a3993f9bda8b2d1">SID</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a8ad6e355243eab1c1a3993f9bda8b2d1">SID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bcf96d2eb6e594a4602399e60b8eddb">SectionToGOTMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a094ed1c8af6bd5bbd8c2a6e0e3f9bfd8">GOTSectionID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc2032a0ce54f51f3ee03b81bcb9ff0f">CurrentGOTIndex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93aca5444595503ba945d58064fb9966">GOTSymbolOffsets</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref">RelocationValueRef</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry">RelocationEntry</a> &gt;, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b15effe97176d5e62f91fe7db8463ec">PendingRelocs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a8ad6e355243eab1c1a3993f9bda8b2d1">SID</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ca2ed40e8a6e11a13ded4e2923f263b">UnregisteredEHFrameSections</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref">RelocationValueRef</a>, uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae72a69469ae3feb90d5a4d140f66099f">GOTOffsetMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a266feca7a5a4cb63a7509a59011803">IFuncStubSectionID</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the current IFunc stub section. <a href="#a9a266feca7a5a4cb63a7509a59011803">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9515648f67b33d1ceed8772f9ca5b0b9">IFuncStubOffset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current offset into the IFunc stub section. <a href="#a9515648f67b33d1ceed8772f9ca5b0b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; IFuncStub, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a904cff557afa8f3c7b5d97183fbbdae0">IFuncStubs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The IFunc stubs. <a href="#a904cff557afa8f3c7b5d97183fbbdae0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf">RuntimeDyldELF</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a43382614f69bdae93a85b8dd43d597">create</a> (Triple::ArchType Arch, RuntimeDyld::MemoryManager &amp;MemMgr, JITSymbolResolver &amp;Resolver)</td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RuntimeDyldELF() {#acff5ec4cbde9c943ffd383afdf1e0bb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RuntimeDyldELF::RuntimeDyldELF (<a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager">RuntimeDyld::MemoryManager</a> &amp; MemMgr, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolresolver">JITSymbolResolver</a> &amp; Resolver)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a9bc5cceb63d0ccdf06f64b587f1cd80e">llvm::RuntimeDyldImpl::MemMgr</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a688485f7fca0fadd7e492dc12218cd16">llvm::RuntimeDyldImpl::Resolver</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a369fb04a71a831101a7bdfa873cb33d0">llvm::RuntimeDyldImpl::RuntimeDyldImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelfmips/#aad15bfdd2152a82763b261fa3831f39c">llvm::RuntimeDyldELFMips::RuntimeDyldELFMips</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RuntimeDyldELF() {#a19bde166e1cf015f0a9e5a2786274299}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RuntimeDyldELF::~RuntimeDyldELF ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#aab98755e5bcb6af82707f749aab3c474">llvm::RuntimeDyldImpl::Arch</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a9bc5cceb63d0ccdf06f64b587f1cd80e">llvm::RuntimeDyldImpl::MemMgr</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a688485f7fca0fadd7e492dc12218cd16">llvm::RuntimeDyldImpl::Resolver</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### finalizeLoad() {#a34d452366da541e62d1f37b1f284800d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::RuntimeDyldELF::finalizeLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a22b1a24bb422a0f0896dd84dff7933e2">ObjSectionToIDMap</a> &amp; SectionMap)</td>
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



<p>Declaration at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 2687 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a4a30a3fae601106b8b33c0871aa3069d">getAddress</a>, <a href="#a1881f42b5c49ba8ed8d1056ee2ff90d8">getGOTEntrySize</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a940c75979815d8de459e2791701e4853">llvm::RuntimeDyldImpl::IsMipsN32ABI</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a3cd00aae21297a0a228ef733b6b47ba4">llvm::RuntimeDyldImpl::IsMipsN64ABI</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#aa431374d08ab68077b4ba96efe411c72">llvm::RuntimeDyldImpl::IsMipsO32ABI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a9bc5cceb63d0ccdf06f64b587f1cd80e">llvm::RuntimeDyldImpl::MemMgr</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#af9eb4120f90b00d473f53ce9877388d0">llvm::object::ObjectFile::section_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a3e48ce01c39d5e5e36eced4e3d3f6f23">llvm::object::ObjectFile::section_end</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afce88102ca208741b470edac5342c4b3">llvm::RuntimeDyldImpl::Sections</a>, <a href="#a3bcf96d2eb6e594a4602399e60b8eddb">SectionToGOTMap</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>.</p>

</div>
</div>

### isCompatibleFile() {#a7dd9538877dad99321dc7babf35d9e17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RuntimeDyldELF::isCompatibleFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj)</td>
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



<p>Declaration at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 2786 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/binary/#ae470b1ff27e3d72e61fcb4a97fd0a461">llvm::object::Binary::isELF</a>.</p>

</div>
</div>

### loadObject() {#a8eaeb3bf0be2e6f9ffce10bab1dcb5f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; RuntimeDyld::LoadedObjectInfo &gt; llvm::RuntimeDyldELF::loadObject (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; O)</td>
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



<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a43f4ef223d6929940f48a82219fc075f">llvm::RuntimeDyldImpl::ErrorStr</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#accd3f8de90a127cd1e8538b9df936681">llvm::RuntimeDyldImpl::HasError</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afe85af578989c7f3e9627866e7fa4962">llvm::RuntimeDyldImpl::loadObjectImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a065ed35b75b9eeb5cca1aa73bcae7183">llvm::logAllUnhandledErrors</a>.</p>

</div>
</div>

### processRelocationRef() {#ad9cec5473cec6044442bceccc2fcee96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; relocation_iterator &gt; llvm::RuntimeDyldELF::processRelocationRef (unsigned SectionID, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a> RelI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a22b1a24bb422a0f0896dd84dff7933e2">ObjSectionToIDMap</a> &amp; ObjSectionToID, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a45d3097b94f4f98303ae36e6c6b7eee6">StubMap</a> &amp; Stubs)</td>
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

<p>Parses one or more object file relocations (some object files use relocation pairs) and stores it to Relocations or SymbolRelocations (this depends on the object file type).</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Iterator to the next relocation that needs to be parsed.</p></dd>
</dl>


<p>Declaration at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 1561 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a6d5df0cfd7a0b0c0854555554396efd9">llvm::Triple::aarch64_be</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref/#a0a2be52a18ce9abea53f265b748a4504">llvm::RelocationValueRef::Addend</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a9ee81c156267d67bed9008ed1a954214">llvm::RuntimeDyldImpl::addRelocationForSection</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a5db8c0beafbba922f1600e24fe6898bc">llvm::RuntimeDyldImpl::addRelocationForSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#aab98755e5bcb6af82707f749aab3c474">llvm::RuntimeDyldImpl::Arch</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">llvm::Triple::arm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#ad76b1f4f9f930bb5d8942b8bb05875cc">llvm::RuntimeDyldImpl::createStubFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a16750618ea029a05ca12ed94d9558f24">llvm::ELF::decodePPC64LocalEntryOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a385e9c7b04e7af58e4afa80c8c70f0aea88f9ea5de9aece90de6bc645eb60b1e8">llvm::ELF::EF_PPC64_ABI</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#aa4b6bd8b78d9901ada802b2363341628">llvm::RuntimeDyldImpl::findOrEmitSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfrelocationref/#a705b6e9363a0fe644bea482dc295cf83">llvm::object::ELFRelocationRef::getAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#ae7343d4154aa28a8bc872b1de1e40df4">llvm::RuntimeDyldImpl::getMaxStubSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/relocationref/#a6aa71653bc8ee52493adf9343d9ac44d">llvm::object::RelocationRef::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#aec0cb1ff46a65c16dbfd773bc5033257">llvm::object::ELFObjectFileBase::getPlatformFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/object/relocationref/#a83bcab1a4f6a9aec56d6a40487f82a5e">llvm::object::RelocationRef::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/relocationref/#a3a14c842fb698c94611978d94b7cf166">llvm::object::RelocationRef::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#af95b57a597e7339755eeb2a4e0470943">llvm::RuntimeDyldImpl::GlobalSymbolTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a940c75979815d8de459e2791701e4853">llvm::RuntimeDyldImpl::IsMipsN32ABI</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a3cd00aae21297a0a228ef733b6b47ba4">llvm::RuntimeDyldImpl::IsMipsN64ABI</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#aa431374d08ab68077b4ba96efe411c72">llvm::RuntimeDyldImpl::IsMipsO32ABI</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a63d27a7beb22a7596ed2f10bdb9a8dda">llvm::RuntimeDyldImpl::IsTargetLittleEndian</a>, <a href="/web-llvm/docs/api/classes/llvm/object/sectionref/#ab78cb663ac0805b3be2756a9148e1d76">llvm::object::SectionRef::isText</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a065ed35b75b9eeb5cca1aa73bcae7183">llvm::logAllUnhandledErrors</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a7e69e3edde4260406241be26e08fbd7c">llvm::Triple::loongarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a9bc5cceb63d0ccdf06f64b587f1cd80e">llvm::RuntimeDyldImpl::MemMgr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">llvm::Triple::ppc64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">llvm::Triple::ppc64le</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#ad8a8e68671c17b1a8dde17365f897406">llvm::RuntimeDyldImpl::readBytesUnaligned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae84559483d0c0f2bddc802ce6f76dd8b">llvm::Triple::riscv32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae4763cb7c05a2a59ce27d51040bf4b08">llvm::Triple::riscv64</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a3e48ce01c39d5e5e36eced4e3d3f6f23">llvm::object::ObjectFile::section_end</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref/#af46f2a8319e7835a38b0b2baaccf13c9">llvm::RelocationValueRef::SectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afce88102ca208741b470edac5342c4b3">llvm::RuntimeDyldImpl::Sections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd6925150e1774fabfaff17efd3f9b9e">llvm::SignExtend32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a8a501fedaaa3e562541580b8f1db3975">llvm::object::SymbolRef::ST_Data</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04afe6722fa933ffee4c116ee60c2de5049">llvm::object::SymbolRef::ST_Debug</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a2fcf5b0171fb8526218be425765b5da1">llvm::object::SymbolRef::ST_Function</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a076f193658db35c0f4d60f9e0a3e329f">llvm::object::SymbolRef::ST_Other</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a2d334a713a4916963744a0cc31ab9552">llvm::object::SymbolRef::ST_Unknown</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#a7bc0f444aecc9b7aaef7facdb3d2bddb">llvm::object::SymbolicFile::symbol_end</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a194e81d6cc18d873ef123d3f78cedce7">llvm::RelocationEntry::SymOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af0a491fddfa0a73d2b9074b587ca337f">llvm::Triple::systemz</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a2e2a818eaa1b3883192a5ae226b38a9e">llvm::RuntimeDyldImpl::writeInt32BE</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">llvm::Triple::x86</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>

</div>
</div>

### registerEHFrames() {#a02aac305b3611765b79dd39adb8dea9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::registerEHFrames ()</td>
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



<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a9bc5cceb63d0ccdf06f64b587f1cd80e">llvm::RuntimeDyldImpl::MemMgr</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afce88102ca208741b470edac5342c4b3">llvm::RuntimeDyldImpl::Sections</a>.</p>

</div>
</div>

### resolveRelocation() {#a66fd1d01cea1089f326652a523d4049a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::resolveRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationentry">RelocationEntry</a> &amp; RE, uint64_t Value)</td>
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

<p>Declaration at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 1362 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a80213c5b59afecdd125a21b28b9637e9">llvm::RelocationEntry::Addend</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a4c2824740d2fcf8bd1f44248bdcd4052">llvm::RelocationEntry::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a4b339d832145cb7ea79bbb90f5233897">llvm::RelocationEntry::RelType</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#aec2f9774e1098853d20912f579f501b9">llvm::RelocationEntry::SectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afce88102ca208741b470edac5342c4b3">llvm::RuntimeDyldImpl::Sections</a> and <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a194e81d6cc18d873ef123d3f78cedce7">llvm::RelocationEntry::SymOffset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getGOTEntrySize() {#a1881f42b5c49ba8ed8d1056ee2ff90d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::RuntimeDyldELF::getGOTEntrySize ()</td>
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



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 2579 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a6d5df0cfd7a0b0c0854555554396efd9">llvm::Triple::aarch64_be</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#aab98755e5bcb6af82707f749aab3c474">llvm::RuntimeDyldImpl::Arch</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">llvm::Triple::arm</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a940c75979815d8de459e2791701e4853">llvm::RuntimeDyldImpl::IsMipsN32ABI</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a3cd00aae21297a0a228ef733b6b47ba4">llvm::RuntimeDyldImpl::IsMipsN64ABI</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#aa431374d08ab68077b4ba96efe411c72">llvm::RuntimeDyldImpl::IsMipsO32ABI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a7e69e3edde4260406241be26e08fbd7c">llvm::Triple::loongarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a867c596b0454c5bbeeb1ff490b9d70bc">llvm::Triple::mips</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a9ff8c8868a9f1892ce3f896e7f0fe1e5">llvm::Triple::mips64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae60fc4f421b40b84a536b24fc2a1919f">llvm::Triple::mips64el</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5fb4823bc5bbdad4684399b118ccace8">llvm::Triple::mipsel</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">llvm::Triple::ppc64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">llvm::Triple::ppc64le</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af0a491fddfa0a73d2b9074b587ca337f">llvm::Triple::systemz</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">llvm::Triple::thumb</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">llvm::Triple::x86</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>


<p>Referenced by <a href="#a34d452366da541e62d1f37b1f284800d">finalizeLoad</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### allocateGOTEntries() {#af1b4d51473386094e1c52a8a47ecfdc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::RuntimeDyldELF::allocateGOTEntries (unsigned no)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 2615 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### computeGOTOffsetRE() {#ae4576e8a5663a39643a3622a736e83e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RelocationEntry llvm::RuntimeDyldELF::computeGOTOffsetRE (uint64_t GOTOffset, uint64_t SymbolOffset, unsigned Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 2656 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### computePlaceholderAddress() {#a8f76c7870e4738e285c0645edb69472a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::RuntimeDyldELF::computePlaceholderAddress (unsigned SectionID, uint64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 1419 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### createIFuncResolver() {#afc70b638ff469e6d9074ba3128ebaaa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::createIFuncResolver (uint8_t * Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create the code for the IFunc resolver at the given address.</p>


<p>This code works together with the stubs created in createIFuncStub() to call the resolver function and then jump to the real function address. It must not be larger than 64B.</p>


<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 2790 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### createIFuncStub() {#a86913a878170b563f12b160635d68379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::createIFuncStub (unsigned IFuncStubSectionID, uint64_t IFuncResolverOffset, uint64_t IFuncStubOffset, unsigned IFuncSectionID, uint64_t IFuncOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create the code for an IFunc stub for the IFunc that is defined in section IFuncSectionID at offset IFuncOffset.</p>


<p>The IFunc resolver created by createIFuncResolver() is defined in the section IFuncStubSectionID at offset IFuncResolverOffset. The code should be written into the section with the id IFuncStubSectionID at the offset IFuncStubOffset.</p>


<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 2831 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### findOPDEntrySection() {#ace5627b647f9be2b4950d433c3d05fb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::RuntimeDyldELF::findOPDEntrySection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase">object::ELFObjectFileBase</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a22b1a24bb422a0f0896dd84dff7933e2">ObjSectionToIDMap</a> &amp; LocalSections, <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref">RelocationValueRef</a> &amp; Rel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 905 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### findOrAllocGOTEntry() {#adc1bb9c0360106a2715f1aa2b0c94c59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::RuntimeDyldELF::findOrAllocGOTEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref">RelocationValueRef</a> &amp; Value, unsigned GOTRelType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 2627 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### findPPC64TOCSection() {#ac6a3add2b8fb55829a867d0b842b78c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::RuntimeDyldELF::findPPC64TOCSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase">object::ELFObjectFileBase</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a22b1a24bb422a0f0896dd84dff7933e2">ObjSectionToIDMap</a> &amp; LocalSections, <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref">RelocationValueRef</a> &amp; Rel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 864 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### getMatchingLoRelocation() {#ad1af3fb770bca9c6996a8035c9a89676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::RuntimeDyldELF::getMatchingLoRelocation (uint32_t RelType, bool IsLocal=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 1432 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### getMaxIFuncStubSize() {#a02af7f1f06530a468085fc57b027fea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RuntimeDyldELF::getMaxIFuncStubSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the maximum size of a stub created by createIFuncStub()</p>

<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 2887 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### getMaxStubSize() {#ac45eee80e2c3d53afab5af51e21a95e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RuntimeDyldELF::getMaxStubSize ()</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>.</p>

</div>
</div>

### getSection() {#a9bfe55c4d3026dcbca4270d97058d19f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionEntry &amp; llvm::RuntimeDyldELF::getSection (unsigned SectionID)</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>.</p>

</div>
</div>

### getStubAlignment() {#a2f4278e151742ba4b371319aa4f431df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::RuntimeDyldELF::getStubAlignment ()</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>.</p>

</div>
</div>

### processNewSymbol() {#af2657d26ba19f02f5ce80b504a70e5d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::processNewSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/symbolref">SymbolRef</a> &amp; ObjSymbol, <a href="/web-llvm/docs/api/classes/llvm/symboltableentry">SymbolTableEntry</a> &amp; Entry)</td>
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



<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 2662 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### processSimpleRelocation() {#ae81b1be82c013b381b3e109097fa33b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::processSimpleRelocation (unsigned SectionID, uint64_t Offset, unsigned RelType, <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref">RelocationValueRef</a> Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 1424 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### processX86\_64GOTTPOFFRelocation() {#aae8b68599cc13956decf8d1755670cb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::processX86_64GOTTPOFFRelocation (unsigned SectionID, uint64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref">RelocationValueRef</a> Value, int64_t Addend)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 2255 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### processX86\_64TLSRelocation() {#aedf426a271c1835cf3793dfa3b2c1384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::processX86_64TLSRelocation (unsigned SectionID, uint64_t Offset, uint64_t RelType, <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref">RelocationValueRef</a> Value, int64_t Addend, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/relocationref">RelocationRef</a> &amp; GetAddrRelocation)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 2374 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### relocationNeedsGot() {#a1cd1b30a6e28245bbac1cdc4acad3764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RuntimeDyldELF::relocationNeedsGot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/relocationref">RelocationRef</a> &amp; R)</td>
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



<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 2894 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### relocationNeedsStub() {#af6c81668bdd2938476b5489e6ff95863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RuntimeDyldELF::relocationNeedsStub (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/relocationref">RelocationRef</a> &amp; R)</td>
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



<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 2912 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### resolveAArch64Branch() {#ae85005c988a5dd5abaa38ea3a7ef7780}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::resolveAArch64Branch (unsigned SectionID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref">RelocationValueRef</a> &amp; Value, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a> RelI, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a45d3097b94f4f98303ae36e6c6b7eee6">StubMap</a> &amp; Stubs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 1507 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### resolveAArch64Relocation() {#ab298b9fefcf46e29e206c740533798c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::resolveAArch64Relocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sectionentry">SectionEntry</a> &amp; Section, uint64_t Offset, uint64_t Value, uint32_t Type, int64_t Addend)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### resolveAArch64ShortBranch() {#ac6fba3fe82f003fec8c741cb2cd3196c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RuntimeDyldELF::resolveAArch64ShortBranch (unsigned SectionID, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a> RelI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref">RelocationValueRef</a> &amp; Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 1464 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### resolveARMRelocation() {#a2bb6eb84bfbc12012604010e7a615fc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::resolveARMRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sectionentry">SectionEntry</a> &amp; Section, uint64_t Offset, uint32_t Value, uint32_t Type, int32_t Addend)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 590 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### resolveBPFRelocation() {#a0cf83cfa0a8085c11c05ff1fb6c44f98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::resolveBPFRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sectionentry">SectionEntry</a> &amp; Section, uint64_t Offset, uint64_t Value, uint32_t Type, int64_t Addend)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 1182 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### resolveGOTOffsetRelocation() {#a38ebdcdd0245e27457fd09c265bf2bd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::resolveGOTOffsetRelocation (unsigned SectionID, uint64_t Offset, uint64_t GOTOffset, uint32_t Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 2647 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### resolveLoongArch64Branch() {#a640a07eed1fadc89947e957abf2246e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::resolveLoongArch64Branch (unsigned SectionID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref">RelocationValueRef</a> &amp; Value, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a> RelI, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a45d3097b94f4f98303ae36e6c6b7eee6">StubMap</a> &amp; Stubs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 672 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### resolveLoongArch64Relocation() {#a1896d71d1aff41f1f34d7196385efce1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::resolveLoongArch64Relocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sectionentry">SectionEntry</a> &amp; Section, uint64_t Offset, uint64_t Value, uint32_t Type, int64_t Addend)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 730 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### resolveLoongArch64ShortBranch() {#a54e89f410dcdf87b323de78d9ed60a4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RuntimeDyldELF::resolveLoongArch64ShortBranch (unsigned SectionID, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a> RelI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref">RelocationValueRef</a> &amp; Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 647 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### resolvePPC32Relocation() {#a48bf5d629d177ec40293610f7a2636fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::resolvePPC32Relocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sectionentry">SectionEntry</a> &amp; Section, uint64_t Offset, uint64_t Value, uint32_t Type, int64_t Addend)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 1014 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### resolvePPC64Relocation() {#a49bcf0947ada129ba1cb1b4295b869fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::resolvePPC64Relocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sectionentry">SectionEntry</a> &amp; Section, uint64_t Offset, uint64_t Value, uint32_t Type, int64_t Addend)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 1034 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### resolveRelocation() {#a8d240a4c8aece0e073b6f44d2391f630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::resolveRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sectionentry">SectionEntry</a> &amp; Section, uint64_t Offset, uint64_t Value, uint32_t Type, int64_t Addend, uint64_t SymOffset=0, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a8ad6e355243eab1c1a3993f9bda8b2d1">SID</a> SectionID=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 1369 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### resolveRISCVRelocation() {#a912f2ec871e6617b38c99d8f347b0690}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::resolveRISCVRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sectionentry">SectionEntry</a> &amp; Section, uint64_t Offset, uint64_t Value, uint32_t Type, int64_t Addend, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a8ad6e355243eab1c1a3993f9bda8b2d1">SID</a> SectionID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 1225 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### resolveSystemZRelocation() {#af054f6b6a2d7b0cc4222763dd8330070}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::resolveSystemZRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sectionentry">SectionEntry</a> &amp; Section, uint64_t Offset, uint64_t Value, uint32_t Type, int64_t Addend)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 1128 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### resolveX86\_64Relocation() {#a17f15f20ced65596361b435a3a3228a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::resolveX86_64Relocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sectionentry">SectionEntry</a> &amp; Section, uint64_t Offset, uint64_t Value, uint32_t Type, int64_t Addend, uint64_t SymOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### resolveX86Relocation() {#abdae956d3e40802d798ac9cb10e3ccdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::resolveX86Relocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sectionentry">SectionEntry</a> &amp; Section, uint64_t Offset, uint32_t Value, uint32_t Type, int32_t Addend)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

### setMipsABI() {#a593a587513a43905825c890ea0a18508}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldELF::setMipsABI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj)</td>
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



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 847 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### SectionToGOTMap {#a3bcf96d2eb6e594a4602399e60b8eddb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;SID, SID&gt; llvm::RuntimeDyldELF::SectionToGOTMap</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>.</p>


<p>Referenced by <a href="#a34d452366da541e62d1f37b1f284800d">finalizeLoad</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurrentGOTIndex {#afc2032a0ce54f51f3ee03b81bcb9ff0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RuntimeDyldELF::CurrentGOTIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>.</p>

</div>
</div>

### GOTOffsetMap {#ae72a69469ae3feb90d5a4d140f66099f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;RelocationValueRef, uint64_t&gt; llvm::RuntimeDyldELF::GOTOffsetMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>.</p>

</div>
</div>

### GOTSectionID {#a094ed1c8af6bd5bbd8c2a6e0e3f9bfd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RuntimeDyldELF::GOTSectionID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>.</p>

</div>
</div>

### GOTSymbolOffsets {#a93aca5444595503ba945d58064fb9966}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;uint64_t&gt; llvm::RuntimeDyldELF::GOTSymbolOffsets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>.</p>

</div>
</div>

### IFuncStubOffset {#a9515648f67b33d1ceed8772f9ca5b0b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::RuntimeDyldELF::IFuncStubOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The current offset into the IFunc stub section.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>.</p>

</div>
</div>

### IFuncStubs {#a904cff557afa8f3c7b5d97183fbbdae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;IFuncStub, 2&gt; llvm::RuntimeDyldELF::IFuncStubs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The IFunc stubs.</p>

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>.</p>

</div>
</div>

### IFuncStubSectionID {#a9a266feca7a5a4cb63a7509a59011803}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RuntimeDyldELF::IFuncStubSectionID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the current IFunc stub section.</p>

<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>.</p>

</div>
</div>

### PendingRelocs {#a0b15effe97176d5e62f91fe7db8463ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::pair&lt;RelocationValueRef, RelocationEntry&gt;, 8&gt; llvm::RuntimeDyldELF::PendingRelocs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>.</p>

</div>
</div>

### UnregisteredEHFrameSections {#a4ca2ed40e8a6e11a13ded4e2923f263b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SID, 2&gt; llvm::RuntimeDyldELF::UnregisteredEHFrameSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#a2a43382614f69bdae93a85b8dd43d597}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; RuntimeDyldELF &gt; llvm::RuntimeDyldELF::create (<a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154">Triple::ArchType</a> Arch, <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager">RuntimeDyld::MemoryManager</a> &amp; MemMgr, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolresolver">JITSymbolResolver</a> &amp; Resolver)</td>
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



<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a>, definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#aab98755e5bcb6af82707f749aab3c474">llvm::RuntimeDyldImpl::Arch</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a9bc5cceb63d0ccdf06f64b587f1cd80e">llvm::RuntimeDyldImpl::MemMgr</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a867c596b0454c5bbeeb1ff490b9d70bc">llvm::Triple::mips</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a9ff8c8868a9f1892ce3f896e7f0fe1e5">llvm::Triple::mips64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae60fc4f421b40b84a536b24fc2a1919f">llvm::Triple::mips64el</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5fb4823bc5bbdad4684399b118ccace8">llvm::Triple::mipsel</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a688485f7fca0fadd7e492dc12218cd16">llvm::RuntimeDyldImpl::Resolver</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aac15efaa1f9a3f1d46ffb0d0807f344f">llvm::createRuntimeDyldELF</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp">RuntimeDyldELF.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-h">RuntimeDyldELF.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
