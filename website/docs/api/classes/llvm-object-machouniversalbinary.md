---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/machouniversalbinary
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MachOUniversalBinary` Class



## Declaration

<div class="doxyDeclaration">
class llvm::object::MachOUniversalBinary { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">llvm/Object/MachOUniversal.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/binary">Binary</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66ced5c57cafe11823df6917a866b17f">MachOUniversalBinary</a> (MemoryBufferRef Souce, Error &amp;Err)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/machouniversalbinary/object-iterator">object_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a084adbcccb9ee43047e737e1f07da745">begin_objects</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/machouniversalbinary/object-iterator">object_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b3142bafcbf3cb4f719d8a58169991a">end_objects</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/machouniversalbinary/object-iterator">object_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f731d354d7269ad1aff01ae8d3a2bac">objects</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a802f2dbab7377e08f8a02ef123dd5f8a">getMagic</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa960a222a515adbe3dc620e30428804">getNumberOfObjects</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/machouniversalbinary/objectforarch">ObjectForArch</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07076459a18346ee7eff313ed1b3ee86">getObjectForArch</a> (StringRef ArchName) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c651dacce72bff08e951493dcf73659">getMachOObjectForArch</a> (StringRef ArchName) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/irobjectfile">IRObjectFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e160de63e8c75d7ef2cc9f020868d2c">getIRObjectForArch</a> (StringRef ArchName, LLVMContext &amp;Ctx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/archive">Archive</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34d2885157a32d05d3fd389617ba5c4a">getArchiveForArch</a> (StringRef ArchName) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bfb707a6fe9546f7e88a9d5362f5162">anchor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd6eb8f0e896779d21810053d5910877">Magic</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c883e994e6ea4ee915e84f8e4f4ab4f">NumberOfObjects</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/machouniversalbinary">MachOUniversalBinary</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a094ea3b3b52a30341f589955d6076434">create</a> (MemoryBufferRef Source)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5c0f4719dcc33bd6e8bf8203d6c6109">classof</a> (Binary const *V)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0ac2adcfd6be41ed526a12ddd2215d2">MaxSectionAlignment</a> = 15</td>
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


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">MachOUniversal.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MachOUniversalBinary() {#a66ced5c57cafe11823df6917a866b17f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachOUniversalBinary::MachOUniversalBinary (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Souce, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">MachOUniversal.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversal-cpp">MachOUniversal.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5efaba206c0c82deb1e8898c4c3aad4b">llvm::object::Binary::Binary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aefdb2fb41f0943557d9436ec51c6ab08af6e05a7fc658dcb0b82b70cb66497529">llvm::MachO::CPU_SUBTYPE_MASK</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa109d22c6d71247dd24ee7ba5670b230a9b343a7482bf7900c441cfffdfaaf5bb">llvm::MachO::FAT_MAGIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa109d22c6d71247dd24ee7ba5670b230a7ee99bd996eb6eda3a4efdd533108991">llvm::MachO::FAT_MAGIC_64</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversal-cpp/#aba032268a29b9c4a5cbbf813370f0c21">getUniversalBinaryStruct</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#af4e569b1876c0dbd751c766d6a1b926aae8d81fb12cacba04ed21f0fd2c1b2ce5">llvm::object::Binary::ID_MachOUniversalBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20ad5a8a27f4e310ea593b285615faaca35">llvm::object::invalid_file_type</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a8160a3004ff47f73b842d7030269ff3d">malformedError</a>, <a href="#ad0ac2adcfd6be41ed526a12ddd2215d2">MaxSectionAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a094ea3b3b52a30341f589955d6076434">create</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machouniversalbinary/objectforarch/#ae50a28178b719e68133f41a2b054ecf7">llvm::object::MachOUniversalBinary::ObjectForArch::ObjectForArch</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin\_objects() {#a084adbcccb9ee43047e737e1f07da745}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">object_iterator llvm::object::MachOUniversalBinary::begin_objects ()</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">MachOUniversal.h</a>.</p>


<p>Referenced by <a href="#a9f731d354d7269ad1aff01ae8d3a2bac">objects</a>.</p>

</div>
</div>

### end\_objects() {#a7b3142bafcbf3cb4f719d8a58169991a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">object_iterator llvm::object::MachOUniversalBinary::end_objects ()</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">MachOUniversal.h</a>.</p>


<p>Referenced by <a href="#a9f731d354d7269ad1aff01ae8d3a2bac">objects</a>.</p>

</div>
</div>

### getArchiveForArch() {#a34d2885157a32d05d3fd389617ba5c4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; Archive &gt; &gt; MachOUniversalBinary::getArchiveForArch (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ArchName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">MachOUniversal.h</a>, definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversal-cpp">MachOUniversal.cpp</a>.</p>


<p>Reference <a href="#a07076459a18346ee7eff313ed1b3ee86">getObjectForArch</a>.</p>

</div>
</div>

### getIRObjectForArch() {#a1e160de63e8c75d7ef2cc9f020868d2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; IRObjectFile &gt; &gt; MachOUniversalBinary::getIRObjectForArch (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ArchName, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">MachOUniversal.h</a>, definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversal-cpp">MachOUniversal.cpp</a>.</p>


<p>Reference <a href="#a07076459a18346ee7eff313ed1b3ee86">getObjectForArch</a>.</p>

</div>
</div>

### getMachOObjectForArch() {#a2c651dacce72bff08e951493dcf73659}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; MachOObjectFile &gt; &gt; MachOUniversalBinary::getMachOObjectForArch (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ArchName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">MachOUniversal.h</a>, definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversal-cpp">MachOUniversal.cpp</a>.</p>


<p>Reference <a href="#a07076459a18346ee7eff313ed1b3ee86">getObjectForArch</a>.</p>

</div>
</div>

### getMagic() {#a802f2dbab7377e08f8a02ef123dd5f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::MachOUniversalBinary::getMagic ()</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">MachOUniversal.h</a>.</p>

</div>
</div>

### getNumberOfObjects() {#aaa960a222a515adbe3dc620e30428804}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::MachOUniversalBinary::getNumberOfObjects ()</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">MachOUniversal.h</a>.</p>

</div>
</div>

### getObjectForArch() {#a07076459a18346ee7eff313ed1b3ee86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; MachOUniversalBinary::ObjectForArch &gt; MachOUniversalBinary::getObjectForArch (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ArchName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">MachOUniversal.h</a>, definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversal-cpp">MachOUniversal.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aa9d094e9a3b7763e4d2813ba8f450b21">llvm::object::arch_not_found</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#a9f731d354d7269ad1aff01ae8d3a2bac">objects</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5b44ea359fcb23c7b1bfdc029979614c">llvm::Triple::UnknownArch</a>.</p>


<p>Referenced by <a href="#a34d2885157a32d05d3fd389617ba5c4a">getArchiveForArch</a>, <a href="#a1e160de63e8c75d7ef2cc9f020868d2c">getIRObjectForArch</a> and <a href="#a2c651dacce72bff08e951493dcf73659">getMachOObjectForArch</a>.</p>

</div>
</div>

### objects() {#a9f731d354d7269ad1aff01ae8d3a2bac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; object_iterator &gt; llvm::object::MachOUniversalBinary::objects ()</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">MachOUniversal.h</a>.</p>


<p>References <a href="#a084adbcccb9ee43047e737e1f07da745">begin_objects</a>, <a href="#a7b3142bafcbf3cb4f719d8a58169991a">end_objects</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#aa01e73e66cd4ea6703e66a9c213f2e6a">llvm::orc::getMachOSliceRangeForTriple</a> and <a href="#a07076459a18346ee7eff313ed1b3ee86">getObjectForArch</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a4bfb707a6fe9546f7e88a9d5362f5162}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOUniversalBinary::anchor ()</td>
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



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">MachOUniversal.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversal-cpp">MachOUniversal.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Magic {#abd6eb8f0e896779d21810053d5910877}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::MachOUniversalBinary::Magic</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">MachOUniversal.h</a>.</p>

</div>
</div>

### NumberOfObjects {#a9c883e994e6ea4ee915e84f8e4f4ab4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::MachOUniversalBinary::NumberOfObjects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">MachOUniversal.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#aa5c0f4719dcc33bd6e8bf8203d6c6109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::MachOUniversalBinary::classof (<a href="/web-llvm/docs/api/classes/llvm/object/binary">Binary</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * V)</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">MachOUniversal.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5efaba206c0c82deb1e8898c4c3aad4b">llvm::object::Binary::Binary</a>.</p>

</div>
</div>

### create() {#a094ea3b3b52a30341f589955d6076434}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; MachOUniversalBinary &gt; &gt; MachOUniversalBinary::create (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Source)</td>
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



<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">MachOUniversal.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversal-cpp">MachOUniversal.cpp</a>.</p>


<p>References <a href="#a66ced5c57cafe11823df6917a866b17f">MachOUniversalBinary</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/object/#aebd3886db896c46327320cfd1ccc808c">llvm::object::createBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#af7d5ad260c22ac8a3f577e0991446a39">llvm::orc::getMachOSliceRangeForTriple</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a23f400453ec5ee74f48de908ba27bc6c">llvm::orc::loadLinkableSliceFromMachOUniversalBinary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### MaxSectionAlignment {#ad0ac2adcfd6be41ed526a12ddd2215d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::MachOUniversalBinary::MaxSectionAlignment = 15</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">MachOUniversal.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp/#a0cf1bd036dc392e17aec8733d9a180e0">calculateFileAlignment</a> and <a href="#a66ced5c57cafe11823df6917a866b17f">MachOUniversalBinary</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">MachOUniversal.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/machouniversal-cpp">MachOUniversal.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
