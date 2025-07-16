---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlcrossmoduleexportssubsection
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `YAMLCrossModuleExportsSubsection` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{CodeViewYAMLDebugSections.cpp}::YAMLCrossModuleExportsSubsection { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/yamlsubsectionbase">YAMLSubsectionBase</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46eab4e968448494abaab29f74153f47">YAMLCrossModuleExportsSubsection</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe4c42b91bb1b2bfec6771dcb62ba7d9">map</a> (IO &amp;IO) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsection">DebugSubsection</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bfa9877a71e7b1e7f40fbdfbc4972a1">toCodeViewSubsection</a> (BumpPtrAllocator &amp;Allocator, const codeview::StringsAndChecksums &amp;SC) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/crossmoduleexport">CrossModuleExport</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abae8847965f6bef51aeb6fbd036fd29b">Exports</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::shared_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlcrossmoduleexportssubsection">YAMLCrossModuleExportsSubsection</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d3e321118a9257121b1254b7e810d0b">fromCodeViewSubsection</a> (const DebugCrossModuleExportsSubsectionRef &amp;Exports)</td>
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


<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### YAMLCrossModuleExportsSubsection() {#a46eab4e968448494abaab29f74153f47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLCrossModuleExportsSubsection::YAMLCrossModuleExportsSubsection ()</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afa48abdbbba67a8179cfad59046eb9507d">llvm::codeview::CrossScopeExports</a> and <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/yamlsubsectionbase/#a84cb32dd1f7b9839cfaed7be5149083c">llvm::CodeViewYAML::detail::YAMLSubsectionBase::YAMLSubsectionBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### map() {#abe4c42b91bb1b2bfec6771dcb62ba7d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void YAMLCrossModuleExportsSubsection::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>References <a href="#abae8847965f6bef51aeb6fbd036fd29b">Exports</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a48aefe64f43e923bdcaddcc2ea3eaf0c">llvm::yaml::IO::mapTag</a>.</p>

</div>
</div>

### toCodeViewSubsection() {#a6bfa9877a71e7b1e7f40fbdfbc4972a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt; DebugSubsection &gt; YAMLCrossModuleExportsSubsection::toCodeViewSubsection (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/stringsandchecksums">codeview::StringsAndChecksums</a> &amp; SC)</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>Reference <a href="#abae8847965f6bef51aeb6fbd036fd29b">Exports</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Exports {#abae8847965f6bef51aeb6fbd036fd29b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;CrossModuleExport&gt; anonymous{CodeViewYAMLDebugSections.cpp}::YAMLCrossModuleExportsSubsection::Exports</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>Referenced by <a href="#a5d3e321118a9257121b1254b7e810d0b">fromCodeViewSubsection</a>, <a href="#abe4c42b91bb1b2bfec6771dcb62ba7d9">map</a> and <a href="#a6bfa9877a71e7b1e7f40fbdfbc4972a1">toCodeViewSubsection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### fromCodeViewSubsection() {#a5d3e321118a9257121b1254b7e810d0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::shared_ptr&lt; YAMLCrossModuleExportsSubsection &gt; &gt; YAMLCrossModuleExportsSubsection::fromCodeViewSubsection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/debugcrossmoduleexportssubsectionref">DebugCrossModuleExportsSubsectionRef</a> &amp; Exports)</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>Reference <a href="#abae8847965f6bef51aeb6fbd036fd29b">Exports</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/subsectionconversionvisitor/#a9fbf9bc88c2dff15da11c242335b2769">anonymous{CodeViewYAMLDebugSections.cpp}::SubsectionConversionVisitor::visitCrossModuleExports</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
