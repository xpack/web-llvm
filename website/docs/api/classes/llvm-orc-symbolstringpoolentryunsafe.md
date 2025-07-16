---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/symbolstringpoolentryunsafe
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SymbolStringPoolEntryUnsafe` Class Reference

<p>Provides unsafe access to ownership operations on <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::SymbolStringPoolEntryUnsafe { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">llvm/ExecutionEngine/Orc/SymbolStringPool.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2560e4a213ecef84962e41b993856039">PoolEntry</a> = <a href="/web-llvm/docs/api/classes/llvm/stringmapentry">SymbolStringPool::PoolMapEntry</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c9a7215d3cfc523feb0a04f4d1f88ab">SymbolStringPoolEntryUnsafe</a> (PoolEntry *E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2560e4a213ecef84962e41b993856039">PoolEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a908a1e1a1ecbfc6b65ab38c7a8fda227">rawPtr</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ee0876c1646b50c1c484300ab45f8bd">copyToSymbolStringPtr</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> for this entry, with the <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> retaining the entry as usual. <a href="#a2ee0876c1646b50c1c484300ab45f8bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab404390b250a0b4ca46d3a6ec59b65d0">moveToSymbolStringPtr</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> for this entry <em>without</em> performing a retain operation during construction. <a href="#ab404390b250a0b4ca46d3a6ec59b65d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d7ddbbafec6e5fefaeade4e07eefb0b">retain</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49c1e5962abd3bde8c73a4a42e69ca69">release</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2560e4a213ecef84962e41b993856039">PoolEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3492b9e5abaf7b8ae763af031c9f51c8">E</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpoolentryunsafe">SymbolStringPoolEntryUnsafe</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08a5c6e6a4cc582bb37eb471ba039019">from</a> (const SymbolStringPtr &amp;S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an unsafe pool entry ref without changing the ref-count. <a href="#a08a5c6e6a4cc582bb37eb471ba039019">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpoolentryunsafe">SymbolStringPoolEntryUnsafe</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e9c4862b3a45f4e96bd602c519991c5">take</a> (SymbolStringPtr &amp;&amp;S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Consumes the given <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> without releasing the pool entry. <a href="#a9e9c4862b3a45f4e96bd602c519991c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Provides unsafe access to ownership operations on <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a>.</p>


<p>This class can be used to manage <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> instances from C.</p>


<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### PoolEntry {#a2560e4a213ecef84962e41b993856039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::SymbolStringPoolEntryUnsafe::PoolEntry =  SymbolStringPool::PoolMapEntry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SymbolStringPoolEntryUnsafe() {#a6c9a7215d3cfc523feb0a04f4d1f88ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::SymbolStringPoolEntryUnsafe::SymbolStringPoolEntryUnsafe (<a href="#a2560e4a213ecef84962e41b993856039">PoolEntry</a> * E)</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>


<p>Referenced by <a href="#a08a5c6e6a4cc582bb37eb471ba039019">from</a> and <a href="#a9e9c4862b3a45f4e96bd602c519991c5">take</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### copyToSymbolStringPtr() {#a2ee0876c1646b50c1c484300ab45f8bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolStringPtr llvm::orc::SymbolStringPoolEntryUnsafe::copyToSymbolStringPtr ()</td>
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

<p>Creates a <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> for this entry, with the <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> retaining the entry as usual.</p>

<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>

</div>
</div>

### moveToSymbolStringPtr() {#ab404390b250a0b4ca46d3a6ec59b65d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolStringPtr llvm::orc::SymbolStringPoolEntryUnsafe::moveToSymbolStringPtr ()</td>
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

<p>Creates a <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> for this entry <em>without</em> performing a retain operation during construction.</p>

<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptrbase/#aa114e683cff1ea8ab53012cc24dd8ae7">llvm::orc::SymbolStringPtrBase::S</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### rawPtr() {#a908a1e1a1ecbfc6b65ab38c7a8fda227}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PoolEntry * llvm::orc::SymbolStringPoolEntryUnsafe::rawPtr ()</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>

</div>
</div>

### release() {#a49c1e5962abd3bde8c73a4a42e69ca69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::SymbolStringPoolEntryUnsafe::release ()</td>
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



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>

</div>
</div>

### retain() {#a3d7ddbbafec6e5fefaeade4e07eefb0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::SymbolStringPoolEntryUnsafe::retain ()</td>
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



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### E {#a3492b9e5abaf7b8ae763af031c9f51c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PoolEntry* llvm::orc::SymbolStringPoolEntryUnsafe::E = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### from() {#a08a5c6e6a4cc582bb37eb471ba039019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolStringPoolEntryUnsafe llvm::orc::SymbolStringPoolEntryUnsafe::from (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> &amp; S)</td>
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

<p>Create an unsafe pool entry ref without changing the ref-count.</p>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptrbase/#aa114e683cff1ea8ab53012cc24dd8ae7">llvm::orc::SymbolStringPtrBase::S</a> and <a href="#a6c9a7215d3cfc523feb0a04f4d1f88ab">SymbolStringPoolEntryUnsafe</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga7286ab56f015dc3d1364ee35c18248a0">LLVMOrcCreateDynamicLibrarySearchGeneratorForPath</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga989066e131860f8fe758251c061860a7">LLVMOrcCreateDynamicLibrarySearchGeneratorForProcess</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga4af207d5a28d38c765a7f33d658df2a5">LLVMOrcExecutionSessionLookup</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga675c5e5d67c4a2c624a575bf8964720d">LLVMOrcMaterializationResponsibilityGetInitializerSymbol</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga120f9b694ced7208de2a0c222f04ce3a">LLVMOrcMaterializationResponsibilityGetRequestedSymbols</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga17349a4a145c7bf1c7891e7057822fa8">LLVMOrcMaterializationResponsibilityGetSymbols</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/capidefinitiongenerator/#a8a004d734e3626fad8ff8455c8e88f1f">llvm::orc::CAPIDefinitionGenerator::tryToGenerate</a>.</p>

</div>
</div>

### take() {#a9e9c4862b3a45f4e96bd602c519991c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolStringPoolEntryUnsafe llvm::orc::SymbolStringPoolEntryUnsafe::take (<a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> &amp;&amp; S)</td>
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

<p>Consumes the given <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> without releasing the pool entry.</p>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a> and <a href="#a6c9a7215d3cfc523feb0a04f4d1f88ab">SymbolStringPoolEntryUnsafe</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gabe10f423ce0da67ab09709135e441758">LLVMOrcExecutionSessionIntern</a> and <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga53d78919ce533b45f86230a41a78c8a9">LLVMOrcLLJITMangleAndIntern</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">SymbolStringPool.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
