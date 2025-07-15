---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-epcindirectionutils-cpp-/epcindirectstubsmanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `EPCIndirectStubsManager` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{EPCIndirectionUtils.cpp}::EPCIndirectStubsManager { ... }
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/indirectstubsmanager">IndirectStubsManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for managing collections of named indirect stubs. <a href="/web-llvm/docs/api/classes/llvm/orc/indirectstubsmanager/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutilsaccess">EPCIndirectionUtilsAccess</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9d85a37b3cf7d44cfae7688770b0947">StubInfo</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutilsaccess/#a04570231559936d47595b1b4375a1879">IndirectStubInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06ba35ca8c01e741624c593b07476fdc">EPCIndirectStubsManager</a> (EPCIndirectionUtils &amp;EPCIU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a21e8ed1dbd249208ad0310dd1d6fe6">deallocateStubs</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fa20132257f02c9809c2d401731be3e">createStub</a> (StringRef StubName, ExecutorAddr StubAddr, JITSymbolFlags StubFlags) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a single stub with the given name, target address and flags. <a href="#a2fa20132257f02c9809c2d401731be3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a199b61ddf7d2eb6a93f8a41d61e41647">createStubs</a> (const StubInitsMap &amp;StubInits) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create StubInits.size() stubs with the given names, target addresses, and flags. <a href="#a199b61ddf7d2eb6a93f8a41d61e41647">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbbf0bb58c1dbed2bb7b9eee52d0bfbc">findStub</a> (StringRef Name, bool ExportedStubsOnly) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the stub with the given name. <a href="#acbbf0bb58c1dbed2bb7b9eee52d0bfbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67bc9859f43b7ba60c4e438102776c0a">findPointer</a> (StringRef Name) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the implementation-pointer for the stub. <a href="#a67bc9859f43b7ba60c4e438102776c0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bac8d07501a16b2f372dea7bb937675">updatePointer</a> (StringRef Name, ExecutorAddr NewAddr) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change the value of the implementation pointer for the stub. <a href="#a6bac8d07501a16b2f372dea7bb937675">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b76add05675736b8df6e2889f1d703f">ISMMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutils">EPCIndirectionUtils</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a697097312a1841eebc21dba1045bb661">EPCIU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; StubInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5e5fc00885fc883003309a4e96d1e2b">StubInfos</a></td>
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


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### StubInfo {#ac9d85a37b3cf7d44cfae7688770b0947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{EPCIndirectionUtils.cpp}::EPCIndirectStubsManager::StubInfo =  std::pair&lt;IndirectStubInfo, JITSymbolFlags&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### EPCIndirectStubsManager() {#a06ba35ca8c01e741624c593b07476fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{EPCIndirectionUtils.cpp}::EPCIndirectStubsManager::EPCIndirectStubsManager (<a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutils">EPCIndirectionUtils</a> &amp; EPCIU)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createStub() {#a2fa20132257f02c9809c2d401731be3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{EPCIndirectionUtils.cpp}::EPCIndirectStubsManager::createStub (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> StubName, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> StubAddr, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> StubFlags)</td>
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

<p>Create a single stub with the given name, target address and flags.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<p>Reference <a href="#a199b61ddf7d2eb6a93f8a41d61e41647">createStubs</a>.</p>


<p>Referenced by <a href="#a4a21e8ed1dbd249208ad0310dd1d6fe6">deallocateStubs</a>.</p>

</div>
</div>

### createStubs() {#a199b61ddf7d2eb6a93f8a41d61e41647}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{EPCIndirectionUtils.cpp}::EPCIndirectStubsManager::createStubs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/indirectstubsmanager/#a35f44bbbe3455bcfcd356050360da658">StubInitsMap</a> &amp; StubInits)</td>
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

<p>Create StubInits.size() stubs with the given names, target addresses, and flags.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutilsaccess/#a149dbb627bef5934546b4d8cade41078">llvm::orc::EPCIndirectionUtilsAccess::getIndirectStubs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/classes/llvm/stringmapimpl/#a80596ea56fa14ea5a773d303ee64293c">llvm::StringMapImpl::size</a>.</p>


<p>Referenced by <a href="#a2fa20132257f02c9809c2d401731be3e">createStub</a> and <a href="#a4a21e8ed1dbd249208ad0310dd1d6fe6">deallocateStubs</a>.</p>

</div>
</div>

### deallocateStubs() {#a4a21e8ed1dbd249208ad0310dd1d6fe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{EPCIndirectionUtils.cpp}::EPCIndirectStubsManager::deallocateStubs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<p>References <a href="#a2fa20132257f02c9809c2d401731be3e">createStub</a>, <a href="#a199b61ddf7d2eb6a93f8a41d61e41647">createStubs</a>, <a href="#a67bc9859f43b7ba60c4e438102776c0a">findPointer</a>, <a href="#acbbf0bb58c1dbed2bb7b9eee52d0bfbc">findStub</a> and <a href="#a6bac8d07501a16b2f372dea7bb937675">updatePointer</a>.</p>

</div>
</div>

### findPointer() {#a67bc9859f43b7ba60c4e438102776c0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorSymbolDef anonymous{EPCIndirectionUtils.cpp}::EPCIndirectStubsManager::findPointer (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Find the implementation-pointer for the stub.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a4a21e8ed1dbd249208ad0310dd1d6fe6">deallocateStubs</a>.</p>

</div>
</div>

### findStub() {#acbbf0bb58c1dbed2bb7b9eee52d0bfbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorSymbolDef anonymous{EPCIndirectionUtils.cpp}::EPCIndirectStubsManager::findStub (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool ExportedStubsOnly)</td>
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

<p>Find the stub with the given name.</p>


<p>If ExportedStubsOnly is true, this will only return a result if the stub's flags indicate that it is exported.</p>


<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a4a21e8ed1dbd249208ad0310dd1d6fe6">deallocateStubs</a>.</p>

</div>
</div>

### updatePointer() {#a6bac8d07501a16b2f372dea7bb937675}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{EPCIndirectionUtils.cpp}::EPCIndirectStubsManager::updatePointer (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> NewAddr)</td>
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

<p>Change the value of the implementation pointer for the stub.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#a4ee908fb9052f020e3c50e3f1a7d81c5">llvm::orc::ExecutorAddr::getValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>.</p>


<p>Referenced by <a href="#a4a21e8ed1dbd249208ad0310dd1d6fe6">deallocateStubs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EPCIU {#a697097312a1841eebc21dba1045bb661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EPCIndirectionUtils&amp; anonymous{EPCIndirectionUtils.cpp}::EPCIndirectStubsManager::EPCIU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>

</div>
</div>

### ISMMutex {#a4b76add05675736b8df6e2889f1d703f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex anonymous{EPCIndirectionUtils.cpp}::EPCIndirectStubsManager::ISMMutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>

</div>
</div>

### StubInfos {#ae5e5fc00885fc883003309a4e96d1e2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;StubInfo&gt; anonymous{EPCIndirectionUtils.cpp}::EPCIndirectStubsManager::StubInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
