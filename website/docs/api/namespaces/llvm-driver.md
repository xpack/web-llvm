---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/driver
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `driver` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::driver { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">VectorLibrary { <a href="#ad1483d70be7c201f82a09cc21f32f137">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vector library option used with -fveclib=. <a href="#ad1483d70be7c201f82a09cc21f32f137">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl">TargetLibraryInfoImpl</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaa83953f1c661c7a3bc7a4af4dc1efe">createTLII</a> (llvm::Triple &amp;TargetTriple, VectorLibrary Veclib)</td>
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

## Enumerations

### VectorLibrary {#ad1483d70be7c201f82a09cc21f32f137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::driver::VectorLibrary </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vector library option used with -fveclib=.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoLibrary<a id="ad1483d70be7c201f82a09cc21f32f137afaf85532d0280f7de22c86f7ab33c0fb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Accelerate<a id="ad1483d70be7c201f82a09cc21f32f137aa552e259a7aec237bbe28b9039dc3395"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LIBMVEC<a id="ad1483d70be7c201f82a09cc21f32f137a1c69b37e2b39b5efffd3e4244814f7c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MASSV<a id="ad1483d70be7c201f82a09cc21f32f137ac8a4351c5c244975ee5499a621cbd79d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SVML<a id="ad1483d70be7c201f82a09cc21f32f137a666e9059fe14dd5cd7d49e297f04de32"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SLEEF<a id="ad1483d70be7c201f82a09cc21f32f137ac31d91e07927b16a8ab888b63dd3d70c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Darwin_libsystem_m<a id="ad1483d70be7c201f82a09cc21f32f137a2f6ebc82487a76f0a553e17d6ca412f2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ArmPL<a id="ad1483d70be7c201f82a09cc21f32f137a7dca4066ea4d931cda62d43e92dce943"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMDLIBM<a id="ad1483d70be7c201f82a09cc21f32f137a997cde549e09094090517f3e84215dcb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/driver/codegenoptions-h">CodeGenOptions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### createTLII() {#aeaa83953f1c661c7a3bc7a4af4dc1efe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfoImpl * llvm::driver::createTLII (<a href="/web-llvm/docs/api/classes/llvm/triple">llvm::Triple</a> &amp; TargetTriple, <a href="#ad1483d70be7c201f82a09cc21f32f137">VectorLibrary</a> Veclib)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 15 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/driver/codegenoptions-cpp">CodeGenOptions.cpp</a>.</p>


<p>References <a href="#ad1483d70be7c201f82a09cc21f32f137aa552e259a7aec237bbe28b9039dc3395">Accelerate</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#abec3cb7868d54c3e24de1dcbc499ffd0af076d4474d59ab5a0efc86d94870f2e5">llvm::TargetLibraryInfoImpl::Accelerate</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a32cf61958e13a95aaf8686f4c55aa873">llvm::TargetLibraryInfoImpl::addVectorizableFunctionsFromVecLib</a>, <a href="#ad1483d70be7c201f82a09cc21f32f137a997cde549e09094090517f3e84215dcb">AMDLIBM</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#abec3cb7868d54c3e24de1dcbc499ffd0aaad66d544007471f9a5cc933ac94ecd1">llvm::TargetLibraryInfoImpl::AMDLIBM</a>, <a href="#ad1483d70be7c201f82a09cc21f32f137a7dca4066ea4d931cda62d43e92dce943">ArmPL</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#abec3cb7868d54c3e24de1dcbc499ffd0aed2d4462f0f3887fee4fa6d184e0901b">llvm::TargetLibraryInfoImpl::ArmPL</a>, <a href="#ad1483d70be7c201f82a09cc21f32f137a2f6ebc82487a76f0a553e17d6ca412f2">Darwin_libsystem_m</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#abec3cb7868d54c3e24de1dcbc499ffd0a61ca8404d1203f719cd0f48109c529e5">llvm::TargetLibraryInfoImpl::DarwinLibSystemM</a>, <a href="#ad1483d70be7c201f82a09cc21f32f137a1c69b37e2b39b5efffd3e4244814f7c1">LIBMVEC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#abec3cb7868d54c3e24de1dcbc499ffd0ab0e4293663c61c643b1851edb142bbf1">llvm::TargetLibraryInfoImpl::LIBMVEC_X86</a>, <a href="#ad1483d70be7c201f82a09cc21f32f137ac8a4351c5c244975ee5499a621cbd79d">MASSV</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#abec3cb7868d54c3e24de1dcbc499ffd0a4992d44d29a3636609efced57fd02704">llvm::TargetLibraryInfoImpl::MASSV</a>, <a href="#ad1483d70be7c201f82a09cc21f32f137ac31d91e07927b16a8ab888b63dd3d70c">SLEEF</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#abec3cb7868d54c3e24de1dcbc499ffd0a7d7e07bb2e6138ddac20854c146d4945">llvm::TargetLibraryInfoImpl::SLEEFGNUABI</a>, <a href="#ad1483d70be7c201f82a09cc21f32f137a666e9059fe14dd5cd7d49e297f04de32">SVML</a> and <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#abec3cb7868d54c3e24de1dcbc499ffd0a6377df1b30e0cfcaced5ebafa0d2d0ac">llvm::TargetLibraryInfoImpl::SVML</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/driver/codegenoptions-h">CodeGenOptions.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/driver/codegenoptions-cpp">CodeGenOptions.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
