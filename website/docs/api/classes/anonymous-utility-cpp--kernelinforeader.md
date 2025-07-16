---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-utility-cpp-/kernelinforeader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `KernelInfoReader` Class Reference

<p>Reads the <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> specific per-kernel-metadata from an image. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{Utility.cpp}::KernelInfoReader { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e7ef51785127b89f264c8923c81d45d">KernelInfoReader</a> (StringMap&lt; offloading::amdgpu::AMDGPUKernelMetaData &gt; &amp;KIM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4be56491fd1f1bfc2d12285da64e4a0">processNote</a> (const llvm::object::ELF64LE::Note &amp;Note, size_t Align)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> note to read <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> metadata from respective information fields. <a href="#aa4be56491fd1f1bfc2d12285da64e4a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbfe23e498fbf73f022a4281f8524bc2">extractKernelData</a> (msgpack::MapDocNode::MapTy::value_type V, std::string &amp;KernelName, offloading::amdgpu::AMDGPUKernelMetaData &amp;KernelData)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extracts the relevant information via simple string look-up in the msgpack document elements. <a href="#abbfe23e498fbf73f022a4281f8524bc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode">msgpack::ArrayDocNode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bddcf78bc905500ed64ac0619ebc223">getAMDKernelsArray</a> (msgpack::MapDocNode &amp;MDN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the "amdhsa.kernels" element from the msgpack Document. <a href="#a3bddcf78bc905500ed64ac0619ebc223">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56554a0db1e46b99da92d4efa062a9f1">generateKernelInfo</a> (msgpack::ArrayDocNode::ArrayTy::iterator It)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterate all entries for one "amdhsa.kernels" entry. <a href="#a56554a0db1e46b99da92d4efa062a9f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a122f09000a0a375d0f3bc7e2d2444863">iterateAMDKernels</a> (msgpack::MapDocNode &amp;MDN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Go over the list of AMD kernels in the "amdhsa.kernels" entry. <a href="#a122f09000a0a375d0f3bc7e2d2444863">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/offloading/amdgpu/amdgpukernelmetadata">offloading::amdgpu::AMDGPUKernelMetaData</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a10b548792511a9d6eb2090524dc8a3">KernelInfoMap</a></td>
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

<p>Reads the <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> specific per-kernel-metadata from an image.</p>

<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/utility-cpp">Utility.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### KernelInfoReader() {#a2e7ef51785127b89f264c8923c81d45d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{Utility.cpp}::KernelInfoReader::KernelInfoReader (<a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/offloading/amdgpu/amdgpukernelmetadata">offloading::amdgpu::AMDGPUKernelMetaData</a> &gt; &amp; KIM)</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/utility-cpp">Utility.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/offloading/amdgpu/#a658b1211d163ef9492d062d29de98201">llvm::offloading::amdgpu::getAMDGPUMetaDataFromImage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### processNote() {#aa4be56491fd1f1bfc2d12285da64e4a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{Utility.cpp}::KernelInfoReader::processNote (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/elftype/#a0c579a13ebb15ab832f64a5ad5809ded">llvm::object::ELF64LE::Note</a> &amp; Note, size_t Align)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> note to read <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> metadata from respective information fields.</p>

<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/utility-cpp">Utility.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a01acd23f4e4e583c9eaf2c03923b157e">llvm::msgpack::DocNode::getMap</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a5deadb4fe33da953cf16a27551f02c3c">llvm::msgpack::Document::getRoot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a3b0649c72650c313a357338dcdfb64ec">llvm::Note</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ae01999f6bb8613fd9cad067b9e8e83b4acd3865a0ae5a4a85ae17d89a549267d3">llvm::ELF::NT_AMDGPU_METADATA</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#aa1132fee67332a4c0a707984b97f9b52">llvm::msgpack::Document::readFromBlob</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ae91b89e3dbb8e36d143a6efcc4d5d85a">Verifier</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### extractKernelData() {#abbfe23e498fbf73f022a4281f8524bc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{Utility.cpp}::KernelInfoReader::extractKernelData (msgpack::MapDocNode::MapTy::value_type V, std::string &amp; KernelName, <a href="/web-llvm/docs/api/structs/llvm/offloading/amdgpu/amdgpukernelmetadata">offloading::amdgpu::AMDGPUKernelMetaData</a> &amp; KernelData)</td>
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

<p>Extracts the relevant information via simple string look-up in the msgpack document elements.</p>

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/utility-cpp">Utility.cpp</a>.</p>

</div>
</div>

### generateKernelInfo() {#a56554a0db1e46b99da92d4efa062a9f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{Utility.cpp}::KernelInfoReader::generateKernelInfo (msgpack::ArrayDocNode::ArrayTy::iterator It)</td>
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

<p>Iterate all entries for one "amdhsa.kernels" entry.</p>


<p>Each entry is a MapDocNode that either maps a string to a single value (most of them) or to another array of things. Currently, we only handle the case that maps to scalar value.</p>


<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/utility-cpp">Utility.cpp</a>.</p>

</div>
</div>

### getAMDKernelsArray() {#a3bddcf78bc905500ed64ac0619ebc223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; msgpack::ArrayDocNode &gt; anonymous{Utility.cpp}::KernelInfoReader::getAMDKernelsArray (<a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">msgpack::MapDocNode</a> &amp; MDN)</td>
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

<p>Get the "amdhsa.kernels" element from the msgpack Document.</p>

<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/utility-cpp">Utility.cpp</a>.</p>

</div>
</div>

### iterateAMDKernels() {#a122f09000a0a375d0f3bc7e2d2444863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{Utility.cpp}::KernelInfoReader::iterateAMDKernels (<a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">msgpack::MapDocNode</a> &amp; MDN)</td>
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

<p>Go over the list of AMD kernels in the "amdhsa.kernels" entry.</p>

<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/utility-cpp">Utility.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### KernelInfoMap {#a8a10b548792511a9d6eb2090524dc8a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;offloading::amdgpu::AMDGPUKernelMetaData&gt;&amp; anonymous{Utility.cpp}::KernelInfoReader::KernelInfoMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/utility-cpp">Utility.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/offloading/utility-cpp">Utility.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
