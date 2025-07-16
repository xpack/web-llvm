---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/relocationentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RelocationEntry` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/relocationentry">RelocationEntry</a> - used to represent relocations internally in the dynamic linker. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::RelocationEntry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">ExecutionEngine/RuntimeDyld/RuntimeDyldImpl.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09c036c118f4296521cbb3a42259371c">RelocationEntry</a> (unsigned id, uint64_t offset, uint32_t type, int64_t addend)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6125eb262e25bd536affe42ebcddbe7a">RelocationEntry</a> (unsigned id, uint64_t offset, uint32_t type, int64_t addend, uint64_t symoffset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a414c98ccf9973a7f9da3e4051054db12">RelocationEntry</a> (unsigned id, uint64_t offset, uint32_t type, int64_t addend, bool IsPCRel, unsigned Size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee220e40d23d18fe2792a24854bd4998">RelocationEntry</a> (unsigned id, uint64_t offset, uint32_t type, int64_t addend, unsigned SectionA, uint64_t SectionAOffset, unsigned SectionB, uint64_t SectionBOffset, bool IsPCRel, unsigned Size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6786a1d017c38534feac16cb351b77a5">RelocationEntry</a> (unsigned id, uint64_t offset, uint32_t type, int64_t addend, unsigned SectionA, uint64_t SectionAOffset, unsigned SectionB, uint64_t SectionBOffset, bool IsPCRel, unsigned Size, bool IsTargetThumbFunc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c2824740d2fcf8bd1f44248bdcd4052">Offset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offset - offset into the section. <a href="#a4c2824740d2fcf8bd1f44248bdcd4052">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80213c5b59afecdd125a21b28b9637e9">Addend</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Addend - the relocation addend encoded in the instruction itself. <a href="#a80213c5b59afecdd125a21b28b9637e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec2f9774e1098853d20912f579f501b9">SectionID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SectionID - the section this relocation points to. <a href="#aec2f9774e1098853d20912f579f501b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b339d832145cb7ea79bbb90f5233897">RelType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RelType - relocation type. <a href="#a4b339d832145cb7ea79bbb90f5233897">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a194e81d6cc18d873ef123d3f78cedce7">SymOffset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/relocationentry/sectionpair">SectionPair</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af42a708ce2732dc8b604b8d32384ee75">Sections</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/relocationentry">llvm::RelocationEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacef862bc8a177a997170c5bbc8c0a01"></a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SymOffset - Section offset of the relocation entry's symbol (used for GOT lookup). <a href="#aacef862bc8a177a997170c5bbc8c0a01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a290c253a00603f2e0cde5f11c6db1372">Size</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The size of this relocation (<a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> specific). <a href="#a290c253a00603f2e0cde5f11c6db1372">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fa763e1036861ba4581c5b3199b4fed">IsPCRel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this is a PCRel relocation (<a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> specific). <a href="#a6fa763e1036861ba4581c5b3199b4fed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22c888f22e370f437b1185af26ec21d3">IsTargetThumbFunc</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/relocationentry">RelocationEntry</a> - used to represent relocations internally in the dynamic linker.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RelocationEntry() {#a09c036c118f4296521cbb3a42259371c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RelocationEntry::RelocationEntry (unsigned id, uint64_t offset, uint32_t type, int64_t addend)</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>References <a href="#a80213c5b59afecdd125a21b28b9637e9">Addend</a>, <a href="#a6fa763e1036861ba4581c5b3199b4fed">IsPCRel</a>, <a href="#a22c888f22e370f437b1185af26ec21d3">IsTargetThumbFunc</a>, <a href="#a4c2824740d2fcf8bd1f44248bdcd4052">Offset</a>, <a href="#a4b339d832145cb7ea79bbb90f5233897">RelType</a>, <a href="#aec2f9774e1098853d20912f579f501b9">SectionID</a>, <a href="#a290c253a00603f2e0cde5f11c6db1372">Size</a> and <a href="#a194e81d6cc18d873ef123d3f78cedce7">SymOffset</a>.</p>

</div>
</div>

### RelocationEntry() {#a6125eb262e25bd536affe42ebcddbe7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RelocationEntry::RelocationEntry (unsigned id, uint64_t offset, uint32_t type, int64_t addend, uint64_t symoffset)</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>References <a href="#a80213c5b59afecdd125a21b28b9637e9">Addend</a>, <a href="#a6fa763e1036861ba4581c5b3199b4fed">IsPCRel</a>, <a href="#a22c888f22e370f437b1185af26ec21d3">IsTargetThumbFunc</a>, <a href="#a4c2824740d2fcf8bd1f44248bdcd4052">Offset</a>, <a href="#a4b339d832145cb7ea79bbb90f5233897">RelType</a>, <a href="#aec2f9774e1098853d20912f579f501b9">SectionID</a>, <a href="#a290c253a00603f2e0cde5f11c6db1372">Size</a> and <a href="#a194e81d6cc18d873ef123d3f78cedce7">SymOffset</a>.</p>

</div>
</div>

### RelocationEntry() {#a414c98ccf9973a7f9da3e4051054db12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RelocationEntry::RelocationEntry (unsigned id, uint64_t offset, uint32_t type, int64_t addend, bool IsPCRel, unsigned Size)</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>References <a href="#a80213c5b59afecdd125a21b28b9637e9">Addend</a>, <a href="#a6fa763e1036861ba4581c5b3199b4fed">IsPCRel</a>, <a href="#a22c888f22e370f437b1185af26ec21d3">IsTargetThumbFunc</a>, <a href="#a4c2824740d2fcf8bd1f44248bdcd4052">Offset</a>, <a href="#a4b339d832145cb7ea79bbb90f5233897">RelType</a>, <a href="#aec2f9774e1098853d20912f579f501b9">SectionID</a>, <a href="#a290c253a00603f2e0cde5f11c6db1372">Size</a> and <a href="#a194e81d6cc18d873ef123d3f78cedce7">SymOffset</a>.</p>

</div>
</div>

### RelocationEntry() {#aee220e40d23d18fe2792a24854bd4998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RelocationEntry::RelocationEntry (unsigned id, uint64_t offset, uint32_t type, int64_t addend, unsigned SectionA, uint64_t SectionAOffset, unsigned SectionB, uint64_t SectionBOffset, bool IsPCRel, unsigned Size)</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>References <a href="#a80213c5b59afecdd125a21b28b9637e9">Addend</a>, <a href="#a6fa763e1036861ba4581c5b3199b4fed">IsPCRel</a>, <a href="#a22c888f22e370f437b1185af26ec21d3">IsTargetThumbFunc</a>, <a href="#a4c2824740d2fcf8bd1f44248bdcd4052">Offset</a>, <a href="#a4b339d832145cb7ea79bbb90f5233897">RelType</a>, <a href="#aec2f9774e1098853d20912f579f501b9">SectionID</a>, <a href="#af42a708ce2732dc8b604b8d32384ee75">Sections</a> and <a href="#a290c253a00603f2e0cde5f11c6db1372">Size</a>.</p>

</div>
</div>

### RelocationEntry() {#a6786a1d017c38534feac16cb351b77a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RelocationEntry::RelocationEntry (unsigned id, uint64_t offset, uint32_t type, int64_t addend, unsigned SectionA, uint64_t SectionAOffset, unsigned SectionB, uint64_t SectionBOffset, bool IsPCRel, unsigned Size, bool IsTargetThumbFunc)</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>References <a href="#a80213c5b59afecdd125a21b28b9637e9">Addend</a>, <a href="#a6fa763e1036861ba4581c5b3199b4fed">IsPCRel</a>, <a href="#a22c888f22e370f437b1185af26ec21d3">IsTargetThumbFunc</a>, <a href="#a4c2824740d2fcf8bd1f44248bdcd4052">Offset</a>, <a href="#a4b339d832145cb7ea79bbb90f5233897">RelType</a>, <a href="#aec2f9774e1098853d20912f579f501b9">SectionID</a>, <a href="#af42a708ce2732dc8b604b8d32384ee75">Sections</a> and <a href="#a290c253a00603f2e0cde5f11c6db1372">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

###  {#aacef862bc8a177a997170c5bbc8c0a01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::RelocationEntry llvm::RelocationEntry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SymOffset - Section offset of the relocation entry's symbol (used for GOT lookup).</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>

</div>
</div>

### Addend {#a80213c5b59afecdd125a21b28b9637e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::RelocationEntry::Addend</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Addend - the relocation addend encoded in the instruction itself.</p>


<p>Also used to make a relocation section relative instead of symbol relative.</p>


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a5db8c0beafbba922f1600e24fe6898bc">llvm::RuntimeDyldImpl::addRelocationForSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ac01d9cc5d2d4a3b6662c7096e54bf8ad">llvm::RuntimeDyldMachO::getRelocationValueRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#a731c45f6ccf4dde3198c1d5147c3cb37">llvm::RuntimeDyldMachOAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#ad0cc2b7a34912033f88c7169756683cb">llvm::RuntimeDyldMachOARM::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoi386/#a5bd3ae889a8d52356bd6b32e45c7aa6c">llvm::RuntimeDyldMachOI386::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#a59ad91c5ccf9ed8867eab9cc5424b151">llvm::RuntimeDyldMachOX86_64::processRelocationRef</a>, <a href="#a09c036c118f4296521cbb3a42259371c">RelocationEntry</a>, <a href="#a414c98ccf9973a7f9da3e4051054db12">RelocationEntry</a>, <a href="#a6125eb262e25bd536affe42ebcddbe7a">RelocationEntry</a>, <a href="#aee220e40d23d18fe2792a24854bd4998">RelocationEntry</a>, <a href="#a6786a1d017c38534feac16cb351b77a5">RelocationEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a35e8cc985018e504a57093b9e0768d00">llvm::RuntimeDyldCOFFAArch64::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffi386/#af5f76d4e975e1864419036651a6b9295">llvm::RuntimeDyldCOFFI386::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#a6339960d2e5a1860dd0ce831fc20c006">llvm::RuntimeDyldCOFFThumb::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#a2743e6f5ddf54d94da5d05aebfdb3c9d">llvm::RuntimeDyldCOFFX86_64::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a66fd1d01cea1089f326652a523d4049a">llvm::RuntimeDyldELF::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelfmips/#a68be6b3ae238497d82af98616431b6a1">llvm::RuntimeDyldELFMips::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#afab03ddb5f92e76f5c7bc8960baf72fa">llvm::RuntimeDyldMachOAArch64::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a42b1bc914cf22878c36dda7a8a31447e">llvm::RuntimeDyldMachOARM::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoi386/#ae8f416dd6dfbdda68a71ef2684092933">llvm::RuntimeDyldMachOI386::resolveRelocation</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#ab9f0c0ad7d8a9a72b2b7b5601eb7cf77">llvm::RuntimeDyldMachOX86_64::resolveRelocation</a>.</p>

</div>
</div>

### IsPCRel {#a6fa763e1036861ba4581c5b3199b4fed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RelocationEntry::IsPCRel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this is a PCRel relocation (<a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> specific).</p>

<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#a731c45f6ccf4dde3198c1d5147c3cb37">llvm::RuntimeDyldMachOAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#ad0cc2b7a34912033f88c7169756683cb">llvm::RuntimeDyldMachOARM::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoi386/#a5bd3ae889a8d52356bd6b32e45c7aa6c">llvm::RuntimeDyldMachOI386::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#a59ad91c5ccf9ed8867eab9cc5424b151">llvm::RuntimeDyldMachOX86_64::processRelocationRef</a>, <a href="#a09c036c118f4296521cbb3a42259371c">RelocationEntry</a>, <a href="#a414c98ccf9973a7f9da3e4051054db12">RelocationEntry</a>, <a href="#a6125eb262e25bd536affe42ebcddbe7a">RelocationEntry</a>, <a href="#aee220e40d23d18fe2792a24854bd4998">RelocationEntry</a>, <a href="#a6786a1d017c38534feac16cb351b77a5">RelocationEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#afab03ddb5f92e76f5c7bc8960baf72fa">llvm::RuntimeDyldMachOAArch64::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a42b1bc914cf22878c36dda7a8a31447e">llvm::RuntimeDyldMachOARM::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoi386/#ae8f416dd6dfbdda68a71ef2684092933">llvm::RuntimeDyldMachOI386::resolveRelocation</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#ab9f0c0ad7d8a9a72b2b7b5601eb7cf77">llvm::RuntimeDyldMachOX86_64::resolveRelocation</a>.</p>

</div>
</div>

### IsTargetThumbFunc {#a22c888f22e370f437b1185af26ec21d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RelocationEntry::IsTargetThumbFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#ad0cc2b7a34912033f88c7169756683cb">llvm::RuntimeDyldMachOARM::processRelocationRef</a>, <a href="#a09c036c118f4296521cbb3a42259371c">RelocationEntry</a>, <a href="#a414c98ccf9973a7f9da3e4051054db12">RelocationEntry</a>, <a href="#a6125eb262e25bd536affe42ebcddbe7a">RelocationEntry</a>, <a href="#aee220e40d23d18fe2792a24854bd4998">RelocationEntry</a>, <a href="#a6786a1d017c38534feac16cb351b77a5">RelocationEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#a6339960d2e5a1860dd0ce831fc20c006">llvm::RuntimeDyldCOFFThumb::resolveRelocation</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a42b1bc914cf22878c36dda7a8a31447e">llvm::RuntimeDyldMachOARM::resolveRelocation</a>.</p>

</div>
</div>

### Offset {#a4c2824740d2fcf8bd1f44248bdcd4052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::RelocationEntry::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Offset - offset into the section.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#a57a3ea47fdc3f7e2de2a3939ea4e5a49">llvm::RuntimeDyldMachOAArch64::decodeAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a4c19829e43ffe8064443b93c1946f9a2">llvm::RuntimeDyldMachOARM::decodeAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#af2314475cd69d029c487927d58778a82">llvm::RuntimeDyldMachO::dumpRelocationToResolve</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#a4ff8b7dc8dd3a4baddc147c6afd14c5e">llvm::RuntimeDyldMachO::memcpyAddend</a>, <a href="#a09c036c118f4296521cbb3a42259371c">RelocationEntry</a>, <a href="#a414c98ccf9973a7f9da3e4051054db12">RelocationEntry</a>, <a href="#a6125eb262e25bd536affe42ebcddbe7a">RelocationEntry</a>, <a href="#aee220e40d23d18fe2792a24854bd4998">RelocationEntry</a>, <a href="#a6786a1d017c38534feac16cb351b77a5">RelocationEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a35e8cc985018e504a57093b9e0768d00">llvm::RuntimeDyldCOFFAArch64::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffi386/#af5f76d4e975e1864419036651a6b9295">llvm::RuntimeDyldCOFFI386::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#a6339960d2e5a1860dd0ce831fc20c006">llvm::RuntimeDyldCOFFThumb::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#a2743e6f5ddf54d94da5d05aebfdb3c9d">llvm::RuntimeDyldCOFFX86_64::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a66fd1d01cea1089f326652a523d4049a">llvm::RuntimeDyldELF::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelfmips/#a68be6b3ae238497d82af98616431b6a1">llvm::RuntimeDyldELFMips::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#afab03ddb5f92e76f5c7bc8960baf72fa">llvm::RuntimeDyldMachOAArch64::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a42b1bc914cf22878c36dda7a8a31447e">llvm::RuntimeDyldMachOARM::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoi386/#ae8f416dd6dfbdda68a71ef2684092933">llvm::RuntimeDyldMachOI386::resolveRelocation</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#ab9f0c0ad7d8a9a72b2b7b5601eb7cf77">llvm::RuntimeDyldMachOX86_64::resolveRelocation</a>.</p>

</div>
</div>

### RelType {#a4b339d832145cb7ea79bbb90f5233897}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::RelocationEntry::RelType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RelType - relocation type.</p>

<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#a57a3ea47fdc3f7e2de2a3939ea4e5a49">llvm::RuntimeDyldMachOAArch64::decodeAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a4c19829e43ffe8064443b93c1946f9a2">llvm::RuntimeDyldMachOARM::decodeAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#a731c45f6ccf4dde3198c1d5147c3cb37">llvm::RuntimeDyldMachOAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#ad0cc2b7a34912033f88c7169756683cb">llvm::RuntimeDyldMachOARM::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#a59ad91c5ccf9ed8867eab9cc5424b151">llvm::RuntimeDyldMachOX86_64::processRelocationRef</a>, <a href="#a09c036c118f4296521cbb3a42259371c">RelocationEntry</a>, <a href="#a414c98ccf9973a7f9da3e4051054db12">RelocationEntry</a>, <a href="#a6125eb262e25bd536affe42ebcddbe7a">RelocationEntry</a>, <a href="#aee220e40d23d18fe2792a24854bd4998">RelocationEntry</a>, <a href="#a6786a1d017c38534feac16cb351b77a5">RelocationEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a35e8cc985018e504a57093b9e0768d00">llvm::RuntimeDyldCOFFAArch64::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffi386/#af5f76d4e975e1864419036651a6b9295">llvm::RuntimeDyldCOFFI386::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#a6339960d2e5a1860dd0ce831fc20c006">llvm::RuntimeDyldCOFFThumb::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#a2743e6f5ddf54d94da5d05aebfdb3c9d">llvm::RuntimeDyldCOFFX86_64::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a66fd1d01cea1089f326652a523d4049a">llvm::RuntimeDyldELF::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelfmips/#a68be6b3ae238497d82af98616431b6a1">llvm::RuntimeDyldELFMips::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#afab03ddb5f92e76f5c7bc8960baf72fa">llvm::RuntimeDyldMachOAArch64::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a42b1bc914cf22878c36dda7a8a31447e">llvm::RuntimeDyldMachOARM::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoi386/#ae8f416dd6dfbdda68a71ef2684092933">llvm::RuntimeDyldMachOI386::resolveRelocation</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#ab9f0c0ad7d8a9a72b2b7b5601eb7cf77">llvm::RuntimeDyldMachOX86_64::resolveRelocation</a>.</p>

</div>
</div>

### SectionID {#aec2f9774e1098853d20912f579f501b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RelocationEntry::SectionID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SectionID - the section this relocation points to.</p>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#a57a3ea47fdc3f7e2de2a3939ea4e5a49">llvm::RuntimeDyldMachOAArch64::decodeAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a4c19829e43ffe8064443b93c1946f9a2">llvm::RuntimeDyldMachOARM::decodeAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#af2314475cd69d029c487927d58778a82">llvm::RuntimeDyldMachO::dumpRelocationToResolve</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#a4ff8b7dc8dd3a4baddc147c6afd14c5e">llvm::RuntimeDyldMachO::memcpyAddend</a>, <a href="#a09c036c118f4296521cbb3a42259371c">RelocationEntry</a>, <a href="#a414c98ccf9973a7f9da3e4051054db12">RelocationEntry</a>, <a href="#a6125eb262e25bd536affe42ebcddbe7a">RelocationEntry</a>, <a href="#aee220e40d23d18fe2792a24854bd4998">RelocationEntry</a>, <a href="#a6786a1d017c38534feac16cb351b77a5">RelocationEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a35e8cc985018e504a57093b9e0768d00">llvm::RuntimeDyldCOFFAArch64::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffi386/#af5f76d4e975e1864419036651a6b9295">llvm::RuntimeDyldCOFFI386::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#a6339960d2e5a1860dd0ce831fc20c006">llvm::RuntimeDyldCOFFThumb::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#a2743e6f5ddf54d94da5d05aebfdb3c9d">llvm::RuntimeDyldCOFFX86_64::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a66fd1d01cea1089f326652a523d4049a">llvm::RuntimeDyldELF::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelfmips/#a68be6b3ae238497d82af98616431b6a1">llvm::RuntimeDyldELFMips::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#afab03ddb5f92e76f5c7bc8960baf72fa">llvm::RuntimeDyldMachOAArch64::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a42b1bc914cf22878c36dda7a8a31447e">llvm::RuntimeDyldMachOARM::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoi386/#ae8f416dd6dfbdda68a71ef2684092933">llvm::RuntimeDyldMachOI386::resolveRelocation</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#ab9f0c0ad7d8a9a72b2b7b5601eb7cf77">llvm::RuntimeDyldMachOX86_64::resolveRelocation</a>.</p>

</div>
</div>

### Sections {#af42a708ce2732dc8b604b8d32384ee75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionPair llvm::RelocationEntry::Sections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#af0b0733da2d8693287bd3bb04ee6ab80">llvm::RuntimeDyldCOFF::getDLLImportOffset</a>, <a href="#aee220e40d23d18fe2792a24854bd4998">RelocationEntry</a>, <a href="#a6786a1d017c38534feac16cb351b77a5">RelocationEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffi386/#af5f76d4e975e1864419036651a6b9295">llvm::RuntimeDyldCOFFI386::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#a6339960d2e5a1860dd0ce831fc20c006">llvm::RuntimeDyldCOFFThumb::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#afab03ddb5f92e76f5c7bc8960baf72fa">llvm::RuntimeDyldMachOAArch64::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a42b1bc914cf22878c36dda7a8a31447e">llvm::RuntimeDyldMachOARM::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoi386/#ae8f416dd6dfbdda68a71ef2684092933">llvm::RuntimeDyldMachOI386::resolveRelocation</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#ab9f0c0ad7d8a9a72b2b7b5601eb7cf77">llvm::RuntimeDyldMachOX86_64::resolveRelocation</a>.</p>

</div>
</div>

### Size {#a290c253a00603f2e0cde5f11c6db1372}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RelocationEntry::Size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The size of this relocation (<a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> specific).</p>

<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#a57a3ea47fdc3f7e2de2a3939ea4e5a49">llvm::RuntimeDyldMachOAArch64::decodeAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#a4ff8b7dc8dd3a4baddc147c6afd14c5e">llvm::RuntimeDyldMachO::memcpyAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#a731c45f6ccf4dde3198c1d5147c3cb37">llvm::RuntimeDyldMachOAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoi386/#a5bd3ae889a8d52356bd6b32e45c7aa6c">llvm::RuntimeDyldMachOI386::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#a59ad91c5ccf9ed8867eab9cc5424b151">llvm::RuntimeDyldMachOX86_64::processRelocationRef</a>, <a href="#a09c036c118f4296521cbb3a42259371c">RelocationEntry</a>, <a href="#a414c98ccf9973a7f9da3e4051054db12">RelocationEntry</a>, <a href="#a6125eb262e25bd536affe42ebcddbe7a">RelocationEntry</a>, <a href="#aee220e40d23d18fe2792a24854bd4998">RelocationEntry</a>, <a href="#a6786a1d017c38534feac16cb351b77a5">RelocationEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#afab03ddb5f92e76f5c7bc8960baf72fa">llvm::RuntimeDyldMachOAArch64::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a42b1bc914cf22878c36dda7a8a31447e">llvm::RuntimeDyldMachOARM::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoi386/#ae8f416dd6dfbdda68a71ef2684092933">llvm::RuntimeDyldMachOI386::resolveRelocation</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#ab9f0c0ad7d8a9a72b2b7b5601eb7cf77">llvm::RuntimeDyldMachOX86_64::resolveRelocation</a>.</p>

</div>
</div>

### SymOffset {#a194e81d6cc18d873ef123d3f78cedce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::RelocationEntry::SymOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a>, <a href="#a09c036c118f4296521cbb3a42259371c">RelocationEntry</a>, <a href="#a414c98ccf9973a7f9da3e4051054db12">RelocationEntry</a>, <a href="#a6125eb262e25bd536affe42ebcddbe7a">RelocationEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a66fd1d01cea1089f326652a523d4049a">llvm::RuntimeDyldELF::resolveRelocation</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelfmips/#a68be6b3ae238497d82af98616431b6a1">llvm::RuntimeDyldELFMips::resolveRelocation</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
