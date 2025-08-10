---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/object/machoobjectfile-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `MachOObjectFile.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">llvm/ADT/StringSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bit-h">llvm/ADT/bit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">llvm/BinaryFormat/MachO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/swift-h">llvm/BinaryFormat/Swift.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/error-h">llvm/Object/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">llvm/Object/MachO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">llvm/Object/ObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">llvm/Object/SymbolicFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">llvm/Support/DataExtractor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errc-h">llvm/Support/Errc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/leb128-h">llvm/Support/LEB128.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybufferref-h">llvm/Support/MemoryBufferRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/swapbyteorder-h">llvm/Support/SwapByteOrder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/host-h">llvm/TargetParser/Host.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstddef&gt;
#include &lt;cstdint&gt;
#include &lt;cstring&gt;
#include &lt;limits&gt;
#include &lt;list&gt;
#include &lt;memory&gt;
#include &lt;system_error&gt;
#include "llvm/BinaryFormat/Swift.def"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-machoobjectfile-cpp-">anonymous{MachOObjectFile.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-machoobjectfile-cpp-/section-base">section_base</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/machoelement">MachOElement</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a> (const Twine &amp;Msg)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static T</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a65d683ab0721978a7568df291210a549">getStruct</a> (const MachOObjectFile &amp;O, const char *P)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a> (const MachOObjectFile &amp;O, const char *P) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; T &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7695bd8a585d6d772c516b6e7b7aa0e3">getSectionPtr</a> (const MachOObjectFile &amp;O, MachOObjectFile::LoadCommandInfo L, unsigned Sec)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d9162ba919b64a3930354acc96f098b">getPtr</a> (const MachOObjectFile &amp;O, size_t Offset, size_t MachOFilesetEntryOffset=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/macho/nlist-base">MachO::nlist_base</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e0b242aa7cb8cb269f5ea9973a9f605">getSymbolTableEntryBase</a> (const MachOObjectFile &amp;O, DataRefImpl DRI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad91ce3ef577757936597aace8a21fdef">parseSegmentOrSectionName</a> (const char *P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae148cedd3b13337408aac7949e546eb9">getCPUType</a> (const MachOObjectFile &amp;O)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afae525cefbe3d0179a73a5ffb555160b">getCPUSubType</a> (const MachOObjectFile &amp;O)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a737f9117ad9ecb54eff89ae39cc5e0c1">getPlainRelocationAddress</a> (const MachO::any_relocation_info &amp;RE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a922ba9d09d115911235efb6e517b5ef9">getScatteredRelocationAddress</a> (const MachO::any_relocation_info &amp;RE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c487242e400b912bb74ac8cdfc4b299">getPlainRelocationPCRel</a> (const MachOObjectFile &amp;O, const MachO::any_relocation_info &amp;RE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6a5d311edf7adea28255db07dd3fc7d">getScatteredRelocationPCRel</a> (const MachO::any_relocation_info &amp;RE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bfc08d3a7440ea1dd3d51785b5d3667">getPlainRelocationLength</a> (const MachOObjectFile &amp;O, const MachO::any_relocation_info &amp;RE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53ac15ba730cd5a7e82f50b6bc1bf715">getScatteredRelocationLength</a> (const MachO::any_relocation_info &amp;RE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20d9592bf3c885c6afab008b7bb1789e">getPlainRelocationType</a> (const MachOObjectFile &amp;O, const MachO::any_relocation_info &amp;RE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5ea45808f76ad3f6b0159739e80d160">getSectionFlags</a> (const MachOObjectFile &amp;O, DataRefImpl Sec)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada8e7ae873a0bd17132af43d3a128f8e">getLoadCommandInfo</a> (const MachOObjectFile &amp;Obj, const char *Ptr, uint32_t LoadCommandIndex)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d77869bd604539426d81bd418ce875f">getFirstLoadCommandInfo</a> (const MachOObjectFile &amp;Obj)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdea79cf3204fe335d9ebceb78e6a778">getNextLoadCommandInfo</a> (const MachOObjectFile &amp;Obj, uint32_t LoadCommandIndex, const MachOObjectFile::LoadCommandInfo &amp;L)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adcb372f00f2b01dc20f3567b2eb97be3">parseHeader</a> (const MachOObjectFile &amp;Obj, T &amp;Header, Error &amp;Err)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8413e5e66b80672de909764764faf7f">checkOverlappingElement</a> (std::list&lt; MachOElement &gt; &amp;Elements, uint64_t Offset, uint64_t Size, const char *Name)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Segment, typename Section&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a488ef72cdaf48278d8a1117a6833bad2">parseSegmentLoadCommand</a> (const MachOObjectFile &amp;Obj, const MachOObjectFile::LoadCommandInfo &amp;Load, SmallVectorImpl&lt; const char * &gt; &amp;Sections, bool &amp;IsPageZeroSegment, uint32_t LoadCommandIndex, const char *CmdName, uint64_t SizeOfHeaders, std::list&lt; MachOElement &gt; &amp;Elements)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a197ed26dbc11fa1cf315ab378b657ec4">checkSymtabCommand</a> (const MachOObjectFile &amp;Obj, const MachOObjectFile::LoadCommandInfo &amp;Load, uint32_t LoadCommandIndex, const char **SymtabLoadCmd, std::list&lt; MachOElement &gt; &amp;Elements)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21566fd3bc19b4348f0deed830e19199">checkDysymtabCommand</a> (const MachOObjectFile &amp;Obj, const MachOObjectFile::LoadCommandInfo &amp;Load, uint32_t LoadCommandIndex, const char **DysymtabLoadCmd, std::list&lt; MachOElement &gt; &amp;Elements)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe7067ce0893d97940a85141e4c44776">checkLinkeditDataCommand</a> (const MachOObjectFile &amp;Obj, const MachOObjectFile::LoadCommandInfo &amp;Load, uint32_t LoadCommandIndex, const char **LoadCmd, const char *CmdName, std::list&lt; MachOElement &gt; &amp;Elements, const char *ElementName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d955f22836e92a508b414d270041628">checkDyldInfoCommand</a> (const MachOObjectFile &amp;Obj, const MachOObjectFile::LoadCommandInfo &amp;Load, uint32_t LoadCommandIndex, const char **LoadCmd, const char *CmdName, std::list&lt; MachOElement &gt; &amp;Elements)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29d1b39b4762b4de7a37817a3a01355f">checkDylibCommand</a> (const MachOObjectFile &amp;Obj, const MachOObjectFile::LoadCommandInfo &amp;Load, uint32_t LoadCommandIndex, const char *CmdName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5d5ac386b9d143dc66cbb3bdac42adf">checkDylibIdCommand</a> (const MachOObjectFile &amp;Obj, const MachOObjectFile::LoadCommandInfo &amp;Load, uint32_t LoadCommandIndex, const char **LoadCmd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8d5d23303122b92e1b4a0afbdb9e656">checkDyldCommand</a> (const MachOObjectFile &amp;Obj, const MachOObjectFile::LoadCommandInfo &amp;Load, uint32_t LoadCommandIndex, const char *CmdName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e53134a7b107f2a0f6213f2f5ed21e1">checkVersCommand</a> (const MachOObjectFile &amp;Obj, const MachOObjectFile::LoadCommandInfo &amp;Load, uint32_t LoadCommandIndex, const char **LoadCmd, const char *CmdName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedcf65b10ecb990ac021daf4f940a881">checkNoteCommand</a> (const MachOObjectFile &amp;Obj, const MachOObjectFile::LoadCommandInfo &amp;Load, uint32_t LoadCommandIndex, std::list&lt; MachOElement &gt; &amp;Elements)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d797aa90eeef9897ebdcf1c8332441e">parseBuildVersionCommand</a> (const MachOObjectFile &amp;Obj, const MachOObjectFile::LoadCommandInfo &amp;Load, SmallVectorImpl&lt; const char * &gt; &amp;BuildTools, uint32_t LoadCommandIndex)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a636124b5ffd9b1f64c447b5d79b385fc">checkRpathCommand</a> (const MachOObjectFile &amp;Obj, const MachOObjectFile::LoadCommandInfo &amp;Load, uint32_t LoadCommandIndex)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbece8143fc21ed045b0d711c7103d17">checkEncryptCommand</a> (const MachOObjectFile &amp;Obj, const MachOObjectFile::LoadCommandInfo &amp;Load, uint32_t LoadCommandIndex, uint64_t cryptoff, uint64_t cryptsize, const char **LoadCmd, const char *CmdName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77b750f0deb484099d9f4f3539bda353">checkLinkerOptCommand</a> (const MachOObjectFile &amp;Obj, const MachOObjectFile::LoadCommandInfo &amp;Load, uint32_t LoadCommandIndex)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6231d1eadcf7d5f81f417fdc5fa394fc">checkSubCommand</a> (const MachOObjectFile &amp;Obj, const MachOObjectFile::LoadCommandInfo &amp;Load, uint32_t LoadCommandIndex, const char *CmdName, size_t SizeOfCmd, const char *CmdStructName, uint32_t PathOffset, const char *PathFieldName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc5ff59b8ea0a100389a37ea8ec40f9a">checkThreadCommand</a> (const MachOObjectFile &amp;Obj, const MachOObjectFile::LoadCommandInfo &amp;Load, uint32_t LoadCommandIndex, const char *CmdName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a0d53be15e648f327c4292341fa7dad">checkTwoLevelHintsCommand</a> (const MachOObjectFile &amp;Obj, const MachOObjectFile::LoadCommandInfo &amp;Load, uint32_t LoadCommandIndex, const char **LoadCmd, std::list&lt; MachOElement &gt; &amp;Elements)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac162ad8e535e9ed3392b5a72f35f0106">isLoadCommandObsolete</a> (uint32_t cmd)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac78e4faf9bf0789dfdf928c2ff83d731">getEncodedOrdinal</a> (T Value)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8e5744e3da3116ce5eaf50660b88d6aa">getArray</a> (const MachOObjectFile &amp;O, const void *Ptr) -&gt; std::array&lt; T, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> &gt;</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed88b751512325308cd8b51594c038c3">HANDLE_SWIFT_SECTION</a>(KIND, MACHO, ELF, COFF)&nbsp;&nbsp;&nbsp;  .Case(MACHO, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h/#a0fe94e4721fb2c4dfc05937e4c71aa2c">llvm::binaryformat::Swift5ReflectionSectionKind::KIND</a>)</td>
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

### checkDyldCommand() {#ae8d5d23303122b92e1b4a0afbdb9e656}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error checkDyldCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> &amp; Load, uint32_t LoadCommandIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * CmdName)</td>
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



<p>Definition at line 787 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### checkDyldInfoCommand() {#a4d955f22836e92a508b414d270041628}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error checkDyldInfoCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> &amp; Load, uint32_t LoadCommandIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char ** LoadCmd, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * CmdName, std::list&lt; <a href="/web-llvm/docs/api/structs/machoelement">MachOElement</a> &gt; &amp; Elements)</td>
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



<p>Definition at line 639 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#ab88cd765d6656769b73824ee3633f9c6">llvm::MachO::dyld_info_command::bind_off</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#a6ffe60a024bfb2a697cf4717e3a1ca5d">llvm::MachO::dyld_info_command::bind_size</a>, <a href="#ad8413e5e66b80672de909764764faf7f">checkOverlappingElement</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#a2fbaf002da3c23fd712b578e391d7e3e">llvm::MachO::dyld_info_command::cmdsize</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#a6abfd90c1ff5f9fab154b1b7c2ca9fdf">llvm::MachO::dyld_info_command::export_off</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#a6cc1cf394f79b0012db18526d363f887">llvm::MachO::dyld_info_command::export_size</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#a66f14c5767f6c0860bcca3f23d15002c">llvm::MachO::dyld_info_command::lazy_bind_off</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#a8bbee159752147265303f294926c72d6">llvm::MachO::dyld_info_command::lazy_bind_size</a>, <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#ac0a251eaae629a1e7f918ff416ff17fd">llvm::MachO::dyld_info_command::rebase_off</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#a6b8dd4f28d4ff3bd7ea7ba0c3cd8a377">llvm::MachO::dyld_info_command::rebase_size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#ad19b3e306dcbd600f6e735c02c118eb6">llvm::MachO::dyld_info_command::weak_bind_off</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#ab64b83ee5772b8d112c8961f209d1ab4">llvm::MachO::dyld_info_command::weak_bind_size</a>.</p>

</div>
</div>

### checkDylibCommand() {#a29d1b39b4762b4de7a37817a3a01355f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error checkDylibCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> &amp; Load, uint32_t LoadCommandIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * CmdName)</td>
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



<p>Definition at line 738 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#af5d5ac386b9d143dc66cbb3bdac42adf">checkDylibIdCommand</a>.</p>

</div>
</div>

### checkDylibIdCommand() {#af5d5ac386b9d143dc66cbb3bdac42adf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error checkDylibIdCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> &amp; Load, uint32_t LoadCommandIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char ** LoadCmd)</td>
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



<p>Definition at line 770 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a29d1b39b4762b4de7a37817a3a01355f">checkDylibCommand</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/mach-header/#a81b6102d4c7c4130c894948b968d9d24">llvm::MachO::mach_header::filetype</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a80dc9af48926f9c1b70075f71c6002a7">llvm::object::MachOObjectFile::getHeader</a>, <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a4099e754341e36bdbc04624fa2f1e19aa61431e5ba87f234d7b1ffa7bfd12c98e">llvm::MachO::MH_DYLIB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a4099e754341e36bdbc04624fa2f1e19aa6885d2f4c415c3e66cb5b2a71b4d6e46">llvm::MachO::MH_DYLIB_STUB</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### checkDysymtabCommand() {#a21566fd3bc19b4348f0deed830e19199}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error checkDysymtabCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> &amp; Load, uint32_t LoadCommandIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char ** DysymtabLoadCmd, std::list&lt; <a href="/web-llvm/docs/api/structs/machoelement">MachOElement</a> &gt; &amp; Elements)</td>
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



<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#ad8413e5e66b80672de909764764faf7f">checkOverlappingElement</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a23abe84aecd6ccce7c5ea1310386b76a">llvm::MachO::dysymtab_command::cmdsize</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a2bfa44a8b4a54932a5a9dbe7fb32a865">llvm::MachO::dysymtab_command::extrefsymoff</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a993c9357665d449e7803fadbb82bf057">llvm::MachO::dysymtab_command::extreloff</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a1e9b3d4be015aa2be10de0a437ad5686">llvm::MachO::dysymtab_command::indirectsymoff</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a9c9aed90376ff1c700f89f5d037decff">llvm::object::MachOObjectFile::is64Bit</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#aacb93138f3f5ba1db874f2bc6844e94e">llvm::MachO::dysymtab_command::locreloff</a>, <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a28de8c2cbc7ca61dd12f5f67c9fab008">llvm::MachO::dysymtab_command::modtaboff</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#aaabc8d90d8f1914bb4a59446bd11efd7">llvm::MachO::dysymtab_command::nextrefsyms</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a5e3a398cb685e1b0056878d31ae550ff">llvm::MachO::dysymtab_command::nextrel</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a84eede0ea68ac0b6f157e46372d226ec">llvm::MachO::dysymtab_command::nindirectsyms</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a4ea035f028815d8cd6f4d0c6d188db2d">llvm::MachO::dysymtab_command::nlocrel</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a90831317c37c80053ba24ca342da234d">llvm::MachO::dysymtab_command::nmodtab</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a060a8e9c435cda35c770e0b03810eefe">llvm::MachO::dysymtab_command::ntoc</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a13a60e45dcd6989958ab4ee352a340ae">llvm::MachO::dysymtab_command::tocoff</a>.</p>

</div>
</div>

### checkEncryptCommand() {#afbece8143fc21ed045b0d711c7103d17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error checkEncryptCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> &amp; Load, uint32_t LoadCommandIndex, uint64_t cryptoff, uint64_t cryptsize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char ** LoadCmd, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * CmdName)</td>
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



<p>Definition at line 918 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### checkLinkeditDataCommand() {#abe7067ce0893d97940a85141e4c44776}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error checkLinkeditDataCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> &amp; Load, uint32_t LoadCommandIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char ** LoadCmd, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * CmdName, std::list&lt; <a href="/web-llvm/docs/api/structs/machoelement">MachOElement</a> &gt; &amp; Elements, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ElementName)</td>
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



<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#ad8413e5e66b80672de909764764faf7f">checkOverlappingElement</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#ae1362ae4d0a99fed872ed4549adc95c4">llvm::MachO::linkedit_data_command::cmdsize</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a718c920e2473631759319ce93d069224">llvm::MachO::linkedit_data_command::dataoff</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a7d4425eb797faa587c5634883588c45d">llvm::MachO::linkedit_data_command::datasize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### checkLinkerOptCommand() {#a77b750f0deb484099d9f4f3539bda353}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error checkLinkerOptCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> &amp; Load, uint32_t LoadCommandIndex)</td>
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



<p>Definition at line 942 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#aab312a8386488873bac2eddfc67c22be">llvm::StringRef::find</a>, <a href="#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a8160a3004ff47f73b842d7030269ff3d">malformedError</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### checkNoteCommand() {#aedcf65b10ecb990ac021daf4f940a881}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error checkNoteCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> &amp; Load, uint32_t LoadCommandIndex, std::list&lt; <a href="/web-llvm/docs/api/structs/machoelement">MachOElement</a> &gt; &amp; Elements)</td>
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



<p>Definition at line 834 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#ad8413e5e66b80672de909764764faf7f">checkOverlappingElement</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/note-command/#ac22d213d8dd25b0d0fe3c5b74aa877ae">llvm::MachO::note_command::offset</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/note-command/#acfd7727342cc20c262f5adbae8c2ae18">llvm::MachO::note_command::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### checkOverlappingElement() {#ad8413e5e66b80672de909764764faf7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error checkOverlappingElement (std::list&lt; <a href="/web-llvm/docs/api/structs/machoelement">MachOElement</a> &gt; &amp; Elements, uint64_t Offset, uint64_t Size, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name)</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a4d955f22836e92a508b414d270041628">checkDyldInfoCommand</a>, <a href="#a21566fd3bc19b4348f0deed830e19199">checkDysymtabCommand</a>, <a href="#abe7067ce0893d97940a85141e4c44776">checkLinkeditDataCommand</a>, <a href="#aedcf65b10ecb990ac021daf4f940a881">checkNoteCommand</a>, <a href="#a197ed26dbc11fa1cf315ab378b657ec4">checkSymtabCommand</a>, <a href="#a1a0d53be15e648f327c4292341fa7dad">checkTwoLevelHintsCommand</a> and <a href="#a488ef72cdaf48278d8a1117a6833bad2">parseSegmentLoadCommand</a>.</p>

</div>
</div>

### checkRpathCommand() {#a636124b5ffd9b1f64c447b5d79b385fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error checkRpathCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> &amp; Load, uint32_t LoadCommandIndex)</td>
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



<p>Definition at line 886 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### checkSubCommand() {#a6231d1eadcf7d5f81f417fdc5fa394fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error checkSubCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> &amp; Load, uint32_t LoadCommandIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * CmdName, size_t SizeOfCmd, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * CmdStructName, uint32_t PathOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * PathFieldName)</td>
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



<p>Definition at line 982 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### checkSymtabCommand() {#a197ed26dbc11fa1cf315ab378b657ec4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error checkSymtabCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> &amp; Load, uint32_t LoadCommandIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char ** SymtabLoadCmd, std::list&lt; <a href="/web-llvm/docs/api/structs/machoelement">MachOElement</a> &gt; &amp; Elements)</td>
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



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#ad8413e5e66b80672de909764764faf7f">checkOverlappingElement</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#a97a6ee3c99c53b7173818e4ed375276f">llvm::MachO::symtab_command::cmdsize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a9c9aed90376ff1c700f89f5d037decff">llvm::object::MachOObjectFile::is64Bit</a>, <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#a1fe8ad1b38dc828beefc5757d7dc1a3a">llvm::MachO::symtab_command::nsyms</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#ad664b3b2032af10912280b74303ee21d">llvm::MachO::symtab_command::stroff</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#a1459968fe2ad55b364958070dde70c6e">llvm::MachO::symtab_command::strsize</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#ae6c74170eea156826ddfb4b61bd5d043">llvm::MachO::symtab_command::symoff</a>.</p>

</div>
</div>

### checkThreadCommand() {#abc5ff59b8ea0a100389a37ea8ec40f9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error checkThreadCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> &amp; Load, uint32_t LoadCommandIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * CmdName)</td>
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



<p>Definition at line 1009 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a24e2199b04f99bb4ac24256d1114f7b6ad94353affeaca0282eacc367c88f51e4">llvm::MachO::ARM_THREAD_STATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a24e2199b04f99bb4ac24256d1114f7b6a4cf242d2ef80e3c83a90c1b1e483d76a">llvm::MachO::ARM_THREAD_STATE64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a14f153503e42c1adab049555b63319ca">llvm::MachO::ARM_THREAD_STATE64_COUNT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa470f6c3231fe763665cff19779ecebb">llvm::MachO::ARM_THREAD_STATE_COUNT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47ae4da455e762f086662789406e1f085e0">llvm::MachO::CPU_TYPE_ARM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a33fddb0190d728c25e266a22d64bd7ad">llvm::MachO::CPU_TYPE_ARM64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a03cac236584f93f35c9ff89f2d65b716">llvm::MachO::CPU_TYPE_ARM64_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47aa9f8e9712ff2848d650f3c5d8c43c2f8">llvm::MachO::CPU_TYPE_I386</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a630a338da04bb807aac2b41f8fe4e6e7">llvm::MachO::CPU_TYPE_POWERPC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a633855cb5719de40d81669897cc571c8">llvm::MachO::CPU_TYPE_X86_64</a>, <a href="#ae148cedd3b13337408aac7949e546eb9">getCPUType</a>, <a href="#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a638ca5d7bf4e2a09998c8e7fe8563ad8">llvm::object::Binary::isLittleEndian</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a4ee2015697caec796e59972aadc2f9e2">llvm::sys::IsLittleEndianHost</a>, <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a85a3a87a2915d2d7578f7f40ce65c3eca1de77cef54cc62ed58cab848d445159b">llvm::MachO::PPC_THREAD_STATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a9ad83a3594a814e3f7c92cb153bbc67b">llvm::MachO::PPC_THREAD_STATE_COUNT</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ad0e418047a3e04c4fd1fb83325b571ae">llvm::sys::swapByteOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a937855dfb9d96613a8c67b100c881475a7285ce13bddeb7bae909614ff95ee515">llvm::MachO::x86_EXCEPTION_STATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a937855dfb9d96613a8c67b100c881475a5dbd22af825b992330b8f7e3d7fcef0f">llvm::MachO::x86_EXCEPTION_STATE64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae82a3ac145ec835b51f21e4d51c91a38">llvm::MachO::x86_EXCEPTION_STATE64_COUNT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a23fed8589b1a8362b310cc7105dc6998">llvm::MachO::x86_EXCEPTION_STATE_COUNT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a937855dfb9d96613a8c67b100c881475a96f117832be9a5c980b8da288224edf1">llvm::MachO::x86_FLOAT_STATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a0139f5c1b6af78d2af3675258d89a4a0">llvm::MachO::x86_FLOAT_STATE_COUNT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a937855dfb9d96613a8c67b100c881475a526320215093b6dac27517119c101295">llvm::MachO::x86_THREAD_STATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a937855dfb9d96613a8c67b100c881475a728c68cffec2bcb5526807a8222e36cc">llvm::MachO::x86_THREAD_STATE32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a7e05f48e6aca0f0b6015b43a6d519cb5">llvm::MachO::x86_THREAD_STATE32_COUNT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a937855dfb9d96613a8c67b100c881475a57dcc9508961024208663e5a0282d001">llvm::MachO::x86_THREAD_STATE64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aec959f0fb66f24095d19b4559e509913">llvm::MachO::x86_THREAD_STATE64_COUNT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac23432e69c77d99d8f5fcb92eee35e09">llvm::MachO::x86_THREAD_STATE_COUNT</a>.</p>

</div>
</div>

### checkTwoLevelHintsCommand() {#a1a0d53be15e648f327c4292341fa7dad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error checkTwoLevelHintsCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> &amp; Load, uint32_t LoadCommandIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char ** LoadCmd, std::list&lt; <a href="/web-llvm/docs/api/structs/machoelement">MachOElement</a> &gt; &amp; Elements)</td>
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



<p>Definition at line 1200 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#ad8413e5e66b80672de909764764faf7f">checkOverlappingElement</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/twolevel-hints-command/#a93d6b4d4278f5ab273840e4f1e121479">llvm::MachO::twolevel_hints_command::nhints</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/twolevel-hints-command/#acbb58bf820a0e8002e1fcf4a6a1a40af">llvm::MachO::twolevel_hints_command::offset</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### checkVersCommand() {#a0e53134a7b107f2a0f6213f2f5ed21e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error checkVersCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> &amp; Load, uint32_t LoadCommandIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char ** LoadCmd, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * CmdName)</td>
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



<p>Definition at line 819 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### getArray() {#a8e5744e3da3116ce5eaf50660b88d6aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt; T, N &gt; getArray (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * Ptr)</td>
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



<p>Definition at line 5148 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a4ee2015697caec796e59972aadc2f9e2">llvm::sys::IsLittleEndianHost</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ad0e418047a3e04c4fd1fb83325b571ae">llvm::sys::swapByteOrder</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a11261ec56e31921149aa022482d80e7e">llvm::object::MachOObjectFile::getDyldChainedFixupTargets</a>.</p>

</div>
</div>

### getCPUSubType() {#afae525cefbe3d0179a73a5ffb555160b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getCPUSubType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; O)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmbackenddarwin/#a8a9aeec3d6dbf964fefb7758055cf0d6">llvm::ARMAsmBackendDarwin::ARMAsmBackendDarwin</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a0c6dd60e5645b2ff160ea7368c04e78f">llvm::object::MachOObjectFile::getArch</a>.</p>

</div>
</div>

### getCPUType() {#ae148cedd3b13337408aac7949e546eb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getCPUType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; O)</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Referenced by <a href="#abc5ff59b8ea0a100389a37ea8ec40f9a">checkThreadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a0c6dd60e5645b2ff160ea7368c04e78f">llvm::object::MachOObjectFile::getArch</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a216609c43afe05c3da08214afdc8e72b">llvm::object::MachOObjectFile::getFileFormatName</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad07c873a9197ed022e779129f28ca028">llvm::object::MachOObjectFile::isRelocationScattered</a>.</p>

</div>
</div>

### getEncodedOrdinal() {#ac78e4faf9bf0789dfdf928c2ff83d731}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getEncodedOrdinal (T Value)</td>
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



<p>Definition at line 5139 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48ca294d164bd72c67e18da73f2677b4ac92d317359f68971056be15d73a5af1f">llvm::MachO::BIND_SPECIAL_DYLIB_FLAT_LOOKUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48ca294d164bd72c67e18da73f2677b4ab94549f22a3024bff13399df18c02d9c">llvm::MachO::BIND_SPECIAL_DYLIB_MAIN_EXECUTABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48ca294d164bd72c67e18da73f2677b4a52dee48bcdbbf0e47685ddb55fcd93c5">llvm::MachO::BIND_SPECIAL_DYLIB_WEAK_LOOKUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd6925150e1774fabfaff17efd3f9b9e">llvm::SignExtend32</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a11261ec56e31921149aa022482d80e7e">llvm::object::MachOObjectFile::getDyldChainedFixupTargets</a>.</p>

</div>
</div>

### getFirstLoadCommandInfo() {#a3d77869bd604539426d81bd418ce875f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; MachOObjectFile::LoadCommandInfo &gt; getFirstLoadCommandInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj)</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a80dc9af48926f9c1b70075f71c6002a7">llvm::object::MachOObjectFile::getHeader</a>, <a href="#ada8e7ae873a0bd17132af43d3a128f8e">getLoadCommandInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aeb95a0420b2442e27f0b4023926c72fe">llvm::object::MachOObjectFile::getMachOFilesetEntryOffset</a>, <a href="#a3d9162ba919b64a3930354acc96f098b">getPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a9c9aed90376ff1c700f89f5d037decff">llvm::object::MachOObjectFile::is64Bit</a>, <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/mach-header/#a702156ea36c201c0e383aac5c1c05cf3">llvm::MachO::mach_header::sizeofcmds</a>.</p>

</div>
</div>

### getLoadCommandInfo() {#ada8e7ae873a0bd17132af43d3a128f8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; MachOObjectFile::LoadCommandInfo &gt; getLoadCommandInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Ptr, uint32_t LoadCommandIndex)</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#a3d77869bd604539426d81bd418ce875f">getFirstLoadCommandInfo</a> and <a href="#afdea79cf3204fe335d9ebceb78e6a778">getNextLoadCommandInfo</a>.</p>

</div>
</div>

### getNextLoadCommandInfo() {#afdea79cf3204fe335d9ebceb78e6a778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; MachOObjectFile::LoadCommandInfo &gt; getNextLoadCommandInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj, uint32_t LoadCommandIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> &amp; L)</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a80dc9af48926f9c1b70075f71c6002a7">llvm::object::MachOObjectFile::getHeader</a>, <a href="#ada8e7ae873a0bd17132af43d3a128f8e">getLoadCommandInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aeb95a0420b2442e27f0b4023926c72fe">llvm::object::MachOObjectFile::getMachOFilesetEntryOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a9c9aed90376ff1c700f89f5d037decff">llvm::object::MachOObjectFile::is64Bit</a>, <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/mach-header/#a702156ea36c201c0e383aac5c1c05cf3">llvm::MachO::mach_header::sizeofcmds</a>.</p>

</div>
</div>

### getPlainRelocationAddress() {#a737f9117ad9ecb54eff89ae39cc5e0c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t getPlainRelocationAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a> &amp; RE)</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info/#a2c1c46bbe4b0ef3065fe91d3e9ca806e">llvm::MachO::any_relocation_info::r_word0</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad388361f228398a0d6ccd304f88138fa">llvm::object::MachOObjectFile::getAnyRelocationAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad07c873a9197ed022e779129f28ca028">llvm::object::MachOObjectFile::isRelocationScattered</a>.</p>

</div>
</div>

### getPlainRelocationLength() {#a5bfc08d3a7440ea1dd3d51785b5d3667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getPlainRelocationLength (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a> &amp; RE)</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info/#aff97edf4109298178b12aca5621bd6ec">llvm::MachO::any_relocation_info::r_word1</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a942691b0e7a01c33a7aa6b36b28472d2">llvm::object::MachOObjectFile::getAnyRelocationLength</a>.</p>

</div>
</div>

### getPlainRelocationPCRel() {#a7c487242e400b912bb74ac8cdfc4b299}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getPlainRelocationPCRel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a> &amp; RE)</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info/#aff97edf4109298178b12aca5621bd6ec">llvm::MachO::any_relocation_info::r_word1</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a86eeaa5626787e6a0c62d7fef9ea33e9">llvm::object::MachOObjectFile::getAnyRelocationPCRel</a>.</p>

</div>
</div>

### getPlainRelocationType() {#a20d9592bf3c885c6afab008b7bb1789e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getPlainRelocationType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a> &amp; RE)</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info/#aff97edf4109298178b12aca5621bd6ec">llvm::MachO::any_relocation_info::r_word1</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a653a63105b842dd49a3a0921ce6a6d66">llvm::object::MachOObjectFile::getAnyRelocationType</a>.</p>

</div>
</div>

### getPtr() {#a3d9162ba919b64a3930354acc96f098b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getPtr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; O, size_t Offset, size_t MachOFilesetEntryOffset=0)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a21eb1fb7d7f36d23fdd47f8e7ff0e2f1">llvm::object::MachOObjectFile::begin_dices</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a3de0b5962983ce2a4ba1d258add13090">llvm::Error::dynamicClassID</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a67ca29eb8dc5ee438d5cc11cf5a460d9">llvm::object::MachOObjectFile::end_dices</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad107a2e9bf01094f9564019267eace1d">llvm::object::MachOObjectFile::getChainedFixupsHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a766c3350d64dde8af24ef7b600b11185">llvm::object::MachOObjectFile::getChainedFixupsSegments</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aaf48787fae336569ae8e87a4a645174b">llvm::object::MachOObjectFile::getDataInCodeTableEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a11261ec56e31921149aa022482d80e7e">llvm::object::MachOObjectFile::getDyldChainedFixupTargets</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a7107ae3ee300f48f02997f50fe543c0f">llvm::object::MachOObjectFile::getDyldExportsTrie</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#abee9da1b8caf9806998dc3fbc8fa02be">llvm::object::MachOObjectFile::getDyldInfoBindOpcodes</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a5d2c48586c800c9f29be71be14da45cf">llvm::object::MachOObjectFile::getDyldInfoExportsTrie</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a428c19e380ff63f21f2bfb4fdf0078b5">llvm::object::MachOObjectFile::getDyldInfoLazyBindOpcodes</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a8bf468d783b97cfaf64cce155ccc9365">llvm::object::MachOObjectFile::getDyldInfoRebaseOpcodes</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ac6987c2142793b0d0eb897b4eb2c2712">llvm::object::MachOObjectFile::getDyldInfoWeakBindOpcodes</a>, <a href="#a3d77869bd604539426d81bd418ce875f">getFirstLoadCommandInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#af0479ec0a64582d6ad2df6f5231beae3">llvm::object::MachOObjectFile::getIndirectSymbolTableEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aaacf649b0759051f6c5327e44b82f8aa">llvm::object::MachOObjectFile::getRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a19321b2c5a24656fe59c193ae2892453">llvm::object::MachOObjectFile::getRelocationSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a7d7c96e485022e0023e9b8eec0257f0e">llvm::object::MachOObjectFile::getSymbolByIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a24c6aaf027b70314a4e7cb05b34ab302">llvm::object::MachOObjectFile::getSymbolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#afbfea2fa926cd1894c74b44c79c75601">llvm::Error::isA</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a981b4992a3b7cce718c7995a7d6193a0">llvm::Error::operator bool</a>, <a href="#adcb372f00f2b01dc20f3567b2eb97be3">parseHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aabf498b6cb34cb967c73e3c0c51baee2">llvm::object::MachOObjectFile::symbol_end</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a31787a05ac40b00e24901840ee2c2f80">llvm::Error::~Error</a>.</p>

</div>
</div>

### getScatteredRelocationAddress() {#a922ba9d09d115911235efb6e517b5ef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getScatteredRelocationAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a> &amp; RE)</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info/#a2c1c46bbe4b0ef3065fe91d3e9ca806e">llvm::MachO::any_relocation_info::r_word0</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad388361f228398a0d6ccd304f88138fa">llvm::object::MachOObjectFile::getAnyRelocationAddress</a>.</p>

</div>
</div>

### getScatteredRelocationLength() {#a53ac15ba730cd5a7e82f50b6bc1bf715}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getScatteredRelocationLength (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a> &amp; RE)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info/#a2c1c46bbe4b0ef3065fe91d3e9ca806e">llvm::MachO::any_relocation_info::r_word0</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a942691b0e7a01c33a7aa6b36b28472d2">llvm::object::MachOObjectFile::getAnyRelocationLength</a>.</p>

</div>
</div>

### getScatteredRelocationPCRel() {#ad6a5d311edf7adea28255db07dd3fc7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getScatteredRelocationPCRel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a> &amp; RE)</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info/#a2c1c46bbe4b0ef3065fe91d3e9ca806e">llvm::MachO::any_relocation_info::r_word0</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a86eeaa5626787e6a0c62d7fef9ea33e9">llvm::object::MachOObjectFile::getAnyRelocationPCRel</a>.</p>

</div>
</div>

### getSectionFlags() {#ac5ea45808f76ad3f6b0159739e80d160}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t getSectionFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; O, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/macho/section/#ab0c6e8f900f73f5d46990669e9fb6998">llvm::MachO::section::flags</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/section-64/#a8eaaee3363d1105468fb49b513fe7e6c">llvm::MachO::section_64::flags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a6219972bdae3e9ac0f4daf447f328d82">llvm::object::MachOObjectFile::getSectionType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a7434406d3c7c482b788bf6db4275831b">llvm::object::MachOObjectFile::isSectionBSS</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a0f8cd1e7801f694e4a6c5e109b96773c">llvm::object::MachOObjectFile::isSectionData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ac7ac740eb18150e6b303020623754638">llvm::object::MachOObjectFile::isSectionText</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a76ba9d917492e4d238d3d9062d755494">llvm::object::MachOObjectFile::isSectionVirtual</a>.</p>

</div>
</div>

### getSectionPtr() {#a7695bd8a585d6d772c516b6e7b7aa0e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getSectionPtr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; O, <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> L, unsigned Sec)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a4916f4a65ce359c50389bc77a5689f7a">llvm::object::MachOObjectFile::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aa868c47bf47a793dbd158c31f3d9864e">llvm::object::MachOObjectFile::getSection64</a> and <a href="#a488ef72cdaf48278d8a1117a6833bad2">parseSegmentLoadCommand</a>.</p>

</div>
</div>

### getStruct() {#a65d683ab0721978a7568df291210a549}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T getStruct (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * P)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a4ee2015697caec796e59972aadc2f9e2">llvm::sys::IsLittleEndianHost</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a754466f4b36d6a2365e56663e0d9de83">llvm::MachO::swapStruct</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a2ab44ec13134d5fef903151e368f3c8a">llvm::object::MachOObjectFile::getBuildToolVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a2576066f592129dbe8f9624c90bf19ef">llvm::object::MachOObjectFile::getBuildVersionLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a2b03ad21c736b26f5396403bf49f2a59">llvm::object::MachOObjectFile::getDataInCodeLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aaf48787fae336569ae8e87a4a645174b">llvm::object::MachOObjectFile::getDataInCodeTableEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aafff2e6b7435d209427acf5ab83bf375">llvm::object::MachOObjectFile::getDice</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a708244b1c588ce222e471dd17719b9b5">llvm::object::MachOObjectFile::getDyldInfoLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aeb9478037b0d4a28a04ad1d690e2f645">llvm::object::MachOObjectFile::getDylibIDLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aa1db3c0b49113ff3627eb1ecd2f7b477">llvm::object::MachOObjectFile::getDylinkerCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a4479f956205d53f462400c0f9e98674a">llvm::object::MachOObjectFile::getDysymtabLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a806af0cdf9cc3ef071e2a103dad08e31">llvm::object::MachOObjectFile::getEncryptionInfoCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a1feb8b357acb0ed676d8b4a1954c5623">llvm::object::MachOObjectFile::getEncryptionInfoCommand64</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a352e221c16019d6045da26a3209e40c4">llvm::object::MachOObjectFile::getEntryPointCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a5203f8a41fa3b6a2e3cbc8949c1fc962">llvm::object::MachOObjectFile::getFilesetEntryLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#af0479ec0a64582d6ad2df6f5231beae3">llvm::object::MachOObjectFile::getIndirectSymbolTableEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ae669e6342a3406842cda2714f1f143c9">llvm::object::MachOObjectFile::getLinkeditDataLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a31b3a7bf8a638884321a2df0f787fe05">llvm::object::MachOObjectFile::getLinkerOptionLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a64bfe87a4a35f817e902fc4c3c50f5d2">llvm::object::MachOObjectFile::getLinkOptHintsLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a527b022bfecb5185b104f66bb26ce3c6">llvm::object::MachOObjectFile::getNoteLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aaacf649b0759051f6c5327e44b82f8aa">llvm::object::MachOObjectFile::getRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a2badd591726f82a2e5942e44907c80ec">llvm::object::MachOObjectFile::getRoutinesCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a6b01323aa4c54564eeef35c5cf7d0151">llvm::object::MachOObjectFile::getRoutinesCommand64</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a66f24d7c05980ed733c32c31f099766d">llvm::object::MachOObjectFile::getRpathCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a4916f4a65ce359c50389bc77a5689f7a">llvm::object::MachOObjectFile::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#abd858c258a4333c61658e66fcbbaa9e7">llvm::object::MachOObjectFile::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aa868c47bf47a793dbd158c31f3d9864e">llvm::object::MachOObjectFile::getSection64</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a4ddf638fa2c882a669517ae17a4e032a">llvm::object::MachOObjectFile::getSection64</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a5b1695c0e56a3fd6bcefcaccb8b9dab6">llvm::object::MachOObjectFile::getSegment64LoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a6317d38843b3ac79b92a3c85bb2ed7b5">llvm::object::MachOObjectFile::getSegmentLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad17a0cc5e558e81985224344a3dd57bb">llvm::object::MachOObjectFile::getSourceVersionCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a023569a7035ef18e014f39cc2800ad07">llvm::object::MachOObjectFile::getSubClientCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a6c0b621a228e683bf4590229691489aa">llvm::object::MachOObjectFile::getSubFrameworkCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a6f9c9811944d064d439d7c5d9bf64cd5">llvm::object::MachOObjectFile::getSubLibraryCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a70b068a5ae812db11c38e8b8dc23617b">llvm::object::MachOObjectFile::getSubUmbrellaCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a62195bc7e86a573ecebe708bee210b61">llvm::object::MachOObjectFile::getSymbol64TableEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a2df84b6031947d33d436f49b29a699b2">llvm::object::MachOObjectFile::getSymbolTableEntry</a>, <a href="#a0e0b242aa7cb8cb269f5ea9973a9f605">getSymbolTableEntryBase</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a9451d5e767c3b97403785baaff3c6a44">llvm::object::MachOObjectFile::getSymtabLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a53d6fbb63f40bcf11cf7e5d674534440">llvm::object::MachOObjectFile::getThreadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a983feccca34dfdfebe0d79c35c166d7d">llvm::object::MachOObjectFile::getUuidCommand</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a9d29d7cb48a7f246f1c0f4507def2aa7">llvm::object::MachOObjectFile::getVersionMinLoadCommand</a>.</p>

</div>
</div>

### getStructOrErr() {#a3be6030c853d0e0ffe5bc8545197118a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; T &gt; getStructOrErr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * P)</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a4ee2015697caec796e59972aadc2f9e2">llvm::sys::IsLittleEndianHost</a>, <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a754466f4b36d6a2365e56663e0d9de83">llvm::MachO::swapStruct</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#ae8d5d23303122b92e1b4a0afbdb9e656">checkDyldCommand</a>, <a href="#a4d955f22836e92a508b414d270041628">checkDyldInfoCommand</a>, <a href="#a29d1b39b4762b4de7a37817a3a01355f">checkDylibCommand</a>, <a href="#a21566fd3bc19b4348f0deed830e19199">checkDysymtabCommand</a>, <a href="#abe7067ce0893d97940a85141e4c44776">checkLinkeditDataCommand</a>, <a href="#a77b750f0deb484099d9f4f3539bda353">checkLinkerOptCommand</a>, <a href="#aedcf65b10ecb990ac021daf4f940a881">checkNoteCommand</a>, <a href="#a636124b5ffd9b1f64c447b5d79b385fc">checkRpathCommand</a>, <a href="#a197ed26dbc11fa1cf315ab378b657ec4">checkSymtabCommand</a>, <a href="#abc5ff59b8ea0a100389a37ea8ec40f9a">checkThreadCommand</a>, <a href="#a1a0d53be15e648f327c4292341fa7dad">checkTwoLevelHintsCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad107a2e9bf01094f9564019267eace1d">llvm::object::MachOObjectFile::getChainedFixupsHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a226f358d6c1305cdba13949825b60b49">llvm::object::MachOObjectFile::getChainedFixupsLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a766c3350d64dde8af24ef7b600b11185">llvm::object::MachOObjectFile::getChainedFixupsSegments</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a7107ae3ee300f48f02997f50fe543c0f">llvm::object::MachOObjectFile::getDyldExportsTrie</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#abee9da1b8caf9806998dc3fbc8fa02be">llvm::object::MachOObjectFile::getDyldInfoBindOpcodes</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a5d2c48586c800c9f29be71be14da45cf">llvm::object::MachOObjectFile::getDyldInfoExportsTrie</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a428c19e380ff63f21f2bfb4fdf0078b5">llvm::object::MachOObjectFile::getDyldInfoLazyBindOpcodes</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a8bf468d783b97cfaf64cce155ccc9365">llvm::object::MachOObjectFile::getDyldInfoRebaseOpcodes</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ac6987c2142793b0d0eb897b4eb2c2712">llvm::object::MachOObjectFile::getDyldInfoWeakBindOpcodes</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a6e304ff95b5d1ea04529da35d5307d6f">llvm::object::MachOObjectFile::getFunctionStarts</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#afea73c1af002769dde1fb465f40b6ac1">llvm::object::MachOObjectFile::getLibraryShortNameByIndex</a>, <a href="#ada8e7ae873a0bd17132af43d3a128f8e">getLoadCommandInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machoobjectfile-cpp-/#a468583934460cfc450055eaac3ec3397">anonymous{MachOObjectFile.cpp}::getSegmentContents</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machoobjectfile-cpp-/#ad6473b2753bdca7d12955749ed652b7c">anonymous{MachOObjectFile.cpp}::getSegmentContents</a>, <a href="#a1d797aa90eeef9897ebdcf1c8332441e">parseBuildVersionCommand</a>, <a href="#adcb372f00f2b01dc20f3567b2eb97be3">parseHeader</a> and <a href="#a488ef72cdaf48278d8a1117a6833bad2">parseSegmentLoadCommand</a>.</p>

</div>
</div>

### getSymbolTableEntryBase() {#a0e0b242aa7cb8cb269f5ea9973a9f605}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::nlist_base getSymbolTableEntryBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; O, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> DRI)</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a65d683ab0721978a7568df291210a549">getStruct</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a1c4dce386c635e9449383a532bc38070">llvm::object::MachOObjectFile::getIndirectName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad12defbd432cf6bb7f7b05f956681e03">llvm::object::MachOObjectFile::getSymbolAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a725d75c745df0f036d8e5fba0670f13d">llvm::object::MachOObjectFile::getSymbolFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a79ff60972cb2fd27ac7280c9e5052d4a">llvm::object::MachOObjectFile::getSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a35b89b3d8775f01eeeb4e36769e2b435">llvm::object::MachOObjectFile::getSymbolSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a2f79817cbc7f06dd7a434e20281a0ad5">llvm::object::MachOObjectFile::getSymbolSectionID</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#abfea148e3e5693c88962ce5add39bf56">llvm::object::MachOObjectFile::getSymbolType</a>.</p>

</div>
</div>

### isLoadCommandObsolete() {#ac162ad8e535e9ed3392b5a72f35f0106}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isLoadCommandObsolete (uint32_t cmd)</td>
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



<p>Definition at line 1239 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/macho/linker-option-command/#a9df5bbe2a9e72c00d7da594e267e13e5">llvm::MachO::linker_option_command::cmd</a>.</p>

</div>
</div>

### malformedError() {#ac0d9caa1a6547eb43569666b040b4b96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error malformedError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>.</p>


<p>Referenced by <a href="#ae8d5d23303122b92e1b4a0afbdb9e656">checkDyldCommand</a>, <a href="#a4d955f22836e92a508b414d270041628">checkDyldInfoCommand</a>, <a href="#a29d1b39b4762b4de7a37817a3a01355f">checkDylibCommand</a>, <a href="#af5d5ac386b9d143dc66cbb3bdac42adf">checkDylibIdCommand</a>, <a href="#a21566fd3bc19b4348f0deed830e19199">checkDysymtabCommand</a>, <a href="#afbece8143fc21ed045b0d711c7103d17">checkEncryptCommand</a>, <a href="#abe7067ce0893d97940a85141e4c44776">checkLinkeditDataCommand</a>, <a href="#a77b750f0deb484099d9f4f3539bda353">checkLinkerOptCommand</a>, <a href="#aedcf65b10ecb990ac021daf4f940a881">checkNoteCommand</a>, <a href="#ad8413e5e66b80672de909764764faf7f">checkOverlappingElement</a>, <a href="#a636124b5ffd9b1f64c447b5d79b385fc">checkRpathCommand</a>, <a href="#a6231d1eadcf7d5f81f417fdc5fa394fc">checkSubCommand</a>, <a href="#a197ed26dbc11fa1cf315ab378b657ec4">checkSymtabCommand</a>, <a href="#abc5ff59b8ea0a100389a37ea8ec40f9a">checkThreadCommand</a>, <a href="#a1a0d53be15e648f327c4292341fa7dad">checkTwoLevelHintsCommand</a>, <a href="#a0e53134a7b107f2a0f6213f2f5ed21e1">checkVersCommand</a>, <a href="#a3d77869bd604539426d81bd418ce875f">getFirstLoadCommandInfo</a>, <a href="#ada8e7ae873a0bd17132af43d3a128f8e">getLoadCommandInfo</a>, <a href="#afdea79cf3204fe335d9ebceb78e6a778">getNextLoadCommandInfo</a>, <a href="#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="#a1d797aa90eeef9897ebdcf1c8332441e">parseBuildVersionCommand</a>, <a href="#adcb372f00f2b01dc20f3567b2eb97be3">parseHeader</a> and <a href="#a488ef72cdaf48278d8a1117a6833bad2">parseSegmentLoadCommand</a>.</p>

</div>
</div>

### parseBuildVersionCommand() {#a1d797aa90eeef9897ebdcf1c8332441e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error parseBuildVersionCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> &amp; Load, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; &amp; BuildTools, uint32_t LoadCommandIndex)</td>
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



<p>Definition at line 863 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/build-version-command/#a39ff09988b1a668f82b7f145b5239659">llvm::MachO::build_version_command::ntools</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### parseHeader() {#adcb372f00f2b01dc20f3567b2eb97be3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void parseHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj, T &amp; Header, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
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



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aeb95a0420b2442e27f0b4023926c72fe">llvm::object::MachOObjectFile::getMachOFilesetEntryOffset</a>, <a href="#a3d9162ba919b64a3930354acc96f098b">getPtr</a>, <a href="#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### parseSegmentLoadCommand() {#a488ef72cdaf48278d8a1117a6833bad2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Segment, typename Section&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error parseSegmentLoadCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">MachOObjectFile::LoadCommandInfo</a> &amp; Load, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; &amp; Sections, bool &amp; IsPageZeroSegment, uint32_t LoadCommandIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * CmdName, uint64_t SizeOfHeaders, std::list&lt; <a href="/web-llvm/docs/api/structs/machoelement">MachOElement</a> &gt; &amp; Elements)</td>
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



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#ad8413e5e66b80672de909764764faf7f">checkOverlappingElement</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/mach-header/#a81b6102d4c7c4130c894948b968d9d24">llvm::MachO::mach_header::filetype</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a80dc9af48926f9c1b70075f71c6002a7">llvm::object::MachOObjectFile::getHeader</a>, <a href="#a7695bd8a585d6d772c516b6e7b7aa0e3">getSectionPtr</a>, <a href="#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="#ac0d9caa1a6547eb43569666b040b4b96">malformedError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a4099e754341e36bdbc04624fa2f1e19aa435d5697f5999438d44a0501ee1da83c">llvm::MachO::MH_DSYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a4099e754341e36bdbc04624fa2f1e19aa6885d2f4c415c3e66cb5b2a71b4d6e46">llvm::MachO::MH_DYLIB_STUB</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a30ad04b8f551f61de19b8756ab76eae2">llvm::MachO::S_THREAD_LOCAL_ZEROFILL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a901e329f9c215482ab4877d7efec0768">llvm::MachO::S_ZEROFILL</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### parseSegmentOrSectionName() {#ad91ce3ef577757936597aace8a21fdef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef parseSegmentOrSectionName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * P)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a647f0ec13a56dcdcf59ff036090db193">llvm::object::MachOObjectFile::getSectionFinalSegmentName</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ac459e969de113b3d211c0a4087656dc7">llvm::object::MachOObjectFile::getSectionName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### HANDLE\_SWIFT\_SECTION {#aed88b751512325308cd8b51594c038c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_SWIFT_SECTION(KIND, MACHO, ELF, COFF)&nbsp;&nbsp;&nbsp;  .Case(MACHO, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h/#a0fe94e4721fb2c4dfc05937e4c71aa2c">llvm::binaryformat::Swift5ReflectionSectionKind::KIND</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5392 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
