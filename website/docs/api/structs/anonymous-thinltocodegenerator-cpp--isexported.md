---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-thinltocodegenerator-cpp-/isexported
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `IsExported` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{ThinLTOCodeGenerator.cpp}::IsExported { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f010a061701a6776769b7370bd9d9eb">IsExported</a> (const DenseMap&lt; StringRef, FunctionImporter::ExportSetTy &gt; &amp;ExportLists, const DenseSet&lt; GlobalValue::GUID &gt; &amp;GUIDPreservedSymbols)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99872f1d3de4a4b227003fdc42759bc7">operator()</a> (StringRef ModuleIdentifier, ValueInfo VI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acd58852b94e5cce68ad66dc3045f72f0">FunctionImporter::ExportSetTy</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d0397735ea890c48df781a21dc326d1">ExportLists</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c229a4a301add8769be6bb003cbc09f">GUIDPreservedSymbols</a></td>
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


<p>Definition at line 620 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### IsExported() {#a8f010a061701a6776769b7370bd9d9eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ThinLTOCodeGenerator.cpp}::IsExported::IsExported (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acd58852b94e5cce68ad66dc3045f72f0">FunctionImporter::ExportSetTy</a> &gt; &amp; ExportLists, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp; GUIDPreservedSymbols)</td>
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



<p>Definition at line 624 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="#a2d0397735ea890c48df781a21dc326d1">ExportLists</a> and <a href="#a7c229a4a301add8769be6bb003cbc09f">GUIDPreservedSymbols</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator()() {#a99872f1d3de4a4b227003fdc42759bc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ThinLTOCodeGenerator.cpp}::IsExported::operator() (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ModuleIdentifier, <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> VI)</td>
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



<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="#a2d0397735ea890c48df781a21dc326d1">ExportLists</a> and <a href="#a7c229a4a301add8769be6bb003cbc09f">GUIDPreservedSymbols</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ExportLists {#a2d0397735ea890c48df781a21dc326d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DenseMap&lt;StringRef, FunctionImporter::ExportSetTy&gt;&amp; anonymous{ThinLTOCodeGenerator.cpp}::IsExported::ExportLists</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>Referenced by <a href="#a8f010a061701a6776769b7370bd9d9eb">IsExported</a> and <a href="#a99872f1d3de4a4b227003fdc42759bc7">operator()</a>.</p>

</div>
</div>

### GUIDPreservedSymbols {#a7c229a4a301add8769be6bb003cbc09f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DenseSet&lt;GlobalValue::GUID&gt;&amp; anonymous{ThinLTOCodeGenerator.cpp}::IsExported::GUIDPreservedSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>Referenced by <a href="#a8f010a061701a6776769b7370bd9d9eb">IsExported</a> and <a href="#a99872f1d3de4a4b227003fdc42759bc7">operator()</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
