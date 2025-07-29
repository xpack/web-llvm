---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/runtimedyldimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RuntimeDyldImpl` Class



## Declaration

<div class="doxyDeclaration">
class llvm::RuntimeDyldImpl { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">ExecutionEngine/RuntimeDyld/RuntimeDyldImpl.h</a>"
</div>

## Derived Classes

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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf">RuntimeDyldELF</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho">RuntimeDyldMachO</a></td>
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

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::deque&lt; <a href="/web-llvm/docs/api/classes/llvm/sectionentry">SectionEntry</a> &gt; <a href="#acf6a023490843587894079e82a5f932f">SectionList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">unsigned <a href="#a8ad6e355243eab1c1a3993f9bda8b2d1">SID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a>, unsigned &gt; <a href="#a22b1a24bb422a0f0896dd84dff7933e2">ObjSectionToIDMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/object/symbolref">SymbolRef</a> &gt; <a href="#a9693f839ffb98a38a3cf620bc36613b3">CommonSymbolList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/relocationentry">RelocationEntry</a>, 64 &gt; <a href="#a43eb198952bc9e33faa657d4cd13a5eb">RelocationList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/relocationvalueref">RelocationValueRef</a>, uintptr_t &gt; <a href="#a45d3097b94f4f98303ae36e6c6b7eee6">StubMap</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c98f8ef5db6e5554327a99a0d745b87">NotifyStubEmittedFunction</a> = <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/#a7ca2c024ef2bb555f0d9c3aae8b40583">RuntimeDyld::NotifyStubEmittedFunction</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a335467c1fc6da6b05bb85b52cfd428ba">RuntimeDyld::LoadedObjectInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a369fb04a71a831101a7bdfa873cb33d0">RuntimeDyldImpl</a> (RuntimeDyld::MemoryManager &amp;MemMgr, JITSymbolResolver &amp;Resolver)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ca2b002382c6a083995e5c0307a388d">~RuntimeDyldImpl</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab33fe725a4ead8129cb4874fa18f2712">setProcessAllSections</a> (bool ProcessAllSections)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/loadedobjectinfo">RuntimeDyld::LoadedObjectInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a791dd5f2ab0b2071a040b97c0ce8c562">loadObject</a> (const object::ObjectFile &amp;Obj)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adada8cf26f3cc4f3560e2af8f7b458bc">getSectionLoadAddress</a> (unsigned SectionID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee6ff05f9ffdbe69760734e002307b18">getSectionAddress</a> (unsigned SectionID) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e48116b879cb9413068e080549d3f47">getSectionContent</a> (unsigned SectionID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac09946fac21b277a58791857159dda69">getSymbolLocalAddress</a> (StringRef Name) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab32409ec13e7d1450227083a972f303e">getSymbolSectionID</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitevaluatedsymbol">JITEvaluatedSymbol</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47b4c96424aa28dc46f2d756ba5e823e">getSymbol</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/jitevaluatedsymbol">JITEvaluatedSymbol</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4965dcbd02c025ceb9683329bf70ba39">getSymbolTable</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af32873ce4ce9becfcc874f9d34f0d793">resolveRelocations</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c0f4b1a5dc30ecf51894a22a51ed441">resolveLocalRelocations</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13ed1aa385513404b0d2bcad53502041">reassignSectionAddress</a> (unsigned SectionID, uint64_t Addr)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04d08776ab3e7bfefea4fed7b22c6613">mapSectionAddress</a> (const void *LocalAddress, uint64_t TargetAddress)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a754e8c8b2570039fabe325bba0053ea1">hasError</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae00b36887501beb4a1c0d5b1272baef8">clearError</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4576876ecc01f47393fd5519d78e0cc7">getErrorString</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29a19907dd2e448344cd8bfae94cac66">isCompatibleFile</a> (const ObjectFile &amp;Obj) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee8e9941d8788cdadb75e127e6690d94">setNotifyStubEmitted</a> (NotifyStubEmittedFunction NotifyStubEmitted)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60870f10414da76f0af4d89d92647642">registerEHFrames</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ea8279ce903e5f1dd9bfc82f6bb57af">deregisterEHFrames</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35ea08a2c201659672a5fc147bb4c03b">finalizeLoad</a> (const ObjectFile &amp;ObjImg, ObjSectionToIDMap &amp;SectionMap)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7343d4154aa28a8bc872b1de1e40df4">getMaxStubSize</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a267138a4cf518ebb229b7c0d59629b66">getStubAlignment</a> ()=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5152bd91da7db6b185d42e839b7a3e82">writeInt16BE</a> (uint8_t *Addr, uint16_t Value)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e2a818eaa1b3883192a5ae226b38a9e">writeInt32BE</a> (uint8_t *Addr, uint32_t Value)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a423b6eebb04795995f7813b4ed73c00c">writeInt64BE</a> (uint8_t *Addr, uint64_t Value)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0a5a1db971902509d6e5f9dc62aca8c">setMipsABI</a> (const ObjectFile &amp;Obj)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8a8e68671c17b1a8dde17365f897406">readBytesUnaligned</a> (uint8_t *Src, unsigned Size) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Endian-aware read Read the least significant Size bytes from Src. <a href="#ad8a8e68671c17b1a8dde17365f897406">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7b095afaba91cf9bf59313c8e94d2d9">writeBytesUnaligned</a> (uint64_t Value, uint8_t *Dst, unsigned Size) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Endian-aware write. <a href="#ac7b095afaba91cf9bf59313c8e94d2d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd8b5e95c65e3bb62ead0dd58732e382">getJITSymbolFlags</a> (const SymbolRef &amp;Sym)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> from a libObject symbol. <a href="#afd8b5e95c65e3bb62ead0dd58732e382">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20888517938004f7256fae2f0d6b89c4">modifyAddressBasedOnFlags</a> (uint64_t Addr, JITSymbolFlags Flags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Modify the given target address based on the given symbol flags. <a href="#a20888517938004f7256fae2f0d6b89c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7516dd41b3867b963148426688fe9ff3">emitCommonSymbols</a> (const ObjectFile &amp;Obj, CommonSymbolList &amp;CommonSymbols, uint64_t CommonSize, uint32_t CommonAlign)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given the common symbols discovered in the object file, emit a new section for them and update the symbol mappings in the object and symbol table. <a href="#a7516dd41b3867b963148426688fe9ff3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dd171407e8c0e19195ea2039f3f83b6">emitSection</a> (const ObjectFile &amp;Obj, const SectionRef &amp;Section, bool IsCode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits section data from the object file to the MemoryManager. <a href="#a7dd171407e8c0e19195ea2039f3f83b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4b6bd8b78d9901ada802b2363341628">findOrEmitSection</a> (const ObjectFile &amp;Obj, const SectionRef &amp;Section, bool IsCode, ObjSectionToIDMap &amp;LocalSections)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find Section in LocalSections. <a href="#aa4b6bd8b78d9901ada802b2363341628">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ee81c156267d67bed9008ed1a954214">addRelocationForSection</a> (const RelocationEntry &amp;RE, unsigned SectionID)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5db8c0beafbba922f1600e24fe6898bc">addRelocationForSymbol</a> (const RelocationEntry &amp;RE, StringRef SymbolName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad76b1f4f9f930bb5d8942b8bb05875cc">createStubFunction</a> (uint8_t *Addr, unsigned AbiVariant=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits long jump instruction to Addr. <a href="#ad76b1f4f9f930bb5d8942b8bb05875cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40f413b46e7b2e713ec1997fe71b2aa1">resolveRelocationList</a> (const RelocationList &amp;Relocs, uint64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resolves relocations from Relocs list with address from <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#a40f413b46e7b2e713ec1997fe71b2aa1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a263a3fecf6a1b50d26130f1ed176dce0">resolveRelocation</a> (const RelocationEntry &amp;RE, uint64_t Value)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A object file specific relocation resolver. <a href="#a263a3fecf6a1b50d26130f1ed176dce0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a220108ed2bc5839a9f8284894a47c5a8">processRelocationRef</a> (unsigned SectionID, relocation_iterator RelI, const ObjectFile &amp;Obj, ObjSectionToIDMap &amp;ObjSectionToID, StubMap &amp;Stubs)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses one or more object file relocations (some object files use relocation pairs) and stores it to Relocations or SymbolRelocations (this depends on the object file type). <a href="#a220108ed2bc5839a9f8284894a47c5a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37c72a2afbbe1c6eee27d8fa2a2e2834">applyExternalSymbolRelocations</a> (const StringMap&lt; JITEvaluatedSymbol &gt; ExternalSymbolMap)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff5abd27370b46872f4470992413c91a">resolveExternalSymbols</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resolve relocations to external symbols. <a href="#aff5abd27370b46872f4470992413c91a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af089befa203447cdf71f665a1993a997">computeTotalAllocSize</a> (const ObjectFile &amp;Obj, uint64_t &amp;CodeSize, Align &amp;CodeAlign, uint64_t &amp;RODataSize, Align &amp;RODataAlign, uint64_t &amp;RWDataSize, Align &amp;RWDataAlign)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3ab5fec568fdd2334001b26dd6d7f35">computeGOTSize</a> (const ObjectFile &amp;Obj)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af12404037d26556e018e61366f026aaa">computeSectionStubBufSize</a> (const ObjectFile &amp;Obj, const SectionRef &amp;Section)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="#a22b1a24bb422a0f0896dd84dff7933e2">ObjSectionToIDMap</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe85af578989c7f3e9627866e7fa4962">loadObjectImpl</a> (const object::ObjectFile &amp;Obj)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf7bb56345cc9540446ef812331f017a">getGOTEntrySize</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a053739959e9149e1dd57423e3140996b">processNewSymbol</a> (const SymbolRef &amp;ObjSymbol, SymbolTableEntry &amp;Entry)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a042ec898366e685c33b16c7967179b6e">relocationNeedsGot</a> (const RelocationRef &amp;R) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8b04315da851e48c69fbf86a1e87f14">relocationNeedsStub</a> (const RelocationRef &amp;R) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9420dc366cfedbf952c959190f126ce">relocationNeedsDLLImportStub</a> (const RelocationRef &amp;R) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a897ccc6208f6a743973bbadd039c67ab">sizeAfterAddingDLLImportStub</a> (unsigned Size) const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager">RuntimeDyld::MemoryManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bc5cceb63d0ccdf06f64b587f1cd80e">MemMgr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitsymbolresolver">JITSymbolResolver</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a688485f7fca0fadd7e492dc12218cd16">Resolver</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#acf6a023490843587894079e82a5f932f">SectionList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afce88102ca208741b470edac5342c4b3">Sections</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae8daafe648d9ff2d5bb937c2d272c64c">RTDyldSymbolTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af95b57a597e7339755eeb2a4e0470943">GlobalSymbolTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; unsigned, <a href="#a43eb198952bc9e33faa657d4cd13a5eb">RelocationList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c55775113ee7e3171e3f7ece1462e1d">Relocations</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="#a43eb198952bc9e33faa657d4cd13a5eb">RelocationList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c12b4806588ffc8548c4f2d53236505">ExternalSymbolRelocations</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab98755e5bcb6af82707f749aab3c474">Arch</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63d27a7beb22a7596ed2f10bdb9a8dda">IsTargetLittleEndian</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa431374d08ab68077b4ba96efe411c72">IsMipsO32ABI</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a940c75979815d8de459e2791701e4853">IsMipsN32ABI</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cd00aae21297a0a228ef733b6b47ba4">IsMipsN64ABI</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7013eadb021bbc67df524aca8a3af8d0">ProcessAllSections</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sys/#a52d48084c5b60251870b6118e4670fee">sys::Mutex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38acc586c344e0db0232becbb9a2923a">lock</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2c98f8ef5db6e5554327a99a0d745b87">NotifyStubEmittedFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1574f80d41478e7569c8546d35119440">NotifyStubEmitted</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accd3f8de90a127cd1e8538b9df936681">HasError</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43f4ef223d6929940f48a82219fc075f">ErrorStr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dfeef2ecf7ff9f91673432765f3b695">finalizeAsync</a> (std::unique_ptr&lt; RuntimeDyldImpl &gt; This, unique_function&lt; void(object::OwningBinary&lt; object::ObjectFile &gt;, std::unique_ptr&lt; RuntimeDyld::LoadedObjectInfo &gt;, Error)&gt; OnEmitted, object::OwningBinary&lt; object::ObjectFile &gt; O, std::unique_ptr&lt; RuntimeDyld::LoadedObjectInfo &gt; Info)</td>
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

## Protected Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bb6f8bb79248648fd25dc7a75661363">AbsoluteSymbolSection</a> = ~0U</td>
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


<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### CommonSymbolList {#a9693f839ffb98a38a3cf620bc36613b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::vector&lt;SymbolRef&gt; llvm::RuntimeDyldImpl::CommonSymbolList</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>

</div>
</div>

### NotifyStubEmittedFunction {#a2c98f8ef5db6e5554327a99a0d745b87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RuntimeDyldImpl::NotifyStubEmittedFunction = 
    RuntimeDyld::NotifyStubEmittedFunction</td>
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



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>

</div>
</div>

### ObjSectionToIDMap {#a22b1a24bb422a0f0896dd84dff7933e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::map&lt;SectionRef, unsigned&gt; llvm::RuntimeDyldImpl::ObjSectionToIDMap</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>

</div>
</div>

### RelocationList {#a43eb198952bc9e33faa657d4cd13a5eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef SmallVector&lt;RelocationEntry, 64&gt; llvm::RuntimeDyldImpl::RelocationList</td>
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



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>

</div>
</div>

### SectionList {#acf6a023490843587894079e82a5f932f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::deque&lt;SectionEntry&gt; llvm::RuntimeDyldImpl::SectionList</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>

</div>
</div>

### SID {#a8ad6e355243eab1c1a3993f9bda8b2d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef unsigned llvm::RuntimeDyldImpl::SID</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>

</div>
</div>

### StubMap {#a45d3097b94f4f98303ae36e6c6b7eee6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::map&lt;RelocationValueRef, uintptr_t&gt; llvm::RuntimeDyldImpl::StubMap</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### RuntimeDyld::LoadedObjectInfo {#a335467c1fc6da6b05bb85b52cfd428ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/loadedobjectinfo">RuntimeDyld::LoadedObjectInfo</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RuntimeDyldImpl() {#a369fb04a71a831101a7bdfa873cb33d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RuntimeDyldImpl::RuntimeDyldImpl (<a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager">RuntimeDyld::MemoryManager</a> &amp; MemMgr, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolresolver">JITSymbolResolver</a> &amp; Resolver)</td>
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



<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>References <a href="#accd3f8de90a127cd1e8538b9df936681">HasError</a>, <a href="#a9bc5cceb63d0ccdf06f64b587f1cd80e">MemMgr</a>, <a href="#a7013eadb021bbc67df524aca8a3af8d0">ProcessAllSections</a> and <a href="#a688485f7fca0fadd7e492dc12218cd16">Resolver</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#a525c1edda0934652055bd4ca610dcf20">llvm::RuntimeDyldCOFF::RuntimeDyldCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#acff5ec4cbde9c943ffd383afdf1e0bb1">llvm::RuntimeDyldELF::RuntimeDyldELF</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#a034c5e05b63e15a357bc5dcff598e1a5">llvm::RuntimeDyldMachO::RuntimeDyldMachO</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RuntimeDyldImpl() {#a6ca2b002382c6a083995e5c0307a388d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeDyldImpl::~RuntimeDyldImpl ()</td>
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



<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clearError() {#ae00b36887501beb4a1c0d5b1272baef8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldImpl::clearError ()</td>
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



<p>Definition at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Reference <a href="#accd3f8de90a127cd1e8538b9df936681">HasError</a>.</p>

</div>
</div>

### deregisterEHFrames() {#a4ea8279ce903e5f1dd9bfc82f6bb57af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldImpl::deregisterEHFrames ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>Reference <a href="#a9bc5cceb63d0ccdf06f64b587f1cd80e">MemMgr</a>.</p>

</div>
</div>

### finalizeLoad() {#a35ea08a2c201659672a5fc147bb4c03b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::RuntimeDyldImpl::finalizeLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; ObjImg, <a href="#a22b1a24bb422a0f0896dd84dff7933e2">ObjSectionToIDMap</a> &amp; SectionMap)</td>
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



<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#afe85af578989c7f3e9627866e7fa4962">loadObjectImpl</a>.</p>

</div>
</div>

### getErrorString() {#a4576876ecc01f47393fd5519d78e0cc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::RuntimeDyldImpl::getErrorString ()</td>
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



<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Reference <a href="#a43f4ef223d6929940f48a82219fc075f">ErrorStr</a>.</p>

</div>
</div>

### getSectionAddress() {#aee6ff05f9ffdbe69760734e002307b18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t * llvm::RuntimeDyldImpl::getSectionAddress (unsigned SectionID)</td>
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



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>References <a href="#a5bb6f8bb79248648fd25dc7a75661363">AbsoluteSymbolSection</a> and <a href="#afce88102ca208741b470edac5342c4b3">Sections</a>.</p>


<p>Referenced by <a href="#ac09946fac21b277a58791857159dda69">getSymbolLocalAddress</a>.</p>

</div>
</div>

### getSectionContent() {#a5e48116b879cb9413068e080549d3f47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::RuntimeDyldImpl::getSectionContent (unsigned SectionID)</td>
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



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>References <a href="#a5bb6f8bb79248648fd25dc7a75661363">AbsoluteSymbolSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a4a30a3fae601106b8b33c0871aa3069d">getAddress</a>, <a href="#ae7343d4154aa28a8bc872b1de1e40df4">getMaxStubSize</a> and <a href="#afce88102ca208741b470edac5342c4b3">Sections</a>.</p>

</div>
</div>

### getSectionLoadAddress() {#adada8cf26f3cc4f3560e2af8f7b458bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::RuntimeDyldImpl::getSectionLoadAddress (unsigned SectionID)</td>
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



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>References <a href="#a5bb6f8bb79248648fd25dc7a75661363">AbsoluteSymbolSection</a> and <a href="#afce88102ca208741b470edac5342c4b3">Sections</a>.</p>


<p>Referenced by <a href="#a37c72a2afbbe1c6eee27d8fa2a2e2834">applyExternalSymbolRelocations</a>, <a href="#a47b4c96424aa28dc46f2d756ba5e823e">getSymbol</a>, <a href="#a4965dcbd02c025ceb9683329bf70ba39">getSymbolTable</a> and <a href="#a9c0f4b1a5dc30ecf51894a22a51ed441">resolveLocalRelocations</a>.</p>

</div>
</div>

### getSymbol() {#a47b4c96424aa28dc46f2d756ba5e823e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITEvaluatedSymbol llvm::RuntimeDyldImpl::getSymbol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>References <a href="#a5bb6f8bb79248648fd25dc7a75661363">AbsoluteSymbolSection</a>, <a href="#adada8cf26f3cc4f3560e2af8f7b458bc">getSectionLoadAddress</a>, <a href="#af95b57a597e7339755eeb2a4e0470943">GlobalSymbolTable</a> and <a href="#a20888517938004f7256fae2f0d6b89c4">modifyAddressBasedOnFlags</a>.</p>

</div>
</div>

### getSymbolLocalAddress() {#ac09946fac21b277a58791857159dda69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t * llvm::RuntimeDyldImpl::getSymbolLocalAddress (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>References <a href="#a5bb6f8bb79248648fd25dc7a75661363">AbsoluteSymbolSection</a>, <a href="#aee6ff05f9ffdbe69760734e002307b18">getSectionAddress</a> and <a href="#af95b57a597e7339755eeb2a4e0470943">GlobalSymbolTable</a>.</p>

</div>
</div>

### getSymbolSectionID() {#ab32409ec13e7d1450227083a972f303e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RuntimeDyldImpl::getSymbolSectionID (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Reference <a href="#af95b57a597e7339755eeb2a4e0470943">GlobalSymbolTable</a>.</p>

</div>
</div>

### getSymbolTable() {#a4965dcbd02c025ceb9683329bf70ba39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt; StringRef, JITEvaluatedSymbol &gt; llvm::RuntimeDyldImpl::getSymbolTable ()</td>
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



<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>References <a href="#adada8cf26f3cc4f3560e2af8f7b458bc">getSectionLoadAddress</a> and <a href="#af95b57a597e7339755eeb2a4e0470943">GlobalSymbolTable</a>.</p>

</div>
</div>

### hasError() {#a754e8c8b2570039fabe325bba0053ea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RuntimeDyldImpl::hasError ()</td>
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



<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Reference <a href="#accd3f8de90a127cd1e8538b9df936681">HasError</a>.</p>

</div>
</div>

### isCompatibleFile() {#a29a19907dd2e448344cd8bfae94cac66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::RuntimeDyldImpl::isCompatibleFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>

</div>
</div>

### loadObject() {#a791dd5f2ab0b2071a040b97c0ce8c562}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::unique_ptr&lt; RuntimeDyld::LoadedObjectInfo &gt; llvm::RuntimeDyldImpl::loadObject (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>

</div>
</div>

### mapSectionAddress() {#a04d08776ab3e7bfefea4fed7b22c6613}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldImpl::mapSectionAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * LocalAddress, uint64_t TargetAddress)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 576 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a4a30a3fae601106b8b33c0871aa3069d">getAddress</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a38acc586c344e0db0232becbb9a2923a">lock</a>, <a href="#a13ed1aa385513404b0d2bcad53502041">reassignSectionAddress</a> and <a href="#afce88102ca208741b470edac5342c4b3">Sections</a>.</p>

</div>
</div>

### reassignSectionAddress() {#a13ed1aa385513404b0d2bcad53502041}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldImpl::reassignSectionAddress (unsigned SectionID, uint64_t Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 574 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 1093 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#afce88102ca208741b470edac5342c4b3">Sections</a>.</p>


<p>Referenced by <a href="#a04d08776ab3e7bfefea4fed7b22c6613">mapSectionAddress</a>.</p>

</div>
</div>

### registerEHFrames() {#a60870f10414da76f0af4d89d92647642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldImpl::registerEHFrames ()</td>
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



<p>Declaration at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>

</div>
</div>

### resolveLocalRelocations() {#a9c0f4b1a5dc30ecf51894a22a51ed441}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldImpl::resolveLocalRelocations ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 563 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#adada8cf26f3cc4f3560e2af8f7b458bc">getSectionLoadAddress</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a8c55775113ee7e3171e3f7ece1462e1d">Relocations</a> and <a href="#a40f413b46e7b2e713ec1997fe71b2aa1">resolveRelocationList</a>.</p>


<p>Referenced by <a href="#af32873ce4ce9becfcc874f9d34f0d793">resolveRelocations</a>.</p>

</div>
</div>

### resolveRelocations() {#af32873ce4ce9becfcc874f9d34f0d793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldImpl::resolveRelocations ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 561 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a448793631ee01413899a51d948775506">llvm::dumpSectionMemory</a>, <a href="#a43f4ef223d6929940f48a82219fc075f">ErrorStr</a>, <a href="#accd3f8de90a127cd1e8538b9df936681">HasError</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a38acc586c344e0db0232becbb9a2923a">lock</a>, <a href="#aff5abd27370b46872f4470992413c91a">resolveExternalSymbols</a>, <a href="#a9c0f4b1a5dc30ecf51894a22a51ed441">resolveLocalRelocations</a>, <a href="#afce88102ca208741b470edac5342c4b3">Sections</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>.</p>

</div>
</div>

### setNotifyStubEmitted() {#aee8e9941d8788cdadb75e127e6690d94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldImpl::setNotifyStubEmitted (<a href="#a2c98f8ef5db6e5554327a99a0d745b87">NotifyStubEmittedFunction</a> NotifyStubEmitted)</td>
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



<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Reference <a href="#a1574f80d41478e7569c8546d35119440">NotifyStubEmitted</a>.</p>

</div>
</div>

### setProcessAllSections() {#ab33fe725a4ead8129cb4874fa18f2712}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldImpl::setProcessAllSections (bool ProcessAllSections)</td>
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



<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Reference <a href="#a7013eadb021bbc67df524aca8a3af8d0">ProcessAllSections</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addRelocationForSection() {#a9ee81c156267d67bed9008ed1a954214}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldImpl::addRelocationForSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationentry">RelocationEntry</a> &amp; RE, unsigned SectionID)</td>
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



<p>Declaration at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 949 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>Reference <a href="#a8c55775113ee7e3171e3f7ece1462e1d">Relocations</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a9114640d8c0477c8c9c502e8acd7cbf7">llvm::RuntimeDyldCOFFAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffi386/#a47afe575c279c175037d664bde7e53a3">llvm::RuntimeDyldCOFFI386::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#a200d4c53b00f55a8d0911279bf576c18">llvm::RuntimeDyldCOFFThumb::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#afcf3722d9ca669767870af1a84877924">llvm::RuntimeDyldCOFFX86_64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#a731c45f6ccf4dde3198c1d5147c3cb37">llvm::RuntimeDyldMachOAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#ad0cc2b7a34912033f88c7169756683cb">llvm::RuntimeDyldMachOARM::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoi386/#a5bd3ae889a8d52356bd6b32e45c7aa6c">llvm::RuntimeDyldMachOI386::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#a59ad91c5ccf9ed8867eab9cc5424b151">llvm::RuntimeDyldMachOX86_64::processRelocationRef</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#acb7257d8eec274d18e7916a0d552a2d7">llvm::RuntimeDyldMachO::processScatteredVANILLA</a>.</p>

</div>
</div>

### addRelocationForSymbol() {#a5db8c0beafbba922f1600e24fe6898bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldImpl::addRelocationForSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationentry">RelocationEntry</a> &amp; RE, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SymbolName)</td>
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



<p>Declaration at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 954 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#a80213c5b59afecdd125a21b28b9637e9">llvm::RelocationEntry::Addend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0c12b4806588ffc8548c4f2d53236505">ExternalSymbolRelocations</a>, <a href="#af95b57a597e7339755eeb2a4e0470943">GlobalSymbolTable</a> and <a href="#a8c55775113ee7e3171e3f7ece1462e1d">Relocations</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#af0b0733da2d8693287bd3bb04ee6ab80">llvm::RuntimeDyldCOFF::getDLLImportOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ab606ca40d5870295837712aa2056f90e">llvm::RuntimeDyldMachO::populateIndirectSymbolPointersSection</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a9114640d8c0477c8c9c502e8acd7cbf7">llvm::RuntimeDyldCOFFAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffi386/#a47afe575c279c175037d664bde7e53a3">llvm::RuntimeDyldCOFFI386::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#a200d4c53b00f55a8d0911279bf576c18">llvm::RuntimeDyldCOFFThumb::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#afcf3722d9ca669767870af1a84877924">llvm::RuntimeDyldCOFFX86_64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#a731c45f6ccf4dde3198c1d5147c3cb37">llvm::RuntimeDyldMachOAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#ad0cc2b7a34912033f88c7169756683cb">llvm::RuntimeDyldMachOARM::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoi386/#a5bd3ae889a8d52356bd6b32e45c7aa6c">llvm::RuntimeDyldMachOI386::processRelocationRef</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#a59ad91c5ccf9ed8867eab9cc5424b151">llvm::RuntimeDyldMachOX86_64::processRelocationRef</a>.</p>

</div>
</div>

### applyExternalSymbolRelocations() {#a37c72a2afbbe1c6eee27d8fa2a2e2834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldImpl::applyExternalSymbolRelocations (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/jitevaluatedsymbol">JITEvaluatedSymbol</a> &gt; ExternalSymbolMap)</td>
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



<p>Declaration at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 1124 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a16e5eaf2df56249e87019be23ee07695">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::end</a>, <a href="#a0c12b4806588ffc8548c4f2d53236505">ExternalSymbolRelocations</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a49e68e4c86fe0b96c633adea0c366d74">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::find</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#adada8cf26f3cc4f3560e2af8f7b458bc">getSectionLoadAddress</a>, <a href="#af95b57a597e7339755eeb2a4e0470943">GlobalSymbolTable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a20888517938004f7256fae2f0d6b89c4">modifyAddressBasedOnFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="#a688485f7fca0fadd7e492dc12218cd16">Resolver</a>, <a href="#a40f413b46e7b2e713ec1997fe71b2aa1">resolveRelocationList</a> and <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a>.</p>


<p>Referenced by <a href="#aff5abd27370b46872f4470992413c91a">resolveExternalSymbols</a>.</p>

</div>
</div>

### computeGOTSize() {#ab3ab5fec568fdd2334001b26dd6d7f35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RuntimeDyldImpl::computeGOTSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj)</td>
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



<p>Declaration at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 650 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="#acf7bb56345cc9540446ef812331f017a">getGOTEntrySize</a>, <a href="#a042ec898366e685c33b16c7967179b6e">relocationNeedsGot</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#af9eb4120f90b00d473f53ce9877388d0">llvm::object::ObjectFile::section_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a3e48ce01c39d5e5e36eced4e3d3f6f23">llvm::object::ObjectFile::section_end</a>.</p>


<p>Referenced by <a href="#af089befa203447cdf71f665a1993a997">computeTotalAllocSize</a>.</p>

</div>
</div>

### computeSectionStubBufSize() {#af12404037d26556e018e61366f026aaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RuntimeDyldImpl::computeSectionStubBufSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a> &amp; Section)</td>
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



<p>Declaration at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 668 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acd6aa057934751aaac54e5c18bcc18eb">llvm::commonAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b9d675b34f20ba67f1f3213e63935d6">llvm::DataSize</a>, <a href="#ae7343d4154aa28a8bc872b1de1e40df4">getMaxStubSize</a>, <a href="#a267138a4cf518ebb229b7c0d59629b66">getStubAlignment</a>, <a href="#a9bc5cceb63d0ccdf06f64b587f1cd80e">MemMgr</a>, <a href="#ad9420dc366cfedbf952c959190f126ce">relocationNeedsDLLImportStub</a>, <a href="#aa8b04315da851e48c69fbf86a1e87f14">relocationNeedsStub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#af9eb4120f90b00d473f53ce9877388d0">llvm::object::ObjectFile::section_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a3e48ce01c39d5e5e36eced4e3d3f6f23">llvm::object::ObjectFile::section_end</a>, <a href="#a897ccc6208f6a743973bbadd039c67ab">sizeAfterAddingDLLImportStub</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#af089befa203447cdf71f665a1993a997">computeTotalAllocSize</a> and <a href="#a7dd171407e8c0e19195ea2039f3f83b6">emitSection</a>.</p>

</div>
</div>

### computeTotalAllocSize() {#af089befa203447cdf71f665a1993a997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::RuntimeDyldImpl::computeTotalAllocSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, uint64_t &amp; CodeSize, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &amp; CodeAlign, uint64_t &amp; RODataSize, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &amp; RODataAlign, uint64_t &amp; RWDataSize, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &amp; RWDataAlign)</td>
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



<p>Declaration at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ade1143d4174c522458d84c083210c0dd">llvm::computeAllocationSizeForSections</a>, <a href="#ab3ab5fec568fdd2334001b26dd6d7f35">computeGOTSize</a>, <a href="#af12404037d26556e018e61366f026aaa">computeSectionStubBufSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b9d675b34f20ba67f1f3213e63935d6">llvm::DataSize</a>, <a href="#acf7bb56345cc9540446ef812331f017a">getGOTEntrySize</a>, <a href="#a267138a4cf518ebb229b7c0d59629b66">getStubAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92107a34e05220d72ef61d8416be486e">llvm::isReadOnlyData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af84608c14d72c4d634360ce6a536e4a4">llvm::isRequiredForExecution</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3c9c204f9d38e82b1f67b87df65bcab0">llvm::isTLS</a>, <a href="#a7013eadb021bbc67df524aca8a3af8d0">ProcessAllSections</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#af9eb4120f90b00d473f53ce9877388d0">llvm::object::ObjectFile::section_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a3e48ce01c39d5e5e36eced4e3d3f6f23">llvm::object::ObjectFile::section_end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a917d4e0252fa1d20b2086b2e99e78e57">llvm::object::BasicSymbolRef::SF_Common</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#a40c5717c994df60bcbe3d9299f6a5982">llvm::object::SymbolicFile::symbol_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#a7bc0f444aecc9b7aaef7facdb3d2bddb">llvm::object::SymbolicFile::symbol_end</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#afe85af578989c7f3e9627866e7fa4962">loadObjectImpl</a>.</p>

</div>
</div>

### createStubFunction() {#ad76b1f4f9f930bb5d8942b8bb05875cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t * llvm::RuntimeDyldImpl::createStubFunction (uint8_t * Addr, unsigned AbiVariant=0)</td>
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

<p>Emits long jump instruction to Addr.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Pointer to the memory area for emitting target address.</p></dd>
</dl>


<p>Declaration at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 973 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af26b2aa05e5a49b91b981143e0e49a34">llvm::Triple::aarch64_32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a6d5df0cfd7a0b0c0854555554396efd9">llvm::Triple::aarch64_be</a>, <a href="#aab98755e5bcb6af82707f749aab3c474">Arch</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">llvm::Triple::arm</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af65ab1964be676bea302940a45765021">llvm::Triple::armeb</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3a2dfa73ee7c131349904a851d8366903e">llvm::ELF::EF_MIPS_ARCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3a3eeb99b011318e43413b3016a2b5742c">llvm::ELF::EF_MIPS_ARCH_32R6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3ae484313416c10f9de49e4181e9fe0736">llvm::ELF::EF_MIPS_ARCH_64R6</a>, <a href="#a940c75979815d8de459e2791701e4853">IsMipsN32ABI</a>, <a href="#a3cd00aae21297a0a228ef733b6b47ba4">IsMipsN64ABI</a>, <a href="#aa431374d08ab68077b4ba96efe411c72">IsMipsO32ABI</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a7e69e3edde4260406241be26e08fbd7c">llvm::Triple::loongarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">llvm::Triple::ppc64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">llvm::Triple::ppc64le</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af0a491fddfa0a73d2b9074b587ca337f">llvm::Triple::systemz</a>, <a href="#ac7b095afaba91cf9bf59313c8e94d2d9">writeBytesUnaligned</a>, <a href="#a5152bd91da7db6b185d42e839b7a3e82">writeInt16BE</a>, <a href="#a2e2a818eaa1b3883192a5ae226b38a9e">writeInt32BE</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">llvm::Triple::x86</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a7c59308f5da9f18a578d5dfaed1285a1">llvm::RuntimeDyldCOFFAArch64::generateRelocationStub</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#ae5595d78c0d45afeec52fccb70b1b209">llvm::RuntimeDyldCOFFX86_64::generateRelocationStub</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a>.</p>

</div>
</div>

### emitCommonSymbols() {#a7516dd41b3867b963148426688fe9ff3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::RuntimeDyldImpl::emitCommonSymbols (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, <a href="#a9693f839ffb98a38a3cf620bc36613b3">CommonSymbolList</a> &amp; CommonSymbols, uint64_t CommonSize, uint32_t CommonAlign)</td>
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

<p>Given the common symbols discovered in the object file, emit a new section for them and update the symbol mappings in the object and symbol table.</p>

<p>Declaration at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 748 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#afd8b5e95c65e3bb62ead0dd58732e382">getJITSymbolFlags</a>, <a href="#af95b57a597e7339755eeb2a4e0470943">GlobalSymbolTable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a9bc5cceb63d0ccdf06f64b587f1cd80e">MemMgr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99cdcecbadc13087f087c61809bb44f1">llvm::offsetToAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="#afce88102ca208741b470edac5342c4b3">Sections</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#afe85af578989c7f3e9627866e7fa4962">loadObjectImpl</a>.</p>

</div>
</div>

### emitSection() {#a7dd171407e8c0e19195ea2039f3f83b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; unsigned &gt; llvm::RuntimeDyldImpl::emitSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a> &amp; Section, bool IsCode)</td>
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

<p>Emits section data from the object file to the MemoryManager.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsCode</td>
<td class="doxyParamItemDescription"><p>if it's true then allocateCodeSection() will be used for emits, else allocateDataSection() will be used.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>SectionID.</p></dd>
</dl>


<p>Declaration at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 804 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="#af12404037d26556e018e61366f026aaa">computeSectionStubBufSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b9d675b34f20ba67f1f3213e63935d6">llvm::DataSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#a267138a4cf518ebb229b7c0d59629b66">getStubAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92107a34e05220d72ef61d8416be486e">llvm::isReadOnlyData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af84608c14d72c4d634360ce6a536e4a4">llvm::isRequiredForExecution</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3c9c204f9d38e82b1f67b87df65bcab0">llvm::isTLS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac0bcf1406ba361ae499b251f7cd33ac9">llvm::isZeroInit</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a9bc5cceb63d0ccdf06f64b587f1cd80e">MemMgr</a>, <a href="#a7013eadb021bbc67df524aca8a3af8d0">ProcessAllSections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="#afce88102ca208741b470edac5342c4b3">Sections</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#aa4b6bd8b78d9901ada802b2363341628">findOrEmitSection</a>.</p>

</div>
</div>

### findOrEmitSection() {#aa4b6bd8b78d9901ada802b2363341628}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; unsigned &gt; llvm::RuntimeDyldImpl::findOrEmitSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a> &amp; Section, bool IsCode, <a href="#a22b1a24bb422a0f0896dd84dff7933e2">ObjSectionToIDMap</a> &amp; LocalSections)</td>
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

<p>Find Section in LocalSections.</p>


<p>If the secton is not found - emit it and store in LocalSections.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsCode</td>
<td class="doxyParamItemDescription"><p>if it's true then allocateCodeSection() will be used for emmits, else allocateDataSection() will be used.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>SectionID.</p></dd>
</dl>


<p>Declaration at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 930 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>Reference <a href="#a7dd171407e8c0e19195ea2039f3f83b6">emitSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachocrtpbase/#afdfe2cf5151ed6e7266417d9f1db5f80">llvm::RuntimeDyldMachOCRTPBase&lt; Impl &gt;::finalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ac01d9cc5d2d4a3b6662c7096e54bf8ad">llvm::RuntimeDyldMachO::getRelocationValueRef</a>, <a href="#afe85af578989c7f3e9627866e7fa4962">loadObjectImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a9114640d8c0477c8c9c502e8acd7cbf7">llvm::RuntimeDyldCOFFAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffi386/#a47afe575c279c175037d664bde7e53a3">llvm::RuntimeDyldCOFFI386::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#a200d4c53b00f55a8d0911279bf576c18">llvm::RuntimeDyldCOFFThumb::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#afcf3722d9ca669767870af1a84877924">llvm::RuntimeDyldCOFFX86_64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#acb7257d8eec274d18e7916a0d552a2d7">llvm::RuntimeDyldMachO::processScatteredVANILLA</a>.</p>

</div>
</div>

### getGOTEntrySize() {#acf7bb56345cc9540446ef812331f017a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual size_t llvm::RuntimeDyldImpl::getGOTEntrySize ()</td>
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



<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#ab3ab5fec568fdd2334001b26dd6d7f35">computeGOTSize</a> and <a href="#af089befa203447cdf71f665a1993a997">computeTotalAllocSize</a>.</p>

</div>
</div>

### getJITSymbolFlags() {#afd8b5e95c65e3bb62ead0dd58732e382}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; JITSymbolFlags &gt; llvm::RuntimeDyldImpl::getJITSymbolFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/symbolref">SymbolRef</a> &amp; Sym)</td>
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

<p>Generate <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> from a libObject symbol.</p>

<p>Declaration at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 744 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#a6d8cec64deb620b732a8a6922c327cf7">llvm::JITSymbolFlags::fromObjectSymbol</a>.</p>


<p>Referenced by <a href="#a7516dd41b3867b963148426688fe9ff3">emitCommonSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#ae71e8902775f8de0490455dc8c929d2f">llvm::RuntimeDyldCOFFThumb::getJITSymbolFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a5be127713fc8105efd1e4261f09b1097">llvm::RuntimeDyldMachOARM::getJITSymbolFlags</a> and <a href="#afe85af578989c7f3e9627866e7fa4962">loadObjectImpl</a>.</p>

</div>
</div>

### getMaxStubSize() {#ae7343d4154aa28a8bc872b1de1e40df4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::RuntimeDyldImpl::getMaxStubSize ()</td>
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



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#af12404037d26556e018e61366f026aaa">computeSectionStubBufSize</a>, <a href="#a5e48116b879cb9413068e080549d3f47">getSectionContent</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a>.</p>

</div>
</div>

### getStubAlignment() {#a267138a4cf518ebb229b7c0d59629b66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Align llvm::RuntimeDyldImpl::getStubAlignment ()</td>
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



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#af12404037d26556e018e61366f026aaa">computeSectionStubBufSize</a>, <a href="#af089befa203447cdf71f665a1993a997">computeTotalAllocSize</a> and <a href="#a7dd171407e8c0e19195ea2039f3f83b6">emitSection</a>.</p>

</div>
</div>

### loadObjectImpl() {#afe85af578989c7f3e9627866e7fa4962}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; RuntimeDyldImpl::ObjSectionToIDMap &gt; llvm::RuntimeDyldImpl::loadObjectImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj)</td>
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



<p>Declaration at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="#a5bb6f8bb79248648fd25dc7a75661363">AbsoluteSymbolSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="#aab98755e5bcb6af82707f749aab3c474">Arch</a>, <a href="#af089befa203447cdf71f665a1993a997">computeTotalAllocSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a7516dd41b3867b963148426688fe9ff3">emitCommonSymbols</a>, <a href="#a35ea08a2c201659672a5fc147bb4c03b">finalizeLoad</a>, <a href="#aa4b6bd8b78d9901ada802b2363341628">findOrEmitSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#ade6a289b7efafc8625daf0575ad81c08">llvm::object::ObjectFile::getArch</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#acecdb20a61e1b407af83d42e1ad9a3f3">llvm::object::Binary::getFileName</a>, <a href="#afd8b5e95c65e3bb62ead0dd58732e382">getJITSymbolFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a603eb2d37a31ea2c14318bedeecb8e3c">llvm::getOffset</a>, <a href="#af95b57a597e7339755eeb2a4e0470943">GlobalSymbolTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a638ca5d7bf4e2a09998c8e7fe8563ad8">llvm::object::Binary::isLittleEndian</a>, <a href="#a63d27a7beb22a7596ed2f10bdb9a8dda">IsTargetLittleEndian</a>, <a href="/web-llvm/docs/api/classes/llvm/object/sectionref/#ab78cb663ac0805b3be2756a9148e1d76">llvm::object::SectionRef::isText</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a38acc586c344e0db0232becbb9a2923a">lock</a>, <a href="#a9bc5cceb63d0ccdf06f64b587f1cd80e">MemMgr</a>, <a href="#a1574f80d41478e7569c8546d35119440">NotifyStubEmitted</a>, <a href="#a7013eadb021bbc67df524aca8a3af8d0">ProcessAllSections</a>, <a href="#a053739959e9149e1dd57423e3140996b">processNewSymbol</a>, <a href="#a220108ed2bc5839a9f8284894a47c5a8">processRelocationRef</a>, <a href="#a688485f7fca0fadd7e492dc12218cd16">Resolver</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#af9eb4120f90b00d473f53ce9877388d0">llvm::object::ObjectFile::section_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a3e48ce01c39d5e5e36eced4e3d3f6f23">llvm::object::ObjectFile::section_end</a>, <a href="#afce88102ca208741b470edac5342c4b3">Sections</a>, <a href="#ac0a5a1db971902509d6e5f9dc62aca8c">setMipsABI</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431acc6eb3e8d6f0fb38a6f3eb9ddef198af">llvm::object::BasicSymbolRef::SF_Absolute</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a917d4e0252fa1d20b2086b2e99e78e57">llvm::object::BasicSymbolRef::SF_Common</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ad1131f10939b205635a0dc81ca3c45d7">llvm::object::BasicSymbolRef::SF_Undefined</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ac199a3dc25299a191397723e89fd303e">llvm::object::BasicSymbolRef::SF_Weak</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a8a501fedaaa3e562541580b8f1db3975">llvm::object::SymbolRef::ST_Data</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a771f3523463fc179b4e89f60841a23b8">llvm::object::SymbolRef::ST_File</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a2fcf5b0171fb8526218be425765b5da1">llvm::object::SymbolRef::ST_Function</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a076f193658db35c0f4d60f9e0a3e329f">llvm::object::SymbolRef::ST_Other</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a2d334a713a4916963744a0cc31ab9552">llvm::object::SymbolRef::ST_Unknown</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#a40c5717c994df60bcbe3d9299f6a5982">llvm::object::SymbolicFile::symbol_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#a7bc0f444aecc9b7aaef7facdb3d2bddb">llvm::object::SymbolicFile::symbol_end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aa22a9825f4937b28269552f5b8db4a69">llvm::object::ObjectFile::symbols</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#a9a395f20a00fadbc2facd11a18be8229">llvm::RuntimeDyldCOFF::loadObject</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a8eaeb3bf0be2e6f9ffce10bab1dcb5f2">llvm::RuntimeDyldELF::loadObject</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#a9756238ad37b76ccc9ff6920f0340a77">llvm::RuntimeDyldMachO::loadObject</a>.</p>

</div>
</div>

### modifyAddressBasedOnFlags() {#a20888517938004f7256fae2f0d6b89c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::RuntimeDyldImpl::modifyAddressBasedOnFlags (uint64_t Addr, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> Flags)</td>
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

<p>Modify the given target address based on the given symbol flags.</p>


<p>This can be used by subclasses to tweak addresses based on symbol flags, For example: the MachO/ARM target uses it to set the low bit if the target is a thumb symbol.</p>


<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#a37c72a2afbbe1c6eee27d8fa2a2e2834">applyExternalSymbolRelocations</a> and <a href="#a47b4c96424aa28dc46f2d756ba5e823e">getSymbol</a>.</p>

</div>
</div>

### processNewSymbol() {#a053739959e9149e1dd57423e3140996b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::RuntimeDyldImpl::processNewSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/symbolref">SymbolRef</a> &amp; ObjSymbol, <a href="/web-llvm/docs/api/classes/llvm/symboltableentry">SymbolTableEntry</a> &amp; Entry)</td>
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



<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#afe85af578989c7f3e9627866e7fa4962">loadObjectImpl</a>.</p>

</div>
</div>

### processRelocationRef() {#a220108ed2bc5839a9f8284894a47c5a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; relocation_iterator &gt; llvm::RuntimeDyldImpl::processRelocationRef (unsigned SectionID, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a> RelI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj, <a href="#a22b1a24bb422a0f0896dd84dff7933e2">ObjSectionToIDMap</a> &amp; ObjSectionToID, <a href="#a45d3097b94f4f98303ae36e6c6b7eee6">StubMap</a> &amp; Stubs)</td>
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

<p>Parses one or more object file relocations (some object files use relocation pairs) and stores it to Relocations or SymbolRelocations (this depends on the object file type).</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Iterator to the next relocation that needs to be parsed.</p></dd>
</dl>


<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#afe85af578989c7f3e9627866e7fa4962">loadObjectImpl</a>.</p>

</div>
</div>

### readBytesUnaligned() {#ad8a8e68671c17b1a8dde17365f897406}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::RuntimeDyldImpl::readBytesUnaligned (uint8_t * Src, unsigned Size)</td>
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

<p>Endian-aware read Read the least significant Size bytes from Src.</p>

<p>Declaration at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 713 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="#a63d27a7beb22a7596ed2f10bdb9a8dda">IsTargetLittleEndian</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a4c19829e43ffe8064443b93c1946f9a2">llvm::RuntimeDyldMachOARM::decodeAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#a4ff8b7dc8dd3a4baddc147c6afd14c5e">llvm::RuntimeDyldMachO::memcpyAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffi386/#a47afe575c279c175037d664bde7e53a3">llvm::RuntimeDyldCOFFI386::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#a200d4c53b00f55a8d0911279bf576c18">llvm::RuntimeDyldCOFFThumb::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#afcf3722d9ca669767870af1a84877924">llvm::RuntimeDyldCOFFX86_64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#acb7257d8eec274d18e7916a0d552a2d7">llvm::RuntimeDyldMachO::processScatteredVANILLA</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a42b1bc914cf22878c36dda7a8a31447e">llvm::RuntimeDyldMachOARM::resolveRelocation</a>.</p>

</div>
</div>

### relocationNeedsDLLImportStub() {#ad9420dc366cfedbf952c959190f126ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::RuntimeDyldImpl::relocationNeedsDLLImportStub (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/relocationref">RelocationRef</a> &amp; R)</td>
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



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#af12404037d26556e018e61366f026aaa">computeSectionStubBufSize</a>.</p>

</div>
</div>

### relocationNeedsGot() {#a042ec898366e685c33b16c7967179b6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::RuntimeDyldImpl::relocationNeedsGot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/relocationref">RelocationRef</a> &amp; R)</td>
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



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#ab3ab5fec568fdd2334001b26dd6d7f35">computeGOTSize</a>.</p>

</div>
</div>

### relocationNeedsStub() {#aa8b04315da851e48c69fbf86a1e87f14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::RuntimeDyldImpl::relocationNeedsStub (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/relocationref">RelocationRef</a> &amp; R)</td>
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



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#af12404037d26556e018e61366f026aaa">computeSectionStubBufSize</a>.</p>

</div>
</div>

### resolveExternalSymbols() {#aff5abd27370b46872f4470992413c91a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::RuntimeDyldImpl::resolveExternalSymbols ()</td>
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

<p>Resolve relocations to external symbols.</p>

<p>Declaration at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 1175 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="#a37c72a2afbbe1c6eee27d8fa2a2e2834">applyExternalSymbolRelocations</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0c12b4806588ffc8548c4f2d53236505">ExternalSymbolRelocations</a>, <a href="#af95b57a597e7339755eeb2a4e0470943">GlobalSymbolTable</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#afea367cbdd62e85c20d3ebe044253ce7">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::insert</a>, <a href="#a688485f7fca0fadd7e492dc12218cd16">Resolver</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#af32873ce4ce9becfcc874f9d34f0d793">resolveRelocations</a>.</p>

</div>
</div>

### resolveRelocation() {#a263a3fecf6a1b50d26130f1ed176dce0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::RuntimeDyldImpl::resolveRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/relocationentry">RelocationEntry</a> &amp; RE, uint64_t Value)</td>
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

<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#a40f413b46e7b2e713ec1997fe71b2aa1">resolveRelocationList</a>.</p>

</div>
</div>

### resolveRelocationList() {#a40f413b46e7b2e713ec1997fe71b2aa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldImpl::resolveRelocationList (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a43eb198952bc9e33faa657d4cd13a5eb">RelocationList</a> &amp; Relocs, uint64_t Value)</td>
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

<p>Resolves relocations from Relocs list with address from <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>

<p>Declaration at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 1113 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="#a5bb6f8bb79248648fd25dc7a75661363">AbsoluteSymbolSection</a>, <a href="#a263a3fecf6a1b50d26130f1ed176dce0">resolveRelocation</a> and <a href="#afce88102ca208741b470edac5342c4b3">Sections</a>.</p>


<p>Referenced by <a href="#a37c72a2afbbe1c6eee27d8fa2a2e2834">applyExternalSymbolRelocations</a> and <a href="#a9c0f4b1a5dc30ecf51894a22a51ed441">resolveLocalRelocations</a>.</p>

</div>
</div>

### setMipsABI() {#ac0a5a1db971902509d6e5f9dc62aca8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::RuntimeDyldImpl::setMipsABI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj)</td>
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



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>References <a href="#a940c75979815d8de459e2791701e4853">IsMipsN32ABI</a>, <a href="#a3cd00aae21297a0a228ef733b6b47ba4">IsMipsN64ABI</a> and <a href="#aa431374d08ab68077b4ba96efe411c72">IsMipsO32ABI</a>.</p>


<p>Referenced by <a href="#afe85af578989c7f3e9627866e7fa4962">loadObjectImpl</a>.</p>

</div>
</div>

### sizeAfterAddingDLLImportStub() {#a897ccc6208f6a743973bbadd039c67ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::RuntimeDyldImpl::sizeAfterAddingDLLImportStub (unsigned Size)</td>
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



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#af12404037d26556e018e61366f026aaa">computeSectionStubBufSize</a>.</p>

</div>
</div>

### writeBytesUnaligned() {#ac7b095afaba91cf9bf59313c8e94d2d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldImpl::writeBytesUnaligned (uint64_t Value, uint8_t * Dst, unsigned Size)</td>
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

<p>Endian-aware write.</p>


<p>Write the least significant Size bytes from <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to Dst.</p>


<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 727 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="#a63d27a7beb22a7596ed2f10bdb9a8dda">IsTargetLittleEndian</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#ad76b1f4f9f930bb5d8942b8bb05875cc">createStubFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffi386/#af5f76d4e975e1864419036651a6b9295">llvm::RuntimeDyldCOFFI386::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#a6339960d2e5a1860dd0ce831fc20c006">llvm::RuntimeDyldCOFFThumb::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#a2743e6f5ddf54d94da5d05aebfdb3c9d">llvm::RuntimeDyldCOFFX86_64::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#afab03ddb5f92e76f5c7bc8960baf72fa">llvm::RuntimeDyldMachOAArch64::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a42b1bc914cf22878c36dda7a8a31447e">llvm::RuntimeDyldMachOARM::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoi386/#ae8f416dd6dfbdda68a71ef2684092933">llvm::RuntimeDyldMachOI386::resolveRelocation</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#ab9f0c0ad7d8a9a72b2b7b5601eb7cf77">llvm::RuntimeDyldMachOX86_64::resolveRelocation</a>.</p>

</div>
</div>

### writeInt16BE() {#a5152bd91da7db6b185d42e839b7a3e82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldImpl::writeInt16BE (uint8_t * Addr, uint16_t Value)</td>
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



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbad861877da56b8b4ceb35c8cbfdf65bb4">llvm::big</a>, <a href="#a63d27a7beb22a7596ed2f10bdb9a8dda">IsTargetLittleEndian</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>


<p>Referenced by <a href="#ad76b1f4f9f930bb5d8942b8bb05875cc">createStubFunction</a>.</p>

</div>
</div>

### writeInt32BE() {#a2e2a818eaa1b3883192a5ae226b38a9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldImpl::writeInt32BE (uint8_t * Addr, uint32_t Value)</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbad861877da56b8b4ceb35c8cbfdf65bb4">llvm::big</a>, <a href="#a63d27a7beb22a7596ed2f10bdb9a8dda">IsTargetLittleEndian</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>


<p>Referenced by <a href="#ad76b1f4f9f930bb5d8942b8bb05875cc">createStubFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a>.</p>

</div>
</div>

### writeInt64BE() {#a423b6eebb04795995f7813b4ed73c00c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldImpl::writeInt64BE (uint8_t * Addr, uint64_t Value)</td>
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



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbad861877da56b8b4ceb35c8cbfdf65bb4">llvm::big</a>, <a href="#a63d27a7beb22a7596ed2f10bdb9a8dda">IsTargetLittleEndian</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Arch {#aab98755e5bcb6af82707f749aab3c474}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::ArchType llvm::RuntimeDyldImpl::Arch</td>
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



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#aaee932c8114ffff69782641103849794">llvm::RuntimeDyldCOFF::create</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a2a43382614f69bdae93a85b8dd43d597">llvm::RuntimeDyldELF::create</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#a25223ec2c4ea3ce3825d9abcc9e6dad1">llvm::RuntimeDyldMachO::create</a>, <a href="#ad76b1f4f9f930bb5d8942b8bb05875cc">createStubFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a1881f42b5c49ba8ed8d1056ee2ff90d8">llvm::RuntimeDyldELF::getGOTEntrySize</a>, <a href="#afe85af578989c7f3e9627866e7fa4962">loadObjectImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a19bde166e1cf015f0a9e5a2786274299">llvm::RuntimeDyldELF::~RuntimeDyldELF</a>.</p>

</div>
</div>

### ErrorStr {#a43f4ef223d6929940f48a82219fc075f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::RuntimeDyldImpl::ErrorStr</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#a4576876ecc01f47393fd5519d78e0cc7">getErrorString</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#a9a395f20a00fadbc2facd11a18be8229">llvm::RuntimeDyldCOFF::loadObject</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a8eaeb3bf0be2e6f9ffce10bab1dcb5f2">llvm::RuntimeDyldELF::loadObject</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#a9756238ad37b76ccc9ff6920f0340a77">llvm::RuntimeDyldMachO::loadObject</a> and <a href="#af32873ce4ce9becfcc874f9d34f0d793">resolveRelocations</a>.</p>

</div>
</div>

### ExternalSymbolRelocations {#a0c12b4806588ffc8548c4f2d53236505}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;RelocationList&gt; llvm::RuntimeDyldImpl::ExternalSymbolRelocations</td>
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



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#a5db8c0beafbba922f1600e24fe6898bc">addRelocationForSymbol</a>, <a href="#a37c72a2afbbe1c6eee27d8fa2a2e2834">applyExternalSymbolRelocations</a> and <a href="#aff5abd27370b46872f4470992413c91a">resolveExternalSymbols</a>.</p>

</div>
</div>

### GlobalSymbolTable {#af95b57a597e7339755eeb2a4e0470943}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTDyldSymbolTable llvm::RuntimeDyldImpl::GlobalSymbolTable</td>
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



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#a5db8c0beafbba922f1600e24fe6898bc">addRelocationForSymbol</a>, <a href="#a37c72a2afbbe1c6eee27d8fa2a2e2834">applyExternalSymbolRelocations</a>, <a href="#a7516dd41b3867b963148426688fe9ff3">emitCommonSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ac01d9cc5d2d4a3b6662c7096e54bf8ad">llvm::RuntimeDyldMachO::getRelocationValueRef</a>, <a href="#a47b4c96424aa28dc46f2d756ba5e823e">getSymbol</a>, <a href="#ac09946fac21b277a58791857159dda69">getSymbolLocalAddress</a>, <a href="#ab32409ec13e7d1450227083a972f303e">getSymbolSectionID</a>, <a href="#a4965dcbd02c025ceb9683329bf70ba39">getSymbolTable</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a66ea8b31d8dedc659636270db9b37790">llvm::RuntimeDyldMachOARM::isAddrTargetThumb</a>, <a href="#afe85af578989c7f3e9627866e7fa4962">loadObjectImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#ad0cc2b7a34912033f88c7169756683cb">llvm::RuntimeDyldMachOARM::processRelocationRef</a> and <a href="#aff5abd27370b46872f4470992413c91a">resolveExternalSymbols</a>.</p>

</div>
</div>

### HasError {#accd3f8de90a127cd1e8538b9df936681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RuntimeDyldImpl::HasError</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#ae00b36887501beb4a1c0d5b1272baef8">clearError</a>, <a href="#a754e8c8b2570039fabe325bba0053ea1">hasError</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#a9a395f20a00fadbc2facd11a18be8229">llvm::RuntimeDyldCOFF::loadObject</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a8eaeb3bf0be2e6f9ffce10bab1dcb5f2">llvm::RuntimeDyldELF::loadObject</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#a9756238ad37b76ccc9ff6920f0340a77">llvm::RuntimeDyldMachO::loadObject</a>, <a href="#af32873ce4ce9becfcc874f9d34f0d793">resolveRelocations</a> and <a href="#a369fb04a71a831101a7bdfa873cb33d0">RuntimeDyldImpl</a>.</p>

</div>
</div>

### IsMipsN32ABI {#a940c75979815d8de459e2791701e4853}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RuntimeDyldImpl::IsMipsN32ABI</td>
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



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#ad76b1f4f9f930bb5d8942b8bb05875cc">createStubFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a34d452366da541e62d1f37b1f284800d">llvm::RuntimeDyldELF::finalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a1881f42b5c49ba8ed8d1056ee2ff90d8">llvm::RuntimeDyldELF::getGOTEntrySize</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelfmips/#a68be6b3ae238497d82af98616431b6a1">llvm::RuntimeDyldELFMips::resolveRelocation</a> and <a href="#ac0a5a1db971902509d6e5f9dc62aca8c">setMipsABI</a>.</p>

</div>
</div>

### IsMipsN64ABI {#a3cd00aae21297a0a228ef733b6b47ba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RuntimeDyldImpl::IsMipsN64ABI</td>
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



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#ad76b1f4f9f930bb5d8942b8bb05875cc">createStubFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a34d452366da541e62d1f37b1f284800d">llvm::RuntimeDyldELF::finalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a1881f42b5c49ba8ed8d1056ee2ff90d8">llvm::RuntimeDyldELF::getGOTEntrySize</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelfmips/#a68be6b3ae238497d82af98616431b6a1">llvm::RuntimeDyldELFMips::resolveRelocation</a> and <a href="#ac0a5a1db971902509d6e5f9dc62aca8c">setMipsABI</a>.</p>

</div>
</div>

### IsMipsO32ABI {#aa431374d08ab68077b4ba96efe411c72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RuntimeDyldImpl::IsMipsO32ABI</td>
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



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#ad76b1f4f9f930bb5d8942b8bb05875cc">createStubFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a34d452366da541e62d1f37b1f284800d">llvm::RuntimeDyldELF::finalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a1881f42b5c49ba8ed8d1056ee2ff90d8">llvm::RuntimeDyldELF::getGOTEntrySize</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelfmips/#a68be6b3ae238497d82af98616431b6a1">llvm::RuntimeDyldELFMips::resolveRelocation</a> and <a href="#ac0a5a1db971902509d6e5f9dc62aca8c">setMipsABI</a>.</p>

</div>
</div>

### IsTargetLittleEndian {#a63d27a7beb22a7596ed2f10bdb9a8dda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RuntimeDyldImpl::IsTargetLittleEndian</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#afe85af578989c7f3e9627866e7fa4962">loadObjectImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a>, <a href="#ad8a8e68671c17b1a8dde17365f897406">readBytesUnaligned</a>, <a href="#ac7b095afaba91cf9bf59313c8e94d2d9">writeBytesUnaligned</a>, <a href="#a5152bd91da7db6b185d42e839b7a3e82">writeInt16BE</a>, <a href="#a2e2a818eaa1b3883192a5ae226b38a9e">writeInt32BE</a> and <a href="#a423b6eebb04795995f7813b4ed73c00c">writeInt64BE</a>.</p>

</div>
</div>

### lock {#a38acc586c344e0db0232becbb9a2923a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sys::Mutex llvm::RuntimeDyldImpl::lock</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#afe85af578989c7f3e9627866e7fa4962">loadObjectImpl</a>, <a href="#a04d08776ab3e7bfefea4fed7b22c6613">mapSectionAddress</a> and <a href="#af32873ce4ce9becfcc874f9d34f0d793">resolveRelocations</a>.</p>

</div>
</div>

### MemMgr {#a9bc5cceb63d0ccdf06f64b587f1cd80e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeDyld::MemoryManager&amp; llvm::RuntimeDyldImpl::MemMgr</td>
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



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#af12404037d26556e018e61366f026aaa">computeSectionStubBufSize</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#aaee932c8114ffff69782641103849794">llvm::RuntimeDyldCOFF::create</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a2a43382614f69bdae93a85b8dd43d597">llvm::RuntimeDyldELF::create</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#a25223ec2c4ea3ce3825d9abcc9e6dad1">llvm::RuntimeDyldMachO::create</a>, <a href="#a4ea8279ce903e5f1dd9bfc82f6bb57af">deregisterEHFrames</a>, <a href="#a7516dd41b3867b963148426688fe9ff3">emitCommonSymbols</a>, <a href="#a7dd171407e8c0e19195ea2039f3f83b6">emitSection</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a34d452366da541e62d1f37b1f284800d">llvm::RuntimeDyldELF::finalizeLoad</a>, <a href="#afe85af578989c7f3e9627866e7fa4962">loadObjectImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#a203c9800704a1e1b1119cfaa3945939a">llvm::RuntimeDyldCOFFX86_64::registerEHFrames</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a02aac305b3611765b79dd39adb8dea9c">llvm::RuntimeDyldELF::registerEHFrames</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachocrtpbase/#a320dd78d770da97700997cca111f7946">llvm::RuntimeDyldMachOCRTPBase&lt; Impl &gt;::registerEHFrames</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#a525c1edda0934652055bd4ca610dcf20">llvm::RuntimeDyldCOFF::RuntimeDyldCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#acff5ec4cbde9c943ffd383afdf1e0bb1">llvm::RuntimeDyldELF::RuntimeDyldELF</a>, <a href="#a369fb04a71a831101a7bdfa873cb33d0">RuntimeDyldImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#a034c5e05b63e15a357bc5dcff598e1a5">llvm::RuntimeDyldMachO::RuntimeDyldMachO</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachocrtpbase/#a4fd1220b5b8aa3aa6d20e7b79ec0f897">llvm::RuntimeDyldMachOCRTPBase&lt; RuntimeDyldMachOARM &gt;::RuntimeDyldMachOCRTPBase</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a19bde166e1cf015f0a9e5a2786274299">llvm::RuntimeDyldELF::~RuntimeDyldELF</a>.</p>

</div>
</div>

### NotifyStubEmitted {#a1574f80d41478e7569c8546d35119440}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NotifyStubEmittedFunction llvm::RuntimeDyldImpl::NotifyStubEmitted</td>
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



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#afe85af578989c7f3e9627866e7fa4962">loadObjectImpl</a> and <a href="#aee8e9941d8788cdadb75e127e6690d94">setNotifyStubEmitted</a>.</p>

</div>
</div>

### ProcessAllSections {#a7013eadb021bbc67df524aca8a3af8d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RuntimeDyldImpl::ProcessAllSections</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#af089befa203447cdf71f665a1993a997">computeTotalAllocSize</a>, <a href="#a7dd171407e8c0e19195ea2039f3f83b6">emitSection</a>, <a href="#afe85af578989c7f3e9627866e7fa4962">loadObjectImpl</a>, <a href="#a369fb04a71a831101a7bdfa873cb33d0">RuntimeDyldImpl</a> and <a href="#ab33fe725a4ead8129cb4874fa18f2712">setProcessAllSections</a>.</p>

</div>
</div>

### Relocations {#a8c55775113ee7e3171e3f7ece1462e1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;unsigned, RelocationList&gt; llvm::RuntimeDyldImpl::Relocations</td>
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



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#a9ee81c156267d67bed9008ed1a954214">addRelocationForSection</a>, <a href="#a5db8c0beafbba922f1600e24fe6898bc">addRelocationForSymbol</a> and <a href="#a9c0f4b1a5dc30ecf51894a22a51ed441">resolveLocalRelocations</a>.</p>

</div>
</div>

### Resolver {#a688485f7fca0fadd7e492dc12218cd16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITSymbolResolver&amp; llvm::RuntimeDyldImpl::Resolver</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#a37c72a2afbbe1c6eee27d8fa2a2e2834">applyExternalSymbolRelocations</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#aaee932c8114ffff69782641103849794">llvm::RuntimeDyldCOFF::create</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a2a43382614f69bdae93a85b8dd43d597">llvm::RuntimeDyldELF::create</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#a25223ec2c4ea3ce3825d9abcc9e6dad1">llvm::RuntimeDyldMachO::create</a>, <a href="#afe85af578989c7f3e9627866e7fa4962">loadObjectImpl</a>, <a href="#aff5abd27370b46872f4470992413c91a">resolveExternalSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#a525c1edda0934652055bd4ca610dcf20">llvm::RuntimeDyldCOFF::RuntimeDyldCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#acff5ec4cbde9c943ffd383afdf1e0bb1">llvm::RuntimeDyldELF::RuntimeDyldELF</a>, <a href="#a369fb04a71a831101a7bdfa873cb33d0">RuntimeDyldImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#a034c5e05b63e15a357bc5dcff598e1a5">llvm::RuntimeDyldMachO::RuntimeDyldMachO</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a19bde166e1cf015f0a9e5a2786274299">llvm::RuntimeDyldELF::~RuntimeDyldELF</a>.</p>

</div>
</div>

### Sections {#afce88102ca208741b470edac5342c4b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionList llvm::RuntimeDyldImpl::Sections</td>
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



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#a57a3ea47fdc3f7e2de2a3939ea4e5a49">llvm::RuntimeDyldMachOAArch64::decodeAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a4c19829e43ffe8064443b93c1946f9a2">llvm::RuntimeDyldMachOARM::decodeAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#af2314475cd69d029c487927d58778a82">llvm::RuntimeDyldMachO::dumpRelocationToResolve</a>, <a href="#a7516dd41b3867b963148426688fe9ff3">emitCommonSymbols</a>, <a href="#a7dd171407e8c0e19195ea2039f3f83b6">emitSection</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a34d452366da541e62d1f37b1f284800d">llvm::RuntimeDyldELF::finalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a7c59308f5da9f18a578d5dfaed1285a1">llvm::RuntimeDyldCOFFAArch64::generateRelocationStub</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#ae5595d78c0d45afeec52fccb70b1b209">llvm::RuntimeDyldCOFFX86_64::generateRelocationStub</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#af0b0733da2d8693287bd3bb04ee6ab80">llvm::RuntimeDyldCOFF::getDLLImportOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#aa8bef91e492828fa00f12f096630a145">llvm::RuntimeDyldMachO::getSection</a>, <a href="#aee6ff05f9ffdbe69760734e002307b18">getSectionAddress</a>, <a href="#a5e48116b879cb9413068e080549d3f47">getSectionContent</a>, <a href="#adada8cf26f3cc4f3560e2af8f7b458bc">getSectionLoadAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a66ea8b31d8dedc659636270db9b37790">llvm::RuntimeDyldMachOARM::isAddrTargetThumb</a>, <a href="#afe85af578989c7f3e9627866e7fa4962">loadObjectImpl</a>, <a href="#a04d08776ab3e7bfefea4fed7b22c6613">mapSectionAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#a4ff8b7dc8dd3a4baddc147c6afd14c5e">llvm::RuntimeDyldMachO::memcpyAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ab606ca40d5870295837712aa2056f90e">llvm::RuntimeDyldMachO::populateIndirectSymbolPointersSection</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a9114640d8c0477c8c9c502e8acd7cbf7">llvm::RuntimeDyldCOFFAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffi386/#a47afe575c279c175037d664bde7e53a3">llvm::RuntimeDyldCOFFI386::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#a200d4c53b00f55a8d0911279bf576c18">llvm::RuntimeDyldCOFFThumb::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#afcf3722d9ca669767870af1a84877924">llvm::RuntimeDyldCOFFX86_64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#acb7257d8eec274d18e7916a0d552a2d7">llvm::RuntimeDyldMachO::processScatteredVANILLA</a>, <a href="#a13ed1aa385513404b0d2bcad53502041">reassignSectionAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#a203c9800704a1e1b1119cfaa3945939a">llvm::RuntimeDyldCOFFX86_64::registerEHFrames</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a02aac305b3611765b79dd39adb8dea9c">llvm::RuntimeDyldELF::registerEHFrames</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachocrtpbase/#a320dd78d770da97700997cca111f7946">llvm::RuntimeDyldMachOCRTPBase&lt; Impl &gt;::registerEHFrames</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a35e8cc985018e504a57093b9e0768d00">llvm::RuntimeDyldCOFFAArch64::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffi386/#af5f76d4e975e1864419036651a6b9295">llvm::RuntimeDyldCOFFI386::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#a6339960d2e5a1860dd0ce831fc20c006">llvm::RuntimeDyldCOFFThumb::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#a2743e6f5ddf54d94da5d05aebfdb3c9d">llvm::RuntimeDyldCOFFX86_64::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#a66fd1d01cea1089f326652a523d4049a">llvm::RuntimeDyldELF::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelfmips/#a68be6b3ae238497d82af98616431b6a1">llvm::RuntimeDyldELFMips::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoaarch64/#afab03ddb5f92e76f5c7bc8960baf72fa">llvm::RuntimeDyldMachOAArch64::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a42b1bc914cf22878c36dda7a8a31447e">llvm::RuntimeDyldMachOARM::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoi386/#ae8f416dd6dfbdda68a71ef2684092933">llvm::RuntimeDyldMachOI386::resolveRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#ab9f0c0ad7d8a9a72b2b7b5601eb7cf77">llvm::RuntimeDyldMachOX86_64::resolveRelocation</a>, <a href="#a40f413b46e7b2e713ec1997fe71b2aa1">resolveRelocationList</a> and <a href="#af32873ce4ce9becfcc874f9d34f0d793">resolveRelocations</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### finalizeAsync() {#a6dfeef2ecf7ff9f91673432765f3b695}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyldImpl::finalizeAsync (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl">RuntimeDyldImpl</a> &gt; This, <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/object/owningbinary">object::OwningBinary</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &gt;, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/loadedobjectinfo">RuntimeDyld::LoadedObjectInfo</a> &gt;, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; OnEmitted, <a href="/web-llvm/docs/api/classes/llvm/object/owningbinary">object::OwningBinary</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &gt; O, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/loadedobjectinfo">RuntimeDyld::LoadedObjectInfo</a> &gt; Info)</td>
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



<p>Declaration at line 565 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>, definition at line 1231 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a497e3b0265fea4f3a0d137a8884c71ff">llvm::jitLinkForORC</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Attributes

### AbsoluteSymbolSection {#a5bb6f8bb79248648fd25dc7a75661363}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::RuntimeDyldImpl::AbsoluteSymbolSection = ~0U</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="#aee6ff05f9ffdbe69760734e002307b18">getSectionAddress</a>, <a href="#a5e48116b879cb9413068e080549d3f47">getSectionContent</a>, <a href="#adada8cf26f3cc4f3560e2af8f7b458bc">getSectionLoadAddress</a>, <a href="#a47b4c96424aa28dc46f2d756ba5e823e">getSymbol</a>, <a href="#ac09946fac21b277a58791857159dda69">getSymbolLocalAddress</a>, <a href="#afe85af578989c7f3e9627866e7fa4962">loadObjectImpl</a> and <a href="#a40f413b46e7b2e713ec1997fe71b2aa1">resolveRelocationList</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
