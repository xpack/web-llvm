---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `AArch64PointerAuth.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">llvm/CodeGen/Register.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/aarch64pauth">AArch64PAuth</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1916a718bc5fe45363e746d758e502f7">AUTH_CHECK_METHOD_CL_VALUES_COMMON</a>&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59266a5187cd295a5caa98592258a641">AUTH_CHECK_METHOD_CL_VALUES_LR</a>&nbsp;&nbsp;&nbsp;...</td>
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

## Macro Definitions

### AUTH\_CHECK\_METHOD\_CL\_VALUES\_COMMON {#a1916a718bc5fe45363e746d758e502f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define AUTH_CHECK_METHOD_CL_VALUES_COMMON&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h/#a187fd767976b311c09dff5e05ac0c1bc">clEnumValN</a>(<a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a8e64f5532820f43f01399ac8bb2ff3e9ac9d3e887722f2bc482bcca9d41c512af">AArch64PAuth::AuthCheckMethod::None</a>, "none",                      \
             "Do not check authenticated address"),                            \
      <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h/#a187fd767976b311c09dff5e05ac0c1bc">clEnumValN</a>(AArch64PAuth::AuthCheckMethod::DummyLoad, "load",             \
                 "Perform dummy <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumarklastscratchload-cpp/#a8a3fe89940744b94ffe5dacd6704c2be">load</a> from authenticated address"),             \
      <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h/#a187fd767976b311c09dff5e05ac0c1bc">clEnumValN</a>(                                                              \
          AArch64PAuth::AuthCheckMethod::HighBitsNoTBI, "high-bits-notbi",     \
          "Compare bits 62 and 61 of address (TBI should be disabled)"),       \
      clEnumValN(AArch64PAuth::AuthCheckMethod::XPAC, "xpac",                  \
                 "Compare with the result of XPAC (requires Armv8.3-a)")
</div>
</dd>
</dl>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-h">AArch64PointerAuth.h</a>.</p>

</div>
</div>

### AUTH\_CHECK\_METHOD\_CL\_VALUES\_LR {#a59266a5187cd295a5caa98592258a641}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define AUTH_CHECK_METHOD_CL_VALUES_LR&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">      <a href="#a1916a718bc5fe45363e746d758e502f7">AUTH_CHECK_METHOD_CL_VALUES_COMMON</a>,                                      \
      <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h/#a187fd767976b311c09dff5e05ac0c1bc">clEnumValN</a>(AArch64PAuth::AuthCheckMethod::XPACHint, "xpac-hint",         \
                 "Compare with the result of XPACLRI")
</div>
</dd>
</dl>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-h">AArch64PointerAuth.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
