---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-bpfpreserveditype-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{BPFPreserveDIType.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{BPFPreserveDIType.cpp} { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72adf7d117af6ebe1a3aee68b6e3e782">BPFPreserveDITypeImpl</a> (Function &amp;F)</td>
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

### BPFPreserveDITypeImpl() {#a72adf7d117af6ebe1a3aee68b6e3e782}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{BPFPreserveDIType.cpp}::BPFPreserveDITypeImpl (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreserveditype-cpp">BPFPreserveDIType.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#af763d890b27bbeacc1b06636740de9a1">llvm::GlobalVariable::addAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799ad68d76b71372e215deecb4c8ed3270c2">llvm::BTF::BTF_TYPE_ID_LOCAL</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfcoresharedinfo/#afa46679f06848e221706a3421f6cb995afedcfc4d4b6376f695095aad3a363358">llvm::BPFCoreSharedInfo::BTF_TYPE_ID_LOCAL_RELOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/btf/#af0e0ebe9cc5df71a99c113f92f148799acbb290538d39cb27fb3cc388297b226b">llvm::BTF::BTF_TYPE_ID_REMOTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aa286a0f7f5d38488d593bb7ef0ba183e">llvm::BasicBlock::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfcoresharedinfo/#adee485b8d8a010d18877f5f41286b079">llvm::BPFCoreSharedInfo::insertPassThrough</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfcoresharedinfo/#afa46679f06848e221706a3421f6cb995a9062c35b270f617deb19f51a2850134d">llvm::BPFCoreSharedInfo::MAX_BTF_TYPE_ID_FLAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a338590123630c357df6340c38d066572">llvm::GlobalObject::setMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/bpfcoresharedinfo/#aa34216df2ec6cc3245ab11f1ac3775ed">llvm::BPFCoreSharedInfo::TypeIdAttr</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreserveditype-cpp">BPFPreserveDIType.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
