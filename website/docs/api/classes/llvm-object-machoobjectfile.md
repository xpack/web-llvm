---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/machoobjectfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachOObjectFile` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::object::MachOObjectFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">llvm/Object/MachO.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is the base class for all object file types. <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacc96233a03b5415af48153d8417a6d0">LoadCommandList</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a>, 4 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cd134566640b52e89fc132841db9957">load_command_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aa11b903431c1931920939bac6b5293a2">LoadCommandList::const_iterator</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adba99d28bc29725e8344aca6be237efe">SectionList</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, 1 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eabb81bd4b3b0adf3dd7175b54c32eb">LibraryList</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, 1 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abae0d92590001fca9e7c9fec9f09ca82">LibraryShortName</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, 1 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3152fadccd6582a33555752dc4e5a8ef">BuildToolList</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, 1 &gt;</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaee0791af10d106514068ddf01003e77">MachOObjectFile</a> (MemoryBufferRef Object, bool IsLittleEndian, bool Is64Bits, Error &amp;Err, uint32_t UniversalCputype=0, uint32_t UniversalIndex=0, size_t MachOFilesetEntryOffset=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42eea1d21f273fb22eb18192e519aaaa">moveSymbolNext</a> (DataRefImpl &amp;Symb) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad823d575bb639330180ee9d8b43bf237">getNValue</a> (DataRefImpl Sym) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79ff60972cb2fd27ac7280c9e5052d4a">getSymbolName</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58bd45157985a622dba76ecef6375f4d">checkSymbolTable</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c4dce386c635e9449383a532bc38070">getIndirectName</a> (DataRefImpl Symb, StringRef &amp;Res) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6219972bdae3e9ac0f4daf447f328d82">getSectionType</a> (SectionRef Sec) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb1975d59d60a84adba98e90c59872e8">getSymbolAddress</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad12defbd432cf6bb7f7b05f956681e03">getSymbolAlignment</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b3abf2e75a61284d8e8bd3547234c5d">getCommonSymbolSizeImpl</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfea148e3e5693c88962ce5add39bf56">getSymbolType</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a725d75c745df0f036d8e5fba0670f13d">getSymbolFlags</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35b89b3d8775f01eeeb4e36769e2b435">getSymbolSection</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f79817cbc7f06dd7a434e20281a0ad5">getSymbolSectionID</a> (SymbolRef Symb) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae48752dc6271082d4f4cb2c9db80703d">getSectionID</a> (SectionRef Sec) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a046bf39ae1f6f6cb4bd3f6910e96a9fb">moveSectionNext</a> (DataRefImpl &amp;Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac459e969de113b3d211c0a4087656dc7">getSectionName</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac223e702ae7330bc836e547bf1023278">getSectionAddress</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4273d5ff85c5d9d4e9e4f69ff7f6a0a">getSectionIndex</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0c6e225cf80ae36a9994bd1e79e8655">getSectionSize</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a541a23560ff0dfbe01c6c1c9e4d07801">getSectionContents</a> (uint32_t Offset, uint64_t Size) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9721b8484141c4d955c6830762a072b">getSectionContents</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12de1fc762e4d94c86bbdffd6a472df4">getSectionAlignment</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a18707996459de69e40ab867eeee801">getSection</a> (unsigned SectionIndex) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88e19a85aa8bc06f5b3e51c382dfbb41">getSection</a> (StringRef SectionName) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7eb997befeaee6e33d42a249c694d6c">isSectionCompressed</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7ac740eb18150e6b303020623754638">isSectionText</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f8cd1e7801f694e4a6c5e109b96773c">isSectionData</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7434406d3c7c482b788bf6db4275831b">isSectionBSS</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76ba9d917492e4d238d3d9062d755494">isSectionVirtual</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acba45c9f1c0b5b00a3fe59eae613b4fb">isSectionBitcode</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d343559880ac878c6a999cd0e85517e">isDebugSection</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb68429296d9cd8a13b4aa3f10f2e780">getSegmentContents</a> (StringRef SegmentName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the raw contents of an entire segment. <a href="#adb68429296d9cd8a13b4aa3f10f2e780">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac696b4147be1f37d5b9180fe83371658">getSegmentContents</a> (size_t SegmentIndex) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab046bef50272d4e0d9abf45b017feaaa">isSectionStripped</a> (DataRefImpl Sec) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When dsymutil generates the companion file, it strips all unnecessary sections (e.g. <a href="#ab046bef50272d4e0d9abf45b017feaaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4db2c6874a1695b79e947621f7bad0ad">section_rel_begin</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b4a2cfae548a9a5cf6228605d4c0e7d">section_rel_end</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7ab27ad809711f7ad62636b2f295a01">extrel_begin</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0fde7879a332b4234a4a2a7e59446db">extrel_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d83c0481fc4f1f16888c6d790bfdffb">external_relocations</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad103fd8ebc431f075697c16d4e66f9e8">locrel_begin</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc59d7882fd3b78d7d8bd063816f450d">locrel_end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7ed0f240e545eaf6ff91ed1128637e9">moveRelocationNext</a> (DataRefImpl &amp;Rel) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f4f04d967a4ea26b58a22ab9e211094">getRelocationOffset</a> (DataRefImpl Rel) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19321b2c5a24656fe59c193ae2892453">getRelocationSymbol</a> (DataRefImpl Rel) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0d1a3db809bbb82228bab61d2f5dc27">getRelocationSection</a> (DataRefImpl Rel) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3c891d7b0434f73b2ae7adceed7bcec">getRelocationType</a> (DataRefImpl Rel) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4f7324b39a6386811a1d2202cfe1fed">getRelocationTypeName</a> (DataRefImpl Rel, SmallVectorImpl&lt; char &gt; &amp;Result) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac48a4a2e5b90072e58a7c0e1d200506c">getRelocationLength</a> (DataRefImpl Rel) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afea73c1af002769dde1fb465f40b6ac1">getLibraryShortNameByIndex</a> (unsigned Index, StringRef &amp;) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3247f2fd52f536bdd17fc78c956da43f">getLibraryCount</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73ddbfba78956c4ed1b7c2ab5b816dbb">getRelocationRelocatedSection</a> (relocation_iterator Rel) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a5bf1bfacdebc64c1f70e3b2861ba76eb">basic_symbol_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21f780beb96b3c8859b9f75422e2c4f9">symbol_begin</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a5bf1bfacdebc64c1f70e3b2861ba76eb">basic_symbol_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabf498b6cb34cb967c73e3c0c51baee2">symbol_end</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d7c96e485022e0023e9b8eec0257f0e">getSymbolByIndex</a> (unsigned Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24c6aaf027b70314a4e7cb05b34ab302">getSymbolIndex</a> (DataRefImpl Symb) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56dc12deef303c47e57819035ab2f2f3">section_begin</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a274c4612a46dd1b0aa44ca5745642e2b">section_end</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07de7aaa40f390071913260478a848ca">getBytesInAddress</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of bytes used to represent an address in this object file format. <a href="#a07de7aaa40f390071913260478a848ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a216609c43afe05c3da08214afdc8e72b">getFileFormatName</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c6dd60e5645b2ff160ea7368c04e78f">getArch</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace0518dae7ee126091d84b4dc0a47ed7">getFeatures</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95b14a72437abf5ec6cb9d25596eb3e4">getArchTriple</a> (const char **McpuDefault=nullptr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47b6dea5d2bb082590a6749c9ac51039">section_rel_begin</a> (unsigned Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bc5a3bf6742bc5fddcd83660fa27034">section_rel_end</a> (unsigned Index) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#af4620ab375bb5888039c46622059db6b">dice_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21eb1fb7d7f36d23fdd47f8e7ff0e2f1">begin_dices</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#af4620ab375bb5888039c46622059db6b">dice_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67ca29eb8dc5ee438d5cc11cf5a460d9">end_dices</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7cd134566640b52e89fc132841db9957">load_command_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e9d2dd4b0a109f60a8c056f4031c5d2">begin_load_commands</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7cd134566640b52e89fc132841db9957">load_command_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcf9c2d9ce13a839012103af5556a2c3">end_load_commands</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a7cd134566640b52e89fc132841db9957">load_command_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9397f336b10a2f4db6c6d5a8f9b49224">load_commands</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6a6920b49f954dc26b2d1dbcbfa80b4b">export_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24c45a64b8e2666c4706d4e0c2c1add4">exports</a> (Error &amp;Err) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For use iterating over all exported symbols. <a href="#a24c45a64b8e2666c4706d4e0c2c1add4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a3c8e7f0193995214b73b45fd825be362">rebase_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b87e710017438cefd497bd5ef89fdbe">rebaseTable</a> (Error &amp;Err)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For use iterating over all rebase table entries. <a href="#a1b87e710017438cefd497bd5ef89fdbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a2888e4397a5987e747e43680fba07dc5">bind_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a460d0b147c8ce41bfda4bcb3f20f6061">bindTable</a> (Error &amp;Err)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For use iterating over all bind table entries. <a href="#a460d0b147c8ce41bfda4bcb3f20f6061">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a3b2c359462cc6d31a7b28a741c4613a4">fixup_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5a90ce0e16d404e8c90801cf2d4ee27">fixupTable</a> (Error &amp;Err)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For iterating over all chained fixups. <a href="#ab5a90ce0e16d404e8c90801cf2d4ee27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a2888e4397a5987e747e43680fba07dc5">bind_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb55e4947514d8643390aacdaa4a7736">lazyBindTable</a> (Error &amp;Err)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For use iterating over all lazy bind table entries. <a href="#abb55e4947514d8643390aacdaa4a7736">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a2888e4397a5987e747e43680fba07dc5">bind_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87a504b58d7827fd3f526335f44cc14a">weakBindTable</a> (Error &amp;Err)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For use iterating over all weak bind table entries. <a href="#a87a504b58d7827fd3f526335f44cc14a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a558d3bad6896e4fe3e8626e18e486097">BindEntryCheckSegAndOffsets</a> (int32_t SegIndex, uint64_t SegOffset, uint8_t PointerSize, uint64_t Count=1, uint64_t Skip=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c92441972e6447b39be377ed4e70c3b">RebaseEntryCheckSegAndOffsets</a> (int32_t SegIndex, uint64_t SegOffset, uint8_t PointerSize, uint64_t Count=1, uint64_t Skip=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa44cc41eb3939d32f17399ad60f442c3">BindRebaseSegmentName</a> (int32_t SegIndex) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For use with the SegIndex of a checked Mach-O Bind or Rebase entry to get the segment name. <a href="#aa44cc41eb3939d32f17399ad60f442c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb0f0e5f4f7f97a7dd98bcb87632e922">BindRebaseSectionName</a> (uint32_t SegIndex, uint64_t SegOffset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For use with a SegIndex,SegOffset pair from a checked Mach-O Bind or Rebase entry to get the section name. <a href="#abb0f0e5f4f7f97a7dd98bcb87632e922">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bddda3bfa43acf097acd33ab73accc8">BindRebaseAddress</a> (uint32_t SegIndex, uint64_t SegOffset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For use with a SegIndex,SegOffset pair from a checked Mach-O Bind or Rebase entry to get the address. <a href="#a9bddda3bfa43acf097acd33ab73accc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a647f0ec13a56dcdcf59ff036090db193">getSectionFinalSegmentName</a> (DataRefImpl Sec) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad79e64ea14a6d005ca27139d6737066f">getSectionRawName</a> (DataRefImpl Sec) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0753fcaceabb5cf8f772cae836fe945b">getSectionRawFinalSegmentName</a> (DataRefImpl Sec) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad07c873a9197ed022e779129f28ca028">isRelocationScattered</a> (const MachO::any_relocation_info &amp;RE) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99471e40aa719f7de1a81c38b8b129cc">getPlainRelocationSymbolNum</a> (const MachO::any_relocation_info &amp;RE) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bec3ca52f60d7ca088f0634a2e8f779">getPlainRelocationExternal</a> (const MachO::any_relocation_info &amp;RE) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77b819d412646ba61fca1a45e57a5a7c">getScatteredRelocationScattered</a> (const MachO::any_relocation_info &amp;RE) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3144dc7cc061533970cd9681fbbc907a">getScatteredRelocationValue</a> (const MachO::any_relocation_info &amp;RE) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17bc598aa230859797b75db2fe68ac4b">getScatteredRelocationType</a> (const MachO::any_relocation_info &amp;RE) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad388361f228398a0d6ccd304f88138fa">getAnyRelocationAddress</a> (const MachO::any_relocation_info &amp;RE) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86eeaa5626787e6a0c62d7fef9ea33e9">getAnyRelocationPCRel</a> (const MachO::any_relocation_info &amp;RE) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a942691b0e7a01c33a7aa6b36b28472d2">getAnyRelocationLength</a> (const MachO::any_relocation_info &amp;RE) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a653a63105b842dd49a3a0921ce6a6d66">getAnyRelocationType</a> (const MachO::any_relocation_info &amp;RE) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43739eb6bed0aa4dc4ac7c50de26674b">getAnyRelocationSection</a> (const MachO::any_relocation_info &amp;RE) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/section">MachO::section</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd858c258a4333c61658e66fcbbaa9e7">getSection</a> (DataRefImpl DRI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/section-64">MachO::section_64</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ddf638fa2c882a669517ae17a4e032a">getSection64</a> (DataRefImpl DRI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/section">MachO::section</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4916f4a65ce359c50389bc77a5689f7a">getSection</a> (const LoadCommandInfo &amp;L, unsigned Index) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/section-64">MachO::section_64</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa868c47bf47a793dbd158c31f3d9864e">getSection64</a> (const LoadCommandInfo &amp;L, unsigned Index) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/nlist">MachO::nlist</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2df84b6031947d33d436f49b29a699b2">getSymbolTableEntry</a> (DataRefImpl DRI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/nlist-64">MachO::nlist_64</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62195bc7e86a573ecebe708bee210b61">getSymbol64TableEntry</a> (DataRefImpl DRI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command">MachO::linkedit_data_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae669e6342a3406842cda2714f1f143c9">getLinkeditDataLoadCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/segment-command">MachO::segment_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6317d38843b3ac79b92a3c85bb2ed7b5">getSegmentLoadCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/segment-command-64">MachO::segment_command_64</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b1695c0e56a3fd6bcefcaccb8b9dab6">getSegment64LoadCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/linker-option-command">MachO::linker_option_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31b3a7bf8a638884321a2df0f787fe05">getLinkerOptionLoadCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/version-min-command">MachO::version_min_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d29d7cb48a7f246f1c0f4507def2aa7">getVersionMinLoadCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/note-command">MachO::note_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a527b022bfecb5185b104f66bb26ce3c6">getNoteLoadCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/build-version-command">MachO::build_version_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2576066f592129dbe8f9624c90bf19ef">getBuildVersionLoadCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/build-tool-version">MachO::build_tool_version</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ab44ec13134d5fef903151e368f3c8a">getBuildToolVersion</a> (unsigned index) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/dylib-command">MachO::dylib_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb9478037b0d4a28a04ad1d690e2f645">getDylibIDLoadCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command">MachO::dyld_info_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a708244b1c588ce222e471dd17719b9b5">getDyldInfoLoadCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/dylinker-command">MachO::dylinker_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1db3c0b49113ff3627eb1ecd2f7b477">getDylinkerCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/uuid-command">MachO::uuid_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a983feccca34dfdfebe0d79c35c166d7d">getUuidCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/rpath-command">MachO::rpath_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66f24d7c05980ed733c32c31f099766d">getRpathCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/source-version-command">MachO::source_version_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad17a0cc5e558e81985224344a3dd57bb">getSourceVersionCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/entry-point-command">MachO::entry_point_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a352e221c16019d6045da26a3209e40c4">getEntryPointCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/encryption-info-command">MachO::encryption_info_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a806af0cdf9cc3ef071e2a103dad08e31">getEncryptionInfoCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/encryption-info-command-64">MachO::encryption_info_command_64</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1feb8b357acb0ed676d8b4a1954c5623">getEncryptionInfoCommand64</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/sub-framework-command">MachO::sub_framework_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c0b621a228e683bf4590229691489aa">getSubFrameworkCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/sub-umbrella-command">MachO::sub_umbrella_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70b068a5ae812db11c38e8b8dc23617b">getSubUmbrellaCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/sub-library-command">MachO::sub_library_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f9c9811944d064d439d7c5d9bf64cd5">getSubLibraryCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/sub-client-command">MachO::sub_client_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a023569a7035ef18e014f39cc2800ad07">getSubClientCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/routines-command">MachO::routines_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2badd591726f82a2e5942e44907c80ec">getRoutinesCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/routines-command-64">MachO::routines_command_64</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b01323aa4c54564eeef35c5cf7d0151">getRoutinesCommand64</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/thread-command">MachO::thread_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53d6fbb63f40bcf11cf7e5d674534440">getThreadCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/fileset-entry-command">MachO::fileset_entry_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5203f8a41fa3b6a2e3cbc8949c1fc962">getFilesetEntryLoadCommand</a> (const LoadCommandInfo &amp;L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaacf649b0759051f6c5327e44b82f8aa">getRelocation</a> (DataRefImpl Rel) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/data-in-code-entry">MachO::data_in_code_entry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafff2e6b7435d209427acf5ab83bf375">getDice</a> (DataRefImpl Rel) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/mach-header">MachO::mach_header</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80dc9af48926f9c1b70075f71c6002a7">getHeader</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/mach-header-64">MachO::mach_header_64</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10ac2a63f6a950994aae39057eeca34a">getHeader64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0479ec0a64582d6ad2df6f5231beae3">getIndirectSymbolTableEntry</a> (const MachO::dysymtab_command &amp;DLC, unsigned Index) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/data-in-code-entry">MachO::data_in_code_entry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf48787fae336569ae8e87a4a645174b">getDataInCodeTableEntry</a> (uint32_t DataOffset, unsigned Index) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command">MachO::symtab_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9451d5e767c3b97403785baaff3c6a44">getSymtabLoadCommand</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command">MachO::dysymtab_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4479f956205d53f462400c0f9e98674a">getDysymtabLoadCommand</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command">MachO::linkedit_data_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b03ad21c736b26f5396403bf49f2a59">getDataInCodeLoadCommand</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command">MachO::linkedit_data_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64bfe87a4a35f817e902fc4c3c50f5d2">getLinkOptHintsLoadCommand</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bf468d783b97cfaf64cce155ccc9365">getDyldInfoRebaseOpcodes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abee9da1b8caf9806998dc3fbc8fa02be">getDyldInfoBindOpcodes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6987c2142793b0d0eb897b4eb2c2712">getDyldInfoWeakBindOpcodes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a428c19e380ff63f21f2bfb4fdf0078b5">getDyldInfoLazyBindOpcodes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d2c48586c800c9f29be71be14da45cf">getDyldInfoExportsTrie</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-chained-fixups-header">MachO::dyld_chained_fixups_header</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad107a2e9bf01094f9564019267eace1d">getChainedFixupsHeader</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the optional is std::nullopt, no header was found, but the object was well-formed. <a href="#ad107a2e9bf01094f9564019267eace1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/object/chainedfixuptarget">ChainedFixupTarget</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11261ec56e31921149aa022482d80e7e">getDyldChainedFixupTargets</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command">MachO::linkedit_data_command</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a226f358d6c1305cdba13949825b60b49">getChainedFixupsLoadCommand</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::pair&lt; size_t, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/object/chainedfixupssegment">ChainedFixupsSegment</a> &gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a766c3350d64dde8af24ef7b600b11185">getChainedFixupsSegments</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7107ae3ee300f48f02997f50fe543c0f">getDyldExportsTrie</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e304ff95b5d1ea04529da35d5307d6f">getFunctionStarts</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99d3e689123b378a1d01ac234f9a6d3c">getUuid</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad451ffea9d6ef1b5ec634f176bf6dcad">getStringTableData</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6717ca91fe3922480a18f3e4250e611">ReadULEB128s</a> (uint64_t Index, SmallVectorImpl&lt; uint64_t &gt; &amp;Out) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5960f71b19779a8db394bae2c9be62c9">isRelocatableObject</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this is a relocatable object (.o/.obj). <a href="#a5960f71b19779a8db394bae2c9be62c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ebf76d221187db6bf7395a664923d80">mapDebugSectionName</a> (StringRef Name) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps a debug section name to a standard DWARF section name. <a href="#a9ebf76d221187db6bf7395a664923d80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/binaryformat/#ab355a2b14b4cc35373b4526fbfab894d">llvm::binaryformat::Swift5ReflectionSectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5d1811aaaa04d131a3a65d89888aab1">mapReflectionSectionNameToEnumValue</a> (StringRef SectionName) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3e05b2d5f00c589ed0d5a9e24c2be59">hasPageZeroSegment</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb95a0420b2442e27f0b4023926c72fe">getMachOFilesetEntryOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52a23ba1858dc6655a925ed1df3db27d">getSymbolValueImpl</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/mach-header-64">MachO::mach_header_64</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d6204611b3f1b7f9772b6165a8f91b8">Header64</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/mach-header">MachO::mach_header</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4883a0c75b5154762599156fc1d27ab2">Header</a></td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">llvm::object::MachOObjectFile</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa385e63c4c044f9d7f5028113fd10f3"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SectionList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accb56f5e84bdfa748cd34ffabe118ac8">Sections</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">LibraryList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedd60923ff3eb57477ea87f1acbc93c2">Libraries</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aacc96233a03b5415af48153d8417a6d0">LoadCommandList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a047861b536671547faaab1f5925a0c23">LoadCommands</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">BuildToolList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaad1be53fc2557587f32945ea335e2d7">BuildTools</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">LibraryShortName</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa3661f61ae4762ac09ec2197e137a08">LibrariesShortNames</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/bindrebaseseginfo">BindRebaseSegInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7537115abb16fb59a59be6af5ba1a74">BindRebaseSectionTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af86f04d226c003ea3ab91c2c90adc32f">SymtabLoadCmd</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b6d2e8189483a02f909be96679b3a81">DysymtabLoadCmd</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45e837ae756c7f16f813255560242005">DataInCodeLoadCmd</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5849dbc8b10e85eaa710c3723b5204cf">LinkOptHintsLoadCmd</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13ca873ebf0c98a47176931013683676">DyldInfoLoadCmd</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f3936e7e894d0ac9bde970f10e30b26">FuncStartsLoadCmd</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a128ebb7c3505862dd45a1752073c4567">DyldChainedFixupsLoadCmd</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a868b5efb596a0e505e5c83ccac4f9cb7">DyldExportsTrieLoadCmd</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a890a10e92635d4b99d4cefa380d17fa0">UuidLoadCmd</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53c7ba241f612d3d35fb621156c2d0eb">HasPageZeroSegment</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51052c5845d2c56e06e9193b8f1e6248">MachOFilesetEntryOffset</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6456a8f4d04f36afe434911ec571ba3a">create</a> (MemoryBufferRef Object, bool IsLittleEndian, bool Is64Bits, uint32_t UniversalCputype=0, uint32_t UniversalIndex=0, size_t MachOFilesetEntryOffset=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bb417c5fd462f13301f4def55f0c49b">isMachOPairedReloc</a> (uint64_t RelocType, uint64_t Arch)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6a6920b49f954dc26b2d1dbcbfa80b4b">export_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99ce62ce3455a7a99df0daaee4fd516e">exports</a> (Error &amp;Err, ArrayRef&lt; uint8_t &gt; Trie, const MachOObjectFile *O=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For use examining a trie not in a <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a>. <a href="#a99ce62ce3455a7a99df0daaee4fd516e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a3c8e7f0193995214b73b45fd825be362">rebase_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec8303f38ce8e043a58bf1818abb1da3">rebaseTable</a> (Error &amp;Err, MachOObjectFile *O, ArrayRef&lt; uint8_t &gt; Opcodes, bool is64)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For use examining rebase opcodes in a <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a>. <a href="#aec8303f38ce8e043a58bf1818abb1da3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a2888e4397a5987e747e43680fba07dc5">bind_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af83dd79fbd25f72be320a930b92eb146">bindTable</a> (Error &amp;Err, MachOObjectFile *O, ArrayRef&lt; uint8_t &gt; Opcodes, bool is64, MachOBindEntry::Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For use examining bind opcodes in a <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a>. <a href="#af83dd79fbd25f72be320a930b92eb146">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3e1bca92860141baaad0a536334d09f">guessLibraryShortName</a> (StringRef Name, bool &amp;isFramework, StringRef &amp;Suffix)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154">Triple::ArchType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5c6a0f3fd86301240cc7cbe9b2a1716">getArch</a> (uint32_t CPUType, uint32_t CPUSubType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12d459ca91f226639852d575af2f1f36">getArchTriple</a> (uint32_t CPUType, uint32_t CPUSubType, const char **McpuDefault=nullptr, const char **ArchFlag=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac74a3d3d939d03f7aaf8984924636f5a">isValidArch</a> (StringRef ArchFlag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac81b6bccdec58d66ed395f5754e5ee31">getValidArchs</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dae944f91922455073b3d3d90ca8182">getHostArch</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6164075d58acb937a7ca44edd9bdbba1">classof</a> (const Binary *v)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe73c477bf18bd1868cba1bff6c10f45">getVersionMinMajor</a> (MachO::version_min_command &amp;C, bool SDK)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7cb36c89b950fb13e0e652288410677">getVersionMinMinor</a> (MachO::version_min_command &amp;C, bool SDK)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90e87895af41ed29b6da842bff759177">getVersionMinUpdate</a> (MachO::version_min_command &amp;C, bool SDK)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58d6e199af0293405aecbdd473952c07">getBuildPlatform</a> (uint32_t platform)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a535da955115db82b34074588a172b401">getBuildTool</a> (uint32_t tools)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0751fcfc33e532271437039379f8a72d">getVersionString</a> (uint32_t version)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; std::string &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a301ba38f5a267f3cf123d6a9f551e3fd">findDsymObjectMembers</a> (StringRef Path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the input path is a .dSYM bundle (as created by the dsymutil tool), return the paths to the object files found in the bundle, otherwise return an empty vector. <a href="#a301ba38f5a267f3cf123d6a9f551e3fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### load\_command\_iterator {#a7cd134566640b52e89fc132841db9957}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::object::MachOObjectFile::load_command_iterator =  LoadCommandList::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### LoadCommandList {#aacc96233a03b5415af48153d8417a6d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::object::MachOObjectFile::LoadCommandList =  SmallVector&lt;LoadCommandInfo, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### BuildToolList {#a3152fadccd6582a33555752dc4e5a8ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::object::MachOObjectFile::BuildToolList =  SmallVector&lt;const char*, 1&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 858 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### LibraryList {#a1eabb81bd4b3b0adf3dd7175b54c32eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::object::MachOObjectFile::LibraryList =  SmallVector&lt;const char*, 1&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 854 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### LibraryShortName {#abae0d92590001fca9e7c9fec9f09ca82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::object::MachOObjectFile::LibraryShortName =  SmallVector&lt;StringRef, 1&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 857 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### SectionList {#adba99d28bc29725e8344aca6be237efe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::object::MachOObjectFile::SectionList =  SmallVector&lt;const char*, 1&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 852 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### MachOObjectFile() {#aaee0791af10d106514068ddf01003e77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachOObjectFile::MachOObjectFile (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object, bool IsLittleEndian, bool Is64Bits, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err, uint32_t UniversalCputype=0, uint32_t UniversalIndex=0, size_t MachOFilesetEntryOffset=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 841 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1267 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin\_dices() {#a21eb1fb7d7f36d23fdd47f8e7ff0e2f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dice_iterator MachOObjectFile::begin_dices ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 528 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2900 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a718c920e2473631759319ce93d069224">llvm::MachO::linkedit_data_command::dataoff</a>, <a href="#a2b03ad21c736b26f5396403bf49f2a59">getDataInCodeLoadCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>.</p>

</div>
</div>

### begin\_load\_commands() {#a1e9d2dd4b0a109f60a8c056f4031c5d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachOObjectFile::load_command_iterator MachOObjectFile::begin_load_commands ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4505 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Referenced by <a href="#a9397f336b10a2f4db6c6d5a8f9b49224">load_commands</a>.</p>

</div>
</div>

### BindEntryCheckSegAndOffsets() {#a558d3bad6896e4fe3e8626e18e486097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::object::MachOObjectFile::BindEntryCheckSegAndOffsets (int32_t SegIndex, uint64_t SegOffset, uint8_t PointerSize, uint64_t Count=1, uint64_t Skip=0)</td>
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



<p>Definition at line 578 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>.</p>

</div>
</div>

### BindRebaseAddress() {#a9bddda3bfa43acf097acd33ab73accc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::MachOObjectFile::BindRebaseAddress (uint32_t SegIndex, uint64_t SegOffset)</td>
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

<p>For use with a SegIndex,SegOffset pair from a checked Mach-O Bind or Rebase entry to get the address.</p>

<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### BindRebaseSectionName() {#abb0f0e5f4f7f97a7dd98bcb87632e922}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::MachOObjectFile::BindRebaseSectionName (uint32_t SegIndex, uint64_t SegOffset)</td>
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

<p>For use with a SegIndex,SegOffset pair from a checked Mach-O Bind or Rebase entry to get the section name.</p>

<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### BindRebaseSegmentName() {#aa44cc41eb3939d32f17399ad60f442c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::MachOObjectFile::BindRebaseSegmentName (int32_t SegIndex)</td>
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

<p>For use with the SegIndex of a checked Mach-O Bind or Rebase entry to get the segment name.</p>

<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### bindTable() {#a460d0b147c8ce41bfda4bcb3f20f6061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; bind_iterator &gt; MachOObjectFile::bindTable (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For use iterating over all bind table entries.</p>

<p>Declaration at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4476 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a460d0b147c8ce41bfda4bcb3f20f6061">bindTable</a>, <a href="#abee9da1b8caf9806998dc3fbc8fa02be">getDyldInfoBindOpcodes</a>, <a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machobindentry/#af6efd0f55e33298ac3bb484e6fd285b9ad2203cb1237cb6460cbad94564e39345">llvm::object::MachOBindEntry::Regular</a>.</p>


<p>Referenced by <a href="#a460d0b147c8ce41bfda4bcb3f20f6061">bindTable</a>, <a href="#abb55e4947514d8643390aacdaa4a7736">lazyBindTable</a> and <a href="#a87a504b58d7827fd3f526335f44cc14a">weakBindTable</a>.</p>

</div>
</div>

### checkSymbolTable() {#a58bd45157985a622dba76ecef6375f4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error MachOObjectFile::checkSymbolTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1701 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a8566ffd52ce0223e6ecc4298a438a721a0845826f0be2fbf47be46290a2bded80">llvm::MachO::DYNAMIC_LOOKUP_ORDINAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a8566ffd52ce0223e6ecc4298a438a721a2adaaf2b1acccf88b087ac41ed13bcce">llvm::MachO::EXECUTABLE_ORDINAL</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/mach-header-64/#a42d75dff6103d71fe474dfc632f109b1">llvm::MachO::mach_header_64::flags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad542dcc84df3390f761dc009bc210314">llvm::MachO::GET_LIBRARY_ORDINAL</a>, <a href="#a80dc9af48926f9c1b70075f71c6002a7">getHeader</a>, <a href="#a10ac2a63f6a950994aae39057eeca34a">getHeader64</a>, <a href="#a62195bc7e86a573ecebe708bee210b61">getSymbol64TableEntry</a>, <a href="#a2df84b6031947d33d436f49b29a699b2">getSymbolTableEntry</a>, <a href="#a9451d5e767c3b97403785baaff3c6a44">getSymtabLoadCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a8160a3004ff47f73b842d7030269ff3d">malformedError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a56796c840e08337bb5693b43bf17360cada9b108f24a668805e4bfc6601bd4d75">llvm::MachO::MH_TWOLEVEL</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/nlist/#a8473c3c8e304856e9f2704b8be1b4734">llvm::MachO::nlist::n_desc</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/nlist-64/#a06ff8e022e126707d83810b5d1138cca">llvm::MachO::nlist_64::n_desc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaca65700aad8ca31abbb94cbb03227eda906620a6f5df2e39717dac5f1473a77a">llvm::MachO::N_INDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaca65700aad8ca31abbb94cbb03227eda739c70e797ce66fa3ac7f96e706a83bd">llvm::MachO::N_PBUD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaca65700aad8ca31abbb94cbb03227eda149563e67229adecb388a1b15854f767">llvm::MachO::N_SECT</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/nlist/#a5468d1804ddc635820832f02d7bf7c5a">llvm::MachO::nlist::n_sect</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/nlist-64/#afe00b9ecf44263e4aad98731443ab37e">llvm::MachO::nlist_64::n_sect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad152fa3b2aff735d4a2e4b644dc93b11afa536dc3de031dfd52aaa5c24691b947">llvm::MachO::N_STAB</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/nlist/#a478ec9d36bc75b1c89f127dd395eafe1">llvm::MachO::nlist::n_strx</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/nlist-64/#ac6cf99f4c9bcde21f534e3d4b3242432">llvm::MachO::nlist_64::n_strx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad152fa3b2aff735d4a2e4b644dc93b11a6d2d703f3e79b6904f129d79b5915e7e">llvm::MachO::N_TYPE</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/nlist/#a9128e432ae33ec6c31b0ebada0a07e4f">llvm::MachO::nlist::n_type</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/nlist-64/#af8d09a42c01cccf166ea43186af49ddf">llvm::MachO::nlist_64::n_type</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaca65700aad8ca31abbb94cbb03227edac444d073d7dfae9ee37913c3ebc18fa9">llvm::MachO::N_UNDF</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/nlist/#acec4c4087a1b624eee980b047995c7a7">llvm::MachO::nlist::n_value</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/nlist-64/#ae1b50af87c0e7cc2c7a2dcb4429cef4d">llvm::MachO::nlist_64::n_value</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#a1459968fe2ad55b364958070dde70c6e">llvm::MachO::symtab_command::strsize</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a23fe52bbc164a30ba18e057d37bd2283">llvm::object::ObjectFile::SymbolRef</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aa22a9825f4937b28269552f5b8db4a69">llvm::object::ObjectFile::symbols</a>.</p>

</div>
</div>

### end\_dices() {#a67ca29eb8dc5ee438d5cc11cf5a460d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dice_iterator MachOObjectFile::end_dices ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2910 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a718c920e2473631759319ce93d069224">llvm::MachO::linkedit_data_command::dataoff</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a7d4425eb797faa587c5634883588c45d">llvm::MachO::linkedit_data_command::datasize</a>, <a href="#a2b03ad21c736b26f5396403bf49f2a59">getDataInCodeLoadCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>.</p>

</div>
</div>

### end\_load\_commands() {#abcf9c2d9ce13a839012103af5556a2c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachOObjectFile::load_command_iterator MachOObjectFile::end_load_commands ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4510 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Referenced by <a href="#a9397f336b10a2f4db6c6d5a8f9b49224">load_commands</a>.</p>

</div>
</div>

### exports() {#a24c45a64b8e2666c4706d4e0c2c1add4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; export_iterator &gt; MachOObjectFile::exports (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For use iterating over all exported symbols.</p>

<p>Declaration at line 536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3241 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a24c45a64b8e2666c4706d4e0c2c1add4">exports</a>, <a href="#a7107ae3ee300f48f02997f50fe543c0f">getDyldExportsTrie</a> and <a href="#a5d2c48586c800c9f29be71be14da45cf">getDyldInfoExportsTrie</a>.</p>


<p>Referenced by <a href="#a24c45a64b8e2666c4706d4e0c2c1add4">exports</a> and <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a2ca546a54409cdfc98988096faaa1674">readSymbols</a>.</p>

</div>
</div>

### external\_relocations() {#a7d83c0481fc4f1f16888c6d790bfdffb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; relocation_iterator &gt; llvm::object::MachOObjectFile::external_relocations ()</td>
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



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>References <a href="#aa7ab27ad809711f7ad62636b2f295a01">extrel_begin</a>, <a href="#af0fde7879a332b4234a4a2a7e59446db">extrel_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### extrel\_begin() {#aa7ab27ad809711f7ad62636b2f295a01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">relocation_iterator MachOObjectFile::extrel_begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2199 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a198fe5e1de4053e999d41555cb796801">llvm::object::ObjectFile::RelocationRef</a>.</p>


<p>Referenced by <a href="#a7d83c0481fc4f1f16888c6d790bfdffb">external_relocations</a>.</p>

</div>
</div>

### extrel\_end() {#af0fde7879a332b4234a4a2a7e59446db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">relocation_iterator MachOObjectFile::extrel_end ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2207 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a4479f956205d53f462400c0f9e98674a">getDysymtabLoadCommand</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a198fe5e1de4053e999d41555cb796801">llvm::object::ObjectFile::RelocationRef</a>.</p>


<p>Referenced by <a href="#a7d83c0481fc4f1f16888c6d790bfdffb">external_relocations</a>.</p>

</div>
</div>

### fixupTable() {#ab5a90ce0e16d404e8c90801cf2d4ee27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; fixup_iterator &gt; MachOObjectFile::fixupTable (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For iterating over all chained fixups.</p>

<p>Declaration at line 557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4491 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a6babc84320fb3f2fa66c109c58c8b1f2">llvm::object::MachOChainedFixupEntry::moveToEnd</a>.</p>

</div>
</div>

### getAnyRelocationAddress() {#ad388361f228398a0d6ccd304f88138fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachOObjectFile::getAnyRelocationAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a> &amp; RE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 640 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4578 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a737f9117ad9ecb54eff89ae39cc5e0c1">getPlainRelocationAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a922ba9d09d115911235efb6e517b5ef9">getScatteredRelocationAddress</a> and <a href="#ad07c873a9197ed022e779129f28ca028">isRelocationScattered</a>.</p>


<p>Referenced by <a href="#a3f4f04d967a4ea26b58a22ab9e211094">getRelocationOffset</a>.</p>

</div>
</div>

### getAnyRelocationLength() {#a942691b0e7a01c33a7aa6b36b28472d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachOObjectFile::getAnyRelocationLength (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a> &amp; RE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 642 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4592 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a5bfc08d3a7440ea1dd3d51785b5d3667">getPlainRelocationLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a53ac15ba730cd5a7e82f50b6bc1bf715">getScatteredRelocationLength</a> and <a href="#ad07c873a9197ed022e779129f28ca028">isRelocationScattered</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#abaf648d88dc891045a7cd0e989789370">llvm::RuntimeDyldMachO::getRelocationEntry</a>, <a href="#ac48a4a2e5b90072e58a7c0e1d200506c">getRelocationLength</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#a731c45f6ccf4dde3198c1d5147c3cb37">llvm::RuntimeDyldMachOAArch64::processRelocationRef</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#acb7257d8eec274d18e7916a0d552a2d7">llvm::RuntimeDyldMachO::processScatteredVANILLA</a>.</p>

</div>
</div>

### getAnyRelocationPCRel() {#a86eeaa5626787e6a0c62d7fef9ea33e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachOObjectFile::getAnyRelocationPCRel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a> &amp; RE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 641 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4585 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a7c487242e400b912bb74ac8cdfc4b299">getPlainRelocationPCRel</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#ad6a5d311edf7adea28255db07dd3fc7d">getScatteredRelocationPCRel</a> and <a href="#ad07c873a9197ed022e779129f28ca028">isRelocationScattered</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#abaf648d88dc891045a7cd0e989789370">llvm::RuntimeDyldMachO::getRelocationEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#a731c45f6ccf4dde3198c1d5147c3cb37">llvm::RuntimeDyldMachOAArch64::processRelocationRef</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#acb7257d8eec274d18e7916a0d552a2d7">llvm::RuntimeDyldMachO::processScatteredVANILLA</a>.</p>

</div>
</div>

### getAnyRelocationSection() {#a43739eb6bed0aa4dc4ac7c50de26674b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionRef MachOObjectFile::getAnyRelocationSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a> &amp; RE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 644 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4608 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>, <a href="#a7bec3ca52f60d7ca088f0634a2e8f779">getPlainRelocationExternal</a>, <a href="#a99471e40aa719f7de1a81c38b8b129cc">getPlainRelocationSymbolNum</a>, <a href="#ad07c873a9197ed022e779129f28ca028">isRelocationScattered</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a5155210832b813b1bb19b1830cad62b5a8e5d4596866c51a629410a34e5530503">llvm::MachO::R_ABS</a>, <a href="#a274c4612a46dd1b0aa44ca5745642e2b">section_end</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a>.</p>


<p>Referenced by <a href="#ae0d1a3db809bbb82228bab61d2f5dc27">getRelocationSection</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ac01d9cc5d2d4a3b6662c7096e54bf8ad">llvm::RuntimeDyldMachO::getRelocationValueRef</a>.</p>

</div>
</div>

### getAnyRelocationType() {#a653a63105b842dd49a3a0921ce6a6d66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachOObjectFile::getAnyRelocationType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a> &amp; RE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4600 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a20d9592bf3c885c6afab008b7bb1789e">getPlainRelocationType</a>, <a href="#a17bc598aa230859797b75db2fe68ac4b">getScatteredRelocationType</a> and <a href="#ad07c873a9197ed022e779129f28ca028">isRelocationScattered</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp/#a3ebc7dd21b6e9c9781e5ac3e5d9b604e">extractSections</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#abaf648d88dc891045a7cd0e989789370">llvm::RuntimeDyldMachO::getRelocationEntry</a>, <a href="#aa3c891d7b0434f73b2ae7adceed7bcec">getRelocationType</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#a731c45f6ccf4dde3198c1d5147c3cb37">llvm::RuntimeDyldMachOAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#ad0cc2b7a34912033f88c7169756683cb">llvm::RuntimeDyldMachOARM::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoi386/#a5bd3ae889a8d52356bd6b32e45c7aa6c">llvm::RuntimeDyldMachOI386::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#a59ad91c5ccf9ed8867eab9cc5424b151">llvm::RuntimeDyldMachOX86_64::processRelocationRef</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#acb7257d8eec274d18e7916a0d552a2d7">llvm::RuntimeDyldMachO::processScatteredVANILLA</a>.</p>

</div>
</div>

### getArch() {#a0c6dd60e5645b2ff160ea7368c04e78f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::ArchType MachOObjectFile::getArch ()</td>
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



<p>Declaration at line 519 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2880 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a0c6dd60e5645b2ff160ea7368c04e78f">getArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#afae525cefbe3d0179a73a5ffb555160b">getCPUSubType</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#ae148cedd3b13337408aac7949e546eb9">getCPUType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a93afe3b7548a63fa4d20b50bedb0a61a">llvm::orc::checkMachORelocatableObject</a>, <a href="#a0c6dd60e5645b2ff160ea7368c04e78f">getArch</a> and <a href="#ad4f7324b39a6386811a1d2202cfe1fed">getRelocationTypeName</a>.</p>

</div>
</div>

### getArchTriple() {#a95b14a72437abf5ec6cb9d25596eb3e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple MachOObjectFile::getArchTriple (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char ** McpuDefault=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2884 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a95b14a72437abf5ec6cb9d25596eb3e4">getArchTriple</a> and <a href="#a4883a0c75b5154762599156fc1d27ab2">Header</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/slice/#abc9b876b08cdf5b2ec2c2bb13fbf4f65">llvm::object::Slice::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machouniversalbinary/objectforarch/#abaea5e82b5b7435949a1cd306c8ac5dc">llvm::object::MachOUniversalBinary::ObjectForArch::getArchFlagName</a>, <a href="#a95b14a72437abf5ec6cb9d25596eb3e4">getArchTriple</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machouniversalbinary/objectforarch/#a79de806c9c6530296a79c279603c4ea0">llvm::object::MachOUniversalBinary::ObjectForArch::getTriple</a>.</p>

</div>
</div>

### getBuildToolVersion() {#a2ab44ec13134d5fef903151e368f3c8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::build_tool_version MachOObjectFile::getBuildToolVersion (unsigned index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 669 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4690 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>

</div>
</div>

### getBuildVersionLoadCommand() {#a2576066f592129dbe8f9624c90bf19ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::build_version_command MachOObjectFile::getBuildVersionLoadCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 667 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4685 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#ab42803a7054d1210223d0e72ec575d22">constructTriples</a>.</p>

</div>
</div>

### getBytesInAddress() {#a07de7aaa40f390071913260478a848ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t MachOObjectFile::getBytesInAddress ()</td>
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

<p>The number of bytes used to represent an address in this object file format.</p>

<p>Declaration at line 516 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2655 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a>.</p>

</div>
</div>

### getChainedFixupsHeader() {#ad107a2e9bf01094f9564019267eace1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::optional&lt; MachO::dyld_chained_fixups_header &gt; &gt; MachOObjectFile::getChainedFixupsHeader ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the optional is std::nullopt, no header was found, but the object was well-formed.</p>

<p>Declaration at line 727 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4998 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a718c920e2473631759319ce93d069224">llvm::MachO::linkedit_data_command::dataoff</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a7d4425eb797faa587c5634883588c45d">llvm::MachO::linkedit_data_command::datasize</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-chained-fixups-header/#acb5495744412094d91b463b61fe6b442">llvm::MachO::dyld_chained_fixups_header::fixups_version</a>, <a href="#a226f358d6c1305cdba13949825b60b49">getChainedFixupsLoadCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-chained-fixups-header/#a267bb8c08a7c01b613017b6abbc4f5d8">llvm::MachO::dyld_chained_fixups_header::imports_format</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a8160a3004ff47f73b842d7030269ff3d">malformedError</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-chained-fixups-header/#ab1d84db8570cf688b0f2554c7c832f9d">llvm::MachO::dyld_chained_fixups_header::starts_offset</a>.</p>


<p>Referenced by <a href="#a766c3350d64dde8af24ef7b600b11185">getChainedFixupsSegments</a> and <a href="#a11261ec56e31921149aa022482d80e7e">getDyldChainedFixupTargets</a>.</p>

</div>
</div>

### getChainedFixupsLoadCommand() {#a226f358d6c1305cdba13949825b60b49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::optional&lt; MachO::linkedit_data_command &gt; &gt; MachOObjectFile::getChainedFixupsLoadCommand ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 733 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4979 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a718c920e2473631759319ce93d069224">llvm::MachO::linkedit_data_command::dataoff</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>.</p>


<p>Referenced by <a href="#ad107a2e9bf01094f9564019267eace1d">getChainedFixupsHeader</a>, <a href="#a766c3350d64dde8af24ef7b600b11185">getChainedFixupsSegments</a> and <a href="#a11261ec56e31921149aa022482d80e7e">getDyldChainedFixupTargets</a>.</p>

</div>
</div>

### getChainedFixupsSegments() {#a766c3350d64dde8af24ef7b600b11185}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::pair&lt; size_t, std::vector&lt; ChainedFixupsSegment &gt; &gt; &gt; MachOObjectFile::getChainedFixupsSegments ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 737 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 5049 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a718c920e2473631759319ce93d069224">llvm::MachO::linkedit_data_command::dataoff</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a7d4425eb797faa587c5634883588c45d">llvm::MachO::linkedit_data_command::datasize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#aae15979c93f7f0929116b975b5c46cd6">Fail</a>, <a href="#ad107a2e9bf01094f9564019267eace1d">getChainedFixupsHeader</a>, <a href="#a226f358d6c1305cdba13949825b60b49">getChainedFixupsLoadCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="#a4883a0c75b5154762599156fc1d27ab2">Header</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a638ca5d7bf4e2a09998c8e7fe8563ad8">llvm::object::Binary::isLittleEndian</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a4ee2015697caec796e59972aadc2f9e2">llvm::sys::IsLittleEndianHost</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a8160a3004ff47f73b842d7030269ff3d">malformedError</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h/#a276e8a32e0bbf024aadd9420b8f2d3b3">offsetof</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-chained-starts-in-segment/#a04686fb2865c9651718cb9118764597f">llvm::MachO::dyld_chained_starts_in_segment::page_count</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-chained-starts-in-segment/#a73c781bc645eed51feca91b4177e321e">llvm::MachO::dyld_chained_starts_in_segment::pointer_format</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-chained-starts-in-image/#a9e998ebf13dc20da601244024f74cab0">llvm::MachO::dyld_chained_starts_in_image::seg_count</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-chained-starts-in-segment/#acab5cc0a3ffbb01c9466fbb9c0c85b98">llvm::MachO::dyld_chained_starts_in_segment::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ad0e418047a3e04c4fd1fb83325b571ae">llvm::sys::swapByteOrder</a>.</p>

</div>
</div>

### getCommonSymbolSizeImpl() {#a4b3abf2e75a61284d8e8bd3547234c5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachOObjectFile::getCommonSymbolSizeImpl (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Declaration at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1838 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="#ad823d575bb639330180ee9d8b43bf237">getNValue</a>.</p>

</div>
</div>

### getDataInCodeLoadCommand() {#a2b03ad21c736b26f5396403bf49f2a59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::linkedit_data_command MachOObjectFile::getDataInCodeLoadCommand ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 716 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4880 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a7baa889dc47e7c8ff2d07fa9240eaaf1">llvm::MachO::linkedit_data_command::cmd</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#ae1362ae4d0a99fed872ed4549adc95c4">llvm::MachO::linkedit_data_command::cmdsize</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a718c920e2473631759319ce93d069224">llvm::MachO::linkedit_data_command::dataoff</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a7d4425eb797faa587c5634883588c45d">llvm::MachO::linkedit_data_command::datasize</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>


<p>Referenced by <a href="#a21eb1fb7d7f36d23fdd47f8e7ff0e2f1">begin_dices</a> and <a href="#a67ca29eb8dc5ee438d5cc11cf5a460d9">end_dices</a>.</p>

</div>
</div>

### getDataInCodeTableEntry() {#aaf48787fae336569ae8e87a4a645174b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::data_in_code_entry MachOObjectFile::getDataInCodeTableEntry (uint32_t DataOffset, unsigned Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 712 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4829 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getDice() {#aafff2e6b7435d209427acf5ab83bf375}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::data_in_code_entry MachOObjectFile::getDice (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 706 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4807 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/diceref/#abbcbae444f68ced6d2c20ad4d9dccb89">llvm::object::DiceRef::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/object/diceref/#a381ee8358f436b2302ffe7bd5c67e602">llvm::object::DiceRef::getLength</a> and <a href="/web-llvm/docs/api/classes/llvm/object/diceref/#a31f7752dd035a07b21fa3fb2d21081bc">llvm::object::DiceRef::getOffset</a>.</p>

</div>
</div>

### getDyldChainedFixupTargets() {#a11261ec56e31921149aa022482d80e7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; ChainedFixupTarget &gt; &gt; MachOObjectFile::getDyldChainedFixupTargets ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 728 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 5158 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a718c920e2473631759319ce93d069224">llvm::MachO::linkedit_data_command::dataoff</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a7d4425eb797faa587c5634883588c45d">llvm::MachO::linkedit_data_command::datasize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a07df1b9847b678f4e32a050816820576a75bd3d5847de0e0cfdd72344312d4f4f">llvm::MachO::DYLD_CHAINED_IMPORT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a07df1b9847b678f4e32a050816820576a97721a4154312d3a65ff26821bc17d98">llvm::MachO::DYLD_CHAINED_IMPORT_ADDEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a07df1b9847b678f4e32a050816820576afdc56fe540aa5f9b29059bcd5f8a5d10">llvm::MachO::DYLD_CHAINED_IMPORT_ADDEND64</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a8e5744e3da3116ce5eaf50660b88d6aa">getArray</a>, <a href="#ad107a2e9bf01094f9564019267eace1d">getChainedFixupsHeader</a>, <a href="#a226f358d6c1305cdba13949825b60b49">getChainedFixupsLoadCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#ac78e4faf9bf0789dfdf928c2ff83d731">getEncodedOrdinal</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a>, <a href="#a4883a0c75b5154762599156fc1d27ab2">Header</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a638ca5d7bf4e2a09998c8e7fe8563ad8">llvm::object::Binary::isLittleEndian</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a8160a3004ff47f73b842d7030269ff3d">malformedError</a>.</p>

</div>
</div>

### getDyldExportsTrie() {#a7107ae3ee300f48f02997f50fe543c0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint8_t &gt; MachOObjectFile::getDyldExportsTrie ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 738 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 5250 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a718c920e2473631759319ce93d069224">llvm::MachO::linkedit_data_command::dataoff</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a7d4425eb797faa587c5634883588c45d">llvm::MachO::linkedit_data_command::datasize</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="#a24c45a64b8e2666c4706d4e0c2c1add4">exports</a>.</p>

</div>
</div>

### getDyldInfoBindOpcodes() {#abee9da1b8caf9806998dc3fbc8fa02be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint8_t &gt; MachOObjectFile::getDyldInfoBindOpcodes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 719 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4922 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#ab88cd765d6656769b73824ee3633f9c6">llvm::MachO::dyld_info_command::bind_off</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#a6ffe60a024bfb2a697cf4717e3a1ca5d">llvm::MachO::dyld_info_command::bind_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="#a460d0b147c8ce41bfda4bcb3f20f6061">bindTable</a>.</p>

</div>
</div>

### getDyldInfoExportsTrie() {#a5d2c48586c800c9f29be71be14da45cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint8_t &gt; MachOObjectFile::getDyldInfoExportsTrie ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 722 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4964 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#a6abfd90c1ff5f9fab154b1b7c2ca9fdf">llvm::MachO::dyld_info_command::export_off</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#a6cc1cf394f79b0012db18526d363f887">llvm::MachO::dyld_info_command::export_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="#a24c45a64b8e2666c4706d4e0c2c1add4">exports</a>.</p>

</div>
</div>

### getDyldInfoLazyBindOpcodes() {#a428c19e380ff63f21f2bfb4fdf0078b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint8_t &gt; MachOObjectFile::getDyldInfoLazyBindOpcodes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 721 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4950 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#a66f14c5767f6c0860bcca3f23d15002c">llvm::MachO::dyld_info_command::lazy_bind_off</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#a8bbee159752147265303f294926c72d6">llvm::MachO::dyld_info_command::lazy_bind_size</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="#abb55e4947514d8643390aacdaa4a7736">lazyBindTable</a>.</p>

</div>
</div>

### getDyldInfoLoadCommand() {#a708244b1c588ce222e471dd17719b9b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::dyld_info_command MachOObjectFile::getDyldInfoLoadCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 673 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4700 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>

</div>
</div>

### getDyldInfoRebaseOpcodes() {#a8bf468d783b97cfaf64cce155ccc9365}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint8_t &gt; MachOObjectFile::getDyldInfoRebaseOpcodes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 718 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4908 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#ac0a251eaae629a1e7f918ff416ff17fd">llvm::MachO::dyld_info_command::rebase_off</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#a6b8dd4f28d4ff3bd7ea7ba0c3cd8a377">llvm::MachO::dyld_info_command::rebase_size</a>.</p>


<p>Referenced by <a href="#a1b87e710017438cefd497bd5ef89fdbe">rebaseTable</a>.</p>

</div>
</div>

### getDyldInfoWeakBindOpcodes() {#ac6987c2142793b0d0eb897b4eb2c2712}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint8_t &gt; MachOObjectFile::getDyldInfoWeakBindOpcodes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 720 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4936 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#ad19b3e306dcbd600f6e735c02c118eb6">llvm::MachO::dyld_info_command::weak_bind_off</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-info-command/#ab64b83ee5772b8d112c8961f209d1ab4">llvm::MachO::dyld_info_command::weak_bind_size</a>.</p>


<p>Referenced by <a href="#a87a504b58d7827fd3f526335f44cc14a">weakBindTable</a>.</p>

</div>
</div>

### getDylibIDLoadCommand() {#aeb9478037b0d4a28a04ad1d690e2f645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::dylib_command MachOObjectFile::getDylibIDLoadCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 671 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4695 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a4f3081cf8f364816d9a91b6e24d10fba">readMachOHeader</a>.</p>

</div>
</div>

### getDylinkerCommand() {#aa1db3c0b49113ff3627eb1ecd2f7b477}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::dylinker_command MachOObjectFile::getDylinkerCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 675 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4705 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>

</div>
</div>

### getDysymtabLoadCommand() {#a4479f956205d53f462400c0f9e98674a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::dysymtab_command MachOObjectFile::getDysymtabLoadCommand ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 715 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4850 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#afbf933351bbdd4cad785d245ce847382">llvm::MachO::dysymtab_command::cmd</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a23abe84aecd6ccce7c5ea1310386b76a">llvm::MachO::dysymtab_command::cmdsize</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a2bfa44a8b4a54932a5a9dbe7fb32a865">llvm::MachO::dysymtab_command::extrefsymoff</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a993c9357665d449e7803fadbb82bf057">llvm::MachO::dysymtab_command::extreloff</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a3e8bd0c8043f5b512c8b860bbe033b07">llvm::MachO::dysymtab_command::iextdefsym</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a57ffb158f384011d4d27bb8e4141a161">llvm::MachO::dysymtab_command::ilocalsym</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a1e9b3d4be015aa2be10de0a437ad5686">llvm::MachO::dysymtab_command::indirectsymoff</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#ac31191cf39d7f78424892ea81de3bd99">llvm::MachO::dysymtab_command::iundefsym</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#aacb93138f3f5ba1db874f2bc6844e94e">llvm::MachO::dysymtab_command::locreloff</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a28de8c2cbc7ca61dd12f5f67c9fab008">llvm::MachO::dysymtab_command::modtaboff</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a706033c7759b4ca692b961cf52a27062">llvm::MachO::dysymtab_command::nextdefsym</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#aaabc8d90d8f1914bb4a59446bd11efd7">llvm::MachO::dysymtab_command::nextrefsyms</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a5e3a398cb685e1b0056878d31ae550ff">llvm::MachO::dysymtab_command::nextrel</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a84eede0ea68ac0b6f157e46372d226ec">llvm::MachO::dysymtab_command::nindirectsyms</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a6e04c03637d2c58efac3781d801a4aaf">llvm::MachO::dysymtab_command::nlocalsym</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a4ea035f028815d8cd6f4d0c6d188db2d">llvm::MachO::dysymtab_command::nlocrel</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a90831317c37c80053ba24ca342da234d">llvm::MachO::dysymtab_command::nmodtab</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a060a8e9c435cda35c770e0b03810eefe">llvm::MachO::dysymtab_command::ntoc</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#ac11564ca42a1a60d0096f9763c8831a8">llvm::MachO::dysymtab_command::nundefsym</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command/#a13a60e45dcd6989958ab4ee352a340ae">llvm::MachO::dysymtab_command::tocoff</a>.</p>


<p>Referenced by <a href="#af0fde7879a332b4234a4a2a7e59446db">extrel_end</a>, <a href="#aaacf649b0759051f6c5327e44b82f8aa">getRelocation</a>, <a href="#afc59d7882fd3b78d7d8bd063816f450d">locrel_end</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ab606ca40d5870295837712aa2056f90e">llvm::RuntimeDyldMachO::populateIndirectSymbolPointersSection</a>.</p>

</div>
</div>

### getEncryptionInfoCommand() {#a806af0cdf9cc3ef071e2a103dad08e31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::encryption_info_command MachOObjectFile::getEncryptionInfoCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 685 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4730 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>

</div>
</div>

### getEncryptionInfoCommand64() {#a1feb8b357acb0ed676d8b4a1954c5623}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::encryption_info_command_64 MachOObjectFile::getEncryptionInfoCommand64 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4735 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>

</div>
</div>

### getEntryPointCommand() {#a352e221c16019d6045da26a3209e40c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::entry_point_command MachOObjectFile::getEntryPointCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 683 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4725 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>

</div>
</div>

### getFeatures() {#ace0518dae7ee126091d84b4dc0a47ed7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SubtargetFeatures &gt; llvm::object::MachOObjectFile::getFeatures ()</td>
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



<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### getFileFormatName() {#a216609c43afe05c3da08214afdc8e72b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef MachOObjectFile::getFileFormatName ()</td>
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



<p>Declaration at line 518 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2659 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47ae4da455e762f086662789406e1f085e0">llvm::MachO::CPU_TYPE_ARM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a33fddb0190d728c25e266a22d64bd7ad">llvm::MachO::CPU_TYPE_ARM64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a03cac236584f93f35c9ff89f2d65b716">llvm::MachO::CPU_TYPE_ARM64_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47aa9f8e9712ff2848d650f3c5d8c43c2f8">llvm::MachO::CPU_TYPE_I386</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a630a338da04bb807aac2b41f8fe4e6e7">llvm::MachO::CPU_TYPE_POWERPC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a6f5e12941e8587f9157b470d297fa451">llvm::MachO::CPU_TYPE_POWERPC64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a633855cb5719de40d81669897cc571c8">llvm::MachO::CPU_TYPE_X86_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#ae148cedd3b13337408aac7949e546eb9">getCPUType</a> and <a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a>.</p>

</div>
</div>

### getFilesetEntryLoadCommand() {#a5203f8a41fa3b6a2e3cbc8949c1fc962}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::fileset_entry_command MachOObjectFile::getFilesetEntryLoadCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4775 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>

</div>
</div>

### getFunctionStarts() {#a6e304ff95b5d1ea04529da35d5307d6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; uint64_t &gt; MachOObjectFile::getFunctionStarts ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 740 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 5264 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a718c920e2473631759319ce93d069224">llvm::MachO::linkedit_data_command::dataoff</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a> and <a href="#ab6717ca91fe3922480a18f3e4250e611">ReadULEB128s</a>.</p>

</div>
</div>

### getHeader() {#a80dc9af48926f9c1b70075f71c6002a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachO::mach_header &amp; MachOObjectFile::getHeader ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 707 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4812 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="#a4883a0c75b5154762599156fc1d27ab2">Header</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#af5d5ac386b9d143dc66cbb3bdac42adf">checkDylibIdCommand</a>, <a href="#a58bd45157985a622dba76ecef6375f4d">checkSymbolTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp/#a3ebc7dd21b6e9c9781e5ac3e5d9b604e">extractSections</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d77869bd604539426d81bd418ce875f">getFirstLoadCommandInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#afdea79cf3204fe335d9ebceb78e6a778">getNextLoadCommandInfo</a>, <a href="#aaacf649b0759051f6c5327e44b82f8aa">getRelocation</a>, <a href="#a3f4f04d967a4ea26b58a22ab9e211094">getRelocationOffset</a>, <a href="#a5960f71b19779a8db394bae2c9be62c9">isRelocatableObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a488ef72cdaf48278d8a1117a6833bad2">parseSegmentLoadCommand</a> and <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a4f3081cf8f364816d9a91b6e24d10fba">readMachOHeader</a>.</p>

</div>
</div>

### getHeader64() {#a10ac2a63f6a950994aae39057eeca34a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachO::mach_header_64 &amp; MachOObjectFile::getHeader64 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 708 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4816 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0d6204611b3f1b7f9772b6165a8f91b8">Header64</a> and <a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a>.</p>


<p>Referenced by <a href="#a58bd45157985a622dba76ecef6375f4d">checkSymbolTable</a>.</p>

</div>
</div>

### getIndirectName() {#a1c4dce386c635e9449383a532bc38070}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code MachOObjectFile::getIndirectName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1807 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#ad823d575bb639330180ee9d8b43bf237">getNValue</a>, <a href="#ad451ffea9d6ef1b5ec634f176bf6dcad">getStringTableData</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a0e0b242aa7cb8cb269f5ea9973a9f605">getSymbolTableEntryBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaca65700aad8ca31abbb94cbb03227eda906620a6f5df2e39717dac5f1473a77a">llvm::MachO::N_INDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad152fa3b2aff735d4a2e4b644dc93b11a6d2d703f3e79b6904f129d79b5915e7e">llvm::MachO::N_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a> and <a href="/web-llvm/docs/api/classes/llvm/stringtable/#a1c25d62b8c2016835a39cd4b64151802">llvm::StringTable::size</a>.</p>

</div>
</div>

### getIndirectSymbolTableEntry() {#af0479ec0a64582d6ad2df6f5231beae3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t MachOObjectFile::getIndirectSymbolTableEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/dysymtab-command">MachO::dysymtab_command</a> &amp; DLC, unsigned Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 710 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4821 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ab606ca40d5870295837712aa2056f90e">llvm::RuntimeDyldMachO::populateIndirectSymbolPointersSection</a>.</p>

</div>
</div>

### getLibraryCount() {#a3247f2fd52f536bdd17fc78c956da43f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t MachOObjectFile::getLibraryCount ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2585 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>

</div>
</div>

### getLibraryShortNameByIndex() {#afea73c1af002769dde1fb465f40b6ac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code MachOObjectFile::getLibraryShortNameByIndex (unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2551 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3be6030c853d0e0ffe5bc8545197118a">getStructOrErr</a>, <a href="#af3e1bca92860141baaad0a536334d09f">guessLibraryShortName</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a>.</p>

</div>
</div>

### getLinkeditDataLoadCommand() {#ae669e6342a3406842cda2714f1f143c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::linkedit_data_command MachOObjectFile::getLinkeditDataLoadCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 655 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4655 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a4f3081cf8f364816d9a91b6e24d10fba">readMachOHeader</a>.</p>

</div>
</div>

### getLinkerOptionLoadCommand() {#a31b3a7bf8a638884321a2df0f787fe05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::linker_option_command MachOObjectFile::getLinkerOptionLoadCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 661 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4670 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>

</div>
</div>

### getLinkOptHintsLoadCommand() {#a64bfe87a4a35f817e902fc4c3c50f5d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::linkedit_data_command MachOObjectFile::getLinkOptHintsLoadCommand ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 717 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4894 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a7baa889dc47e7c8ff2d07fa9240eaaf1">llvm::MachO::linkedit_data_command::cmd</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#ae1362ae4d0a99fed872ed4549adc95c4">llvm::MachO::linkedit_data_command::cmdsize</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a718c920e2473631759319ce93d069224">llvm::MachO::linkedit_data_command::dataoff</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/linkedit-data-command/#a7d4425eb797faa587c5634883588c45d">llvm::MachO::linkedit_data_command::datasize</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>

</div>
</div>

### getMachOFilesetEntryOffset() {#aeb95a0420b2442e27f0b4023926c72fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::object::MachOObjectFile::getMachOFilesetEntryOffset ()</td>
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



<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d77869bd604539426d81bd418ce875f">getFirstLoadCommandInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#afdea79cf3204fe335d9ebceb78e6a778">getNextLoadCommandInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#adcb372f00f2b01dc20f3567b2eb97be3">parseHeader</a>.</p>

</div>
</div>

### getNoteLoadCommand() {#a527b022bfecb5185b104f66bb26ce3c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::note_command MachOObjectFile::getNoteLoadCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4680 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>

</div>
</div>

### getNValue() {#ad823d575bb639330180ee9d8b43bf237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachOObjectFile::getNValue (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1796 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a62195bc7e86a573ecebe708bee210b61">getSymbol64TableEntry</a>, <a href="#a2df84b6031947d33d436f49b29a699b2">getSymbolTableEntry</a> and <a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a>.</p>


<p>Referenced by <a href="#a4b3abf2e75a61284d8e8bd3547234c5d">getCommonSymbolSizeImpl</a>, <a href="#a1c4dce386c635e9449383a532bc38070">getIndirectName</a> and <a href="#a725d75c745df0f036d8e5fba0670f13d">getSymbolFlags</a>.</p>

</div>
</div>

### getPlainRelocationExternal() {#a7bec3ca52f60d7ca088f0634a2e8f779}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachOObjectFile::getPlainRelocationExternal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a> &amp; RE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 633 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4556 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a638ca5d7bf4e2a09998c8e7fe8563ad8">llvm::object::Binary::isLittleEndian</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info/#aff97edf4109298178b12aca5621bd6ec">llvm::MachO::any_relocation_info::r_word1</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp/#a3ebc7dd21b6e9c9781e5ac3e5d9b604e">extractSections</a>, <a href="#a43739eb6bed0aa4dc4ac7c50de26674b">getAnyRelocationSection</a>, <a href="#a19321b2c5a24656fe59c193ae2892453">getRelocationSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ac01d9cc5d2d4a3b6662c7096e54bf8ad">llvm::RuntimeDyldMachO::getRelocationValueRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#a731c45f6ccf4dde3198c1d5147c3cb37">llvm::RuntimeDyldMachOAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#ad0cc2b7a34912033f88c7169756683cb">llvm::RuntimeDyldMachOARM::processRelocationRef</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#a59ad91c5ccf9ed8867eab9cc5424b151">llvm::RuntimeDyldMachOX86_64::processRelocationRef</a>.</p>

</div>
</div>

### getPlainRelocationSymbolNum() {#a99471e40aa719f7de1a81c38b8b129cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachOObjectFile::getPlainRelocationSymbolNum (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a> &amp; RE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 631 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4549 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a638ca5d7bf4e2a09998c8e7fe8563ad8">llvm::object::Binary::isLittleEndian</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info/#aff97edf4109298178b12aca5621bd6ec">llvm::MachO::any_relocation_info::r_word1</a>.</p>


<p>Referenced by <a href="#a43739eb6bed0aa4dc4ac7c50de26674b">getAnyRelocationSection</a>, <a href="#a19321b2c5a24656fe59c193ae2892453">getRelocationSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#a731c45f6ccf4dde3198c1d5147c3cb37">llvm::RuntimeDyldMachOAArch64::processRelocationRef</a>.</p>

</div>
</div>

### getRelocation() {#aaacf649b0759051f6c5327e44b82f8aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::any_relocation_info MachOObjectFile::getRelocation (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 705 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4780 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2820613261c431d4de10b49e30b90ae4">llvm::object::DataRefImpl::b</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>, <a href="#a4479f956205d53f462400c0f9e98674a">getDysymtabLoadCommand</a>, <a href="#a80dc9af48926f9c1b70075f71c6002a7">getHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a>, <a href="#a1a18707996459de69e40ab867eeee801">getSection</a>, <a href="#a4ddf638fa2c882a669517ae17a4e032a">getSection64</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>, <a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a4099e754341e36bdbc04624fa2f1e19aa0720b97729bd97889599a4dc76faf0dc">llvm::MachO::MH_OBJECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/section/#a4463af1400a8cb0c7a4b0c89efb3b861">llvm::MachO::section::reloff</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/section-64/#a44ef72d19789a575cac088af4d0c22a5">llvm::MachO::section_64::reloff</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp/#a3ebc7dd21b6e9c9781e5ac3e5d9b604e">extractSections</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#abaf648d88dc891045a7cd0e989789370">llvm::RuntimeDyldMachO::getRelocationEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/macholinkgraphbuilder/#ad63fca6e6e001f3e97eebaa2c397ffc9">llvm::jitlink::MachOLinkGraphBuilder::getRelocationInfo</a>, <a href="#ac48a4a2e5b90072e58a7c0e1d200506c">getRelocationLength</a>, <a href="#a3f4f04d967a4ea26b58a22ab9e211094">getRelocationOffset</a>, <a href="#ae0d1a3db809bbb82228bab61d2f5dc27">getRelocationSection</a>, <a href="#a19321b2c5a24656fe59c193ae2892453">getRelocationSymbol</a>, <a href="#aa3c891d7b0434f73b2ae7adceed7bcec">getRelocationType</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ac01d9cc5d2d4a3b6662c7096e54bf8ad">llvm::RuntimeDyldMachO::getRelocationValueRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#ae415bc5251a1c0a2bd01a1e7efaa6828">isRelocScattered</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#a731c45f6ccf4dde3198c1d5147c3cb37">llvm::RuntimeDyldMachOAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#ad0cc2b7a34912033f88c7169756683cb">llvm::RuntimeDyldMachOARM::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoi386/#a5bd3ae889a8d52356bd6b32e45c7aa6c">llvm::RuntimeDyldMachOI386::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#a59ad91c5ccf9ed8867eab9cc5424b151">llvm::RuntimeDyldMachOX86_64::processRelocationRef</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#acb7257d8eec274d18e7916a0d552a2d7">llvm::RuntimeDyldMachO::processScatteredVANILLA</a>.</p>

</div>
</div>

### getRelocationLength() {#ac48a4a2e5b90072e58a7c0e1d200506c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t MachOObjectFile::getRelocationLength (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2386 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a942691b0e7a01c33a7aa6b36b28472d2">getAnyRelocationLength</a> and <a href="#aaacf649b0759051f6c5327e44b82f8aa">getRelocation</a>.</p>

</div>
</div>

### getRelocationOffset() {#a3f4f04d967a4ea26b58a22ab9e211094}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachOObjectFile::getRelocationOffset (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
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



<p>Declaration at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2237 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad388361f228398a0d6ccd304f88138fa">getAnyRelocationAddress</a>, <a href="#a80dc9af48926f9c1b70075f71c6002a7">getHeader</a>, <a href="#aaacf649b0759051f6c5327e44b82f8aa">getRelocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a4099e754341e36bdbc04624fa2f1e19aa7cf8cdddea54349189e933228d850445">llvm::MachO::MH_KEXT_BUNDLE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a4099e754341e36bdbc04624fa2f1e19aa0720b97729bd97889599a4dc76faf0dc">llvm::MachO::MH_OBJECT</a>.</p>

</div>
</div>

### getRelocationRelocatedSection() {#a73ddbfba78956c4ed1b7c2ab5b816dbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">section_iterator MachOObjectFile::getRelocationRelocatedSection (<a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a> Rel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2590 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>, <a href="/web-llvm/docs/api/classes/llvm/object/relocationref/#acd93a9353f94b029cdfa295b88874b38">llvm::object::RelocationRef::getRawDataRefImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a>.</p>

</div>
</div>

### getRelocationSection() {#ae0d1a3db809bbb82228bab61d2f5dc27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">section_iterator MachOObjectFile::getRelocationSection (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2267 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a43739eb6bed0aa4dc4ac7c50de26674b">getAnyRelocationSection</a> and <a href="#aaacf649b0759051f6c5327e44b82f8aa">getRelocation</a>.</p>

</div>
</div>

### getRelocationSymbol() {#a19321b2c5a24656fe59c193ae2892453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">symbol_iterator MachOObjectFile::getRelocationSymbol (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
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



<p>Declaration at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2246 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a7bec3ca52f60d7ca088f0634a2e8f779">getPlainRelocationExternal</a>, <a href="#a99471e40aa719f7de1a81c38b8b129cc">getPlainRelocationSymbolNum</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a>, <a href="#aaacf649b0759051f6c5327e44b82f8aa">getRelocation</a>, <a href="#a9451d5e767c3b97403785baaff3c6a44">getSymtabLoadCommand</a>, <a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a>, <a href="#ad07c873a9197ed022e779129f28ca028">isRelocationScattered</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>, <a href="#aabf498b6cb34cb967c73e3c0c51baee2">symbol_end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a23fe52bbc164a30ba18e057d37bd2283">llvm::object::ObjectFile::SymbolRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ad0cbda82482585d346b65687e2f3a38a">llvm::XCOFF::SymbolTableEntrySize</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#ae6c74170eea156826ddfb4b61bd5d043">llvm::MachO::symtab_command::symoff</a>.</p>

</div>
</div>

### getRelocationType() {#aa3c891d7b0434f73b2ae7adceed7bcec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachOObjectFile::getRelocationType (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
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



<p>Declaration at line 490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2271 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a653a63105b842dd49a3a0921ce6a6d66">getAnyRelocationType</a> and <a href="#aaacf649b0759051f6c5327e44b82f8aa">getRelocation</a>.</p>


<p>Referenced by <a href="#ad4f7324b39a6386811a1d2202cfe1fed">getRelocationTypeName</a>.</p>

</div>
</div>

### getRelocationTypeName() {#ad4f7324b39a6386811a1d2202cfe1fed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOObjectFile::getRelocationTypeName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Result)</td>
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



<p>Declaration at line 491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2276 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af26b2aa05e5a49b91b981143e0e49a34">llvm::Triple::aarch64_32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">llvm::Triple::arm</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a>, <a href="#a0c6dd60e5645b2ff160ea7368c04e78f">getArch</a>, <a href="#aa3c891d7b0434f73b2ae7adceed7bcec">getRelocationType</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704">llvm::Triple::ppc</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5b44ea359fcb23c7b1bfdc029979614c">llvm::Triple::UnknownArch</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">llvm::Triple::x86</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>

</div>
</div>

### getRoutinesCommand() {#a2badd591726f82a2e5942e44907c80ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::routines_command MachOObjectFile::getRoutinesCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4760 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>

</div>
</div>

### getRoutinesCommand64() {#a6b01323aa4c54564eeef35c5cf7d0151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::routines_command_64 MachOObjectFile::getRoutinesCommand64 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 699 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4765 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>

</div>
</div>

### getRpathCommand() {#a66f24d7c05980ed733c32c31f099766d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::rpath_command MachOObjectFile::getRpathCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 679 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4715 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a4f3081cf8f364816d9a91b6e24d10fba">readMachOHeader</a>.</p>

</div>
</div>

### getScatteredRelocationScattered() {#a77b819d412646ba61fca1a45e57a5a7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachOObjectFile::getScatteredRelocationScattered (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a> &amp; RE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 634 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4563 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info/#a2c1c46bbe4b0ef3065fe91d3e9ca806e">llvm::MachO::any_relocation_info::r_word0</a>.</p>

</div>
</div>

### getScatteredRelocationType() {#a17bc598aa230859797b75db2fe68ac4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t MachOObjectFile::getScatteredRelocationType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a> &amp; RE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 638 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4573 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info/#a2c1c46bbe4b0ef3065fe91d3e9ca806e">llvm::MachO::any_relocation_info::r_word0</a>.</p>


<p>Referenced by <a href="#a653a63105b842dd49a3a0921ce6a6d66">getAnyRelocationType</a>.</p>

</div>
</div>

### getScatteredRelocationValue() {#a3144dc7cc061533970cd9681fbbc907a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t MachOObjectFile::getScatteredRelocationValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a> &amp; RE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4568 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info/#aff97edf4109298178b12aca5621bd6ec">llvm::MachO::any_relocation_info::r_word1</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#acb7257d8eec274d18e7916a0d552a2d7">llvm::RuntimeDyldMachO::processScatteredVANILLA</a>.</p>

</div>
</div>

### getSection() {#a1a18707996459de69e40ab867eeee801}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SectionRef &gt; MachOObjectFile::getSection (unsigned SectionIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2017 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a8160a3004ff47f73b842d7030269ff3d">malformedError</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp/#a3ebc7dd21b6e9c9781e5ac3e5d9b604e">extractSections</a>, <a href="#aaacf649b0759051f6c5327e44b82f8aa">getRelocation</a>, <a href="#ac223e702ae7330bc836e547bf1023278">getSectionAddress</a>, <a href="#a12de1fc762e4d94c86bbdffd6a472df4">getSectionAlignment</a>, <a href="#ae9721b8484141c4d955c6830762a072b">getSectionContents</a>, <a href="#af0c6e225cf80ae36a9994bd1e79e8655">getSectionSize</a>, <a href="#ab046bef50272d4e0d9abf45b017feaaa">isSectionStripped</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ab606ca40d5870295837712aa2056f90e">llvm::RuntimeDyldMachO::populateIndirectSymbolPointersSection</a> and <a href="#a5b4a2cfae548a9a5cf6228605d4c0e7d">section_rel_end</a>.</p>

</div>
</div>

### getSection() {#a88e19a85aa8bc06f5b3e51c382dfbb41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SectionRef &gt; MachOObjectFile::getSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2026 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a7f73649118e365a230be4870d824e7cf">llvm::object::ObjectFile::sections</a>.</p>

</div>
</div>

### getSection() {#abd858c258a4333c61658e66fcbbaa9e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::section MachOObjectFile::getSection (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> DRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 647 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4620 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>

</div>
</div>

### getSection() {#a4916f4a65ce359c50389bc77a5689f7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::section MachOObjectFile::getSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L, unsigned Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4630 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a7695bd8a585d6d772c516b6e7b7aa0e3">getSectionPtr</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>

</div>
</div>

### getSection64() {#a4ddf638fa2c882a669517ae17a4e032a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::section_64 MachOObjectFile::getSection64 (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> DRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 648 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4625 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>


<p>Referenced by <a href="#aaacf649b0759051f6c5327e44b82f8aa">getRelocation</a>, <a href="#ac223e702ae7330bc836e547bf1023278">getSectionAddress</a>, <a href="#a12de1fc762e4d94c86bbdffd6a472df4">getSectionAlignment</a>, <a href="#ae9721b8484141c4d955c6830762a072b">getSectionContents</a>, <a href="#af0c6e225cf80ae36a9994bd1e79e8655">getSectionSize</a>, <a href="#ab046bef50272d4e0d9abf45b017feaaa">isSectionStripped</a> and <a href="#a5b4a2cfae548a9a5cf6228605d4c0e7d">section_rel_end</a>.</p>

</div>
</div>

### getSection64() {#aa868c47bf47a793dbd158c31f3d9864e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::section_64 MachOObjectFile::getSection64 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L, unsigned Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 650 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4636 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a7695bd8a585d6d772c516b6e7b7aa0e3">getSectionPtr</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>

</div>
</div>

### getSectionAddress() {#ac223e702ae7330bc836e547bf1023278}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachOObjectFile::getSectionAddress (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1942 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/macho/section-64/#a0f65c0b1363fee2b46216dfacbb66288">llvm::MachO::section_64::addr</a>, <a href="#a1a18707996459de69e40ab867eeee801">getSection</a>, <a href="#a4ddf638fa2c882a669517ae17a4e032a">getSection64</a> and <a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a>.</p>

</div>
</div>

### getSectionAlignment() {#a12de1fc762e4d94c86bbdffd6a472df4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachOObjectFile::getSectionAlignment (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2004 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/macho/section/#a5327b3f6a6da23eebb52fdd41d30e4e4">llvm::MachO::section::align</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/section-64/#a241f45c100fc4f835472baed240193d4">llvm::MachO::section_64::align</a>, <a href="#a1a18707996459de69e40ab867eeee801">getSection</a>, <a href="#a4ddf638fa2c882a669517ae17a4e032a">getSection64</a> and <a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a>.</p>

</div>
</div>

### getSectionContents() {#a541a23560ff0dfbe01c6c1c9e4d07801}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint8_t &gt; MachOObjectFile::getSectionContents (uint32_t Offset, uint64_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1981 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1b144823e66f38f789fb4909c29b8bec">llvm::arrayRefFromStringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ab845621311caa169682acb9c65516ae1">substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp/#a3ebc7dd21b6e9c9781e5ac3e5d9b604e">extractSections</a> and <a href="#ae9721b8484141c4d955c6830762a072b">getSectionContents</a>.</p>

</div>
</div>

### getSectionContents() {#ae9721b8484141c4d955c6830762a072b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ArrayRef&lt; uint8_t &gt; &gt; MachOObjectFile::getSectionContents (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1987 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a1a18707996459de69e40ab867eeee801">getSection</a>, <a href="#a4ddf638fa2c882a669517ae17a4e032a">getSection64</a>, <a href="#a541a23560ff0dfbe01c6c1c9e4d07801">getSectionContents</a>, <a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/section/#ad3c2cc59900b59684f4e7961679a928b">llvm::MachO::section::offset</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/section-64/#a235d0ebc85332907ba154085b3cc0a1a">llvm::MachO::section_64::offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/section/#a1f4525d629a0d8bde4d942a294895168">llvm::MachO::section::size</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/section-64/#a811eac027455d467634d621976da1daf">llvm::MachO::section_64::size</a>.</p>

</div>
</div>

### getSectionFinalSegmentName() {#a647f0ec13a56dcdcf59ff036090db193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef MachOObjectFile::getSectionFinalSegmentName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 622 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4520 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="#a0753fcaceabb5cf8f772cae836fe945b">getSectionRawFinalSegmentName</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#ad91ce3ef577757936597aace8a21fdef">parseSegmentOrSectionName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/bindrebaseseginfo/#aaaf6cee47713cc12a459bc779d459f13">llvm::object::BindRebaseSegInfo::BindRebaseSegInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2143f8386a6b8bcb33011fdd240c38f1">llvm::orc::getMachOObjectFileSymbolInfo</a> and <a href="#acba45c9f1c0b5b00a3fe59eae613b4fb">isSectionBitcode</a>.</p>

</div>
</div>

### getSectionID() {#ae48752dc6271082d4f4cb2c9db80703d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachOObjectFile::getSectionID (<a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a> Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2151 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>, <a href="/web-llvm/docs/api/classes/llvm/object/sectionref/#a1f7697438cbf778f7d1b051e97204606">llvm::object::SectionRef::getRawDataRefImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a>.</p>

</div>
</div>

### getSectionIndex() {#ab4273d5ff85c5d9d4e9e4f69ff7f6a0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachOObjectFile::getSectionIndex (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1948 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>.</p>

</div>
</div>

### getSectionName() {#ac459e969de113b3d211c0a4087656dc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; MachOObjectFile::getSectionName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1937 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="#ad79e64ea14a6d005ca27139d6737066f">getSectionRawName</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#ad91ce3ef577757936597aace8a21fdef">parseSegmentOrSectionName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2143f8386a6b8bcb33011fdd240c38f1">llvm::orc::getMachOObjectFileSymbolInfo</a>, <a href="#a5d343559880ac878c6a999cd0e85517e">isDebugSection</a> and <a href="#acba45c9f1c0b5b00a3fe59eae613b4fb">isSectionBitcode</a>.</p>

</div>
</div>

### getSectionRawFinalSegmentName() {#a0753fcaceabb5cf8f772cae836fe945b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; char &gt; MachOObjectFile::getSectionRawFinalSegmentName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 627 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4534 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>.</p>


<p>Referenced by <a href="#a647f0ec13a56dcdcf59ff036090db193">getSectionFinalSegmentName</a>.</p>

</div>
</div>

### getSectionRawName() {#ad79e64ea14a6d005ca27139d6737066f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; char &gt; MachOObjectFile::getSectionRawName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 626 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4526 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>.</p>


<p>Referenced by <a href="#ac459e969de113b3d211c0a4087656dc7">getSectionName</a>.</p>

</div>
</div>

### getSectionSize() {#af0c6e225cf80ae36a9994bd1e79e8655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachOObjectFile::getSectionSize (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1952 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/macho/section/#ab0c6e8f900f73f5d46990669e9fb6998">llvm::MachO::section::flags</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/section-64/#a8eaaee3363d1105468fb49b513fe7e6c">llvm::MachO::section_64::flags</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="#a1a18707996459de69e40ab867eeee801">getSection</a>, <a href="#a4ddf638fa2c882a669517ae17a4e032a">getSection64</a>, <a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/section/#ad3c2cc59900b59684f4e7961679a928b">llvm::MachO::section::offset</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/section-64/#a235d0ebc85332907ba154085b3cc0a1a">llvm::MachO::section_64::offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a18315ad92b87c2abc1ff1a795b4119c0">llvm::MachO::S_GB_ZEROFILL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a901e329f9c215482ab4877d7efec0768">llvm::MachO::S_ZEROFILL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a03740c22238cbe574a5d3aaf3cd5d198afcc0f8ee030bc9729199d678956638b3">llvm::MachO::SECTION_TYPE</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/section/#a1f4525d629a0d8bde4d942a294895168">llvm::MachO::section::size</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/section-64/#a811eac027455d467634d621976da1daf">llvm::MachO::section_64::size</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### getSectionType() {#a6219972bdae3e9ac0f4daf447f328d82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachOObjectFile::getSectionType (<a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a> Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1790 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/sectionref/#a1f7697438cbf778f7d1b051e97204606">llvm::object::SectionRef::getRawDataRefImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#ac5ea45808f76ad3f6b0159739e80d160">getSectionFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a03740c22238cbe574a5d3aaf3cd5d198afcc0f8ee030bc9729199d678956638b3">llvm::MachO::SECTION_TYPE</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2143f8386a6b8bcb33011fdd240c38f1">llvm::orc::getMachOObjectFileSymbolInfo</a>.</p>

</div>
</div>

### getSegment64LoadCommand() {#a5b1695c0e56a3fd6bcefcaccb8b9dab6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::segment_command_64 MachOObjectFile::getSegment64LoadCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 659 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4665 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>

</div>
</div>

### getSegmentContents() {#adb68429296d9cd8a13b4aa3f10f2e780}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint8_t &gt; MachOObjectFile::getSegmentContents (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SegmentName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the raw contents of an entire segment.</p>

<p>Declaration at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2108 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="#adb68429296d9cd8a13b4aa3f10f2e780">getSegmentContents</a> and <a href="#a9397f336b10a2f4db6c6d5a8f9b49224">load_commands</a>.</p>


<p>Referenced by <a href="#adb68429296d9cd8a13b4aa3f10f2e780">getSegmentContents</a>.</p>

</div>
</div>

### getSegmentContents() {#ac696b4147be1f37d5b9180fe83371658}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint8_t &gt; MachOObjectFile::getSegmentContents (size_t SegmentIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2130 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="#a9397f336b10a2f4db6c6d5a8f9b49224">load_commands</a>.</p>

</div>
</div>

### getSegmentLoadCommand() {#a6317d38843b3ac79b92a3c85bb2ed7b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::segment_command MachOObjectFile::getSegmentLoadCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4660 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>

</div>
</div>

### getSourceVersionCommand() {#ad17a0cc5e558e81985224344a3dd57bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::source_version_command MachOObjectFile::getSourceVersionCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 681 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4720 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>

</div>
</div>

### getStringTableData() {#ad451ffea9d6ef1b5ec634f176bf6dcad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef MachOObjectFile::getStringTableData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 743 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 5287 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="#a9451d5e767c3b97403785baaff3c6a44">getSymtabLoadCommand</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#ad664b3b2032af10912280b74303ee21d">llvm::MachO::symtab_command::stroff</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#a1459968fe2ad55b364958070dde70c6e">llvm::MachO::symtab_command::strsize</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="#a1c4dce386c635e9449383a532bc38070">getIndirectName</a> and <a href="#a79ff60972cb2fd27ac7280c9e5052d4a">getSymbolName</a>.</p>

</div>
</div>

### getSubClientCommand() {#a023569a7035ef18e014f39cc2800ad07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::sub_client_command MachOObjectFile::getSubClientCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4755 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a4f3081cf8f364816d9a91b6e24d10fba">readMachOHeader</a>.</p>

</div>
</div>

### getSubFrameworkCommand() {#a6c0b621a228e683bf4590229691489aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::sub_framework_command MachOObjectFile::getSubFrameworkCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 689 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4740 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a4f3081cf8f364816d9a91b6e24d10fba">readMachOHeader</a>.</p>

</div>
</div>

### getSubLibraryCommand() {#a6f9c9811944d064d439d7c5d9bf64cd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::sub_library_command MachOObjectFile::getSubLibraryCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 693 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4750 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>

</div>
</div>

### getSubUmbrellaCommand() {#a70b068a5ae812db11c38e8b8dc23617b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::sub_umbrella_command MachOObjectFile::getSubUmbrellaCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 691 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4745 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>

</div>
</div>

### getSymbol64TableEntry() {#a62195bc7e86a573ecebe708bee210b61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::nlist_64 MachOObjectFile::getSymbol64TableEntry (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> DRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 652 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4649 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>.</p>


<p>Referenced by <a href="#a58bd45157985a622dba76ecef6375f4d">checkSymbolTable</a> and <a href="#ad823d575bb639330180ee9d8b43bf237">getNValue</a>.</p>

</div>
</div>

### getSymbolAddress() {#aeb1975d59d60a84adba98e90c59872e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; MachOObjectFile::getSymbolAddress (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Declaration at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1825 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aa520e1a721f81e1befb66b422c6e4a60">llvm::object::ObjectFile::getSymbolValue</a>.</p>

</div>
</div>

### getSymbolAlignment() {#ad12defbd432cf6bb7f7b05f956681e03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t MachOObjectFile::getSymbolAlignment (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Declaration at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1829 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a72b7b59bb84329c4f3e3e516a341f01a">llvm::MachO::GET_COMM_ALIGN</a>, <a href="#a725d75c745df0f036d8e5fba0670f13d">getSymbolFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a0e0b242aa7cb8cb269f5ea9973a9f605">getSymbolTableEntryBase</a> and <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a917d4e0252fa1d20b2086b2e99e78e57">llvm::object::BasicSymbolRef::SF_Common</a>.</p>

</div>
</div>

### getSymbolByIndex() {#a7d7c96e485022e0023e9b8eec0257f0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">symbol_iterator MachOObjectFile::getSymbolByIndex (unsigned Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2620 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a>, <a href="#a9451d5e767c3b97403785baaff3c6a44">getSymtabLoadCommand</a>, <a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#a1fe8ad1b38dc828beefc5757d7dc1a3a">llvm::MachO::symtab_command::nsyms</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a23fe52bbc164a30ba18e057d37bd2283">llvm::object::ObjectFile::SymbolRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ad0cbda82482585d346b65687e2f3a38a">llvm::XCOFF::SymbolTableEntrySize</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#ae6c74170eea156826ddfb4b61bd5d043">llvm::MachO::symtab_command::symoff</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ab606ca40d5870295837712aa2056f90e">llvm::RuntimeDyldMachO::populateIndirectSymbolPointersSection</a> and <a href="#a21f780beb96b3c8859b9f75422e2c4f9">symbol_begin</a>.</p>

</div>
</div>

### getSymbolFlags() {#a725d75c745df0f036d8e5fba0670f13d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint32_t &gt; MachOObjectFile::getSymbolFlags (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Declaration at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1868 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#ad823d575bb639330180ee9d8b43bf237">getNValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a0e0b242aa7cb8cb269f5ea9973a9f605">getSymbolTableEntryBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaca65700aad8ca31abbb94cbb03227eda77259a8efd8dc293c93df006d02b90c5">llvm::MachO::N_ABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a8566ffd52ce0223e6ecc4298a438a721a3a8a9929963eda78942022a0bdb737ae">llvm::MachO::N_ARM_THUMB_DEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad152fa3b2aff735d4a2e4b644dc93b11a8bc1bbfcee7206480576072973724a1a">llvm::MachO::N_EXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaca65700aad8ca31abbb94cbb03227eda906620a6f5df2e39717dac5f1473a77a">llvm::MachO::N_INDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad152fa3b2aff735d4a2e4b644dc93b11aa76667ab09bbf06002b68e0c1a015806">llvm::MachO::N_PEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad152fa3b2aff735d4a2e4b644dc93b11afa536dc3de031dfd52aaa5c24691b947">llvm::MachO::N_STAB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad152fa3b2aff735d4a2e4b644dc93b11a6d2d703f3e79b6904f129d79b5915e7e">llvm::MachO::N_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaca65700aad8ca31abbb94cbb03227edac444d073d7dfae9ee37913c3ebc18fa9">llvm::MachO::N_UNDF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a8566ffd52ce0223e6ecc4298a438a721a28ba3855aefcfc5bf5bdf4e9f75562a4">llvm::MachO::N_WEAK_DEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a8566ffd52ce0223e6ecc4298a438a721ae26e92b75aa9de849f70b2efba5bfba5">llvm::MachO::N_WEAK_REF</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431acc6eb3e8d6f0fb38a6f3eb9ddef198af">llvm::object::BasicSymbolRef::SF_Absolute</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a917d4e0252fa1d20b2086b2e99e78e57">llvm::object::BasicSymbolRef::SF_Common</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a3936e16c4ba4b109e74006ad9bdc06f8">llvm::object::BasicSymbolRef::SF_Exported</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ac0848bf2e216fe6f4664820d93ab7265">llvm::object::BasicSymbolRef::SF_FormatSpecific</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a1cc593ee22b60969ba0a3cb1e5e21b34">llvm::object::BasicSymbolRef::SF_Global</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a204140e5ce85b4dc444bf37cb0d8e402">llvm::object::BasicSymbolRef::SF_Hidden</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a9660b615b36c70668b966e987719d9d6">llvm::object::BasicSymbolRef::SF_Indirect</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ad1cfe0c449b3dd82ae0eaeff1da6f766">llvm::object::BasicSymbolRef::SF_None</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a586a24e61bc504778e4c89c8bb929e90">llvm::object::BasicSymbolRef::SF_Thumb</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ad1131f10939b205635a0dc81ca3c45d7">llvm::object::BasicSymbolRef::SF_Undefined</a> and <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ac199a3dc25299a191397723e89fd303e">llvm::object::BasicSymbolRef::SF_Weak</a>.</p>


<p>Referenced by <a href="#ad12defbd432cf6bb7f7b05f956681e03">getSymbolAlignment</a>.</p>

</div>
</div>

### getSymbolIndex() {#a24c6aaf027b70314a4e7cb05b34ab302}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachOObjectFile::getSymbolIndex (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2632 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a>, <a href="#a9451d5e767c3b97403785baaff3c6a44">getSymtabLoadCommand</a>, <a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ad0cbda82482585d346b65687e2f3a38a">llvm::XCOFF::SymbolTableEntrySize</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#ae6c74170eea156826ddfb4b61bd5d043">llvm::MachO::symtab_command::symoff</a>.</p>


<p>Referenced by <a href="#a79ff60972cb2fd27ac7280c9e5052d4a">getSymbolName</a> and <a href="#a35b89b3d8775f01eeeb4e36769e2b435">getSymbolSection</a>.</p>

</div>
</div>

### getSymbolName() {#a79ff60972cb2fd27ac7280c9e5052d4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; MachOObjectFile::getSymbolName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Declaration at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1775 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="#ad451ffea9d6ef1b5ec634f176bf6dcad">getStringTableData</a>, <a href="#a24c6aaf027b70314a4e7cb05b34ab302">getSymbolIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a0e0b242aa7cb8cb269f5ea9973a9f605">getSymbolTableEntryBase</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a8160a3004ff47f73b842d7030269ff3d">malformedError</a>.</p>

</div>
</div>

### getSymbolSection() {#a35b89b3d8775f01eeeb4e36769e2b435}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; section_iterator &gt; MachOObjectFile::getSymbolSection (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Declaration at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1912 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>, <a href="#a24c6aaf027b70314a4e7cb05b34ab302">getSymbolIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a0e0b242aa7cb8cb269f5ea9973a9f605">getSymbolTableEntryBase</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a8160a3004ff47f73b842d7030269ff3d">malformedError</a>, <a href="#a274c4612a46dd1b0aa44ca5745642e2b">section_end</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a>.</p>


<p>Referenced by <a href="#abfea148e3e5693c88962ce5add39bf56">getSymbolType</a>.</p>

</div>
</div>

### getSymbolSectionID() {#a2f79817cbc7f06dd7a434e20281a0ad5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachOObjectFile::getSymbolSectionID (<a href="/web-llvm/docs/api/classes/llvm/object/symbolref">SymbolRef</a> Symb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1927 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a4edbb76f7d11d8891e10524e40bdaa85">llvm::object::BasicSymbolRef::getRawDataRefImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a0e0b242aa7cb8cb269f5ea9973a9f605">getSymbolTableEntryBase</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a23fe52bbc164a30ba18e057d37bd2283">llvm::object::ObjectFile::SymbolRef</a>.</p>

</div>
</div>

### getSymbolTableEntry() {#a2df84b6031947d33d436f49b29a699b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::nlist MachOObjectFile::getSymbolTableEntry (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> DRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 651 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4643 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>.</p>


<p>Referenced by <a href="#a58bd45157985a622dba76ecef6375f4d">checkSymbolTable</a> and <a href="#ad823d575bb639330180ee9d8b43bf237">getNValue</a>.</p>

</div>
</div>

### getSymbolType() {#abfea148e3e5693c88962ce5add39bf56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SymbolRef::Type &gt; MachOObjectFile::getSymbolType (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Declaration at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1843 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a35b89b3d8775f01eeeb4e36769e2b435">getSymbolSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a0e0b242aa7cb8cb269f5ea9973a9f605">getSymbolTableEntryBase</a>, <a href="/web-llvm/docs/api/classes/llvm/object/sectionref/#a85b626cd5412e6c9739be877e575bbc7">llvm::object::SectionRef::isBSS</a>, <a href="/web-llvm/docs/api/classes/llvm/object/sectionref/#a5bf5dc4878ff8425b046dc9b4d5ce95c">llvm::object::SectionRef::isData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaca65700aad8ca31abbb94cbb03227eda149563e67229adecb388a1b15854f767">llvm::MachO::N_SECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad152fa3b2aff735d4a2e4b644dc93b11afa536dc3de031dfd52aaa5c24691b947">llvm::MachO::N_STAB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad152fa3b2aff735d4a2e4b644dc93b11a6d2d703f3e79b6904f129d79b5915e7e">llvm::MachO::N_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaca65700aad8ca31abbb94cbb03227edac444d073d7dfae9ee37913c3ebc18fa9">llvm::MachO::N_UNDF</a>, <a href="#a274c4612a46dd1b0aa44ca5745642e2b">section_end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a8a501fedaaa3e562541580b8f1db3975">llvm::object::SymbolRef::ST_Data</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04afe6722fa933ffee4c116ee60c2de5049">llvm::object::SymbolRef::ST_Debug</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a2fcf5b0171fb8526218be425765b5da1">llvm::object::SymbolRef::ST_Function</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a076f193658db35c0f4d60f9e0a3e329f">llvm::object::SymbolRef::ST_Other</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a2d334a713a4916963744a0cc31ab9552">llvm::object::SymbolRef::ST_Unknown</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getSymtabLoadCommand() {#a9451d5e767c3b97403785baaff3c6a44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::symtab_command MachOObjectFile::getSymtabLoadCommand ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4835 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#ac73d1a8cae2f0eb315e69c92f67fde5f">llvm::MachO::symtab_command::cmd</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#a97a6ee3c99c53b7173818e4ed375276f">llvm::MachO::symtab_command::cmdsize</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#a1fe8ad1b38dc828beefc5757d7dc1a3a">llvm::MachO::symtab_command::nsyms</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#ad664b3b2032af10912280b74303ee21d">llvm::MachO::symtab_command::stroff</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#a1459968fe2ad55b364958070dde70c6e">llvm::MachO::symtab_command::strsize</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#ae6c74170eea156826ddfb4b61bd5d043">llvm::MachO::symtab_command::symoff</a>.</p>


<p>Referenced by <a href="#a58bd45157985a622dba76ecef6375f4d">checkSymbolTable</a>, <a href="#a19321b2c5a24656fe59c193ae2892453">getRelocationSymbol</a>, <a href="#ad451ffea9d6ef1b5ec634f176bf6dcad">getStringTableData</a>, <a href="#a7d7c96e485022e0023e9b8eec0257f0e">getSymbolByIndex</a>, <a href="#a24c6aaf027b70314a4e7cb05b34ab302">getSymbolIndex</a>, <a href="#a21f780beb96b3c8859b9f75422e2c4f9">symbol_begin</a> and <a href="#aabf498b6cb34cb967c73e3c0c51baee2">symbol_end</a>.</p>

</div>
</div>

### getThreadCommand() {#a53d6fbb63f40bcf11cf7e5d674534440}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::thread_command MachOObjectFile::getThreadCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 701 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4770 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>

</div>
</div>

### getUuid() {#a99d3e689123b378a1d01ac234f9a6d3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint8_t &gt; MachOObjectFile::getUuid ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 741 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 5279 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h/#a276e8a32e0bbf024aadd9420b8f2d3b3">offsetof</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/anonymous-symbolize-cpp-/#a992787f0142954b821c221ff5a2c921f">llvm::symbolize::anonymous{Symbolize.cpp}::darwinDsymMatchesBinary</a>.</p>

</div>
</div>

### getUuidCommand() {#a983feccca34dfdfebe0d79c35c166d7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::uuid_command MachOObjectFile::getUuidCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 677 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4710 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a4f3081cf8f364816d9a91b6e24d10fba">readMachOHeader</a>.</p>

</div>
</div>

### getVersionMinLoadCommand() {#a9d29d7cb48a7f246f1c0f4507def2aa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::version_min_command MachOObjectFile::getVersionMinLoadCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">LoadCommandInfo</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4675 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a65d683ab0721978a7568df291210a549">getStruct</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#ab42803a7054d1210223d0e72ec575d22">constructTriples</a>.</p>

</div>
</div>

### hasPageZeroSegment() {#ac3e05b2d5f00c589ed0d5a9e24c2be59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::MachOObjectFile::hasPageZeroSegment ()</td>
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



<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/bindrebaseseginfo/#aaaf6cee47713cc12a459bc779d459f13">llvm::object::BindRebaseSegInfo::BindRebaseSegInfo</a>.</p>

</div>
</div>

### is64Bit() {#a9c9aed90376ff1c700f89f5d037decff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachOObjectFile::is64Bit ()</td>
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



<p>Declaration at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 5292 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a8dba4a19dc0e1666a117c2aa023c410f">llvm::object::Binary::getMachOType</a> and <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a60b6c7df2a6f0927102c0e2a23dd0b2e">llvm::object::Binary::getType</a>.</p>


<p>Referenced by <a href="#a460d0b147c8ce41bfda4bcb3f20f6061">bindTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a21566fd3bc19b4348f0deed830e19199">checkDysymtabCommand</a>, <a href="#a58bd45157985a622dba76ecef6375f4d">checkSymbolTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a197ed26dbc11fa1cf315ab378b657ec4">checkSymtabCommand</a>, <a href="#a07de7aaa40f390071913260478a848ca">getBytesInAddress</a>, <a href="#a216609c43afe05c3da08214afdc8e72b">getFileFormatName</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d77869bd604539426d81bd418ce875f">getFirstLoadCommandInfo</a>, <a href="#a10ac2a63f6a950994aae39057eeca34a">getHeader64</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#afdea79cf3204fe335d9ebceb78e6a778">getNextLoadCommandInfo</a>, <a href="#ad823d575bb639330180ee9d8b43bf237">getNValue</a>, <a href="#aaacf649b0759051f6c5327e44b82f8aa">getRelocation</a>, <a href="#a19321b2c5a24656fe59c193ae2892453">getRelocationSymbol</a>, <a href="#ac223e702ae7330bc836e547bf1023278">getSectionAddress</a>, <a href="#a12de1fc762e4d94c86bbdffd6a472df4">getSectionAlignment</a>, <a href="#ae9721b8484141c4d955c6830762a072b">getSectionContents</a>, <a href="#af0c6e225cf80ae36a9994bd1e79e8655">getSectionSize</a>, <a href="#a7d7c96e485022e0023e9b8eec0257f0e">getSymbolByIndex</a>, <a href="#a24c6aaf027b70314a4e7cb05b34ab302">getSymbolIndex</a>, <a href="#ab046bef50272d4e0d9abf45b017feaaa">isSectionStripped</a>, <a href="#abb55e4947514d8643390aacdaa4a7736">lazyBindTable</a>, <a href="#a42eea1d21f273fb22eb18192e519aaaa">moveSymbolNext</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ab606ca40d5870295837712aa2056f90e">llvm::RuntimeDyldMachO::populateIndirectSymbolPointersSection</a>, <a href="#a1b87e710017438cefd497bd5ef89fdbe">rebaseTable</a>, <a href="#a5b4a2cfae548a9a5cf6228605d4c0e7d">section_rel_end</a>, <a href="#aabf498b6cb34cb967c73e3c0c51baee2">symbol_end</a> and <a href="#a87a504b58d7827fd3f526335f44cc14a">weakBindTable</a>.</p>

</div>
</div>

### isDebugSection() {#a5d343559880ac878c6a999cd0e85517e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachOObjectFile::isDebugSection (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2062 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="#ac459e969de113b3d211c0a4087656dc7">getSectionName</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### isRelocatableObject() {#a5960f71b19779a8db394bae2c9be62c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachOObjectFile::isRelocatableObject ()</td>
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

<p>True if this is a relocatable object (.o/.obj).</p>

<p>Declaration at line 758 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 5309 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/macho/mach-header/#a81b6102d4c7c4130c894948b968d9d24">llvm::MachO::mach_header::filetype</a>, <a href="#a80dc9af48926f9c1b70075f71c6002a7">getHeader</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a4099e754341e36bdbc04624fa2f1e19aa0720b97729bd97889599a4dc76faf0dc">llvm::MachO::MH_OBJECT</a>.</p>

</div>
</div>

### isRelocationScattered() {#ad07c873a9197ed022e779129f28ca028}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachOObjectFile::isRelocationScattered (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a> &amp; RE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 630 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4542 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a633855cb5719de40d81669897cc571c8">llvm::MachO::CPU_TYPE_X86_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#ae148cedd3b13337408aac7949e546eb9">getCPUType</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a737f9117ad9ecb54eff89ae39cc5e0c1">getPlainRelocationAddress</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a5155210832b813b1bb19b1830cad62b5ad528edd5b6f57022a7d7f12b5d8d55c7">llvm::MachO::R_SCATTERED</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp/#a3ebc7dd21b6e9c9781e5ac3e5d9b604e">extractSections</a>, <a href="#ad388361f228398a0d6ccd304f88138fa">getAnyRelocationAddress</a>, <a href="#a942691b0e7a01c33a7aa6b36b28472d2">getAnyRelocationLength</a>, <a href="#a86eeaa5626787e6a0c62d7fef9ea33e9">getAnyRelocationPCRel</a>, <a href="#a43739eb6bed0aa4dc4ac7c50de26674b">getAnyRelocationSection</a>, <a href="#a653a63105b842dd49a3a0921ce6a6d66">getAnyRelocationType</a>, <a href="#a19321b2c5a24656fe59c193ae2892453">getRelocationSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#ae415bc5251a1c0a2bd01a1e7efaa6828">isRelocScattered</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#a731c45f6ccf4dde3198c1d5147c3cb37">llvm::RuntimeDyldMachOAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#ad0cc2b7a34912033f88c7169756683cb">llvm::RuntimeDyldMachOARM::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoi386/#a5bd3ae889a8d52356bd6b32e45c7aa6c">llvm::RuntimeDyldMachOI386::processRelocationRef</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#a59ad91c5ccf9ed8867eab9cc5424b151">llvm::RuntimeDyldMachOX86_64::processRelocationRef</a>.</p>

</div>
</div>

### isSectionBitcode() {#acba45c9f1c0b5b00a3fe59eae613b4fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachOObjectFile::isSectionBitcode (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2162 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a647f0ec13a56dcdcf59ff036090db193">getSectionFinalSegmentName</a> and <a href="#ac459e969de113b3d211c0a4087656dc7">getSectionName</a>.</p>

</div>
</div>

### isSectionBSS() {#a7434406d3c7c482b788bf6db4275831b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachOObjectFile::isSectionBSS (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2054 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#ac5ea45808f76ad3f6b0159739e80d160">getSectionFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a96ef438f63eb95474a1bb24b8ef24e5b">llvm::MachO::S_ATTR_PURE_INSTRUCTIONS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a18315ad92b87c2abc1ff1a795b4119c0">llvm::MachO::S_GB_ZEROFILL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a901e329f9c215482ab4877d7efec0768">llvm::MachO::S_ZEROFILL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a03740c22238cbe574a5d3aaf3cd5d198afcc0f8ee030bc9729199d678956638b3">llvm::MachO::SECTION_TYPE</a>.</p>

</div>
</div>

### isSectionCompressed() {#ac7eb997befeaee6e33d42a249c694d6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachOObjectFile::isSectionCompressed (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2037 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>

</div>
</div>

### isSectionData() {#a0f8cd1e7801f694e4a6c5e109b96773c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachOObjectFile::isSectionData (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2046 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#ac5ea45808f76ad3f6b0159739e80d160">getSectionFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a96ef438f63eb95474a1bb24b8ef24e5b">llvm::MachO::S_ATTR_PURE_INSTRUCTIONS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a18315ad92b87c2abc1ff1a795b4119c0">llvm::MachO::S_GB_ZEROFILL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a901e329f9c215482ab4877d7efec0768">llvm::MachO::S_ZEROFILL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a03740c22238cbe574a5d3aaf3cd5d198afcc0f8ee030bc9729199d678956638b3">llvm::MachO::SECTION_TYPE</a>.</p>

</div>
</div>

### isSectionStripped() {#ab046bef50272d4e0d9abf45b017feaaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachOObjectFile::isSectionStripped (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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

<p>When dsymutil generates the companion file, it strips all unnecessary sections (e.g.</p>


<p>everything in the _TEXT segment) by omitting their body and setting the offset in their corresponding load command to zero.</p>


<p>While the load command itself is valid, reading the section corresponds to reading the number of bytes specified in the load command, starting from offset 0 (i.e. the Mach-O header at the beginning of the file).</p>


<p>Declaration at line 472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2169 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a1a18707996459de69e40ab867eeee801">getSection</a>, <a href="#a4ddf638fa2c882a669517ae17a4e032a">getSection64</a>, <a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/section-64/#a235d0ebc85332907ba154085b3cc0a1a">llvm::MachO::section_64::offset</a>.</p>

</div>
</div>

### isSectionText() {#ac7ac740eb18150e6b303020623754638}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachOObjectFile::isSectionText (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2041 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#ac5ea45808f76ad3f6b0159739e80d160">getSectionFlags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a96ef438f63eb95474a1bb24b8ef24e5b">llvm::MachO::S_ATTR_PURE_INSTRUCTIONS</a>.</p>

</div>
</div>

### isSectionVirtual() {#a76ba9d917492e4d238d3d9062d755494}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachOObjectFile::isSectionVirtual (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2155 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#ac5ea45808f76ad3f6b0159739e80d160">getSectionFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a18315ad92b87c2abc1ff1a795b4119c0">llvm::MachO::S_GB_ZEROFILL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a901e329f9c215482ab4877d7efec0768">llvm::MachO::S_ZEROFILL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a03740c22238cbe574a5d3aaf3cd5d198afcc0f8ee030bc9729199d678956638b3">llvm::MachO::SECTION_TYPE</a>.</p>

</div>
</div>

### lazyBindTable() {#abb55e4947514d8643390aacdaa4a7736}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; bind_iterator &gt; MachOObjectFile::lazyBindTable (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For use iterating over all lazy bind table entries.</p>

<p>Declaration at line 560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4481 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a460d0b147c8ce41bfda4bcb3f20f6061">bindTable</a>, <a href="#a428c19e380ff63f21f2bfb4fdf0078b5">getDyldInfoLazyBindOpcodes</a>, <a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machobindentry/#af6efd0f55e33298ac3bb484e6fd285b9a46a9ebdb80117bfa1f0cdea65438290a">llvm::object::MachOBindEntry::Lazy</a>.</p>

</div>
</div>

### load\_commands() {#a9397f336b10a2f4db6c6d5a8f9b49224}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; MachOObjectFile::load_command_iterator &gt; MachOObjectFile::load_commands ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4515 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a1e9d2dd4b0a109f60a8c056f4031c5d2">begin_load_commands</a>, <a href="#abcf9c2d9ce13a839012103af5556a2c3">end_load_commands</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#ab42803a7054d1210223d0e72ec575d22">constructTriples</a>, <a href="#ac696b4147be1f37d5b9180fe83371658">getSegmentContents</a>, <a href="#adb68429296d9cd8a13b4aa3f10f2e780">getSegmentContents</a> and <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a4f3081cf8f364816d9a91b6e24d10fba">readMachOHeader</a>.</p>

</div>
</div>

### locrel\_begin() {#ad103fd8ebc431f075697c16d4e66f9e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">relocation_iterator MachOObjectFile::locrel_begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2216 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a198fe5e1de4053e999d41555cb796801">llvm::object::ObjectFile::RelocationRef</a>.</p>

</div>
</div>

### locrel\_end() {#afc59d7882fd3b78d7d8bd063816f450d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">relocation_iterator MachOObjectFile::locrel_end ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2224 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a4479f956205d53f462400c0f9e98674a">getDysymtabLoadCommand</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a198fe5e1de4053e999d41555cb796801">llvm::object::ObjectFile::RelocationRef</a>.</p>

</div>
</div>

### mapDebugSectionName() {#a9ebf76d221187db6bf7395a664923d80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef MachOObjectFile::mapDebugSectionName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Maps a debug section name to a standard DWARF section name.</p>

<p>Declaration at line 760 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 5340 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a> and <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>.</p>

</div>
</div>

### mapReflectionSectionNameToEnumValue() {#ac5d1811aaaa04d131a3a65d89888aab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::binaryformat::Swift5ReflectionSectionKind MachOObjectFile::mapReflectionSectionNameToEnumValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName)</td>
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



<p>Declaration at line 763 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 5390 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a> and <a href="/web-llvm/docs/api/namespaces/llvm/binaryformat/#ab355a2b14b4cc35373b4526fbfab894da80eaeeee65cce2c1b9fa9a5741956f9a">llvm::binaryformat::unknown</a>.</p>

</div>
</div>

### moveRelocationNext() {#aa7ed0f240e545eaf6ff91ed1128637e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOObjectFile::moveRelocationNext (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Rel)</td>
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



<p>Declaration at line 486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2233 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2820613261c431d4de10b49e30b90ae4">llvm::object::DataRefImpl::b</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>.</p>

</div>
</div>

### moveSectionNext() {#a046bf39ae1f6f6cb4bd3f6910e96a9fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOObjectFile::moveSectionNext (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Sec)</td>
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



<p>Declaration at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1933 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>.</p>

</div>
</div>

### moveSymbolNext() {#a42eea1d21f273fb22eb18192e519aaaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOObjectFile::moveSymbolNext (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Symb)</td>
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



<p>Declaration at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1768 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ad0cbda82482585d346b65687e2f3a38a">llvm::XCOFF::SymbolTableEntrySize</a>.</p>

</div>
</div>

### ReadULEB128s() {#ab6717ca91fe3922480a18f3e4250e611}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOObjectFile::ReadULEB128s (uint64_t Index, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 745 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 5297 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a6f2f68613d44758a66e49320fb075a02">llvm::DataExtractor::getULEB128</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a6e304ff95b5d1ea04529da35d5307d6f">getFunctionStarts</a>.</p>

</div>
</div>

### RebaseEntryCheckSegAndOffsets() {#a3c92441972e6447b39be377ed4e70c3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::object::MachOObjectFile::RebaseEntryCheckSegAndOffsets (int32_t SegIndex, uint64_t SegOffset, uint8_t PointerSize, uint64_t Count=1, uint64_t Skip=0)</td>
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



<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>.</p>

</div>
</div>

### rebaseTable() {#a1b87e710017438cefd497bd5ef89fdbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; rebase_iterator &gt; MachOObjectFile::rebaseTable (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For use iterating over all rebase table entries.</p>

<p>Declaration at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3814 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a8bf468d783b97cfaf64cce155ccc9365">getDyldInfoRebaseOpcodes</a>, <a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a> and <a href="#a1b87e710017438cefd497bd5ef89fdbe">rebaseTable</a>.</p>


<p>Referenced by <a href="#a1b87e710017438cefd497bd5ef89fdbe">rebaseTable</a>.</p>

</div>
</div>

### section\_begin() {#a56dc12deef303c47e57819035ab2f2f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">section_iterator MachOObjectFile::section_begin ()</td>
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



<p>Declaration at line 513 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2644 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#a280cc6694e181e13e4c9a79870b0626a">llvm::RuntimeDyldMachO::getSectionByAddress</a>.</p>

</div>
</div>

### section\_end() {#a274c4612a46dd1b0aa44ca5745642e2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">section_iterator MachOObjectFile::section_end ()</td>
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



<p>Declaration at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2649 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a>.</p>


<p>Referenced by <a href="#a43739eb6bed0aa4dc4ac7c50de26674b">getAnyRelocationSection</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#a280cc6694e181e13e4c9a79870b0626a">llvm::RuntimeDyldMachO::getSectionByAddress</a>, <a href="#a35b89b3d8775f01eeeb4e36769e2b435">getSymbolSection</a>, <a href="#abfea148e3e5693c88962ce5add39bf56">getSymbolType</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#acb7257d8eec274d18e7916a0d552a2d7">llvm::RuntimeDyldMachO::processScatteredVANILLA</a>.</p>

</div>
</div>

### section\_rel\_begin() {#a4db2c6874a1695b79e947621f7bad0ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">relocation_iterator MachOObjectFile::section_rel_begin (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2175 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a198fe5e1de4053e999d41555cb796801">llvm::object::ObjectFile::RelocationRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp/#a3ebc7dd21b6e9c9781e5ac3e5d9b604e">extractSections</a> and <a href="#a47b6dea5d2bb082590a6749c9ac51039">section_rel_begin</a>.</p>

</div>
</div>

### section\_rel\_begin() {#a47b6dea5d2bb082590a6749c9ac51039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">relocation_iterator MachOObjectFile::section_rel_begin (unsigned Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2888 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a> and <a href="#a4db2c6874a1695b79e947621f7bad0ad">section_rel_begin</a>.</p>

</div>
</div>

### section\_rel\_end() {#a5b4a2cfae548a9a5cf6228605d4c0e7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">relocation_iterator MachOObjectFile::section_rel_end (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2183 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a>, <a href="#a1a18707996459de69e40ab867eeee801">getSection</a>, <a href="#a4ddf638fa2c882a669517ae17a4e032a">getSection64</a>, <a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/section/#adc915d5c4ef2ef12c64ad681e366287e">llvm::MachO::section::nreloc</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/section-64/#a8dd58f519ee76b78b1efbf95071b1124">llvm::MachO::section_64::nreloc</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a198fe5e1de4053e999d41555cb796801">llvm::object::ObjectFile::RelocationRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp/#a3ebc7dd21b6e9c9781e5ac3e5d9b604e">extractSections</a> and <a href="#a2bc5a3bf6742bc5fddcd83660fa27034">section_rel_end</a>.</p>

</div>
</div>

### section\_rel\_end() {#a2bc5a3bf6742bc5fddcd83660fa27034}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">relocation_iterator MachOObjectFile::section_rel_end (unsigned Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2894 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a7fdc4ddba62f47c71da3252c30ce9441">llvm::object::DataRefImpl::a</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a4f65e798a8ff3a72293bdaf9a6538e3b">llvm::object::DataRefImpl::d</a> and <a href="#a5b4a2cfae548a9a5cf6228605d4c0e7d">section_rel_end</a>.</p>

</div>
</div>

### symbol\_begin() {#a21f780beb96b3c8859b9f75422e2c4f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">basic_symbol_iterator MachOObjectFile::symbol_begin ()</td>
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



<p>Declaration at line 504 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2596 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a7d7c96e485022e0023e9b8eec0257f0e">getSymbolByIndex</a>, <a href="#a9451d5e767c3b97403785baaff3c6a44">getSymtabLoadCommand</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#a1fe8ad1b38dc828beefc5757d7dc1a3a">llvm::MachO::symtab_command::nsyms</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a23fe52bbc164a30ba18e057d37bd2283">llvm::object::ObjectFile::SymbolRef</a>.</p>

</div>
</div>

### symbol\_end() {#aabf498b6cb34cb967c73e3c0c51baee2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">basic_symbol_iterator MachOObjectFile::symbol_end ()</td>
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



<p>Declaration at line 505 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2605 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a3d9162ba919b64a3930354acc96f098b">getPtr</a>, <a href="#a9451d5e767c3b97403785baaff3c6a44">getSymtabLoadCommand</a>, <a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#a1fe8ad1b38dc828beefc5757d7dc1a3a">llvm::MachO::symtab_command::nsyms</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a23fe52bbc164a30ba18e057d37bd2283">llvm::object::ObjectFile::SymbolRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ad0cbda82482585d346b65687e2f3a38a">llvm::XCOFF::SymbolTableEntrySize</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/symtab-command/#ae6c74170eea156826ddfb4b61bd5d043">llvm::MachO::symtab_command::symoff</a>.</p>


<p>Referenced by <a href="#a19321b2c5a24656fe59c193ae2892453">getRelocationSymbol</a>.</p>

</div>
</div>

### weakBindTable() {#a87a504b58d7827fd3f526335f44cc14a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; bind_iterator &gt; MachOObjectFile::weakBindTable (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For use iterating over all weak bind table entries.</p>

<p>Declaration at line 563 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4486 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#a460d0b147c8ce41bfda4bcb3f20f6061">bindTable</a>, <a href="#ac6987c2142793b0d0eb897b4eb2c2712">getDyldInfoWeakBindOpcodes</a>, <a href="#a9c9aed90376ff1c700f89f5d037decff">is64Bit</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machobindentry/#af6efd0f55e33298ac3bb484e6fd285b9a7324e3727807d95037eb19d304fd91ec">llvm::object::MachOBindEntry::Weak</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getSymbolValueImpl() {#a52a23ba1858dc6655a925ed1df3db27d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachOObjectFile::getSymbolValueImpl (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Declaration at line 846 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1821 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Header {#a4883a0c75b5154762599156fc1d27ab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::mach_header llvm::object::MachOObjectFile::Header</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 850 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="#a95b14a72437abf5ec6cb9d25596eb3e4">getArchTriple</a>, <a href="#a766c3350d64dde8af24ef7b600b11185">getChainedFixupsSegments</a>, <a href="#a11261ec56e31921149aa022482d80e7e">getDyldChainedFixupTargets</a> and <a href="#a80dc9af48926f9c1b70075f71c6002a7">getHeader</a>.</p>

</div>
</div>

### Header64 {#a0d6204611b3f1b7f9772b6165a8f91b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::mach_header_64 llvm::object::MachOObjectFile::Header64</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 849 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="#a10ac2a63f6a950994aae39057eeca34a">getHeader64</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#aaa385e63c4c044f9d7f5028113fd10f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::object::MachOObjectFile llvm::object::MachOObjectFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 851 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### BindRebaseSectionTable {#ac7537115abb16fb59a59be6af5ba1a74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;BindRebaseSegInfo&gt; llvm::object::MachOObjectFile::BindRebaseSectionTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 861 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### BuildTools {#aaad1be53fc2557587f32945ea335e2d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BuildToolList llvm::object::MachOObjectFile::BuildTools</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 859 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### DataInCodeLoadCmd {#a45e837ae756c7f16f813255560242005}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::object::MachOObjectFile::DataInCodeLoadCmd = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 864 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### DyldChainedFixupsLoadCmd {#a128ebb7c3505862dd45a1752073c4567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::object::MachOObjectFile::DyldChainedFixupsLoadCmd = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 868 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### DyldExportsTrieLoadCmd {#a868b5efb596a0e505e5c83ccac4f9cb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::object::MachOObjectFile::DyldExportsTrieLoadCmd = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 869 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### DyldInfoLoadCmd {#a13ca873ebf0c98a47176931013683676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::object::MachOObjectFile::DyldInfoLoadCmd = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 866 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### DysymtabLoadCmd {#a3b6d2e8189483a02f909be96679b3a81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::object::MachOObjectFile::DysymtabLoadCmd = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 863 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### FuncStartsLoadCmd {#a3f3936e7e894d0ac9bde970f10e30b26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::object::MachOObjectFile::FuncStartsLoadCmd = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 867 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### HasPageZeroSegment {#a53c7ba241f612d3d35fb621156c2d0eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::MachOObjectFile::HasPageZeroSegment = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### Libraries {#aedd60923ff3eb57477ea87f1acbc93c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LibraryList llvm::object::MachOObjectFile::Libraries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 855 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### LibrariesShortNames {#afa3661f61ae4762ac09ec2197e137a08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LibraryShortName llvm::object::MachOObjectFile::LibrariesShortNames</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 860 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### LinkOptHintsLoadCmd {#a5849dbc8b10e85eaa710c3723b5204cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::object::MachOObjectFile::LinkOptHintsLoadCmd = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 865 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### LoadCommands {#a047861b536671547faaab1f5925a0c23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoadCommandList llvm::object::MachOObjectFile::LoadCommands</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 856 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### MachOFilesetEntryOffset {#a51052c5845d2c56e06e9193b8f1e6248}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::object::MachOObjectFile::MachOFilesetEntryOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 872 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### Sections {#accb56f5e84bdfa748cd34ffabe118ac8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionList llvm::object::MachOObjectFile::Sections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 853 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### SymtabLoadCmd {#af86f04d226c003ea3ab91c2c90adc32f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::object::MachOObjectFile::SymtabLoadCmd = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 862 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### UuidLoadCmd {#a890a10e92635d4b99d4cefa380d17fa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::object::MachOObjectFile::UuidLoadCmd = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 870 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### bindTable() {#af83dd79fbd25f72be320a930b92eb146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; bind_iterator &gt; MachOObjectFile::bindTable (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> * O, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Opcodes, bool is64, <a href="/web-llvm/docs/api/classes/llvm/object/machobindentry/#af6efd0f55e33298ac3bb484e6fd285b9">MachOBindEntry::Kind</a> BKind)</td>
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

<p>For use examining bind opcodes in a <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a>.</p>

<p>Declaration at line 566 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4462 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### classof() {#a6164075d58acb937a7ca44edd9bdbba1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::MachOObjectFile::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/binary">Binary</a> * v)</td>
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



<p>Definition at line 769 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### create() {#a6456a8f4d04f36afe434911ec571ba3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; MachOObjectFile &gt; &gt; MachOObjectFile::create (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object, bool IsLittleEndian, bool Is64Bits, uint32_t UniversalCputype=0, uint32_t UniversalIndex=0, size_t MachOFilesetEntryOffset=0)</td>
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



<p>Declaration at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 1254 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a3bcb896473d4c0e5275a58bf731ee899">llvm::object::ObjectFile::createMachOObjectFile</a>.</p>

</div>
</div>

### exports() {#a99ce62ce3455a7a99df0daaee4fd516e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; export_iterator &gt; MachOObjectFile::exports (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Trie, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> * O=nullptr)</td>
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

<p>For use examining a trie not in a <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a>.</p>

<p>Declaration at line 539 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3227 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### findDsymObjectMembers() {#a301ba38f5a267f3cf123d6a9f551e3fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; std::string &gt; &gt; MachOObjectFile::findDsymObjectMembers (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path)</td>
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

<p>If the input path is a .dSYM bundle (as created by the dsymutil tool), return the paths to the object files found in the bundle, otherwise return an empty vector.</p>


<p>If the path appears to be a .dSYM bundle but no objects were found or there was a filesystem error, then return an error.</p>


<p>Declaration at line 838 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 5347 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f4ffaa2f15fc8f612a233e3b45510c0">llvm::createFileError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#ad1056825d31bf187d0be430c51aac281">llvm::sys::path::extension</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#afed705977bd3f8af4b19b0fd57c0adf4">llvm::sys::fs::is_directory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546ba2e70fc89b08f26fa3fc77694c91e8f7a">llvm::no_such_file_or_directory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca4676601564b208338edf7317182f473e">llvm::sys::fs::regular_file</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a35c103b5fb70a66a1cb5da3b56f588a1">llvm::sys::path::remove_dots</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a5f126cc7b64d31cd709215b48656d83d">llvm::sys::fs::status</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5cad978ac65911e3b23055a644703f89615">llvm::sys::fs::symlink_file</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca415c07e20d98e11ce0d5e52a2ce2572f">llvm::sys::fs::type_unknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/macho/dylibreader/#a1fbf6763e62eb4e5268f421eee37d6b1">llvm::MachO::DylibReader::accumulateSourceLocFromDSYM</a> and <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#ad3a7b88fce11b12853e7b60a06a033ec">llvm::InstrProfCorrelator::get</a>.</p>

</div>
</div>

### getArch() {#ab5c6a0f3fd86301240cc7cbe9b2a1716}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::ArchType MachOObjectFile::getArch (uint32_t CPUType, uint32_t CPUSubType)</td>
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



<p>Declaration at line 750 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2688 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af26b2aa05e5a49b91b981143e0e49a34">llvm::Triple::aarch64_32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">llvm::Triple::arm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47ae4da455e762f086662789406e1f085e0">llvm::MachO::CPU_TYPE_ARM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a33fddb0190d728c25e266a22d64bd7ad">llvm::MachO::CPU_TYPE_ARM64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a03cac236584f93f35c9ff89f2d65b716">llvm::MachO::CPU_TYPE_ARM64_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47aa9f8e9712ff2848d650f3c5d8c43c2f8">llvm::MachO::CPU_TYPE_I386</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a630a338da04bb807aac2b41f8fe4e6e7">llvm::MachO::CPU_TYPE_POWERPC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a6f5e12941e8587f9157b470d297fa451">llvm::MachO::CPU_TYPE_POWERPC64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a633855cb5719de40d81669897cc571c8">llvm::MachO::CPU_TYPE_X86_64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704">llvm::Triple::ppc</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">llvm::Triple::ppc64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5b44ea359fcb23c7b1bfdc029979614c">llvm::Triple::UnknownArch</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">llvm::Triple::x86</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>

</div>
</div>

### getArchTriple() {#a12d459ca91f226639852d575af2f1f36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple MachOObjectFile::getArchTriple (uint32_t CPUType, uint32_t CPUSubType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char ** McpuDefault=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char ** ArchFlag=nullptr)</td>
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



<p>Declaration at line 751 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2709 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac55ffefe5905580a4f7bad9c73250482a4e2da395b7669ab4b4b61c91d59430a0">llvm::MachO::CPU_SUBTYPE_ARM64_32_V8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac1c361fc17a664c6c8eb2deb666a495aa8520fa7ada41507bd9affc1763435e2e">llvm::MachO::CPU_SUBTYPE_ARM64_ALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac1c361fc17a664c6c8eb2deb666a495aa371e02a5be76919ad4f0176d3c81a223">llvm::MachO::CPU_SUBTYPE_ARM64E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35daff65a2a2e4c45b92bef46ef737af0250">llvm::MachO::CPU_SUBTYPE_ARM_V4T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35da2aba7ad89534306dd50fbd898c7a17ad">llvm::MachO::CPU_SUBTYPE_ARM_V5TEJ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35da561b67be1fb77d9eff6a5a3beaecd95d">llvm::MachO::CPU_SUBTYPE_ARM_V6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35da99a7d8c3d13be67ffdbe24f8a0f7cf0c">llvm::MachO::CPU_SUBTYPE_ARM_V6M</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35da0c055c23e0811aa0db0d6d53060a5b89">llvm::MachO::CPU_SUBTYPE_ARM_V7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35dac2e49349f0163fe1f71a1ded22e3f49a">llvm::MachO::CPU_SUBTYPE_ARM_V7EM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35da924279e3d69d7d0cbdebe029eecc11ed">llvm::MachO::CPU_SUBTYPE_ARM_V7K</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35da52697bfd7c14e98a528e53a1fbdea33c">llvm::MachO::CPU_SUBTYPE_ARM_V7M</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35daf84be5758df808a4722cde3519645725">llvm::MachO::CPU_SUBTYPE_ARM_V7S</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35da7b4daee73f7665f4580737c8ad3d6b9f">llvm::MachO::CPU_SUBTYPE_ARM_XSCALE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae86e82720723217878cee426edacb5cea4560b8aea1445b3cdd6382b7f9d637ae">llvm::MachO::CPU_SUBTYPE_I386_ALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aefdb2fb41f0943557d9436ec51c6ab08af6e05a7fc658dcb0b82b70cb66497529">llvm::MachO::CPU_SUBTYPE_MASK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a912c7d3d71ff10e3710dae142cf2e129abe6e563133c3b815b0bdd18f34f1b699">llvm::MachO::CPU_SUBTYPE_POWERPC_ALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae86e82720723217878cee426edacb5ceaa924bb600517a47108514a58b30e9df1">llvm::MachO::CPU_SUBTYPE_X86_64_ALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae86e82720723217878cee426edacb5cea77d4de2bbc7e17e45a135907d3772e93">llvm::MachO::CPU_SUBTYPE_X86_64_H</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47ae4da455e762f086662789406e1f085e0">llvm::MachO::CPU_TYPE_ARM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a33fddb0190d728c25e266a22d64bd7ad">llvm::MachO::CPU_TYPE_ARM64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a03cac236584f93f35c9ff89f2d65b716">llvm::MachO::CPU_TYPE_ARM64_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47aa9f8e9712ff2848d650f3c5d8c43c2f8">llvm::MachO::CPU_TYPE_I386</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a630a338da04bb807aac2b41f8fe4e6e7">llvm::MachO::CPU_TYPE_POWERPC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a6f5e12941e8587f9157b470d297fa451">llvm::MachO::CPU_TYPE_POWERPC64</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a633855cb5719de40d81669897cc571c8">llvm::MachO::CPU_TYPE_X86_64</a>.</p>

</div>
</div>

### getBuildPlatform() {#a58d6e199af0293405aecbdd473952c07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::object::MachOObjectFile::getBuildPlatform (uint32_t platform)</td>
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



<p>Definition at line 791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a90c017a4d672e046b7e98f67edf082ec">llvm::format_hex</a>.</p>

</div>
</div>

### getBuildTool() {#a535da955115db82b34074588a172b401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::object::MachOObjectFile::getBuildTool (uint32_t tools)</td>
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



<p>Definition at line 806 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a90c017a4d672e046b7e98f67edf082ec">llvm::format_hex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a98ad92d3b09d986c952b2f20f7b48575ab443ddf97069a6532222f3e3b0e48c0c">llvm::MachO::TOOL_CLANG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a98ad92d3b09d986c952b2f20f7b48575a77c397b3385f0d98bd1bd2373c582a34">llvm::MachO::TOOL_LD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a98ad92d3b09d986c952b2f20f7b48575a60efa15a4040b79f61acb377b4fe66c2">llvm::MachO::TOOL_LLD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a98ad92d3b09d986c952b2f20f7b48575a8df824ff94bc7c30fd4448832e0a13c1">llvm::MachO::TOOL_SWIFT</a>.</p>

</div>
</div>

### getHostArch() {#a7dae944f91922455073b3d3d90ca8182}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple MachOObjectFile::getHostArch ()</td>
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



<p>Declaration at line 756 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2846 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ae329f3571e25025c5496be7a9746a94f">llvm::sys::getDefaultTargetTriple</a>.</p>

</div>
</div>

### getValidArchs() {#ac81b6bccdec58d66ed395f5754e5ee31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; StringRef &gt; MachOObjectFile::getValidArchs ()</td>
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



<p>Declaration at line 755 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2855 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Referenced by <a href="#ac74a3d3d939d03f7aaf8984924636f5a">isValidArch</a>.</p>

</div>
</div>

### getVersionMinMajor() {#abe73c477bf18bd1868cba1bff6c10f45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::MachOObjectFile::getVersionMinMajor (<a href="/web-llvm/docs/api/structs/llvm/macho/version-min-command">MachO::version_min_command</a> &amp; C, bool SDK)</td>
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



<p>Definition at line 774 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### getVersionMinMinor() {#ae7cb36c89b950fb13e0e652288410677}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::MachOObjectFile::getVersionMinMinor (<a href="/web-llvm/docs/api/structs/llvm/macho/version-min-command">MachO::version_min_command</a> &amp; C, bool SDK)</td>
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



<p>Definition at line 780 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### getVersionMinUpdate() {#a90e87895af41ed29b6da842bff759177}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::MachOObjectFile::getVersionMinUpdate (<a href="/web-llvm/docs/api/structs/llvm/macho/version-min-command">MachO::version_min_command</a> &amp; C, bool SDK)</td>
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



<p>Definition at line 786 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### getVersionString() {#a0751fcfc33e532271437039379f8a72d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::object::MachOObjectFile::getVersionString (uint32_t version)</td>
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



<p>Definition at line 821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a41972fe6f3fab862543b7b835a714f9b">llvm::utostr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>

</div>
</div>

### guessLibraryShortName() {#af3e1bca92860141baaad0a536334d09f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef MachOObjectFile::guessLibraryShortName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool &amp; isFramework, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Suffix)</td>
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



<p>Declaration at line 747 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2427 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a372f87e2cac1c83389c98554dc44806da043d23e54edc5360a7785ae212d1b806">llvm::Lib</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a97d45ce069c1a09ca84672df63acf096">llvm::StringRef::rfind</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5d4c961b9b6f1da17df74b4496ecb30e">llvm::StringRef::slice</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="#afea73c1af002769dde1fb465f40b6ac1">getLibraryShortNameByIndex</a>.</p>

</div>
</div>

### isMachOPairedReloc() {#a8bb417c5fd462f13301f4def55f0c49b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachOObjectFile::isMachOPairedReloc (uint64_t RelocType, uint64_t Arch)</td>
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



<p>Declaration at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 5401 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">llvm::Triple::arm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa78b1160279497250f62c414267853f1f">llvm::MachO::ARM64_RELOC_SUBTRACTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfaf6e91ff8795152a02d4310c2debff044">llvm::MachO::ARM_RELOC_HALF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa7ddb841f45e7015c8cbb2694c78205d8">llvm::MachO::ARM_RELOC_HALF_SECTDIFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa280d7617c91ec05b4daf2c62202dc11f">llvm::MachO::ARM_RELOC_LOCAL_SECTDIFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa94f9f6152db97d1fab522c2273d9e1d1">llvm::MachO::ARM_RELOC_SECTDIFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa0a27931fcd66197e422c658d96f32470">llvm::MachO::GENERIC_RELOC_LOCAL_SECTDIFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfac5f8fc2f99eb5ec9106ac3bc226f3aed">llvm::MachO::GENERIC_RELOC_SECTDIFF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">llvm::Triple::thumb</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">llvm::Triple::x86</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfac646834a5cf45e7b071d4d554ec653ed">llvm::MachO::X86_64_RELOC_SUBTRACTOR</a>.</p>

</div>
</div>

### isValidArch() {#ac74a3d3d939d03f7aaf8984924636f5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachOObjectFile::isValidArch (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ArchFlag)</td>
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



<p>Declaration at line 754 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 2850 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="#ac81b6bccdec58d66ed395f5754e5ee31">getValidArchs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>

</div>
</div>

### rebaseTable() {#aec8303f38ce8e043a58bf1818abb1da3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; rebase_iterator &gt; MachOObjectFile::rebaseTable (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> * O, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Opcodes, bool is64)</td>
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

<p>For use examining rebase opcodes in a <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a>.</p>

<p>Declaration at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3801 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
