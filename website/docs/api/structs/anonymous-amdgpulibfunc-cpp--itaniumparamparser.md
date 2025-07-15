---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-amdgpulibfunc-cpp-/itaniumparamparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ItaniumParamParser` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{AMDGPULibFunc.cpp}::ItaniumParamParser { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa21569cfdba76deadeb40added273001">parseItaniumParam</a> (StringRef &amp;param, AMDGPULibFunc::Param &amp;res)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">AMDGPULibFunc::Param</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a5149869148ed6da1b347b5c128226f">Prev</a></td>
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


<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp">AMDGPULibFunc.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### parseItaniumParam() {#aa21569cfdba76deadeb40added273001}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ItaniumParamParser::parseItaniumParam (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; param, AMDGPULibFunc::Param &amp; res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp">AMDGPULibFunc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/amdgpulibfuncbase/param/#afe6aba5ea4aaeb77192a50982874a003">llvm::AMDGPULibFuncBase::Param::ArgType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#aac00986b9c47fed034287e1eeb01a141ace38fa4a412a5fe40cde9a544b2e64f3">llvm::AMDGPULibFuncBase::BYVALUE</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#aac00986b9c47fed034287e1eeb01a141ab71327ef08041a654a35def14111691c">llvm::AMDGPULibFuncBase::CONST</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulibfunc-cpp-/#af1d0120f54489e515264a9ed0668ce9a">anonymous{AMDGPULibFunc.cpp}::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a3bcd722d2d045ca33574c1cd0a1ea34d">llvm::AMDGPULibFuncBase::DUMMY</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulibfunc-cpp-/#a5d574989dd4688949082681ec54010f6">anonymous{AMDGPULibFunc.cpp}::eatLengthPrefixedName</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulibfunc-cpp-/#ab3836b4bb1237941003273adb235b8e2">anonymous{AMDGPULibFunc.cpp}::eatNumber</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulibfunc-cpp-/#a41c1d2d1393c23d25c9cc13f39ca6742">anonymous{AMDGPULibFunc.cpp}::eatTerm</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8af91b4c3fb5deff779fa5884c0d521278">llvm::AMDGPULibFuncBase::F16</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8af5e427970dc9c29ec50cb3f39fbcf774">llvm::AMDGPULibFuncBase::F32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a06c2414f8276b0025f4057efce9bc562">llvm::AMDGPULibFuncBase::F64</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a61364ca3a5ff90fb2aa0d5a371fd43f7">llvm::StringRef::front</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a234ff52a2593b9d0f6fbd4d8aee25d11">llvm::AMDGPULibFuncBase::getEPtrKindFromAddrSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a3a5514459881fc9d2444d6ac8a18a8c2">llvm::AMDGPULibFuncBase::I16</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a8039c0339aea621d2589419bc0c7ffdf">llvm::AMDGPULibFuncBase::I32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8aaeb097d554a6e77e61dd1dc797ea062f">llvm::AMDGPULibFuncBase::I64</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8ad0af55ef4d18b5452d50afa947f2f150">llvm::AMDGPULibFuncBase::I8</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a2d2bd20792beb08e2871525ff0bd61bd">llvm::AMDGPULibFuncBase::IMG1D</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8aa4a0749682012c0c912a6c67faac089f">llvm::AMDGPULibFuncBase::IMG1DA</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8acdc53f4dbf399c54a795dcd836b085b4">llvm::AMDGPULibFuncBase::IMG1DB</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a678e88a9aa9bd4cecb5a9a75f11e0b2a">llvm::AMDGPULibFuncBase::IMG2D</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8acbd1cf99158a98160aeba7a1e350ed80">llvm::AMDGPULibFuncBase::IMG2DA</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8ad6ca04175915d03dee3f3d3d2669dfd7">llvm::AMDGPULibFuncBase::IMG3D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a82c27bc751f7669f9c2a79de96e2d0fd">llvm::isDigit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp/#ac7b4b404af5f382847f4d289c5579a39">parseVecSize</a>, <a href="#a9a5149869148ed6da1b347b5c128226f">Prev</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpulibfuncbase/param/#a909a7690a970a0c70d7c3ff1a2df63b0">llvm::AMDGPULibFuncBase::Param::PtrKind</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpulibfuncbase/param/#a0cb34f43d41245b5146fe08697283cea">llvm::AMDGPULibFuncBase::Param::reset</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a88e653a89d15149cc7a68f88be360303">llvm::StringSwitch&lt; T, R &gt;::StartsWith</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a76424308db519548eaeda3655a288bc4">llvm::AMDGPULibFuncBase::U16</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a3e402cd027c568fa43f4b554c0b348b6">llvm::AMDGPULibFuncBase::U32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8a8c6c6342eca81ee6609a590cdc4fcad6">llvm::AMDGPULibFuncBase::U64</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a858436a6ac3e32480363df7ec66765a8ae8baa7f9c7af35b4306f6d225214404e">llvm::AMDGPULibFuncBase::U8</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpulibfuncbase/param/#a469fe9010014da053431ef7376268c47">llvm::AMDGPULibFuncBase::Param::VectorSize</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#aac00986b9c47fed034287e1eeb01a141a6987d7ee902a05bb1ede8f10f5956ba7">llvm::AMDGPULibFuncBase::VOLATILE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Prev {#a9a5149869148ed6da1b347b5c128226f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPULibFunc::Param anonymous{AMDGPULibFunc.cpp}::ItaniumParamParser::Prev</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp">AMDGPULibFunc.cpp</a>.</p>


<p>Referenced by <a href="#aa21569cfdba76deadeb40added273001">parseItaniumParam</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp">AMDGPULibFunc.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
