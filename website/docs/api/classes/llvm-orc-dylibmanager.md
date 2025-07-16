---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/dylibmanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DylibManager` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::orc::DylibManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/dylibmanager-h">llvm/ExecutionEngine/Orc/DylibManager.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol">SelfExecutorProcessControl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> implementation targeting the current process. <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc">SimpleRemoteEPC</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae71ec09d3b629cd60c40a90681bf09d3">SymbolLookupCompleteFn</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/tpctypes/#a1235ce448cabb700be379dceb933d899">tpctypes::LookupResult</a> &gt; &gt;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d7c63537a7b64227dd10c93f59e5829">~DylibManager</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/tpctypes/#a791ec0843cc10da4c64ae6d79f8381d8">tpctypes::DylibHandle</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3949ea92bf2614064d7303fb0cc3629">loadDylib</a> (const char *DylibPath)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Load the dynamic library at the given path and return a handle to it. <a href="#aa3949ea92bf2614064d7303fb0cc3629">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/tpctypes/#a1235ce448cabb700be379dceb933d899">tpctypes::LookupResult</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64e84968129d54de0a32d0d43550ceb4">lookupSymbols</a> (ArrayRef&lt; LookupRequest &gt; Request)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for symbols in the target process. <a href="#a64e84968129d54de0a32d0d43550ceb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a632bc46fd555571d3c82bbf22c7c928a">lookupSymbolsAsync</a> (ArrayRef&lt; LookupRequest &gt; Request, SymbolLookupCompleteFn F)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for symbols in the target process. <a href="#a632bc46fd555571d3c82bbf22c7c928a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/dylibmanager-h">DylibManager.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### SymbolLookupCompleteFn {#ae71ec09d3b629cd60c40a90681bf09d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::DylibManager::SymbolLookupCompleteFn = 
      unique_function&lt;void(Expected&lt;std::vector&lt;tpctypes::LookupResult&gt;&gt;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/dylibmanager-h">DylibManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DylibManager() {#a1d7c63537a7b64227dd10c93f59e5829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::DylibManager::~DylibManager ()</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/dylibmanager-h">DylibManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### loadDylib() {#aa3949ea92bf2614064d7303fb0cc3629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; tpctypes::DylibHandle &gt; llvm::orc::DylibManager::loadDylib (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * DylibPath)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Load the dynamic library at the given path and return a handle to it.</p>


<p>If LibraryPath is null this function will return the global handle for the target process.</p>


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/dylibmanager-h">DylibManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/epcdynamiclibrarysearchgenerator/#a0be4b6ee27375703c0be30f0b730d0ba">llvm::orc::EPCDynamicLibrarySearchGenerator::Load</a>.</p>

</div>
</div>

### lookupSymbols() {#a64e84968129d54de0a32d0d43550ceb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; tpctypes::LookupResult &gt; &gt; llvm::orc::DylibManager::lookupSymbols (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/dylibmanager/lookuprequest">LookupRequest</a> &gt; Request)</td>
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

<p>Search for symbols in the target process.</p>


<p>The result of the lookup is a 2-dimensional array of target addresses that correspond to the lookup order. If a required symbol is not found then this method will return an error. If a weakly referenced symbol is not found then it be assigned a '0' value.</p>


<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/dylibmanager-h">DylibManager.h</a>.</p>


<p>References <a href="#a632bc46fd555571d3c82bbf22c7c928a">lookupSymbolsAsync</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a578c0003fa8d6a75ea0e805e20104439">llvm::orc::lookupAndRecordAddrs</a>.</p>

</div>
</div>

### lookupSymbolsAsync() {#a632bc46fd555571d3c82bbf22c7c928a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::orc::DylibManager::lookupSymbolsAsync (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/dylibmanager/lookuprequest">LookupRequest</a> &gt; Request, <a href="#ae71ec09d3b629cd60c40a90681bf09d3">SymbolLookupCompleteFn</a> F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Search for symbols in the target process.</p>


<p>The result of the lookup is a 2-dimensional array of target addresses that correspond to the lookup order. If a required symbol is not found then this method will return an error. If a weakly referenced symbol is not found then it be assigned a '0' value.</p>


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/dylibmanager-h">DylibManager.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#a64e84968129d54de0a32d0d43550ceb4">lookupSymbols</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/dylibmanager-h">DylibManager.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
