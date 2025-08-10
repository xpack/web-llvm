---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/wholeprogramdevirtresolution
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `WholeProgramDevirtResolution` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::WholeProgramDevirtResolution { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">llvm/IR/ModuleSummaryIndex.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Kind { <a href="#ae992643f8965e97ffbc353b083615208">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="#ae992643f8965e97ffbc353b083615208">llvm::WholeProgramDevirtResolution::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11bddbadb47e3bd7803ded5d4f4248fc">TheKind</a> = <a href="#ae992643f8965e97ffbc353b083615208a332c5d66d09e0ce9c774ed84ce4aaa2d">Indir</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab97c12959c5cc7b46b115da7e1ac5047">SingleImplName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; std::vector&lt; uint64_t &gt;, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg">ByArg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c0a0ec1654585583572f16e799176dc">ResByArg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resolutions for calls with all constant integer arguments (excluding the first argument, "this"), where the key is the argument vector. <a href="#a1c0a0ec1654585583572f16e799176dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 1247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Kind {#ae992643f8965e97ffbc353b083615208}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::WholeProgramDevirtResolution::Kind </td>
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
<td class="doxyEnumItemName">Indir<a id="ae992643f8965e97ffbc353b083615208a332c5d66d09e0ce9c774ed84ce4aaa2d"></a></td>
<td class="doxyEnumItemDescription">Just do a regular virtual call</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SingleImpl<a id="ae992643f8965e97ffbc353b083615208a05ee7e7ff849410d68ccfd73e177387f"></a></td>
<td class="doxyEnumItemDescription">Single implementation devirtualization</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BranchFunnel<a id="ae992643f8965e97ffbc353b083615208ac74c33fab6fb30be2bf7db1f86b0853d"></a></td>
<td class="doxyEnumItemDescription">When retpoline mitigation is enabled, use a branch funnel that is defined in the merged module</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ResByArg {#a1c0a0ec1654585583572f16e799176dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;std::vector&lt;uint64_t&gt;, ByArg&gt; llvm::WholeProgramDevirtResolution::ResByArg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Resolutions for calls with all constant integer arguments (excluding the first argument, "this"), where the key is the argument vector.</p>

<p>Definition at line 1281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a2571433d1b220fb84bfcb7584002cb02">anonymous{WholeProgramDevirt.cpp}::DevirtModule::importResolution</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-2365973b01ec74a29165da4ca33e275f/#a5216c56829df976d43ea4f010b06aff8">llvm::yaml::MappingTraits&lt; WholeProgramDevirtResolution &gt;::mapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a46bea8d236da27677962598b5bd45703">parseWholeProgramDevirtResolutionByArg</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a83d9a3fded69b1a33d8f581f75efe4f3">anonymous{AsmWriter.cpp}::AssemblyWriter::printWPDRes</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a85892c8cb2a8b36248f88a963d8a09ca">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryVirtualConstProp</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#ae4770e119c132809f74cc6faaf62698e">writeWholeProgramDevirtResolution</a>.</p>

</div>
</div>

### SingleImplName {#ab97c12959c5cc7b46b115da7e1ac5047}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::WholeProgramDevirtResolution::SingleImplName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a2571433d1b220fb84bfcb7584002cb02">anonymous{WholeProgramDevirt.cpp}::DevirtModule::importResolution</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-2365973b01ec74a29165da4ca33e275f/#a5216c56829df976d43ea4f010b06aff8">llvm::yaml::MappingTraits&lt; WholeProgramDevirtResolution &gt;::mapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#aaffdb3054263427a7df8fdac667a0c5b">parseWholeProgramDevirtResolution</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a83d9a3fded69b1a33d8f581f75efe4f3">anonymous{AsmWriter.cpp}::AssemblyWriter::printWPDRes</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtindex/#a0e99a7c09395086976fe39e08dbe36a6">anonymous{WholeProgramDevirt.cpp}::DevirtIndex::trySingleImplDevirt</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#ae9f4748bfea60c7f38b8a1f4357b0150">anonymous{WholeProgramDevirt.cpp}::DevirtModule::trySingleImplDevirt</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#ae4770e119c132809f74cc6faaf62698e">writeWholeProgramDevirtResolution</a>.</p>

</div>
</div>

### TheKind {#a11bddbadb47e3bd7803ded5d4f4248fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::WholeProgramDevirtResolution::Kind llvm::WholeProgramDevirtResolution::TheKind = <a href="#ae992643f8965e97ffbc353b083615208a332c5d66d09e0ce9c774ed84ce4aaa2d">Indir</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a2571433d1b220fb84bfcb7584002cb02">anonymous{WholeProgramDevirt.cpp}::DevirtModule::importResolution</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-2365973b01ec74a29165da4ca33e275f/#a5216c56829df976d43ea4f010b06aff8">llvm::yaml::MappingTraits&lt; WholeProgramDevirtResolution &gt;::mapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#aaffdb3054263427a7df8fdac667a0c5b">parseWholeProgramDevirtResolution</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a83d9a3fded69b1a33d8f581f75efe4f3">anonymous{AsmWriter.cpp}::AssemblyWriter::printWPDRes</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#ad722656aa63d87c356ec659228865f65">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryICallBranchFunnel</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtindex/#a0e99a7c09395086976fe39e08dbe36a6">anonymous{WholeProgramDevirt.cpp}::DevirtIndex::trySingleImplDevirt</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#ae9f4748bfea60c7f38b8a1f4357b0150">anonymous{WholeProgramDevirt.cpp}::DevirtModule::trySingleImplDevirt</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#ae4770e119c132809f74cc6faaf62698e">writeWholeProgramDevirtResolution</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
