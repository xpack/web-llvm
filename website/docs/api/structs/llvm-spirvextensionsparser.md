---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/spirvextensionsparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `SPIRVExtensionsParser` Struct

<p>Command line parser for toggling SPIR-V extensions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::SPIRVExtensionsParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcommandline-h">Target/SPIRV/SPIRVCommandLine.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/parser">parser&lt;DataType&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22edcffe7457161757b4b065b473e3ce">SPIRVExtensionsParser</a> (cl::Option &amp;O)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c59e739efd5cf76e15f932543c272e3">parse</a> (cl::Option &amp;O, StringRef ArgName, StringRef ArgValue, std::set&lt; SPIRV::Extension::Extension &gt; &amp;Vals)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses SPIR-V extension name from CLI arguments. <a href="#a9c59e739efd5cf76e15f932543c272e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1565934563ca4588b6385767ae235516">checkExtensions</a> (const std::vector&lt; std::string &gt; &amp;ExtNames, std::set&lt; SPIRV::Extension::Extension &gt; &amp;AllowedExtensions)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Validates and converts extension names into internal enum values. <a href="#a1565934563ca4588b6385767ae235516">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Command line parser for toggling SPIR-V extensions.</p>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcommandline-h">SPIRVCommandLine.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SPIRVExtensionsParser() {#a22edcffe7457161757b4b065b473e3ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SPIRVExtensionsParser::SPIRVExtensionsParser (<a href="/web-llvm/docs/api/classes/llvm/cl/option">cl::Option</a> &amp; O)</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcommandline-h">SPIRVCommandLine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/cl/parser/#a5438381d402f2464672bc4e355f36bc7">llvm::cl::parser&lt; std::set&lt; SPIRV::Extension::Extension &gt; &gt;::parser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### parse() {#a9c59e739efd5cf76e15f932543c272e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SPIRVExtensionsParser::parse (<a href="/web-llvm/docs/api/classes/llvm/cl/option">cl::Option</a> &amp; O, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ArgName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ArgValue, std::set&lt; SPIRV::Extension::Extension &gt; &amp; Vals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parses SPIR-V extension name from CLI arguments.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Returns true on error.</p></dd>
</dl>


<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcommandline-h">SPIRVCommandLine.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcommandline-cpp">SPIRVCommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcommandline-cpp/#acc69830a46221294cfc7f04a3f7c99ee">SPIRVExtensionMap</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### checkExtensions() {#a1565934563ca4588b6385767ae235516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringRef SPIRVExtensionsParser::checkExtensions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::string &gt; &amp; ExtNames, std::set&lt; SPIRV::Extension::Extension &gt; &amp; AllowedExtensions)</td>
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

<p>Validates and converts extension names into internal enum values.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Returns a reference to the unknown SPIR-V extension name from the list if present, or an empty <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> on success.</p></dd>
</dl>


<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcommandline-h">SPIRVCommandLine.h</a>, definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcommandline-cpp">SPIRVCommandLine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcommandline-cpp/#acc69830a46221294cfc7f04a3f7c99ee">SPIRVExtensionMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6d9c43797976f73bdbe0c75995f84865">llvm::SPIRVTranslate</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcommandline-cpp">SPIRVCommandLine.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcommandline-h">SPIRVCommandLine.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
