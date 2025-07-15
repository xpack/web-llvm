---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gsym/callsiteinfoloader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CallSiteInfoLoader` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::gsym::CallSiteInfoLoader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/callsiteinfo-h">llvm/DebugInfo/GSYM/CallSiteInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb98f699283ca3c44ceec5b16c2d9c9c">CallSiteInfoLoader</a> (GsymCreator &amp;GCreator, std::vector&lt; FunctionInfo &gt; &amp;Funcs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor that initializes the <a href="/web-llvm/docs/api/classes/llvm/gsym/callsiteinfoloader">CallSiteInfoLoader</a> with necessary data structures. <a href="#afb98f699283ca3c44ceec5b16c2d9c9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af96a5f4033bb285a8570b073578aceb1">loadYAML</a> (StringRef YAMLFile)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method reads the specified YAML file, parses its content, and updates the <span class="doxyComputerOutput">Funcs</span> vector with call site information based on the YAML data. <a href="#af96a5f4033bb285a8570b073578aceb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13db985a82c753b8d6b5d3e35575bfc4">buildFunctionMap</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Builds a map from function names to <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> pointers based on the provided <span class="doxyComputerOutput">Funcs</span> vector. <a href="#a13db985a82c753b8d6b5d3e35575bfc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a21eecf302e1ca9a632fc37bf493e5c">processYAMLFunctions</a> (const llvm::yaml::FunctionsYAML &amp;FuncYAMLs, StringMap&lt; FunctionInfo * &gt; &amp;FuncMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Processes the parsed YAML functions and updates the <span class="doxyComputerOutput">FuncMap</span> accordingly. <a href="#a6a21eecf302e1ca9a632fc37bf493e5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cf5bafec3436d2f6699fbcb9f54eeba">GCreator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reference to the parent Gsym Creator object. <a href="#a3cf5bafec3436d2f6699fbcb9f54eeba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4f58daca8862a3fa11af35308b4c97f">Funcs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reference to the vector of <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> objects to be populated. <a href="#aa4f58daca8862a3fa11af35308b4c97f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/callsiteinfo-h">CallSiteInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CallSiteInfoLoader() {#afb98f699283ca3c44ceec5b16c2d9c9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::gsym::CallSiteInfoLoader::CallSiteInfoLoader (<a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> &amp; GCreator, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> &gt; &amp; Funcs)</td>
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

<p>Constructor that initializes the <a href="/web-llvm/docs/api/classes/llvm/gsym/callsiteinfoloader">CallSiteInfoLoader</a> with necessary data structures.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">GCreator</td>
<td class="doxyParamItemDescription"><p>A reference to the <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/callsiteinfo-h">CallSiteInfo.h</a>.</p>


<p>Referenced by <a href="#af96a5f4033bb285a8570b073578aceb1">loadYAML</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### loadYAML() {#af96a5f4033bb285a8570b073578aceb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CallSiteInfoLoader::loadYAML (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> YAMLFile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method reads the specified YAML file, parses its content, and updates the <span class="doxyComputerOutput">Funcs</span> vector with call site information based on the YAML data.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Funcs</td>
<td class="doxyParamItemDescription"><p>A reference to a vector of <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> objects to be populated.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">YAMLFile</td>
<td class="doxyParamItemDescription"><p>A <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> representing the path to the YAML file to be loaded.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></span> indicating success or describing any issues encountered during the loading process.</p></dd>
</dl>


<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/callsiteinfo-h">CallSiteInfo.h</a>, definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/callsiteinfo-cpp">CallSiteInfo.cpp</a>.</p>


<p>References <a href="#afb98f699283ca3c44ceec5b16c2d9c9c">CallSiteInfoLoader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/input/#aa353fb192bcd1d2e0561858ad440829b">llvm::yaml::Input::error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa98611beefe78f907beeee7305cc8174">llvm::MemoryBuffer::getFile</a> and <a href="#af96a5f4033bb285a8570b073578aceb1">loadYAML</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#a9e3037da68715a480cd7b1996f5737a8">llvm::gsym::GsymCreator::loadCallSitesFromYAML</a> and <a href="#af96a5f4033bb285a8570b073578aceb1">loadYAML</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### buildFunctionMap() {#a13db985a82c753b8d6b5d3e35575bfc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt; FunctionInfo * &gt; CallSiteInfoLoader::buildFunctionMap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Builds a map from function names to <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> pointers based on the provided <span class="doxyComputerOutput">Funcs</span> vector.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Funcs</td>
<td class="doxyParamItemDescription"><p>A reference to a vector of <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> objects.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a> mapping function names (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>) to their corresponding <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> pointers.</p></dd>
</dl>


<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/callsiteinfo-h">CallSiteInfo.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/callsiteinfo-cpp">CallSiteInfo.cpp</a>.</p>

</div>
</div>

### processYAMLFunctions() {#a6a21eecf302e1ca9a632fc37bf493e5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CallSiteInfoLoader::processYAMLFunctions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/functionsyaml">llvm::yaml::FunctionsYAML</a> &amp; FuncYAMLs, <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> * &gt; &amp; FuncMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Processes the parsed YAML functions and updates the <span class="doxyComputerOutput">FuncMap</span> accordingly.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">FuncYAMLs</td>
<td class="doxyParamItemDescription"><p>A constant reference to an <a href="/web-llvm/docs/api/structs/llvm/yaml/functionsyaml">llvm::yaml::FunctionsYAML</a> object containing parsed YAML data.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FuncMap</td>
<td class="doxyParamItemDescription"><p>A reference to a <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a> mapping function names to <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> pointers.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></span> indicating success or describing any issues encountered during processing.</p></dd>
</dl>


<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/callsiteinfo-h">CallSiteInfo.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/callsiteinfo-cpp">CallSiteInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Funcs {#aa4f58daca8862a3fa11af35308b4c97f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;FunctionInfo&gt;&amp; llvm::gsym::CallSiteInfoLoader::Funcs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reference to the vector of <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> objects to be populated.</p>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/callsiteinfo-h">CallSiteInfo.h</a>.</p>

</div>
</div>

### GCreator {#a3cf5bafec3436d2f6699fbcb9f54eeba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GsymCreator&amp; llvm::gsym::CallSiteInfoLoader::GCreator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reference to the parent Gsym Creator object.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/callsiteinfo-h">CallSiteInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/callsiteinfo-h">CallSiteInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/callsiteinfo-cpp">CallSiteInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
