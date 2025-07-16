---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MachOObjcopy.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/include/llvm/objcopy/macho/machoobjcopy-h">llvm/ObjCopy/MachO/MachOObjcopy.h</a>"
#include "Archive.h"
#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-h">MachOReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/denseset-h">llvm/ADT/DenseSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/commonconfig-h">llvm/ObjCopy/CommonConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/include/llvm/objcopy/macho/machoconfig-h">llvm/ObjCopy/MachO/MachOConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/multiformatconfig-h">llvm/ObjCopy/MultiFormatConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objcopy/objcopy-h">llvm/ObjCopy/ObjCopy.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archivewriter-h">llvm/Object/ArchiveWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">llvm/Object/MachOUniversal.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversalwriter-h">llvm/Object/MachOUniversalWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errc-h">llvm/Support/Errc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileoutputbuffer-h">llvm/Support/FileOutputBuffer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smallvectormemorybuffer-h">llvm/Support/SmallVectorMemoryBuffer.h</a>"
</div>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a149edc9fb81a1275062af3c72b7d0e94">SectionPred</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">std::function</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section">Section</a> &gt; &amp;Sec)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9acdfbcce7bf8b9cb5ac43e036141d08">LoadCommandPred</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">std::function</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand">LoadCommand</a> &amp;LC)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49343f777e053584c42f916b5e567142">isLoadCommandWithPayloadString</a> (const LoadCommand &amp;LC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3326a9bb0843a456b29982ae9be935d">getPayloadString</a> (const LoadCommand &amp;LC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a918836be9d98b9555fa33b3153155511">removeSections</a> (const CommonConfig &amp;Config, Object &amp;Obj)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a506d6e3bcda2cef91232c70016b03355">markSymbols</a> (const CommonConfig &amp;, Object &amp;Obj)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af77b232892df5c7e1321f2885b0c49ef">updateAndRemoveSymbols</a> (const CommonConfig &amp;Config, const MachOConfig &amp;MachOConfig, Object &amp;Obj)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LCType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a36314b2982eff94abe0b78ad9c97f53f">updateLoadCommandPayloadString</a> (LoadCommand &amp;LC, StringRef S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand">LoadCommand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4002ef7d78e41ceeaa9ca3e21222e725">buildRPathLoadCommand</a> (StringRef Path)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14dfead54615906a608b43ce6881920b">processLoadCommands</a> (const MachOConfig &amp;MachOConfig, Object &amp;Obj)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6138676e4615546fc1c7d559029916a">addSection</a> (const NewSectionInfo &amp;NewSection, Object &amp;Obj)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section">Section</a> &amp; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19fc4c64b801bb8ba465fdede95e7ca3">findSection</a> (StringRef SecName, Object &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcfed892d87764504587749693efe357">updateSection</a> (const NewSectionInfo &amp;NewSection, Object &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d2a5be3f3c66e1c7670d490725af1d8">isValidMachOCannonicalName</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fdf1b59602b3fa2d23286e468abb8a9">handleArgs</a> (const CommonConfig &amp;Config, const MachOConfig &amp;MachOConfig, Object &amp;Obj)</td>
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

### LoadCommandPred {#a9acdfbcce7bf8b9cb5ac43e036141d08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LoadCommandPred =  std::function&lt;bool(const LoadCommand &amp;LC)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp">MachOObjcopy.cpp</a>.</p>

</div>
</div>

### SectionPred {#a149edc9fb81a1275062af3c72b7d0e94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using SectionPred =  std::function&lt;bool(const std::unique_ptr&lt;Section&gt; &amp;Sec)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp">MachOObjcopy.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### addSection() {#aa6138676e4615546fc1c7d559029916a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error addSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/newsectioninfo">NewSectionInfo</a> &amp; NewSection, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object">Object</a> &amp; Obj)</td>
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



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp">MachOObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object/#aede39cad347831c61affdf79666a37db">llvm::objcopy::macho::Object::addSegment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section/#a6560167012e320de6291d4d2897cb26c">llvm::objcopy::macho::Section::Content</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand/#a9f8d500e5dff1d5da2c3acb1cdf633e9">llvm::objcopy::macho::LoadCommand::getSegmentName</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand/#aba583cbf3f31bbb8851463e449bf5cd5">llvm::objcopy::macho::LoadCommand::getSegmentVMAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object/#a7056fc4479dd0274dea7baabfaea80bb">llvm::objcopy::macho::Object::LoadCommands</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object/#a16bee11bc1500081f5af7293e515a6f8">llvm::objcopy::macho::Object::NewSectionsContents</a>, <a href="/web-llvm/docs/api/classes/llvm/stringsaver/#ada08f15f76fa550da28d92b038b6644b">llvm::StringSaver::save</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/newsectioninfo/#a641257caac84236fba46e30aa91f6c7a">llvm::objcopy::NewSectionInfo::SectionData</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/newsectioninfo/#a05c34cfa6560e1e8b1aa9a540d5505e3">llvm::objcopy::NewSectionInfo::SectionName</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand/#aa9d03f7cb5acb5efb6c8aaa9fa5df989">llvm::objcopy::macho::LoadCommand::Sections</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section/#af8518cb8fda5065b350c17c993b2f187">llvm::objcopy::macho::Section::Size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a8fdf1b59602b3fa2d23286e468abb8a9">handleArgs</a>.</p>

</div>
</div>

### buildRPathLoadCommand() {#a4002ef7d78e41ceeaa9ca3e21222e725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoadCommand buildRPathLoadCommand (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path)</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp">MachOObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/rpath-command/#acce18417e443d6bc1c36cf3340c8dfe8">llvm::MachO::rpath_command::cmd</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/rpath-command/#a5d19f90388f4d2a771c2374b91ce3b7f">llvm::MachO::rpath_command::cmdsize</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand/#a521ae30565359d9c67ad94fed18ce660">llvm::objcopy::macho::LoadCommand::MachOLoadCommand</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/rpath-command/#a15e13b0a7dd3c76275917a090e4cbfff">llvm::MachO::rpath_command::path</a> and <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand/#ae25df5c778a8f3a989d3f384ca9fc116">llvm::objcopy::macho::LoadCommand::Payload</a>.</p>


<p>Referenced by <a href="#a14dfead54615906a608b43ce6881920b">processLoadCommands</a>.</p>

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
<td class="doxyMemberName">Error dumpSectionToFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SecName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> InputFilename, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object">Object</a> &amp; Obj)</td>
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



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp">MachOObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abb650e853db0ddbb60411b885c499737">llvm::copy</a>, <a href="/web-llvm/docs/api/classes/llvm/fileoutputbuffer/#a3a10ce8cad8fee5d6a4c55270866aa05">llvm::FileOutputBuffer::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f4ffaa2f15fc8f612a233e3b45510c0">llvm::createFileError</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/main-cpp/#aaa0fa37480ba9aa590065846d7ccb1d2">InputFilename</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object/#a7056fc4479dd0274dea7baabfaea80bb">llvm::objcopy::macho::Object::LoadCommands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand/#aa9d03f7cb5acb5efb6c8aaa9fa5df989">llvm::objcopy::macho::LoadCommand::Sections</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#a8fdf1b59602b3fa2d23286e468abb8a9">handleArgs</a>.</p>

</div>
</div>

### findSection() {#a19fc4c64b801bb8ba465fdede95e7ca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; Section &amp; &gt; findSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SecName, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object">Object</a> &amp; O)</td>
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



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp">MachOObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>.</p>


<p>Referenced by <a href="#afcfed892d87764504587749693efe357">updateSection</a>.</p>

</div>
</div>

### getPayloadString() {#ae3326a9bb0843a456b29982ae9be935d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getPayloadString (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand">LoadCommand</a> &amp; LC)</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp">MachOObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a49343f777e053584c42f916b5e567142">isLoadCommandWithPayloadString</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand/#ae25df5c778a8f3a989d3f384ca9fc116">llvm::objcopy::macho::LoadCommand::Payload</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a9b52404a8d2877d3b32ebb5d1f5c72ff">llvm::StringRef::rtrim</a>.</p>


<p>Referenced by <a href="#a14dfead54615906a608b43ce6881920b">processLoadCommands</a>.</p>

</div>
</div>

### handleArgs() {#a8fdf1b59602b3fa2d23286e468abb8a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error handleArgs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig">CommonConfig</a> &amp; Config, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/machoconfig">MachOConfig</a> &amp; MachOConfig, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object">Object</a> &amp; Obj)</td>
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



<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp">MachOObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a935828d3516e07952f9982eedb0af62f">llvm::objcopy::CommonConfig::AddSection</a>, <a href="#aa6138676e4615546fc1c7d559029916a">addSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f4ffaa2f15fc8f612a233e3b45510c0">llvm::createFileError</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a42cc07e96293a65eb61cf4ce8a489b41">llvm::objcopy::CommonConfig::DumpSection</a>, <a href="#aa40e91285159d4c13a609b1810b19485">dumpSectionToFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a24e1ca7d92cbc2a42152ac37dbc0e7ad">llvm::objcopy::CommonConfig::InputFilename</a>, <a href="#a1d2a5be3f3c66e1c7670d490725af1d8">isValidMachOCannonicalName</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object/#a7056fc4479dd0274dea7baabfaea80bb">llvm::objcopy::macho::Object::LoadCommands</a>, <a href="#a506d6e3bcda2cef91232c70016b03355">markSymbols</a>, <a href="#a14dfead54615906a608b43ce6881920b">processLoadCommands</a>, <a href="#a918836be9d98b9555fa33b3153155511">removeSections</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/newsectioninfo/#a05c34cfa6560e1e8b1aa9a540d5505e3">llvm::objcopy::NewSectionInfo::SectionName</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand/#aa9d03f7cb5acb5efb6c8aaa9fa5df989">llvm::objcopy::macho::LoadCommand::Sections</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a9d5713c258905f31b34b13b07086b7c7">llvm::objcopy::CommonConfig::StripAll</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#af77b232892df5c7e1321f2885b0c49ef">updateAndRemoveSymbols</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a09e6e864fb7b362b8437042529fdb5be">llvm::objcopy::CommonConfig::UpdateSection</a> and <a href="#afcfed892d87764504587749693efe357">updateSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/macho/#ad23f6403620ffb61f8c0e1f006f6ea66">llvm::objcopy::macho::executeObjcopyOnBinary</a>.</p>

</div>
</div>

### isLoadCommandWithPayloadString() {#a49343f777e053584c42f916b5e567142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isLoadCommandWithPayloadString (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand">LoadCommand</a> &amp; LC)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp">MachOObjcopy.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand/#a521ae30565359d9c67ad94fed18ce660">llvm::objcopy::macho::LoadCommand::MachOLoadCommand</a>.</p>


<p>Referenced by <a href="#ae3326a9bb0843a456b29982ae9be935d">getPayloadString</a> and <a href="#a36314b2982eff94abe0b78ad9c97f53f">updateLoadCommandPayloadString</a>.</p>

</div>
</div>

### isValidMachOCannonicalName() {#a1d2a5be3f3c66e1c7670d490725af1d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error isValidMachOCannonicalName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp">MachOObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a8fdf1b59602b3fa2d23286e468abb8a9">handleArgs</a>.</p>

</div>
</div>

### markSymbols() {#a506d6e3bcda2cef91232c70016b03355}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void markSymbols (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig">CommonConfig</a> &amp;, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object">Object</a> &amp; Obj)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp">MachOObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object/#ae196d6fcc377004d38c6a1a70f4f8146">llvm::objcopy::macho::Object::IndirectSymTable</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/indirectsymbolentry/#a245bdcc73e0fa8718af5c9ffeeabf765">llvm::objcopy::macho::IndirectSymbolEntry::Symbol</a> and <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/indirectsymboltable/#aa75fd45f620f74df78d9ed001171048f">llvm::objcopy::macho::IndirectSymbolTable::Symbols</a>.</p>


<p>Referenced by <a href="#a8fdf1b59602b3fa2d23286e468abb8a9">handleArgs</a>.</p>

</div>
</div>

### processLoadCommands() {#a14dfead54615906a608b43ce6881920b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error processLoadCommands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/machoconfig">MachOConfig</a> &amp; MachOConfig, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object">Object</a> &amp; Obj)</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp">MachOObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad7dc7318244359268414719e0959346e">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::begin</a>, <a href="#a4002ef7d78e41ceeaa9ca3e21222e725">buildRPathLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#afe504aa31a6a354cec13f5b32d0b1d9d">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a9a3c9d867ff6bde97841c2b7983f5c70">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/machoconfig/#a8fa1caf761d4acd4745c4eb38040cfda">llvm::objcopy::MachOConfig::EmptySegmentsToRemove</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a8cd802dcaed35e1f28ea3cbe4af4eff5">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#af972d87e15b5f6ed61bd5c3956c5213d">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::erase</a>, <a href="#ae3326a9bb0843a456b29982ae9be935d">getPayloadString</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand/#a9f8d500e5dff1d5da2c3acb1cdf633e9">llvm::objcopy::macho::LoadCommand::getSegmentName</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/machoconfig/#a43a835e9dea583015d151fb5bbe8aa2c">llvm::objcopy::MachOConfig::InstallNamesToUpdate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object/#a7056fc4479dd0274dea7baabfaea80bb">llvm::objcopy::macho::Object::LoadCommands</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand/#a521ae30565359d9c67ad94fed18ce660">llvm::objcopy::macho::LoadCommand::MachOLoadCommand</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/machoconfig/#ab25866653b367bec23cf05ef587b4051">llvm::objcopy::MachOConfig::RemoveAllRpaths</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object/#a29234a4bcb1dca0dabae964f8eacb264">llvm::objcopy::macho::Object::removeLoadCommands</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/machoconfig/#a916f81c0e991f3f0dea3717cae887764">llvm::objcopy::MachOConfig::RPathsToRemove</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/machoconfig/#ad9f5e6ffb240fdcc1cdfa1aac327fd4b">llvm::objcopy::MachOConfig::RPathsToUpdate</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/machoconfig/#aeaabcf623530c6964340a7fbf1429711">llvm::objcopy::MachOConfig::RPathToAdd</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/machoconfig/#a40a1fde31114835514985bff83320863">llvm::objcopy::MachOConfig::RPathToPrepend</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand/#aa9d03f7cb5acb5efb6c8aaa9fa5df989">llvm::objcopy::macho::LoadCommand::Sections</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/machoconfig/#a8e23bb7046c989748f162eab83122d93">llvm::objcopy::MachOConfig::SharedLibId</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object/#a113f3affc038124b490bb878a5a05b04">llvm::objcopy::macho::Object::updateLoadCommandIndexes</a> and <a href="#a36314b2982eff94abe0b78ad9c97f53f">updateLoadCommandPayloadString</a>.</p>


<p>Referenced by <a href="#a8fdf1b59602b3fa2d23286e468abb8a9">handleArgs</a>.</p>

</div>
</div>

### removeSections() {#a918836be9d98b9555fa33b3153155511}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error removeSections (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig">CommonConfig</a> &amp; Config, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object">Object</a> &amp; Obj)</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp">MachOObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/objcopy/namematcher/#ae37fd1e51553e31998f280b07d853e77">llvm::objcopy::NameMatcher::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/namematcher/#a8fe6d6e80304c85e35c03066ae1bcfa9">llvm::objcopy::NameMatcher::matches</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#aba256fcc9763c4d144e805e67f6790f9">llvm::objcopy::CommonConfig::OnlySection</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object/#a47fbc494119ba51bed1e722d310bba1e">llvm::objcopy::macho::Object::removeSections</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a9d5713c258905f31b34b13b07086b7c7">llvm::objcopy::CommonConfig::StripAll</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#abadfb5107f778ad8d81df7893db2c25e">llvm::objcopy::CommonConfig::StripDebug</a> and <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#addbcdc27b0e6e19fba3ec20ef5de05d9">llvm::objcopy::CommonConfig::ToRemove</a>.</p>


<p>Referenced by <a href="#a8fdf1b59602b3fa2d23286e468abb8a9">handleArgs</a>.</p>

</div>
</div>

### updateAndRemoveSymbols() {#af77b232892df5c7e1321f2885b0c49ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void updateAndRemoveSymbols (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig">CommonConfig</a> &amp; Config, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/machoconfig">MachOConfig</a> &amp; MachOConfig, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object">Object</a> &amp; Obj)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp">MachOObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#ad8575ac23541d1433a8e492cc876f75aab1c94ca2fbc3e78fc30069c8d0f01680">llvm::objcopy::All</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#ac6efd384d0ad969083034e1205ec5166">llvm::objcopy::CommonConfig::DiscardMode</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/namematcher/#ae37fd1e51553e31998f280b07d853e77">llvm::objcopy::NameMatcher::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/machheader/#ac51ba4499832320329016831ef5910e4">llvm::objcopy::macho::MachHeader::Flags</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object/#ad496d543def51ce6b51763279ddd7584">llvm::objcopy::macho::Object::Header</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/symbolentry/#a0c9d81f91808f0ffb9f2bd3e9af630c1">llvm::objcopy::macho::SymbolEntry::isExternalSymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/symbolentry/#a3a63a1935a2580819745fcbbfbe5aab4">llvm::objcopy::macho::SymbolEntry::isUndefinedSymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/machoconfig/#af941dc09de3a437e11895a41b8de23f5">llvm::objcopy::MachOConfig::KeepUndefined</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/namematcher/#a8fe6d6e80304c85e35c03066ae1bcfa9">llvm::objcopy::NameMatcher::matches</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a56796c840e08337bb5693b43bf17360ca0716fd35b77fa761c2bfd30224c1c687">llvm::MachO::MH_DYLDLINK</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/symbolentry/#ad93a3bb12765133a3ec10e11d7916657">llvm::objcopy::macho::SymbolEntry::n_desc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad152fa3b2aff735d4a2e4b644dc93b11a8bc1bbfcee7206480576072973724a1a">llvm::MachO::N_EXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad152fa3b2aff735d4a2e4b644dc93b11afa536dc3de031dfd52aaa5c24691b947">llvm::MachO::N_STAB</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/symbolentry/#a05de774a480bbfc1c398d279bbc85965">llvm::objcopy::macho::SymbolEntry::n_type</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a8566ffd52ce0223e6ecc4298a438a721a28ba3855aefcfc5bf5bdf4e9f75562a4">llvm::MachO::N_WEAK_DEF</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/symbolentry/#a614b7cc8bdf811b60786c0dba3214906">llvm::objcopy::macho::SymbolEntry::Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a8566ffd52ce0223e6ecc4298a438a721a30911644caa01a2fcdc733f62bbbb80b">llvm::MachO::REFERENCED_DYNAMICALLY</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/symboltable/#a93dd1b9a6cbe03781efa0a11ea3bd236">llvm::objcopy::macho::SymbolTable::removeSymbols</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a9d5713c258905f31b34b13b07086b7c7">llvm::objcopy::CommonConfig::StripAll</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#abadfb5107f778ad8d81df7893db2c25e">llvm::objcopy::CommonConfig::StripDebug</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/machoconfig/#adc7cdb19bae50c7c3ed42b1a2e34525c">llvm::objcopy::MachOConfig::StripSwiftSymbols</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object/#a83bd3e89b50db37fd5e21b7591f5ac31">llvm::objcopy::macho::Object::SwiftVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a0f2cbaa3e8f07c0749e1e32954284d2d">llvm::objcopy::CommonConfig::SymbolsToGlobalize</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a7a26aeb2b5098af0e7f95731f5c2f8ff">llvm::objcopy::CommonConfig::SymbolsToKeepGlobal</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#aeb767ad630fb4a422c50005a552cd285">llvm::objcopy::CommonConfig::SymbolsToLocalize</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#ae7d2b6748551fda8ea5d3757f96f7d0b">llvm::objcopy::CommonConfig::SymbolsToRename</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a9234cc1ade22c8ccdf67ced0c6391c7f">llvm::objcopy::CommonConfig::SymbolsToSkip</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a6381920481481c711ef0d61bad60d60e">llvm::objcopy::CommonConfig::SymbolsToWeaken</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object/#a653496a554313e67608e0d8f90f39c40">llvm::objcopy::macho::Object::SymTable</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/symboltable/#a20afc4f554451875cd5c6502a482586a">llvm::objcopy::macho::SymbolTable::updateSymbols</a> and <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a7cad72eb42330ce3a12c516038b0ff00">llvm::objcopy::CommonConfig::Weaken</a>.</p>


<p>Referenced by <a href="#a8fdf1b59602b3fa2d23286e468abb8a9">handleArgs</a>.</p>

</div>
</div>

### updateLoadCommandPayloadString() {#a36314b2982eff94abe0b78ad9c97f53f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LCType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void updateLoadCommandPayloadString (<a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand">LoadCommand</a> &amp; LC, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp">MachOObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a>, <a href="#a49343f777e053584c42f916b5e567142">isLoadCommandWithPayloadString</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand/#a521ae30565359d9c67ad94fed18ce660">llvm::objcopy::macho::LoadCommand::MachOLoadCommand</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand/#ae25df5c778a8f3a989d3f384ca9fc116">llvm::objcopy::macho::LoadCommand::Payload</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="#a14dfead54615906a608b43ce6881920b">processLoadCommands</a>.</p>

</div>
</div>

### updateSection() {#afcfed892d87764504587749693efe357}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error updateSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/newsectioninfo">NewSectionInfo</a> &amp; NewSection, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object">Object</a> &amp; O)</td>
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



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp">MachOObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section/#a6560167012e320de6291d4d2897cb26c">llvm::objcopy::macho::Section::Content</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#a19fc4c64b801bb8ba465fdede95e7ca3">findSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/newsectioninfo/#a641257caac84236fba46e30aa91f6c7a">llvm::objcopy::NewSectionInfo::SectionData</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/newsectioninfo/#a05c34cfa6560e1e8b1aa9a540d5505e3">llvm::objcopy::NewSectionInfo::SectionName</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section/#af8518cb8fda5065b350c17c993b2f187">llvm::objcopy::macho::Section::Size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#a8fdf1b59602b3fa2d23286e468abb8a9">handleArgs</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
