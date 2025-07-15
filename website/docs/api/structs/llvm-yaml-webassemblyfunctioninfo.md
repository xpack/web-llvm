---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/webassemblyfunctioninfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `WebAssemblyFunctionInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::WebAssemblyFunctionInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymachinefunctioninfo-h">Target/WebAssembly/WebAssemblyMachineFunctionInfo.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctioninfo">MachineFunctionInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets should override this in a way that mirrors the implementation of <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">llvm::MachineFunctionInfo</a>. <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctioninfo/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a433a54cdb74b28977498e7859159c3e9">WebAssemblyFunctionInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62d795cff608d1ce90ce6edab413169b">WebAssemblyFunctionInfo</a> (const llvm::MachineFunction &amp;MF, const llvm::WebAssemblyFunctionInfo &amp;MFI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f402f81c191602b1f9b147ab6d64892">~WebAssemblyFunctionInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7de1232350499332f12ed0c92ad52253">mappingImpl</a> (yaml::IO &amp;YamlIO) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/yaml/flowstringvalue">FlowStringValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a965882bfac2d9a8b43cdd7317a0aaeb7">Params</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/yaml/flowstringvalue">FlowStringValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8872f86323af5abb4162462e8e2009a5">Results</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52108b82dd5aa67a796d4c0d4572bc17">CFGStackified</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a4a8e844b724d6a47b530c32bc4eddbba">BBNumberMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae98f2c6a12e6f01046af10aeaf7d205">SrcToUnwindDest</a></td>
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


<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymachinefunctioninfo-h">WebAssemblyMachineFunctionInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WebAssemblyFunctionInfo() {#a433a54cdb74b28977498e7859159c3e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::WebAssemblyFunctionInfo::WebAssemblyFunctionInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymachinefunctioninfo-h">WebAssemblyMachineFunctionInfo.h</a>.</p>

</div>
</div>

### WebAssemblyFunctionInfo() {#a62d795cff608d1ce90ce6edab413169b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::WebAssemblyFunctionInfo::WebAssemblyFunctionInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">llvm::MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo">llvm::WebAssemblyFunctionInfo</a> &amp; MFI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymachinefunctioninfo-h">WebAssemblyMachineFunctionInfo.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymachinefunctioninfo-cpp">WebAssemblyMachineFunctionInfo.cpp</a>.</p>


<p>References <a href="#a52108b82dd5aa67a796d4c0d4572bc17">CFGStackified</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo/#af05f6370f2508ffc40a3600dfb6e2341">llvm::WebAssemblyFunctionInfo::getParams</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo/#a1d1bfc648a07740b28effab9ebb3f0d7">llvm::WebAssemblyFunctionInfo::getResults</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aba3a6e52588de22d265ca68259e0c771">llvm::MachineFunction::getWasmEHFuncInfo</a>, <a href="#a965882bfac2d9a8b43cdd7317a0aaeb7">Params</a> and <a href="#a8872f86323af5abb4162462e8e2009a5">Results</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~WebAssemblyFunctionInfo() {#a2f402f81c191602b1f9b147ab6d64892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::WebAssemblyFunctionInfo::~WebAssemblyFunctionInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymachinefunctioninfo-h">WebAssemblyMachineFunctionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### mappingImpl() {#a7de1232350499332f12ed0c92ad52253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void yaml::WebAssemblyFunctionInfo::mappingImpl (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">yaml::IO</a> &amp; YamlIO)</td>
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



<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymachinefunctioninfo-h">WebAssemblyMachineFunctionInfo.h</a>, definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymachinefunctioninfo-cpp">WebAssemblyMachineFunctionInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CFGStackified {#a52108b82dd5aa67a796d4c0d4572bc17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::WebAssemblyFunctionInfo::CFGStackified = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymachinefunctioninfo-h">WebAssemblyMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo/#adeea4dff058fbf427bf9b0dd9462e61c">llvm::WebAssemblyFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-2ef46f95f3a96c9dc966ec79c81b019c/#a4b42fffcb4fe29140c9073f3270807a2">llvm::yaml::MappingTraits&lt; WebAssemblyFunctionInfo &gt;::mapping</a> and <a href="#a62d795cff608d1ce90ce6edab413169b">WebAssemblyFunctionInfo</a>.</p>

</div>
</div>

### Params {#a965882bfac2d9a8b43cdd7317a0aaeb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;FlowStringValue&gt; llvm::yaml::WebAssemblyFunctionInfo::Params</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymachinefunctioninfo-h">WebAssemblyMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo/#adeea4dff058fbf427bf9b0dd9462e61c">llvm::WebAssemblyFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-2ef46f95f3a96c9dc966ec79c81b019c/#a4b42fffcb4fe29140c9073f3270807a2">llvm::yaml::MappingTraits&lt; WebAssemblyFunctionInfo &gt;::mapping</a> and <a href="#a62d795cff608d1ce90ce6edab413169b">WebAssemblyFunctionInfo</a>.</p>

</div>
</div>

### Results {#a8872f86323af5abb4162462e8e2009a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;FlowStringValue&gt; llvm::yaml::WebAssemblyFunctionInfo::Results</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymachinefunctioninfo-h">WebAssemblyMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo/#adeea4dff058fbf427bf9b0dd9462e61c">llvm::WebAssemblyFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-2ef46f95f3a96c9dc966ec79c81b019c/#a4b42fffcb4fe29140c9073f3270807a2">llvm::yaml::MappingTraits&lt; WebAssemblyFunctionInfo &gt;::mapping</a> and <a href="#a62d795cff608d1ce90ce6edab413169b">WebAssemblyFunctionInfo</a>.</p>

</div>
</div>

### SrcToUnwindDest {#aae98f2c6a12e6f01046af10aeaf7d205}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BBNumberMap llvm::yaml::WebAssemblyFunctionInfo::SrcToUnwindDest</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymachinefunctioninfo-h">WebAssemblyMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo/#adeea4dff058fbf427bf9b0dd9462e61c">llvm::WebAssemblyFunctionInfo::initializeBaseYamlFields</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-2ef46f95f3a96c9dc966ec79c81b019c/#a4b42fffcb4fe29140c9073f3270807a2">llvm::yaml::MappingTraits&lt; WebAssemblyFunctionInfo &gt;::mapping</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymachinefunctioninfo-cpp">WebAssemblyMachineFunctionInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymachinefunctioninfo-h">WebAssemblyMachineFunctionInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
