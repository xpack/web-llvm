---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/runtimedyldcoffthumb
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RuntimeDyldCOFFThumb` Class



## Declaration

<div class="doxyDeclaration">
class llvm::RuntimeDyldCOFFThumb { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffthumb-h">ExecutionEngine/RuntimeDyld/Targets/RuntimeDyldCOFFThumb.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff">RuntimeDyldCOFF</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afce0d119047191cb3f7df8eecf1ca7af">RuntimeDyldCOFFThumb</a> (RuntimeDyld::MemoryManager &amp;MM, JITSymbolResolver &amp;Resolver)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae25304d9c9c211dd642c9274bd475faa">getMaxStubSize</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae71e8902775f8de0490455dc8c929d2f">getJITSymbolFlags</a> (const SymbolRef &amp;SR) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> from a libObject symbol. <a href="#ae71e8902775f8de0490455dc8c929d2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a938120e75bb3044dbc9011b6b1af71fd">getStubAlignment</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">object::relocation_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a200d4c53b00f55a8d0911279bf576c18">processRelocationRef</a> (unsigned SectionID, object::relocation_iterator RelI, const object::ObjectFile &amp;Obj, ObjSectionToIDMap &amp;ObjSectionToID, StubMap &amp;Stubs) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses one or more object file relocations (some object files use relocation pairs) and stores it to Relocations or SymbolRelocations (this depends on the object file type). <a href="#a200d4c53b00f55a8d0911279bf576c18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6339960d2e5a1860dd0ce831fc20c006">resolveRelocation</a> (const RelocationEntry &amp;RE, uint64_t Value) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A object file specific relocation resolver. <a href="#a6339960d2e5a1860dd0ce831fc20c006">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8aadbab00f8290c04405675cd1c1159">registerEHFrames</a> () override</td>
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


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffthumb-h">RuntimeDyldCOFFThumb.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RuntimeDyldCOFFThumb() {#afce0d119047191cb3f7df8eecf1ca7af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RuntimeDyldCOFFThumb::RuntimeDyldCOFFThumb (<a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager">RuntimeDyld::MemoryManager</a> &amp; MM, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolresolver">JITSymbolResolver</a> &amp; Resolver)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffthumb-h">RuntimeDyldCOFFThumb.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#a525c1edda0934652055bd4ca610dcf20">llvm::RuntimeDyldCOFF::RuntimeDyldCOFF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getJITSymbolFlags() {#ae71e8902775f8de0490455dc8c929d2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; JITSymbolFlags &gt; llvm::RuntimeDyldCOFFThumb::getJITSymbolFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/symbolref">SymbolRef</a> &amp; Sym)</td>
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

<p>Generate <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> from a libObject symbol.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffthumb-h">RuntimeDyldCOFFThumb.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/object/coff-section/#a5d5c6f0e1d23df171e3bdd1c027a06e1">llvm::object::coff_section::Characteristics</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ab5c5fe9889d863b8a8fbe02cbf68f662">llvm::object::COFFObjectFile::getCOFFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afd8b5e95c65e3bb62ead0dd58732e382">llvm::RuntimeDyldImpl::getJITSymbolFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/object/sectionref/#af325f1df60eef3a8a8a47e22a1f43c5e">llvm::object::SectionRef::getObject</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#af8b31890b3cf3677a9c279325661e3af">llvm::object::SymbolRef::getSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa64a6c00401f530708fa161270b0b8177">llvm::COFF::IMAGE_SCN_MEM_16BIT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#ac74d5e6c2cf6e4a41c5cd533e7f88fad">isThumb</a>.</p>

</div>
</div>

### getMaxStubSize() {#ae25304d9c9c211dd642c9274bd475faa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RuntimeDyldCOFFThumb::getMaxStubSize ()</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffthumb-h">RuntimeDyldCOFFThumb.h</a>.</p>

</div>
</div>

### getStubAlignment() {#a938120e75bb3044dbc9011b6b1af71fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::RuntimeDyldCOFFThumb::getStubAlignment ()</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffthumb-h">RuntimeDyldCOFFThumb.h</a>.</p>

</div>
</div>

### processRelocationRef() {#a200d4c53b00f55a8d0911279bf576c18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; object::relocation_iterator &gt; llvm::RuntimeDyldCOFFThumb::processRelocationRef (unsigned SectionID, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">object::relocation_iterator</a> RelI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a22b1a24bb422a0f0896dd84dff7933e2">ObjSectionToIDMap</a> &amp; ObjSectionToID, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a45d3097b94f4f98303ae36e6c6b7eee6">StubMap</a> &amp; Stubs)</td>
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

<p>Parses one or more object file relocations (some object files use relocation pairs) and stores it to Relocations or SymbolRelocations (this depends on the object file type).</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Iterator to the next relocation that needs to be parsed.</p></dd>
</dl>


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffthumb-h">RuntimeDyldCOFFThumb.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a9ee81c156267d67bed9008ed1a954214">llvm::RuntimeDyldImpl::addRelocationForSection</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a5db8c0beafbba922f1600e24fe6898bc">llvm::RuntimeDyldImpl::addRelocationForSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#aa4b6bd8b78d9901ada802b2363341628">llvm::RuntimeDyldImpl::findOrEmitSection</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#af0b0733da2d8693287bd3bb04ee6ab80">llvm::RuntimeDyldCOFF::getDLLImportOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#a4178559e89663ce1a69c039e3147a481">llvm::RuntimeDyldCOFF::getImportSymbolPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionentry/#a873c676a0b78fcac1c9840af57815aee">llvm::SectionEntry::getObjAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/object/relocationref/#a6aa71653bc8ee52493adf9343d9ac44d">llvm::object::RelocationRef::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/relocationref/#a83bcab1a4f6a9aec56d6a40487f82a5e">llvm::object::RelocationRef::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#a2fe9aab3874eece3b45203f68bdc6079">llvm::RuntimeDyldCOFF::getSymbolOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/relocationref/#a3a14c842fb698c94611978d94b7cf166">llvm::object::RelocationRef::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/relocationref/#ab4faf8b9fa8fa74ac1062275d89e73ed">llvm::object::RelocationRef::getTypeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a905028c6320edfd212e3cffd365e6cf4">llvm::COFF::IMAGE_REL_ARM_ABSOLUTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a746d514c28aa512d8ddd56dc058e8faf">llvm::COFF::IMAGE_REL_ARM_ADDR32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a4674ff1d84292a919b54e9ebd3d5fd46">llvm::COFF::IMAGE_REL_ARM_ADDR32NB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a99ba87de124124cda61beaeeef90e547">llvm::COFF::IMAGE_REL_ARM_BLX23T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a3ebd5ea614167c6fccba3b326dd215be">llvm::COFF::IMAGE_REL_ARM_BRANCH20T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a8898d58c6174b9ced49e3092764a27b5">llvm::COFF::IMAGE_REL_ARM_BRANCH24T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a865cc9cadbef2c0b2034ed1f7d49a8d3">llvm::COFF::IMAGE_REL_ARM_MOV32T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5aa3675a902af589d1fe8239cb229e834c">llvm::COFF::IMAGE_REL_ARM_SECREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5aa99263a4ddef9c6522025169308d6d80">llvm::COFF::IMAGE_REL_ARM_SECTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abff0d6ad3853141a03b46790c091c8d1">llvm::isThumbFunc</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#ad8a8e68671c17b1a8dde17365f897406">llvm::RuntimeDyldImpl::readBytesUnaligned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a3e48ce01c39d5e5e36eced4e3d3f6f23">llvm::object::ObjectFile::section_end</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afce88102ca208741b470edac5342c4b3">llvm::RuntimeDyldImpl::Sections</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#a7bc0f444aecc9b7aaef7facdb3d2bddb">llvm::object::SymbolicFile::symbol_end</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### registerEHFrames() {#ae8aadbab00f8290c04405675cd1c1159}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldCOFFThumb::registerEHFrames ()</td>
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



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffthumb-h">RuntimeDyldCOFFThumb.h</a>.</p>

</div>
</div>

### resolveRelocation() {#a6339960d2e5a1860dd0ce831fc20c006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldCOFFThumb::resolveRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationentry">RelocationEntry</a> &amp; RE, uint64_t Value)</td>
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

<p>A object file specific relocation resolver.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">RE</td>
<td class="doxyParamItemDescription"><p>The relocation to be resolved</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> symbol address to apply the relocation action</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffthumb-h">RuntimeDyldCOFFThumb.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a80213c5b59afecdd125a21b28b9637e9">llvm::RelocationEntry::Addend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a905028c6320edfd212e3cffd365e6cf4">llvm::COFF::IMAGE_REL_ARM_ABSOLUTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a746d514c28aa512d8ddd56dc058e8faf">llvm::COFF::IMAGE_REL_ARM_ADDR32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a4674ff1d84292a919b54e9ebd3d5fd46">llvm::COFF::IMAGE_REL_ARM_ADDR32NB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a99ba87de124124cda61beaeeef90e547">llvm::COFF::IMAGE_REL_ARM_BLX23T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a3ebd5ea614167c6fccba3b326dd215be">llvm::COFF::IMAGE_REL_ARM_BRANCH20T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a8898d58c6174b9ced49e3092764a27b5">llvm::COFF::IMAGE_REL_ARM_BRANCH24T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a865cc9cadbef2c0b2034ed1f7d49a8d3">llvm::COFF::IMAGE_REL_ARM_MOV32T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5aa3675a902af589d1fe8239cb229e834c">llvm::COFF::IMAGE_REL_ARM_SECREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5aa99263a4ddef9c6522025169308d6d80">llvm::COFF::IMAGE_REL_ARM_SECTION</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a22c888f22e370f437b1185af26ec21d3">llvm::RelocationEntry::IsTargetThumbFunc</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a4c2824740d2fcf8bd1f44248bdcd4052">llvm::RelocationEntry::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a4b339d832145cb7ea79bbb90f5233897">llvm::RelocationEntry::RelType</a>, <a href="/web-llvm/docs/api/structs/llvm/relocationentry/sectionpair/#ae8eb65258b27fa965c977f7e8e3d025d">llvm::RelocationEntry::SectionPair::SectionA</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#aec2f9774e1098853d20912f579f501b9">llvm::RelocationEntry::SectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#af42a708ce2732dc8b604b8d32384ee75">llvm::RelocationEntry::Sections</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afce88102ca208741b470edac5342c4b3">llvm::RuntimeDyldImpl::Sections</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#ac7b095afaba91cf9bf59313c8e94d2d9">llvm::RuntimeDyldImpl::writeBytesUnaligned</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffthumb-h">RuntimeDyldCOFFThumb.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
