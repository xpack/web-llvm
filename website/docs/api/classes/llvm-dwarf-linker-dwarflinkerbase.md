---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/dwarflinkerbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DWARFLinkerBase` Class

<p>The base interface for <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker">DWARFLinker</a> implementations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::DWARFLinkerBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">llvm/DWARFLinker/DWARFLinkerBase.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker">DWARFLinker</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The core of the Dwarf linking logic. <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinker">DWARFLinker</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6171d1affe838c4595f5bc1306ca5749">MessageHandlerTy</a> = std::function&lt; void( <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a0eaadb4fcb48a0a0ed7bc9868be9fbaa">Warning</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> *<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>)&gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdf3094623b3752dabeeb5bd7ceb24ad">ObjFileLoaderTy</a> = std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; &gt;( <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ContainerName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path)&gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac482b3b01bd8e00cd02ecfba94e88694">InputVerificationHandlerTy</a> = std::function&lt; void(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp;File, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Output)&gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b10e00e608ed9bcead9c3c7bcd62b4c">ObjectPrefixMapTy</a> = std::map&lt; std::string, std::string &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a537122974e714f93e8ad5fa29439e856">CompileUnitHandlerTy</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> &amp;Unit)&gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7230244084c9a0c89b2113444331260">SwiftInterfacesMapTy</a> = std::map&lt; std::string, std::string &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OutputFileType : uint8_t { <a href="#aba62c3e12b7c341d64f21e98325f4082">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of output file. <a href="#aba62c3e12b7c341d64f21e98325f4082">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AccelTableKind : uint8_t { <a href="#a78ca7920cd1aaf69f7da553285c55308">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The kind of accelerator tables to be emitted. <a href="#a78ca7920cd1aaf69f7da553285c55308">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e1120c43e3a5dad3262ab158857bfce">~DWARFLinkerBase</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cd1c06e048565246194a799ecbc9486">addObjectFile</a> (DWARFFile &amp;File, ObjFileLoaderTy Loader=nullptr, CompileUnitHandlerTy OnCUDieLoaded=[](const DWARFUnit &amp;) {})=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an object file to be linked. <a href="#a1cd1c06e048565246194a799ecbc9486">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c06ee4a3b2d38bf3fc825fc74580383">link</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Link the debug info for all object files added through calls to addObjectFile. <a href="#a5c06ee4a3b2d38bf3fc825fc74580383">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dca372a9ce194fb6229528b4a1f9ed1">setVerbosity</a> (bool Verbose)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A number of methods setting various linking options: Enable logging to standard output. <a href="#a6dca372a9ce194fb6229528b4a1f9ed1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dfbf23fdcb24d443f9bc71946ff162e">setStatistics</a> (bool Statistics)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print statistics to standard output. <a href="#a9dfbf23fdcb24d443f9bc71946ff162e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e83aaae6734ba1c6b88cf33c1385433">setVerifyInputDWARF</a> (bool Verify)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the input DWARF. <a href="#a7e83aaae6734ba1c6b88cf33c1385433">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd26699118ddc2e3a819d96ceae62105">setNoODR</a> (bool NoODR)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do not unique types according to ODR. <a href="#afd26699118ddc2e3a819d96ceae62105">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84197c8fcb9b0eaec294a800bdfa6f69">setUpdateIndexTablesOnly</a> (bool Update)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update index tables only (do not modify rest of DWARF). <a href="#a84197c8fcb9b0eaec294a800bdfa6f69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a410af2fa92cd9d9212ec907727bd20b7">setAllowNonDeterministicOutput</a> (bool)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allows generating non-deterministic output in exchange for more parallelism. <a href="#a410af2fa92cd9d9212ec907727bd20b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a348a3140c262752a95cf457cc4f87f56">setKeepFunctionForStatic</a> (bool KeepFunctionForStatic)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set whether to keep the enclosing function for a static variable. <a href="#a348a3140c262752a95cf457cc4f87f56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06d0812f600a91908eb8e3dff058842a">setNumThreads</a> (unsigned NumThreads)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> specified number of threads for parallel files linking. <a href="#a06d0812f600a91908eb8e3dff058842a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a695221640f0ce12baf933c6c84a56304">addAccelTableKind</a> (AccelTableKind Kind)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add kind of accelerator tables to be generated. <a href="#a695221640f0ce12baf933c6c84a56304">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4cb202f68a8a4e00b0795eaaa96634f">setPrependPath</a> (StringRef Ppath)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set prepend path for clang modules. <a href="#ad4cb202f68a8a4e00b0795eaaa96634f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a1a44080da5982bafd54dc2e4e1fae0">setEstimatedObjfilesAmount</a> (unsigned ObjFilesNum)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set estimated objects files amount, for preliminary data allocation. <a href="#a2a1a44080da5982bafd54dc2e4e1fae0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeefca349d3a5f672394a68ac92f5f43">setInputVerificationHandler</a> (InputVerificationHandlerTy Handler)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set verification handler used to report verification errors. <a href="#adeefca349d3a5f672394a68ac92f5f43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4de4f6bdb6745431d564e632324d27d7">setSwiftInterfacesMap</a> (SwiftInterfacesMapTy *Map)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set map for Swift interfaces. <a href="#a4de4f6bdb6745431d564e632324d27d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a618ba947bc20587d40c9caeac603af3d">setObjectPrefixMap</a> (ObjectPrefixMapTy *Map)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set prefix map for objects. <a href="#a618ba947bc20587d40c9caeac603af3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f64d34a0a87ea1901a0029abb5db6b9">setTargetDWARFVersion</a> (uint16_t TargetDWARFVersion)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set target DWARF version. <a href="#a6f64d34a0a87ea1901a0029abb5db6b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The base interface for <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker">DWARFLinker</a> implementations.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### CompileUnitHandlerTy {#a537122974e714f93e8ad5fa29439e856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::DWARFLinkerBase::CompileUnitHandlerTy =  function_ref&lt;void(const DWARFUnit &amp;Unit)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

### InputVerificationHandlerTy {#ac482b3b01bd8e00cd02ecfba94e88694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::DWARFLinkerBase::InputVerificationHandlerTy = 
      std::function&lt;void(const DWARFFile &amp;File, llvm::StringRef Output)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

### MessageHandlerTy {#a6171d1affe838c4595f5bc1306ca5749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::DWARFLinkerBase::MessageHandlerTy =  std::function&lt;void(
      const Twine &amp;Warning, StringRef Context, const DWARFDie *DIE)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

### ObjectPrefixMapTy {#a0b10e00e608ed9bcead9c3c7bcd62b4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::DWARFLinkerBase::ObjectPrefixMapTy =  std::map&lt;std::string, std::string&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

### ObjFileLoaderTy {#abdf3094623b3752dabeeb5bd7ceb24ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::DWARFLinkerBase::ObjFileLoaderTy =  std::function&lt;ErrorOr&lt;DWARFFile &amp;&gt;(
      StringRef ContainerName, StringRef Path)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

### SwiftInterfacesMapTy {#ab7230244084c9a0c89b2113444331260}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::DWARFLinkerBase::SwiftInterfacesMapTy =  std::map&lt;std::string, std::string&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### AccelTableKind {#a78ca7920cd1aaf69f7da553285c55308}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::dwarf_linker::DWARFLinkerBase::AccelTableKind : uint8_t</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The kind of accelerator tables to be emitted.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Apple<a id="a78ca7920cd1aaf69f7da553285c55308a9f6290f4436e5a2351f12e03b6433c3c"></a></td>
<td class="doxyEnumItemDescription">.apple_names, .apple_namespaces, .apple_types, .apple_objc</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pub<a id="a78ca7920cd1aaf69f7da553285c55308aa29bdd003ef6c0c34279807341f450f2"></a></td>
<td class="doxyEnumItemDescription">.debug_pubnames, .debug_pubtypes</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DebugNames<a id="a78ca7920cd1aaf69f7da553285c55308a20f18d4a28570b83b8f5bd6c9d26d7b8"></a></td>
<td class="doxyEnumItemDescription">.debug_names</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

### OutputFileType {#aba62c3e12b7c341d64f21e98325f4082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::dwarf_linker::DWARFLinkerBase::OutputFileType : uint8_t</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of output file.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Object<a id="aba62c3e12b7c341d64f21e98325f4082a497031794414a552435f90151ac3b54b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Assembly<a id="aba62c3e12b7c341d64f21e98325f4082ad75c45e11c8aeb13494dba59a388a164"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DWARFLinkerBase() {#a3e1120c43e3a5dad3262ab158857bfce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::dwarf_linker::DWARFLinkerBase::~DWARFLinkerBase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAccelTableKind() {#a695221640f0ce12baf933c6c84a56304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::DWARFLinkerBase::addAccelTableKind (<a href="#a78ca7920cd1aaf69f7da553285c55308">AccelTableKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add kind of accelerator tables to be generated.</p>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

### addObjectFile() {#a1cd1c06e048565246194a799ecbc9486}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::DWARFLinkerBase::addObjectFile (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; File, <a href="#abdf3094623b3752dabeeb5bd7ceb24ad">ObjFileLoaderTy</a> Loader=nullptr, <a href="#a537122974e714f93e8ad5fa29439e856">CompileUnitHandlerTy</a> OnCUDieLoaded=[](<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> &amp;) {})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an object file to be linked.</p>


<p>Pre-load compile unit die. Call <span class="doxyComputerOutput">OnCUDieLoaded</span> for each compile unit die. If <span class="doxyComputerOutput">File</span> has reference to a Clang module and UpdateIndexTablesOnly == false then the module is be pre-loaded by <span class="doxyComputerOutput">Loader</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>a call to setNoODR(true) and/or <a href="#a84197c8fcb9b0eaec294a800bdfa6f69">setUpdateIndexTablesOnly(bool Update)</a> must be made when required.</p></dd>
</dl>


<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

### link() {#a5c06ee4a3b2d38bf3fc825fc74580383}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::dwarf_linker::DWARFLinkerBase::link ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Link the debug info for all object files added through calls to addObjectFile.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

### setAllowNonDeterministicOutput() {#a410af2fa92cd9d9212ec907727bd20b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::DWARFLinkerBase::setAllowNonDeterministicOutput (bool)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allows generating non-deterministic output in exchange for more parallelism.</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

### setEstimatedObjfilesAmount() {#a2a1a44080da5982bafd54dc2e4e1fae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::DWARFLinkerBase::setEstimatedObjfilesAmount (unsigned ObjFilesNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set estimated objects files amount, for preliminary data allocation.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

### setInputVerificationHandler() {#adeefca349d3a5f672394a68ac92f5f43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::DWARFLinkerBase::setInputVerificationHandler (<a href="#ac482b3b01bd8e00cd02ecfba94e88694">InputVerificationHandlerTy</a> Handler)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set verification handler used to report verification errors.</p>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

### setKeepFunctionForStatic() {#a348a3140c262752a95cf457cc4f87f56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::DWARFLinkerBase::setKeepFunctionForStatic (bool KeepFunctionForStatic)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set whether to keep the enclosing function for a static variable.</p>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

### setNoODR() {#afd26699118ddc2e3a819d96ceae62105}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::DWARFLinkerBase::setNoODR (bool NoODR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Do not unique types according to ODR.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

### setNumThreads() {#a06d0812f600a91908eb8e3dff058842a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::DWARFLinkerBase::setNumThreads (unsigned NumThreads)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> specified number of threads for parallel files linking.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

### setObjectPrefixMap() {#a618ba947bc20587d40c9caeac603af3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::DWARFLinkerBase::setObjectPrefixMap (<a href="#a0b10e00e608ed9bcead9c3c7bcd62b4c">ObjectPrefixMapTy</a> * Map)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set prefix map for objects.</p>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

### setPrependPath() {#ad4cb202f68a8a4e00b0795eaaa96634f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::DWARFLinkerBase::setPrependPath (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Ppath)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set prepend path for clang modules.</p>

<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

### setStatistics() {#a9dfbf23fdcb24d443f9bc71946ff162e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::DWARFLinkerBase::setStatistics (bool Statistics)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print statistics to standard output.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

### setSwiftInterfacesMap() {#a4de4f6bdb6745431d564e632324d27d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::DWARFLinkerBase::setSwiftInterfacesMap (<a href="#ab7230244084c9a0c89b2113444331260">SwiftInterfacesMapTy</a> * Map)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set map for Swift interfaces.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

### setTargetDWARFVersion() {#a6f64d34a0a87ea1901a0029abb5db6b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::dwarf_linker::DWARFLinkerBase::setTargetDWARFVersion (uint16_t TargetDWARFVersion)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set target DWARF version.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

### setUpdateIndexTablesOnly() {#a84197c8fcb9b0eaec294a800bdfa6f69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::DWARFLinkerBase::setUpdateIndexTablesOnly (bool Update)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update index tables only (do not modify rest of DWARF).</p>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>

</div>
</div>

### setVerbosity() {#a6dca372a9ce194fb6229528b4a1f9ed1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::DWARFLinkerBase::setVerbosity (bool Verbose)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A number of methods setting various linking options: Enable logging to standard output.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#adacba4cb06d1dd9232ee3d2d49a44d8fad4a9fa383ab700c5bdd6f31cf7df0faf">llvm::Verbose</a>.</p>

</div>
</div>

### setVerifyInputDWARF() {#a7e83aaae6734ba1c6b88cf33c1385433}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::DWARFLinkerBase::setVerifyInputDWARF (bool Verify)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify the input DWARF.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp/#a345bd69760b9ee32b3f49d4fc04120fb">Verify</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarflinkerbase-h">DWARFLinkerBase.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
