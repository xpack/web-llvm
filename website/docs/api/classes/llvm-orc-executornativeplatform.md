---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/executornativeplatform
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ExecutorNativePlatform` Class Reference

<p>Configure the <a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a> instance to use the ORC runtime and the detected native target for the executor. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::ExecutorNativePlatform { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">llvm/ExecutionEngine/Orc/LLJIT.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b99d889bc18b755711334b38d3fa07d">ExecutorNativePlatform</a> (std::string OrcRuntimePath)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set up using path to Orc runtime. <a href="#a9b99d889bc18b755711334b38d3fa07d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6112e947baaa04723e4fcf54b1732f0e">ExecutorNativePlatform</a> (std::unique_ptr&lt; MemoryBuffer &gt; OrcRuntimeMB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set up using the given memory buffer. <a href="#a6112e947baaa04723e4fcf54b1732f0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1baadbec01aced37be13a1b86c76397e">JITDylibSP</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1bd92add845031ceeaab24c2c25c275">operator()</a> (LLJIT &amp;J)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executornativeplatform">ExecutorNativePlatform</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a122e02b20677cd672dec07591ff4eeff">addVCRuntime</a> (std::string VCRuntimePath, bool StaticVCRuntime)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a path to the VC runtime. <a href="#a122e02b20677cd672dec07591ff4eeff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::variant&lt; std::string, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a511ee076f37947dab30c887159516b25">OrcRuntime</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::pair&lt; std::string, bool &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ad3a0c276c6d5e50103448745bb1fab">VCRuntime</a></td>
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

## Description {#details}

<p>Configure the <a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a> instance to use the ORC runtime and the detected native target for the executor.</p>

<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ExecutorNativePlatform() {#a9b99d889bc18b755711334b38d3fa07d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ExecutorNativePlatform::ExecutorNativePlatform (std::string OrcRuntimePath)</td>
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

<p>Set up using path to Orc runtime.</p>

<p>Definition at line 578 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="#a122e02b20677cd672dec07591ff4eeff">addVCRuntime</a>.</p>

</div>
</div>

### ExecutorNativePlatform() {#a6112e947baaa04723e4fcf54b1732f0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ExecutorNativePlatform::ExecutorNativePlatform (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; OrcRuntimeMB)</td>
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

<p>Set up using the given memory buffer.</p>

<p>Definition at line 582 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator()() {#aa1bd92add845031ceeaab24c2c25c275}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; JITDylibSP &gt; llvm::orc::ExecutorNativePlatform::operator() (<a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a> &amp; J)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 594 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>, definition at line 1128 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a6dfad3bd64c32a0f80f488fee7f637de">llvm::orc::JITDylib::addToLinkOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201aa943abc041caa1cc4c074bbf38b76267">llvm::Triple::COFF</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform/#a0ff140ec3eee8b9a860f3626b5640c04">llvm::orc::COFFPlatform::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform/#aa9a419d5abbdb82bc571c3867365716d">llvm::orc::ELFNixPlatform::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/machoplatform/#ad166f5736231229286c93cd8c6aa8b6d">llvm::orc::MachOPlatform::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator/#a6e910497d88200a16108f6849b074ab8">llvm::orc::StaticLibraryDefinitionGenerator::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#a6576b19a186104b0ee0d910ea472cab2">llvm::orc::ExecutionSession::createBareJITDylib</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a456b64e26b8bcdbd8294689615d8a055">llvm::Triple::ELF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab97c9dc8dec5b044b551639baf324053">llvm::errorOrToExpected</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#a94c1b4d9e95a5d56aa3659c9a92bd286">llvm::orc::LLJIT::getExecutionSession</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa98611beefe78f907beeee7305cc8174">llvm::MemoryBuffer::getFile</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#a2c595f2ceaeed6e7996a984dca44e2b7">llvm::orc::LLJIT::getObjLinkingLayer</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#a784ec48bdbb34855fde8f7585b00acfe">llvm::orc::LLJIT::getProcessSymbolsJITDylib</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#a67c6b2d9d2593a5231245f9055f126c1">llvm::orc::LLJIT::getTargetTriple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a2ed78f59e2d35011e1d1ed0ad96cf411">llvm::Triple::MachO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#a2ed4129361eccda71fea45447353df4a">llvm::orc::ExecutionSession::setPlatform</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#a04b302aa7a486cbfc0bc4f51c44ef5ae">llvm::orc::LLJIT::setPlatformSupport</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addVCRuntime() {#a122e02b20677cd672dec07591ff4eeff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorNativePlatform &amp; llvm::orc::ExecutorNativePlatform::addVCRuntime (std::string VCRuntimePath, bool StaticVCRuntime)</td>
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

<p>Add a path to the VC runtime.</p>

<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#a9b99d889bc18b755711334b38d3fa07d">ExecutorNativePlatform</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### OrcRuntime {#a511ee076f37947dab30c887159516b25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::variant&lt;std::string, std::unique_ptr&lt;MemoryBuffer&gt; &gt; llvm::orc::ExecutorNativePlatform::OrcRuntime</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>

</div>
</div>

### VCRuntime {#a9ad3a0c276c6d5e50103448745bb1fab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;std::pair&lt;std::string, bool&gt; &gt; llvm::orc::ExecutorNativePlatform::VCRuntime</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
