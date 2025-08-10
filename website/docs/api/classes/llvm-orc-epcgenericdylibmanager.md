---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/epcgenericdylibmanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `EPCGenericDylibManager` Class



## Declaration

<div class="doxyDeclaration">
class llvm::orc::EPCGenericDylibManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericdylibmanager-h">llvm/ExecutionEngine/Orc/EPCGenericDylibManager.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae63bfef8805adb7f9d0f399e7ec79828">SymbolLookupCompleteFn</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a> &gt; &gt;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc0bffae84f1dbeb0672b3fac437df97">EPCGenericDylibManager</a> (ExecutorProcessControl &amp;EPC, SymbolAddrs SAs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericmemoryaccess">EPCGenericMemoryAccess</a> instance from a given set of function addrs. <a href="#acc0bffae84f1dbeb0672b3fac437df97">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8ff17813ed881db4af1f6ef52300519">open</a> (StringRef Path, uint64_t Mode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads the dylib with the given name. <a href="#aa8ff17813ed881db4af1f6ef52300519">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a128bedb499eb1c68900d8dbec053b9f9">lookup</a> (tpctypes::DylibHandle H, const SymbolLookupSet &amp;Lookup)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks up symbols within the given dylib. <a href="#a128bedb499eb1c68900d8dbec053b9f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6adb2b787ab8da0a98dd6e385cd9f5b9">lookup</a> (tpctypes::DylibHandle H, const RemoteSymbolLookupSet &amp;Lookup)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks up symbols within the given dylib. <a href="#a6adb2b787ab8da0a98dd6e385cd9f5b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56d1a298963123bd7d97461aceb6d9c2">lookupAsync</a> (tpctypes::DylibHandle H, const SymbolLookupSet &amp;Lookup, SymbolLookupCompleteFn Complete)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks up symbols within the given dylib. <a href="#a56d1a298963123bd7d97461aceb6d9c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65c75adf08e8934cebd374ceee8a6aad">lookupAsync</a> (tpctypes::DylibHandle H, const RemoteSymbolLookupSet &amp;Lookup, SymbolLookupCompleteFn Complete)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks up symbols within the given dylib. <a href="#a65c75adf08e8934cebd374ceee8a6aad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a817191ca507daf681314075f294f7844">EPC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/epcgenericdylibmanager/symboladdrs">SymbolAddrs</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5481bfbca4be5ac5dc1678081293bb31">SAs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericdylibmanager">EPCGenericDylibManager</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f31d0ec435c55a5b3e976c20ea3bf6c">CreateWithDefaultBootstrapSymbols</a> (ExecutorProcessControl &amp;EPC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericmemoryaccess">EPCGenericMemoryAccess</a> instance from a given set of function addrs. <a href="#a3f31d0ec435c55a5b3e976c20ea3bf6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericdylibmanager-h">EPCGenericDylibManager.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### SymbolLookupCompleteFn {#ae63bfef8805adb7f9d0f399e7ec79828}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::EPCGenericDylibManager::SymbolLookupCompleteFn = 
      unique_function&lt;void(Expected&lt;std::vector&lt;ExecutorSymbolDef&gt;&gt;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericdylibmanager-h">EPCGenericDylibManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### EPCGenericDylibManager() {#acc0bffae84f1dbeb0672b3fac437df97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::EPCGenericDylibManager::EPCGenericDylibManager (<a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> &amp; EPC, <a href="/web-llvm/docs/api/structs/llvm/orc/epcgenericdylibmanager/symboladdrs">SymbolAddrs</a> SAs)</td>
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

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericmemoryaccess">EPCGenericMemoryAccess</a> instance from a given set of function addrs.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericdylibmanager-h">EPCGenericDylibManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### lookup() {#a128bedb499eb1c68900d8dbec053b9f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; ExecutorSymbolDef &gt; &gt; llvm::orc::EPCGenericDylibManager::lookup (<a href="/web-llvm/docs/api/namespaces/llvm/orc/tpctypes/#a791ec0843cc10da4c64ae6d79f8381d8">tpctypes::DylibHandle</a> H, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a> &amp; Lookup)</td>
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

<p>Looks up symbols within the given dylib.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericdylibmanager-h">EPCGenericDylibManager.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86floatingpoint-cpp/#ac28513e2e067144d291d2d8f0301b61a">Lookup</a> and <a href="#a56d1a298963123bd7d97461aceb6d9c2">lookupAsync</a>.</p>

</div>
</div>

### lookup() {#a6adb2b787ab8da0a98dd6e385cd9f5b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; ExecutorSymbolDef &gt; &gt; llvm::orc::EPCGenericDylibManager::lookup (<a href="/web-llvm/docs/api/namespaces/llvm/orc/tpctypes/#a791ec0843cc10da4c64ae6d79f8381d8">tpctypes::DylibHandle</a> H, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a6ed8943340ff5fdbb423c5a9f55daf4c">RemoteSymbolLookupSet</a> &amp; Lookup)</td>
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

<p>Looks up symbols within the given dylib.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericdylibmanager-h">EPCGenericDylibManager.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86floatingpoint-cpp/#ac28513e2e067144d291d2d8f0301b61a">Lookup</a> and <a href="#a56d1a298963123bd7d97461aceb6d9c2">lookupAsync</a>.</p>

</div>
</div>

### lookupAsync() {#a56d1a298963123bd7d97461aceb6d9c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::EPCGenericDylibManager::lookupAsync (<a href="/web-llvm/docs/api/namespaces/llvm/orc/tpctypes/#a791ec0843cc10da4c64ae6d79f8381d8">tpctypes::DylibHandle</a> H, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a> &amp; Lookup, <a href="#ae63bfef8805adb7f9d0f399e7ec79828">SymbolLookupCompleteFn</a> Complete)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Looks up symbols within the given dylib.</p>

<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericdylibmanager-h">EPCGenericDylibManager.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericdylibmanager-cpp">EPCGenericDylibManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86floatingpoint-cpp/#ac28513e2e067144d291d2d8f0301b61a">Lookup</a>, <a href="#a56d1a298963123bd7d97461aceb6d9c2">lookupAsync</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>.</p>


<p>Referenced by <a href="#a6adb2b787ab8da0a98dd6e385cd9f5b9">lookup</a>, <a href="#a128bedb499eb1c68900d8dbec053b9f9">lookup</a>, <a href="#a65c75adf08e8934cebd374ceee8a6aad">lookupAsync</a>, <a href="#a56d1a298963123bd7d97461aceb6d9c2">lookupAsync</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7593114c182697759ffe3404df7df008">llvm::orc::lookupSymbolsAsyncHelper</a>.</p>

</div>
</div>

### lookupAsync() {#a65c75adf08e8934cebd374ceee8a6aad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::EPCGenericDylibManager::lookupAsync (<a href="/web-llvm/docs/api/namespaces/llvm/orc/tpctypes/#a791ec0843cc10da4c64ae6d79f8381d8">tpctypes::DylibHandle</a> H, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a6ed8943340ff5fdbb423c5a9f55daf4c">RemoteSymbolLookupSet</a> &amp; Lookup, <a href="#ae63bfef8805adb7f9d0f399e7ec79828">SymbolLookupCompleteFn</a> Complete)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Looks up symbols within the given dylib.</p>

<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericdylibmanager-h">EPCGenericDylibManager.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericdylibmanager-cpp">EPCGenericDylibManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86floatingpoint-cpp/#ac28513e2e067144d291d2d8f0301b61a">Lookup</a>, <a href="#a56d1a298963123bd7d97461aceb6d9c2">lookupAsync</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>.</p>

</div>
</div>

### open() {#aa8ff17813ed881db4af1f6ef52300519}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; tpctypes::DylibHandle &gt; llvm::orc::EPCGenericDylibManager::open (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path, uint64_t Mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Loads the dylib with the given name.</p>

<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericdylibmanager-h">EPCGenericDylibManager.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericdylibmanager-cpp">EPCGenericDylibManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a> and <a href="#aa8ff17813ed881db4af1f6ef52300519">open</a>.</p>


<p>Referenced by <a href="#aa8ff17813ed881db4af1f6ef52300519">open</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EPC {#a817191ca507daf681314075f294f7844}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorProcessControl&amp; llvm::orc::EPCGenericDylibManager::EPC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericdylibmanager-h">EPCGenericDylibManager.h</a>.</p>

</div>
</div>

### SAs {#a5481bfbca4be5ac5dc1678081293bb31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolAddrs llvm::orc::EPCGenericDylibManager::SAs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericdylibmanager-h">EPCGenericDylibManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### CreateWithDefaultBootstrapSymbols() {#a3f31d0ec435c55a5b3e976c20ea3bf6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; EPCGenericDylibManager &gt; llvm::orc::EPCGenericDylibManager::CreateWithDefaultBootstrapSymbols (<a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> &amp; EPC)</td>
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

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericmemoryaccess">EPCGenericMemoryAccess</a> instance from a given set of function addrs.</p>

<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericdylibmanager-h">EPCGenericDylibManager.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericdylibmanager-cpp">EPCGenericDylibManager.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcgenericdylibmanager-h">EPCGenericDylibManager.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericdylibmanager-cpp">EPCGenericDylibManager.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
