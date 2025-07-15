---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/findrootdies
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The Find DIEs corresponding to Address map entries. Reference

<p>Recursively walk the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a></span> tree and look for DIEs to keep. <a href="#details">More...</a></p>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga2b4682e0fe0146440fe8826e4e67182e">lookForDIEsToKeep</a> (AddressesMap &amp;RelocMgr, const UnitListTy &amp;Units, const DWARFDie &amp;DIE, const DWARFFile &amp;File, CompileUnit &amp;CU, unsigned Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively walk the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a></span> tree and look for DIEs to keep. <a href="#ga2b4682e0fe0146440fe8826e4e67182e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; bool, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga343cf73eec78f37be68c0f8a131a0d49">isClangModuleRef</a> (const DWARFDie &amp;CUDie, std::string &amp;PCMFile, LinkContext &amp;Context, unsigned Indent, bool Quiet)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether specified <span class="doxyComputerOutput">CUDie</span> is a Clang module reference. <a href="#ga343cf73eec78f37be68c0f8a131a0d49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gabd5556765c8fe5426d92dc474a1e7966">registerModuleReference</a> (const DWARFDie &amp;CUDie, LinkContext &amp;Context, ObjFileLoaderTy Loader, CompileUnitHandlerTy OnCUDieLoaded, unsigned Indent=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this compile unit is really a skeleton <a href="/web-llvm/docs/api/namespaces/cu">CU</a> that points to a clang module, register it in ClangModules and return true. <a href="#gabd5556765c8fe5426d92dc474a1e7966">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Error</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga173d5c588b7bec182a851c6cfd7b3fa4">loadClangModule</a> (ObjFileLoaderTy Loader, const DWARFDie &amp;CUDie, const std::string &amp;PCMFile, LinkContext &amp;Context, CompileUnitHandlerTy OnCUDieLoaded, unsigned Indent=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively add the debug info in this clang module .pcm file (and all the modules imported by it in a bottom-up fashion) to ModuleUnits. <a href="#ga173d5c588b7bec182a851c6cfd7b3fa4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Error</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga16541c95c463709f1163b52f913e6bc4">cloneModuleUnit</a> (LinkContext &amp;Context, RefModuleUnit &amp;Unit, DeclContextTree &amp;ODRContexts, OffsetsStringPool &amp;DebugStrPool, OffsetsStringPool &amp;DebugLineStrPool, DebugDieValuePool &amp;StringOffsetPool, unsigned Indent=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone specified Clang module unit <span class="doxyComputerOutput">Unit</span>. <a href="#ga16541c95c463709f1163b52f913e6bc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga24c2bcead90bfc63a47c4c1832093b10">shouldKeepDIE</a> (AddressesMap &amp;RelocMgr, const DWARFDie &amp;DIE, const DWARFFile &amp;File, CompileUnit &amp;Unit, CompileUnit::DIEInfo &amp;MyInfo, unsigned Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> should be kept. <a href="#ga24c2bcead90bfc63a47c4c1832093b10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; bool, std::optional&lt; int64_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaa180d20c87f7cda613a75894475ca2f0">getVariableRelocAdjustment</a> (AddressesMap &amp;RelocMgr, const DWARFDie &amp;DIE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function checks whether variable has DWARF expression containing operation referencing live address(f.e. <a href="#gaa180d20c87f7cda613a75894475ca2f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga036b9988329e2d2dff7482b094cc5d63">shouldKeepVariableDIE</a> (AddressesMap &amp;RelocMgr, const DWARFDie &amp;DIE, CompileUnit::DIEInfo &amp;MyInfo, unsigned Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a variable describing <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> should be kept. <a href="#ga036b9988329e2d2dff7482b094cc5d63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf0bf84a58c76b6f9173903dc44014df7">shouldKeepSubprogramDIE</a> (AddressesMap &amp;RelocMgr, const DWARFDie &amp;DIE, const DWARFFile &amp;File, CompileUnit &amp;Unit, CompileUnit::DIEInfo &amp;MyInfo, unsigned Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a function describing <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> should be kept. <a href="#gaf0bf84a58c76b6f9173903dc44014df7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">DWARFDie</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga6061ea947e754c29e1a73d644b113f03">resolveDIEReference</a> (const DWARFFile &amp;File, const UnitListTy &amp;Units, const DWARFFormValue &amp;RefValue, const DWARFDie &amp;DIE, CompileUnit *&amp;RefCU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resolve the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> attribute reference that has been extracted in <span class="doxyComputerOutput">RefValue</span>. <a href="#ga6061ea947e754c29e1a73d644b113f03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Recursively walk the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a></span> tree and look for DIEs to keep.</p>


<p>Store that information in <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/cu">CU</a>'s</span> DIEInfo.</p>


<p>The return value indicates whether the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> is incomplete.</p>


<div class="doxySectionDef">

## Functions

### cloneModuleUnit() {#ga16541c95c463709f1163b52f913e6bc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::DWARFLinker::cloneModuleUnit (LinkContext &amp; Context, RefModuleUnit &amp; Unit, DeclContextTree &amp; ODRContexts, OffsetsStringPool &amp; DebugStrPool, OffsetsStringPool &amp; DebugLineStrPool, DebugDieValuePool &amp; StringOffsetPool, unsigned Indent=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone specified Clang module unit <span class="doxyComputerOutput">Unit</span>.</p>

<p>Declaration at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 3031 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### getVariableRelocAdjustment() {#gaa180d20c87f7cda613a75894475ca2f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; bool, std::optional&lt; int64_t &gt; &gt; llvm::DWARFLinker::getVariableRelocAdjustment (AddressesMap &amp; RelocMgr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDie &amp; DIE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function checks whether variable has DWARF expression containing operation referencing live address(f.e.</p>


<p>DW_OP_addr, DW_OP_addrx...).</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>first is true if the expression has an operation referencing an address. second is the relocation adjustment value if the live address is referenced.</p></dd>
</dl>


<p>Declaration at line 515 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### isClangModuleRef() {#ga343cf73eec78f37be68c0f8a131a0d49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; bool, bool &gt; llvm::DWARFLinker::isClangModuleRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDie &amp; CUDie, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &amp; PCMFile, LinkContext &amp; Context, unsigned Indent, bool Quiet)</td>
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


<p>Declaration at line 472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 2468 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### loadClangModule() {#ga173d5c588b7bec182a851c6cfd7b3fa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::DWARFLinker::loadClangModule (ObjFileLoaderTy Loader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDie &amp; CUDie, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &amp; PCMFile, LinkContext &amp; Context, CompileUnitHandlerTy OnCUDieLoaded, unsigned Indent=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursively add the debug info in this clang module .pcm file (and all the modules imported by it in a bottom-up fashion) to ModuleUnits.</p>

<p>Declaration at line 491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 2540 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### lookForDIEsToKeep() {#ga2b4682e0fe0146440fe8826e4e67182e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFLinker::lookForDIEsToKeep (AddressesMap &amp; AddressesMap, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> UnitListTy &amp; Units, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDie &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFFile &amp; File, CompileUnit &amp; Cu, unsigned Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursively walk the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a></span> tree and look for DIEs to keep.</p>


<p>Store that information in <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/cu">CU</a>'s</span> DIEInfo.</p>


<p>This function is the entry point of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> selection algorithm. It is expected to walk the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree in file order and (though the mediation of its helper) call hasValidRelocation() on each <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> that might be a 'root <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>' (See DwarfLinker class comment).</p>


<p>While walking the dependencies of root DIEs, this function is also called, but during these dependency walks the file order is not respected. The TF_DependencyWalk flag tells us which kind of traversal we are currently doing.</p>


<p>The recursive algorithm is implemented iteratively as a work list because very deep recursion could exhaust the stack for large projects. The work list acts as a scheduler for different types of work that need to be performed.</p>


<p>The recursive nature of the algorithm is simulated by running the "main" algorithm (LookForDIEsToKeep) followed by either looking at more DIEs (LookForChildDIEsToKeep, LookForRefDIEsToKeep, LookForParentDIEsToKeep) or fixing up a computed property (UpdateChildIncompleteness, UpdateRefIncompleteness).</p>


<p>The return value indicates whether the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> is incomplete.</p>


<p>Declaration at line 464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 848 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### registerModuleReference() {#gabd5556765c8fe5426d92dc474a1e7966}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFLinker::registerModuleReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDie &amp; CUDie, LinkContext &amp; Context, ObjFileLoaderTy Loader, CompileUnitHandlerTy OnCUDieLoaded, unsigned Indent=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this compile unit is really a skeleton <a href="/web-llvm/docs/api/namespaces/cu">CU</a> that points to a clang module, register it in ClangModules and return true.</p>


<p>A skeleton <a href="/web-llvm/docs/api/namespaces/cu">CU</a> is a <a href="/web-llvm/docs/api/namespaces/cu">CU</a> without children, a DW_AT_gnu_dwo_name pointing to the module, and a DW_AT_gnu_dwo_id with the module hash.</p>


<p>Declaration at line 483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 2510 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### resolveDIEReference() {#ga6061ea947e754c29e1a73d644b113f03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie llvm::DWARFLinker::resolveDIEReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFFile &amp; File, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> UnitListTy &amp; Units, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFFormValue &amp; RefValue, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDie &amp; DIE, CompileUnit *&amp; RefCU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Resolve the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> attribute reference that has been extracted in <span class="doxyComputerOutput">RefValue</span>.</p>


<p>The resulting <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> might be in another <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> which is stored into <span class="doxyComputerOutput">ReferencedCU</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>null if resolving fails for any reason.</p></dd>
</dl>


<p>Declaration at line 531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### shouldKeepDIE() {#ga24c2bcead90bfc63a47c4c1832093b10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARFLinker::shouldKeepDIE (AddressesMap &amp; RelocMgr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDie &amp; DIE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFFile &amp; File, CompileUnit &amp; Unit, CompileUnit::DIEInfo &amp; MyInfo, unsigned Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> should be kept.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>updated TraversalFlags.</p></dd>
</dl>


<p>Declaration at line 504 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### shouldKeepSubprogramDIE() {#gaf0bf84a58c76b6f9173903dc44014df7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARFLinker::shouldKeepSubprogramDIE (AddressesMap &amp; RelocMgr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDie &amp; DIE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFFile &amp; File, CompileUnit &amp; Unit, CompileUnit::DIEInfo &amp; MyInfo, unsigned Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a function describing <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> should be kept.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>updated TraversalFlags.</p></dd>
</dl>


<p>Declaration at line 522 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 556 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### shouldKeepVariableDIE() {#ga036b9988329e2d2dff7482b094cc5d63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARFLinker::shouldKeepVariableDIE (AddressesMap &amp; RelocMgr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDie &amp; DIE, CompileUnit::DIEInfo &amp; MyInfo, unsigned Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a variable describing <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> should be kept.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>updated TraversalFlags.</p></dd>
</dl>


<p>Declaration at line 519 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
