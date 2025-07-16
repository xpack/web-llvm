---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/dynamicrelocref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DynamicRelocRef` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::object::DynamicRelocRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">llvm/Object/COFF.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a650e486f79d3940cbeef3c7b9c2405d9">COFFObjectFile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d0a81c627ecf13001cb8463d802303c">DynamicRelocRef</a> ()=default</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af62bcfea8c669f8936ff1c2c1aa9f32b">DynamicRelocRef</a> (const void *Header, const COFFObjectFile *Owner)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fee0273520ffaede0bb55ef696c7f83">operator==</a> (const DynamicRelocRef &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7523123bb5bee3d9fe8936bc4f7e355d">moveNext</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6340234f5dfd87fba237c6427a7c7221">getType</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19a16d028317311f7ddb3d5dc706c9e7">getContents</a> (ArrayRef&lt; uint8_t &gt; &amp;Ref) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#ad89863cbbbe43129f7fb98b4d77e1d7b">arm64x_reloc_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14e72d8da8272877aec734b67972a0eb">arm64x_reloc_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#ad89863cbbbe43129f7fb98b4d77e1d7b">arm64x_reloc_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a667314594711210c817f136e0966c0e6">arm64x_reloc_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#ad89863cbbbe43129f7fb98b4d77e1d7b">arm64x_reloc_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7037077f3f2a200ce1ed2b3f6cc82937">arm64x_relocs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadef81647a70af2a355f69c9bd2e0a8f">validate</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile">COFFObjectFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f085eb24495f675eb6cbc93ecc8cb7b">Obj</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a92c333814e04c3204b842296509c8c">Header</a></td>
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


<p>Definition at line 1351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<div class="doxySectionDef">

## Friends

### COFFObjectFile {#a650e486f79d3940cbeef3c7b9c2405d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile">COFFObjectFile</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Reference <a href="#a650e486f79d3940cbeef3c7b9c2405d9">COFFObjectFile</a>.</p>


<p>Referenced by <a href="#a650e486f79d3940cbeef3c7b9c2405d9">COFFObjectFile</a> and <a href="#af62bcfea8c669f8936ff1c2c1aa9f32b">DynamicRelocRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DynamicRelocRef() {#a4d0a81c627ecf13001cb8463d802303c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::DynamicRelocRef::DynamicRelocRef ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Referenced by <a href="#a0fee0273520ffaede0bb55ef696c7f83">operator==</a>.</p>

</div>
</div>

### DynamicRelocRef() {#af62bcfea8c669f8936ff1c2c1aa9f32b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::DynamicRelocRef::DynamicRelocRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * Header, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile">COFFObjectFile</a> * Owner)</td>
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



<p>Definition at line 1354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="#a650e486f79d3940cbeef3c7b9c2405d9">COFFObjectFile</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#a0fee0273520ffaede0bb55ef696c7f83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DynamicRelocRef::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/dynamicrelocref">DynamicRelocRef</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1934 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#a4d0a81c627ecf13001cb8463d802303c">DynamicRelocRef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### arm64x\_reloc\_begin() {#a14e72d8da8272877aec734b67972a0eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">arm64x_reloc_iterator DynamicRelocRef::arm64x_reloc_begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 2057 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="#a19a16d028317311f7ddb3d5dc706c9e7">getContents</a>, <a href="#a6340234f5dfd87fba237c6427a7c7221">getType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a345b3a1b6871f21b2ebc3a314cb7c5a5a29324aa9942197c3a4b8a44d6690e96f">llvm::COFF::IMAGE_DYNAMIC_RELOCATION_ARM64X</a>.</p>


<p>Referenced by <a href="#a7037077f3f2a200ce1ed2b3f6cc82937">arm64x_relocs</a>.</p>

</div>
</div>

### arm64x\_reloc\_end() {#a667314594711210c817f136e0966c0e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">arm64x_reloc_iterator DynamicRelocRef::arm64x_reloc_end ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 2066 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="#a19a16d028317311f7ddb3d5dc706c9e7">getContents</a>, <a href="#a6340234f5dfd87fba237c6427a7c7221">getType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a345b3a1b6871f21b2ebc3a314cb7c5a5a29324aa9942197c3a4b8a44d6690e96f">llvm::COFF::IMAGE_DYNAMIC_RELOCATION_ARM64X</a>.</p>


<p>Referenced by <a href="#a7037077f3f2a200ce1ed2b3f6cc82937">arm64x_relocs</a>.</p>

</div>
</div>

### arm64x\_relocs() {#a7037077f3f2a200ce1ed2b3f6cc82937}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; arm64x_reloc_iterator &gt; DynamicRelocRef::arm64x_relocs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 2075 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#a14e72d8da8272877aec734b67972a0eb">arm64x_reloc_begin</a>, <a href="#a667314594711210c817f136e0966c0e6">arm64x_reloc_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### getContents() {#a19a16d028317311f7ddb3d5dc706c9e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DynamicRelocRef::getContents (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &amp; Ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1986 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>


<p>Referenced by <a href="#a14e72d8da8272877aec734b67972a0eb">arm64x_reloc_begin</a> and <a href="#a667314594711210c817f136e0966c0e6">arm64x_reloc_end</a>.</p>

</div>
</div>

### getType() {#a6340234f5dfd87fba237c6427a7c7221}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t DynamicRelocRef::getType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1961 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a14e72d8da8272877aec734b67972a0eb">arm64x_reloc_begin</a> and <a href="#a667314594711210c817f136e0966c0e6">arm64x_reloc_end</a>.</p>

</div>
</div>

### moveNext() {#a7523123bb5bee3d9fe8936bc4f7e355d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DynamicRelocRef::moveNext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1938 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### validate() {#aadef81647a70af2a355f69c9bd2e0a8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DynamicRelocRef::validate ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 2009 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Header {#a7a92c333814e04c3204b842296509c8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t* llvm::object::DynamicRelocRef::Header</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### Obj {#a4f085eb24495f675eb6cbc93ecc8cb7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const COFFObjectFile* llvm::object::DynamicRelocRef::Obj</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
