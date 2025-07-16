---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/irsymbolmapper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `IRSymbolMapper` Class Reference

<p>Maps IR global values to their linker symbol names / flags. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::IRSymbolMapper { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/mangling-h">llvm/ExecutionEngine/Orc/Mangling.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80bcbfaeb3f9c379c94c969f84623c18">SymbolNameToDefinitionMap</a> = std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49258c0e5a9200b48bd7122eea077796">add</a> (ExecutionSession &amp;ES, const ManglingOptions &amp;MO, ArrayRef&lt; GlobalValue * &gt; GVs, SymbolFlagsMap &amp;SymbolFlags, SymbolNameToDefinitionMap *SymbolToDefinition=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add mangled symbols for the given GlobalValues to SymbolFlags. <a href="#a49258c0e5a9200b48bd7122eea077796">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Maps IR global values to their linker symbol names / flags.</p>


<p>This utility can be used when adding new IR globals in the JIT.</p>


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/mangling-h">Mangling.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### SymbolNameToDefinitionMap {#a80bcbfaeb3f9c379c94c969f84623c18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::IRSymbolMapper::SymbolNameToDefinitionMap =  std::map&lt;SymbolStringPtr, GlobalValue *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/mangling-h">Mangling.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### add() {#a49258c0e5a9200b48bd7122eea077796}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::IRSymbolMapper::add (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/irsymbolmapper/manglingoptions">ManglingOptions</a> &amp; MO, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt; GVs, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#afd6431981e7fdfd4b5d2794f04d7d913">SymbolFlagsMap</a> &amp; SymbolFlags, <a href="#a80bcbfaeb3f9c379c94c969f84623c18">SymbolNameToDefinitionMap</a> * SymbolToDefinition=nullptr)</td>
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

<p>Add mangled symbols for the given GlobalValues to SymbolFlags.</p>


<p>If a SymbolToDefinitionMap pointer is supplied then it will be populated with Name-to-GlobalValue* mappings. Note that this mapping is not necessarily one-to-one: thread-local GlobalValues, for example, may produce more than one symbol, in which case the map will contain duplicate values.</p>


<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/mangling-h">Mangling.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/mangling-cpp">Mangling.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/irsymbolmapper/manglingoptions/#a4d4da595dfbf867a4cab51af1b4c6255">llvm::orc::IRSymbolMapper::ManglingOptions::EmulatedTLS</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#aa66476422470ab204074b3198bcf4d15">llvm::JITSymbolFlags::fromGlobalValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/mangling-h">Mangling.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/mangling-cpp">Mangling.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
