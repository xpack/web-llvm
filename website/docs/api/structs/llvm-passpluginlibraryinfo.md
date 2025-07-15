---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/passpluginlibraryinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PassPluginLibraryInfo` Struct Reference

<p>Information about the plugin required to load its passes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::PassPluginLibraryInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passplugin-h">llvm/Passes/PassPlugin.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dc3ec55b672cefc52e3e18b94c40db5">APIVersion</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The API version understood by this plugin, usually <span class="doxyComputerOutput">LLVM_PLUGIN_API_VERSION</span>. <a href="#a2dc3ec55b672cefc52e3e18b94c40db5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a135291521c79bd085abf48a18edef317">PluginName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A meaningful name of the plugin. <a href="#a135291521c79bd085abf48a18edef317">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd6eb70c00b52cdcf777211111ec5b89">PluginVersion</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The version of the plugin. <a href="#acd6eb70c00b52cdcf777211111ec5b89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void(*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9441b9616c2cc926275d955d8dfe6ccc">RegisterPassBuilderCallbacks</a>)(PassBuilder &)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The callback for registering plugin passes with a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/passbuilder">PassBuilder</a></span> instance. <a href="#a9441b9616c2cc926275d955d8dfe6ccc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Information about the plugin required to load its passes.</p>


<p>This struct defines the core interface for pass plugins and is supposed to be filled out by plugin implementors. LLVM-side users of a plugin are expected to use the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/passplugin">PassPlugin</a></span> class below to interface with it.</p>


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passplugin-h">PassPlugin.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### APIVersion {#a2dc3ec55b672cefc52e3e18b94c40db5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::PassPluginLibraryInfo::APIVersion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The API version understood by this plugin, usually <span class="doxyComputerOutput">LLVM_PLUGIN_API_VERSION</span>.</p>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passplugin-h">PassPlugin.h</a>.</p>

</div>
</div>

### PluginName {#a135291521c79bd085abf48a18edef317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::PassPluginLibraryInfo::PluginName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A meaningful name of the plugin.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passplugin-h">PassPlugin.h</a>.</p>

</div>
</div>

### PluginVersion {#acd6eb70c00b52cdcf777211111ec5b89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::PassPluginLibraryInfo::PluginVersion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The version of the plugin.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passplugin-h">PassPlugin.h</a>.</p>

</div>
</div>

### RegisterPassBuilderCallbacks {#a9441b9616c2cc926275d955d8dfe6ccc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void(* llvm::PassPluginLibraryInfo::RegisterPassBuilderCallbacks) (PassBuilder &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The callback for registering plugin passes with a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/passbuilder">PassBuilder</a></span> instance.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passplugin-h">PassPlugin.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passplugin-h">PassPlugin.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
