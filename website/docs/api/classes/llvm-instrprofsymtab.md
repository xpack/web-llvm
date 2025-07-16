---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/instrprofsymtab
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InstrProfSymtab` Class Reference

<p>A symbol table used for function [IR]PGO name look-up with keys (such as pointers, md5hash values) to the function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::InstrProfSymtab { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">llvm/ProfileData/InstrProf.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73f97a26627fe3fe742d2103c7ce13e9">AddrHashMap</a> = std::vector&lt; std::pair&lt; uint64_t, uint64_t &gt; &gt;</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7039960b2242d9fd985c9a0a811ce53d">AddrIntervalMap</a> = <a href="/web-llvm/docs/api/classes/llvm/intervalmap">IntervalMap</a>&lt; uint64_t, uint64_t, 4, <a href="/web-llvm/docs/api/structs/llvm/intervalmaphalfopeninfo">IntervalMapHalfOpenInfo</a>&lt; uint64_t &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4d9ed5dd3f88588ef0df3c89be58423">InstrProfSymtab</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4645b1c6911c38d3e8e9b9b67b9f89b">InstrProfSymtab</a> (const InstrProfSymtab &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af073975a777bb7b2647d1e0139695fb3">InstrProfSymtab</a> (InstrProfSymtab &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade967f0bd3c4b8f2c7b1a98f031a92da">operator=</a> (const InstrProfSymtab &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50aaca1df7226bbe16f7c9f61e48355b">operator=</a> (InstrProfSymtab &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4f8c9517d7d182974ce657311440a6b">create</a> (object::SectionRef &amp;Section)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> from an object file section which contains function PGO names. <a href="#aa4f8c9517d7d182974ce657311440a6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07b1b3d62dd8354884a452ca2fcc7928">create</a> (StringRef NameStrings)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">NameStrings</span> is a string composed of one of more sub-strings encoded in the format described in <span class="doxyComputerOutput">collectPGOFuncNameStrings</span>. <a href="#a07b1b3d62dd8354884a452ca2fcc7928">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b001e37b2b66b4c68912ecfd0ce1222">create</a> (StringRef FuncNameStrings, StringRef VTableNameStrings)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize symtab states with function names and vtable names. <a href="#a0b001e37b2b66b4c68912ecfd0ce1222">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac66b15dbe401ba9b85985d386c1a30b6">initVTableNamesFromCompressedStrings</a> (StringRef CompressedVTableNames)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize 'this' with the set of vtable names encoded in <span class="doxyComputerOutput">CompressedVTableNames</span>. <a href="#ac66b15dbe401ba9b85985d386c1a30b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a257438a6abdc8699555b7385b354922a">create</a> (StringRef D, uint64_t BaseAddr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This interface is used by reader of CoverageMapping test format. <a href="#a257438a6abdc8699555b7385b354922a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d8ea668d32a807e0313e35e6c564a5d">create</a> (Module &amp;M, bool InLTO=false, bool AddCanonical=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A wrapper interface to populate the PGO symtab with functions decls from module <span class="doxyComputerOutput">M</span>. <a href="#a9d8ea668d32a807e0313e35e6c564a5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NameIterRange&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4e1b4f3ad8f68eee1a8bd258ca6487aa">create</a> (const NameIterRange &amp;IterRange)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> from a set of names iteratable from <span class="doxyComputerOutput">IterRange</span>. <a href="#a4e1b4f3ad8f68eee1a8bd258ca6487aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FuncNameIterRange, typename VTableNameIterRange&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a46c4a2e0de8a1253010e2a0221f4814a">create</a> (const FuncNameIterRange &amp;FuncIterRange, const VTableNameIterRange &amp;VTableIterRange)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> from a set of function names and vtable names iteratable from <span class="doxyComputerOutput">IterRange</span>. <a href="#a46c4a2e0de8a1253010e2a0221f4814a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a161861cead69eb257424d8e90d9bf26d">addSymbolName</a> (StringRef SymbolName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab6da5958ec329a4ea11683d414e8366">addFuncName</a> (StringRef FuncName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The method name is kept since there are many callers. <a href="#aab6da5958ec329a4ea11683d414e8366">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e42074180a160835f3222c6d6017fc1">addVTableName</a> (StringRef VTableName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds VTableName as a known symbol, and inserts it to a map that tracks all vtable names. <a href="#a6e42074180a160835f3222c6d6017fc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac86aeb12fe870a103a351a108f0f5f75">getVTableNames</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dd108dadd266afe80d3d7c50ae3df5c">mapAddress</a> (uint64_t Addr, uint64_t MD5Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a function address to its name's <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> hash. <a href="#a6dd108dadd266afe80d3d7c50ae3df5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac023ab7d81083691a2e68508914c0e8">mapVTableAddress</a> (uint64_t StartAddr, uint64_t EndAddr, uint64_t MD5Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map the address range (i.e., [start_address, end_address)) of a variable to its names' <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> hash. <a href="#aac023ab7d81083691a2e68508914c0e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a149be06917128912dc2f9ee4f9adebdc">getFunctionHashFromAddress</a> (uint64_t Address)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a function's hash, or 0, if the function isn't in this SymTab. <a href="#a149be06917128912dc2f9ee4f9adebdc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28d09bfda673a2e6a713cff18ae5c34e">getVTableHashFromAddress</a> (uint64_t Address)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a vtable's hash, or 0 if the vtable doesn't exist in this SymTab. <a href="#a28d09bfda673a2e6a713cff18ae5c34e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad23192fa27a46e12f4a8165466b72c5f">getFuncName</a> (uint64_t FuncNameAddress, size_t NameSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return function's PGO name from the function name's symbol address in the object file. <a href="#ad23192fa27a46e12f4a8165466b72c5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4368b520bb5883d23d6c2c59bf129b5a">getFuncOrVarName</a> (uint64_t ValMD5Hash)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return name of functions or global variables from the name's md5 hash value. <a href="#a4368b520bb5883d23d6c2c59bf129b5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7fa5af32e8d5c5142f7a39ae905681b">getFuncOrVarNameIfDefined</a> (uint64_t ValMD5Hash)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Just like getFuncOrVarName, except that it will return literal string 'External Symbol' if the function or global variable is external to this symbol table. <a href="#af7fa5af32e8d5c5142f7a39ae905681b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e9990bcce5681d3af7644defc380eda">getFunction</a> (uint64_t FuncMD5Hash)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return function from the name's md5 hash. Return nullptr if not found. <a href="#a8e9990bcce5681d3af7644defc380eda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26076577560fe95a690aa07783d9c59c">getGlobalVariable</a> (uint64_t MD5Hash)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the global variable corresponding to md5 hash. <a href="#a26076577560fe95a690aa07783d9c59c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9896bf8d3b772b6a64d85541f1ebd0e3">getNameData</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the name section data. <a href="#a9896bf8d3b772b6a64d85541f1ebd0e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7514f424ff0cceffc668a7ceaa728104">dumpNames</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the symbols in this table. <a href="#a7514f424ff0cceffc668a7ceaa728104">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67a5f2aa878dadabe6090a5c9ea12664">addFuncWithName</a> (Function &amp;F, StringRef PGOFuncName, bool AddCanonical)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af55408d1b2ecdb51489bf199a86976a0">addVTableWithName</a> (GlobalVariable &amp;V, StringRef PGOVTableName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7436a3dde08bcba62eca148fa4fe148b">finalizeSymtab</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff4d9d18969a8acd422aaf3735078a4f">Data</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae56aeb37d2bae9861ee75a151a899ff4">Address</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3811568d54e499d912aecbd5efda9f7">NameTab</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ba7015ff4ed0cd7b1849af75117c247">VTableNames</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb2e16d617e4aeb43e7fe6d887997845">MD5NameMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab205fa5b8017eaaa659d63788f1b1042">MD5FuncMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb56701125a6bf0bd4109980011914bb">MD5VTableMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a73f97a26627fe3fe742d2103c7ce13e9">AddrHashMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04c74dba8e510aeb7a2d77fbfbdb7c41">AddrToMD5Map</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap/#a6b645fcc5ae44b9a8e2fef275890ae4b">AddrIntervalMap::Allocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf50118a259a7f593ce46dd7e65f5dc4">VTableAddrMapAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap">AddrIntervalMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9899f369a9807b78a04852615617683">VTableAddrMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9f71dd50f13466596a4046b30a6035a">Sorted</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a5f19e33dda9a2ad1f49191df00aacf">isExternalSymbol</a> (const StringRef &amp;Symbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if Symbol is the value used to represent external symbols. <a href="#a0a5f19e33dda9a2ad1f49191df00aacf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0623f701e5823261dc09f9a57d4f8cbf">getExternalSymbol</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0917ccf8007838284e52708eb51d3121">getCanonicalName</a> (StringRef PGOName)</td>
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

<p>A symbol table used for function [IR]PGO name look-up with keys (such as pointers, md5hash values) to the function.</p>


<p>A function's [IR]PGO name or name's md5hash are used in retrieving the profile data of the function. See <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a1b3e6af13e7130b5bd9994948ec48ccd">getIRPGOFuncName()</a></span> and <span class="doxyComputerOutput">getPGOFuncName</span> methods for details how [IR]PGO name is formed.</p>


<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### AddrHashMap {#a73f97a26627fe3fe742d2103c7ce13e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InstrProfSymtab::AddrHashMap =  std::vector&lt;std::pair&lt;uint64_t, uint64_t&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### AddrIntervalMap {#a7039960b2242d9fd985c9a0a811ce53d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InstrProfSymtab::AddrIntervalMap = 
      IntervalMap&lt;uint64_t, uint64_t, 4, IntervalMapHalfOpenInfo&lt;uint64_t&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InstrProfSymtab() {#ab4d9ed5dd3f88588ef0df3c89be58423}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrProfSymtab::InstrProfSymtab ()</td>
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



<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#af4645b1c6911c38d3e8e9b9b67b9f89b">InstrProfSymtab</a>, <a href="#af073975a777bb7b2647d1e0139695fb3">InstrProfSymtab</a>, <a href="#ade967f0bd3c4b8f2c7b1a98f031a92da">operator=</a> and <a href="#a50aaca1df7226bbe16f7c9f61e48355b">operator=</a>.</p>

</div>
</div>

### InstrProfSymtab() {#af4645b1c6911c38d3e8e9b9b67b9f89b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrProfSymtab::InstrProfSymtab (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> &amp;)</td>
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



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Reference <a href="#ab4d9ed5dd3f88588ef0df3c89be58423">InstrProfSymtab</a>.</p>

</div>
</div>

### InstrProfSymtab() {#af073975a777bb7b2647d1e0139695fb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrProfSymtab::InstrProfSymtab (<a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> &amp;&amp;)</td>
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



<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Reference <a href="#ab4d9ed5dd3f88588ef0df3c89be58423">InstrProfSymtab</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ade967f0bd3c4b8f2c7b1a98f031a92da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfSymtab &amp; llvm::InstrProfSymtab::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> &amp;)</td>
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



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Reference <a href="#ab4d9ed5dd3f88588ef0df3c89be58423">InstrProfSymtab</a>.</p>

</div>
</div>

### operator=() {#a50aaca1df7226bbe16f7c9f61e48355b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfSymtab &amp; llvm::InstrProfSymtab::operator= (<a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> &amp;&amp;)</td>
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



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Reference <a href="#ab4d9ed5dd3f88588ef0df3c89be58423">InstrProfSymtab</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addFuncName() {#aab6da5958ec329a4ea11683d414e8366}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::InstrProfSymtab::addFuncName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncName)</td>
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

<p>The method name is kept since there are many callers.</p>


<p>It just forwards to 'addSymbolName'.</p>


<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Reference <a href="#a161861cead69eb257424d8e90d9bf26d">addSymbolName</a>.</p>


<p>Referenced by <a href="#a46c4a2e0de8a1253010e2a0221f4814a">create</a>, <a href="#a4e1b4f3ad8f68eee1a8bd258ca6487aa">create</a>, <a href="#a0b001e37b2b66b4c68912ecfd0ce1222">create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939047c06de84c6a45e40012255c2aa6">llvm::getValueProfRecordValueData</a> and <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#a2a76e869a218e271ec68f8a68968fde2">llvm::InstrProfWriter::writeText</a>.</p>

</div>
</div>

### addSymbolName() {#a161861cead69eb257424d8e90d9bf26d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::InstrProfSymtab::addSymbolName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SymbolName)</td>
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



<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/indexedinstrprof/#a26647986f25d6168afc4204fd79873df">llvm::IndexedInstrProf::ComputeHash</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086a7596fdd04dba990373ab2f3da0c7dd3f">llvm::malformed</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#aab6da5958ec329a4ea11683d414e8366">addFuncName</a> and <a href="#a6e42074180a160835f3222c6d6017fc1">addVTableName</a>.</p>

</div>
</div>

### addVTableName() {#a6e42074180a160835f3222c6d6017fc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::InstrProfSymtab::addVTableName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> VTableName)</td>
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

<p>Adds VTableName as a known symbol, and inserts it to a map that tracks all vtable names.</p>

<p>Definition at line 605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="#a161861cead69eb257424d8e90d9bf26d">addSymbolName</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a46c4a2e0de8a1253010e2a0221f4814a">create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd64959f7986bb6761c2445a90f020d3">llvm::getValueProfRecordNumValueData</a>, <a href="#ac66b15dbe401ba9b85985d386c1a30b6">initVTableNamesFromCompressedStrings</a> and <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#a2a76e869a218e271ec68f8a68968fde2">llvm::InstrProfWriter::writeText</a>.</p>

</div>
</div>

### create() {#aa4f8c9517d7d182974ce657311440a6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error InstrProfSymtab::create (<a href="/web-llvm/docs/api/classes/llvm/object/sectionref">object::SectionRef</a> &amp; Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> from an object file section which contains function PGO names.</p>


<p>When section may contain raw string data or string data in compressed form. This method only initialize the symtab with reference to the data and the section base address. The decompression will be delayed until before it is used. See also <span class="doxyComputerOutput"><a href="#a07b1b3d62dd8354884a452ca2fcc7928">create(StringRef)</a></span> method.</p>


<p>Declaration at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp/#a98355bc7c5d0793f5950328a4d4e6a9b">shouldSkipSectionFirstByte</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderindex/#a1b1487936be38ff8caf0cbf72ba45f2a">llvm::InstrProfReaderIndex&lt; HashTableImpl &gt;::populateSymtab</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp/#a42ff11c63c1a675d13cc97eaec48d621">promoteIndirectCalls</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/cgprofile-cpp/#a804d6eb117c9b69c6b52f2655438e787">runCGProfilePass</a>.</p>

</div>
</div>

### create() {#a07b1b3d62dd8354884a452ca2fcc7928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::InstrProfSymtab::create (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> NameStrings)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><span class="doxyComputerOutput">NameStrings</span> is a string composed of one of more sub-strings encoded in the format described in <span class="doxyComputerOutput">collectPGOFuncNameStrings</span>.</p>


<p>This method is a wrapper to <span class="doxyComputerOutput">readAndDecodeStrings</span> method.</p>


<p>Declaration at line 546 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ad73613c8e8495c4d7e3aaf2da575f2e2">llvm::readAndDecodeStrings</a>.</p>

</div>
</div>

### create() {#a0b001e37b2b66b4c68912ecfd0ce1222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::InstrProfSymtab::create (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncNameStrings, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> VTableNameStrings)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize symtab states with function names and vtable names.</p>


<p><span class="doxyComputerOutput">FuncNameStrings</span> is a string composed of one or more encoded function name strings, and <span class="doxyComputerOutput">VTableNameStrings</span> composes of one or more encoded vtable names. This interface is solely used by raw profile reader.</p>


<p>Declaration at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 588 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>


<p>References <a href="#aab6da5958ec329a4ea11683d414e8366">addFuncName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad73613c8e8495c4d7e3aaf2da575f2e2">llvm::readAndDecodeStrings</a>.</p>

</div>
</div>

### create() {#a257438a6abdc8699555b7385b354922a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::InstrProfSymtab::create (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> D, uint64_t BaseAddr)</td>
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

<p>This interface is used by reader of CoverageMapping test format.</p>

<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### create() {#a9d8ea668d32a807e0313e35e6c564a5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::InstrProfSymtab::create (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, bool InLTO=false, bool AddCanonical=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A wrapper interface to populate the PGO symtab with functions decls from module <span class="doxyComputerOutput">M</span>.</p>


<p>This interface is used by transformation passes such as indirect function call promotion. Variable <span class="doxyComputerOutput">InLTO</span> indicates if this is called from LTO optimization passes. A canonical name, removing non-__uniq suffixes, is added if <span class="doxyComputerOutput">AddCanonical</span> is true.</p>


<p>Declaration at line 568 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1b3e6af13e7130b5bd9994948ec48ccd">llvm::getIRPGOFuncName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a133c5cb70e0ea68fc5e503b7a7732390">llvm::getPGOFuncName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a60f2adf97ae1dde0bc158fbf5a020dad">llvm::getPGOName</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### create() {#a4e1b4f3ad8f68eee1a8bd258ca6487aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NameIterRange&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::InstrProfSymtab::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NameIterRange &amp; IterRange)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> from a set of names iteratable from <span class="doxyComputerOutput">IterRange</span>.</p>


<p>This interface is used by IndexedProfReader.</p>


<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="#aab6da5958ec329a4ea11683d414e8366">addFuncName</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### create() {#a46c4a2e0de8a1253010e2a0221f4814a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FuncNameIterRange, typename VTableNameIterRange&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::InstrProfSymtab::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncNameIterRange &amp; FuncIterRange, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VTableNameIterRange &amp; VTableIterRange)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> from a set of function names and vtable names iteratable from <span class="doxyComputerOutput">IterRange</span>.</p>


<p>This interface is used by IndexedProfReader.</p>


<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="#aab6da5958ec329a4ea11683d414e8366">addFuncName</a>, <a href="#a6e42074180a160835f3222c6d6017fc1">addVTableName</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### dumpNames() {#a7514f424ff0cceffc668a7ceaa728104}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfSymtab::dumpNames (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the symbols in this table.</p>

<p>Declaration at line 666 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 674 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>

</div>
</div>

### getFuncName() {#ad23192fa27a46e12f4a8165466b72c5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef InstrProfSymtab::getFuncName (uint64_t FuncNameAddress, size_t NameSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return function's PGO name from the function name's symbol address in the object file.</p>


<p>If an error occurs, return an empty string.</p>


<p>Declaration at line 639 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### getFuncOrVarName() {#a4368b520bb5883d23d6c2c59bf129b5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::InstrProfSymtab::getFuncOrVarName (uint64_t ValMD5Hash)</td>
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

<p>Return name of functions or global variables from the name's md5 hash value.</p>


<p>If not found, return an empty string.</p>


<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a8e89e6935aaf48cde9d60fd12a3dae0f">llvm::sampleprof::MD5Hash</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/coverage/accessors/#ab6161a32808a77777e006ca358dac0b2">llvm::coverage::accessors::getFuncNameViaRef</a>, <a href="#af7fa5af32e8d5c5142f7a39ae905681b">getFuncOrVarNameIfDefined</a> and <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#ab803c3548558a7dd296a3b2be2ef9773">llvm::InstrProfWriter::writeTextTemporalProfTraceData</a>.</p>

</div>
</div>

### getFuncOrVarNameIfDefined() {#af7fa5af32e8d5c5142f7a39ae905681b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::InstrProfSymtab::getFuncOrVarNameIfDefined (uint64_t ValMD5Hash)</td>
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

<p>Just like getFuncOrVarName, except that it will return literal string 'External Symbol' if the function or global variable is external to this symbol table.</p>

<p>Definition at line 648 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="#a4368b520bb5883d23d6c2c59bf129b5a">getFuncOrVarName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a8e89e6935aaf48cde9d60fd12a3dae0f">llvm::sampleprof::MD5Hash</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#a764569b7bb113502ca90fca3c07fa816">llvm::InstrProfWriter::writeRecordInText</a>.</p>

</div>
</div>

### getFunction() {#a8e9990bcce5681d3af7644defc380eda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::InstrProfSymtab::getFunction (uint64_t FuncMD5Hash)</td>
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

<p>Return function from the name's md5 hash. Return nullptr if not found.</p>

<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/cgprofile-cpp/#a804d6eb117c9b69c6b52f2655438e787">runCGProfilePass</a>.</p>

</div>
</div>

### getFunctionHashFromAddress() {#a149be06917128912dc2f9ee4f9adebdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::InstrProfSymtab::getFunctionHashFromAddress (uint64_t Address)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a function's hash, or 0, if the function isn't in this SymTab.</p>

<p>Declaration at line 631 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a327a399b9f6ef414a29ddeffba934d26">llvm::partition_point</a>.</p>

</div>
</div>

### getGlobalVariable() {#a26076577560fe95a690aa07783d9c59c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * llvm::InstrProfSymtab::getGlobalVariable (uint64_t MD5Hash)</td>
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

<p>Return the global variable corresponding to md5 hash.</p>


<p>Return nullptr if not found.</p>


<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a8e89e6935aaf48cde9d60fd12a3dae0f">llvm::sampleprof::MD5Hash</a>.</p>

</div>
</div>

### getNameData() {#a9896bf8d3b772b6a64d85541f1ebd0e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::InstrProfSymtab::getNameData ()</td>
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

<p>Return the name section data.</p>

<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### getVTableHashFromAddress() {#a28d09bfda673a2e6a713cff18ae5c34e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::InstrProfSymtab::getVTableHashFromAddress (uint64_t Address)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a vtable's hash, or 0 if the vtable doesn't exist in this SymTab.</p>

<p>Declaration at line 634 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 654 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>

</div>
</div>

### getVTableNames() {#ac86aeb12fe870a103a351a108f0f5f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StringSet &amp; llvm::InstrProfSymtab::getVTableNames ()</td>
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



<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### initVTableNamesFromCompressedStrings() {#ac66b15dbe401ba9b85985d386c1a30b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::InstrProfSymtab::initVTableNamesFromCompressedStrings (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CompressedVTableNames)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize 'this' with the set of vtable names encoded in <span class="doxyComputerOutput">CompressedVTableNames</span>.</p>

<p>Declaration at line 556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>


<p>References <a href="#a6e42074180a160835f3222c6d6017fc1">addVTableName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad73613c8e8495c4d7e3aaf2da575f2e2">llvm::readAndDecodeStrings</a>.</p>

</div>
</div>

### mapAddress() {#a6dd108dadd266afe80d3d7c50ae3df5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfSymtab::mapAddress (uint64_t Addr, uint64_t MD5Val)</td>
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

<p>Map a function address to its name's <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> hash.</p>


<p>This interface is only used by the raw profiler reader.</p>


<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### mapVTableAddress() {#aac023ab7d81083691a2e68508914c0e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfSymtab::mapVTableAddress (uint64_t StartAddr, uint64_t EndAddr, uint64_t MD5Val)</td>
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

<p>Map the address range (i.e., [start_address, end_address)) of a variable to its names' <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> hash.</p>


<p>This interface is only used by the raw profile reader.</p>


<p>Definition at line 626 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addFuncWithName() {#a67a5f2aa878dadabe6090a5c9ea12664}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::InstrProfSymtab::addFuncWithName (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PGOFuncName, bool AddCanonical)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 633 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>

</div>
</div>

### addVTableWithName() {#af55408d1b2ecdb51489bf199a86976a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::InstrProfSymtab::addVTableWithName (<a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &amp; V, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PGOVTableName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>

</div>
</div>

### finalizeSymtab() {#a7436a3dde08bcba62eca148fa4fe148b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfSymtab::finalizeSymtab ()</td>
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



<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Address {#ae56aeb37d2bae9861ee75a151a899ff4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::InstrProfSymtab::Address = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### AddrToMD5Map {#a04c74dba8e510aeb7a2d77fbfbdb7c41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddrHashMap llvm::InstrProfSymtab::AddrToMD5Map</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### Data {#aff4d9d18969a8acd422aaf3735078a4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::InstrProfSymtab::Data</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### MD5FuncMap {#ab205fa5b8017eaaa659d63788f1b1042}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::pair&lt;uint64_t, Function *&gt; &gt; llvm::InstrProfSymtab::MD5FuncMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### MD5NameMap {#afb2e16d617e4aeb43e7fe6d887997845}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::pair&lt;uint64_t, StringRef&gt; &gt; llvm::InstrProfSymtab::MD5NameMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### MD5VTableMap {#acb56701125a6bf0bd4109980011914bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;uint64_t, GlobalVariable *&gt; llvm::InstrProfSymtab::MD5VTableMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### NameTab {#ac3811568d54e499d912aecbd5efda9f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSet llvm::InstrProfSymtab::NameTab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### Sorted {#ab9f71dd50f13466596a4046b30a6035a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstrProfSymtab::Sorted = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### VTableAddrMap {#ad9899f369a9807b78a04852615617683}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddrIntervalMap llvm::InstrProfSymtab::VTableAddrMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### VTableAddrMapAllocator {#adf50118a259a7f593ce46dd7e65f5dc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddrIntervalMap::Allocator llvm::InstrProfSymtab::VTableAddrMapAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

### VTableNames {#a5ba7015ff4ed0cd7b1849af75117c247}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSet llvm::InstrProfSymtab::VTableNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isExternalSymbol() {#a0a5f19e33dda9a2ad1f49191df00aacf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstrProfSymtab::isExternalSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Symbol)</td>
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

<p>True if Symbol is the value used to represent external symbols.</p>

<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getCanonicalName() {#a0917ccf8007838284e52708eb51d3121}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::InstrProfSymtab::getCanonicalName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PGOName)</td>
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



<p>Declaration at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 607 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>

</div>
</div>

### getExternalSymbol() {#a0623f701e5823261dc09f9a57d4f8cbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::InstrProfSymtab::getExternalSymbol ()</td>
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



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
