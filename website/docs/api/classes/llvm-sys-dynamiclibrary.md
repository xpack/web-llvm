---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sys/dynamiclibrary
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DynamicLibrary` Class

<p>This class provides a portable interface to dynamic libraries which also might be known as shared libraries, shared objects, dynamic shared objects, or dynamic link libraries. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sys::DynamicLibrary { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dynamiclibrary-h">llvm/Support/DynamicLibrary.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SearchOrdering { <a href="#a5e198e8003db7c5e9f35ee98a5897e59">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57f3eea5ad36a6b82ec5bb2b63363227">DynamicLibrary</a> (void *data=&amp;Invalid)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51c12a36736447d90300d62519f1879f">getOSSpecificHandle</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the OS specific handle value. <a href="#a51c12a36736447d90300d62519f1879f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad719c4aa9bee4753891741603642eca4">isValid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the object refers to a valid library. <a href="#ad719c4aa9bee4753891741603642eca4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba426dbb54c99f3421554c5087c91f85">getAddressOfSymbol</a> (const char *symbolName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Searches through the library for the symbol <span class="doxyComputerOutput">symbolName</span>. <a href="#aba426dbb54c99f3421554c5087c91f85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f2f33f19363d0acd00a7c978ba03e81">Data</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary">DynamicLibrary</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fe607fc919d5fcd00bdfded75f46643">getPermanentLibrary</a> (const char *filename, std::string *errMsg=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function permanently loads the dynamic library at the given path using the library load operation from the host operating system. <a href="#a5fe607fc919d5fcd00bdfded75f46643">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary">DynamicLibrary</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ef93af5b33193a6575a733c1a7104af">addPermanentLibrary</a> (void *handle, std::string *errMsg=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Registers an externally loaded library. <a href="#a1ef93af5b33193a6575a733c1a7104af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53d32d3b3baefdec31d3d94b0586d437">LoadLibraryPermanently</a> (const char *Filename, std::string *ErrMsg=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function permanently loads the dynamic library at the given path. <a href="#a53d32d3b3baefdec31d3d94b0586d437">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary">DynamicLibrary</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1222f2fb8f4a8b093d6419c74ff30e1e">getLibrary</a> (const char *FileName, std::string *Err=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function loads the dynamic library at the given path, using the library load operation from the host operating system. <a href="#a1222f2fb8f4a8b093d6419c74ff30e1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed402a3aa473bf44f618d2ec9129738c">closeLibrary</a> (DynamicLibrary &amp;Lib)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function closes the dynamic library at the given path, using the library close operation of the host operating system, and there is no guarantee if or when this will cause the library to be unloaded. <a href="#aed402a3aa473bf44f618d2ec9129738c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae003d16a33e81b88943d3e3aa179fcc4">SearchForAddressOfSymbol</a> (const char *symbolName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function will search through all previously loaded dynamic libraries for the symbol <span class="doxyComputerOutput">symbolName</span>. <a href="#ae003d16a33e81b88943d3e3aa179fcc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d4956a5c03696b5bb8230f61deb8061">SearchForAddressOfSymbol</a> (const std::string &amp;symbolName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience function for C++ophiles. <a href="#a5d4956a5c03696b5bb8230f61deb8061">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f997f2beb9cf206cd215663be3b9617">AddSymbol</a> (StringRef symbolName, void *symbolValue)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This functions permanently adds the symbol <span class="doxyComputerOutput">symbolName</span> with the value <span class="doxyComputerOutput">symbolValue</span>. <a href="#a2f997f2beb9cf206cd215663be3b9617">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a5e198e8003db7c5e9f35ee98a5897e59">SearchOrdering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a796ad78100654a505c1803a39208fb5d">SearchOrder</a> = ...</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b07f244d11dea80d03128cbadaa1cd4">Invalid</a></td>
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

<p>This class provides a portable interface to dynamic libraries which also might be known as shared libraries, shared objects, dynamic shared objects, or dynamic link libraries.</p>


<p>Regardless of the terminology or the operating system interface, this class provides a portable interface that allows dynamic libraries to be loaded and searched for externally defined symbols. This is typically used to provide "plug-in" support. It also allows for symbols to be defined which don't live in any library, but rather the main program itself, useful on Windows where the main executable cannot be searched.</p>


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dynamiclibrary-h">DynamicLibrary.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### SearchOrdering {#a5e198e8003db7c5e9f35ee98a5897e59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::sys::DynamicLibrary::SearchOrdering </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SO_Linker<a id="a5e198e8003db7c5e9f35ee98a5897e59a8e2b356d38ac9fe1f4a792153d6049a0"></a></td>
<td class="doxyEnumItemDescription">SO_Linker - Search as a call to dlsym(dlopen(NULL)) would when DynamicLibrary::getPermanentLibrary(NULL) has been called or search the list of explcitly loaded symbols if not</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SO_LoadedFirst<a id="a5e198e8003db7c5e9f35ee98a5897e59a8e941223db97baefe656ec0adc0d78ab"></a></td>
<td class="doxyEnumItemDescription">SO_LoadedFirst - Search all loaded libraries, then as SO_Linker would</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SO_LoadedLast<a id="a5e198e8003db7c5e9f35ee98a5897e59a455bb962eea2904a7faa441d04b59946"></a></td>
<td class="doxyEnumItemDescription">SO_LoadedLast - Search as SO_Linker would, then loaded libraries</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SO_LoadOrder<a id="a5e198e8003db7c5e9f35ee98a5897e59a766335f02cb77f4bea92f2212f65c0b5"></a></td>
<td class="doxyEnumItemDescription">SO_LoadOrder - Or this in to search libraries in the ordered loaded (= 4)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dynamiclibrary-h">DynamicLibrary.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DynamicLibrary() {#a57f3eea5ad36a6b82ec5bb2b63363227}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::DynamicLibrary::DynamicLibrary (void * data=&amp;Invalid)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dynamiclibrary-h">DynamicLibrary.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>.</p>


<p>Referenced by <a href="#a1ef93af5b33193a6575a733c1a7104af">addPermanentLibrary</a>, <a href="#aed402a3aa473bf44f618d2ec9129738c">closeLibrary</a>, <a href="#a1222f2fb8f4a8b093d6419c74ff30e1e">getLibrary</a> and <a href="#a5fe607fc919d5fcd00bdfded75f46643">getPermanentLibrary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAddressOfSymbol() {#aba426dbb54c99f3421554c5087c91f85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * DynamicLibrary::getAddressOfSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * symbolName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Searches through the library for the symbol <span class="doxyComputerOutput">symbolName</span>.</p>


<p>If it is found, the address of that symbol is returned. If not, NULL is returned. Note that NULL will also be returned if the library failed to load. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <a href="#ad719c4aa9bee4753891741603642eca4">isValid()</a> to distinguish these cases if it is important. Note that this will <em>not</em> search symbols explicitly registered by <a href="#a2f997f2beb9cf206cd215663be3b9617">AddSymbol()</a>.</p>


<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dynamiclibrary-h">DynamicLibrary.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/dynamiclibrary/handleset/#aaea4161534624cd91cd5404b6f25291c">llvm::sys::DynamicLibrary::HandleSet::DLSym</a> and <a href="#ad719c4aa9bee4753891741603642eca4">isValid</a>.</p>

</div>
</div>

### getOSSpecificHandle() {#a51c12a36736447d90300d62519f1879f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::sys::DynamicLibrary::getOSSpecificHandle ()</td>
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

<p>Return the OS specific handle value.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dynamiclibrary-h">DynamicLibrary.h</a>.</p>

</div>
</div>

### isValid() {#ad719c4aa9bee4753891741603642eca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::DynamicLibrary::isValid ()</td>
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

<p>Returns true if the object refers to a valid library.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dynamiclibrary-h">DynamicLibrary.h</a>.</p>


<p>Referenced by <a href="#aba426dbb54c99f3421554c5087c91f85">getAddressOfSymbol</a> and <a href="#a53d32d3b3baefdec31d3d94b0586d437">LoadLibraryPermanently</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Data {#a2f2f33f19363d0acd00a7c978ba03e81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::sys::DynamicLibrary::Data</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dynamiclibrary-h">DynamicLibrary.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### addPermanentLibrary() {#a1ef93af5b33193a6575a733c1a7104af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DynamicLibrary DynamicLibrary::addPermanentLibrary (void * handle, std::string * errMsg=nullptr)</td>
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

<p>Registers an externally loaded library.</p>


<p>The library will be unloaded when the program terminates.</p>


<p>It is safe to call this function multiple times for the same library, though ownership is only taken if there was no error.</p>


<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dynamiclibrary-h">DynamicLibrary.h</a>, definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>


<p>References <a href="#a57f3eea5ad36a6b82ec5bb2b63363227">DynamicLibrary</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>

</div>
</div>

### AddSymbol() {#a2f997f2beb9cf206cd215663be3b9617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DynamicLibrary::AddSymbol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> symbolName, void * symbolValue)</td>
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

<p>This functions permanently adds the symbol <span class="doxyComputerOutput">symbolName</span> with the value <span class="doxyComputerOutput">symbolValue</span>.</p>


<p>These symbols are searched before any libraries. Add searchable symbol/value pair.</p>


<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dynamiclibrary-h">DynamicLibrary.h</a>, definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmccore/#ga8706a6e4aa81193f97cf40c1dd8c0d3a">LLVMAddSymbol</a>.</p>

</div>
</div>

### closeLibrary() {#aed402a3aa473bf44f618d2ec9129738c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DynamicLibrary::closeLibrary (<a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary">DynamicLibrary</a> &amp; Lib)</td>
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

<p>This function closes the dynamic library at the given path, using the library close operation of the host operating system, and there is no guarantee if or when this will cause the library to be unloaded.</p>


<p>This function should be called only if the library was loaded using the <a href="#a1222f2fb8f4a8b093d6419c74ff30e1e">getLibrary()</a> function.</p>


<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dynamiclibrary-h">DynamicLibrary.h</a>, definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>


<p>References <a href="#a57f3eea5ad36a6b82ec5bb2b63363227">DynamicLibrary</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a372f87e2cac1c83389c98554dc44806da043d23e54edc5360a7785ae212d1b806">llvm::Lib</a>.</p>

</div>
</div>

### getLibrary() {#a1222f2fb8f4a8b093d6419c74ff30e1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DynamicLibrary DynamicLibrary::getLibrary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * FileName, std::string * Err=nullptr)</td>
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

<p>This function loads the dynamic library at the given path, using the library load operation from the host operating system.</p>


<p>The library instance will be closed when closeLibrary is called or global destructors are run, but there is no guarantee when the library will be unloaded.</p>


<p>This returns a valid <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary">DynamicLibrary</a> instance on success and an invalid instance on failure (see <a href="#ad719c4aa9bee4753891741603642eca4">isValid()</a>). <span class="doxyComputerOutput">*Err</span> will only be modified if the library fails to load.</p>


<p>It is safe to call this function multiple times for the same library.</p>


<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dynamiclibrary-h">DynamicLibrary.h</a>, definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/dynamiclibrary/handleset/#a9df2a55f4a1ee34610802540457f3fab">llvm::sys::DynamicLibrary::HandleSet::DLOpen</a>, <a href="#a57f3eea5ad36a6b82ec5bb2b63363227">DynamicLibrary</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>

</div>
</div>

### getPermanentLibrary() {#a5fe607fc919d5fcd00bdfded75f46643}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DynamicLibrary DynamicLibrary::getPermanentLibrary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * filename, std::string * errMsg=nullptr)</td>
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

<p>This function permanently loads the dynamic library at the given path using the library load operation from the host operating system.</p>


<p>The library instance will only be closed when global destructors run, and there is no guarantee when the library will be unloaded.</p>


<p>This returns a valid <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary">DynamicLibrary</a> instance on success and an invalid instance on failure (see <a href="#ad719c4aa9bee4753891741603642eca4">isValid()</a>). <span class="doxyComputerOutput">*errMsg</span> will only be modified if the library fails to load.</p>


<p>It is safe to call this function multiple times for the same library. Open a dynamic library permanently.</p>


<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dynamiclibrary-h">DynamicLibrary.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/dynamiclibrary/handleset/#a9df2a55f4a1ee34610802540457f3fab">llvm::sys::DynamicLibrary::HandleSet::DLOpen</a>, <a href="#a57f3eea5ad36a6b82ec5bb2b63363227">DynamicLibrary</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/dynamiclibrarysearchgenerator/#a6a9c2b5ee04aac9abc6857434c7d71b4">llvm::orc::DynamicLibrarySearchGenerator::Load</a>, <a href="/web-llvm/docs/api/classes/llvm/passplugin/#a16bba9d356b9f317678e118c6de531da">llvm::PassPlugin::Load</a>, <a href="#a53d32d3b3baefdec31d3d94b0586d437">LoadLibraryPermanently</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutordylibmanager/#a89babf245d443732b10c16ced7ca9c08">llvm::orc::rt_bootstrap::SimpleExecutorDylibManager::open</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86loadvalueinjectionloadhardening-cpp-/x86loadvalueinjectionloadhardeningpass/#a54e4ad32ffe88b1a55da7ca8c9d90521">anonymous{X86LoadValueInjectionLoadHardening.cpp}::X86LoadValueInjectionLoadHardeningPass::runOnMachineFunction</a>.</p>

</div>
</div>

### LoadLibraryPermanently() {#a53d32d3b3baefdec31d3d94b0586d437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::DynamicLibrary::LoadLibraryPermanently (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Filename, std::string * ErrMsg=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function permanently loads the dynamic library at the given path.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> this instead of <a href="#a5fe607fc919d5fcd00bdfded75f46643">getPermanentLibrary()</a> when you won't need to get symbols from the library itself.</p>


<p>It is safe to call this function multiple times for the same library.</p>


<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dynamiclibrary-h">DynamicLibrary.h</a>.</p>


<p>References <a href="#a5fe607fc919d5fcd00bdfded75f46643">getPermanentLibrary</a> and <a href="#ad719c4aa9bee4753891741603642eca4">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#af775bc7e1e968734ced732bfceae8c57">llvm::EngineBuilder::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a224802805182e755345184d485c164b8">llvm::MCJIT::createJIT</a>, <a href="/web-llvm/docs/api/groups/llvmccore/#ga6fc1331c1a6d2cc6f0fda94f4a4636f9">LLVMLoadLibraryPermanently</a> and <a href="/web-llvm/docs/api/structs/llvm/pluginloader/#ad128978e88e7b6b2c2c5ee07728c7cf3">llvm::PluginLoader::operator=</a>.</p>

</div>
</div>

### SearchForAddressOfSymbol() {#ae003d16a33e81b88943d3e3aa179fcc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * DynamicLibrary::SearchForAddressOfSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * symbolName)</td>
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

<p>This function will search through all previously loaded dynamic libraries for the symbol <span class="doxyComputerOutput">symbolName</span>.</p>


<p>If it is found, the address of that symbol is returned. If not, null is returned. Note that this will search permanently loaded libraries (<a href="#a5fe607fc919d5fcd00bdfded75f46643">getPermanentLibrary()</a>) as well as explicitly registered symbols (<a href="#a2f997f2beb9cf206cd215663be3b9617">AddSymbol()</a>).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Exceptions</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">std::string</td>
<td class="doxyParamItemDescription"><p>on error. Search through libraries for address of a symbol</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dynamiclibrary-h">DynamicLibrary.h</a>, definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae640baa7177b5de5f1726f808db2d813">llvm::SearchForAddressOfSpecialSymbol</a> and <a href="#a796ad78100654a505c1803a39208fb5d">SearchOrder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#afcef52f821fbc5ad3e5539e5ae80b66e">llvm::__deregister_frame</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ac90cfcdb0c2a25c0969106ebff1be9f8">llvm::Interpreter::callExternalFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#aca88a09e03611e624c1b6ac0aad41ce3">llvm::ExecutionEngine::emitGlobals</a>, <a href="/web-llvm/docs/api/classes/llvm/rtdyldmemorymanager/#a5fee247bdc0c5af393b66bfd73a0a347">llvm::RTDyldMemoryManager::getSymbolAddressInProcess</a>, <a href="/web-llvm/docs/api/groups/llvmccore/#ga9361c91b1806a646e7c019ee82f927f2">LLVMSearchForAddressOfSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp/#a290f71a162bc8e8fd0bc72b222c029fc">lookupFunction</a> and <a href="#a5d4956a5c03696b5bb8230f61deb8061">SearchForAddressOfSymbol</a>.</p>

</div>
</div>

### SearchForAddressOfSymbol() {#a5d4956a5c03696b5bb8230f61deb8061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::sys::DynamicLibrary::SearchForAddressOfSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; symbolName)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convenience function for C++ophiles.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dynamiclibrary-h">DynamicLibrary.h</a>.</p>


<p>Reference <a href="#ae003d16a33e81b88943d3e3aa179fcc4">SearchForAddressOfSymbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### SearchOrder {#a796ad78100654a505c1803a39208fb5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DynamicLibrary::SearchOrdering DynamicLibrary::SearchOrder</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    <a href="#a5e198e8003db7c5e9f35ee98a5897e59a8e2b356d38ac9fe1f4a792153d6049a0">DynamicLibrary::SO_Linker</a>
</div>
</dd>
</dl>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dynamiclibrary-h">DynamicLibrary.h</a>.</p>


<p>Referenced by <a href="#ae003d16a33e81b88943d3e3aa179fcc4">SearchForAddressOfSymbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### Invalid {#a9b07f244d11dea80d03128cbadaa1cd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char DynamicLibrary::Invalid</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dynamiclibrary-h">DynamicLibrary.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dynamiclibrary-h">DynamicLibrary.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/dynamiclibrary-cpp">DynamicLibrary.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
