---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/objcopy/macho/exportinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ExportInfo` Struct Reference

<p>The location of the export info inside the binary is described by LC_DYLD_INFO load command. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::objcopy::macho::ExportInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">ObjCopy/MachO/MachOObject.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa185fe5f6e7a83126aecc73067527a1f">Trie</a></td>
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

<p>The location of the export info inside the binary is described by LC_DYLD_INFO load command.</p>


<p>The symbols exported by a dylib are encoded in a trie. This is a compact representation that factors out common prefixes. It also reduces LINKEDIT pages in RAM because it encodes all information (name, address, flags) in one small, contiguous range. The export area is a stream of nodes. The first node sequentially is the start node for the trie. Nodes for a symbol start with a uleb128 that is the length of the exported symbol information for the string so far. If there is no exported symbol, the node starts with a zero byte. If there is exported info, it follows the length. First is a uleb128 containing flags. Normally, it is followed by a uleb128 encoded offset which is location of the content named by the symbol from the mach_header for the image. If the flags is EXPORT_SYMBOL_FLAGS_REEXPORT, then following the flags is a uleb128 encoded library ordinal, then a zero terminated <a href="/web-llvm/docs/api/namespaces/llvm/#ad9748bf198e8fae8a64c80a0720d4012">UTF8</a> string. If the string is zero length, then the symbol is re-export from the specified dylib with the same name. If the flags is EXPORT_SYMBOL_FLAGS_STUB_AND_RESOLVER, then following the flags is two uleb128s: the stub offset and the resolver offset. The stub is used by non-lazy pointers. The resolver is used by lazy pointers and must be called to get the actual address to use. After the optional exported symbol information is a byte of how many edges (0-255) that this node has leaving it, followed by each edge. Each edge is a zero terminated <a href="/web-llvm/docs/api/namespaces/llvm/#ad9748bf198e8fae8a64c80a0720d4012">UTF8</a> of the addition chars in the symbol, followed by a uleb128 offset for the node that edge points to.</p>


<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Trie {#aa185fe5f6e7a83126aecc73067527a1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;uint8_t&gt; llvm::objcopy::macho::ExportInfo::Trie</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
