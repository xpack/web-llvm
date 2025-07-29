---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-amdgpuunifymetadata-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{AMDGPUUnifyMetadata.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{AMDGPUUnifyMetadata.cpp} { ... }
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuunifymetadata-cpp-/koclmd">kOCLMD</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifymetadata-cpp-/amdgpuunifymetadata">AMDGPUUnifyMetadata</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unify multiple OpenCL metadata due to linking. <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifymetadata-cpp-/amdgpuunifymetadata/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42808949a508a2f6e635b6ae584adcd5">unifyVersionMD</a> (Module &amp;M, StringRef Name, bool PickFirst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unify version metadata. <a href="#a42808949a508a2f6e635b6ae584adcd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe1326abb7803c9088d08b7348c8b5e6">unifyExtensionMD</a> (Module &amp;M, StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unify version metadata. <a href="#afe1326abb7803c9088d08b7348c8b5e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c3148760d2e3e57a1eeefdefba4a574">unifyMetadataImpl</a> (Module &amp;M)</td>
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


<div class="doxySectionDef">

## Functions

### unifyExtensionMD() {#afe1326abb7803c9088d08b7348c8b5e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUUnifyMetadata.cpp}::unifyExtensionMD (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unify version metadata.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if changes are made. Assume the named metadata has operands each of which is a list e.g. !Name = {!n1, !n2} !n1 = !{!"cl_khr_fp16", {!"cl_khr_fp64"}} !n2 = !{!"cl_khr_image"} Combine it into a single list with unique operands.</p></dd>
</dl>


<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuunifymetadata-cpp">AMDGPUUnifyMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27ab1c94ca2fbc3e78fc30069c8d0f01680">llvm::All</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>


<p>Referenced by <a href="#a0c3148760d2e3e57a1eeefdefba4a574">unifyMetadataImpl</a>.</p>

</div>
</div>

### unifyMetadataImpl() {#a0c3148760d2e3e57a1eeefdefba4a574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUUnifyMetadata.cpp}::unifyMetadataImpl (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuunifymetadata-cpp">AMDGPUUnifyMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuunifymetadata-cpp-/koclmd/#a7b13ffc4f9ce44bd46177b1402e2bad3">anonymous{AMDGPUUnifyMetadata.cpp}::kOCLMD::CompilerOptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuunifymetadata-cpp-/koclmd/#a20434ac3c8d4c8653aa86f9b0ba22205">anonymous{AMDGPUUnifyMetadata.cpp}::kOCLMD::LLVMIdent</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuunifymetadata-cpp-/koclmd/#a58ee873753d9be926610869bdb372789">anonymous{AMDGPUUnifyMetadata.cpp}::kOCLMD::OCLVer</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuunifymetadata-cpp-/koclmd/#a2cd3612dc08a1e821886207ac1c8b11a">anonymous{AMDGPUUnifyMetadata.cpp}::kOCLMD::SpirVer</a>, <a href="#afe1326abb7803c9088d08b7348c8b5e6">unifyExtensionMD</a>, <a href="#a42808949a508a2f6e635b6ae584adcd5">unifyVersionMD</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuunifymetadata-cpp-/koclmd/#a9218d0e3dcce571246846d808c7999d7">anonymous{AMDGPUUnifyMetadata.cpp}::kOCLMD::UsedExt</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuunifymetadata-cpp-/koclmd/#a6e7a391c6e7b866fcfd8f2857abff41e">anonymous{AMDGPUUnifyMetadata.cpp}::kOCLMD::UsedOptCoreFeat</a>.</p>

</div>
</div>

### unifyVersionMD() {#a42808949a508a2f6e635b6ae584adcd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUUnifyMetadata.cpp}::unifyVersionMD (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool PickFirst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unify version metadata.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if changes are made. Assume the named metadata has operands each of which is a pair of integer constant, e.g. !Name = {!n1, !n2} !n1 = {i32 1, i32 2} !n2 = {i32 2, i32 0} Keep the largest version as the sole operand if PickFirst is false. Otherwise pick it from the first value, representing kernel module.</p></dd>
</dl>


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuunifymetadata-cpp">AMDGPUUnifyMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a>.</p>


<p>Referenced by <a href="#a0c3148760d2e3e57a1eeefdefba4a574">unifyMetadataImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuunifymetadata-cpp">AMDGPUUnifyMetadata.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
