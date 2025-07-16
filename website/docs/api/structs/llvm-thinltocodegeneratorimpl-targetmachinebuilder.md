---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/thinltocodegeneratorimpl/targetmachinebuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `TargetMachineBuilder` Struct Reference

<p>Helper to gather options relevant to the target machine creation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::ThinLTOCodeGeneratorImpl::TargetMachineBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">llvm/LTO/legacy/ThinLTOCodeGenerator.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a057a55d2ecdfd54087c9d8ffbe9f9c2a">create</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d090359baa2bc30408e907adda03fac">TheTriple</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06cf12c8177f10834c0aead2763f9120">MCpu</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2eb44751a3e8aff58119fd0145dd7d18">MAttr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2453cdc658e93b250f98b04e27be439">Options</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac601aa74c8e90d0be29cf5228279f20d">RelocModel</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add469ed4300520656f905214e9c3dbb6">CGOptLevel</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">CodeGenOptLevel::Aggressive</a></td>
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

<p>Helper to gather options relevant to the target machine creation.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### create() {#a057a55d2ecdfd54087c9d8ffbe9f9c2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; TargetMachine &gt; TargetMachineBuilder::create ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>, definition at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#add469ed4300520656f905214e9c3dbb6">CGOptLevel</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a97b31e68ba164458a37e49e7d1053fc1">llvm::Target::createTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#a5a24823d504d2c91c152e69250b2197d">llvm::SubtargetFeatures::getDefaultSubtargetFeatures</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#aaa9679917091c7e93f866894599f923e">llvm::SubtargetFeatures::getString</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a85a69009ec328d5835241f56fb62cc6d">llvm::TargetRegistry::lookupTarget</a>, <a href="#a2eb44751a3e8aff58119fd0145dd7d18">MAttr</a>, <a href="#a06cf12c8177f10834c0aead2763f9120">MCpu</a>, <a href="#ab2453cdc658e93b250f98b04e27be439">Options</a>, <a href="#ac601aa74c8e90d0be29cf5228279f20d">RelocModel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="#a3d090359baa2bc30408e907adda03fac">TheTriple</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CGOptLevel {#add469ed4300520656f905214e9c3dbb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeGenOptLevel llvm::ThinLTOCodeGeneratorImpl::TargetMachineBuilder::CGOptLevel = <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">CodeGenOptLevel::Aggressive</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>


<p>Referenced by <a href="#a057a55d2ecdfd54087c9d8ffbe9f9c2a">create</a> and <a href="/web-llvm/docs/api/classes/anonymous-thinltocodegenerator-cpp-/modulecacheentry/#aea61f7d56840b1a92477a55f4a526de0">anonymous{ThinLTOCodeGenerator.cpp}::ModuleCacheEntry::ModuleCacheEntry</a>.</p>

</div>
</div>

### MAttr {#a2eb44751a3e8aff58119fd0145dd7d18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::ThinLTOCodeGeneratorImpl::TargetMachineBuilder::MAttr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>


<p>Referenced by <a href="#a057a55d2ecdfd54087c9d8ffbe9f9c2a">create</a> and <a href="/web-llvm/docs/api/classes/anonymous-thinltocodegenerator-cpp-/modulecacheentry/#aea61f7d56840b1a92477a55f4a526de0">anonymous{ThinLTOCodeGenerator.cpp}::ModuleCacheEntry::ModuleCacheEntry</a>.</p>

</div>
</div>

### MCpu {#a06cf12c8177f10834c0aead2763f9120}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::ThinLTOCodeGeneratorImpl::TargetMachineBuilder::MCpu</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>


<p>Referenced by <a href="#a057a55d2ecdfd54087c9d8ffbe9f9c2a">create</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a3378f6544e8a6b129793370d1399c66a">initTMBuilder</a> and <a href="/web-llvm/docs/api/classes/anonymous-thinltocodegenerator-cpp-/modulecacheentry/#aea61f7d56840b1a92477a55f4a526de0">anonymous{ThinLTOCodeGenerator.cpp}::ModuleCacheEntry::ModuleCacheEntry</a>.</p>

</div>
</div>

### Options {#ab2453cdc658e93b250f98b04e27be439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetOptions llvm::ThinLTOCodeGeneratorImpl::TargetMachineBuilder::Options</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>


<p>Referenced by <a href="#a057a55d2ecdfd54087c9d8ffbe9f9c2a">create</a> and <a href="/web-llvm/docs/api/classes/anonymous-thinltocodegenerator-cpp-/modulecacheentry/#aea61f7d56840b1a92477a55f4a526de0">anonymous{ThinLTOCodeGenerator.cpp}::ModuleCacheEntry::ModuleCacheEntry</a>.</p>

</div>
</div>

### RelocModel {#ac601aa74c8e90d0be29cf5228279f20d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;Reloc::Model&gt; llvm::ThinLTOCodeGeneratorImpl::TargetMachineBuilder::RelocModel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>


<p>Referenced by <a href="#a057a55d2ecdfd54087c9d8ffbe9f9c2a">create</a> and <a href="/web-llvm/docs/api/classes/anonymous-thinltocodegenerator-cpp-/modulecacheentry/#aea61f7d56840b1a92477a55f4a526de0">anonymous{ThinLTOCodeGenerator.cpp}::ModuleCacheEntry::ModuleCacheEntry</a>.</p>

</div>
</div>

### TheTriple {#a3d090359baa2bc30408e907adda03fac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple llvm::ThinLTOCodeGeneratorImpl::TargetMachineBuilder::TheTriple</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>


<p>Referenced by <a href="#a057a55d2ecdfd54087c9d8ffbe9f9c2a">create</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a3378f6544e8a6b129793370d1399c66a">initTMBuilder</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
