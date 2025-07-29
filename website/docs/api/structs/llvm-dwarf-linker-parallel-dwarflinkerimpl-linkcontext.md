---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `LinkContext` Struct

<p>Keeps track of data associated with one object during linking. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinker/Parallel/DWARFLinkerImpl.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections">OutputSections</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class keeps contents and offsets to the debug sections. <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a761021d422f8d1e09ae7ed3472575229">UnitListTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> &gt; &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52133b657f383fa508cda0681fd7d5b5">ModuleUnitListTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/refmoduleunit">RefModuleUnit</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ab3780e334068dcd1d8e0525e7b9607">LinkContext</a> (LinkingGlobalData &amp;GlobalData, DWARFFile &amp;File, StringMap&lt; uint64_t &gt; &amp;ClangModules, std::atomic&lt; size_t &gt; &amp;UniqueUnitID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; bool, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62ed34db5672583fcefb9c152e2dad01">isClangModuleRef</a> (const DWARFDie &amp;CUDie, std::string &amp;PCMFile, unsigned Indent, bool Quiet)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether specified <span class="doxyComputerOutput">CUDie</span> is a Clang module reference. <a href="#a62ed34db5672583fcefb9c152e2dad01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cd88157223b53c481e0e884c7e01933">registerModuleReference</a> (const DWARFDie &amp;CUDie, ObjFileLoaderTy Loader, CompileUnitHandlerTy OnCUDieLoaded, unsigned Indent=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this compile unit is really a skeleton <a href="/web-llvm/docs/api/namespaces/cu">CU</a> that points to a clang module, register it in ClangModules and return true. <a href="#a1cd88157223b53c481e0e884c7e01933">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21dc5ae67ffaf38250ef5b5d377b5358">loadClangModule</a> (ObjFileLoaderTy Loader, const DWARFDie &amp;CUDie, const std::string &amp;PCMFile, CompileUnitHandlerTy OnCUDieLoaded, unsigned Indent=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively add the debug info in this clang module .pcm file (and all the modules imported by it in a bottom-up fashion) to ModuleUnits. <a href="#a21dc5ae67ffaf38250ef5b5d377b5358">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a2ea523c01ea8054a7ac17d4ac88a88">addModulesCompileUnit</a> (RefModuleUnit &amp;&amp;Unit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add Compile Unit corresponding to the module. <a href="#a6a2ea523c01ea8054a7ac17d4ac88a88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05534779d40c36897d51602a488e002a">getInputDebugInfoSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the total size of the debug info. <a href="#a05534779d40c36897d51602a488e002a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad06d8aa0d7980827ad6f0a8543657f73">link</a> (TypeUnit *ArtificialTypeUnit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Link compile units for this context. <a href="#ad06d8aa0d7980827ad6f0a8543657f73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d0aeeed6972f179a2b97439943e7629">linkSingleCompileUnit</a> (CompileUnit &amp;CU, TypeUnit *ArtificialTypeUnit, enum CompileUnit::Stage DoUntilStage=CompileUnit::Stage::Cleaned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Link specified compile unit until specified stage. <a href="#a8d0aeeed6972f179a2b97439943e7629">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e9424dbd42c4c0b08ff61c556bd9aa1">emitInvariantSections</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit invariant sections. <a href="#a5e9424dbd42c4c0b08ff61c556bd9aa1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4560fb1d6b91d4ba6edb7e907573c1e">cloneAndEmitDebugFrame</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone and emit .debug_frame. <a href="#ac4560fb1d6b91d4ba6edb7e907573c1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c61c3e648797ee04fda231739eedfa2">emitFDE</a> (uint32_t CIEOffset, uint32_t AddrSize, uint64_t Address, StringRef FDEBytes, SectionDescriptor &amp;Section)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit FDE record. <a href="#a6c61c3e648797ee04fda231739eedfa2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a417c1e564a19f0f7e0c6dc59be1c6600">InputDWARFFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Object file descriptor. <a href="#a417c1e564a19f0f7e0c6dc59be1c6600">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a761021d422f8d1e09ae7ed3472575229">UnitListTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ef418e361948dd4503650d033d22963">CompileUnits</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of Compilation Units(may be accessed asynchroniously for reading). <a href="#a6ef418e361948dd4503650d033d22963">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a52133b657f383fa508cda0681fd7d5b5">ModuleUnitListTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4f8392645d2249731beb417750a2dc6">ModulesCompileUnits</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of Compile Units for modules. <a href="#af4f8392645d2249731beb417750a2dc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e4c50d63f8ad2ec4d1bac07ec6549df">OriginalDebugInfoSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size of Debug info before optimizing. <a href="#a5e4c50d63f8ad2ec4d1bac07ec6549df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c9dded231809812ab62437da9ab5ed3">InterCUProcessingStarted</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag indicating that all inter-connected units are loaded and the dwarf linking process for these units is started. <a href="#a0c9dded231809812ab62437da9ab5ed3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; uint64_t &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1fdd4e78bba5b397fb2dd50ec53b856">ClangModules</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaf7494cb3e5c41c67dc7086c909e4e8">HasNewInterconnectedCUs</a> = {false}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag indicating that new inter-connected compilation units were discovered. <a href="#abaf7494cb3e5c41c67dc7086c909e4e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeeef0198c6829d7289ee79d9886eca8">HasNewGlobalDependency</a> = {false}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; size_t &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8fa0b20d640780b6f573746e0c06620">UniqueUnitID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Counter for compile units <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#ac8fa0b20d640780b6f573746e0c06620">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> *(uint64_t)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af19e106ec06ab341fb66c99516f420b5">getUnitForOffset</a> = ...</td>
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

<p>Keeps track of data associated with one object during linking.</p>


<p>i.e. source file descriptor, compilation units, output data for compilation units common tables.</p>


<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ModuleUnitListTy {#a52133b657f383fa508cda0681fd7d5b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::ModuleUnitListTy =  SmallVector&lt;RefModuleUnit&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>

</div>
</div>

### UnitListTy {#a761021d422f8d1e09ae7ed3472575229}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::UnitListTy =  SmallVector&lt;std::unique_ptr&lt;CompileUnit&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LinkContext() {#a5ab3780e334068dcd1d8e0525e7b9607}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFLinkerImpl::LinkContext::LinkContext (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/linkingglobaldata">LinkingGlobalData</a> &amp; GlobalData, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; File, <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; uint64_t &gt; &amp; ClangModules, std::atomic&lt; size_t &gt; &amp; UniqueUnitID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="#ac1fdd4e78bba5b397fb2dd50ec53b856">ClangModules</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a>, <a href="#a417c1e564a19f0f7e0c6dc59be1c6600">InputDWARFFile</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0f3129c5b81b6f215d2ac67d576f6c5f">llvm::dwarf_linker::parallel::OutputSections::OutputSections</a> and <a href="#ac8fa0b20d640780b6f573746e0c06620">UniqueUnitID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addModulesCompileUnit() {#a6a2ea523c01ea8054a7ac17d4ac88a88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::LinkContext::addModulesCompileUnit (<a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/refmoduleunit">RefModuleUnit</a> &amp;&amp; Unit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add Compile Unit corresponding to the module.</p>

<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>Reference <a href="#af4f8392645d2249731beb417750a2dc6">ModulesCompileUnits</a>.</p>

</div>
</div>

### cloneAndEmitDebugFrame() {#ac4560fb1d6b91d4ba6edb7e907573c1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DWARFLinkerImpl::LinkContext::cloneAndEmitDebugFrame ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone and emit .debug_frame.</p>

<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 731 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="#a6ef418e361948dd4503650d033d22963">CompileUnits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f4ffaa2f15fc8f612a233e3b45510c0">llvm::createFileError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfsection/#a9e58386bb12fb74a439b815c0b219c8b">llvm::DWARFSection::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24af10a68fc1fe9d1ce73395130849d4269">llvm::dwarf_linker::DebugFrame</a>, <a href="#a6c61c3e648797ee04fda231739eedfa2">emitFDE</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#affecf20a5e4d1351ace92b2b76f8c8b7">llvm::DWARFObject::getAddressSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#a15d7005fd6f90e6e9415f68094b43542">llvm::DWARFObject::getFileName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#a28c711b52cb292791c9da24c5144dc79">llvm::DWARFObject::getFrameSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#ab6597212694001f13f816944c69bb0b2">llvm::dwarf_linker::parallel::OutputSections::getOrCreateSectionDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/addressrangesbase/#a98c9746510478a6bf94369316794e1ea">llvm::AddressRangesBase&lt; T &gt;::getRangeThatContains</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a>, <a href="#a417c1e564a19f0f7e0c6dc59be1c6600">InputDWARFFile</a>, <a href="/web-llvm/docs/api/classes/llvm/addressrangesmap/#a94b4c5f0709d739fb1fe98712618afe6">llvm::AddressRangesMap::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#afea367cbdd62e85c20d3ebe044253ce7">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#a0883bc300220df6b45d9c6c6feb362d7">llvm::DWARFObject::isLittleEndian</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a01de9af3f8e9b5ca39f42089c9a0e8ce">llvm::dwarf_linker::parallel::SectionDescriptor::OS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a>.</p>


<p>Referenced by <a href="#ad06d8aa0d7980827ad6f0a8543657f73">link</a>.</p>

</div>
</div>

### emitFDE() {#a6c61c3e648797ee04fda231739eedfa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::LinkContext::emitFDE (uint32_t CIEOffset, uint32_t AddrSize, uint64_t Address, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FDEBytes, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> &amp; Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit FDE record.</p>


<p>Emit a FDE into the debug_frame section.</p>


<p><span class="doxyComputerOutput">FDEBytes</span> contains the FDE data without the length, CIE offset and address which will be replaced with the parameter values.</p>


<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 842 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="#ac4560fb1d6b91d4ba6edb7e907573c1e">cloneAndEmitDebugFrame</a>.</p>

</div>
</div>

### emitInvariantSections() {#a5e9424dbd42c4c0b08ff61c556bd9aa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DWARFLinkerImpl::LinkContext::emitInvariantSections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit invariant sections.</p>

<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 709 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24aef3096c553fe7abacddd617a1c377330">llvm::dwarf_linker::DebugAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a422efaefecbe9d2217dbee8ea8dc812c">llvm::dwarf_linker::DebugARanges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24af10a68fc1fe9d1ce73395130849d4269">llvm::dwarf_linker::DebugFrame</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a0b4ec7dfa0beee39e0d09a0cf5c09f54">llvm::dwarf_linker::DebugLocLists</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a558f46094c3e1ffac3dba6928d34c2b9">llvm::dwarf_linker::DebugRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ab09a90abca61cf08407bb116fdc3b75d">llvm::dwarf_linker::DebugRngLists</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#ab6597212694001f13f816944c69bb0b2">llvm::dwarf_linker::parallel::OutputSections::getOrCreateSectionDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a>, <a href="#a417c1e564a19f0f7e0c6dc59be1c6600">InputDWARFFile</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a01de9af3f8e9b5ca39f42089c9a0e8ce">llvm::dwarf_linker::parallel::SectionDescriptor::OS</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#ad06d8aa0d7980827ad6f0a8543657f73">link</a>.</p>

</div>
</div>

### getInputDebugInfoSize() {#a05534779d40c36897d51602a488e002a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::getInputDebugInfoSize ()</td>
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

<p>Computes the total size of the debug info.</p>

<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>References <a href="#a417c1e564a19f0f7e0c6dc59be1c6600">InputDWARFFile</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#ad06d8aa0d7980827ad6f0a8543657f73">link</a>.</p>

</div>
</div>

### isClangModuleRef() {#a62ed34db5672583fcefb9c152e2dad01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; bool, bool &gt; DWARFLinkerImpl::LinkContext::isClangModuleRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; CUDie, std::string &amp; PCMFile, unsigned Indent, bool Quiet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether specified <span class="doxyComputerOutput">CUDie</span> is a Clang module reference.</p>


<p>if <span class="doxyComputerOutput">Quiet</span> is false then display error messages.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>first == true if CUDie is a Clang module reference. second == true if module is already loaded.</p></dd>
</dl>


<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="#ac1fdd4e78bba5b397fb2dd50ec53b856">ClangModules</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a315f90678bfa85d85d71a9dd12d5457a">llvm::DWARFDie::find</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8aeafac87842fc748625b83753887067">llvm::getDwoId</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="#a417c1e564a19f0f7e0c6dc59be1c6600">InputDWARFFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d9d5328bc7a7ba4906fb7a366cc9a32a098753f8980036f4b936e3d4b6997111">llvm::Quiet</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a39a67e6dc97585d609932dc2fb04a377">llvm::dwarf::toString</a>.</p>


<p>Referenced by <a href="#ad06d8aa0d7980827ad6f0a8543657f73">link</a> and <a href="#a1cd88157223b53c481e0e884c7e01933">registerModuleReference</a>.</p>

</div>
</div>

### link() {#ad06d8aa0d7980827ad6f0a8543657f73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DWARFLinkerImpl::LinkContext::link (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit">TypeUnit</a> * ArtificialTypeUnit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Link compile units for this context.</p>

<p>Declaration at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/data/#ga83a3aaddca0607d7b14c89dcf9dd0ccd">llvm::dwarf_linker::parallel::DWARFLinkerImpl::ArtificialTypeUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ac8f9de0c8d86b73c76368b681f0d7883a71fb656255391c5f521e5742aaad23dd">llvm::dwarf_linker::parallel::CompileUnit::Cleaned</a>, <a href="#ac4560fb1d6b91d4ba6edb7e907573c1e">cloneAndEmitDebugFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ac8f9de0c8d86b73c76368b681f0d7883a19a35ef9463a94f30004fac9ddb0fd52">llvm::dwarf_linker::parallel::CompileUnit::Cloned</a>, <a href="#a6ef418e361948dd4503650d033d22963">CompileUnits</a>, <a href="#a5e9424dbd42c4c0b08ff61c556bd9aa1">emitInvariantSections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a98a8554492a59019e487d750863f96f2">llvm::dwarf_linker::finiteLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#ab0df9b23ed5b92045b815ebf04d16070">llvm::dwarf_linker::parallel::OutputSections::getEndianness</a>, <a href="#a05534779d40c36897d51602a488e002a">getInputDebugInfoSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a58c8277a8af9d4c7d299c82c95b39668">llvm::getPCMFile</a>, <a href="#af19e106ec06ab341fb66c99516f420b5">getUnitForOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a>, <a href="#aeeeef0198c6829d7289ee79d9886eca8">HasNewGlobalDependency</a>, <a href="#abaf7494cb3e5c41c67dc7086c909e4e8">HasNewInterconnectedCUs</a>, <a href="#a417c1e564a19f0f7e0c6dc59be1c6600">InputDWARFFile</a>, <a href="#a0c9dded231809812ab62437da9ab5ed3">InterCUProcessingStarted</a>, <a href="#a62ed34db5672583fcefb9c152e2dad01">isClangModuleRef</a>, <a href="#a8d0aeeed6972f179a2b97439943e7629">linkSingleCompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ac8f9de0c8d86b73c76368b681f0d7883aa1af45d7ba3138a16acdede1e85ede84">llvm::dwarf_linker::parallel::CompileUnit::LivenessAnalysisDone</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ac8f9de0c8d86b73c76368b681f0d7883a7381d487d18845b379422325c0a768d6">llvm::dwarf_linker::parallel::CompileUnit::Loaded</a>, <a href="#af4f8392645d2249731beb417750a2dc6">ModulesCompileUnits</a>, <a href="#a5e4c50d63f8ad2ec4d1bac07ec6549df">OriginalDebugInfoSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1d81feea56661c4d5cfa58bcc1f4347">llvm::parallelForEach</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ac8f9de0c8d86b73c76368b681f0d7883a4e1541154b3fa09fc872add2c3993a62">llvm::dwarf_linker::parallel::CompileUnit::PatchesUpdated</a>, <a href="/web-llvm/docs/api/classes/llvm/parallel/taskgroup/#a5f936d7e589b0615fccac0a4c0cb8d97">llvm::parallel::TaskGroup::spawn</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ac8f9de0c8d86b73c76368b681f0d7883a2872e735c9749db6fa8336d07e11389e">llvm::dwarf_linker::parallel::CompileUnit::TypeNamesAssigned</a>, <a href="#ac8fa0b20d640780b6f573746e0c06620">UniqueUnitID</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/refmoduleunit/#a9ed3724a2c9ce77f034408ef50cae6d5">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::RefModuleUnit::Unit</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ac8f9de0c8d86b73c76368b681f0d7883ad0387a23f6c7310e7543f802cff3bce0">llvm::dwarf_linker::parallel::CompileUnit::UpdateDependenciesCompleteness</a>.</p>

</div>
</div>

### linkSingleCompileUnit() {#a8d0aeeed6972f179a2b97439943e7629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::LinkContext::linkSingleCompileUnit (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> &amp; CU, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit">TypeUnit</a> * ArtificialTypeUnit, enum <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ac8f9de0c8d86b73c76368b681f0d7883">CompileUnit::Stage</a> DoUntilStage=<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ac8f9de0c8d86b73c76368b681f0d7883a71fb656255391c5f521e5742aaad23dd">CompileUnit::Stage::Cleaned</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Link specified compile unit until specified stage.</p>

<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 591 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/data/#ga83a3aaddca0607d7b14c89dcf9dd0ccd">llvm::dwarf_linker::parallel::DWARFLinkerImpl::ArtificialTypeUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ac8f9de0c8d86b73c76368b681f0d7883a71fb656255391c5f521e5742aaad23dd">llvm::dwarf_linker::parallel::CompileUnit::Cleaned</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ac8f9de0c8d86b73c76368b681f0d7883a19a35ef9463a94f30004fac9ddb0fd52">llvm::dwarf_linker::parallel::CompileUnit::Cloned</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ac8f9de0c8d86b73c76368b681f0d7883a44f476a85bed95ceb67cabb6d0de35b7">llvm::dwarf_linker::parallel::CompileUnit::CreatedNotLoaded</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a98a8554492a59019e487d750863f96f2">llvm::dwarf_linker::finiteLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a>, <a href="#aeeeef0198c6829d7289ee79d9886eca8">HasNewGlobalDependency</a>, <a href="#abaf7494cb3e5c41c67dc7086c909e4e8">HasNewInterconnectedCUs</a>, <a href="#a0c9dded231809812ab62437da9ab5ed3">InterCUProcessingStarted</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ac8f9de0c8d86b73c76368b681f0d7883aa1af45d7ba3138a16acdede1e85ede84">llvm::dwarf_linker::parallel::CompileUnit::LivenessAnalysisDone</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ac8f9de0c8d86b73c76368b681f0d7883a7381d487d18845b379422325c0a768d6">llvm::dwarf_linker::parallel::CompileUnit::Loaded</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ac8f9de0c8d86b73c76368b681f0d7883a4e1541154b3fa09fc872add2c3993a62">llvm::dwarf_linker::parallel::CompileUnit::PatchesUpdated</a>, <a href="#a1cd88157223b53c481e0e884c7e01933">registerModuleReference</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ac8f9de0c8d86b73c76368b681f0d7883ad9c8f187972e6320a34e9c40b4cba605">llvm::dwarf_linker::parallel::CompileUnit::Skipped</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ac8f9de0c8d86b73c76368b681f0d7883a2872e735c9749db6fa8336d07e11389e">llvm::dwarf_linker::parallel::CompileUnit::TypeNamesAssigned</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ac8f9de0c8d86b73c76368b681f0d7883ad0387a23f6c7310e7543f802cff3bce0">llvm::dwarf_linker::parallel::CompileUnit::UpdateDependenciesCompleteness</a>.</p>


<p>Referenced by <a href="#ad06d8aa0d7980827ad6f0a8543657f73">link</a>.</p>

</div>
</div>

### loadClangModule() {#a21dc5ae67ffaf38250ef5b5d377b5358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DWARFLinkerImpl::LinkContext::loadClangModule (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#abdf3094623b3752dabeeb5bd7ceb24ad">ObjFileLoaderTy</a> Loader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; CUDie, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; PCMFile, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a537122974e714f93e8ad5fa29439e856">CompileUnitHandlerTy</a> OnCUDieLoaded, unsigned Indent=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursively add the debug info in this clang module .pcm file (and all the modules imported by it in a bottom-up fashion) to ModuleUnits.</p>

<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="#ac1fdd4e78bba5b397fb2dd50ec53b856">ClangModules</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a315f90678bfa85d85d71a9dd12d5457a">llvm::DWARFDie::find</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8aeafac87842fc748625b83753887067">llvm::getDwoId</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#ab0df9b23ed5b92045b815ebf04d16070">llvm::dwarf_linker::parallel::OutputSections::getEndianness</a>, <a href="#af19e106ec06ab341fb66c99516f420b5">getUnitForOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="#a417c1e564a19f0f7e0c6dc59be1c6600">InputDWARFFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a59d172f36ecf079548e9c539ae54e5a4">llvm::sys::path::is_relative</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#af4f8392645d2249731beb417750a2dc6">ModulesCompileUnits</a>, <a href="#a1cd88157223b53c481e0e884c7e01933">registerModuleReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a562e5e47a3837612432809e480b901e3">llvm::resolveRelativeObjectPath</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a39a67e6dc97585d609932dc2fb04a377">llvm::dwarf::toString</a> and <a href="#ac8fa0b20d640780b6f573746e0c06620">UniqueUnitID</a>.</p>


<p>Referenced by <a href="#a1cd88157223b53c481e0e884c7e01933">registerModuleReference</a>.</p>

</div>
</div>

### registerModuleReference() {#a1cd88157223b53c481e0e884c7e01933}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFLinkerImpl::LinkContext::registerModuleReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; CUDie, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#abdf3094623b3752dabeeb5bd7ceb24ad">ObjFileLoaderTy</a> Loader, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a537122974e714f93e8ad5fa29439e856">CompileUnitHandlerTy</a> OnCUDieLoaded, unsigned Indent=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this compile unit is really a skeleton <a href="/web-llvm/docs/api/namespaces/cu">CU</a> that points to a clang module, register it in ClangModules and return true.</p>


<p>A skeleton <a href="/web-llvm/docs/api/namespaces/cu">CU</a> is a <a href="/web-llvm/docs/api/namespaces/cu">CU</a> without children, a DW_AT_gnu_dwo_name pointing to the module, and a DW_AT_gnu_dwo_id with the module hash.</p>


<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="#ac1fdd4e78bba5b397fb2dd50ec53b856">ClangModules</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8aeafac87842fc748625b83753887067">llvm::getDwoId</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a58c8277a8af9d4c7d299c82c95b39668">llvm::getPCMFile</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a>, <a href="#a62ed34db5672583fcefb9c152e2dad01">isClangModuleRef</a>, <a href="#a21dc5ae67ffaf38250ef5b5d377b5358">loadClangModule</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a>.</p>


<p>Referenced by <a href="#a8d0aeeed6972f179a2b97439943e7629">linkSingleCompileUnit</a> and <a href="#a21dc5ae67ffaf38250ef5b5d377b5358">loadClangModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ClangModules {#ac1fdd4e78bba5b397fb2dd50ec53b856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;uint64_t&gt;&amp; llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::ClangModules</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Referenced by <a href="#a62ed34db5672583fcefb9c152e2dad01">isClangModuleRef</a>, <a href="#a5ab3780e334068dcd1d8e0525e7b9607">LinkContext</a>, <a href="#a21dc5ae67ffaf38250ef5b5d377b5358">loadClangModule</a> and <a href="#a1cd88157223b53c481e0e884c7e01933">registerModuleReference</a>.</p>

</div>
</div>

### CompileUnits {#a6ef418e361948dd4503650d033d22963}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnitListTy llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::CompileUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of Compilation Units(may be accessed asynchroniously for reading).</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Referenced by <a href="#ac4560fb1d6b91d4ba6edb7e907573c1e">cloneAndEmitDebugFrame</a> and <a href="#ad06d8aa0d7980827ad6f0a8543657f73">link</a>.</p>

</div>
</div>

### getUnitForOffset {#af19e106ec06ab341fb66c99516f420b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;CompileUnit *(uint64_t)&gt; llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::getUnitForOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
        [&amp;](uint64_t <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">Offset</a>) -&gt; <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> * {
      auto CU = <a href="/web-llvm/docs/api/namespaces/llvm/#a4b7d2ab11554bd10d15b6cb21b2c2787">llvm::upper_bound</a>(
          <a href="#a6ef418e361948dd4503650d033d22963">CompileUnits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">Offset</a>,
          [](uint64_t <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::unique_ptr&lt;<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a>&gt; &amp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>) {
            return <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> &lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>-&gt;getOrigUnit().getNextUnitOffset();
          });
      return CU != CompileUnits.end() ? CU-&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">get</a>() : nullptr;
    }
</div>
</dd>
</dl>

<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Referenced by <a href="#ad06d8aa0d7980827ad6f0a8543657f73">link</a> and <a href="#a21dc5ae67ffaf38250ef5b5d377b5358">loadClangModule</a>.</p>

</div>
</div>

### HasNewGlobalDependency {#aeeeef0198c6829d7289ee79d9886eca8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;bool&gt; llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::HasNewGlobalDependency = {false}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Referenced by <a href="#ad06d8aa0d7980827ad6f0a8543657f73">link</a> and <a href="#a8d0aeeed6972f179a2b97439943e7629">linkSingleCompileUnit</a>.</p>

</div>
</div>

### HasNewInterconnectedCUs {#abaf7494cb3e5c41c67dc7086c909e4e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;bool&gt; llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::HasNewInterconnectedCUs = {false}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag indicating that new inter-connected compilation units were discovered.</p>


<p>It is used for restarting units processing if new inter-connected units were found.</p>


<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Referenced by <a href="#ad06d8aa0d7980827ad6f0a8543657f73">link</a> and <a href="#a8d0aeeed6972f179a2b97439943e7629">linkSingleCompileUnit</a>.</p>

</div>
</div>

### InputDWARFFile {#a417c1e564a19f0f7e0c6dc59be1c6600}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFFile&amp; llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::InputDWARFFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Object file descriptor.</p>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Referenced by <a href="#ac4560fb1d6b91d4ba6edb7e907573c1e">cloneAndEmitDebugFrame</a>, <a href="#a5e9424dbd42c4c0b08ff61c556bd9aa1">emitInvariantSections</a>, <a href="#a05534779d40c36897d51602a488e002a">getInputDebugInfoSize</a>, <a href="#a62ed34db5672583fcefb9c152e2dad01">isClangModuleRef</a>, <a href="#ad06d8aa0d7980827ad6f0a8543657f73">link</a>, <a href="#a5ab3780e334068dcd1d8e0525e7b9607">LinkContext</a> and <a href="#a21dc5ae67ffaf38250ef5b5d377b5358">loadClangModule</a>.</p>

</div>
</div>

### InterCUProcessingStarted {#a0c9dded231809812ab62437da9ab5ed3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::InterCUProcessingStarted = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag indicating that all inter-connected units are loaded and the dwarf linking process for these units is started.</p>

<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Referenced by <a href="#ad06d8aa0d7980827ad6f0a8543657f73">link</a> and <a href="#a8d0aeeed6972f179a2b97439943e7629">linkSingleCompileUnit</a>.</p>

</div>
</div>

### ModulesCompileUnits {#af4f8392645d2249731beb417750a2dc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleUnitListTy llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::ModulesCompileUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of Compile Units for modules.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Referenced by <a href="#a6a2ea523c01ea8054a7ac17d4ac88a88">addModulesCompileUnit</a>, <a href="#ad06d8aa0d7980827ad6f0a8543657f73">link</a> and <a href="#a21dc5ae67ffaf38250ef5b5d377b5358">loadClangModule</a>.</p>

</div>
</div>

### OriginalDebugInfoSize {#a5e4c50d63f8ad2ec4d1bac07ec6549df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::OriginalDebugInfoSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size of Debug info before optimizing.</p>

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Referenced by <a href="#ad06d8aa0d7980827ad6f0a8543657f73">link</a>.</p>

</div>
</div>

### UniqueUnitID {#ac8fa0b20d640780b6f573746e0c06620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;size_t&gt;&amp; llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::UniqueUnitID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Counter for compile units <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>

<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Referenced by <a href="#ad06d8aa0d7980827ad6f0a8543657f73">link</a>, <a href="#a5ab3780e334068dcd1d8e0525e7b9607">LinkContext</a> and <a href="#a21dc5ae67ffaf38250ef5b5d377b5358">loadClangModule</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
