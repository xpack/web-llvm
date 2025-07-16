---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MachOObject.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "llvm/Support/SystemZ/zOSSupport.h"
#include &lt;unordered_set&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SegmentType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9d36087a89aca95c0df3141528c1dc2a">constructSegment</a> (SegmentType &amp;Seg, llvm::MachO::LoadCommandType CmdType, StringRef SegName, uint64_t SegVMAddr, uint64_t SegVMSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac592550b6c41fd8e701dee5932087027">extractSegmentName</a> (const char *SegName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extracts a segment name from a string which is possibly non-null-terminated. <a href="#ac592550b6c41fd8e701dee5932087027">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### constructSegment() {#a9d36087a89aca95c0df3141528c1dc2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SegmentType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void constructSegment (SegmentType &amp; Seg, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad8cb90f953b327ab043258a76922cde1">llvm::MachO::LoadCommandType</a> CmdType, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SegName, uint64_t SegVMAddr, uint64_t SegVMSize)</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-cpp">MachOObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a113815f0ead74239386436bbebdbd783a459028b54c6de464c939b7a148dee815">llvm::MachO::VM_PROT_EXECUTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a113815f0ead74239386436bbebdbd783a9dccfb77c950352acfcae05d2002d5d4">llvm::MachO::VM_PROT_READ</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a113815f0ead74239386436bbebdbd783acca2a1b89bc84f63aa45c62455c7fcae">llvm::MachO::VM_PROT_WRITE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object/#aede39cad347831c61affdf79666a37db">llvm::objcopy::macho::Object::addSegment</a>.</p>

</div>
</div>

### extractSegmentName() {#ac592550b6c41fd8e701dee5932087027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef extractSegmentName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * SegName)</td>
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

<p>Extracts a segment name from a string which is possibly non-null-terminated.</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-cpp">MachOObject.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/macho/segment-command/#a9457e59b3897c8c2461d68972f3d420a">llvm::MachO::segment_command::segname</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/loadcommand/#a9f8d500e5dff1d5da2c3acb1cdf633e9">llvm::objcopy::macho::LoadCommand::getSegmentName</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
