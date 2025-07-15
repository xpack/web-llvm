---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/staticlibrarydefinitiongenerator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `StaticLibraryDefinitionGenerator` Class Reference

<p>A utility class to expose symbols from a static library. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::StaticLibraryDefinitionGenerator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">llvm/ExecutionEngine/Orc/ExecutionUtils.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/definitiongenerator">DefinitionGenerator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Definition generators can be attached to JITDylibs to generate new definitions for otherwise unresolved symbols during lookup. <a href="/web-llvm/docs/api/classes/llvm/orc/definitiongenerator/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b5526b1881d5905911be2bc2ae1b74f">GetObjectFileInterface</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/materializationunit/interface">MaterializationUnit::Interface</a> &gt;( <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp;ES, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> ObjBuffer)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface builder function for objects loaded from this archive. <a href="#a1b5526b1881d5905911be2bc2ae1b74f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a056835b41d568acaa2b5a15ec1a4a93b">VisitMembersFunction</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>(<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a>)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback for visiting archive members at construction time. <a href="#a056835b41d568acaa2b5a15ec1a4a93b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b0b9e4566b3447852e22e35af1b95bf">StaticLibraryDefinitionGenerator</a> (ObjectLayer &amp;L, std::unique_ptr&lt; MemoryBuffer &gt; ArchiveBuffer, std::unique_ptr&lt; object::Archive &gt; Archive, GetObjectFileInterface GetObjFileInterface, Error &amp;Err)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::set&lt; std::string &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02e80f80933d19509377fe6a7114a38e">getImportedDynamicLibraries</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a list of filenames of dynamic libraries that this archive has imported. <a href="#a02e80f80933d19509377fe6a7114a38e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a553c068fc6fde1b82ee28bbc7bd11a8f">tryToGenerate</a> (LookupState &amp;LS, LookupKind K, JITDylib &amp;JD, JITDylibLookupFlags JDLookupFlags, const SymbolLookupSet &amp;Symbols) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DefinitionGenerators should override this method to insert new definitions into the parent <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a553c068fc6fde1b82ee28bbc7bd11a8f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af73a5e0047a84647b4331a52fc042919">buildObjectFilesMap</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/objectlayer">ObjectLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45ead74afff2f00c0f43d1a886cc33f4">L</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1b5526b1881d5905911be2bc2ae1b74f">GetObjectFileInterface</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8a9cf5d2174e5e51921114574d0764d">GetObjFileInterface</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::set&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac644d44037fe2b45fbb715a1fb242976">ImportedDynamicLibraries</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a102d9612f3d82756242639cf0efcf00f">ArchiveBuffer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/archive">object::Archive</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98b289c402188a5e7197e7d75783cff4">Archive</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a673e9f7c824a8debcc43b654efb7c80e">ObjectFilesMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a867ed3833d8a66dc15e9d06f69339db6">ObjFileNameStorage</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a056835b41d568acaa2b5a15ec1a4a93b">VisitMembersFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16a84f60ff615b07935df943c5f84a5e">loadAllObjectFileMembers</a> (ObjectLayer &amp;L, JITDylib &amp;JD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="#a056835b41d568acaa2b5a15ec1a4a93b">VisitMembersFunction</a> that unconditionally loads all object files from the archive. <a href="#a16a84f60ff615b07935df943c5f84a5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator">StaticLibraryDefinitionGenerator</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a703cd8845907b2859b4ebdd00c206bc1">Load</a> (ObjectLayer &amp;L, const char *FileName, VisitMembersFunction VisitMembers=VisitMembersFunction(), GetObjectFileInterface GetObjFileInterface=GetObjectFileInterface())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to create a <a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator">StaticLibraryDefinitionGenerator</a> from the given path. <a href="#a703cd8845907b2859b4ebdd00c206bc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator">StaticLibraryDefinitionGenerator</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e910497d88200a16108f6849b074ab8">Create</a> (ObjectLayer &amp;L, std::unique_ptr&lt; MemoryBuffer &gt; ArchiveBuffer, std::unique_ptr&lt; object::Archive &gt; Archive, VisitMembersFunction VisitMembers=VisitMembersFunction(), GetObjectFileInterface GetObjFileInterface=GetObjectFileInterface())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to create a StaticLibrarySearchGenerator from the given memory buffer and Archive object. <a href="#a6e910497d88200a16108f6849b074ab8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator">StaticLibraryDefinitionGenerator</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab4f9dfc17222d93cc4942c9b84470c6">Create</a> (ObjectLayer &amp;L, std::unique_ptr&lt; MemoryBuffer &gt; ArchiveBuffer, VisitMembersFunction VisitMembers=VisitMembersFunction(), GetObjectFileInterface GetObjFileInterface=GetObjectFileInterface())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to create a StaticLibrarySearchGenerator from the given memory buffer. <a href="#aab4f9dfc17222d93cc4942c9b84470c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A utility class to expose symbols from a static library.</p>


<p>If an instance of this class is attached to a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> as a fallback definition generator, then any symbol found in the archive will result in the containing object being added to the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### GetObjectFileInterface {#a1b5526b1881d5905911be2bc2ae1b74f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::StaticLibraryDefinitionGenerator::GetObjectFileInterface = 
      unique_function&lt;Expected&lt;MaterializationUnit::Interface&gt;(
          ExecutionSession &amp;ES, MemoryBufferRef ObjBuffer)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Interface builder function for objects loaded from this archive.</p>

<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>

</div>
</div>

### VisitMembersFunction {#a056835b41d568acaa2b5a15ec1a4a93b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::StaticLibraryDefinitionGenerator::VisitMembersFunction =  unique_function&lt;Error(MemoryBufferRef)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback for visiting archive members at construction time.</p>


<p>Con be used to pre-load archive members.</p>


<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### StaticLibraryDefinitionGenerator() {#a5b0b9e4566b3447852e22e35af1b95bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::StaticLibraryDefinitionGenerator::StaticLibraryDefinitionGenerator (<a href="/web-llvm/docs/api/classes/llvm/orc/objectlayer">ObjectLayer</a> &amp; L, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; ArchiveBuffer, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/archive">object::Archive</a> &gt; Archive, <a href="#a1b5526b1881d5905911be2bc2ae1b74f">GetObjectFileInterface</a> GetObjFileInterface, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>, definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executionutils-cpp">ExecutionUtils.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getImportedDynamicLibraries() {#a02e80f80933d19509377fe6a7114a38e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::set&lt; std::string &gt; &amp; llvm::orc::StaticLibraryDefinitionGenerator::getImportedDynamicLibraries ()</td>
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

<p>Returns a list of filenames of dynamic libraries that this archive has imported.</p>


<p>This class does not load these libraries by itself. <a href="/web-llvm/docs/api/classes/llvm/user">User</a> is responsible for making sure these libraries are available to the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>

</div>
</div>

### tryToGenerate() {#a553c068fc6fde1b82ee28bbc7bd11a8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::StaticLibraryDefinitionGenerator::tryToGenerate (<a href="/web-llvm/docs/api/classes/llvm/orc/lookupstate">LookupState</a> &amp; LS, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eb">LookupKind</a> K, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81d">JITDylibLookupFlags</a> JDLookupFlags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a> &amp; LookupSet)</td>
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

<p>DefinitionGenerators should override this method to insert new definitions into the parent <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>K specifies the kind of this lookup. JD specifies the target <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> being searched, and JDLookupFlags specifies whether the search should match against hidden symbols. Finally, Symbols describes the set of unresolved symbols and their associated lookup flags.</p>


<p>Declaration at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executionutils-cpp">ExecutionUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a0f68098734d6d3b451aacf5b38a67131">llvm::MemoryBuffer::getMemBuffer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eba84a8921b25f505d0d2077aeb5db4bc16">llvm::orc::Static</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### buildObjectFilesMap() {#af73a5e0047a84647b4331a52fc042919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::StaticLibraryDefinitionGenerator::buildObjectFilesMap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>, definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executionutils-cpp">ExecutionUtils.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Archive {#a98b289c402188a5e7197e7d75783cff4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;object::Archive&gt; llvm::orc::StaticLibraryDefinitionGenerator::Archive</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>

</div>
</div>

### ArchiveBuffer {#a102d9612f3d82756242639cf0efcf00f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemoryBuffer&gt; llvm::orc::StaticLibraryDefinitionGenerator::ArchiveBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>

</div>
</div>

### GetObjFileInterface {#aa8a9cf5d2174e5e51921114574d0764d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GetObjectFileInterface llvm::orc::StaticLibraryDefinitionGenerator::GetObjFileInterface</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>

</div>
</div>

### ImportedDynamicLibraries {#ac644d44037fe2b45fbb715a1fb242976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt;std::string&gt; llvm::orc::StaticLibraryDefinitionGenerator::ImportedDynamicLibraries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>

</div>
</div>

### L {#a45ead74afff2f00c0f43d1a886cc33f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectLayer&amp; llvm::orc::StaticLibraryDefinitionGenerator::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>

</div>
</div>

### ObjectFilesMap {#a673e9f7c824a8debcc43b654efb7c80e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;SymbolStringPtr, MemoryBufferRef&gt; llvm::orc::StaticLibraryDefinitionGenerator::ObjectFilesMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>

</div>
</div>

### ObjFileNameStorage {#a867ed3833d8a66dc15e9d06f69339db6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::orc::StaticLibraryDefinitionGenerator::ObjFileNameStorage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Create() {#a6e910497d88200a16108f6849b074ab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; StaticLibraryDefinitionGenerator &gt; &gt; llvm::orc::StaticLibraryDefinitionGenerator::Create (<a href="/web-llvm/docs/api/classes/llvm/orc/objectlayer">ObjectLayer</a> &amp; L, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; ArchiveBuffer, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/archive">object::Archive</a> &gt; Archive, <a href="#a056835b41d568acaa2b5a15ec1a4a93b">VisitMembersFunction</a> VisitMembers=<a href="#a056835b41d568acaa2b5a15ec1a4a93b">VisitMembersFunction</a>(), <a href="#a1b5526b1881d5905911be2bc2ae1b74f">GetObjectFileInterface</a> GetObjFileInterface=<a href="#a1b5526b1881d5905911be2bc2ae1b74f">GetObjectFileInterface</a>())</td>
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

<p>Try to create a StaticLibrarySearchGenerator from the given memory buffer and Archive object.</p>

<p>Declaration at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>, definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executionutils-cpp">ExecutionUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform/#a0ff140ec3eee8b9a860f3626b5640c04">llvm::orc::COFFPlatform::Create</a>, <a href="#aab4f9dfc17222d93cc4942c9b84470c6">Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#aaa681b188079626ba7d773d29128e3bf">llvm::orc::LLJIT::linkStaticLibraryInto</a>, <a href="#a703cd8845907b2859b4ebdd00c206bc1">Load</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/executornativeplatform/#aa1bd92add845031ceeaab24c2c25c275">llvm::orc::ExecutorNativePlatform::operator()</a>.</p>

</div>
</div>

### Create() {#aab4f9dfc17222d93cc4942c9b84470c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; StaticLibraryDefinitionGenerator &gt; &gt; llvm::orc::StaticLibraryDefinitionGenerator::Create (<a href="/web-llvm/docs/api/classes/llvm/orc/objectlayer">ObjectLayer</a> &amp; L, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; ArchiveBuffer, <a href="#a056835b41d568acaa2b5a15ec1a4a93b">VisitMembersFunction</a> VisitMembers=<a href="#a056835b41d568acaa2b5a15ec1a4a93b">VisitMembersFunction</a>(), <a href="#a1b5526b1881d5905911be2bc2ae1b74f">GetObjectFileInterface</a> GetObjFileInterface=<a href="#a1b5526b1881d5905911be2bc2ae1b74f">GetObjectFileInterface</a>())</td>
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

<p>Try to create a StaticLibrarySearchGenerator from the given memory buffer.</p>


<p>This call will succeed if the buffer contains a valid archive, otherwise it will return an error.</p>


<p>This call will succeed if the buffer contains a valid static library or a <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> universal binary containing a static library that is compatible with the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>'s triple. Otherwise it will return an error.</p>


<p>Declaration at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>, definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executionutils-cpp">ExecutionUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a6e910497d88200a16108f6849b074ab8">Create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#afff545dbbc7e3d85c4e6d914200747db">llvm::object::Archive::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#aebd3886db896c46327320cfd1ccc808c">llvm::object::createBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#aa01e73e66cd4ea6703e66a9c213f2e6a">llvm::orc::getMachOSliceRangeForTriple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>.</p>

</div>
</div>

### Load() {#a703cd8845907b2859b4ebdd00c206bc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; StaticLibraryDefinitionGenerator &gt; &gt; llvm::orc::StaticLibraryDefinitionGenerator::Load (<a href="/web-llvm/docs/api/classes/llvm/orc/objectlayer">ObjectLayer</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * FileName, <a href="#a056835b41d568acaa2b5a15ec1a4a93b">VisitMembersFunction</a> VisitMembers=<a href="#a056835b41d568acaa2b5a15ec1a4a93b">VisitMembersFunction</a>(), <a href="#a1b5526b1881d5905911be2bc2ae1b74f">GetObjectFileInterface</a> GetObjFileInterface=<a href="#a1b5526b1881d5905911be2bc2ae1b74f">GetObjectFileInterface</a>())</td>
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

<p>Try to create a <a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator">StaticLibraryDefinitionGenerator</a> from the given path.</p>


<p>This call will succeed if the file at the given path is a static library or a <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> universal binary containing a static library that is compatible with the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>'s triple. Otherwise it will return an error.</p>


<p>Declaration at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>, definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executionutils-cpp">ExecutionUtils.cpp</a>.</p>


<p>References <a href="#a6e910497d88200a16108f6849b074ab8">Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1a325b7b8ec75f271d91355d4216b6c4">llvm::orc::loadLinkableFile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a8062d0529fef4a678f022739e603e196af62b6d5aa008bfa83a2510cbda8e7960">llvm::orc::Required</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform/#a176a05717f48de0630c7881365edd895">llvm::orc::ELFNixPlatform::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/machoplatform/#a1d471ce68684309b46d6afa43f8ec0a9">llvm::orc::MachOPlatform::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#aa7573528896e709770c5e31bdf597555">llvm::orc::LLJIT::linkStaticLibraryInto</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp/#a734850637f9fd595b4fb8aac2f1fe061">LLVMOrcCreateStaticLibrarySearchGeneratorForPath</a>.</p>

</div>
</div>

### loadAllObjectFileMembers() {#a16a84f60ff615b07935df943c5f84a5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StaticLibraryDefinitionGenerator::VisitMembersFunction llvm::orc::StaticLibraryDefinitionGenerator::loadAllObjectFileMembers (<a href="/web-llvm/docs/api/classes/llvm/orc/objectlayer">ObjectLayer</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD)</td>
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

<p>A <a href="#a056835b41d568acaa2b5a15ec1a4a93b">VisitMembersFunction</a> that unconditionally loads all object files from the archive.</p>


<p>Archive members that are not valid object files will be skipped.</p>


<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a>, definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executionutils-cpp">ExecutionUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aac575f4e16f05741d7656211f860dfcc3">llvm::file_magic::coff_object</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa1b167178973059ff5b3a4b2bf2377450">llvm::file_magic::elf_relocatable</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a0f68098734d6d3b451aacf5b38a67131">llvm::MemoryBuffer::getMemBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a00941e59a16ad6eb14e905557a612501">llvm::identify_magic</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aac557d5088dac1a5cca0c2c7e78174632">llvm::file_magic::macho_object</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executionutils-h">ExecutionUtils.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/executionutils-cpp">ExecutionUtils.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
