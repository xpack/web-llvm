---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/runtimedyldcoffaarch64
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RuntimeDyldCOFFAArch64` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::RuntimeDyldCOFFAArch64 { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffaarch64-h">ExecutionEngine/RuntimeDyld/Targets/RuntimeDyldCOFFAArch64.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41edb4d9d27e254e93a355c505adc3c8">RuntimeDyldCOFFAArch64</a> (RuntimeDyld::MemoryManager &amp;MM, JITSymbolResolver &amp;Resolver)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22ce49b2d9fc67b8904648dbe2b2dc3d">getStubAlignment</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36536db6d311c696a2053fc12f2aa1bb">getMaxStubSize</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; uint64_t, uint64_t, uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c59308f5da9f18a578d5dfaed1285a1">generateRelocationStub</a> (unsigned SectionID, StringRef TargetName, uint64_t Offset, uint64_t RelType, uint64_t Addend, StubMap &amp;Stubs)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9114640d8c0477c8c9c502e8acd7cbf7">processRelocationRef</a> (unsigned SectionID, object::relocation_iterator RelI, const object::ObjectFile &amp;Obj, ObjSectionToIDMap &amp;ObjSectionToID, StubMap &amp;Stubs) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses one or more object file relocations (some object files use relocation pairs) and stores it to Relocations or SymbolRelocations (this depends on the object file type). <a href="#a9114640d8c0477c8c9c502e8acd7cbf7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35e8cc985018e504a57093b9e0768d00">resolveRelocation</a> (const RelocationEntry &amp;RE, uint64_t Value) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A object file specific relocation resolver. <a href="#a35e8cc985018e504a57093b9e0768d00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58821594456be509347c899b2b8a23bc">registerEHFrames</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4543e8f07da34a4308b4a59aa3d14027">getImageBase</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a8ad6e355243eab1c1a3993f9bda8b2d1">SID</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e3b9b72ed876795f12d975a86ae9198">UnregisteredEHFrameSections</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a8ad6e355243eab1c1a3993f9bda8b2d1">SID</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a4e49d7fdf81cb1e0b7a9fa8d3b684e">RegisteredEHFrameSections</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a85072d3ccb6d05a33f33e325bfdd2a">ImageBase</a></td>
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


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffaarch64-h">RuntimeDyldCOFFAArch64.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RuntimeDyldCOFFAArch64() {#a41edb4d9d27e254e93a355c505adc3c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RuntimeDyldCOFFAArch64::RuntimeDyldCOFFAArch64 (<a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager">RuntimeDyld::MemoryManager</a> &amp; MM, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolresolver">JITSymbolResolver</a> &amp; Resolver)</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffaarch64-h">RuntimeDyldCOFFAArch64.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#a525c1edda0934652055bd4ca610dcf20">llvm::RuntimeDyldCOFF::RuntimeDyldCOFF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### generateRelocationStub() {#a7c59308f5da9f18a578d5dfaed1285a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; uint64_t, uint64_t, uint64_t &gt; llvm::RuntimeDyldCOFFAArch64::generateRelocationStub (unsigned SectionID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TargetName, uint64_t Offset, uint64_t RelType, uint64_t Addend, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a45d3097b94f4f98303ae36e6c6b7eee6">StubMap</a> &amp; Stubs)</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffaarch64-h">RuntimeDyldCOFFAArch64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref/#a0a2be52a18ce9abea53f265b748a4504">llvm::RelocationValueRef::Addend</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#ad76b1f4f9f930bb5d8942b8bb05875cc">llvm::RuntimeDyldImpl::createStubFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a36536db6d311c696a2053fc12f2aa1bb">getMaxStubSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b1eb13bc1a26f44b7571c5739409efca1b08b3d644394de21ab28d2e8bd426ad">llvm::INTERNAL_REL_ARM64_LONG_BRANCH26</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref/#a56635022517d81457f74c036897231b8">llvm::RelocationValueRef::Offset</a>, <a href="#a35e8cc985018e504a57093b9e0768d00">resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref/#af46f2a8319e7835a38b0b2baaccf13c9">llvm::RelocationValueRef::SectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afce88102ca208741b470edac5342c4b3">llvm::RuntimeDyldImpl::Sections</a> and <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref/#a0830c7b6d0eb10532252bec66b6a02b9">llvm::RelocationValueRef::SymbolName</a>.</p>


<p>Referenced by <a href="#a9114640d8c0477c8c9c502e8acd7cbf7">processRelocationRef</a>.</p>

</div>
</div>

### getMaxStubSize() {#a36536db6d311c696a2053fc12f2aa1bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RuntimeDyldCOFFAArch64::getMaxStubSize ()</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffaarch64-h">RuntimeDyldCOFFAArch64.h</a>.</p>


<p>Referenced by <a href="#a7c59308f5da9f18a578d5dfaed1285a1">generateRelocationStub</a>.</p>

</div>
</div>

### getStubAlignment() {#a22ce49b2d9fc67b8904648dbe2b2dc3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::RuntimeDyldCOFFAArch64::getStubAlignment ()</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffaarch64-h">RuntimeDyldCOFFAArch64.h</a>.</p>

</div>
</div>

### processRelocationRef() {#a9114640d8c0477c8c9c502e8acd7cbf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; object::relocation_iterator &gt; llvm::RuntimeDyldCOFFAArch64::processRelocationRef (unsigned SectionID, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">object::relocation_iterator</a> RelI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a22b1a24bb422a0f0896dd84dff7933e2">ObjSectionToIDMap</a> &amp; ObjSectionToID, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a45d3097b94f4f98303ae36e6c6b7eee6">StubMap</a> &amp; Stubs)</td>
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


<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffaarch64-h">RuntimeDyldCOFFAArch64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a9ee81c156267d67bed9008ed1a954214">llvm::RuntimeDyldImpl::addRelocationForSection</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a5db8c0beafbba922f1600e24fe6898bc">llvm::RuntimeDyldImpl::addRelocationForSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#aa4b6bd8b78d9901ada802b2363341628">llvm::RuntimeDyldImpl::findOrEmitSection</a>, <a href="#a7c59308f5da9f18a578d5dfaed1285a1">generateRelocationStub</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#af0b0733da2d8693287bd3bb04ee6ab80">llvm::RuntimeDyldCOFF::getDLLImportOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#a4178559e89663ce1a69c039e3147a481">llvm::RuntimeDyldCOFF::getImportSymbolPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionentry/#a873c676a0b78fcac1c9840af57815aee">llvm::SectionEntry::getObjAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/object/relocationref/#a6aa71653bc8ee52493adf9343d9ac44d">llvm::object::RelocationRef::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/relocationref/#a83bcab1a4f6a9aec56d6a40487f82a5e">llvm::object::RelocationRef::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#a2fe9aab3874eece3b45203f68bdc6079">llvm::RuntimeDyldCOFF::getSymbolOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/relocationref/#a3a14c842fb698c94611978d94b7cf166">llvm::object::RelocationRef::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/relocationref/#ab4faf8b9fa8fa74ac1062275d89e73ed">llvm::object::RelocationRef::getTypeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4ea5eef7fcc1ce4e904b4674667edcb05d1">llvm::COFF::IMAGE_REL_ARM64_ADDR32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eae2871250d400787e7f8ec6fd55f1ba40">llvm::COFF::IMAGE_REL_ARM64_ADDR32NB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eafe178efa3ce63a8ff56cc587a18db82c">llvm::COFF::IMAGE_REL_ARM64_ADDR64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eac43ef804249b1c1f07711a9866299819">llvm::COFF::IMAGE_REL_ARM64_BRANCH14</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4ea097bfbb62502b9566c9e1985a04b5c6b">llvm::COFF::IMAGE_REL_ARM64_BRANCH19</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eac53ed10f9401665d19e5eefa59984bd9">llvm::COFF::IMAGE_REL_ARM64_BRANCH26</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eaf208e10668d261aed713825f256f420d">llvm::COFF::IMAGE_REL_ARM64_PAGEBASE_REL21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eaafd0e1b4a38680cf94e03fa4c1d29957">llvm::COFF::IMAGE_REL_ARM64_PAGEOFFSET_12A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eacb363e20befbd3ed6e3e871ddf982aa8">llvm::COFF::IMAGE_REL_ARM64_PAGEOFFSET_12L</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eaf22de55fb18b610776fa84d8f4e956ca">llvm::COFF::IMAGE_REL_ARM64_REL21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4ea1dde8be4528eebd8bfb4962a11b91d36">llvm::COFF::IMAGE_REL_ARM64_REL32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4ea079834a37edaf463583319d7578077fd">llvm::COFF::IMAGE_REL_ARM64_SECREL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae865d5defb8785b365f342375822beaa">llvm::support::endian::read32le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a0fa2f859066acd16820ab083040158c9">llvm::support::endian::read64le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a3e48ce01c39d5e5e36eced4e3d3f6f23">llvm::object::ObjectFile::section_end</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afce88102ca208741b470edac5342c4b3">llvm::RuntimeDyldImpl::Sections</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#a7bc0f444aecc9b7aaef7facdb3d2bddb">llvm::object::SymbolicFile::symbol_end</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### registerEHFrames() {#a58821594456be509347c899b2b8a23bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldCOFFAArch64::registerEHFrames ()</td>
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



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffaarch64-h">RuntimeDyldCOFFAArch64.h</a>.</p>

</div>
</div>

### resolveRelocation() {#a35e8cc985018e504a57093b9e0768d00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldCOFFAArch64::resolveRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationentry">RelocationEntry</a> &amp; RE, uint64_t Value)</td>
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

<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffaarch64-h">RuntimeDyldCOFFAArch64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad00527cce4ac88d76673ec97bc0c57da">llvm::add16</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a80213c5b59afecdd125a21b28b9637e9">llvm::RelocationEntry::Addend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eaaf8d91439b6c0c905ee9cd3eca3cea1c">llvm::COFF::IMAGE_REL_ARM64_ABSOLUTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4ea5eef7fcc1ce4e904b4674667edcb05d1">llvm::COFF::IMAGE_REL_ARM64_ADDR32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eae2871250d400787e7f8ec6fd55f1ba40">llvm::COFF::IMAGE_REL_ARM64_ADDR32NB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eafe178efa3ce63a8ff56cc587a18db82c">llvm::COFF::IMAGE_REL_ARM64_ADDR64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eac43ef804249b1c1f07711a9866299819">llvm::COFF::IMAGE_REL_ARM64_BRANCH14</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4ea097bfbb62502b9566c9e1985a04b5c6b">llvm::COFF::IMAGE_REL_ARM64_BRANCH19</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eac53ed10f9401665d19e5eefa59984bd9">llvm::COFF::IMAGE_REL_ARM64_BRANCH26</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eaf208e10668d261aed713825f256f420d">llvm::COFF::IMAGE_REL_ARM64_PAGEBASE_REL21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eaafd0e1b4a38680cf94e03fa4c1d29957">llvm::COFF::IMAGE_REL_ARM64_PAGEOFFSET_12A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eacb363e20befbd3ed6e3e871ddf982aa8">llvm::COFF::IMAGE_REL_ARM64_PAGEOFFSET_12L</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4eaf22de55fb18b610776fa84d8f4e956ca">llvm::COFF::IMAGE_REL_ARM64_REL21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4ea1dde8be4528eebd8bfb4962a11b91d36">llvm::COFF::IMAGE_REL_ARM64_REL32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4ea079834a37edaf463583319d7578077fd">llvm::COFF::IMAGE_REL_ARM64_SECREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4ea6a6d329033fe824d392778107e5349a9">llvm::COFF::IMAGE_REL_ARM64_SECTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b1eb13bc1a26f44b7571c5739409efca1b08b3d644394de21ab28d2e8bd426ad">llvm::INTERNAL_REL_ARM64_LONG_BRANCH26</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a4c2824740d2fcf8bd1f44248bdcd4052">llvm::RelocationEntry::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab89fe4a3f1dc1b523f15e228f00a8574">llvm::or32le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae865d5defb8785b365f342375822beaa">llvm::support::endian::read32le</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a4b339d832145cb7ea79bbb90f5233897">llvm::RelocationEntry::RelType</a>, <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#aec2f9774e1098853d20912f579f501b9">llvm::RelocationEntry::SectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afce88102ca208741b470edac5342c4b3">llvm::RuntimeDyldImpl::Sections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afe9cd0d362607fa28dff081a7723c9dc">llvm::write32AArch64Addr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad5228b17874209f1777d90a8f5b75287">llvm::write32AArch64Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a80cb40734a5dea76db890881dadf50c1">llvm::write32AArch64Ldr</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp/#a4f05956d010455624c13f5eb2217bc8b">write32le</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a46eee35129898d0466b2af97eacb19ee">llvm::support::endian::write64le</a>.</p>


<p>Referenced by <a href="#a7c59308f5da9f18a578d5dfaed1285a1">generateRelocationStub</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getImageBase() {#a4543e8f07da34a4308b4a59aa3d14027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::RuntimeDyldCOFFAArch64::getImageBase ()</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffaarch64-h">RuntimeDyldCOFFAArch64.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ImageBase {#a2a85072d3ccb6d05a33f33e325bfdd2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::RuntimeDyldCOFFAArch64::ImageBase</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffaarch64-h">RuntimeDyldCOFFAArch64.h</a>.</p>

</div>
</div>

### RegisteredEHFrameSections {#a8a4e49d7fdf81cb1e0b7a9fa8d3b684e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SID, 2&gt; llvm::RuntimeDyldCOFFAArch64::RegisteredEHFrameSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffaarch64-h">RuntimeDyldCOFFAArch64.h</a>.</p>

</div>
</div>

### UnregisteredEHFrameSections {#a4e3b9b72ed876795f12d975a86ae9198}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SID, 2&gt; llvm::RuntimeDyldCOFFAArch64::UnregisteredEHFrameSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffaarch64-h">RuntimeDyldCOFFAArch64.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/lib/executionengine/runtimedyld/targets/runtimedyldcoffaarch64-h">RuntimeDyldCOFFAArch64.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
