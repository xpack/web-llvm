---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/irmaterializationunit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `IRMaterializationUnit` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit">IRMaterializationUnit</a> is a convenient base class for MaterializationUnits wrapping LLVM IR. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::IRMaterializationUnit { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">llvm/ExecutionEngine/Orc/Layer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> represents a set of symbol definitions that can be materialized as a group, or individually discarded (when overriding definitions are encountered). <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/basicirlayermaterializationunit">BasicIRLayerMaterializationUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> that materializes modules by calling the 'emit' method on the given <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer">IRLayer</a>. <a href="/web-llvm/docs/api/classes/llvm/orc/basicirlayermaterializationunit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/partitioningirmaterializationunit">PartitioningIRMaterializationUnit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acda17e0078ab60791c6e794f403b71ff">SymbolNameToDefinitionMap</a> = std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ba5ee0773bcb7bf0614f9ae9f010198">IRMaterializationUnit</a> (ExecutionSession &amp;ES, const IRSymbolMapper::ManglingOptions &amp;MO, ThreadSafeModule TSM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an IRMaterializationLayer. <a href="#a6ba5ee0773bcb7bf0614f9ae9f010198">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd7587e443a02c59f86f70c0cd9ca04d">IRMaterializationUnit</a> (ThreadSafeModule TSM, Interface I, SymbolNameToDefinitionMap SymbolToDefinition)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an IRMaterializationLayer from a module, and pre-existing SymbolFlags and SymbolToDefinition maps. <a href="#abd7587e443a02c59f86f70c0cd9ca04d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a066e5df8f78009d6abd5342c6c1707c7">getName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the ModuleIdentifier as the name for this <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a>. <a href="#a066e5df8f78009d6abd5342c6c1707c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a648770ab5b66085b4a1d6c05b33a2ca5">getModule</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reference to the contained <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a>. <a href="#a648770ab5b66085b4a1d6c05b33a2ca5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0990d18053c36ab475b5a8dd9a5937a6">discard</a> (const JITDylib &amp;JD, const SymbolStringPtr &amp;Name) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementations of this method should discard the given symbol from the source (e.g. <a href="#a0990d18053c36ab475b5a8dd9a5937a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c041de2ccbd4ea7436a03c71c79b900">TSM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#acda17e0078ab60791c6e794f403b71ff">SymbolNameToDefinitionMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29b40cb9c20cdb418674500762eaeb77">SymbolToDefinition</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27d6fa7d94c376471c6505815aa9db9a">getInitSymbol</a> (ExecutionSession &amp;ES, const ThreadSafeModule &amp;TSM)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit">IRMaterializationUnit</a> is a convenient base class for MaterializationUnits wrapping LLVM IR.</p>


<p>Represents materialization responsibility for all symbols in the given module. If symbols are overridden by other definitions, then their linkage is changed to available-externally.</p>


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### SymbolNameToDefinitionMap {#acda17e0078ab60791c6e794f403b71ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::IRMaterializationUnit::SymbolNameToDefinitionMap =  std::map&lt;SymbolStringPtr, GlobalValue *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### IRMaterializationUnit() {#a6ba5ee0773bcb7bf0614f9ae9f010198}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::IRMaterializationUnit::IRMaterializationUnit (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/irsymbolmapper/manglingoptions">IRSymbolMapper::ManglingOptions</a> &amp; MO, <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> TSM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an IRMaterializationLayer.</p>


<p>Scans the module to build the SymbolFlags and SymbolToDefinition maps.</p>


<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/layer-cpp">Layer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/irsymbolmapper/manglingoptions/#a4d4da595dfbf867a4cab51af1b4c6255">llvm::orc::IRSymbolMapper::ManglingOptions::EmulatedTLS</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit/#ae073d99ba71b23b530556f075655fc61">llvm::orc::MaterializationUnit::ExecutionSession</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#aa66476422470ab204074b3198bcf4d15">llvm::JITSymbolFlags::fromGlobalValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#abcbe492bce3ccc16e0bbb50292576c5c">llvm::Module::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule/#a58bcc80e93468f93bcb88913975c9d14">llvm::orc::ThreadSafeModule::getModuleUnlocked</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a4174e4c948f0b4ebcdb9c539a2902d8c">llvm::orc::getStaticInitGVs</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit/#a2d3b77ff8ea5f0bcf4ba2ec912ee0c58">llvm::orc::MaterializationUnit::InitSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#a4a6187a7b7e11faffbcb0f788bd2543c">llvm::orc::ExecutionSession::intern</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cbab78b49be60a6b5faf277860a45753ea5">llvm::JITSymbolFlags::MaterializationSideEffectsOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit/#a1233ea2ef51205e4954cdc12e7bc2d81">llvm::orc::MaterializationUnit::MaterializationUnit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035ab2d0d4bc9ba11b7324f5ffc20a9dc37a">llvm::Comdat::NoDeduplicate</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit/#a387220b1a2a52bb23b83009c9c33527a">llvm::orc::MaterializationUnit::SymbolFlags</a>, <a href="#a29b40cb9c20cdb418674500762eaeb77">SymbolToDefinition</a>, <a href="#a8c041de2ccbd4ea7436a03c71c79b900">TSM</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cbabe8fbc5eba26a22d11d3ed68f8ada397">llvm::JITSymbolFlags::Weak</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule/#a5dc53e9bbda9066a1ade839494fe0cd9">llvm::orc::ThreadSafeModule::withModuleDo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/basicirlayermaterializationunit/#a6ecb87f3ae601f79964b914bf0363e57">llvm::orc::BasicIRLayerMaterializationUnit::BasicIRLayerMaterializationUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/partitioningirmaterializationunit/#a8ff29e163abadbf9b7e3e90b8a16426d">llvm::orc::PartitioningIRMaterializationUnit::PartitioningIRMaterializationUnit</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/partitioningirmaterializationunit/#a248354be41911727ade17aeed4fadf40">llvm::orc::PartitioningIRMaterializationUnit::PartitioningIRMaterializationUnit</a>.</p>

</div>
</div>

### IRMaterializationUnit() {#abd7587e443a02c59f86f70c0cd9ca04d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::IRMaterializationUnit::IRMaterializationUnit (<a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> TSM, <a href="/web-llvm/docs/api/structs/llvm/orc/materializationunit/interface">Interface</a> I, <a href="#acda17e0078ab60791c6e794f403b71ff">SymbolNameToDefinitionMap</a> SymbolToDefinition)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an IRMaterializationLayer from a module, and pre-existing SymbolFlags and SymbolToDefinition maps.</p>


<p>The maps must provide entries for each definition in M. This constructor is useful for delegating work from one <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit">IRMaterializationUnit</a> to another.</p>


<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/layer-cpp">Layer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit/#a1233ea2ef51205e4954cdc12e7bc2d81">llvm::orc::MaterializationUnit::MaterializationUnit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#a29b40cb9c20cdb418674500762eaeb77">SymbolToDefinition</a> and <a href="#a8c041de2ccbd4ea7436a03c71c79b900">TSM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getModule() {#a648770ab5b66085b4a1d6c05b33a2ca5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ThreadSafeModule &amp; llvm::orc::IRMaterializationUnit::getModule ()</td>
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

<p>Return a reference to the contained <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a>.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>.</p>


<p>Reference <a href="#a8c041de2ccbd4ea7436a03c71c79b900">TSM</a>.</p>

</div>
</div>

### getName() {#a066e5df8f78009d6abd5342c6c1707c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::orc::IRMaterializationUnit::getName ()</td>
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

<p>Return the ModuleIdentifier as the name for this <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a>.</p>

<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/layer-cpp">Layer.cpp</a>.</p>


<p>Reference <a href="#a8c041de2ccbd4ea7436a03c71c79b900">TSM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### discard() {#a0990d18053c36ab475b5a8dd9a5937a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::IRMaterializationUnit::discard (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> &amp; Name)</td>
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

<p>Implementations of this method should discard the given symbol from the source (e.g.</p>


<p>if the source is an LLVM IR <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> and the symbol is a function, delete the function body or mark it available externally).</p>


<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/layer-cpp">Layer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### SymbolToDefinition {#a29b40cb9c20cdb418674500762eaeb77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolNameToDefinitionMap llvm::orc::IRMaterializationUnit::SymbolToDefinition</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>.</p>


<p>Referenced by <a href="#a6ba5ee0773bcb7bf0614f9ae9f010198">IRMaterializationUnit</a>, <a href="#abd7587e443a02c59f86f70c0cd9ca04d">IRMaterializationUnit</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/partitioningirmaterializationunit/#a248354be41911727ade17aeed4fadf40">llvm::orc::PartitioningIRMaterializationUnit::PartitioningIRMaterializationUnit</a>.</p>

</div>
</div>

### TSM {#a8c041de2ccbd4ea7436a03c71c79b900}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadSafeModule llvm::orc::IRMaterializationUnit::TSM</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/basicirlayermaterializationunit/#a6ecb87f3ae601f79964b914bf0363e57">llvm::orc::BasicIRLayerMaterializationUnit::BasicIRLayerMaterializationUnit</a>, <a href="#a648770ab5b66085b4a1d6c05b33a2ca5">getModule</a>, <a href="#a066e5df8f78009d6abd5342c6c1707c7">getName</a>, <a href="#a6ba5ee0773bcb7bf0614f9ae9f010198">IRMaterializationUnit</a>, <a href="#abd7587e443a02c59f86f70c0cd9ca04d">IRMaterializationUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/partitioningirmaterializationunit/#a8ff29e163abadbf9b7e3e90b8a16426d">llvm::orc::PartitioningIRMaterializationUnit::PartitioningIRMaterializationUnit</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/partitioningirmaterializationunit/#a248354be41911727ade17aeed4fadf40">llvm::orc::PartitioningIRMaterializationUnit::PartitioningIRMaterializationUnit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getInitSymbol() {#a27d6fa7d94c376471c6505815aa9db9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolStringPtr llvm::orc::IRMaterializationUnit::getInitSymbol (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> &amp; TSM)</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/layer-cpp">Layer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
