---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ELFObjcopy.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/include/llvm/objcopy/elf/elfobjcopy-h">llvm/ObjCopy/ELF/ELFObjcopy.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitmaskenum-h">llvm/ADT/BitmaskEnum.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/denseset-h">llvm/ADT/DenseSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">llvm/BinaryFormat/ELF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">llvm/MC/MCTargetOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/commonconfig-h">llvm/ObjCopy/CommonConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/include/llvm/objcopy/elf/elfconfig-h">llvm/ObjCopy/ELF/ELFConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/binary-h">llvm/Object/Binary.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">llvm/Object/ELFObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">llvm/Object/ELFTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/error-h">llvm/Object/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">llvm/Option/Option.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compression-h">llvm/Support/Compression.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errc-h">llvm/Support/Errc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memory-h">llvm/Support/Memory.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstdlib&gt;
#include &lt;functional&gt;
#include &lt;memory&gt;
#include &lt;string&gt;
#include &lt;system_error&gt;
#include &lt;utility&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-elfobjcopy-cpp-">anonymous{ELFObjcopy.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-elfobjcopy-cpp-/removenotedetail">RemoveNoteDetail</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-elfobjcopy-cpp-/removenotedetail/deletedrange">DeletedRange</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d2098d7d394c83ff9e7e4c780987788">SectionPred</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">std::function</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase">SectionBase</a> &amp;Sec)&gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa080c38d82f500daf23c736bba23b17b">isDebugSection</a> (const SectionBase &amp;Sec)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a803c3a86a5b67ff8123a45143bbe7586">isDWOSection</a> (const SectionBase &amp;Sec)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae35a722a2cd0dda812793c6e52fdd130">onlyKeepDWOPred</a> (const Object &amp;Obj, const SectionBase &amp;Sec)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef707b818903d07ba361fda725b70535">getNewShfFlags</a> (SectionFlag AllFlags, uint16_t EMachine)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af89c6b030af06ff05dbad7d43da092de">getSectionFlagsPreserveMask</a> (uint64_t OldFlags, uint64_t NewFlags, uint16_t EMachine)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6b496602d8ee433064896a9742c766a">setSectionType</a> (SectionBase &amp;Sec, uint64_t Type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5bc7bb3463aa7528d85207065490482">setSectionFlagsAndType</a> (SectionBase &amp;Sec, SectionFlag Flags, uint16_t EMachine)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a05b443eeddaf38be35f2de5dcfcc833b">ElfType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afda0e76ccd38bd614c1eefa534b8d25f">getOutputElfType</a> (const Binary &amp;Bin)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a05b443eeddaf38be35f2de5dcfcc833b">ElfType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5c7dbb4f05e4e34f8347a9677b073df">getOutputElfType</a> (const MachineInfo &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/writer">Writer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af799c939a84893d6b7e282b6771a0dfa">createELFWriter</a> (const CommonConfig &amp;Config, Object &amp;Obj, raw_ostream &amp;Out, ElfType OutputElfType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/writer">Writer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb076c75c71a43f683c48aeced9f9f78">createWriter</a> (const CommonConfig &amp;Config, Object &amp;Obj, raw_ostream &amp;Out, ElfType OutputElfType)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa40e91285159d4c13a609b1810b19485">dumpSectionToFile</a> (StringRef SecName, StringRef Filename, StringRef InputFilename, Object &amp;Obj)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0d4b42054c461c36914f330dfeb6a2f">isAArch64MappingSymbol</a> (const Symbol &amp;Sym)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fba79f4ceb18ec7c14f9a5cc803336d">isArmMappingSymbol</a> (const Symbol &amp;Sym)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92cd760b5502a4ca65bd18343560e39e">isRequiredByABISymbol</a> (const Object &amp;Obj, const Symbol &amp;Sym)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1a626d227da26acd29100b5f2c68172">isUnneededSymbol</a> (const Symbol &amp;Sym)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a8b0267a862203c3082ed955abd326c">updateAndRemoveSymbols</a> (const CommonConfig &amp;Config, const ELFConfig &amp;ELFConfig, Object &amp;Obj)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0caf08c068a9900ddcabffcf9f004b41">replaceAndRemoveSections</a> (const CommonConfig &amp;Config, const ELFConfig &amp;ELFConfig, Object &amp;Obj)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a485a790f83f65357b91f1e369bc194da">addSymbol</a> (Object &amp;Obj, const NewSymbolInfo &amp;SymInfo, uint8_t DefaultVisibility)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06d536441c3553e3bc7639fdfb0fb45c">removeNotes</a> (Object &amp;Obj, endianness Endianness, ArrayRef&lt; RemoveNoteInfo &gt; NotesToRemove, function_ref&lt; Error(Error)&gt; ErrorCallback)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4454edff33cc45fad3f75d835f91cb37">handleUserSection</a> (const NewSectionInfo &amp;NewSection, function_ref&lt; Error(StringRef, ArrayRef&lt; uint8_t &gt;)&gt; F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73b370d004cc941240050b8048fefb7e">verifyNoteSection</a> (StringRef Name, endianness Endianness, ArrayRef&lt; uint8_t &gt; Data)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a0331e763d1ccb3e64db8de4d9791c8">handleArgs</a> (const CommonConfig &amp;Config, const ELFConfig &amp;ELFConfig, ElfType OutputElfType, Object &amp;Obj)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac889c429edbee2b4f43a2292ecb1ceb0">writeOutput</a> (const CommonConfig &amp;Config, Object &amp;Obj, raw_ostream &amp;Out, ElfType OutputElfType)</td>
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

## Typedefs

### SectionPred {#a5d2098d7d394c83ff9e7e4c780987788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using SectionPred =  std::function&lt;bool(const SectionBase &amp;Sec)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### addSymbol() {#a485a790f83f65357b91f1e369bc194da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addSymbol (<a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object">Object</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/newsymbolinfo">NewSymbolInfo</a> &amp; SymInfo, uint8_t DefaultVisibility)</td>
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



<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#aaf9e58af43e8a65398a93a487d2bdb5f">llvm::objcopy::elf::SectionBase::Addr</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/symboltablesection/#a4ea6559044a6a659b3228044447682ca">llvm::objcopy::elf::SymbolTableSection::addSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a88eeb89876019c1a9f2540275fb96457a7a1920d61156abc05a60135aefe8bc67">llvm::objcopy::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a88eeb89876019c1a9f2540275fb96457a0b27918290ff5323bea1e3b78a9cf04e">llvm::objcopy::File</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#ae85ce81813d60e59c704aecbf2525a1d">llvm::objcopy::elf::Object::findSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a88eeb89876019c1a9f2540275fb96457a86408593c34af77fdd90df932f8b5261">llvm::objcopy::Function</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a88eeb89876019c1a9f2540275fb96457a4cc6684df7b4a92b1dec6fce3264fac8">llvm::objcopy::Global</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a88eeb89876019c1a9f2540275fb96457a7acdf85c69cc3c5305456a293524386e">llvm::objcopy::Hidden</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a88eeb89876019c1a9f2540275fb96457a2909072b8677a9129708480ceec25dac">llvm::objcopy::IndirectFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a88eeb89876019c1a9f2540275fb96457a509820290d57f333403f490dde7316f4">llvm::objcopy::Local</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a88eeb89876019c1a9f2540275fb96457a497031794414a552435f90151ac3b54b">llvm::objcopy::Object</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a88eeb89876019c1a9f2540275fb96457a56f0605c9795b173abd2e34fab7fc164">llvm::objcopy::Protected</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a88eeb89876019c1a9f2540275fb96457ad2c24d59e0baff4d0155fbdf62590867">llvm::objcopy::Section</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a319b64bc6b9c38e948eda8bfafff58b5">llvm::ELF::SHN_ABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a3056225276d5d76c1b142d3505704851">llvm::ELF::STB_GLOBAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a492b026d2205f6f178f7eb7863018e31">llvm::ELF::STB_LOCAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77afb3fa0269fc31b10834def07f16c1649">llvm::ELF::STB_WEAK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a58921cad23ba8bdf0c8077b7a2923127">llvm::ELF::STT_FILE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a28ceebccd9f41f8a7e2359ac45c59f66">llvm::ELF::STT_FUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a7269ceaea4bf3dbd15caa427598cbcb9">llvm::ELF::STT_GNU_IFUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a2addd3222711e927ec6604bc65bccb2c">llvm::ELF::STT_NOTYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a9803bad2cfdce7601000ee3f6b979d9b">llvm::ELF::STT_OBJECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a579f54f07d96da2627125a17e0353b14">llvm::ELF::STT_SECTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a78278359d67657d43c307d922ad9a1d5af3e7284f94dabe52ad31412ab70c15f4">llvm::ELF::STV_DEFAULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a78278359d67657d43c307d922ad9a1d5ab38517de2fd6c124c49e40bc25c25c0c">llvm::ELF::STV_HIDDEN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a78278359d67657d43c307d922ad9a1d5aec3ecfdbfbbe90889a70c56df29b263a">llvm::ELF::STV_PROTECTED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#ad662eaf5ade24ec38c0b3d5330d20235aa9b48dec355621d54558da7d4768a660">llvm::objcopy::elf::SYMBOL_SIMPLE_INDEX</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a992d6065f91670a70730547fa168dcc7">llvm::objcopy::elf::Object::SymbolTable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a88eeb89876019c1a9f2540275fb96457a7324e3727807d95037eb19d304fd91ec">llvm::objcopy::Weak</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/symboladdressmap/#a9ffd5531d6187a911efd7354ded9e3d4">llvm::jitlink::SymbolAddressMap::addSymbols</a> and <a href="#a1a0331e763d1ccb3e64db8de4d9791c8">handleArgs</a>.</p>

</div>
</div>

### createELFWriter() {#af799c939a84893d6b7e282b6771a0dfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; Writer &gt; createELFWriter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig">CommonConfig</a> &amp; Config, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object">Object</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a05b443eeddaf38be35f2de5dcfcc833b">ElfType</a> OutputElfType)</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a05b443eeddaf38be35f2de5dcfcc833ba590309530fe1edef41f590dc89a01533">llvm::objcopy::elf::ELFT_ELF32BE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a05b443eeddaf38be35f2de5dcfcc833ba97af7034398dd43cd50d950e2f6592ca">llvm::objcopy::elf::ELFT_ELF32LE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a05b443eeddaf38be35f2de5dcfcc833ba1b23098136b3f9e95520dece615e2fd0">llvm::objcopy::elf::ELFT_ELF64BE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a05b443eeddaf38be35f2de5dcfcc833ba73024a212dc73d97878da45b8a90cd21">llvm::objcopy::elf::ELFT_ELF64LE</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a44946f210492495ee1add2b497ddc31a">llvm::objcopy::CommonConfig::OnlyKeepDebug</a> and <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a98ebc0edb9e5e2332d04b67bc6d93481">llvm::objcopy::CommonConfig::StripSections</a>.</p>


<p>Referenced by <a href="#afb076c75c71a43f683c48aeced9f9f78">createWriter</a>.</p>

</div>
</div>

### createWriter() {#afb076c75c71a43f683c48aeced9f9f78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; Writer &gt; createWriter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig">CommonConfig</a> &amp; Config, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object">Object</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a05b443eeddaf38be35f2de5dcfcc833b">ElfType</a> OutputElfType)</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#ac6aef8715c902e0061de80e3d18dd566a6ce976e8f061b2b5cfe4d0c50c3405dd">llvm::objcopy::Binary</a>, <a href="#af799c939a84893d6b7e282b6771a0dfa">createELFWriter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#ac6aef8715c902e0061de80e3d18dd566a4cf30bded5e7ac442f2c1e0b1c3849f5">llvm::objcopy::IHex</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a8a04952cef062450e2bd671d5e4b3c0c">llvm::objcopy::CommonConfig::OutputFilename</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a74f59cb1b08531e5a80815b1c17048d3">llvm::objcopy::CommonConfig::OutputFormat</a> and <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#ac6aef8715c902e0061de80e3d18dd566a8bd6ee86f68d9b975509566d4a24d26c">llvm::objcopy::SREC</a>.</p>


<p>Referenced by <a href="#ac889c429edbee2b4f43a2292ecb1ceb0">writeOutput</a>.</p>

</div>
</div>

### dumpSectionToFile() {#aa40e91285159d4c13a609b1810b19485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error dumpSectionToFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SecName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> InputFilename, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object">Object</a> &amp; Obj)</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fileoutputbuffer/#a3a10ce8cad8fee5d6a4c55270866aa05">llvm::FileOutputBuffer::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f4ffaa2f15fc8f612a233e3b45510c0">llvm::createFileError</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/main-cpp/#aaa0fa37480ba9aa590065846d7ccb1d2">InputFilename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a19d73e6ba4dbdb613614c9109fa0f1c6">llvm::objcopy::elf::Object::sections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca45212cec20bcd4ca3449dcd8654010ac">llvm::ELF::SHT_NOBITS</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#a1a0331e763d1ccb3e64db8de4d9791c8">handleArgs</a>.</p>

</div>
</div>

### getNewShfFlags() {#aef707b818903d07ba361fda725b70535}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; getNewShfFlags (<a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a0a74dc7cb64459b3271f6e2a9ea7b562">SectionFlag</a> AllFlags, uint16_t EMachine)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daa298f18ed198890cf54b635b54eafee3">llvm::ELF::EM_X86_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a0a74dc7cb64459b3271f6e2a9ea7b562a12597c230a14e9fecb20ea2533b1797e">llvm::objcopy::SecAlloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a0a74dc7cb64459b3271f6e2a9ea7b562a1f15b014c010ed3abad6308840996d32">llvm::objcopy::SecCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a0a74dc7cb64459b3271f6e2a9ea7b562a83814f584ba89794f75bd604189af1f3">llvm::objcopy::SecExclude</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a0a74dc7cb64459b3271f6e2a9ea7b562a7de509e8643e6666052fc44514830e09">llvm::objcopy::SecLarge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a0a74dc7cb64459b3271f6e2a9ea7b562abf13d767e48a05928e2a1e05e4ff9e8f">llvm::objcopy::SecMerge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a0a74dc7cb64459b3271f6e2a9ea7b562a6ec694a128d394b84914de2af082b232">llvm::objcopy::SecReadonly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a0a74dc7cb64459b3271f6e2a9ea7b562aaffbf217bc297d7cef0d49eef3443292">llvm::objcopy::SecStrings</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a4ed5db5129e0b0fe70bf59b691698a72">llvm::ELF::SHF_EXCLUDE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015affae0e6af56cc351c85d9c208e27af02">llvm::ELF::SHF_EXECINSTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a0e54850eb2f8e74ae549f6dd70926723">llvm::ELF::SHF_MERGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a1997ac83cc5cdf3e9ccc1e2de7bb8d45">llvm::ELF::SHF_STRINGS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015ae4bcae1b3b4fa53eba0886cbd799f0a8">llvm::ELF::SHF_WRITE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015ac3670b9f8f377801e941e3d341c51800">llvm::ELF::SHF_X86_64_LARGE</a>.</p>


<p>Referenced by <a href="#af5bc7bb3463aa7528d85207065490482">setSectionFlagsAndType</a>.</p>

</div>
</div>

### getOutputElfType() {#afda0e76ccd38bd614c1eefa534b8d25f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ElfType getOutputElfType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/binary">Binary</a> &amp; Bin)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a372f87e2cac1c83389c98554dc44806da807dbe7d1c25a633894d4a231b1c76d3">llvm::Bin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a05b443eeddaf38be35f2de5dcfcc833ba590309530fe1edef41f590dc89a01533">llvm::objcopy::elf::ELFT_ELF32BE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a05b443eeddaf38be35f2de5dcfcc833ba97af7034398dd43cd50d950e2f6592ca">llvm::objcopy::elf::ELFT_ELF32LE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a05b443eeddaf38be35f2de5dcfcc833ba1b23098136b3f9e95520dece615e2fd0">llvm::objcopy::elf::ELFT_ELF64BE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a05b443eeddaf38be35f2de5dcfcc833ba73024a212dc73d97878da45b8a90cd21">llvm::objcopy::elf::ELFT_ELF64LE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a55af853235c79ddae3c55b4670a825dd">llvm::objcopy::elf::executeObjcopyOnBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a19ff9cfed0ad17d7b4d3cde1c2b940f4">llvm::objcopy::elf::executeObjcopyOnIHex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#ae86d4be0de6470d9b5ac070eaa69c41e">llvm::objcopy::elf::executeObjcopyOnRawBinary</a>.</p>

</div>
</div>

### getOutputElfType() {#ae5c7dbb4f05e4e34f8347a9677b073df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ElfType getOutputElfType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/machineinfo">MachineInfo</a> &amp; MI)</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a05b443eeddaf38be35f2de5dcfcc833ba590309530fe1edef41f590dc89a01533">llvm::objcopy::elf::ELFT_ELF32BE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a05b443eeddaf38be35f2de5dcfcc833ba97af7034398dd43cd50d950e2f6592ca">llvm::objcopy::elf::ELFT_ELF32LE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a05b443eeddaf38be35f2de5dcfcc833ba1b23098136b3f9e95520dece615e2fd0">llvm::objcopy::elf::ELFT_ELF64BE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a05b443eeddaf38be35f2de5dcfcc833ba73024a212dc73d97878da45b8a90cd21">llvm::objcopy::elf::ELFT_ELF64LE</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getSectionFlagsPreserveMask() {#af89c6b030af06ff05dbad7d43da092de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t getSectionFlagsPreserveMask (uint64_t OldFlags, uint64_t NewFlags, uint16_t EMachine)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daa298f18ed198890cf54b635b54eafee3">llvm::ELF::EM_X86_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015abf799091c82aff654ed25824e734ffcc">llvm::ELF::SHF_COMPRESSED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a4ed5db5129e0b0fe70bf59b691698a72">llvm::ELF::SHF_EXCLUDE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015aa4128c7283d8e6e763e8810a91c2dc1e">llvm::ELF::SHF_GROUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a4e2b2b87092f84d740d8e9f34e8b86ee">llvm::ELF::SHF_INFO_LINK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a9284ee71917fdddaa2eeaba1bfe17e2b">llvm::ELF::SHF_LINK_ORDER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015ac242b427eb7ddd8d411c4d3e09f8836d">llvm::ELF::SHF_MASKOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a6a12af03a1299922764e071f05fe9f8c">llvm::ELF::SHF_MASKPROC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015af09f8799cc15fd856ff2284c7519d6d8">llvm::ELF::SHF_TLS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015ac3670b9f8f377801e941e3d341c51800">llvm::ELF::SHF_X86_64_LARGE</a>.</p>


<p>Referenced by <a href="#af5bc7bb3463aa7528d85207065490482">setSectionFlagsAndType</a>.</p>

</div>
</div>

### handleArgs() {#a1a0331e763d1ccb3e64db8de4d9791c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error handleArgs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig">CommonConfig</a> &amp; Config, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/elfconfig">ELFConfig</a> &amp; ELFConfig, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a05b443eeddaf38be35f2de5dcfcc833b">ElfType</a> OutputElfType, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object">Object</a> &amp; Obj)</td>
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



<p>Definition at line 784 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#aa91a92d1d1ad7e8b84c1ecdceb0a439faec211f7c20af43e742bf2570c3cb84f9">llvm::objcopy::Add</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a59b34ccbf34cdf41e82b97304dee7bb0">llvm::objcopy::CommonConfig::AddGnuDebugLink</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#af0b046931b74ef054f7290e9ec6b64d7">llvm::objcopy::elf::Object::addNewSymbolTable</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a935828d3516e07952f9982eedb0af62f">llvm::objcopy::CommonConfig::AddSection</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a7790ee69d77ed5d41ffd6df91e60609f">llvm::objcopy::elf::Object::addSection</a>, <a href="#a485a790f83f65357b91f1e369bc194da">addSymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#ad6e1886828cf9b2142a0077796608c12">llvm::objcopy::CommonConfig::AllocSectionsPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elfconfig/#abf8197d4f0b15c5a86321a8b63066c53">llvm::objcopy::ELFConfig::AllowBrokenLinks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbad861877da56b8b4ceb35c8cbfdf65bb4">llvm::big</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a0367dcf1230be5469dc3bbcb579bdcae">llvm::objcopy::CommonConfig::ChangeSectionAddress</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a12083ef2f7c8fafdac1a98702fb10381">llvm::objcopy::CommonConfig::ChangeSectionLMAValAll</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#afe504aa31a6a354cec13f5b32d0b1d9d">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f4ffaa2f15fc8f612a233e3b45510c0">llvm::createFileError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a42cc07e96293a65eb61cf4ce8a489b41">llvm::objcopy::CommonConfig::DumpSection</a>, <a href="#aa40e91285159d4c13a609b1810b19485">dumpSectionToFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a05b443eeddaf38be35f2de5dcfcc833ba97af7034398dd43cd50d950e2f6592ca">llvm::objcopy::elf::ELFT_ELF32LE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a05b443eeddaf38be35f2de5dcfcc833ba73024a212dc73d97878da45b8a90cd21">llvm::objcopy::elf::ELFT_ELF64LE</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmapimpl/#af513f5818af71e93fabc6e30630ed3f2">llvm::StringMapImpl::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a8cd802dcaed35e1f28ea3cbe4af4eff5">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a16e5eaf2df56249e87019be23ee07695">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#afb190a75aa3b3f2539bdc02250dc4742">llvm::objcopy::elf::Object::Entry</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elfconfig/#aab2c400f6cd08cb4fd6cba123d400f90">llvm::objcopy::ELFConfig::EntryExpr</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a7f420da0701b6102112ca50493d496ad">llvm::objcopy::CommonConfig::ErrorCallback</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aadbc5ef54c920f724d4e267f41d2c00aaba0cdd056685bc8fe4fab01da806afdc">llvm::ELF::ET_REL</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#adfc4c871523575405f07f3dec773f4b0">llvm::objcopy::CommonConfig::ExtractDWO</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a56034ec173ce8feff8568c0e29462094">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a49e68e4c86fe0b96c633adea0c366d74">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a68df71b92d4532e6ceabfb620f5ba02c">llvm::objcopy::elf::SectionBase::Flags</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a6f458988098dd7ac7c11d698fc16678c">llvm::objcopy::CommonConfig::GnuDebugLinkCRC32</a>, <a href="#a4454edff33cc45fad3f75d835f91cb37">handleUserSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a24e1ca7d92cbc2a42152ac37dbc0e7ad">llvm::objcopy::CommonConfig::InputFilename</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20ad5a8a27f4e310ea593b285615faaca35">llvm::object::invalid_file_type</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#aac217cf5f5749becd423b45672cebfc4">llvm::objcopy::elf::Object::Machine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a6ca324c9086862d837e0593199d1e58e">llvm::objcopy::elf::SectionBase::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/sectionflagsupdate/#a3b8163fb73d718cb83859bda5cefa7c4">llvm::objcopy::SectionFlagsUpdate::NewFlags</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/sectionrename/#a4eedcd5a492a00e00330558ba01b1a1f">llvm::objcopy::SectionRename::NewFlags</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/sectionrename/#a1989ac5a2bfcfe79ca20fa02e18c4cbe">llvm::objcopy::SectionRename::NewName</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elfconfig/#a6716734366261c78137eeaccd9447bc6">llvm::objcopy::ELFConfig::NewSymbolVisibility</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elfconfig/#a98f5dfd94d8821c3dd8ec127ab2838a2">llvm::objcopy::ELFConfig::NotesToRemove</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a44946f210492495ee1add2b497ddc31a">llvm::objcopy::CommonConfig::OnlyKeepDebug</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#aee62acd23271e934dbe0b4bdfe5e844f">llvm::objcopy::elf::Object::OSABI</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a2063175d6ed540202f4d478ee54d922c">llvm::objcopy::CommonConfig::OutputArch</a>, <a href="#a06d536441c3553e3bc7639fdfb0fb45c">removeNotes</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a7ffd3f6642f3190ce71003bbe6500203">llvm::objcopy::elf::Object::removeSections</a>, <a href="#a0caf08c068a9900ddcabffcf9f004b41">replaceAndRemoveSections</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a19d73e6ba4dbdb613614c9109fa0f1c6">llvm::objcopy::elf::Object::sections</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a1373eb6c088beb80d2e0ba69be64f932">llvm::objcopy::CommonConfig::SectionsToRename</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a91e54a48df15368d3a524b497b20ab52">llvm::objcopy::elf::Object::segments</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#aa91a92d1d1ad7e8b84c1ecdceb0a439fa5d5b78699e57104f2fa03bbdf7b9197b">llvm::objcopy::Set</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a6266f6dfe157a0896f879b1501f31fe1">llvm::objcopy::CommonConfig::SetSectionAlignment</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a89c18ab7386b44885ab7c4789d0f87f7">llvm::objcopy::CommonConfig::SetSectionFlags</a>, <a href="#af5bc7bb3463aa7528d85207065490482">setSectionFlagsAndType</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#aefab644d04e4c8d4acc01868a464a163">llvm::objcopy::CommonConfig::SetSectionType</a>, <a href="#ae6b496602d8ee433064896a9742c766a">setSectionType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca45212cec20bcd4ca3449dcd8654010ac">llvm::ELF::SHT_NOBITS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcad8d748e7ddd6a4fa31b32710bdd5aae2">llvm::ELF::SHT_NOTE</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#ac9c961426639f44b392bd57eff99ce52">llvm::objcopy::CommonConfig::SplitDWO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#aa91a92d1d1ad7e8b84c1ecdceb0a439fa1d9baf077ee87921f57a8fe42d510b65">llvm::objcopy::Subtract</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a4b6d460ad33362acc77c676999ece9ef">llvm::objcopy::CommonConfig::SymbolsToAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a992d6065f91670a70730547fa168dcc7">llvm::objcopy::elf::Object::SymbolTable</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#acef94957604524790af3fbcb3cebc050">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::try_emplace</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a24faee578f7faaa11989577767b5c560">llvm::objcopy::elf::Object::Type</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a44c3c5507dfeccfdb9f1ba5164fed1fc">llvm::objcopy::elf::SectionBase::Type</a>, <a href="#a4a8b0267a862203c3082ed955abd326c">updateAndRemoveSymbols</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a09e6e864fb7b362b8437042529fdb5be">llvm::objcopy::CommonConfig::UpdateSection</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a64c7e9315762586c7fdea2fbb9d672d8">llvm::objcopy::elf::Object::updateSection</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>, <a href="#a73b370d004cc941240050b8048fefb7e">verifyNoteSection</a> and <a href="/web-llvm/docs/api/structs/llvm/objcopy/elfconfig/#ac9b88e4d61ae592dbbd50bf7cf313e1b">llvm::objcopy::ELFConfig::VerifyNoteSections</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a55af853235c79ddae3c55b4670a825dd">llvm::objcopy::elf::executeObjcopyOnBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a19ff9cfed0ad17d7b4d3cde1c2b940f4">llvm::objcopy::elf::executeObjcopyOnIHex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#ae86d4be0de6470d9b5ac070eaa69c41e">llvm::objcopy::elf::executeObjcopyOnRawBinary</a>.</p>

</div>
</div>

### handleUserSection() {#a4454edff33cc45fad3f75d835f91cb37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error handleUserSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/newsectioninfo">NewSectionInfo</a> &amp; NewSection, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;)&gt; F)</td>
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



<p>Definition at line 721 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/newsectioninfo/#a641257caac84236fba46e30aa91f6c7a">llvm::objcopy::NewSectionInfo::SectionData</a> and <a href="/web-llvm/docs/api/structs/llvm/objcopy/newsectioninfo/#a05c34cfa6560e1e8b1aa9a540d5505e3">llvm::objcopy::NewSectionInfo::SectionName</a>.</p>


<p>Referenced by <a href="#a1a0331e763d1ccb3e64db8de4d9791c8">handleArgs</a>.</p>

</div>
</div>

### isAArch64MappingSymbol() {#ae0d4b42054c461c36914f330dfeb6a2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isAArch64MappingSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol">Symbol</a> &amp; Sym)</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol/#ac643fa5fd6952e2663055299d19b7236">llvm::objcopy::elf::Symbol::Binding</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol/#a9238719393611ce882b8c1c9c1fd31c9">llvm::objcopy::elf::Symbol::getShndx</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol/#a978bae0e123fcdf29e0635a316994ba4">llvm::objcopy::elf::Symbol::Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a742dfa2d775f5b3b041d915133f9356b">llvm::ELF::SHN_UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a492b026d2205f6f178f7eb7863018e31">llvm::ELF::STB_LOCAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a2addd3222711e927ec6604bc65bccb2c">llvm::ELF::STT_NOTYPE</a> and <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol/#a0903db5bb55a91233c61e12933f88031">llvm::objcopy::elf::Symbol::Type</a>.</p>


<p>Referenced by <a href="#a92cd760b5502a4ca65bd18343560e39e">isRequiredByABISymbol</a>.</p>

</div>
</div>

### isArmMappingSymbol() {#a0fba79f4ceb18ec7c14f9a5cc803336d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isArmMappingSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol">Symbol</a> &amp; Sym)</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol/#ac643fa5fd6952e2663055299d19b7236">llvm::objcopy::elf::Symbol::Binding</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol/#a9238719393611ce882b8c1c9c1fd31c9">llvm::objcopy::elf::Symbol::getShndx</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol/#a978bae0e123fcdf29e0635a316994ba4">llvm::objcopy::elf::Symbol::Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a742dfa2d775f5b3b041d915133f9356b">llvm::ELF::SHN_UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a492b026d2205f6f178f7eb7863018e31">llvm::ELF::STB_LOCAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a2addd3222711e927ec6604bc65bccb2c">llvm::ELF::STT_NOTYPE</a> and <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol/#a0903db5bb55a91233c61e12933f88031">llvm::objcopy::elf::Symbol::Type</a>.</p>


<p>Referenced by <a href="#a92cd760b5502a4ca65bd18343560e39e">isRequiredByABISymbol</a>.</p>

</div>
</div>

### isDebugSection() {#aa080c38d82f500daf23c736bba23b17b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isDebugSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase">SectionBase</a> &amp; Sec)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a6ca324c9086862d837e0593199d1e58e">llvm::objcopy::elf::SectionBase::Name</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizerbase/#a2e160e39a23517dff688b6bb5dfa1c06">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizerBase::preserveDebugSections</a>, <a href="#a0caf08c068a9900ddcabffcf9f004b41">replaceAndRemoveSections</a> and <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizer/#a59a5eeccde7b8eef0833cee7b914443b">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::startSynthesis</a>.</p>

</div>
</div>

### isDWOSection() {#a803c3a86a5b67ff8123a45143bbe7586}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isDWOSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase">SectionBase</a> &amp; Sec)</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#aca439bf65258d9d8d057812938b617c5">llvm::StringRef::ends_with</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a6ca324c9086862d837e0593199d1e58e">llvm::objcopy::elf::SectionBase::Name</a>.</p>


<p>Referenced by <a href="#ae35a722a2cd0dda812793c6e52fdd130">onlyKeepDWOPred</a> and <a href="#a0caf08c068a9900ddcabffcf9f004b41">replaceAndRemoveSections</a>.</p>

</div>
</div>

### isRequiredByABISymbol() {#a92cd760b5502a4ca65bd18343560e39e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isRequiredByABISymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object">Object</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol">Symbol</a> &amp; Sym)</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030dace9c7753eed878839a8fb04768d1436c">llvm::ELF::EM_AARCH64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030dae70d9dc0883af67df7d3a1b521031c21">llvm::ELF::EM_ARM</a>, <a href="#ae0d4b42054c461c36914f330dfeb6a2f">isAArch64MappingSymbol</a>, <a href="#a0fba79f4ceb18ec7c14f9a5cc803336d">isArmMappingSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a23fc5f374af95efe6f832eb8d5bb2e6e">llvm::objcopy::elf::Object::isRelocatable</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#aac217cf5f5749becd423b45672cebfc4">llvm::objcopy::elf::Object::Machine</a>.</p>


<p>Referenced by <a href="#a4a8b0267a862203c3082ed955abd326c">updateAndRemoveSymbols</a>.</p>

</div>
</div>

### isUnneededSymbol() {#ad1a626d227da26acd29100b5f2c68172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isUnneededSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol">Symbol</a> &amp; Sym)</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol/#ac643fa5fd6952e2663055299d19b7236">llvm::objcopy::elf::Symbol::Binding</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol/#a9238719393611ce882b8c1c9c1fd31c9">llvm::objcopy::elf::Symbol::getShndx</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol/#ae5097af0fd03e4b7110cb53cfca8860b">llvm::objcopy::elf::Symbol::Referenced</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a742dfa2d775f5b3b041d915133f9356b">llvm::ELF::SHN_UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a492b026d2205f6f178f7eb7863018e31">llvm::ELF::STB_LOCAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a579f54f07d96da2627125a17e0353b14">llvm::ELF::STT_SECTION</a> and <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol/#a0903db5bb55a91233c61e12933f88031">llvm::objcopy::elf::Symbol::Type</a>.</p>


<p>Referenced by <a href="#a4a8b0267a862203c3082ed955abd326c">updateAndRemoveSymbols</a>.</p>

</div>
</div>

### onlyKeepDWOPred() {#ae35a722a2cd0dda812793c6e52fdd130}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool onlyKeepDWOPred (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object">Object</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase">SectionBase</a> &amp; Sec)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="#a803c3a86a5b67ff8123a45143bbe7586">isDWOSection</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a2172b7ef6bf057ac354973c90fa28694">llvm::objcopy::elf::Object::SectionNames</a>.</p>


<p>Referenced by <a href="#a0caf08c068a9900ddcabffcf9f004b41">replaceAndRemoveSections</a>.</p>

</div>
</div>

### removeNotes() {#a06d536441c3553e3bc7639fdfb0fb45c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error removeNotes (<a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object">Object</a> &amp; Obj, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a> Endianness, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/objcopy/removenoteinfo">RemoveNoteInfo</a> &gt; NotesToRemove, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; ErrorCallback)</td>
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



<p>Definition at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjcopy-cpp-/removenotedetail/#a8f3aa0867bb68ba0c5f04860633f6ca9">anonymous{ELFObjcopy.cpp}::RemoveNoteDetail::findNotesToRemove</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546baa55e82356e9721946aa9ba954733c6f0">llvm::not_supported</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4c1b3bf29b3c86c8d11b6708ff244669a8915c7c1855e12fed06c6d15cf2e69c0">llvm::ELF::PT_NOTE</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a19d73e6ba4dbdb613614c9109fa0f1c6">llvm::objcopy::elf::Object::sections</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a91e54a48df15368d3a524b497b20ab52">llvm::objcopy::elf::Object::segments</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcad8d748e7ddd6a4fa31b32710bdd5aae2">llvm::ELF::SHT_NOTE</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a3bf42baf773b375802538951c88d8e12">ToRemove</a> and <a href="/web-llvm/docs/api/structs/anonymous-elfobjcopy-cpp-/removenotedetail/#aed2b24c385053ea197788dfc04744582">anonymous{ELFObjcopy.cpp}::RemoveNoteDetail::updateData</a>.</p>


<p>Referenced by <a href="#a1a0331e763d1ccb3e64db8de4d9791c8">handleArgs</a>.</p>

</div>
</div>

### replaceAndRemoveSections() {#a0caf08c068a9900ddcabffcf9f004b41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error replaceAndRemoveSections (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig">CommonConfig</a> &amp; Config, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/elfconfig">ELFConfig</a> &amp; ELFConfig, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object">Object</a> &amp; Obj)</td>
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



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/objcopy/elfconfig/#abf8197d4f0b15c5a86321a8b63066c53">llvm::objcopy::ELFConfig::AllowBrokenLinks</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#aa740dcfa0d271bee33ae7e65af71662d">llvm::objcopy::elf::Object::compressOrDecompressSections</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/symboltablesection/#a4783a0242422b4ace09e50fbca2d0bd6">llvm::objcopy::elf::SymbolTableSection::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/namematcher/#ae37fd1e51553e31998f280b07d853e77">llvm::objcopy::NameMatcher::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#adfc4c871523575405f07f3dec773f4b0">llvm::objcopy::CommonConfig::ExtractDWO</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a37ba6b32108a2983f4a9f3cd37e13590">llvm::objcopy::CommonConfig::ExtractMainPartition</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#ac0823eb447d0f422742565f0eba40e99">llvm::objcopy::CommonConfig::ExtractPartition</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/symboltablesection/#a122412f2ac2507ed4e3fa9ce22b6628e">llvm::objcopy::elf::SymbolTableSection::getStrTab</a>, <a href="#aa080c38d82f500daf23c736bba23b17b">isDebugSection</a>, <a href="#a803c3a86a5b67ff8123a45143bbe7586">isDWOSection</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elfconfig/#a4c606c61a099a674d7d027ccadd0885d">llvm::objcopy::ELFConfig::KeepFileSymbols</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#abebf9b7925c5e3587702549e836500ff">llvm::objcopy::CommonConfig::KeepSection</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/namematcher/#a8fe6d6e80304c85e35c03066ae1bcfa9">llvm::objcopy::NameMatcher::matches</a>, <a href="#ae35a722a2cd0dda812793c6e52fdd130">onlyKeepDWOPred</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#aba256fcc9763c4d144e805e67f6790f9">llvm::objcopy::CommonConfig::OnlySection</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a7ffd3f6642f3190ce71003bbe6500203">llvm::objcopy::elf::Object::removeSections</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a2172b7ef6bf057ac354973c90fa28694">llvm::objcopy::elf::Object::SectionNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca27bddb44fc2192b6c9ced408d989d0e2">llvm::ELF::SHT_ARM_ATTRIBUTES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca7cb758b706d54d9ed56f6a562052e6f4">llvm::ELF::SHT_LLVM_PART_EHDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcad684b804de723b5f40844f2e63fa0427">llvm::ELF::SHT_LLVM_PART_PHDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca1fc220dae6e53d3aca8d431cd209e74e">llvm::ELF::SHT_REL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcad32bebb3c18c53470e49d5ad192e1158">llvm::ELF::SHT_RELA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca095782f71f1df92eff34130f8a6d15f5">llvm::ELF::SHT_STRTAB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca4f0cd819b71791cb5a1945952dbc9166">llvm::ELF::SHT_SYMTAB</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a9d5713c258905f31b34b13b07086b7c7">llvm::objcopy::CommonConfig::StripAll</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#aef2d23d828ad0d0453f27d4720afeca6">llvm::objcopy::CommonConfig::StripAllGNU</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#abadfb5107f778ad8d81df7893db2c25e">llvm::objcopy::CommonConfig::StripDebug</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a06e658eeea098806e15d04a725b654b6">llvm::objcopy::CommonConfig::StripDWO</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a93ebd2efb0206eb76ed6cbe7ee752dd0">llvm::objcopy::CommonConfig::StripNonAlloc</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a98ebc0edb9e5e2332d04b67bc6d93481">llvm::objcopy::CommonConfig::StripSections</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a978856b980f494b38439e6915ebb08ab">llvm::objcopy::CommonConfig::StripUnneeded</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a55b3b7bbfa7bfc2fbaa04e4aa07e6977">llvm::objcopy::CommonConfig::SymbolsToKeep</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a992d6065f91670a70730547fa168dcc7">llvm::objcopy::elf::Object::SymbolTable</a> and <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#addbcdc27b0e6e19fba3ec20ef5de05d9">llvm::objcopy::CommonConfig::ToRemove</a>.</p>


<p>Referenced by <a href="#a1a0331e763d1ccb3e64db8de4d9791c8">handleArgs</a>.</p>

</div>
</div>

### setSectionFlagsAndType() {#af5bc7bb3463aa7528d85207065490482}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error setSectionFlagsAndType (<a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase">SectionBase</a> &amp; Sec, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a0a74dc7cb64459b3271f6e2a9ea7b562">SectionFlag</a> Flags, uint16_t EMachine)</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a68df71b92d4532e6ceabfb620f5ba02c">llvm::objcopy::elf::SectionBase::Flags</a>, <a href="#aef707b818903d07ba361fda725b70535">getNewShfFlags</a>, <a href="#af89c6b030af06ff05dbad7d43da092de">getSectionFlagsPreserveMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a0a74dc7cb64459b3271f6e2a9ea7b562af40551cf4c0e9fe30b39284e1bf23ac8">llvm::objcopy::SecContents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#a0a74dc7cb64459b3271f6e2a9ea7b562a3ba962ce443370e77abf4d098c833335">llvm::objcopy::SecLoad</a>, <a href="#ae6b496602d8ee433064896a9742c766a">setSectionType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca45212cec20bcd4ca3449dcd8654010ac">llvm::ELF::SHT_NOBITS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca18ae5a64ac74a4265698b956bc797b32">llvm::ELF::SHT_PROGBITS</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a44c3c5507dfeccfdb9f1ba5164fed1fc">llvm::objcopy::elf::SectionBase::Type</a>.</p>


<p>Referenced by <a href="#a1a0331e763d1ccb3e64db8de4d9791c8">handleArgs</a>.</p>

</div>
</div>

### setSectionType() {#ae6b496602d8ee433064896a9742c766a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setSectionType (<a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase">SectionBase</a> &amp; Sec, uint64_t Type)</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a964962447545ebfaaffa4deacfbf3940">llvm::objcopy::elf::SectionBase::Align</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a9ab60ac6df1d07f5866f34453f9efe15">llvm::objcopy::elf::SectionBase::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca45212cec20bcd4ca3449dcd8654010ac">llvm::ELF::SHT_NOBITS</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a44c3c5507dfeccfdb9f1ba5164fed1fc">llvm::objcopy::elf::SectionBase::Type</a>.</p>


<p>Referenced by <a href="#a1a0331e763d1ccb3e64db8de4d9791c8">handleArgs</a> and <a href="#af5bc7bb3463aa7528d85207065490482">setSectionFlagsAndType</a>.</p>

</div>
</div>

### updateAndRemoveSymbols() {#a4a8b0267a862203c3082ed955abd326c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error updateAndRemoveSymbols (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig">CommonConfig</a> &amp; Config, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/elfconfig">ELFConfig</a> &amp; ELFConfig, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object">Object</a> &amp; Obj)</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#ad8575ac23541d1433a8e492cc876f75aab1c94ca2fbc3e78fc30069c8d0f01680">llvm::objcopy::All</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol/#ac643fa5fd6952e2663055299d19b7236">llvm::objcopy::elf::Symbol::Binding</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#ac6efd384d0ad969083034e1205ec5166">llvm::objcopy::CommonConfig::DiscardMode</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/namematcher/#ae37fd1e51553e31998f280b07d853e77">llvm::objcopy::NameMatcher::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol/#a9238719393611ce882b8c1c9c1fd31c9">llvm::objcopy::elf::Symbol::getShndx</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol/#a1e6b658617411be291c07848e083a7a0">llvm::objcopy::elf::Symbol::isCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a23fc5f374af95efe6f832eb8d5bb2e6e">llvm::objcopy::elf::Object::isRelocatable</a>, <a href="#a92cd760b5502a4ca65bd18343560e39e">isRequiredByABISymbol</a>, <a href="#ad1a626d227da26acd29100b5f2c68172">isUnneededSymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elfconfig/#a4c606c61a099a674d7d027ccadd0885d">llvm::objcopy::ELFConfig::KeepFileSymbols</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elfconfig/#a3dcf4a25ad7a66ddb75cc98adfbb07d9">llvm::objcopy::ELFConfig::LocalizeHidden</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#ad8575ac23541d1433a8e492cc876f75aa4779ca01c794c33a58436d7e60869829">llvm::objcopy::Locals</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/namematcher/#a8fe6d6e80304c85e35c03066ae1bcfa9">llvm::objcopy::NameMatcher::matches</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol/#a978bae0e123fcdf29e0635a316994ba4">llvm::objcopy::elf::Symbol::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#aba256fcc9763c4d144e805e67f6790f9">llvm::objcopy::CommonConfig::OnlySection</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol/#ae5097af0fd03e4b7110cb53cfca8860b">llvm::objcopy::elf::Symbol::Referenced</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a6f5260724ddb92daec8287a2365ba36f">llvm::objcopy::elf::Object::removeSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a19d73e6ba4dbdb613614c9109fa0f1c6">llvm::objcopy::elf::Object::sections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a742dfa2d775f5b3b041d915133f9356b">llvm::ELF::SHN_UNDEF</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a3056225276d5d76c1b142d3505704851">llvm::ELF::STB_GLOBAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a492b026d2205f6f178f7eb7863018e31">llvm::ELF::STB_LOCAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77afb3fa0269fc31b10834def07f16c1649">llvm::ELF::STB_WEAK</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a9d5713c258905f31b34b13b07086b7c7">llvm::objcopy::CommonConfig::StripAll</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#aef2d23d828ad0d0453f27d4720afeca6">llvm::objcopy::CommonConfig::StripAllGNU</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#abadfb5107f778ad8d81df7893db2c25e">llvm::objcopy::CommonConfig::StripDebug</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a978856b980f494b38439e6915ebb08ab">llvm::objcopy::CommonConfig::StripUnneeded</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a58921cad23ba8bdf0c8077b7a2923127">llvm::ELF::STT_FILE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a579f54f07d96da2627125a17e0353b14">llvm::ELF::STT_SECTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a78278359d67657d43c307d922ad9a1d5ab38517de2fd6c124c49e40bc25c25c0c">llvm::ELF::STV_HIDDEN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a78278359d67657d43c307d922ad9a1d5a443262fcc164a05e17cef6868ab529d3">llvm::ELF::STV_INTERNAL</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a5f8443d2d5a7029f14b4dd1e957751f6">llvm::objcopy::CommonConfig::SymbolsPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#aa88273e28678734e1d89b294c79f73cc">llvm::objcopy::CommonConfig::SymbolsPrefixRemove</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a0f2cbaa3e8f07c0749e1e32954284d2d">llvm::objcopy::CommonConfig::SymbolsToGlobalize</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a55b3b7bbfa7bfc2fbaa04e4aa07e6977">llvm::objcopy::CommonConfig::SymbolsToKeep</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a7a26aeb2b5098af0e7f95731f5c2f8ff">llvm::objcopy::CommonConfig::SymbolsToKeepGlobal</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#aeb767ad630fb4a422c50005a552cd285">llvm::objcopy::CommonConfig::SymbolsToLocalize</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a1d8345e6518fe133dd67d094a69bb8c6">llvm::objcopy::CommonConfig::SymbolsToRemove</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#ae7d2b6748551fda8ea5d3757f96f7d0b">llvm::objcopy::CommonConfig::SymbolsToRename</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elfconfig/#a4b1a820ec7ebbbdc3722e9589503656f">llvm::objcopy::ELFConfig::SymbolsToSetVisibility</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a9234cc1ade22c8ccdf67ced0c6391c7f">llvm::objcopy::CommonConfig::SymbolsToSkip</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a6381920481481c711ef0d61bad60d60e">llvm::objcopy::CommonConfig::SymbolsToWeaken</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a992d6065f91670a70730547fa168dcc7">llvm::objcopy::elf::Object::SymbolTable</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol/#a0903db5bb55a91233c61e12933f88031">llvm::objcopy::elf::Symbol::Type</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a97da34bb10ec4abee4cf43b4271da29a">llvm::objcopy::CommonConfig::UnneededSymbolsToRemove</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/symboltablesection/#a52a920e0691d794d27d330171e270553">llvm::objcopy::elf::SymbolTableSection::updateSymbols</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/symbol/#aa0f420a6d7bf0d8c42a3290564dd6f83">llvm::objcopy::elf::Symbol::Visibility</a> and <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a7cad72eb42330ce3a12c516038b0ff00">llvm::objcopy::CommonConfig::Weaken</a>.</p>


<p>Referenced by <a href="#a1a0331e763d1ccb3e64db8de4d9791c8">handleArgs</a>.</p>

</div>
</div>

### verifyNoteSection() {#a73b370d004cc941240050b8048fefb7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error verifyNoteSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a> Endianness, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data)</td>
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



<p>Definition at line 729 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a9a03aac7419558e56bd606aeab244118">llvm::XCOFF::NameSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a1fda585fbf18128d11d28fa4c5b0ad7d">llvm::support::endian::read32</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a1a0331e763d1ccb3e64db8de4d9791c8">handleArgs</a>.</p>

</div>
</div>

### writeOutput() {#ac889c429edbee2b4f43a2292ecb1ceb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error writeOutput (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig">CommonConfig</a> &amp; Config, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object">Object</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a05b443eeddaf38be35f2de5dcfcc833b">ElfType</a> OutputElfType)</td>
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



<p>Definition at line 1038 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp">ELFObjcopy.cpp</a>.</p>


<p>References <a href="#afb076c75c71a43f683c48aeced9f9f78">createWriter</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/writer/#a6ce9ed786d6d6e992ca993389d338b74">llvm::objcopy::elf::Writer::finalize</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/writer/#a726d996516b35a7aaa997a8b010d8b00">llvm::objcopy::elf::Writer::write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a55af853235c79ddae3c55b4670a825dd">llvm::objcopy::elf::executeObjcopyOnBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a19ff9cfed0ad17d7b4d3cde1c2b940f4">llvm::objcopy::elf::executeObjcopyOnIHex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#ae86d4be0de6470d9b5ac070eaa69c41e">llvm::objcopy::elf::executeObjcopyOnRawBinary</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
