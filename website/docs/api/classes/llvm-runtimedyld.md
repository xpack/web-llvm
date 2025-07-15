---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/runtimedyld
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RuntimeDyld` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::RuntimeDyld { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">llvm/ExecutionEngine/RuntimeDyld.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ca2c024ef2bb555f0d9c3aae8b40583">NotifyStubEmittedFunction</a> = std::function&lt; void( <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="/web-llvm/docs/api/structs/llvm/sectionname">SectionName</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SymbolName, unsigned SectionID, uint32_t StubOffset)&gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae59a33f02ce3fc77a53efa0677914bde">jitLinkForORC</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac342ba1ff1f7d8a4d6a15a890ffcad8b">RuntimeDyld</a> (MemoryManager &amp;MemMgr, JITSymbolResolver &amp;Resolver)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> instance. <a href="#ac342ba1ff1f7d8a4d6a15a890ffcad8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0367fbc495a82dbb6c19217c8be626a6">RuntimeDyld</a> (const RuntimeDyld &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2313a97b3f26e7784ce066e1de44924">~RuntimeDyld</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb6656196719be5ba5376dabf81a9d1f">operator=</a> (const RuntimeDyld &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30ce7d72b88e0bc27b8c9e416e9a096c">reassignSectionAddress</a> (unsigned SectionID, uint64_t Addr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/loadedobjectinfo">LoadedObjectInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2ab8021c32ef2200c8b01e2105f1821">loadObject</a> (const object::ObjectFile &amp;O)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the referenced object file to the list of objects to be loaded and relocated. <a href="#ad2ab8021c32ef2200c8b01e2105f1821">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a386fd7c34168ea0124ab65e01987f84c">getSymbolLocalAddress</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the address of our local copy of the symbol. <a href="#a386fd7c34168ea0124ab65e01987f84c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addb3f8e92465a1c1176a59939ce3bc6d">getSymbolSectionID</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the section <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the section containing the given symbol. <a href="#addb3f8e92465a1c1176a59939ce3bc6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitevaluatedsymbol">JITEvaluatedSymbol</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3411f5eff279e382200680d3d415a96">getSymbol</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the target address and flags for the named symbol. <a href="#ab3411f5eff279e382200680d3d415a96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/jitevaluatedsymbol">JITEvaluatedSymbol</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38e5c630fbb8b8fe89bfa069e408c0dd">getSymbolTable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a copy of the symbol table. <a href="#a38e5c630fbb8b8fe89bfa069e408c0dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b3756c713e9a0e034b96a96ebd8ebc2">resolveRelocations</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resolve the relocations for all symbols we currently know about. <a href="#a4b3756c713e9a0e034b96a96ebd8ebc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b3c521130df594d63177bda62de400d">mapSectionAddress</a> (const void *LocalAddress, uint64_t TargetAddress)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a section to its target address space value. <a href="#a0b3c521130df594d63177bda62de400d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8f5e35aabe96a9401f209c376dec977">getSectionContent</a> (unsigned SectionID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the section's working memory. <a href="#aa8f5e35aabe96a9401f209c376dec977">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a370cc407634530729130aba543fa1707">getSectionLoadAddress</a> (unsigned SectionID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the section was loaded, return the section's load address, otherwise return std::nullopt. <a href="#a370cc407634530729130aba543fa1707">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78efb467e88df60120327e89b66f6b87">setNotifyStubEmitted</a> (NotifyStubEmittedFunction NotifyStubEmitted)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the NotifyStubEmitted callback. <a href="#a78efb467e88df60120327e89b66f6b87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90259a498cbb50bc825202e2a1ef6d3f">registerEHFrames</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> any EH frame sections that have been loaded but not previously registered with the memory manager. <a href="#a90259a498cbb50bc825202e2a1ef6d3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ff6de79072ece9676fbf6a9f4adcf8a">deregisterEHFrames</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9ca4615d0ed50de50b989f9cb21dfc3">hasError</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add134b6e2d6db80ec96cec44eef17552">getErrorString</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19cd93eb917e2a8cc5c900a5c0c015a4">setProcessAllSections</a> (bool ProcessAllSections)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>By default, only sections that are "required for execution" are passed to the <a href="/web-llvm/docs/api/classes/llvm/rtdyldmemorymanager">RTDyldMemoryManager</a>, and other sections are discarded. <a href="#a19cd93eb917e2a8cc5c900a5c0c015a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71b4a375f2964ea13d4064b81dba59ef">finalizeWithMemoryManagerLocking</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform all actions needed to make the code owned by this <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> instance executable: <a href="#a71b4a375f2964ea13d4064b81dba59ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl">RuntimeDyldImpl</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad038d9250b8b0b6b64dc6b6feedcc40">Dyld</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager">MemoryManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefd32b9fb140fa9dd099f6393a54b761">MemMgr</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af053c407b8042ae61886dcc403328480">Resolver</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd90a1ee49b7276a3382e6f0caf320eb">ProcessAllSections</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7ca2c024ef2bb555f0d9c3aae8b40583">NotifyStubEmittedFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaaf202caa0796f7054d426654079cea">NotifyStubEmitted</a></td>
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


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### NotifyStubEmittedFunction {#a7ca2c024ef2bb555f0d9c3aae8b40583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RuntimeDyld::NotifyStubEmittedFunction =  std::function&lt;void(
      StringRef FileName, StringRef SectionName, StringRef SymbolName,
      unsigned SectionID, uint32_t StubOffset)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### jitLinkForORC {#ae59a33f02ce3fc77a53efa0677914bde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend void <a href="/web-llvm/docs/api/classes/llvm/object/owningbinary">object::OwningBinary</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &gt; O, <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager">RuntimeDyld::MemoryManager</a> &amp; MemMgr, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolresolver">JITSymbolResolver</a> &amp; Resolver, bool ProcessAllSections, <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp;Obj, <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/loadedobjectinfo">LoadedObjectInfo</a> &amp;, std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/jitevaluatedsymbol">JITEvaluatedSymbol</a> &gt;)&gt; OnLoaded, <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/object/owningbinary">object::OwningBinary</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &gt; O, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/loadedobjectinfo">LoadedObjectInfo</a> &gt;, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; OnEmitted</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RuntimeDyld() {#ac342ba1ff1f7d8a4d6a15a890ffcad8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RuntimeDyld::RuntimeDyld (<a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager">MemoryManager</a> &amp; MemMgr, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolresolver">JITSymbolResolver</a> &amp; Resolver)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> instance.</p>

<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>, definition at line 1309 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>Referenced by <a href="#acb6656196719be5ba5376dabf81a9d1f">operator=</a> and <a href="#a0367fbc495a82dbb6c19217c8be626a6">RuntimeDyld</a>.</p>

</div>
</div>

### RuntimeDyld() {#a0367fbc495a82dbb6c19217c8be626a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RuntimeDyld::RuntimeDyld (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> &amp;)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>


<p>Reference <a href="#ac342ba1ff1f7d8a4d6a15a890ffcad8b">RuntimeDyld</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RuntimeDyld() {#aa2313a97b3f26e7784ce066e1de44924}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RuntimeDyld::~RuntimeDyld ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#acb6656196719be5ba5376dabf81a9d1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeDyld &amp; llvm::RuntimeDyld::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> &amp;)</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>


<p>Reference <a href="#ac342ba1ff1f7d8a4d6a15a890ffcad8b">RuntimeDyld</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### deregisterEHFrames() {#a7ff6de79072ece9676fbf6a9f4adcf8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyld::deregisterEHFrames ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>, definition at line 1452 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>

</div>
</div>

### finalizeWithMemoryManagerLocking() {#a71b4a375f2964ea13d4064b81dba59ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyld::finalizeWithMemoryManagerLocking ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform all actions needed to make the code owned by this <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> instance executable:</p>


<p>1) Apply relocations. 2) <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> EH frames. 3) Update memory permissions*.</p>


<ul class="doxyList ">
<li>Finalization is potentially recursive**, and the 3rd step will only be applied by the outermost call to finalize. This allows different <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> instances to share a memory manager without the innermost finalization locking the memory and causing relocation fixup errors in outer instances.</li>
</ul>

<p>** Recursive finalization occurs when one <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> instances needs the address of a symbol owned by some other instance in order to apply relocations.</p>


<p>Declaration at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>, definition at line 1426 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="#a90259a498cbb50bc825202e2a1ef6d3f">registerEHFrames</a> and <a href="#a4b3756c713e9a0e034b96a96ebd8ebc2">resolveRelocations</a>.</p>

</div>
</div>

### getErrorString() {#add134b6e2d6db80ec96cec44eef17552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::RuntimeDyld::getErrorString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>, definition at line 1424 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a497e3b0265fea4f3a0d137a8884c71ff">llvm::jitLinkForORC</a>.</p>

</div>
</div>

### getSectionContent() {#aa8f5e35aabe96a9401f209c376dec977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::RuntimeDyld::getSectionContent (unsigned SectionID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the section's working memory.</p>

<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>, definition at line 1437 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getSectionLoadAddress() {#a370cc407634530729130aba543fa1707}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::RuntimeDyld::getSectionLoadAddress (unsigned SectionID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the section was loaded, return the section's load address, otherwise return std::nullopt.</p>

<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>, definition at line 1442 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getSymbol() {#ab3411f5eff279e382200680d3d415a96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITEvaluatedSymbol llvm::RuntimeDyld::getSymbol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the target address and flags for the named symbol.</p>


<p>This address is the one used for relocation.</p>


<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>, definition at line 1399 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>

</div>
</div>

### getSymbolLocalAddress() {#a386fd7c34168ea0124ab65e01987f84c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::RuntimeDyld::getSymbolLocalAddress (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the address of our local copy of the symbol.</p>


<p>This may or may not be the address used for relocation (clients can copy the data around and resolve relocatons based on where they put it).</p>


<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>, definition at line 1388 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>

</div>
</div>

### getSymbolSectionID() {#addb3f8e92465a1c1176a59939ce3bc6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RuntimeDyld::getSymbolSectionID (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the section <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the section containing the given symbol.</p>

<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>, definition at line 1394 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getSymbolTable() {#a38e5c630fbb8b8fe89bfa069e408c0dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt; StringRef, JITEvaluatedSymbol &gt; llvm::RuntimeDyld::getSymbolTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a copy of the symbol table.</p>


<p>This can be used by on-finalized callbacks to extract the symbol table before throwing away the <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> instance. Because the map keys (StringRefs) are backed by strings inside the <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> instance, the map should be processed before the <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> instance is discarded.</p>


<p>Declaration at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>, definition at line 1405 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a497e3b0265fea4f3a0d137a8884c71ff">llvm::jitLinkForORC</a>.</p>

</div>
</div>

### hasError() {#ac9ca4615d0ed50de50b989f9cb21dfc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RuntimeDyld::hasError ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>, definition at line 1422 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a497e3b0265fea4f3a0d137a8884c71ff">llvm::jitLinkForORC</a>.</p>

</div>
</div>

### loadObject() {#ad2ab8021c32ef2200c8b01e2105f1821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; RuntimeDyld::LoadedObjectInfo &gt; llvm::RuntimeDyld::loadObject (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the referenced object file to the list of objects to be loaded and relocated.</p>

<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>, definition at line 1361 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7111867eeceb3da6255a3586b39e29dc">llvm::createRuntimeDyldCOFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac15efaa1f9a3f1d46ffb0d0807f344f">llvm::createRuntimeDyldELF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a380ea73d38ddf536162107ad3229e1fc">llvm::createRuntimeDyldMachO</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#ade6a289b7efafc8625daf0575ad81c08">llvm::object::ObjectFile::getArch</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#ac391f637f5960964588dfac009094396">llvm::object::Binary::isCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#ae470b1ff27e3d72e61fcb4a97fd0a461">llvm::object::Binary::isELF</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a81663775ec5f9cc32d3d2d15815effbd">llvm::object::Binary::isMachO</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a497e3b0265fea4f3a0d137a8884c71ff">llvm::jitLinkForORC</a>.</p>

</div>
</div>

### mapSectionAddress() {#a0b3c521130df594d63177bda62de400d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyld::mapSectionAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * LocalAddress, uint64_t TargetAddress)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map a section to its target address space value.</p>


<p>Map the address of a JIT section as returned from the memory manager to the address in the target process as the running code will see it. This is the address which will be used for relocation resolution.</p>


<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>, definition at line 1417 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>

</div>
</div>

### reassignSectionAddress() {#a30ce7d72b88e0bc27b8c9e416e9a096c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyld::reassignSectionAddress (unsigned SectionID, uint64_t Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>, definition at line 1413 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>

</div>
</div>

### registerEHFrames() {#a90259a498cbb50bc825202e2a1ef6d3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyld::registerEHFrames ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> any EH frame sections that have been loaded but not previously registered with the memory manager.</p>


<p>Note, <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> is responsible for identifying the EH frame and calling the memory manager with the EH frame section data. However, the memory manager itself will handle the actual target-specific EH frame registration.</p>


<p>Declaration at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>, definition at line 1447 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>Referenced by <a href="#a71b4a375f2964ea13d4064b81dba59ef">finalizeWithMemoryManagerLocking</a>.</p>

</div>
</div>

### resolveRelocations() {#a4b3756c713e9a0e034b96a96ebd8ebc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyld::resolveRelocations ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Resolve the relocations for all symbols we currently know about.</p>

<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>, definition at line 1411 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a>.</p>


<p>Referenced by <a href="#a71b4a375f2964ea13d4064b81dba59ef">finalizeWithMemoryManagerLocking</a>.</p>

</div>
</div>

### setNotifyStubEmitted() {#a78efb467e88df60120327e89b66f6b87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyld::setNotifyStubEmitted (<a href="#a7ca2c024ef2bb555f0d9c3aae8b40583">NotifyStubEmittedFunction</a> NotifyStubEmitted)</td>
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

<p>Set the NotifyStubEmitted callback.</p>


<p>This is used for debugging purposes. A callback is made for each stub that is generated.</p>


<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>

</div>
</div>

### setProcessAllSections() {#a19cd93eb917e2a8cc5c900a5c0c015a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RuntimeDyld::setProcessAllSections (bool ProcessAllSections)</td>
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

<p>By default, only sections that are "required for execution" are passed to the <a href="/web-llvm/docs/api/classes/llvm/rtdyldmemorymanager">RTDyldMemoryManager</a>, and other sections are discarded.</p>


<p>Passing 'true' to this method will cause <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> to pass all sections to its memory manager regardless of whether they are "required to execute" in the usual sense. This is useful for inspecting metadata sections that may not contain relocations, E.g. Debug info, stackmaps.</p>


<p>Must be called before the first object file is loaded.</p>


<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a497e3b0265fea4f3a0d137a8884c71ff">llvm::jitLinkForORC</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Dyld {#aad038d9250b8b0b6b64dc6b6feedcc40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;RuntimeDyldImpl&gt; llvm::RuntimeDyld::Dyld</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>

</div>
</div>

### MemMgr {#aefd32b9fb140fa9dd099f6393a54b761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryManager&amp; llvm::RuntimeDyld::MemMgr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>

</div>
</div>

### NotifyStubEmitted {#abaaf202caa0796f7054d426654079cea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NotifyStubEmittedFunction llvm::RuntimeDyld::NotifyStubEmitted</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>

</div>
</div>

### ProcessAllSections {#afd90a1ee49b7276a3382e6f0caf320eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RuntimeDyld::ProcessAllSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>

</div>
</div>

### Resolver {#af053c407b8042ae61886dcc403328480}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITSymbolResolver&amp; llvm::RuntimeDyld::Resolver</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">RuntimeDyld.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyld-cpp">RuntimeDyld.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
