---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-memorybuffer-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{MemoryBuffer.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{MemoryBuffer.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memorybuffer-cpp-/namedbufferalloc">NamedBufferAlloc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-memorybuffer-cpp-/memorybuffermem">MemoryBufferMem&lt;MB&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-memorybuffer-cpp-/memorybuffermem">MemoryBufferMem</a> - Named <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> pointing to a block of memory. <a href="/web-llvm/docs/api/classes/anonymous-memorybuffer-cpp-/memorybuffermem/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-memorybuffer-cpp-/memorybuffermmapfile">MemoryBufferMMapFile&lt;MB&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> maps a file descriptor using <a href="/web-llvm/docs/api/classes/llvm/sys/fs/mapped-file-region">sys::fs::mapped_file_region</a>. <a href="/web-llvm/docs/api/classes/anonymous-memorybuffer-cpp-/memorybuffermmapfile/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/sys/fs/mapped-file-region/#a7d087bce12e64c2578f57ca0e1884919">sys::fs::mapped_file_region::mapmode</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a48b9c1ead27294cc1b519fedfd9b4c37">Mapmode</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/sys/fs/mapped-file-region/#a7d087bce12e64c2578f57ca0e1884919">sys::fs::mapped_file_region::mapmode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7146662aac657d5d55b1ca9d4e299086">Mapmode&lt; MemoryBuffer &gt;</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/sys/fs/mapped-file-region/#a7d087bce12e64c2578f57ca0e1884919">sys::fs::mapped_file_region::mapmode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac48a456bffcc4eb2e5f7dfa6d0113851">Mapmode&lt; WritableMemoryBuffer &gt;</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/sys/fs/mapped-file-region/#a7d087bce12e64c2578f57ca0e1884919">sys::fs::mapped_file_region::mapmode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b25a53de8c77047609a00eb2db2a9f2">Mapmode&lt; WriteThroughMemoryBuffer &gt;</a> = sys::fs::mapped_file_region::readwrite</td>
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

## Variables

### Mapmode {#a48b9c1ead27294cc1b519fedfd9b4c37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sys::fs::mapped_file_region::mapmode anonymous{MemoryBuffer.cpp}::Mapmode</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    sys::fs::mapped_file_region::readonly
</div>
</dd>
</dl>

<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-memorybuffer-cpp-/memorybuffermmapfile/#a2c9ab83ebcf60eb23389620b47c6e9b6">anonymous{MemoryBuffer.cpp}::MemoryBufferMMapFile&lt; MB &gt;::MemoryBufferMMapFile</a>.</p>

</div>
</div>

### Mapmode&lt; MemoryBuffer &gt; {#a7146662aac657d5d55b1ca9d4e299086}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sys::fs::mapped_file_region::mapmode anonymous{MemoryBuffer.cpp}::Mapmode&lt; MemoryBuffer &gt;</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    sys::fs::mapped_file_region::readonly
</div>
</dd>
</dl>

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>

</div>
</div>

### Mapmode&lt; WritableMemoryBuffer &gt; {#ac48a456bffcc4eb2e5f7dfa6d0113851}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sys::fs::mapped_file_region::mapmode anonymous{MemoryBuffer.cpp}::Mapmode&lt; WritableMemoryBuffer &gt;</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    sys::fs::mapped_file_region::priv
</div>
</dd>
</dl>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>

</div>
</div>

### Mapmode&lt; WriteThroughMemoryBuffer &gt; {#a7b25a53de8c77047609a00eb2db2a9f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sys::fs::mapped_file_region::mapmode anonymous{MemoryBuffer.cpp}::Mapmode&lt; WriteThroughMemoryBuffer &gt; = sys::fs::mapped_file_region::readwrite</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
