---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/partitioningirmaterializationunit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PartitioningIRMaterializationUnit` Class



## Declaration

<div class="doxyDeclaration">
class llvm::orc::PartitioningIRMaterializationUnit { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit">IRMaterializationUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit">IRMaterializationUnit</a> is a convenient base class for MaterializationUnits wrapping LLVM IR. <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ff29e163abadbf9b7e3e90b8a16426d">PartitioningIRMaterializationUnit</a> (ExecutionSession &amp;ES, const IRSymbolMapper::ManglingOptions &amp;MO, ThreadSafeModule TSM, IRPartitionLayer &amp;Parent)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a248354be41911727ade17aeed4fadf40">PartitioningIRMaterializationUnit</a> (ThreadSafeModule TSM, Interface I, SymbolNameToDefinitionMap SymbolToDefinition, IRPartitionLayer &amp;Parent)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae258e3d12e2e8ad36bf540327f172ac5">materialize</a> (std::unique_ptr&lt; MaterializationResponsibility &gt; R) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementations of this method should materialize all symbols in the materialzation unit, except for those that have been previously discarded. <a href="#ae258e3d12e2e8ad36bf540327f172ac5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72dc47242762e95f29379655ed158051">discard</a> (const JITDylib &amp;V, const SymbolStringPtr &amp;Name) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementations of this method should discard the given symbol from the source (e.g. <a href="#a72dc47242762e95f29379655ed158051">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/irpartitionlayer">IRPartitionLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a619c20bfc235c42629a21cd574a7c053">Parent</a></td>
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


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/irpartitionlayer-cpp">IRPartitionLayer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PartitioningIRMaterializationUnit() {#a8ff29e163abadbf9b7e3e90b8a16426d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::PartitioningIRMaterializationUnit::PartitioningIRMaterializationUnit (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/irsymbolmapper/manglingoptions">IRSymbolMapper::ManglingOptions</a> &amp; MO, <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> TSM, <a href="/web-llvm/docs/api/classes/llvm/orc/irpartitionlayer">IRPartitionLayer</a> &amp; Parent)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/irpartitionlayer-cpp">IRPartitionLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#a6ba5ee0773bcb7bf0614f9ae9f010198">llvm::orc::IRMaterializationUnit::IRMaterializationUnit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#a8c041de2ccbd4ea7436a03c71c79b900">llvm::orc::IRMaterializationUnit::TSM</a>.</p>

</div>
</div>

### PartitioningIRMaterializationUnit() {#a248354be41911727ade17aeed4fadf40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::PartitioningIRMaterializationUnit::PartitioningIRMaterializationUnit (<a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> TSM, <a href="/web-llvm/docs/api/structs/llvm/orc/materializationunit/interface">Interface</a> I, <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#acda17e0078ab60791c6e794f403b71ff">SymbolNameToDefinitionMap</a> SymbolToDefinition, <a href="/web-llvm/docs/api/classes/llvm/orc/irpartitionlayer">IRPartitionLayer</a> &amp; Parent)</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/irpartitionlayer-cpp">IRPartitionLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#a6ba5ee0773bcb7bf0614f9ae9f010198">llvm::orc::IRMaterializationUnit::IRMaterializationUnit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#a29b40cb9c20cdb418674500762eaeb77">llvm::orc::IRMaterializationUnit::SymbolToDefinition</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#a8c041de2ccbd4ea7436a03c71c79b900">llvm::orc::IRMaterializationUnit::TSM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### discard() {#a72dc47242762e95f29379655ed158051}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::PartitioningIRMaterializationUnit::discard (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a> &amp; Name)</td>
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


<p>if the source is an LLVM IR <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> and the symbol is a function, delete the function body or mark it available externally).</p>


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/irpartitionlayer-cpp">IRPartitionLayer.cpp</a>.</p>

</div>
</div>

### materialize() {#ae258e3d12e2e8ad36bf540327f172ac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::PartitioningIRMaterializationUnit::materialize (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; R)</td>
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

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/irpartitionlayer-cpp">IRPartitionLayer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Parent {#a619c20bfc235c42629a21cd574a7c053}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRPartitionLayer&amp; llvm::orc::PartitioningIRMaterializationUnit::Parent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/irpartitionlayer-cpp">IRPartitionLayer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/irpartitionlayer-cpp">IRPartitionLayer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
