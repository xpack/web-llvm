---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MachOWriter.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-h">MachOWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/macholayoutbuilder-h">MachOLayoutBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">llvm/BinaryFormat/MachO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errc-h">llvm/Support/Errc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sha256-h">llvm/Support/SHA256.h</a>"
#include &lt;memory&gt;
#include "llvm/BinaryFormat/MachO.def"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NListType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afb198633cab14d4e8eb44bbcbfae5cde">writeNListEntry</a> (const SymbolEntry &amp;SE, bool IsLittleEndian, char *&amp;Out, uint32_t Nstrx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48b4534ab5a04eae69e7a554c7b59bb5">getSegmentFileOffset</a> (const LoadCommand &amp;TextSegmentLoadCommand)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab07c1c0ec0499cf22858e16d3b3859b1">getSegmentFileSize</a> (const LoadCommand &amp;TextSegmentLoadCommand)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dab6874da96415aa59776844fcc8574">HANDLE_LOAD_COMMAND</a>(LCName, LCValue, LCStruct)&nbsp;&nbsp;&nbsp;...</td>
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

### getSegmentFileOffset() {#a48b4534ab5a04eae69e7a554c7b59bb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t getSegmentFileOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand">LoadCommand</a> &amp; TextSegmentLoadCommand)</td>
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



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand/#a521ae30565359d9c67ad94fed18ce660">llvm::objcopy::macho::LoadCommand::MachOLoadCommand</a>.</p>

</div>
</div>

### getSegmentFileSize() {#ab07c1c0ec0499cf22858e16d3b3859b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t getSegmentFileSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand">LoadCommand</a> &amp; TextSegmentLoadCommand)</td>
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



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand/#a521ae30565359d9c67ad94fed18ce660">llvm::objcopy::macho::LoadCommand::MachOLoadCommand</a>.</p>

</div>
</div>

### writeNListEntry() {#afb198633cab14d4e8eb44bbcbfae5cde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NListType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeNListEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/symbolentry">SymbolEntry</a> &amp; SE, bool IsLittleEndian, char *&amp; Out, uint32_t Nstrx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a4ee2015697caec796e59972aadc2f9e2">llvm::sys::IsLittleEndianHost</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/symbolentry/#ad93a3bb12765133a3ec10e11d7916657">llvm::objcopy::macho::SymbolEntry::n_desc</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/symbolentry/#a74f5e6f40870c2d8f759bfaa9893e134">llvm::objcopy::macho::SymbolEntry::n_sect</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/symbolentry/#a05de774a480bbfc1c398d279bbc85965">llvm::objcopy::macho::SymbolEntry::n_type</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/symbolentry/#aa91e6d5d585bde132f3a3af577b6d3a5">llvm::objcopy::macho::SymbolEntry::n_value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a754466f4b36d6a2365e56663e0d9de83">llvm::MachO::swapStruct</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### HANDLE\_LOAD\_COMMAND {#a2dab6874da96415aa59776844fcc8574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_LOAD_COMMAND(LCName, LCValue, LCStruct)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case MachO::LCName:                                                          \
    <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>(sizeof(MachO::LCStruct) + <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">LC.Payload.size</a>() ==                      \
           MLC.load_command_data.cmdsize);                                     \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (IsLittleEndian != sys::IsLittleEndianHost)                             \
      MachO::swapStruct(MLC.LCStruct##_data);                                  \
    memcpy(Begin, &amp;MLC.LCStruct##_data, sizeof(MachO::LCStruct));              \
    Begin += sizeof(MachO::LCStruct);                                          \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (!LC.Payload.empty())                                                   \
      memcpy(Begin, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">LC.Payload.data</a>(), <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">LC.Payload.size</a>());                     \
    Begin += <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">LC.Payload.size</a>();                                                \
    break;
</div>
</dd>
</dl>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machowriter-cpp">MachOWriter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
