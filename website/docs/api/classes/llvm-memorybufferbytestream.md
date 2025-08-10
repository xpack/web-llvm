---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memorybufferbytestream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MemoryBufferByteStream` Class

<p>An implementation of <a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a> whose data is backed by an llvm <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> object. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MemoryBufferByteStream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarybytestream-h">llvm/Support/BinaryByteStream.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binarybytestream">BinaryByteStream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An implementation of <a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a> which holds its entire data set in a single contiguous buffer. <a href="/web-llvm/docs/api/classes/llvm/binarybytestream/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d8f1923d8bfafed7211c1bba84dbb02">MemoryBufferByteStream</a> (std::unique_ptr&lt; MemoryBuffer &gt; Buffer, llvm::endianness Endian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2307f2f081ad9d019a6638d2be2d9d8c">MemBuffer</a></td>
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

<p>An implementation of <a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a> whose data is backed by an llvm <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> object.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/memorybufferbytestream">MemoryBufferByteStream</a> owns the <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> in question. As with <a href="/web-llvm/docs/api/classes/llvm/binarybytestream">BinaryByteStream</a>, reading from a <a href="/web-llvm/docs/api/classes/llvm/memorybufferbytestream">MemoryBufferByteStream</a> will never cause a copy.</p>


<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarybytestream-h">BinaryByteStream.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MemoryBufferByteStream() {#a4d8f1923d8bfafed7211c1bba84dbb02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemoryBufferByteStream::MemoryBufferByteStream (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; Buffer, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> Endian)</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarybytestream-h">BinaryByteStream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/binarybytestream/#a4363fb07df2a89ba41a8ea63a48ce9de">llvm::BinaryByteStream::BinaryByteStream</a>, <a href="/web-llvm/docs/api/classes/llvm/binarybytestream/#a71597bbef163273d2905cf9ab4cea214">llvm::BinaryByteStream::Endian</a>, <a href="#a2307f2f081ad9d019a6638d2be2d9d8c">MemBuffer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### MemBuffer {#a2307f2f081ad9d019a6638d2be2d9d8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemoryBuffer&gt; llvm::MemoryBufferByteStream::MemBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarybytestream-h">BinaryByteStream.h</a>.</p>


<p>Referenced by <a href="#a4d8f1923d8bfafed7211c1bba84dbb02">MemoryBufferByteStream</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarybytestream-h">BinaryByteStream.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
