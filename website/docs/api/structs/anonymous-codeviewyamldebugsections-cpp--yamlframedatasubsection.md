---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlframedatasubsection
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `YAMLFrameDataSubsection` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{CodeViewYAMLDebugSections.cpp}::YAMLFrameDataSubsection { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78e0a58767b1879dd2312147944f2a45">YAMLFrameDataSubsection</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae234910ba90c89b6f2dbb2835cf03fbe">map</a> (IO &amp;IO) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a579f3d420bc3612e81c5558364df19f3">toCodeViewSubsection</a> (BumpPtrAllocator &amp;Allocator, const codeview::StringsAndChecksums &amp;SC) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/yamlframedata">YAMLFrameData</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef3388e125ac0accc5239468bf23c959">Frames</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::shared_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlframedatasubsection">YAMLFrameDataSubsection</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbb271a35aa3f6d4d6209ed00bf1620b">fromCodeViewSubsection</a> (const DebugStringTableSubsectionRef &amp;Strings, const DebugFrameDataSubsectionRef &amp;Frames)</td>
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


<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### YAMLFrameDataSubsection() {#a78e0a58767b1879dd2312147944f2a45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLFrameDataSubsection::YAMLFrameDataSubsection ()</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/yamlsubsectionbase/#a84cb32dd1f7b9839cfaed7be5149083c">llvm::CodeViewYAML::detail::YAMLSubsectionBase::YAMLSubsectionBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### map() {#ae234910ba90c89b6f2dbb2835cf03fbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void YAMLFrameDataSubsection::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>References <a href="#aef3388e125ac0accc5239468bf23c959">Frames</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a48aefe64f43e923bdcaddcc2ea3eaf0c">llvm::yaml::IO::mapTag</a>.</p>

</div>
</div>

### toCodeViewSubsection() {#a579f3d420bc3612e81c5558364df19f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt; DebugSubsection &gt; YAMLFrameDataSubsection::toCodeViewSubsection (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/stringsandchecksums">codeview::StringsAndChecksums</a> &amp; SC)</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#aef3388e125ac0accc5239468bf23c959">Frames</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Frames {#aef3388e125ac0accc5239468bf23c959}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;YAMLFrameData&gt; anonymous{CodeViewYAMLDebugSections.cpp}::YAMLFrameDataSubsection::Frames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>Referenced by <a href="#adbb271a35aa3f6d4d6209ed00bf1620b">fromCodeViewSubsection</a>, <a href="#ae234910ba90c89b6f2dbb2835cf03fbe">map</a> and <a href="#a579f3d420bc3612e81c5558364df19f3">toCodeViewSubsection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### fromCodeViewSubsection() {#adbb271a35aa3f6d4d6209ed00bf1620b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::shared_ptr&lt; YAMLFrameDataSubsection &gt; &gt; YAMLFrameDataSubsection::fromCodeViewSubsection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/debugstringtablesubsectionref">DebugStringTableSubsectionRef</a> &amp; Strings, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/debugframedatasubsectionref">DebugFrameDataSubsectionRef</a> &amp; Frames)</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamldebugsections-cpp">CodeViewYAMLDebugSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/yamlframedata/#abf49a56b9e58768e39418bc61e4aca8b">llvm::CodeViewYAML::YAMLFrameData::CodeSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/yamlframedata/#a2f71245bade02a59ba1fb0bb47a18ea0">llvm::CodeViewYAML::YAMLFrameData::Flags</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/yamlframedata/#a3095b5e3ed40ba632ed26d507d2b9251">llvm::CodeViewYAML::YAMLFrameData::FrameFunc</a>, <a href="#aef3388e125ac0accc5239468bf23c959">Frames</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugstringtablesubsectionref/#a89f91fb97bacfa2e66d5f5b912a85304">llvm::codeview::DebugStringTableSubsectionRef::getString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/yamlframedata/#acbad2edcfab6a6b06a72a48e9d92bab9">llvm::CodeViewYAML::YAMLFrameData::LocalSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/yamlframedata/#a3152b3bd2fb17bdae0f436799cb4d5e8">llvm::CodeViewYAML::YAMLFrameData::MaxStackSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0e494c491fad71e29cc10efce7c59f6ca9b2c3bb0332b451775b5ee8ed63bd1d8">llvm::codeview::no_records</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/yamlframedata/#afc7d14532f426554fd5582ddc7894322">llvm::CodeViewYAML::YAMLFrameData::ParamsSize</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/yamlframedata/#aaba0a7c3da5f76b8b2d2beb7edc2f77c">llvm::CodeViewYAML::YAMLFrameData::PrologSize</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/yamlframedata/#a4054f3bf2e038f51a954a9f04de16838">llvm::CodeViewYAML::YAMLFrameData::RvaStart</a> and <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/yamlframedata/#a2193c800cd0f7af0a646f3d86851ed32">llvm::CodeViewYAML::YAMLFrameData::SavedRegsSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/subsectionconversionvisitor/#a59986054f1f5fed916f1e896ee9a2368">anonymous{CodeViewYAMLDebugSections.cpp}::SubsectionConversionVisitor::visitFrameData</a>.</p>

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
