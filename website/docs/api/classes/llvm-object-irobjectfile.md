---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/irobjectfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `IRObjectFile` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::object::IRObjectFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">llvm/Object/IRObjectFile.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile">SymbolicFile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d920fca798b8768e2a6ebbb631d6cc4">module_iterator</a> = <a href="/web-llvm/docs/api/structs/llvm/pointee-iterator">pointee_iterator</a>&lt; std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; &gt;::const_iterator, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt;</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22e88bbe808114eb0d13956d994e6540">IRObjectFile</a> (MemoryBufferRef Object, std::vector&lt; std::unique_ptr&lt; Module &gt; &gt; Mods)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad047da8377319bb842a7f8c599cf3500">~IRObjectFile</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fc5bfd0e7eff579588296220dcdf230">moveSymbolNext</a> (DataRefImpl &amp;Symb) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2584de961c69042c7afb892ad5f76b1a">printSymbolName</a> (raw_ostream &amp;OS, DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a137560af83faf7a336b0684c627227a1">getSymbolFlags</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a5bf1bfacdebc64c1f70e3b2861ba76eb">basic_symbol_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ea6749cdcd6c8b985d67441ab66180c">symbol_begin</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a5bf1bfacdebc64c1f70e3b2861ba76eb">basic_symbol_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90838b84033f2f9576def8909bac94b7">symbol_end</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b78a9dc71e54e2032c3578f48910a76">is64Bit</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a318fb3fff5cdd380b99d7dde9d1e8513">getTargetTriple</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a4d920fca798b8768e2a6ebbb631d6cc4">module_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa59b8320d00fa5327970a22a137efbb6">module_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a4d920fca798b8768e2a6ebbb631d6cc4">module_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88a43d0cbe0e955b941970b15f5b9d25">module_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a4d920fca798b8768e2a6ebbb631d6cc4">module_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca911e45ef08a3f6c38d144f825c5222">modules</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4c0987f7477fdf2eb6bff86920267d4">Mods</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/modulesymboltable">ModuleSymbolTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a524d70bd1d8b755a3ef55e70e8684f68">SymTab</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6bc8c2b2a50fecd8a066e191f0cace3">classof</a> (const Binary *v)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a803ed79cb2444088841a8c8618b21ab8">findBitcodeInObject</a> (const ObjectFile &amp;Obj)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finds and returns bitcode embedded in the given object file, or an error code if not found. <a href="#a803ed79cb2444088841a8c8618b21ab8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaceb8997142b34e42f329adfba36658">findBitcodeInMemBuffer</a> (MemoryBufferRef Object)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finds and returns bitcode in the given memory buffer (which may be either a bitcode file or a native object file with embedded bitcode), or an error code if not found. <a href="#aeaceb8997142b34e42f329adfba36658">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/irobjectfile">IRObjectFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcce1b766f055cfac90081cebb14ad23">create</a> (MemoryBufferRef Object, LLVMContext &amp;Context)</td>
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


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">IRObjectFile.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### module\_iterator {#a4d920fca798b8768e2a6ebbb631d6cc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::object::IRObjectFile::module_iterator = 
      pointee_iterator&lt;std::vector&lt;std::unique_ptr&lt;Module&gt;&gt;::const_iterator,
                       const Module&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">IRObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### IRObjectFile() {#a22e88bbe808114eb0d13956d994e6540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRObjectFile::IRObjectFile (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object, std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; &gt; Mods)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">IRObjectFile.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irobjectfile-cpp">IRObjectFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~IRObjectFile() {#ad047da8377319bb842a7f8c599cf3500}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRObjectFile::~IRObjectFile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">IRObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getSymbolFlags() {#a137560af83faf7a336b0684c627227a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint32_t &gt; IRObjectFile::getSymbolFlags (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">IRObjectFile.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irobjectfile-cpp">IRObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/object/irobjectfile-cpp/#a133ac9782d26c2803a17b87d1ddb7095">getSym</a>.</p>

</div>
</div>

### getTargetTriple() {#a318fb3fff5cdd380b99d7dde9d1e8513}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef IRObjectFile::getTargetTriple ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">IRObjectFile.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irobjectfile-cpp">IRObjectFile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/slice/#abc9b876b08cdf5b2ec2c2bb13fbf4f65">llvm::object::Slice::create</a> and <a href="#a2b78a9dc71e54e2032c3578f48910a76">is64Bit</a>.</p>

</div>
</div>

### is64Bit() {#a2b78a9dc71e54e2032c3578f48910a76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::IRObjectFile::is64Bit ()</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">IRObjectFile.h</a>.</p>


<p>References <a href="#a318fb3fff5cdd380b99d7dde9d1e8513">getTargetTriple</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a9e0d7431e635bbbf753602d214d89f0e">llvm::Triple::isArch64Bit</a>.</p>

</div>
</div>

### module\_begin() {#aa59b8320d00fa5327970a22a137efbb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">module_iterator llvm::object::IRObjectFile::module_begin ()</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">IRObjectFile.h</a>.</p>


<p>Referenced by <a href="#aca911e45ef08a3f6c38d144f825c5222">modules</a>.</p>

</div>
</div>

### module\_end() {#a88a43d0cbe0e955b941970b15f5b9d25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">module_iterator llvm::object::IRObjectFile::module_end ()</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">IRObjectFile.h</a>.</p>


<p>Referenced by <a href="#aca911e45ef08a3f6c38d144f825c5222">modules</a>.</p>

</div>
</div>

### modules() {#aca911e45ef08a3f6c38d144f825c5222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; module_iterator &gt; llvm::object::IRObjectFile::modules ()</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">IRObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#aa59b8320d00fa5327970a22a137efbb6">module_begin</a> and <a href="#a88a43d0cbe0e955b941970b15f5b9d25">module_end</a>.</p>

</div>
</div>

### moveSymbolNext() {#a9fc5bfd0e7eff579588296220dcdf230}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRObjectFile::moveSymbolNext (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Symb)</td>
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



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">IRObjectFile.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irobjectfile-cpp">IRObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>.</p>

</div>
</div>

### printSymbolName() {#a2584de961c69042c7afb892ad5f76b1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error IRObjectFile::printSymbolName (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">IRObjectFile.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irobjectfile-cpp">IRObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/irobjectfile-cpp/#a133ac9782d26c2803a17b87d1ddb7095">getSym</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### symbol\_begin() {#a6ea6749cdcd6c8b985d67441ab66180c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">basic_symbol_iterator IRObjectFile::symbol_begin ()</td>
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



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">IRObjectFile.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irobjectfile-cpp">IRObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>.</p>

</div>
</div>

### symbol\_end() {#a90838b84033f2f9576def8909bac94b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">basic_symbol_iterator IRObjectFile::symbol_end ()</td>
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



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">IRObjectFile.h</a>, definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irobjectfile-cpp">IRObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Mods {#aa4c0987f7477fdf2eb6bff86920267d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;Module&gt; &gt; llvm::object::IRObjectFile::Mods</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">IRObjectFile.h</a>.</p>

</div>
</div>

### SymTab {#a524d70bd1d8b755a3ef55e70e8684f68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleSymbolTable llvm::object::IRObjectFile::SymTab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">IRObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#aa6bc8c2b2a50fecd8a066e191f0cace3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::IRObjectFile::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/binary">Binary</a> * v)</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">IRObjectFile.h</a>.</p>

</div>
</div>

### create() {#afcce1b766f055cfac90081cebb14ad23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; IRObjectFile &gt; &gt; IRObjectFile::create (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context)</td>
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



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">IRObjectFile.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irobjectfile-cpp">IRObjectFile.cpp</a>.</p>


<p>References <a href="#aeaceb8997142b34e42f329adfba36658">findBitcodeInMemBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84ff19acc1b6cba55e1006e5be8e6453">llvm::getBitcodeModuleList</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#a4ee418c47f5baa9b4b570371fc9630ce">llvm::object::SymbolicFile::createSymbolicFile</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machouniversalbinary/objectforarch/#ae5f1caff8db19eaa70746ee93fe04b6f">llvm::object::MachOUniversalBinary::ObjectForArch::getAsIRObject</a>.</p>

</div>
</div>

### findBitcodeInMemBuffer() {#aeaceb8997142b34e42f329adfba36658}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; MemoryBufferRef &gt; IRObjectFile::findBitcodeInMemBuffer (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object)</td>
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

<p>Finds and returns bitcode in the given memory buffer (which may be either a bitcode file or a native object file with embedded bitcode), or an error code if not found.</p>

<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">IRObjectFile.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irobjectfile-cpp">IRObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa9b217cf59bac16d57cf52c3e76f3ce50">llvm::file_magic::bitcode</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aac575f4e16f05741d7656211f860dfcc3">llvm::file_magic::coff_object</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a926af6aca697fdbacb3e3ea1000f0ec4">llvm::object::ObjectFile::createObjectFile</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa1b167178973059ff5b3a4b2bf2377450">llvm::file_magic::elf_relocatable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="#a803ed79cb2444088841a8c8618b21ab8">findBitcodeInObject</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a00941e59a16ad6eb14e905557a612501">llvm::identify_magic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20ad5a8a27f4e310ea593b285615faaca35">llvm::object::invalid_file_type</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aac557d5088dac1a5cca0c2c7e78174632">llvm::file_magic::macho_object</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aaa0dedd1117ef34a81cb4b8751c3c1e4f">llvm::file_magic::wasm_object</a>.</p>


<p>Referenced by <a href="#afcce1b766f055cfac90081cebb14ad23">create</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#a969833caa131b8a26c7b12bf917294a7">llvm::LTOModule::getProducerString</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#a18c6d81a89ce7251370098d5fca14eed">llvm::LTOModule::isBitcodeFile</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#af8c1c55aabd3c2fe773936a5aeec05c8">llvm::LTOModule::isBitcodeFile</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#aa9588be24002d2f7603334d8dd1846e7">llvm::LTOModule::isBitcodeForTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltomodule-cpp/#afc4790b3e3d093c39ef63dbf4f840b8f">parseBitcodeFileImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#a01155893a99bd03c0b13bb52d2f7083e">llvm::object::readIRSymtab</a>.</p>

</div>
</div>

### findBitcodeInObject() {#a803ed79cb2444088841a8c8618b21ab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; MemoryBufferRef &gt; IRObjectFile::findBitcodeInObject (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &amp; Obj)</td>
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

<p>Finds and returns bitcode embedded in the given object file, or an error code if not found.</p>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">IRObjectFile.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/object/irobjectfile-cpp">IRObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20acf4e23aab5a1a4938f1a2cd521acf882">llvm::object::bitcode_section_not_found</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#acecdb20a61e1b407af83d42e1ad9a3f3">llvm::object::Binary::getFileName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a7f73649118e365a230be4870d824e7cf">llvm::object::ObjectFile::sections</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#a4ee418c47f5baa9b4b570371fc9630ce">llvm::object::SymbolicFile::createSymbolicFile</a> and <a href="#aeaceb8997142b34e42f329adfba36658">findBitcodeInMemBuffer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">IRObjectFile.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/irobjectfile-cpp">IRObjectFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
