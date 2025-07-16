---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/objcopy/macho/lazybindinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LazyBindInfo` Struct Reference

<p>The location of the lazy bind info inside the binary is described by LC_DYLD_INFO load command. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::objcopy::macho::LazyBindInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">ObjCopy/MachO/MachOObject.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d32b13b4857e04203d0307f0faa3af5">Opcodes</a></td>
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

<p>The location of the lazy bind info inside the binary is described by LC_DYLD_INFO load command.</p>


<p>Some uses of external symbols do not need to be bound immediately. Instead they can be lazily bound on first use. The lazy_bind contains a stream of BIND opcodes to bind all lazy symbols. Normal use is that dyld ignores the lazy_bind section when loading an image. Instead the static linker arranged for the lazy pointer to initially point to a helper function which pushes the offset into the lazy_bind area for the symbol needing to be bound, then jumps to dyld which simply adds the offset to lazy_bind_off to get the information on what to bind.</p>


<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Opcodes {#a2d32b13b4857e04203d0307f0faa3af5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;uint8_t&gt; llvm::objcopy::macho::LazyBindInfo::Opcodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
