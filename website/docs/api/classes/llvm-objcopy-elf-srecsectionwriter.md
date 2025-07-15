---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/objcopy/elf/srecsectionwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SRECSectionWriter` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::objcopy::elf::SRECSectionWriter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ObjCopy/ELF/ELFObject.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/srecsectionwriterbase">SRECSectionWriterBase</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb229673b412baa92282ffee03736a08">SRECSectionWriter</a> (WritableMemoryBuffer &amp;Buf, uint64_t Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c0bdb8c0a5dc11c8f200df17eb17df3">visit</a> (const StringTableSection &amp;Sec) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3309f7373b0d574882e15934f708347e">writeRecord</a> (SRecord &amp;Record, uint64_t Off) override</td>
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


<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SRECSectionWriter() {#adb229673b412baa92282ffee03736a08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::objcopy::elf::SRECSectionWriter::SRECSectionWriter (<a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer">WritableMemoryBuffer</a> &amp; Buf, uint64_t Offset)</td>
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



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/srecsectionwriterbase/#a698a24045cf53b7148f7e408f5ecad14">llvm::objcopy::elf::SRECSectionWriterBase::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/srecsectionwriterbase/#ad1db0dd6add44e78f7b4a07d28894ef9">llvm::objcopy::elf::SRECSectionWriterBase::SRECSectionWriterBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### visit() {#a2c0bdb8c0a5dc11c8f200df17eb17df3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SRECSectionWriter::visit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/stringtablesection">StringTableSection</a> &amp; Sec)</td>
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



<p>Declaration at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>, definition at line 2932 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#af48cff00887e58910f0074f00165b784">llvm::StringTableBuilder::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a6fefaf0cf6568001708fc6f9b862687a">llvm::objcopy::elf::SectionBase::Size</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#ae2469d919349b52e2d98dd09fed5d623">llvm::StringTableBuilder::write</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/srecsectionwriterbase/#a6c620527600c3b7b2f5ef48b7646b0c4">llvm::objcopy::elf::SRECSectionWriterBase::writeSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### writeRecord() {#a3309f7373b0d574882e15934f708347e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SRECSectionWriter::writeRecord (<a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/srecord">SRecord</a> &amp; Record, uint64_t Off)</td>
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



<p>Declaration at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>, definition at line 2899 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionwriter/#adc4efb8608176f891017b0fae1505ca9">llvm::objcopy::elf::SectionWriter::Out</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
