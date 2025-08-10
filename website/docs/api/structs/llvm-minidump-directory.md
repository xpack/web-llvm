---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/minidump/directory
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Directory` Struct

<p>Specifies the location and type of a single stream in the minidump file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::minidump::Directory { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/minidump-h">llvm/BinaryFormat/Minidump.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#af987d06ebd01c222f54d957f97dd7650">support::little_t</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/minidump/#aa8cbdda4c517e8f73a3f150077295280">StreamType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13a26a23295f6783a46d9dcd6e2e27c0">Type</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/minidump/locationdescriptor">LocationDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0274e66af4b8081e718c87e75bd9be9b">Location</a></td>
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

<p>Specifies the location and type of a single stream in the minidump file.</p>


<p>The minidump stream directory is an array of entries of this type, with its size given by <a href="/web-llvm/docs/api/structs/llvm/minidump/header/#a255d6e4cb11c68599f007278b07bdf86">Header.NumberOfStreams</a>.</p>


<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/minidump-h">Minidump.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Location {#a0274e66af4b8081e718c87e75bd9be9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocationDescriptor llvm::minidump::Directory::Location</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/minidump-h">Minidump.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile/#a544c2983fe03425d0dfe7b5ff0b59d9e">llvm::object::MinidumpFile::getRawStream</a>.</p>

</div>
</div>

### Type {#a13a26a23295f6783a46d9dcd6e2e27c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::little_t&lt;StreamType&gt; llvm::minidump::Directory::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/minidump-h">Minidump.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#a7370b2f0babea4afada61ccc3b15c54e">llvm::MinidumpYAML::Stream::create</a> and <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile/#a2f2d260d8171013121787f6fa0c985f3">llvm::object::MinidumpFile::getExceptionStream</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/minidump-h">Minidump.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
