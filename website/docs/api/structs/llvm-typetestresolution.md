---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/typetestresolution
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `TypeTestResolution` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::TypeTestResolution { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">llvm/IR/ModuleSummaryIndex.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Kind { <a href="#a3a09256c2858f8b38ce2b9481c528bed">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specifies which kind of type check we should emit for this byte array. <a href="#a3a09256c2858f8b38ce2b9481c528bed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="#a3a09256c2858f8b38ce2b9481c528bed">llvm::TypeTestResolution::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66ff82a2443a6f422cd95843084564f6">TheKind</a> = <a href="#a3a09256c2858f8b38ce2b9481c528beda1893cdb6dc7d73055db02b7e1f46a276">Unknown</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a453599f2782c97d48d8bcedf6f75122d">SizeM1BitWidth</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Range of size-1 expressed as a bit width. <a href="#a453599f2782c97d48d8bcedf6f75122d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad43ecb12669b6fda67694c153847ebdd">AlignLog2</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f7d657b28994fc8695b080cb20b1c97">SizeM1</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a742493488e02c32e595b0052a4c247d5">BitMask</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad940f79d8b859f1b9bdbc4df5b9bda75">InlineBits</a> = 0</td>
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


<p>Definition at line 1216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Kind {#a3a09256c2858f8b38ce2b9481c528bed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::TypeTestResolution::Kind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Specifies which kind of type check we should emit for this byte array.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unsat<a id="a3a09256c2858f8b38ce2b9481c528beda5826b981efc11834692037f016343fca"></a></td>
<td class="doxyEnumItemDescription">Unsatisfiable type (i.e. no global has this type metadata)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ByteArray<a id="a3a09256c2858f8b38ce2b9481c528bedad6fc792b7da30012ba5aa2e942383f1f"></a></td>
<td class="doxyEnumItemDescription">Test a byte array (first example)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Inline<a id="a3a09256c2858f8b38ce2b9481c528beda2f70fb5ef215b0969f3b319bab4b03c6"></a></td>
<td class="doxyEnumItemDescription">Inlined bit vector ("Short Inline Bit Vectors")</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Single<a id="a3a09256c2858f8b38ce2b9481c528beda2c2da6acce4cf440ed9351dfe34899f0"></a></td>
<td class="doxyEnumItemDescription">Single element (last example in "Short Inline Bit Vectors")</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllOnes<a id="a3a09256c2858f8b38ce2b9481c528bedacbf788f41139e3717dfde370ec59c0aa"></a></td>
<td class="doxyEnumItemDescription">
All-ones bit vector ("Eliminating Bit Vector Checks for
           All-Ones Bit Vectors")
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unknown<a id="a3a09256c2858f8b38ce2b9481c528beda1893cdb6dc7d73055db02b7e1f46a276"></a></td>
<td class="doxyEnumItemDescription">Unknown (analysis not performed, don't lower)</td>
</tr>

</table>
</dd>
</dl>


<p>See <a href="http://clang.llvm.org/docs/ControlFlowIntegrityDesign.html">http://clang.llvm.org/docs/ControlFlowIntegrityDesign.html</a> for full details on each kind of check; the enumerators are described with reference to that document.</p>


<p>Definition at line 1221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AlignLog2 {#ad43ecb12669b6fda67694c153847ebdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::TypeTestResolution::AlignLog2 = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-19754de8db6a5803cd6e0257923ca0a9/#ab2aaf9aa4fa74f208892a8f2543c1e79">llvm::yaml::MappingTraits&lt; TypeTestResolution &gt;::mapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a79b49cae32dc65f1026c9202d100da6f">parseTypeIdSummaryRecord</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a0673433b10a762c449d89d6255ee9f4b">anonymous{AsmWriter.cpp}::AssemblyWriter::printTypeTestResolution</a>.</p>

</div>
</div>

### BitMask {#a742493488e02c32e595b0052a4c247d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::TypeTestResolution::BitMask = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-19754de8db6a5803cd6e0257923ca0a9/#ab2aaf9aa4fa74f208892a8f2543c1e79">llvm::yaml::MappingTraits&lt; TypeTestResolution &gt;::mapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a79b49cae32dc65f1026c9202d100da6f">parseTypeIdSummaryRecord</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a0673433b10a762c449d89d6255ee9f4b">anonymous{AsmWriter.cpp}::AssemblyWriter::printTypeTestResolution</a>.</p>

</div>
</div>

### InlineBits {#ad940f79d8b859f1b9bdbc4df5b9bda75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::TypeTestResolution::InlineBits = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-19754de8db6a5803cd6e0257923ca0a9/#ab2aaf9aa4fa74f208892a8f2543c1e79">llvm::yaml::MappingTraits&lt; TypeTestResolution &gt;::mapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a79b49cae32dc65f1026c9202d100da6f">parseTypeIdSummaryRecord</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a0673433b10a762c449d89d6255ee9f4b">anonymous{AsmWriter.cpp}::AssemblyWriter::printTypeTestResolution</a>.</p>

</div>
</div>

### SizeM1 {#a4f7d657b28994fc8695b080cb20b1c97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::TypeTestResolution::SizeM1 = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-19754de8db6a5803cd6e0257923ca0a9/#ab2aaf9aa4fa74f208892a8f2543c1e79">llvm::yaml::MappingTraits&lt; TypeTestResolution &gt;::mapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a79b49cae32dc65f1026c9202d100da6f">parseTypeIdSummaryRecord</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a0673433b10a762c449d89d6255ee9f4b">anonymous{AsmWriter.cpp}::AssemblyWriter::printTypeTestResolution</a>.</p>

</div>
</div>

### SizeM1BitWidth {#a453599f2782c97d48d8bcedf6f75122d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TypeTestResolution::SizeM1BitWidth = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Range of size-1 expressed as a bit width.</p>


<p>For example, if the size is in range [1,256], this number will be 8. This helps generate the most compact instruction sequences.</p>


<p>Definition at line 1234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-19754de8db6a5803cd6e0257923ca0a9/#ab2aaf9aa4fa74f208892a8f2543c1e79">llvm::yaml::MappingTraits&lt; TypeTestResolution &gt;::mapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a79b49cae32dc65f1026c9202d100da6f">parseTypeIdSummaryRecord</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a0673433b10a762c449d89d6255ee9f4b">anonymous{AsmWriter.cpp}::AssemblyWriter::printTypeTestResolution</a>.</p>

</div>
</div>

### TheKind {#a66ff82a2443a6f422cd95843084564f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::TypeTestResolution::Kind llvm::TypeTestResolution::TheKind = <a href="#a3a09256c2858f8b38ce2b9481c528beda1893cdb6dc7d73055db02b7e1f46a276">Unknown</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-19754de8db6a5803cd6e0257923ca0a9/#ab2aaf9aa4fa74f208892a8f2543c1e79">llvm::yaml::MappingTraits&lt; TypeTestResolution &gt;::mapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a79b49cae32dc65f1026c9202d100da6f">parseTypeIdSummaryRecord</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a0673433b10a762c449d89d6255ee9f4b">anonymous{AsmWriter.cpp}::AssemblyWriter::printTypeTestResolution</a> and <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a9b3924d6dbe1bfa285ef3d3a6c3d4b6f">anonymous{WholeProgramDevirt.cpp}::DevirtModule::scanTypeTestUsers</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
