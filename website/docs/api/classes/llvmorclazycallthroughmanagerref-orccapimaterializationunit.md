---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvmorclazycallthroughmanagerref/orccapimaterializationunit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `OrcCAPIMaterializationUnit` Class Reference



## Declaration

<div class="doxyDeclaration">
class LLVMOrcLazyCallThroughManagerRef::OrcCAPIMaterializationUnit { ... }
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a4c7a8eb402130db2164aeaacce8009">OrcCAPIMaterializationUnit</a> (std::string Name, SymbolFlagsMap InitialSymbolFlags, SymbolStringPtr InitSymbol, void *Ctx, LLVMOrcMaterializationUnitMaterializeFunction Materialize, LLVMOrcMaterializationUnitDiscardFunction Discard, LLVMOrcMaterializationUnitDestroyFunction Destroy)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63c57c658f58f155dfdeef07b179bba5">~OrcCAPIMaterializationUnit</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25e68eb90bafe0c9ab7d1e406d666e9b">getName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the name of this materialization unit. <a href="#a25e68eb90bafe0c9ab7d1e406d666e9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91fe96ec6e24d78a343ac2b553d42c9e">materialize</a> (std::unique_ptr&lt; MaterializationResponsibility &gt; R) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementations of this method should materialize all symbols in the materialzation unit, except for those that have been previously discarded. <a href="#a91fe96ec6e24d78a343ac2b553d42c9e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed73ccf531c336fb596dc3bb73399bf0">discard</a> (const JITDylib &amp;JD, const SymbolStringPtr &amp;Name) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementations of this method should discard the given symbol from the source (e.g. <a href="#aed73ccf531c336fb596dc3bb73399bf0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7aa9f13e6a3dafe2a4843ad42eebad1">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81055fd020c9fba8887bb99a2018dd23">Ctx</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gacd70f412e613614839766293b19a1bc5">LLVMOrcMaterializationUnitMaterializeFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b779af3c359c69258f83121708db97b">Materialize</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gac5ff0262f17e21b218425ea47651fdb4">LLVMOrcMaterializationUnitDiscardFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea59e9bbc27e041a7cb1bebe0a2251a3">Discard</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga864c46b3900d86a78ad328d9f5a11ff9">LLVMOrcMaterializationUnitDestroyFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c1eb9bf5da9d94abadbe9575bad9e7a">Destroy</a> = nullptr</td>
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


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OrcCAPIMaterializationUnit() {#a9a4c7a8eb402130db2164aeaacce8009}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOrcLazyCallThroughManagerRef::OrcCAPIMaterializationUnit::OrcCAPIMaterializationUnit (std::string Name, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#afd6431981e7fdfd4b5d2794f04d7d913">SymbolFlagsMap</a> InitialSymbolFlags, <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> InitSymbol, void * Ctx, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gacd70f412e613614839766293b19a1bc5">LLVMOrcMaterializationUnitMaterializeFunction</a> Materialize, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gac5ff0262f17e21b218425ea47651fdb4">LLVMOrcMaterializationUnitDiscardFunction</a> Discard, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga864c46b3900d86a78ad328d9f5a11ff9">LLVMOrcMaterializationUnitDestroyFunction</a> Destroy)</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit/#a2d3b77ff8ea5f0bcf4ba2ec912ee0c58">llvm::orc::MaterializationUnit::InitSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit/#a1233ea2ef51205e4954cdc12e7bc2d81">llvm::orc::MaterializationUnit::MaterializationUnit</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~OrcCAPIMaterializationUnit() {#a63c57c658f58f155dfdeef07b179bba5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOrcLazyCallThroughManagerRef::OrcCAPIMaterializationUnit::~OrcCAPIMaterializationUnit ()</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getName() {#a25e68eb90bafe0c9ab7d1e406d666e9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef LLVMOrcLazyCallThroughManagerRef::OrcCAPIMaterializationUnit::getName ()</td>
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

<p>Return the name of this materialization unit.</p>


<p>Useful for debugging output.</p>


<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>

</div>
</div>

### materialize() {#a91fe96ec6e24d78a343ac2b553d42c9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMOrcLazyCallThroughManagerRef::OrcCAPIMaterializationUnit::materialize (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; R)</td>
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

<p>Implementations of this method should materialize all symbols in the materialzation unit, except for those that have been previously discarded.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### discard() {#aed73ccf531c336fb596dc3bb73399bf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMOrcLazyCallThroughManagerRef::OrcCAPIMaterializationUnit::discard (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> &amp; Name)</td>
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

<p>Implementations of this method should discard the given symbol from the source (e.g.</p>


<p>if the source is an LLVM IR Module and the symbol is a function, delete the function body or mark it available externally).</p>


<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Ctx {#a81055fd020c9fba8887bb99a2018dd23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* LLVMOrcLazyCallThroughManagerRef::OrcCAPIMaterializationUnit::Ctx = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>

</div>
</div>

### Destroy {#a2c1eb9bf5da9d94abadbe9575bad9e7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOrcMaterializationUnitDestroyFunction LLVMOrcLazyCallThroughManagerRef::OrcCAPIMaterializationUnit::Destroy = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>

</div>
</div>

### Discard {#aea59e9bbc27e041a7cb1bebe0a2251a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOrcMaterializationUnitDiscardFunction LLVMOrcLazyCallThroughManagerRef::OrcCAPIMaterializationUnit::Discard = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>

</div>
</div>

### Materialize {#a0b779af3c359c69258f83121708db97b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOrcMaterializationUnitMaterializeFunction LLVMOrcLazyCallThroughManagerRef::OrcCAPIMaterializationUnit::Materialize = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>

</div>
</div>

### Name {#aa7aa9f13e6a3dafe2a4843ad42eebad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string LLVMOrcLazyCallThroughManagerRef::OrcCAPIMaterializationUnit::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
