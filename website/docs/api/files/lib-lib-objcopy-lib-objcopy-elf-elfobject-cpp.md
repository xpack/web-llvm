---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ELFObject.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/iterator-range-h">llvm/ADT/iterator_range.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">llvm/BinaryFormat/ELF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfextras-h">llvm/MC/MCELFExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">llvm/MC/MCTargetOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compression-h">llvm/Support/Compression.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">llvm/Support/Endian.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
#include &lt;algorithm&gt;
#include &lt;cstddef&gt;
#include &lt;cstdint&gt;
#include &lt;iterator&gt;
#include &lt;unordered_set&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/objcopy">objcopy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf">elf</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool Is64&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a452a61df637c73694947964730309450">encodeCrel</a> (ArrayRef&lt; Relocation &gt; Relocations) -&gt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; char, 0 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e652f9dd88b836da88406eab24d3bfd">addressOverflows32bit</a> (uint64_t Addr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static T</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9a4cc51d7866092e51abf7273e809191">checkedGetHex</a> (StringRef S)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class Iterator&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static Iterator</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ace9ca57da9b4fcd62a7db7e96bd75a73">toHexStr</a> (T X, Iterator It, size_t Len)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf0bc94655eb3c27e0fffcbfd4bc0c7b">checkRecord</a> (const IHexRecord &amp;R)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48aee64ef267e404f3579eb20f5c3e39">checkChars</a> (StringRef Line)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5d242f614645bc321d171d7a19a1bbc">sectionPhysicalAddr</a> (const SectionBase *Sec)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79cb02a6a30f77e1c1b4ef016c460a63">isValidReservedSectionIndex</a> (uint16_t Index, uint16_t Machine)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3bded3924c618927547646df788faf09">setAddend</a> (Elf_Rel_Impl&lt; ELFT, false &gt; &amp;, uint64_t)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8996ba915bc18774be6e64f60f926050">setAddend</a> (Elf_Rel_Impl&lt; ELFT, true &gt; &amp;Rela, uint64_t Addend)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class RelRange, class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8d6f1232b558b82b1fd19c190ca20052">writeRel</a> (const RelRange &amp;Relocations, T *Buf, bool IsMips64EL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6c79769133b79f357d7916674b3eb9b">sectionWithinSegment</a> (const SectionBase &amp;Sec, const Segment &amp;Seg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28200052e2b319a32b0e938b694f7967">segmentOverlapsSegment</a> (const Segment &amp;Child, const Segment &amp;Parent)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fc44e403374b7c21a88d67ffe88edc6">compareSegmentsByOffset</a> (const Segment *A, const Segment *B)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8900af579239e32944046beb6f37e31a">getAddend</a> (uint64_t &amp;, const Elf_Rel_Impl&lt; ELFT, false &gt; &amp;)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a09365904f1d73df96751c6b2d4c17754">getAddend</a> (uint64_t &amp;ToSet, const Elf_Rel_Impl&lt; ELFT, true &gt; &amp;Rela)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad1b78430e677c5ac22430b0af1797615">initRelocations</a> (RelocationSection *Relocs, T RelRange)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5299c97aa0af6f626985eb7a5882746a">orderSegments</a> (std::vector&lt; Segment * &gt; &amp;Segments)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57752aa0e0e6281fecc0fe16dc609cd5">layoutSegments</a> (std::vector&lt; Segment * &gt; &amp;Segments, uint64_t Offset)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Range&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a782bd3507c3ce21c87bc884e7211afe3">layoutSections</a> (Range Sections, uint64_t Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78ce20255776ffc35a2da78ba3f19892">layoutSectionsForOnlyKeepDebug</a> (Object &amp;Obj, uint64_t Off)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7db0cfaec1a4fb39e28b687ff68dcaec">layoutSegmentsForOnlyKeepDebug</a> (std::vector&lt; Segment * &gt; &amp;Segments, uint64_t HdrEnd)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4ba1a6e27314176648bc330ac6f90da">removeUnneededSections</a> (Object &amp;Obj)</td>
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


<div class="doxySectionDef">

## Functions

### addressOverflows32bit() {#a8e652f9dd88b836da88406eab24d3bfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool addressOverflows32bit (uint64_t Addr)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/asciihexwriter/#a522931f04346e88ee1e60431d25bcc62">llvm::objcopy::elf::ASCIIHexWriter::checkSection</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/asciihexwriter/#a6c8bb3c922ce45c595377546d41f1222">llvm::objcopy::elf::ASCIIHexWriter::finalize</a>.</p>

</div>
</div>

### checkChars() {#a48aee64ef267e404f3579eb20f5c3e39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error checkChars (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Line)</td>
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



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/ihexrecord/#a5af15c8c6dcb6f71dff853ebdbae3ef4">llvm::objcopy::elf::IHexRecord::parse</a>.</p>

</div>
</div>

### checkedGetHex() {#a9a4cc51d7866092e51abf7273e809191}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T checkedGetHex (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#aae15979c93f7f0929116b975b5c46cd6">Fail</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1881146f2dcc2ca57c9c5f77f938db9d">llvm::StringRef::getAsInteger</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/owneddatasection/#a124ee6d61bfd830c483ce8273529bfcf">llvm::objcopy::elf::OwnedDataSection::appendHexData</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/ihexrecord/#a36361ab61c92cc509c46bcc75b8dd34a">llvm::objcopy::elf::IHexRecord::getChecksum</a> and <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/ihexrecord/#a5af15c8c6dcb6f71dff853ebdbae3ef4">llvm::objcopy::elf::IHexRecord::parse</a>.</p>

</div>
</div>

### checkRecord() {#acf0bc94655eb3c27e0fffcbfd4bc0c7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error checkRecord (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/ihexrecord">IHexRecord</a> &amp; R)</td>
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



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/ihexrecord/#a0edef690b68eda42710473270d9a0f35a9a50f8bf29974951a166212a08837edb">llvm::objcopy::elf::IHexRecord::Data</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/ihexrecord/#a0edef690b68eda42710473270d9a0f35a8e2df6a62da76caf0639c33b2441dbfd">llvm::objcopy::elf::IHexRecord::EndOfFile</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/ihexrecord/#a0edef690b68eda42710473270d9a0f35ae524d4984e373da1467ced1e805501a0">llvm::objcopy::elf::IHexRecord::ExtendedAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/ihexrecord/#a0edef690b68eda42710473270d9a0f35aa23fe5b66dcc6cf788ccc5fc8339a208">llvm::objcopy::elf::IHexRecord::SegmentAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/ihexrecord/#a0edef690b68eda42710473270d9a0f35a1ee44c2ba5272564456032e4cababee2">llvm::objcopy::elf::IHexRecord::StartAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/ihexrecord/#a0edef690b68eda42710473270d9a0f35a6b5fcdbfab85c3e3f9c8428292bb1435">llvm::objcopy::elf::IHexRecord::StartAddr80x86</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/ihexrecord/#a5af15c8c6dcb6f71dff853ebdbae3ef4">llvm::objcopy::elf::IHexRecord::parse</a>.</p>

</div>
</div>

### compareSegmentsByOffset() {#a5fc44e403374b7c21a88d67ffe88edc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool compareSegmentsByOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment">Segment</a> * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment">Segment</a> * B)</td>
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



<p>Definition at line 1253 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="#a57752aa0e0e6281fecc0fe16dc609cd5">layoutSegments</a> and <a href="#a5299c97aa0af6f626985eb7a5882746a">orderSegments</a>.</p>

</div>
</div>

### encodeCrel() {#a452a61df637c73694947964730309450}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool Is64&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; char, 0 &gt; encodeCrel (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/relocation">Relocation</a> &gt; Relocations)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a245f7316a45bb5bca2d5221a68de5646">llvm::ELF::encodeCrel</a>.</p>

</div>
</div>

### getAddend() {#a8900af579239e32944046beb6f37e31a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void getAddend (uint64_t &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/elf-rel-impl">Elf_Rel_Impl</a>&lt; ELFT, false &gt; &amp;)</td>
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



<p>Definition at line 1647 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>Referenced by <a href="#ad1b78430e677c5ac22430b0af1797615">initRelocations</a> and <a href="/web-llvm/docs/api/files/lib/lib/xray/instrumentationmap-cpp/#a39d3991edccf18f18b801032e9ab89b5">loadObj</a>.</p>

</div>
</div>

### getAddend() {#a09365904f1d73df96751c6b2d4c17754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void getAddend (uint64_t &amp; ToSet, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/elf-rel-impl">Elf_Rel_Impl</a>&lt; ELFT, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt; &amp; Rela)</td>
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



<p>Definition at line 1650 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>

</div>
</div>

### initRelocations() {#ad1b78430e677c5ac22430b0af1797615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error initRelocations (<a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/relocationsection">RelocationSection</a> * Relocs, T RelRange)</td>
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



<p>Definition at line 1655 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/relocation/#a3deb2b93afffc362d5abc1b0105e3f84">llvm::objcopy::elf::Relocation::Addend</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/relocationsection/#a8aaacd3ffa08833a92080683b284c6d5">llvm::objcopy::elf::RelocationSection::addRelocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#a8900af579239e32944046beb6f37e31a">getAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/relocationsection/#a1bd367b72ddb3b6f0d8a3195c145808a">llvm::objcopy::elf::RelocationSection::getObject</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/symboltablesection/#a80fcb2845504030d7466c8a4c0d4b2dd">llvm::objcopy::elf::SymbolTableSection::getSymbolByIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a76c91c722947016f13f9852fa023d98b">llvm::objcopy::elf::Object::IsMips64EL</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a6ca324c9086862d837e0593199d1e58e">llvm::objcopy::elf::SectionBase::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/relocation/#a59700b6987fba783c0e5aa96f36db6b9">llvm::objcopy::elf::Relocation::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/relocation/#a45d547446d88eee17b8ea12c287d73b4">llvm::objcopy::elf::Relocation::RelocSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a992d6065f91670a70730547fa168dcc7">llvm::objcopy::elf::Object::SymbolTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/relocation/#a51f716f9908be1a269cdb1033ae1f774">llvm::objcopy::elf::Relocation::Type</a>.</p>

</div>
</div>

### isValidReservedSectionIndex() {#a79cb02a6a30f77e1c1b4ef016c460a63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isValidReservedSectionIndex (uint16_t Index, uint16_t Machine)</td>
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



<p>Definition at line 648 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030dafb457612e3f91aca5d93ee2f1de6d4be">llvm::ELF::EM_AMDGPU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daa4bdb6dee5d86bb842354637ef53e14c">llvm::ELF::EM_HEXAGON</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daaf29cd80fceba94e4f48b143fcf354c6">llvm::ELF::EM_MIPS</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a2e16e55de32fe349f3e8242166918205">Machine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a319b64bc6b9c38e948eda8bfafff58b5">llvm::ELF::SHN_ABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ade1e281f7783e3cacd627341a116501ea2b1f8fd9974acef592ec96f7757f1442">llvm::ELF::SHN_AMDGPU_LDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a39083466eebf0993a765922244288d20">llvm::ELF::SHN_COMMON</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a366e4bc69bde6c253d7fc89d02ac9464a9a9b2bfc7328ff060a9114f9d6eac3e9">llvm::ELF::SHN_HEXAGON_SCOMMON</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a366e4bc69bde6c253d7fc89d02ac9464a95f4d3980b35e8451bacfbe1017a3340">llvm::ELF::SHN_HEXAGON_SCOMMON_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a366e4bc69bde6c253d7fc89d02ac9464a00ff3e90e6726f4ff08ff391ec29e2fd">llvm::ELF::SHN_HEXAGON_SCOMMON_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a366e4bc69bde6c253d7fc89d02ac9464a308d28f1a168aac9a28677ae1a76ad53">llvm::ELF::SHN_HEXAGON_SCOMMON_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a366e4bc69bde6c253d7fc89d02ac9464a3c059d54e4ae3b7f6b7ff55f6bd82b40">llvm::ELF::SHN_HEXAGON_SCOMMON_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a1266bce9cae9898d6475c353ef66be30ae67b27542080c6622bd2c748ce88fb78">llvm::ELF::SHN_MIPS_ACOMMON</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a1266bce9cae9898d6475c353ef66be30ae404ac632d80f5dc92342ddc1f292486">llvm::ELF::SHN_MIPS_SCOMMON</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a1266bce9cae9898d6475c353ef66be30ac06176780f63757004c106619b85f218">llvm::ELF::SHN_MIPS_SUNDEFINED</a>.</p>

</div>
</div>

### layoutSections() {#a782bd3507c3ce21c87bc884e7211afe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Range&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t layoutSections (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> Sections, uint64_t Offset)</td>
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



<p>Definition at line 2361 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#ac6c2aa733d3af071d31065d0090ff5c6">llvm::objcopy::elf::Segment::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a175b3cb20485be4d75ac2e380dd3dae8">llvm::objcopy::elf::SectionBase::OriginalOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#a7e21fcbce74455cf2bd3dd2eeeebacd5">llvm::objcopy::elf::Segment::OriginalOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#a47a40ff6267a0d5a1680e6564432a18c">llvm::objcopy::elf::Segment::ParentSegment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca45212cec20bcd4ca3449dcd8654010ac">llvm::ELF::SHT_NOBITS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>.</p>

</div>
</div>

### layoutSectionsForOnlyKeepDebug() {#a78ce20255776ffc35a2da78ba3f19892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t layoutSectionsForOnlyKeepDebug (<a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object">Object</a> &amp; Obj, uint64_t Off)</td>
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



<p>Definition at line 2397 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a175b3cb20485be4d75ac2e380dd3dae8">llvm::objcopy::elf::SectionBase::OriginalOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4c1b3bf29b3c86c8d11b6708ff244669a15ee14963e8cb0e95f10994bbd35a050">llvm::ELF::PT_LOAD</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a19d73e6ba4dbdb613614c9109fa0f1c6">llvm::objcopy::elf::Object::sections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca45212cec20bcd4ca3449dcd8654010ac">llvm::ELF::SHT_NOBITS</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectiontableref/#ae39c0033de705d12bff1c11d411d65b0">llvm::objcopy::elf::SectionTableRef::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>.</p>

</div>
</div>

### layoutSegments() {#a57752aa0e0e6281fecc0fe16dc609cd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t layoutSegments (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment">Segment</a> * &gt; &amp; Segments, uint64_t Offset)</td>
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



<p>Definition at line 2328 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#a7d4c0fbb1c341d6b45b7e7bf3c175477">llvm::objcopy::elf::Segment::Align</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5fc44e403374b7c21a88d67ffe88edc6">compareSegmentsByOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#a5db1dbd2d6c37e72890bab3d1523d25d">llvm::objcopy::elf::Segment::FileSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a864e071375fea140a5441a243372ff81">llvm::is_sorted</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#ac6c2aa733d3af071d31065d0090ff5c6">llvm::objcopy::elf::Segment::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#a7e21fcbce74455cf2bd3dd2eeeebacd5">llvm::objcopy::elf::Segment::OriginalOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#a47a40ff6267a0d5a1680e6564432a18c">llvm::objcopy::elf::Segment::ParentSegment</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#a88267282dde7a19f1b5fc3b8d75d2c6a">llvm::objcopy::elf::Segment::VAddr</a>.</p>

</div>
</div>

### layoutSegmentsForOnlyKeepDebug() {#a7db0cfaec1a4fb39e28b687ff68dcaec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t layoutSegmentsForOnlyKeepDebug (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment">Segment</a> * &gt; &amp; Segments, uint64_t HdrEnd)</td>
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



<p>Definition at line 2447 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#a5db1dbd2d6c37e72890bab3d1523d25d">llvm::objcopy::elf::Segment::FileSize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#a721a11215fa5edc76768ad33f46064f0">llvm::objcopy::elf::Segment::firstSection</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a9ab60ac6df1d07f5866f34453f9efe15">llvm::objcopy::elf::SectionBase::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#ac6c2aa733d3af071d31065d0090ff5c6">llvm::objcopy::elf::Segment::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#a47a40ff6267a0d5a1680e6564432a18c">llvm::objcopy::elf::Segment::ParentSegment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4c1b3bf29b3c86c8d11b6708ff244669af95333de0bb9b94266d0aef1869a4a17">llvm::ELF::PT_PHDR</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#ae73f605c85ed9995737a565aa663bd3c">llvm::objcopy::elf::Segment::Sections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca45212cec20bcd4ca3449dcd8654010ac">llvm::ELF::SHT_NOBITS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a6fefaf0cf6568001708fc6f9b862687a">llvm::objcopy::elf::SectionBase::Size</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a44c3c5507dfeccfdb9f1ba5164fed1fc">llvm::objcopy::elf::SectionBase::Type</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#a5db127e6cf62bb2d7c9ced84cdbb8531">llvm::objcopy::elf::Segment::Type</a>.</p>

</div>
</div>

### orderSegments() {#a5299c97aa0af6f626985eb7a5882746a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void orderSegments (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment">Segment</a> * &gt; &amp; Segments)</td>
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



<p>Definition at line 2321 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="#a5fc44e403374b7c21a88d67ffe88edc6">compareSegmentsByOffset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>.</p>

</div>
</div>

### removeUnneededSections() {#ae4ba1a6e27314176648bc330ac6f90da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error removeUnneededSections (<a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object">Object</a> &amp; Obj)</td>
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



<p>Definition at line 2557 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/symboltablesection/#a4783a0242422b4ace09e50fbca2d0bd6">llvm::objcopy::elf::SymbolTableSection::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/symboltablesection/#a122412f2ac2507ed4e3fa9ce22b6628e">llvm::objcopy::elf::SymbolTableSection::getStrTab</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a23fc5f374af95efe6f832eb8d5bb2e6e">llvm::objcopy::elf::Object::isRelocatable</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a7ffd3f6642f3190ce71003bbe6500203">llvm::objcopy::elf::Object::removeSections</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a2172b7ef6bf057ac354973c90fa28694">llvm::objcopy::elf::Object::SectionNames</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a992d6065f91670a70730547fa168dcc7">llvm::objcopy::elf::Object::SymbolTable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfwriter/#a96ec94d70c19707787f756fa97cc3467">llvm::objcopy::elf::ELFWriter&lt; ELFT &gt;::finalize</a>.</p>

</div>
</div>

### sectionPhysicalAddr() {#ac5d242f614645bc321d171d7a19a1bbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t sectionPhysicalAddr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase">SectionBase</a> * Sec)</td>
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



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#aaf9e58af43e8a65398a93a487d2bdb5f">llvm::objcopy::elf::SectionBase::Addr</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a175b3cb20485be4d75ac2e380dd3dae8">llvm::objcopy::elf::SectionBase::OriginalOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#a7e21fcbce74455cf2bd3dd2eeeebacd5">llvm::objcopy::elf::Segment::OriginalOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#a2682b7d94a55e576af1faf6beed186fa">llvm::objcopy::elf::Segment::PAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a67ee68d95726b2bceb453c20c02cd1db">llvm::objcopy::elf::SectionBase::ParentSegment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4c1b3bf29b3c86c8d11b6708ff244669a15ee14963e8cb0e95f10994bbd35a050">llvm::ELF::PT_LOAD</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#a5db127e6cf62bb2d7c9ced84cdbb8531">llvm::objcopy::elf::Segment::Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/asciihexwriter/#a6c8bb3c922ce45c595377546d41f1222">llvm::objcopy::elf::ASCIIHexWriter::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexsectionwriterbase/#a86adc7d0a31f9ece1614e0498abf4ecf">llvm::objcopy::elf::IHexSectionWriterBase::writeSection</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/srecsectionwriterbase/#a6c620527600c3b7b2f5ef48b7646b0c4">llvm::objcopy::elf::SRECSectionWriterBase::writeSection</a>.</p>

</div>
</div>

### sectionWithinSegment() {#af6c79769133b79f357d7916674b3eb9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool sectionWithinSegment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase">SectionBase</a> &amp; Sec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment">Segment</a> &amp; Seg)</td>
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



<p>Definition at line 1216 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#aaf9e58af43e8a65398a93a487d2bdb5f">llvm::objcopy::elf::SectionBase::Addr</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#a5db1dbd2d6c37e72890bab3d1523d25d">llvm::objcopy::elf::Segment::FileSize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a68df71b92d4532e6ceabfb620f5ba02c">llvm::objcopy::elf::SectionBase::Flags</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#abd976c267c7d2e4320b3f0776474ba13">llvm::objcopy::elf::Segment::MemSize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#ac6c2aa733d3af071d31065d0090ff5c6">llvm::objcopy::elf::Segment::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a175b3cb20485be4d75ac2e380dd3dae8">llvm::objcopy::elf::SectionBase::OriginalOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4c1b3bf29b3c86c8d11b6708ff244669a1a83bc45f6d729192b0f1d9d7e9833e6">llvm::ELF::PT_TLS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015af09f8799cc15fd856ff2284c7519d6d8">llvm::ELF::SHF_TLS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca45212cec20bcd4ca3449dcd8654010ac">llvm::ELF::SHT_NOBITS</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a6fefaf0cf6568001708fc6f9b862687a">llvm::objcopy::elf::SectionBase::Size</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a44c3c5507dfeccfdb9f1ba5164fed1fc">llvm::objcopy::elf::SectionBase::Type</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#a5db127e6cf62bb2d7c9ced84cdbb8531">llvm::objcopy::elf::Segment::Type</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#a88267282dde7a19f1b5fc3b8d75d2c6a">llvm::objcopy::elf::Segment::VAddr</a>.</p>

</div>
</div>

### segmentOverlapsSegment() {#a28200052e2b319a32b0e938b694f7967}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool segmentOverlapsSegment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment">Segment</a> &amp; Child, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment">Segment</a> &amp; Parent)</td>
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



<p>Definition at line 1246 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#a5db1dbd2d6c37e72890bab3d1523d25d">llvm::objcopy::elf::Segment::FileSize</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/segment/#a7e21fcbce74455cf2bd3dd2eeeebacd5">llvm::objcopy::elf::Segment::OriginalOffset</a>.</p>

</div>
</div>

### setAddend() {#a3bded3924c618927547646df788faf09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setAddend (<a href="/web-llvm/docs/api/structs/llvm/object/elf-rel-impl">Elf_Rel_Impl</a>&lt; ELFT, false &gt; &amp;, uint64_t)</td>
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



<p>Definition at line 965 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>Referenced by <a href="#a8d6f1232b558b82b1fd19c190ca20052">writeRel</a>.</p>

</div>
</div>

### setAddend() {#a8996ba915bc18774be6e64f60f926050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setAddend (<a href="/web-llvm/docs/api/structs/llvm/object/elf-rel-impl">Elf_Rel_Impl</a>&lt; ELFT, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt; &amp; Rela, uint64_t Addend)</td>
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



<p>Definition at line 968 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>

</div>
</div>

### toHexStr() {#ace9ca57da9b4fcd62a7db7e96bd75a73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class Iterator&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Iterator toHexStr (T X, Iterator It, size_t Len)</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/ihexrecord/#a219548daa98092da7c5c31fc6e029f07">llvm::objcopy::elf::IHexRecord::getLine</a> and <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/srecord/#aad1cb0897aed593c359266f009482c57">llvm::objcopy::elf::SRecord::toString</a>.</p>

</div>
</div>

### writeRel() {#a8d6f1232b558b82b1fd19c190ca20052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class RelRange, class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeRel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RelRange &amp; Relocations, T * Buf, bool IsMips64EL)</td>
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



<p>Definition at line 973 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="#a3bded3924c618927547646df788faf09">setAddend</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionwriter/#aa394fee185f6e8554b5cdb6ad6084394">llvm::objcopy::elf::ELFSectionWriter&lt; ELFT &gt;::visit</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
