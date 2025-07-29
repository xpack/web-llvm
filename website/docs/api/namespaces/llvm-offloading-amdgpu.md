---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/offloading/amdgpu
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `amdgpu` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::offloading::amdgpu { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offloading/amdgpu/amdgpukernelmetadata">AMDGPUKernelMetaData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Struct for holding metadata related to <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> kernels, for more information about the metadata and its meaning see: <a href="https://llvm.org/docs/AMDGPUUsage.html#code-object-v3">https://llvm.org/docs/AMDGPUUsage.html#code-object-v3</a>. <a href="/web-llvm/docs/api/structs/llvm/offloading/amdgpu/amdgpukernelmetadata/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad772ba5923d08e11379f06cc8c3c5e4d">isImageCompatibleWithEnv</a> (StringRef ImageArch, uint32_t ImageFlags, StringRef EnvTargetID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if an image is compatible with current system's environment. <a href="#ad772ba5923d08e11379f06cc8c3c5e4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a658b1211d163ef9492d062d29de98201">getAMDGPUMetaDataFromImage</a> (MemoryBufferRef MemBuffer, StringMap&lt; AMDGPUKernelMetaData &gt; &amp;KernelInfoMap, uint16_t &amp;ELFABIVersion)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reads <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> specific metadata from the <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> file and propagates the KernelInfoMap. <a href="#a658b1211d163ef9492d062d29de98201">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### getAMDGPUMetaDataFromImage() {#a658b1211d163ef9492d062d29de98201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::offloading::amdgpu::getAMDGPUMetaDataFromImage (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> MemBuffer, <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/offloading/amdgpu/amdgpukernelmetadata">AMDGPUKernelMetaData</a> &gt; &amp; KernelInfoMap, uint16_t &amp; ELFABIVersion)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reads <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> specific metadata from the <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> file and propagates the KernelInfoMap.</p>

<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a>, definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/utility-cpp">Utility.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a0c43c56d0ce8c5e87d92506d7b567a5b">llvm::object::ELFFile&lt; ELF64LE &gt;::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4848e3ad29a6f6a8216e031204f636e9ab54026aa6391d97c62b4d249ee2bcf8d">llvm::ELF::EI_ABIVERSION</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a7301c8fd89ad0f595f4ce4609c872704">llvm::MemoryBufferRef::getBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a02cea47a954fd499a8dc8d80b75935ee">llvm::object::ELFFile&lt; ELFT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/anonymous-utility-cpp-/kernelinforeader/#a2e7ef51785127b89f264c8923c81d45d">anonymous{Utility.cpp}::KernelInfoReader::KernelInfoReader</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a54e0eb7b4c7bff44dd72334b6184a045">llvm::object::ELFFile&lt; ELFT &gt;::notes</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#ab64e03f049c8588f24e0ec69a568aef9">llvm::object::ELFFile&lt; ELFT &gt;::sections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcad8d748e7ddd6a4fa31b32710bdd5aae2">llvm::ELF::SHT_NOTE</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### isImageCompatibleWithEnv() {#ad772ba5923d08e11379f06cc8c3c5e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::offloading::amdgpu::isImageCompatibleWithEnv (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ImageArch, uint32_t ImageFlags, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> EnvTargetID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if an image is compatible with current system's environment.</p>


<p>The system environment is given as a 'target-id' which has the form:</p>


<p>&lt;target-id&gt; := &lt;processor&gt; ( ":" &lt;target-feature&gt; ( "+" | "-" ) )*</p>


<p>If a feature is not specific as '+' or '-' it is assumed to be in an 'any' and is compatible with either '+' or '-'. The HSA runtime returns this information using the target-id, while we use the <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> header to determine these features.</p>


<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a>, definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/utility-cpp">Utility.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a83a294111af6d4412163b209725ca556">llvm::StringRef::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbaebf04c1c314401947208295657d8e1a5">llvm::ELF::EF_AMDGPU_FEATURE_SRAMECC_ANY_V4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba44a0a7895447f3100cb32df252755962">llvm::ELF::EF_AMDGPU_FEATURE_SRAMECC_OFF_V4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbaf1be86f2b9736bc3605cc038ab121a03">llvm::ELF::EF_AMDGPU_FEATURE_SRAMECC_ON_V4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba167805eef92b6cdd6c37eca5ffa160d8">llvm::ELF::EF_AMDGPU_FEATURE_SRAMECC_UNSUPPORTED_V4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbaa9000224ab154ac4a26cdd8d3cd4128e">llvm::ELF::EF_AMDGPU_FEATURE_SRAMECC_V4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba0513967370ed5299596fcf4a7f64044f">llvm::ELF::EF_AMDGPU_FEATURE_XNACK_ANY_V4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba6a674f409073f063b14b6edaf4407ea7">llvm::ELF::EF_AMDGPU_FEATURE_XNACK_OFF_V4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bbaaa9b75bf71ae7571ff568d055f4f2736">llvm::ELF::EF_AMDGPU_FEATURE_XNACK_ON_V4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba45e1135509e667519e86c2f3a8f4cf86">llvm::ELF::EF_AMDGPU_FEATURE_XNACK_UNSUPPORTED_V4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a8c8b409421e57197b53fe880f51920bba86700e7fbfd4ee16e79a53491292ea61">llvm::ELF::EF_AMDGPU_FEATURE_XNACK_V4</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/offloading/utility-h">Utility.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/utility-cpp">Utility.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
