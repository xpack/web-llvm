---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/relocationref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RelocationRef` Class

<p>This is a value type class that represents a single relocation in the list of relocations in the object file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::object::RelocationRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">llvm/Object/ObjectFile.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/elfrelocationref">ELFRelocationRef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97cd936e0dbdf74282c70b59434ef6d8">RelocationRef</a> ()=default</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c2bc02351111a95b55000ac375f443c">RelocationRef</a> (DataRefImpl RelocationP, const ObjectFile *Owner)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/object/relocationref">RelocationRef</a>. <a href="#a5c2bc02351111a95b55000ac375f443c">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4350b6c301ce016c8286f93f26f764dc">operator==</a> (const RelocationRef &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6888a715557c033610b2aad8b95318fb">moveNext</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aa71653bc8ee52493adf9343d9ac44d">getOffset</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83bcab1a4f6a9aec56d6a40487f82a5e">getSymbol</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a14c842fb698c94611978d94b7cf166">getType</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4faf8b9fa8fa74ac1062275d89e73ed">getTypeName</a> (SmallVectorImpl&lt; char &gt; &amp;Result) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a string that represents the type of this relocation. <a href="#ab4faf8b9fa8fa74ac1062275d89e73ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd93a9353f94b029cdfa295b88874b38">getRawDataRefImpl</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a68972e67eca0c5723212eff1289422">getObject</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3b8e74b3be202e2d0f7d654304a93f2">RelocationPimpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45d3bc28ebed22151a46856805feb5b5">OwningObject</a> = nullptr</td>
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

<p>This is a value type class that represents a single relocation in the list of relocations in the object file.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RelocationRef() {#a97cd936e0dbdf74282c70b59434ef6d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::RelocationRef::RelocationRef ()</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a97cd936e0dbdf74282c70b59434ef6d8">RelocationRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/elfrelocationref/#ac347c1a3f76e8eea2fc2557361d41d34">llvm::object::ELFRelocationRef::ELFRelocationRef</a>, <a href="#a4350b6c301ce016c8286f93f26f764dc">operator==</a> and <a href="#a97cd936e0dbdf74282c70b59434ef6d8">RelocationRef</a>.</p>

</div>
</div>

### RelocationRef() {#a5c2bc02351111a95b55000ac375f443c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::RelocationRef::RelocationRef (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> RelocationP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> * Owner)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/object/relocationref">RelocationRef</a>.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#a4350b6c301ce016c8286f93f26f764dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::RelocationRef::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/relocationref">RelocationRef</a> &amp; Other)</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a97cd936e0dbdf74282c70b59434ef6d8">RelocationRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getObject() {#a9a68972e67eca0c5723212eff1289422}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ObjectFile * llvm::object::RelocationRef::getObject ()</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/elfrelocationref/#ac347c1a3f76e8eea2fc2557361d41d34">llvm::object::ELFRelocationRef::ELFRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfrelocationref/#a7f37404ddc9c36b26595c92bfd62910c">llvm::object::ELFRelocationRef::getObject</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ab8281e64fb0c8b5bc71fdb5876df6c9d">llvm::RuntimeDyldMachO::makeValueAddendPCRel</a>.</p>

</div>
</div>

### getOffset() {#a6aa71653bc8ee52493adf9343d9ac44d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::RelocationRef::getOffset ()</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#abaf648d88dc891045a7cd0e989789370">llvm::RuntimeDyldMachO::getRelocationEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ab8281e64fb0c8b5bc71fdb5876df6c9d">llvm::RuntimeDyldMachO::makeValueAddendPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a9114640d8c0477c8c9c502e8acd7cbf7">llvm::RuntimeDyldCOFFAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffi386/#a47afe575c279c175037d664bde7e53a3">llvm::RuntimeDyldCOFFI386::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#a200d4c53b00f55a8d0911279bf576c18">llvm::RuntimeDyldCOFFThumb::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#afcf3722d9ca669767870af1a84877924">llvm::RuntimeDyldCOFFX86_64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#acb7257d8eec274d18e7916a0d552a2d7">llvm::RuntimeDyldMachO::processScatteredVANILLA</a>.</p>

</div>
</div>

### getRawDataRefImpl() {#acd93a9353f94b029cdfa295b88874b38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataRefImpl llvm::object::RelocationRef::getRawDataRefImpl ()</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/elfrelocationref/#a705b6e9363a0fe644bea482dc295cf83">llvm::object::ELFRelocationRef::getAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#abaf648d88dc891045a7cd0e989789370">llvm::RuntimeDyldMachO::getRelocationEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/macholinkgraphbuilder/#ad63fca6e6e001f3e97eebaa2c397ffc9">llvm::jitlink::MachOLinkGraphBuilder::getRelocationInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a73ddbfba78956c4ed1b7c2ab5b816dbb">llvm::object::MachOObjectFile::getRelocationRelocatedSection</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ac01d9cc5d2d4a3b6662c7096e54bf8ad">llvm::RuntimeDyldMachO::getRelocationValueRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#a731c45f6ccf4dde3198c1d5147c3cb37">llvm::RuntimeDyldMachOAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#ad0cc2b7a34912033f88c7169756683cb">llvm::RuntimeDyldMachOARM::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoi386/#a5bd3ae889a8d52356bd6b32e45c7aa6c">llvm::RuntimeDyldMachOI386::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#a59ad91c5ccf9ed8867eab9cc5424b151">llvm::RuntimeDyldMachOX86_64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#acb7257d8eec274d18e7916a0d552a2d7">llvm::RuntimeDyldMachO::processScatteredVANILLA</a> and <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#aca0c5ead089272fe21045ffd6895b298">llvm::object::ELFObjectFile&lt; ELFT &gt;::section_rel_end</a>.</p>

</div>
</div>

### getSymbol() {#a83bcab1a4f6a9aec56d6a40487f82a5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">symbol_iterator llvm::object::RelocationRef::getSymbol ()</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ac01d9cc5d2d4a3b6662c7096e54bf8ad">llvm::RuntimeDyldMachO::getRelocationValueRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a9114640d8c0477c8c9c502e8acd7cbf7">llvm::RuntimeDyldCOFFAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffi386/#a47afe575c279c175037d664bde7e53a3">llvm::RuntimeDyldCOFFI386::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#a200d4c53b00f55a8d0911279bf576c18">llvm::RuntimeDyldCOFFThumb::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#afcf3722d9ca669767870af1a84877924">llvm::RuntimeDyldCOFFX86_64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#ad0cc2b7a34912033f88c7169756683cb">llvm::RuntimeDyldMachOARM::processRelocationRef</a>.</p>

</div>
</div>

### getType() {#a3a14c842fb698c94611978d94b7cf166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::RelocationRef::getType ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a9114640d8c0477c8c9c502e8acd7cbf7">llvm::RuntimeDyldCOFFAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffi386/#a47afe575c279c175037d664bde7e53a3">llvm::RuntimeDyldCOFFI386::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#a200d4c53b00f55a8d0911279bf576c18">llvm::RuntimeDyldCOFFThumb::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#afcf3722d9ca669767870af1a84877924">llvm::RuntimeDyldCOFFX86_64::processRelocationRef</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a>.</p>

</div>
</div>

### getTypeName() {#ab4faf8b9fa8fa74ac1062275d89e73ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::RelocationRef::getTypeName (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Result)</td>
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

<p>Get a string that represents the type of this relocation.</p>


<p>This is for display purposes only.</p>


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a9114640d8c0477c8c9c502e8acd7cbf7">llvm::RuntimeDyldCOFFAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffi386/#a47afe575c279c175037d664bde7e53a3">llvm::RuntimeDyldCOFFI386::processRelocationRef</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#a200d4c53b00f55a8d0911279bf576c18">llvm::RuntimeDyldCOFFThumb::processRelocationRef</a>.</p>

</div>
</div>

### moveNext() {#a6888a715557c033610b2aad8b95318fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::RelocationRef::moveNext ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### OwningObject {#a45d3bc28ebed22151a46856805feb5b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ObjectFile* llvm::object::RelocationRef::OwningObject = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### RelocationPimpl {#ab3b8e74b3be202e2d0f7d654304a93f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataRefImpl llvm::object::RelocationRef::RelocationPimpl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
