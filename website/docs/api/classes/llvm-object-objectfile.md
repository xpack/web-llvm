---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/objectfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ObjectFile` Class

<p>This class is the base class for all object file types. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::object::ObjectFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">llvm/Object/ObjectFile.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile">SymbolicFile</a></td>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile">COFFObjectFile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase">ELFObjectFileBase</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/goffobjectfile">GOFFObjectFile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile">WasmObjectFile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile">XCOFFObjectFile</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedbd7a30383971b6104ec43d14c49ad0">symbol_iterator_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/symbol-iterator">symbol_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa59ff68c982a17c63770d7eb866a1f65">section_iterator_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a18a35d6d108ec102a6bff8ac2bfd4c62">section_iterator</a> &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23fe52bbc164a30ba18e057d37bd2283">SymbolRef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84e7ca90f9c05219e1c82f602bad10fc">SectionRef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a198fe5e1de4053e999d41555cb796801">RelocationRef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a012f0d21dc79aa5e5884556e54fc05">ObjectFile</a> ()=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99201364d9ccfb139575ef271c218b33">ObjectFile</a> (const ObjectFile &amp;other)=delete</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af74504142c7146b3602a3aa280d07df7">ObjectFile</a> (unsigned int Type, MemoryBufferRef Source)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3bf89e1a48e2a63b62280a93c468f09">operator=</a> (const ObjectFile &amp;other)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0be1fdc703dfefdcd9298662351d5daf">getCommonSymbolSize</a> (DataRefImpl Symb) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bb2a3e93220e7762d7b378775dbb5ad">dynamic_relocation_sections</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aedbd7a30383971b6104ec43d14c49ad0">symbol_iterator_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa22a9825f4937b28269552f5b8db4a69">symbols</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a18a35d6d108ec102a6bff8ac2bfd4c62">section_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9eb4120f90b00d473f53ce9877388d0">section_begin</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a18a35d6d108ec102a6bff8ac2bfd4c62">section_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e48ce01c39d5e5e36eced4e3d3f6f23">section_end</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa59ff68c982a17c63770d7eb866a1f65">section_iterator_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f73649118e365a230be4870d824e7cf">sections</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd84145c9ebe80a3a256dea1ee944946">hasDebugInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43ad027c7a7cc0488f41d28529096967">getBytesInAddress</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of bytes used to represent an address in this object file format. <a href="#a43ad027c7a7cc0488f41d28529096967">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8548b20e00cecb916cf36d5b8005f787">getFileFormatName</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154">Triple::ArchType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade6a289b7efafc8625daf0575ad81c08">getArch</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cd">Triple::OSType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abab8f4c1f92f99c54485c00ff2910b89">getOS</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures">SubtargetFeatures</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6525573202e0f8287d46eab98e5ae39e">getFeatures</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec7a09f249c61917699f80f43e2f052e">tryGetCPUName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cc057c599c19bd6bf19d89ce44fe3af">setARMSubArch</a> (Triple &amp;TheTriple) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add9e6e848f0b07f65c7770faff6a4018">getStartAddress</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f6cda42b5be79b59179a5ca1a3e7bfa">makeTriple</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a triple from the data in this object file. <a href="#a6f6cda42b5be79b59179a5ca1a3e7bfa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ac12f0d523f7e7c9c5d23baa1ed6439">mapDebugSectionName</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps a debug section name to a standard DWARF section name. <a href="#a9ac12f0d523f7e7c9c5d23baa1ed6439">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8f3b539b9b900281504a67b6777f3a9">isRelocatableObject</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this is a relocatable object (.o/.obj). <a href="#ab8f3b539b9b900281504a67b6777f3a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb3a55d5aef67debd24f38e6bf9a92d3">isReflectionSectionStrippable</a> (llvm::binaryformat::Swift5ReflectionSectionKind ReflectionSectionKind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the reflection section can be stripped by the linker. <a href="#abb3a55d5aef67debd24f38e6bf9a92d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa1c9b49781cf9386252a4cf41ab3abc">base</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a381659cd808b1ca92fc7628a067d9346">getSymbolName</a> (DataRefImpl Symb) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50eb735d1fb3b6f5cc988c6d7caf5aa5">printSymbolName</a> (raw_ostream &amp;OS, DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51815869de4debd52444c1e3d3e79a31">getSymbolAddress</a> (DataRefImpl Symb) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a876d36732f99f718f70e65c63b4ef79f">getSymbolValueImpl</a> (DataRefImpl Symb) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a964fad6d745daec631670b795505f1b6">getSymbolAlignment</a> (DataRefImpl Symb) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a604c175a708a243eaa72b30ad38b8985">getCommonSymbolSizeImpl</a> (DataRefImpl Symb) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04">SymbolRef::Type</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5dd4b48117d96394d09345a2b42f039">getSymbolType</a> (DataRefImpl Symb) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a18a35d6d108ec102a6bff8ac2bfd4c62">section_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab21d0cb75a969e21f3eb9271d80ffb36">getSymbolSection</a> (DataRefImpl Symb) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b288b34e229073386b036788f29f5f7">moveSectionNext</a> (DataRefImpl &amp;Sec) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a267ae46a4e10888c5af821906a95b82b">getSectionName</a> (DataRefImpl Sec) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90edd6594e49af23a0cac1e7f6c58610">getSectionAddress</a> (DataRefImpl Sec) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e3c3e220433b62bc7782940939a6977">getSectionIndex</a> (DataRefImpl Sec) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f24aaa0b0e973fe55c17f3163d3c955">getSectionSize</a> (DataRefImpl Sec) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594425ae5ff83026dd0a80293a8309bb">getSectionContents</a> (DataRefImpl Sec) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26c49e2cb4daedb7a72657452ce18559">getSectionAlignment</a> (DataRefImpl Sec) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e87fa8b55da44c472ddb9285b0f7395">isSectionCompressed</a> (DataRefImpl Sec) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75f7ee1182e754528e7255604daa532e">isSectionText</a> (DataRefImpl Sec) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa307b78951bc4a850af80d0b83b460b4">isSectionData</a> (DataRefImpl Sec) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d9d5c8cd3be40c71dfd472e2e24e5f0">isSectionBSS</a> (DataRefImpl Sec) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cd53a474df70c87957caa57eebce7da">isSectionVirtual</a> (DataRefImpl Sec) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed7ed4cb387ecbb7339ba44ff631ebf0">isSectionBitcode</a> (DataRefImpl Sec) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3e01c3acb47b509641cf2bf14f5625d">isSectionStripped</a> (DataRefImpl Sec) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02c8908bb9d5015e99e258331e01da3a">isBerkeleyText</a> (DataRefImpl Sec) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29439ca2c354a5c2a2252f79f44dd3ff">isBerkeleyData</a> (DataRefImpl Sec) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c04696c0654db76cb8f79b5251be274">isDebugSection</a> (DataRefImpl Sec) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cdfced70f9768c23d77933e548ab2a9">section_rel_begin</a> (DataRefImpl Sec) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade1b7ddee5e9cad4f1e2cdac8a786e6e">section_rel_end</a> (DataRefImpl Sec) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a18a35d6d108ec102a6bff8ac2bfd4c62">section_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a099a2b47a2203c1db18dda6a7a2f1065">getRelocatedSection</a> (DataRefImpl Sec) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5ebf47a552e5ae9bdabc47ea4d46c84">moveRelocationNext</a> (DataRefImpl &amp;Rel) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3ae99ea077142b4b36a5f905fab9b94">getRelocationOffset</a> (DataRefImpl Rel) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/symbol-iterator">symbol_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cdb66a55557e9385c8af8c04e66a2af">getRelocationSymbol</a> (DataRefImpl Rel) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dd0448ad4d382a3802a51518d05a5f8">getRelocationType</a> (DataRefImpl Rel) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b001dc3cd308f8fba7bdca9df006986">getRelocationTypeName</a> (DataRefImpl Rel, SmallVectorImpl&lt; char &gt; &amp;Result) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/binaryformat/#ab355a2b14b4cc35373b4526fbfab894d">llvm::binaryformat::Swift5ReflectionSectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42e0a645446a260055f2d7424ad749a3">mapReflectionSectionNameToEnumValue</a> (StringRef SectionName) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa520e1a721f81e1befb66b422c6e4a60">getSymbolValue</a> (DataRefImpl Symb) const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83e21f1f1e1dce4788e8ba2c803c4d81">anchor</a> ()</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/owningbinary">OwningBinary</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a926af6aca697fdbacb3e3ea1000f0ec4">createObjectFile</a> (StringRef ObjectPath)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2fa24b430bb715d3519191162e402e2">createObjectFile</a> (MemoryBufferRef Object, llvm::file_magic Type, bool InitContent=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af476b74fea2b1f162925eb114e5236f5">createObjectFile</a> (MemoryBufferRef Object)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfd2c845df728147a668adc4d48dd152">classof</a> (const Binary *v)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile">COFFObjectFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e3b4e38f2043b08c7a0df72bc8bd0f3">createCOFFObjectFile</a> (MemoryBufferRef Object)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3a58183c0e4b64719f5ffd6ae7a88c3">createXCOFFObjectFile</a> (MemoryBufferRef Object, unsigned FileType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ef8ed10341ed52e784b5408bac56424">createELFObjectFile</a> (MemoryBufferRef Object, bool InitContent=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bcb896473d4c0e5275a58bf731ee899">createMachOObjectFile</a> (MemoryBufferRef Object, uint32_t UniversalCputype=0, uint32_t UniversalIndex=0, size_t MachOFilesetEntryOffset=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> instance from a given buffer. <a href="#a3bcb896473d4c0e5275a58bf731ee899">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc723cdaf6e00f67816de239cdaf82cb">createGOFFObjectFile</a> (MemoryBufferRef Object)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile">WasmObjectFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a920bb15c9298c61cbd6db1cef2394a82">createWasmObjectFile</a> (MemoryBufferRef Object)</td>
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

<p>This class is the base class for all object file types.</p>


<p>Concrete instances of this object are created by createObjectFile, which figures out which type to create.</p>


<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### section\_iterator\_range {#aa59ff68c982a17c63770d7eb866a1f65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::object::ObjectFile::section_iterator_range =  iterator_range&lt;section_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### symbol\_iterator\_range {#aedbd7a30383971b6104ec43d14c49ad0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::object::ObjectFile::symbol_iterator_range =  iterator_range&lt;symbol_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### RelocationRef {#a198fe5e1de4053e999d41555cb796801}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/object/relocationref">RelocationRef</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Reference <a href="#a198fe5e1de4053e999d41555cb796801">RelocationRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aa7ab27ad809711f7ad62636b2f295a01">llvm::object::MachOObjectFile::extrel_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#af0fde7879a332b4234a4a2a7e59446db">llvm::object::MachOObjectFile::extrel_end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a4f61c62b32627fa1844d8d08f28bab35">llvm::object::COFFObjectFile::getCOFFRelocation</a>, <a href="/web-llvm/docs/api/structs/llvm/object/xcoffrelocation/#ac7628f9e0b10c3a71a88985030168481">llvm::object::XCOFFRelocation&lt; llvm::support::ubig32_t &gt;::getRelocatedLength</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#adcc00d1267df0ecc8d7a6d18caf4dbd0">llvm::object::WasmObjectFile::getWasmRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad103fd8ebc431f075697c16d4e66f9e8">llvm::object::MachOObjectFile::locrel_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#afc59d7882fd3b78d7d8bd063816f450d">llvm::object::MachOObjectFile::locrel_end</a>, <a href="#a198fe5e1de4053e999d41555cb796801">RelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a7a78994887ac9a82a012307b4f7baf27">llvm::object::COFFObjectFile::section_rel_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a4db2c6874a1695b79e947621f7bad0ad">llvm::object::MachOObjectFile::section_rel_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a75c2cc14199307ebc8e9a27cd3630ed0">llvm::object::WasmObjectFile::section_rel_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ac105d56f284be37d59dbca7613dcbf88">llvm::object::COFFObjectFile::section_rel_end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a5b4a2cfae548a9a5cf6228605d4c0e7d">llvm::object::MachOObjectFile::section_rel_end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a03425ecd6379bfd3afa9e0be578fc3c5">llvm::object::WasmObjectFile::section_rel_end</a> and <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a09d1ca2c06b80838d961631a71384907">llvm::object::XCOFFObjectFile::section_rel_end</a>.</p>

</div>
</div>

### SectionRef {#a84e7ca90f9c05219e1c82f602bad10fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Reference <a href="#a84e7ca90f9c05219e1c82f602bad10fc">SectionRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a43739eb6bed0aa4dc4ac7c50de26674b">llvm::object::MachOObjectFile::getAnyRelocationSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ab5c5fe9889d863b8a8fbe02cbf68f662">llvm::object::COFFObjectFile::getCOFFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#a93cfe4f193a8a7d9cb445841cde670db">llvm::object::ELFObjectFileBase::getCrelDecodeProblem</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#a39999704ecb9ef34c545abea6e44258a">llvm::object::ELFObjectFileBase::getEIdentABIVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#ab5019ff9e3502f422f3d8668201f5756">llvm::object::ELFObjectFileBase::getPltEntries</a>, <a href="#a099a2b47a2203c1db18dda6a7a2f1065">getRelocatedSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a73ddbfba78956c4ed1b7c2ab5b816dbb">llvm::object::MachOObjectFile::getRelocationRelocatedSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a8b53a54831e9ad9cb7fe4c06fef03c43">llvm::object::COFFObjectFile::getRvaAndSizeAsBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ad35aa17b159b4fcc409db6230a7168a2">llvm::object::COFFObjectFile::getRvaPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a88e19a85aa8bc06f5b3e51c382dfbb41">llvm::object::MachOObjectFile::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a1a18707996459de69e40ab867eeee801">llvm::object::MachOObjectFile::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a76ab692cb3d70a67aafcb0ab4c22041e">llvm::object::COFFObjectFile::getSectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ae48752dc6271082d4f4cb2c9db80703d">llvm::object::MachOObjectFile::getSectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a6219972bdae3e9ac0f4daf447f328d82">llvm::object::MachOObjectFile::getSectionType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a2456423e9e3bb5ffdc0a75fa36dd16cf">llvm::object::COFFObjectFile::getSymbolSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a35b89b3d8775f01eeeb4e36769e2b435">llvm::object::MachOObjectFile::getSymbolSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#ac663c397d2633e31dac4bf80c5840a78">llvm::object::WasmObjectFile::getSymbolSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#af0d12d4046ba19c552b1e86fbe25abe9">llvm::object::XCOFFObjectFile::getSymbolSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#ab9204e81d88bc6fc86d82831d13beb0f">llvm::object::WasmObjectFile::getWasmSection</a>, <a href="#abd84145c9ebe80a3a256dea1ee944946">hasDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a69eb80f1d4302a2c29668cde1bb00797">llvm::object::COFFObjectFile::section_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/goffobjectfile/#a202f0f8b78ce5c09fc0f7a55a37fedad">llvm::object::GOFFObjectFile::section_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a56dc12deef303c47e57819035ab2f2f3">llvm::object::MachOObjectFile::section_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a3b0d45e8e8093653af68f7567eb67f25">llvm::object::WasmObjectFile::section_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a065428320f2dc6545e5a6b8d6f85df1b">llvm::object::XCOFFObjectFile::section_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a2ae5b3985996bc3c13fd150a47af0330">llvm::object::COFFObjectFile::section_end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/goffobjectfile/#a99e8b69967e7995c1fd97f34086f08ed">llvm::object::GOFFObjectFile::section_end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a274c4612a46dd1b0aa44ca5745642e2b">llvm::object::MachOObjectFile::section_end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a8349576fbde57780d1474b92f0352127">llvm::object::WasmObjectFile::section_end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#af23bd63f7e9ab9c9da2bffd45a529a6e">llvm::object::XCOFFObjectFile::section_end</a>, <a href="#a84e7ca90f9c05219e1c82f602bad10fc">SectionRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#a26a8b66384eac1604e4ce7bd35bb6878">llvm::object::ELFObjectFile&lt; ELF32LE &gt;::toSectionRef</a> and <a href="/web-llvm/docs/api/classes/anonymous-runtimedyldelf-cpp-/dyldelfobject/#aaf9af47b48d2f4d53961dbba93fda6b6">anonymous{RuntimeDyldELF.cpp}::DyldELFObject&lt; ELFT &gt;::updateSectionAddress</a>.</p>

</div>
</div>

### SymbolRef {#a23fe52bbc164a30ba18e057d37bd2283}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/object/symbolref">SymbolRef</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Reference <a href="#a23fe52bbc164a30ba18e057d37bd2283">SymbolRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a58bd45157985a622dba76ecef6375f4d">llvm::object::MachOObjectFile::checkSymbolTable</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a208278a65c14652df9a01a2e82cddb9b">llvm::object::COFFObjectFile::getCOFFSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#aebd5952e2b3dc1062533d96df0762772">llvm::object::COFFObjectFile::getRelocationSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a19321b2c5a24656fe59c193ae2892453">llvm::object::MachOObjectFile::getRelocationSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#acab3ba419eaa03698db0773f121a8075">llvm::object::WasmObjectFile::getRelocationSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a5608b1db31841e33e852d5e8e7362523">llvm::object::XCOFFObjectFile::getRelocationSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a7d7c96e485022e0023e9b8eec0257f0e">llvm::object::MachOObjectFile::getSymbolByIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/goffobjectfile/#ab19fe362905e7f52bfcaca67a1ffdb55">llvm::object::GOFFObjectFile::getSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#adeefe77eeb81c0dfee4bb876927e90c8">llvm::object::COFFObjectFile::getSymbolSectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a2f79817cbc7f06dd7a434e20281a0ad5">llvm::object::MachOObjectFile::getSymbolSectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a71d6474e0580f137735002afb39321c4">llvm::object::XCOFFObjectFile::getSymbolSectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a527185d51f8cd613611201b0ba35c4db">llvm::object::WasmObjectFile::getSymbolSectionId</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#ae34ddc299f0c959d7c22636cf103c2f1">llvm::object::WasmObjectFile::getSymbolSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a6b97101d75c9c68d1d2cdcbe733cb80c">llvm::object::WasmObjectFile::getWasmSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/goffobjectfile/#ad3d750211f4d6992f028417364c49453">llvm::object::GOFFObjectFile::GOFFSymbolRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a995b2c5fbe06dc317b26e03bd3012f22">llvm::object::COFFObjectFile::symbol_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/goffobjectfile/#ae783f12825518dd9914461c30f8df66d">llvm::object::GOFFObjectFile::symbol_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a21f780beb96b3c8859b9f75422e2c4f9">llvm::object::MachOObjectFile::symbol_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a6f2700f065d466d121516e7dbaa56348">llvm::object::XCOFFObjectFile::symbol_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a8669c4d5032cf05442f9f4373d5795a9">llvm::object::COFFObjectFile::symbol_end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/goffobjectfile/#a2c74478a25e84bddb116a56970c5c45e">llvm::object::GOFFObjectFile::symbol_end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aabf498b6cb34cb967c73e3c0c51baee2">llvm::object::MachOObjectFile::symbol_end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#abc7d6556798e014fdfae78bc0b3d5235">llvm::object::XCOFFObjectFile::symbol_end</a>, <a href="#a23fe52bbc164a30ba18e057d37bd2283">SymbolRef</a> and <a href="/web-llvm/docs/api/classes/anonymous-runtimedyldelf-cpp-/dyldelfobject/#affb416a373e2586e69aaf93b7b9da3f3">anonymous{RuntimeDyldELF.cpp}::DyldELFObject&lt; ELFT &gt;::updateSymbolAddress</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ObjectFile() {#a2a012f0d21dc79aa5e5884556e54fc05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::ObjectFile::ObjectFile ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### ObjectFile() {#a99201364d9ccfb139575ef271c218b33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::ObjectFile::ObjectFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Reference <a href="#af74504142c7146b3602a3aa280d07df7">ObjectFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### ObjectFile() {#af74504142c7146b3602a3aa280d07df7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectFile::ObjectFile (unsigned int Type, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Source)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/object/objectfile-cpp">ObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#a8eeef7e2323c6f1ec25eb240e1842fee">llvm::object::SymbolicFile::SymbolicFile</a>.</p>


<p>Referenced by <a href="#a920bb15c9298c61cbd6db1cef2394a82">createWasmObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#aed152f23b3ae2ebb42dac2af8b79cd0b">llvm::object::ELFObjectFileBase::ELFObjectFileBase</a>, <a href="/web-llvm/docs/api/classes/llvm/object/goffobjectfile/#a3b3a59937edbc6f58ff06abe51ce621f">llvm::object::GOFFObjectFile::GOFFObjectFile</a>, <a href="#a99201364d9ccfb139575ef271c218b33">ObjectFile</a>, <a href="#ae3bf89e1a48e2a63b62280a93c468f09">operator=</a> and <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a78b45ebf4772364c848d6aedf38fd199">llvm::object::WasmObjectFile::WasmObjectFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ae3bf89e1a48e2a63b62280a93c468f09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectFile &amp; llvm::object::ObjectFile::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Reference <a href="#af74504142c7146b3602a3aa280d07df7">ObjectFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dynamic\_relocation\_sections() {#a3bb2a3e93220e7762d7b378775dbb5ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::vector&lt; SectionRef &gt; llvm::object::ObjectFile::dynamic_relocation_sections ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### getArch() {#ade6a289b7efafc8625daf0575ad81c08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Triple::ArchType llvm::object::ObjectFile::getArch ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#a3ea94ca4d9dff028d5c6c11d8b045917">llvm::symbolize::SymbolizableObjectFile::create</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a10da25a01692d7f5b04afee82a84e17e">llvm::DWARFContext::getArch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a974d2440be47c5644fe899f3ec74a000">llvm::object::getRelocationResolver</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/#ad2ab8021c32ef2200c8b01e2105f1821">llvm::RuntimeDyld::loadObject</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afe85af578989c7f3e9627866e7fa4962">llvm::RuntimeDyldImpl::loadObjectImpl</a> and <a href="#a6f6cda42b5be79b59179a5ca1a3e7bfa">makeTriple</a>.</p>

</div>
</div>

### getBytesInAddress() {#a43ad027c7a7cc0488f41d28529096967}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint8_t llvm::object::ObjectFile::getBytesInAddress ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of bytes used to represent an address in this object file format.</p>

<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#a3ea94ca4d9dff028d5c6c11d8b045917">llvm::symbolize::SymbolizableObjectFile::create</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-runtimedyldelf-cpp-/#a4c89c8ae8b758aaf88cb3ddcb0a25c20">anonymous{RuntimeDyldELF.cpp}::createELFDebugObject</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#a974d2440be47c5644fe899f3ec74a000">llvm::object::getRelocationResolver</a>.</p>

</div>
</div>

### getCommonSymbolSize() {#a0be1fdc703dfefdcd9298662351d5daf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::ObjectFile::getCommonSymbolSize (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a604c175a708a243eaa72b30ad38b8985">getCommonSymbolSizeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#aa060785f66d4e44ba0fbdc3ae33a1e42">llvm::object::SymbolicFile::getSymbolFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a917d4e0252fa1d20b2086b2e99e78e57">llvm::object::BasicSymbolRef::SF_Common</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#afc6576af9f6c428aaeb91be518ef565d">llvm::object::SymbolRef::getCommonSize</a> and <a href="#aa520e1a721f81e1befb66b422c6e4a60">getSymbolValue</a>.</p>

</div>
</div>

### getFeatures() {#a6525573202e0f8287d46eab98e5ae39e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; SubtargetFeatures &gt; llvm::object::ObjectFile::getFeatures ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### getFileFormatName() {#a8548b20e00cecb916cf36d5b8005f787}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual StringRef llvm::object::ObjectFile::getFileFormatName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### getOS() {#abab8f4c1f92f99c54485c00ff2910b89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Triple::OSType llvm::object::ObjectFile::getOS ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda4b110a50637320a1a0db33999b809ddd">llvm::Triple::UnknownOS</a>.</p>


<p>Referenced by <a href="#a6f6cda42b5be79b59179a5ca1a3e7bfa">makeTriple</a>.</p>

</div>
</div>

### getStartAddress() {#add9e6e848f0b07f65c7770faff6a4018}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; uint64_t &gt; llvm::object::ObjectFile::getStartAddress ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a>.</p>

</div>
</div>

### hasDebugInfo() {#abd84145c9ebe80a3a256dea1ee944946}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ObjectFile::hasDebugInfo ()</td>
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



<p>Declaration at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/object/objectfile-cpp">ObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/object/sectionref/#a57539e8934c3c44b150bf8670697c783">llvm::object::SectionRef::isDebugSection</a>, <a href="#a84e7ca90f9c05219e1c82f602bad10fc">SectionRef</a> and <a href="#a7f73649118e365a230be4870d824e7cf">sections</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#a13fb59a051bd91cde4c307f263ac5e9c">llvm::symbolize::useBTFContext</a>.</p>

</div>
</div>

### isReflectionSectionStrippable() {#abb3a55d5aef67debd24f38e6bf9a92d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ObjectFile::isReflectionSectionStrippable (<a href="/web-llvm/docs/api/namespaces/llvm/binaryformat/#ab355a2b14b4cc35373b4526fbfab894d">llvm::binaryformat::Swift5ReflectionSectionKind</a> ReflectionSectionKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the reflection section can be stripped by the linker.</p>

<p>Declaration at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/object/objectfile-cpp">ObjectFile.cpp</a>.</p>

</div>
</div>

### isRelocatableObject() {#ab8f3b539b9b900281504a67b6777f3a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::object::ObjectFile::isRelocatableObject ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this is a relocatable object (.o/.obj).</p>

<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp/#a98355bc7c5d0793f5950328a4d4e6a9b">shouldSkipSectionFirstByte</a>.</p>

</div>
</div>

### makeTriple() {#a6f6cda42b5be79b59179a5ca1a3e7bfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple ObjectFile::makeTriple ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a triple from the data in this object file.</p>

<p>Declaration at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/object/objectfile-cpp">ObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda55c9e8cff2a0eab89d1b234d419ee93f">llvm::Triple::AIX</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eeca77be73c19a4451fa0580ac5b9018357b">llvm::Triple::AMD</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">llvm::Triple::arm</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af65ab1964be676bea302940a45765021">llvm::Triple::armeb</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ade6a289b7efafc8625daf0575ad81c08">getArch</a>, <a href="#abab8f4c1f92f99c54485c00ff2910b89">getOS</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a7d71851eea2209e547ae06c9c03768f5">llvm::Triple::GOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9318bd992483581cc335e1a33782ea45">llvm::Triple::isAMDGPU</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#ac391f637f5960964588dfac009094396">llvm::object::Binary::isCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#af1643080780da74a42cc8d2b517733b1">llvm::object::Binary::isGOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a81663775ec5f9cc32d3d2d15815effbd">llvm::object::Binary::isMachO</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9871d348bbc1e85bd1daacb428238707">llvm::Triple::isNVPTX</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a4e03242af50828c7cfbc08b2df1d0b71">llvm::object::Binary::isXCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a2ed78f59e2d35011e1d1ed0ad96cf411">llvm::Triple::MachO</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eecaeb014b23b113a1cda5058e4e31aca881">llvm::Triple::NVIDIA</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#af70f4019638c4a7cccaaad403c25c048">llvm::Triple::setArch</a>, <a href="#a8cc057c599c19bd6bf19d89ce44fe3af">setARMSubArch</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a0e2cea374a7428eb1b5ec87ef774e552">llvm::Triple::setObjectFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#aadd45e5c167eb85f1741ee869ea790e8">llvm::Triple::setOS</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a58ffeec08324cdbd301158e5ef874cc3">llvm::Triple::setTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#af96094469e937492a76dd8e01e81e7cc">llvm::Triple::setVendor</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">llvm::Triple::thumb</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda4b110a50637320a1a0db33999b809ddd">llvm::Triple::UnknownOS</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a1f7d761ca747e66d2ac0caa0d54b1824">llvm::Triple::XCOFF</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdafd36ac5f07b0474e2b5c167ab7158538">llvm::Triple::ZOS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#ab5019ff9e3502f422f3d8668201f5756">llvm::object::ELFObjectFileBase::getPltEntries</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/objectfiletransformer-cpp/#a675f0690b04eaa2c63f91d8e05c75106">getUUID</a>, <a href="/web-llvm/docs/api/classes/llvm/codegendatareader/#ad41848e26234890d2d908a09f6709022">llvm::CodeGenDataReader::mergeFromObjectFile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#a13fb59a051bd91cde4c307f263ac5e9c">llvm::symbolize::useBTFContext</a>.</p>

</div>
</div>

### mapDebugSectionName() {#a9ac12f0d523f7e7c9c5d23baa1ed6439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual StringRef llvm::object::ObjectFile::mapDebugSectionName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps a debug section name to a standard DWARF section name.</p>

<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### section\_begin() {#af9eb4120f90b00d473f53ce9877388d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual section_iterator llvm::object::ObjectFile::section_begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#ab3ab5fec568fdd2334001b26dd6d7f35">llvm::RuntimeDyldImpl::computeGOTSize</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#af12404037d26556e018e61366f026aaa">llvm::RuntimeDyldImpl::computeSectionStubBufSize</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#af089befa203447cdf71f665a1993a997">llvm::RuntimeDyldImpl::computeTotalAllocSize</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-runtimedyldelf-cpp-/#a65a5f8b0f9826efcc591765237e02b77">anonymous{RuntimeDyldELF.cpp}::createRTDyldELFObject</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a34d452366da541e62d1f37b1f284800d">llvm::RuntimeDyldELF::finalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afe85af578989c7f3e9627866e7fa4962">llvm::RuntimeDyldImpl::loadObjectImpl</a> and <a href="#a7f73649118e365a230be4870d824e7cf">sections</a>.</p>

</div>
</div>

### section\_end() {#a3e48ce01c39d5e5e36eced4e3d3f6f23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual section_iterator llvm::object::ObjectFile::section_end ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#ab3ab5fec568fdd2334001b26dd6d7f35">llvm::RuntimeDyldImpl::computeGOTSize</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#af12404037d26556e018e61366f026aaa">llvm::RuntimeDyldImpl::computeSectionStubBufSize</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#af089befa203447cdf71f665a1993a997">llvm::RuntimeDyldImpl::computeTotalAllocSize</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a34d452366da541e62d1f37b1f284800d">llvm::RuntimeDyldELF::finalizeLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#aaca2a6196a0b153d686419f0fd252e91">getSymbolInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afe85af578989c7f3e9627866e7fa4962">llvm::RuntimeDyldImpl::loadObjectImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener/#a89cbcd5cb777a56db440c87f1ebffdb4">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyObjectLoaded</a>, <a href="/web-llvm/docs/api/classes/anonymous-perfjiteventlistener-cpp-/perfjiteventlistener/#a502ebf0f061782cbcfa72244fbd0ec97">anonymous{PerfJITEventListener.cpp}::PerfJITEventListener::notifyObjectLoaded</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a9114640d8c0477c8c9c502e8acd7cbf7">llvm::RuntimeDyldCOFFAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffi386/#a47afe575c279c175037d664bde7e53a3">llvm::RuntimeDyldCOFFI386::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#a200d4c53b00f55a8d0911279bf576c18">llvm::RuntimeDyldCOFFThumb::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#afcf3722d9ca669767870af1a84877924">llvm::RuntimeDyldCOFFX86_64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a> and <a href="#a7f73649118e365a230be4870d824e7cf">sections</a>.</p>

</div>
</div>

### sections() {#a7f73649118e365a230be4870d824e7cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">section_iterator_range llvm::object::ObjectFile::sections ()</td>
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



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>References <a href="#af9eb4120f90b00d473f53ce9877388d0">section_begin</a> and <a href="#a3e48ce01c39d5e5e36eced4e3d3f6f23">section_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/bindrebaseseginfo/#aaaf6cee47713cc12a459bc779d459f13">llvm::object::BindRebaseSegInfo::BindRebaseSegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#a3ea94ca4d9dff028d5c6c11d8b045917">llvm::symbolize::SymbolizableObjectFile::create</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#a426a48f358aaf6be7a95428dae0d4f31">anonymous{OffloadBinary.cpp}::extractFromObject</a>, <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/intelittnotifyinfo/#a1b2e1cb1c6d2d1f8a038916a90f993a9">anonymous{IntelJITEventListener.cpp}::IntelIttnotifyInfo::fillSectionInformation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachocrtpbase/#afdfe2cf5151ed6e7266417d9f1db5f80">llvm::RuntimeDyldMachOCRTPBase&lt; Impl &gt;::finalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/object/irobjectfile/#a803ed79cb2444088841a8c8618b21ab8">llvm::object::IRObjectFile::findBitcodeInObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#aeeec63b61f99af14a9ca2c631e6b9cec">llvm::orc::getCOFFObjectFileSymbolInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a5943e7713622fd9365b27abfefd1703f">llvm::orc::getELFObjectFileSymbolInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/anonymous-symbolize-cpp-/#aca915d08912b7239d76d1044c7a8a073">llvm::symbolize::anonymous{Symbolize.cpp}::getGNUDebuglinkContents</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp/#a7d13f4f140cc4980cb2e6fe4d404b7cd">getInstrProfSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2143f8386a6b8bcb33011fdd240c38f1">llvm::orc::getMachOObjectFileSymbolInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#ab5019ff9e3502f422f3d8668201f5756">llvm::object::ELFObjectFileBase::getPltEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aff5f4a955d855eddcf05807595306406">llvm::remarks::getRemarksSectionContents</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a8b53a54831e9ad9cb7fe4c06fef03c43">llvm::object::COFFObjectFile::getRvaAndSizeAsBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ad35aa17b159b4fcc409db6230a7168a2">llvm::object::COFFObjectFile::getRvaPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a88e19a85aa8bc06f5b3e51c382dfbb41">llvm::object::MachOObjectFile::getSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/objectfiletransformer-cpp/#a675f0690b04eaa2c63f91d8e05c75106">getUUID</a>, <a href="/web-llvm/docs/api/classes/llvm/btfparser/#ad79aeb0e88860433b5085bcae9006bbd">llvm::BTFParser::hasBTFSections</a>, <a href="#abd84145c9ebe80a3a256dea1ee944946">hasDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#ae6071096c441061cfc9f7b4cf8f4ec9e">anonymous{DlltoolDriver.cpp}::identifyImportName</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp/#a7d0e6c07b7e07a14b8006f915ceb6e6d">lookupSections</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a50b4341d651ea41cb74546557170ebaa">llvm::logicalview::LVBinaryReader::mapVirtualAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a8f648767e6fee704685f85355aa7fa64">llvm::logicalview::LVBinaryReader::mapVirtualAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/codegendatareader/#ad41848e26234890d2d908a09f6709022">llvm::CodeGenDataReader::mergeFromObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/btfparser/#a4c7c5e28bb5767c6be05394c38ab0d21">llvm::BTFParser::parse</a> and <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a4f3081cf8f364816d9a91b6e24d10fba">readMachOHeader</a>.</p>

</div>
</div>

### setARMSubArch() {#a8cc057c599c19bd6bf19d89ce44fe3af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::object::ObjectFile::setARMSubArch (<a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TheTriple)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="#a6f6cda42b5be79b59179a5ca1a3e7bfa">makeTriple</a>.</p>

</div>
</div>

### symbols() {#aa22a9825f4937b28269552f5b8db4a69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">symbol_iterator_range llvm::object::ObjectFile::symbols ()</td>
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



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#a40c5717c994df60bcbe3d9299f6a5982">llvm::object::SymbolicFile::symbol_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#a7bc0f444aecc9b7aaef7facdb3d2bddb">llvm::object::SymbolicFile::symbol_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a0bf6fb10c8a68470e3b84ab25d8e5c59">accumulateLocs</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a58bd45157985a622dba76ecef6375f4d">llvm::object::MachOObjectFile::checkSymbolTable</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/objectfiletransformer/#a9940b2d9a5f2a7de1dcfcdb970bf5e51">llvm::gsym::ObjectFileTransformer::convert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#aeeec63b61f99af14a9ca2c631e6b9cec">llvm::orc::getCOFFObjectFileSymbolInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a46b8e71e338ddab38e9a33ed9502a3a2">llvm::orc::getGenericObjectFileSymbolInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2143f8386a6b8bcb33011fdd240c38f1">llvm::orc::getMachOObjectFileSymbolInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afe85af578989c7f3e9627866e7fa4962">llvm::RuntimeDyldImpl::loadObjectImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a2ca546a54409cdfc98988096faaa1674">readSymbols</a>.</p>

</div>
</div>

### tryGetCPUName() {#aec7a09f249c61917699f80f43e2f052e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::optional&lt; StringRef &gt; llvm::object::ObjectFile::tryGetCPUName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### base() {#aaa1c9b49781cf9386252a4cf41ab3abc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t * llvm::object::ObjectFile::base ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#a1300a4c221076a37306ccd4eb96b2e2a">llvm::object::ELFObjectFile&lt; ELFT &gt;::dynamic_relocation_sections</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a0008623098af6f1fd97b1ff14e46e301">llvm::object::COFFObjectFile::getDOSHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a138ae135dded82599e2cd8a1a80cdab4">llvm::object::COFFObjectFile::getHybridObjectView</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ac89ef015c6338da9a9c460c25b6f3576">llvm::object::COFFObjectFile::getRelocations</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a8b53a54831e9ad9cb7fe4c06fef03c43">llvm::object::COFFObjectFile::getRvaAndSizeAsBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ad35aa17b159b4fcc409db6230a7168a2">llvm::object::COFFObjectFile::getRvaPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ae94132813b134e3bca64884e6b6b3cd5">llvm::object::COFFObjectFile::getSectionContents</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#a6aa9147fe46df8a395d32bfcfb7585bd">llvm::object::ELFObjectFile&lt; ELFT &gt;::getSectionContents</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a9800b5c811f6cb665c2c118d1ceccb54">llvm::object::XCOFFObjectFile::getSectionContents</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a68866f040b091698a4a3bf9c744e263e">llvm::object::XCOFFObjectFile::getSectionFileOffsetToRawData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ab0d21e61fd2e024f451f6bd4a021523b">llvm::object::COFFObjectFile::getSymbolAuxData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/goffobjectfile/#a3b3a59937edbc6f58ff06abe51ce621f">llvm::object::GOFFObjectFile::GOFFObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a7a78994887ac9a82a012307b4f7baf27">llvm::object::COFFObjectFile::section_rel_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ac105d56f284be37d59dbca7613dcbf88">llvm::object::COFFObjectFile::section_rel_end</a>.</p>

</div>
</div>

### getCommonSymbolSizeImpl() {#a604c175a708a243eaa72b30ad38b8985}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::object::ObjectFile::getCommonSymbolSizeImpl (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="#a0be1fdc703dfefdcd9298662351d5daf">getCommonSymbolSize</a>.</p>

</div>
</div>

### getRelocatedSection() {#a099a2b47a2203c1db18dda6a7a2f1065}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; section_iterator &gt; ObjectFile::getRelocatedSection (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/object/objectfile-cpp">ObjectFile.cpp</a>.</p>


<p>Reference <a href="#a84e7ca90f9c05219e1c82f602bad10fc">SectionRef</a>.</p>

</div>
</div>

### getRelocationOffset() {#af3ae99ea077142b4b36a5f905fab9b94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::object::ObjectFile::getRelocationOffset (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### getRelocationSymbol() {#a8cdb66a55557e9385c8af8c04e66a2af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual symbol_iterator llvm::object::ObjectFile::getRelocationSymbol (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### getRelocationType() {#a5dd0448ad4d382a3802a51518d05a5f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::object::ObjectFile::getRelocationType (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### getRelocationTypeName() {#a3b001dc3cd308f8fba7bdca9df006986}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::object::ObjectFile::getRelocationTypeName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Result)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### getSectionAddress() {#a90edd6594e49af23a0cac1e7f6c58610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::object::ObjectFile::getSectionAddress (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### getSectionAlignment() {#a26c49e2cb4daedb7a72657452ce18559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::object::ObjectFile::getSectionAlignment (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### getSectionContents() {#a594425ae5ff83026dd0a80293a8309bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; ArrayRef&lt; uint8_t &gt; &gt; llvm::object::ObjectFile::getSectionContents (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### getSectionIndex() {#a0e3c3e220433b62bc7782940939a6977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::object::ObjectFile::getSectionIndex (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### getSectionName() {#a267ae46a4e10888c5af821906a95b82b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; StringRef &gt; llvm::object::ObjectFile::getSectionName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="#aed7ed4cb387ecbb7339ba44ff631ebf0">isSectionBitcode</a>.</p>

</div>
</div>

### getSectionSize() {#a6f24aaa0b0e973fe55c17f3163d3c955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::object::ObjectFile::getSectionSize (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### getSymbolAddress() {#a51815869de4debd52444c1e3d3e79a31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; uint64_t &gt; llvm::object::ObjectFile::getSymbolAddress (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#ac22d03239bd28b53a229486b43a9d3b8">llvm::object::SymbolRef::getAddress</a>.</p>

</div>
</div>

### getSymbolAlignment() {#a964fad6d745daec631670b795505f1b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t ObjectFile::getSymbolAlignment (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/object/objectfile-cpp">ObjectFile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a964202e1e17cee946ac67303dd34a9a2">llvm::object::SymbolRef::getAlignment</a>.</p>

</div>
</div>

### getSymbolName() {#a381659cd808b1ca92fc7628a067d9346}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; StringRef &gt; llvm::object::ObjectFile::getSymbolName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a6935271c0f6df1209adbb91f2f68d2c1">llvm::object::SymbolRef::getName</a> and <a href="#a50eb735d1fb3b6f5cc988c6d7caf5aa5">printSymbolName</a>.</p>

</div>
</div>

### getSymbolSection() {#ab21d0cb75a969e21f3eb9271d80ffb36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; section_iterator &gt; llvm::object::ObjectFile::getSymbolSection (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#af8b31890b3cf3677a9c279325661e3af">llvm::object::SymbolRef::getSection</a>.</p>

</div>
</div>

### getSymbolType() {#af5dd4b48117d96394d09345a2b42f039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; SymbolRef::Type &gt; llvm::object::ObjectFile::getSymbolType (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a234b2c90b26a44886a6f04c4281b1b65">llvm::object::SymbolRef::getType</a>.</p>

</div>
</div>

### getSymbolValue() {#aa520e1a721f81e1befb66b422c6e4a60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; ObjectFile::getSymbolValue (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/object/objectfile-cpp">ObjectFile.cpp</a>.</p>


<p>References <a href="#a0be1fdc703dfefdcd9298662351d5daf">getCommonSymbolSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#aa060785f66d4e44ba0fbdc3ae33a1e42">llvm::object::SymbolicFile::getSymbolFlags</a>, <a href="#a876d36732f99f718f70e65c63b4ef79f">getSymbolValueImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a917d4e0252fa1d20b2086b2e99e78e57">llvm::object::BasicSymbolRef::SF_Common</a> and <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ad1131f10939b205635a0dc81ca3c45d7">llvm::object::BasicSymbolRef::SF_Undefined</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a62ace90d17446bf72452ac5df2d0cfbd">llvm::object::COFFObjectFile::getSymbolAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aeb1975d59d60a84adba98e90c59872e8">llvm::object::MachOObjectFile::getSymbolAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#af2a2757f91471e6b80ccffa7840cb154">llvm::object::WasmObjectFile::getSymbolAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#aefbba218ff811c972e66adacb950989c">llvm::object::SymbolRef::getValue</a>.</p>

</div>
</div>

### getSymbolValueImpl() {#a876d36732f99f718f70e65c63b4ef79f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::object::ObjectFile::getSymbolValueImpl (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="#aa520e1a721f81e1befb66b422c6e4a60">getSymbolValue</a>.</p>

</div>
</div>

### isBerkeleyData() {#a29439ca2c354a5c2a2252f79f44dd3ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ObjectFile::isBerkeleyData (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/object/objectfile-cpp">ObjectFile.cpp</a>.</p>


<p>Reference <a href="#aa307b78951bc4a850af80d0b83b460b4">isSectionData</a>.</p>

</div>
</div>

### isBerkeleyText() {#a02c8908bb9d5015e99e258331e01da3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ObjectFile::isBerkeleyText (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/object/objectfile-cpp">ObjectFile.cpp</a>.</p>


<p>Reference <a href="#a75f7ee1182e754528e7255604daa532e">isSectionText</a>.</p>

</div>
</div>

### isDebugSection() {#a8c04696c0654db76cb8f79b5251be274}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ObjectFile::isDebugSection (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/object/objectfile-cpp">ObjectFile.cpp</a>.</p>

</div>
</div>

### isSectionBitcode() {#aed7ed4cb387ecbb7339ba44ff631ebf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ObjectFile::isSectionBitcode (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/object/objectfile-cpp">ObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="#a267ae46a4e10888c5af821906a95b82b">getSectionName</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### isSectionBSS() {#a2d9d5c8cd3be40c71dfd472e2e24e5f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::object::ObjectFile::isSectionBSS (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### isSectionCompressed() {#a6e87fa8b55da44c472ddb9285b0f7395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::object::ObjectFile::isSectionCompressed (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### isSectionData() {#aa307b78951bc4a850af80d0b83b460b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::object::ObjectFile::isSectionData (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="#a29439ca2c354a5c2a2252f79f44dd3ff">isBerkeleyData</a>.</p>

</div>
</div>

### isSectionStripped() {#ae3e01c3acb47b509641cf2bf14f5625d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ObjectFile::isSectionStripped (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/object/objectfile-cpp">ObjectFile.cpp</a>.</p>

</div>
</div>

### isSectionText() {#a75f7ee1182e754528e7255604daa532e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::object::ObjectFile::isSectionText (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="#a02c8908bb9d5015e99e258331e01da3a">isBerkeleyText</a>.</p>

</div>
</div>

### isSectionVirtual() {#a5cd53a474df70c87957caa57eebce7da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::object::ObjectFile::isSectionVirtual (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### mapReflectionSectionNameToEnumValue() {#a42e0a645446a260055f2d7424ad749a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::binaryformat::Swift5ReflectionSectionKind llvm::object::ObjectFile::mapReflectionSectionNameToEnumValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/binaryformat/#ab355a2b14b4cc35373b4526fbfab894da80eaeeee65cce2c1b9fa9a5741956f9a">llvm::binaryformat::unknown</a>.</p>

</div>
</div>

### moveRelocationNext() {#aa5ebf47a552e5ae9bdabc47ea4d46c84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::object::ObjectFile::moveRelocationNext (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Rel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### moveSectionNext() {#a8b288b34e229073386b036788f29f5f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::object::ObjectFile::moveSectionNext (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### printSymbolName() {#a50eb735d1fb3b6f5cc988c6d7caf5aa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ObjectFile::printSymbolName (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/object/objectfile-cpp">ObjectFile.cpp</a>.</p>


<p>References <a href="#a381659cd808b1ca92fc7628a067d9346">getSymbolName</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### section\_rel\_begin() {#a7cdfced70f9768c23d77933e548ab2a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual relocation_iterator llvm::object::ObjectFile::section_rel_begin (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### section\_rel\_end() {#ade1b7ddee5e9cad4f1e2cdac8a786e6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual relocation_iterator llvm::object::ObjectFile::section_rel_end (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a83e21f1f1e1dce4788e8ba2c803c4d81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ObjectFile::anchor ()</td>
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



<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/object/objectfile-cpp">ObjectFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#acfd2c845df728147a668adc4d48dd152}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::ObjectFile::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/binary">Binary</a> * v)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### createCOFFObjectFile() {#a3e3b4e38f2043b08c7a0df72bc8bd0f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; COFFObjectFile &gt; &gt; ObjectFile::createCOFFObjectFile (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object)</td>
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



<p>Declaration at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 1896 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a75ab5f6073614bedfd40289035d5fd2f">llvm::object::COFFObjectFile::create</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a489285433291b13eea20e7849a2aff39">llvm::jitlink::createLinkGraphFromCOFFObject_x86_64</a> and <a href="#ac2fa24b430bb715d3519191162e402e2">createObjectFile</a>.</p>

</div>
</div>

### createELFObjectFile() {#a5ef8ed10341ed52e784b5408bac56424}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; ObjectFile &gt; &gt; ObjectFile::createELFObjectFile (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object, bool InitContent=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Declaration at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elfobjectfile-cpp">ELFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/elfobjectfile-cpp/#a595f1eb44be7dd8b0cad008384c9d721">createPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aa87228a0d135b2b897952fa11ff023c5ac700ff9a9a24f46587997e131502702c">llvm::ELF::ELFCLASS32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aa87228a0d135b2b897952fa11ff023c5a54b4da97cdda07031363b240c26c9794">llvm::ELF::ELFCLASS64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a868a39064cf90c55a5a8b267d8018c2bafedc8af0121f7104ef49a576b30865de">llvm::ELF::ELFDATA2LSB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a868a39064cf90c55a5a8b267d8018c2ba133a1bcc89f1dca304102b741ecbf299">llvm::ELF::ELFDATA2MSB</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a7301c8fd89ad0f595f4ce4609c872704">llvm::MemoryBufferRef::getBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a62b2843b74e5f05930ebf5c63766a668">llvm::MemoryBufferRef::getBufferStart</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6e5453100b9e598d90cae8bc9f6d45f4">llvm::object::getElfArchType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ac95049051540ea75bfbcab8a7c8e1f69">llvm::jitlink::createLinkGraphFromELFObject_aarch64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a2a0dc55fe67dc6e71c079367865cd57a">llvm::jitlink::createLinkGraphFromELFObject_i386</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ac2b9ede3e13dcfd4f770f6ea25c35ba9">llvm::jitlink::createLinkGraphFromELFObject_loongarch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#af23db7aa950c030363b723a4558961f7">llvm::jitlink::createLinkGraphFromELFObject_ppc64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a1f68b000ad84d40757482a867e804ce9">llvm::jitlink::createLinkGraphFromELFObject_riscv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ade7e70a675849d2a83bd269102ab6f55">llvm::jitlink::createLinkGraphFromELFObject_x86_64</a> and <a href="#ac2fa24b430bb715d3519191162e402e2">createObjectFile</a>.</p>

</div>
</div>

### createGOFFObjectFile() {#acc723cdaf6e00f67816de239cdaf82cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; ObjectFile &gt; &gt; ObjectFile::createGOFFObjectFile (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object)</td>
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



<p>Declaration at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/object/goffobjectfile-cpp">GOFFObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### createMachOObjectFile() {#a3bcb896473d4c0e5275a58bf731ee899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; MachOObjectFile &gt; &gt; ObjectFile::createMachOObjectFile (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Buffer, uint32_t UniversalCputype=0, uint32_t UniversalIndex=0, size_t MachOFilesetEntryOffset=0)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> instance from a given buffer.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Buffer</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> buffer containing the <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> binary data.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UniversalCputype</td>
<td class="doxyParamItemDescription"><p>CPU type when the <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> part of a universal binary.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UniversalIndex</td>
<td class="doxyParamItemDescription"><p>Index of the <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> within a universal binary.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MachOFilesetEntryOffset</td>
<td class="doxyParamItemDescription"><p>Offset of the <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> entry in a fileset <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A std::unique_ptr to a <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> instance on success.</p></dd>
</dl>


<p>Declaration at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 5320 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a6456a8f4d04f36afe434911ec571ba3a">llvm::object::MachOObjectFile::create</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a7301c8fd89ad0f595f4ce4609c872704">llvm::MemoryBufferRef::getBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20ad5a8a27f4e310ea593b285615faaca35">llvm::object::invalid_file_type</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5d4c961b9b6f1da17df74b4496ecb30e">llvm::StringRef::slice</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ad6d1e1cefa758f81b79f12c1d639d3b5">llvm::jitlink::createLinkGraphFromMachOObject_arm64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a3e227783299e3067cd6b136af9eb6bbc">llvm::jitlink::createLinkGraphFromMachOObject_x86_64</a>, <a href="#ac2fa24b430bb715d3519191162e402e2">createObjectFile</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machouniversalbinary/objectforarch/#a8ab7ed72632476f2d49c80dae14ce478">llvm::object::MachOUniversalBinary::ObjectForArch::getAsObjectFile</a>.</p>

</div>
</div>

### createObjectFile() {#a926af6aca697fdbacb3e3ea1000f0ec4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; OwningBinary&lt; ObjectFile &gt; &gt; ObjectFile::createObjectFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ObjectPath)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Pointer to <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> subclass to handle this type of object.</p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ObjectPath</td>
<td class="doxyParamItemDescription"><p>The path to the object file. ObjectPath.isObject must return true. Create <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> from path.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/object/objectfile-cpp">ObjectFile.cpp</a>.</p>


<p>References <a href="#a926af6aca697fdbacb3e3ea1000f0ec4">createObjectFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/classes/llvm/erroror/#a7903f14c3b4fb5b4f9f9fa8b4ee0b4eb">llvm::ErrorOr&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/erroror/#a8300c72908f1845c931951ed4b2a2375">llvm::ErrorOr&lt; T &gt;::getError</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa98611beefe78f907beeee7305cc8174">llvm::MemoryBuffer::getFile</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#af476b74fea2b1f162925eb114e5236f5">createObjectFile</a>, <a href="#a926af6aca697fdbacb3e3ea1000f0ec4">createObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#a4ee418c47f5baa9b4b570371fc9630ce">llvm::object::SymbolicFile::createSymbolicFile</a>, <a href="/web-llvm/docs/api/structs/llvm/newarchivemember/#a5b9ae09da2b1f1939e37ba537fdf9eb1">llvm::NewArchiveMember::detectKindFromObject</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rtdyldobjectlinkinglayer/#a640efdfe6f9a9949a292dc894222e8f5">llvm::orc::RTDyldObjectLinkingLayer::emit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a214181fcdbdcdd2ce1d22fe395716abc">llvm::object::extractOffloadBinaries</a>, <a href="/web-llvm/docs/api/classes/llvm/object/irobjectfile/#aeaceb8997142b34e42f329adfba36658">llvm::object::IRObjectFile::findBitcodeInMemBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a5236c37b672e45c22ef2ebb47518871e">llvm::MCJIT::generateCodeForModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a54233894e754c548da87c0d21d69003d">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDWOContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a94a67b1b1afd0088aecc47ddcc329096">llvm::orc::getObjectFileInterface</a>, <a href="/web-llvm/docs/api/groups/llvmcobject/#ga0fd9f7bc65117c049c14c047fb7907dc">LLVMCreateObjectFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xray/#aa457a825eb8236aa6f36de72e86109ca">llvm::xray::loadInstrumentationMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a05b4c070c172287759f5f2f437a3edcb">llvm::cgdata::mergeCodeGenData</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/forceloadmachoarchivemembers/#aafbc2404a509204e5983e140d1038581">llvm::orc::ForceLoadMachOArchiveMembers::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/simplecompiler/#a603ecdc5d1b7bfa7d9408896489ca31d">llvm::orc::SimpleCompiler::operator()</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a0756e89d8eafc4bc2503dd3976765f61">llvm::dwarf_linker::parallel::SectionDescriptor::setSizesForSectionCreatedByAsmPrinter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7363e46d4dd6c78affffabaea0de482b">llvm::write</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a995e3c2084bb6204a7496128e9562fc0">llvm::yaml::yaml2ObjectFile</a>.</p>

</div>
</div>

### createObjectFile() {#ac2fa24b430bb715d3519191162e402e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; ObjectFile &gt; &gt; ObjectFile::createObjectFile (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object, <a href="/web-llvm/docs/api/structs/llvm/file-magic">llvm::file_magic</a> Type, bool InitContent=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/object/objectfile-cpp">ObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa35fa482a9a36a65cbd44ed6a98563cd9">llvm::file_magic::archive</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa9b217cf59bac16d57cf52c3e76f3ce50">llvm::file_magic::bitcode</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aabb25bd86fcacafa4654636a3985d0f5e">llvm::file_magic::clang_ast</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aadcfa112d629e18c0a4eed4980ca4a7ae">llvm::file_magic::coff_cl_gl_object</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa007729224f13c224129cef854ce5fc0c">llvm::file_magic::coff_import_library</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aac575f4e16f05741d7656211f860dfcc3">llvm::file_magic::coff_object</a>, <a href="#a3e3b4e38f2043b08c7a0df72bc8bd0f3">createCOFFObjectFile</a>, <a href="#a5ef8ed10341ed52e784b5408bac56424">createELFObjectFile</a>, <a href="#a3bcb896473d4c0e5275a58bf731ee899">createMachOObjectFile</a>, <a href="#a920bb15c9298c61cbd6db1cef2394a82">createWasmObjectFile</a>, <a href="#ad3a58183c0e4b64719f5ffd6ae7a88c3">createXCOFFObjectFile</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aadeb5166eb440a9fc83a3c586223b25e8">llvm::file_magic::cuda_fatbinary</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa8570da074cd02b24514d79e2b84dd600">llvm::file_magic::dxcontainer_object</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aad31db91c55e2f1f5090ddbe652c20b1f">llvm::file_magic::elf</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aabf5672e0a28c6ed1db85035f1b85fc5b">llvm::file_magic::elf_core</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa46a884b4756415ac19d0ac5d2bf56079">llvm::file_magic::elf_executable</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa1b167178973059ff5b3a4b2bf2377450">llvm::file_magic::elf_relocatable</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa380638a0d06dd9003d4dd307f7b0851c">llvm::file_magic::elf_shared_object</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa40ebaa45e99e5d81f24d506e33afdb42">llvm::file_magic::goff_object</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#af4e569b1876c0dbd751c766d6a1b926aaacc1d58eb5b8f54127732d6126d8ae79">llvm::object::Binary::ID_XCOFF32</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#af4e569b1876c0dbd751c766d6a1b926aaf10c5cafe80d2255fee25e3fb79f4069">llvm::object::Binary::ID_XCOFF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a00941e59a16ad6eb14e905557a612501">llvm::identify_magic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20ad5a8a27f4e310ea593b285615faaca35">llvm::object::invalid_file_type</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aad50da1fb17899eb0b0f714edf96c83c7">llvm::file_magic::macho_bundle</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aaa01c66176cb9de4bb75c2b551133e38e">llvm::file_magic::macho_core</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aae40fb5199f3d0b10d917738a06b4b6b0">llvm::file_magic::macho_dsym_companion</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aaea9f98c476ea8892d4bf66157d526cde">llvm::file_magic::macho_dynamic_linker</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa45f3946b8331a826457113aa5d81bc96">llvm::file_magic::macho_dynamically_linked_shared_lib</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa56440a39ccbe80c75e2e674aaafd00d4">llvm::file_magic::macho_dynamically_linked_shared_lib_stub</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aae3fbcf9e4d077fe08e7e73eb785f0a2c">llvm::file_magic::macho_executable</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa75fee6d4cd7dfafcb268524c93b56101">llvm::file_magic::macho_file_set</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aae796c2e08310bfe518ffc166cb788601">llvm::file_magic::macho_fixed_virtual_memory_shared_lib</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa86da0e718a3fbe29422c095c55af3bfa">llvm::file_magic::macho_kext_bundle</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aac557d5088dac1a5cca0c2c7e78174632">llvm::file_magic::macho_object</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa590d298012f657bc6b970e50d9f774c1">llvm::file_magic::macho_preload_executable</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa9afb9b390f3041249d9a2dee384e4c1d">llvm::file_magic::macho_universal_binary</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa41c57613a130abf5992d1e1a16497b04">llvm::file_magic::minidump</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa91e1aaaa67b1f5232dbea39497ef9250">llvm::file_magic::offload_binary</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa5b3ee11ca5b4c14dd6c13ac147d76b77">llvm::file_magic::offload_bundle</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa73165d81a387644aea1856f9a567a23a">llvm::file_magic::offload_bundle_compressed</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa0d7b7082a37cb024864ce149d0b04f5f">llvm::file_magic::pdb</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa906a95690dc1df5a24e4253c83edd77c">llvm::file_magic::pecoff_executable</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa11ec46239073e8ad58f263bedf619cbc">llvm::file_magic::spirv_object</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aafa3f3f16300b9876aa0147b61ca8edaa">llvm::file_magic::tapi_file</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aae5a2f339dd671d3caf9b616ef7bf1efd">llvm::file_magic::unknown</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aaa0dedd1117ef34a81cb4b8751c3c1e4f">llvm::file_magic::wasm_object</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aab93daf35debe3630ad69460b3c1d072a">llvm::file_magic::windows_resource</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aaa39e4e5aa8493605e279d127dc484379">llvm::file_magic::xcoff_object_32</a> and <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa45ff397494885b031c2b6a75797e7d7e">llvm::file_magic::xcoff_object_64</a>.</p>

</div>
</div>

### createObjectFile() {#af476b74fea2b1f162925eb114e5236f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; ObjectFile &gt; &gt; llvm::object::ObjectFile::createObjectFile (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>References <a href="#a926af6aca697fdbacb3e3ea1000f0ec4">createObjectFile</a> and <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aae5a2f339dd671d3caf9b616ef7bf1efd">llvm::file_magic::unknown</a>.</p>

</div>
</div>

### createWasmObjectFile() {#a920bb15c9298c61cbd6db1cef2394a82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; WasmObjectFile &gt; &gt; ObjectFile::createWasmObjectFile (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object)</td>
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



<p>Declaration at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a>.</p>


<p>References <a href="#af74504142c7146b3602a3aa280d07df7">ObjectFile</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#ac2fa24b430bb715d3519191162e402e2">createObjectFile</a>.</p>

</div>
</div>

### createXCOFFObjectFile() {#ad3a58183c0e4b64719f5ffd6ae7a88c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; ObjectFile &gt; &gt; llvm::object::ObjectFile::createXCOFFObjectFile (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object, unsigned FileType)</td>
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



<p>Declaration at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 1232 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>Referenced by <a href="#ac2fa24b430bb715d3519191162e402e2">createObjectFile</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/elfobjectfile-cpp">ELFObjectFile.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/goffobjectfile-cpp">GOFFObjectFile.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/objectfile-cpp">ObjectFile.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/wasmobjectfile-cpp">WasmObjectFile.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
