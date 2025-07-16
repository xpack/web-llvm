---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `AMDGPULibCalls.cpp` File Reference

<p>This file does AMD library function optimizations. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpu-h">AMDGPU.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">llvm/Analysis/AssumptionCache.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributemask-h">llvm/IR/AttributeMask.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">llvm/IR/MDBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
#include &lt;cmath&gt;
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

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls">AMDGPULibCalls</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6401a89e23c7a457e1bfc7289dc90345">TableRef</a> = <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a> &gt;</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a23abf96a3a2a01343eea80f705cbe36b">CreateCallEx</a> (IRB &amp;B, FunctionCallee Callee, Value *Arg, const Twine &amp;Name="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2a74b4d421ef6b6d459480a8cc174645">CreateCallEx2</a> (IRB &amp;B, FunctionCallee Callee, Value *Arg1, Value *Arg2, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfa93be20aafc0740ce9e4d48640406c">getPownType</a> (FunctionType *FT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dbbc20ea13b965c7622e591e09113d8">HasNative</a> (AMDGPULibFunc::EFuncId id)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a6401a89e23c7a457e1bfc7289dc90345">TableRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a> (AMDGPULibFunc::EFuncId id)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66b370f607062909219c834ffca364dd">getVecSize</a> (const AMDGPULibFunc &amp;FInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static AMDGPULibFunc::EType</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b53d60342909a86b16824b265a29a4b">getArgType</a> (const AMDGPULibFunc &amp;FInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a035312f0450b07253231a7a9a7153b74">isKnownIntegral</a> (const Value *V, const DataLayout &amp;DL, FastMathFlags FMF)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a0fe8addf642e6ea7e18eac1159856b">EnablePreLink</a>("amdgpu-prelink", cl::desc("Enable pre-link mode optimizations"), cl::init(false), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/list">cl::list</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d374fe79be31cc3d1acd2a31a1ec01">UseNative</a>("amdgpu-use-native", cl::desc("Comma separated list of functions to replace with native, or all"), cl::CommaSeparated, cl::ValueOptional, cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a485a1af9146353e6ef251cfa44f19ebb">tbl_acos</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac2c900ab03a2e77364bebaae0567a5a">tbl_acosh</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bbd4dec56d1d11917fcd775f00430a0">tbl_acospi</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e22b4d9a459ab49c9f45590243423cc">tbl_asin</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ccd6c28dc46369bf80a034dd2a45fad">tbl_asinh</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a108f727742bcc3e5b6fbc403379cfc82">tbl_asinpi</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a820b2dce80eec642eba8da3cc0ea5b0f">tbl_atan</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a349bb0e3f56793141904c1a3b43f55bd">tbl_atanh</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac545c3b78483d21b8d21038f1698d195">tbl_atanpi</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab622ede28608256150b7145a0d8d1ee8">tbl_cbrt</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ad9fe04c360c6d787b80dfb4ca8d4ce">tbl_cos</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cf26f78ea7d450c740649838c482535">tbl_cosh</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a538b8ec430e2d6e803cc96140566774d">tbl_cospi</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af186e6038668ad764f408653c5282ab5">tbl_erfc</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae442a92763e717102aa1e51e3d38b387">tbl_erf</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5d72c4eecba0dfda21ef0722c43793d">tbl_exp</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8a898865d0d526876504c10d513f55d">tbl_exp2</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a236f89de2094d638988432d695939089">tbl_exp10</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cdb18d6a65c06d295102a9491506e38">tbl_expm1</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04136401fac85c56db62dd265e9ae9c5">tbl_log</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a849c7be8acb49b68ec7761835c307084">tbl_log2</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae833a822abdcd8f374ddaa7981a8eaeb">tbl_log10</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fedc0046f6da24ed45a39d22abe3388">tbl_rsqrt</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f0b2a48ceb84fd2fafda433fc3c522b">tbl_sin</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48125913441f8e891f6baa0b88fe37e5">tbl_sinh</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe3d03ac758bedd9da8bff78125fb218">tbl_sinpi</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a999479698290e297a1fe611710c7c8b7">tbl_sqrt</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52d3218a2cdf69a313aa12a363a3acad">tbl_tan</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af78cd85b6d53037cd89f8a9c921470a8">tbl_tanh</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a538e705d061f7e10b16014a106ef5dba">tbl_tanpi</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/tableentry">TableEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06e1ba4b579dbe07a541e578eff89b70">tbl_tgamma</a>[] = ...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"amdgpu-simplifylib"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac58cbaeae310f551049f77b7c098599e">MATH_PI</a>&nbsp;&nbsp;&nbsp;numbers::pi</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ee56816d83d03ce2644259a848f0ecb">MATH_E</a>&nbsp;&nbsp;&nbsp;numbers::e</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b5b2c5357942d9380b41e7d9327bf9f">MATH_SQRT2</a>&nbsp;&nbsp;&nbsp;numbers::sqrt2</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeed2b305e2dd34973b9778caf212e7b9">MATH_SQRT1_2</a>&nbsp;&nbsp;&nbsp;numbers::inv_sqrt2</td>
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

<p>This file does AMD library function optimizations.</p>

<div class="doxySectionDef">

## Typedefs

### TableRef {#a6401a89e23c7a457e1bfc7289dc90345}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using TableRef =  ArrayRef&lt;TableEntry&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### CreateCallEx() {#a23abf96a3a2a01343eea80f705cbe36b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * CreateCallEx (IRB &amp; B, <a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a> Callee, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Arg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### CreateCallEx2() {#a2a74b4d421ef6b6d459480a8cc174645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * CreateCallEx2 (IRB &amp; B, <a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a> Callee, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Arg1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Arg2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### getArgType() {#a0b53d60342909a86b16824b265a29a4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPULibFunc::EType getArgType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc">AMDGPULibFunc</a> &amp; FInfo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/amdgpulibfuncbase/param/#afe6aba5ea4aaeb77192a50982874a003">llvm::AMDGPULibFuncBase::Param::ArgType</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc/#ac5568354b42fe6522775d468164b379a">llvm::AMDGPULibFunc::getLeads</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#ab013e5e37e15eee5725a24b6a6df2416">llvm::AMDGPULibCalls::useNative</a>.</p>

</div>
</div>

### getOptTable() {#aa6775066b72a4aca1c78f5d73c4128c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TableRef getOptTable (AMDGPULibFunc::EFuncId id)</td>
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



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a64ebd7cb2e2ddbbe65bedc595ed505b9">llvm::AMDGPULibFuncBase::EI_ACOS</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a1fcbab56d02054f724d9e58c4c49f58b">llvm::AMDGPULibFuncBase::EI_ACOSH</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3acfab5cd81c45e0ec2185b36cb4ca0b88">llvm::AMDGPULibFuncBase::EI_ACOSPI</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3ab9167ecfbfdb3df233e4d5c55bb37c57">llvm::AMDGPULibFuncBase::EI_ASIN</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3abe8ff053ab125cc4349ac586b5424afb">llvm::AMDGPULibFuncBase::EI_ASINH</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3adc64d60bbd6e41f59736e2b8ee335366">llvm::AMDGPULibFuncBase::EI_ASINPI</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a03f7d754b99577d67a0cde1e78619e94">llvm::AMDGPULibFuncBase::EI_ATAN</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a52a876775e5291c599191a9071f11833">llvm::AMDGPULibFuncBase::EI_ATANH</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a7cbdaddf2fff263ffb500fa546dccdeb">llvm::AMDGPULibFuncBase::EI_ATANPI</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a2015aaaf552cf3eecd11ae9803cde39d">llvm::AMDGPULibFuncBase::EI_CBRT</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3adb71933f23940e062fc5a3eac31ccc11">llvm::AMDGPULibFuncBase::EI_COS</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3ab42c3fd0368ecc3c9cf55f26d4d12855">llvm::AMDGPULibFuncBase::EI_COSH</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a2c50d065aea9e2b8f146693bac7c26f7">llvm::AMDGPULibFuncBase::EI_COSPI</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a795f914e82976318f0fa415cd4859b0a">llvm::AMDGPULibFuncBase::EI_ERF</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a4494538ca2bb859cdb080fd90950dd3d">llvm::AMDGPULibFuncBase::EI_ERFC</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a2e987433a67ea17eda081f27ecd098db">llvm::AMDGPULibFuncBase::EI_EXP</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3acd876b65a7e15700fead4d4ba2426774">llvm::AMDGPULibFuncBase::EI_EXP10</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a49bd67da9ac6801dcfaa8ef97e2960d3">llvm::AMDGPULibFuncBase::EI_EXP2</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3addf1df6d45e3cb09c8e07b424c7d285c">llvm::AMDGPULibFuncBase::EI_EXPM1</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3ab5e69549fb42b96e18a69c438e1f9761">llvm::AMDGPULibFuncBase::EI_LOG</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a52a423fd81e8bb4925add23cb778498c">llvm::AMDGPULibFuncBase::EI_LOG10</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3afe8ecaad2f1178bc0a4f3e3ca266ec6d">llvm::AMDGPULibFuncBase::EI_LOG2</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a4882dda175b9e6246d5212c9a5cddb0c">llvm::AMDGPULibFuncBase::EI_NCOS</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a3e74573d665d2957769a7dd21d628978">llvm::AMDGPULibFuncBase::EI_NEXP2</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3ae0db9cb46ec4b65a52ad9dee0f16f926">llvm::AMDGPULibFuncBase::EI_NLOG2</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a6cdd0cf8a4be6b68e54e0399bf6fa7d5">llvm::AMDGPULibFuncBase::EI_NRSQRT</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a9c4c88a3c8b3c4f502153a61ddd736c1">llvm::AMDGPULibFuncBase::EI_NSIN</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3ac711cdac2769081a1445b8025ddef68a">llvm::AMDGPULibFuncBase::EI_NSQRT</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a443810632d10d7cbc053cca01af12d4b">llvm::AMDGPULibFuncBase::EI_RSQRT</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a9de3a011a924c901cd12142bf48a83ec">llvm::AMDGPULibFuncBase::EI_SIN</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3ab4b8bd994713d2024deb5d2a85d48464">llvm::AMDGPULibFuncBase::EI_SINH</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a8033a316d573e66e8a89ec903fa4b64b">llvm::AMDGPULibFuncBase::EI_SINPI</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a2d19318cd15f1d0bc987640a6545419a">llvm::AMDGPULibFuncBase::EI_SQRT</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3aa3b8c714bac2150cd9742ec5dbc5f936">llvm::AMDGPULibFuncBase::EI_TAN</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3ad2329b67e476dad41b495394d26fa26e">llvm::AMDGPULibFuncBase::EI_TANH</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a6d2eb151d08967da6807ca2f791aa282">llvm::AMDGPULibFuncBase::EI_TANPI</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a60e82d51f89b268d4a061d66ad0212a1">llvm::AMDGPULibFuncBase::EI_TGAMMA</a>, <a href="#a485a1af9146353e6ef251cfa44f19ebb">tbl_acos</a>, <a href="#aac2c900ab03a2e77364bebaae0567a5a">tbl_acosh</a>, <a href="#a8bbd4dec56d1d11917fcd775f00430a0">tbl_acospi</a>, <a href="#a3e22b4d9a459ab49c9f45590243423cc">tbl_asin</a>, <a href="#a9ccd6c28dc46369bf80a034dd2a45fad">tbl_asinh</a>, <a href="#a108f727742bcc3e5b6fbc403379cfc82">tbl_asinpi</a>, <a href="#a820b2dce80eec642eba8da3cc0ea5b0f">tbl_atan</a>, <a href="#a349bb0e3f56793141904c1a3b43f55bd">tbl_atanh</a>, <a href="#ac545c3b78483d21b8d21038f1698d195">tbl_atanpi</a>, <a href="#ab622ede28608256150b7145a0d8d1ee8">tbl_cbrt</a>, <a href="#a1ad9fe04c360c6d787b80dfb4ca8d4ce">tbl_cos</a>, <a href="#a3cf26f78ea7d450c740649838c482535">tbl_cosh</a>, <a href="#a538b8ec430e2d6e803cc96140566774d">tbl_cospi</a>, <a href="#ae442a92763e717102aa1e51e3d38b387">tbl_erf</a>, <a href="#af186e6038668ad764f408653c5282ab5">tbl_erfc</a>, <a href="#ab5d72c4eecba0dfda21ef0722c43793d">tbl_exp</a>, <a href="#a236f89de2094d638988432d695939089">tbl_exp10</a>, <a href="#af8a898865d0d526876504c10d513f55d">tbl_exp2</a>, <a href="#a0cdb18d6a65c06d295102a9491506e38">tbl_expm1</a>, <a href="#a04136401fac85c56db62dd265e9ae9c5">tbl_log</a>, <a href="#ae833a822abdcd8f374ddaa7981a8eaeb">tbl_log10</a>, <a href="#a849c7be8acb49b68ec7761835c307084">tbl_log2</a>, <a href="#a2fedc0046f6da24ed45a39d22abe3388">tbl_rsqrt</a>, <a href="#a7f0b2a48ceb84fd2fafda433fc3c522b">tbl_sin</a>, <a href="#a48125913441f8e891f6baa0b88fe37e5">tbl_sinh</a>, <a href="#abe3d03ac758bedd9da8bff78125fb218">tbl_sinpi</a>, <a href="#a999479698290e297a1fe611710c7c8b7">tbl_sqrt</a>, <a href="#a52d3218a2cdf69a313aa12a363a3acad">tbl_tan</a>, <a href="#af78cd85b6d53037cd89f8a9c921470a8">tbl_tanh</a>, <a href="#a538e705d061f7e10b16014a106ef5dba">tbl_tanpi</a> and <a href="#a06e1ba4b579dbe07a541e578eff89b70">tbl_tgamma</a>.</p>

</div>
</div>

### getPownType() {#adfa93be20aafc0740ce9e4d48640406c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType * getPownType (<a href="/web-llvm/docs/api/classes/functiontype">FunctionType</a> * FT)</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#a615317b48f533b3087abb06d3a96319c">llvm::AMDGPULibCalls::fold</a>.</p>

</div>
</div>

### getVecSize() {#a66b370f607062909219c834ffca364dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getVecSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc">AMDGPULibFunc</a> &amp; FInfo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc/#ac5568354b42fe6522775d468164b379a">llvm::AMDGPULibFunc::getLeads</a> and <a href="/web-llvm/docs/api/structs/llvm/amdgpulibfuncbase/param/#a469fe9010014da053431ef7376268c47">llvm::AMDGPULibFuncBase::Param::VectorSize</a>.</p>

</div>
</div>

### HasNative() {#a5dbbc20ea13b965c7622e591e09113d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HasNative (AMDGPULibFunc::EFuncId id)</td>
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



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3adb71933f23940e062fc5a3eac31ccc11">llvm::AMDGPULibFuncBase::EI_COS</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3ab5b311e12c491b514bb13be4a1fb4f7e">llvm::AMDGPULibFuncBase::EI_DIVIDE</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a2e987433a67ea17eda081f27ecd098db">llvm::AMDGPULibFuncBase::EI_EXP</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3acd876b65a7e15700fead4d4ba2426774">llvm::AMDGPULibFuncBase::EI_EXP10</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a49bd67da9ac6801dcfaa8ef97e2960d3">llvm::AMDGPULibFuncBase::EI_EXP2</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3ab5e69549fb42b96e18a69c438e1f9761">llvm::AMDGPULibFuncBase::EI_LOG</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a52a423fd81e8bb4925add23cb778498c">llvm::AMDGPULibFuncBase::EI_LOG10</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3afe8ecaad2f1178bc0a4f3e3ca266ec6d">llvm::AMDGPULibFuncBase::EI_LOG2</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a890b3d788fc247f94186955daaedaa12">llvm::AMDGPULibFuncBase::EI_POWR</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3af47c7744369abb31a2f95599e6d32164">llvm::AMDGPULibFuncBase::EI_RECIP</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a443810632d10d7cbc053cca01af12d4b">llvm::AMDGPULibFuncBase::EI_RSQRT</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a9de3a011a924c901cd12142bf48a83ec">llvm::AMDGPULibFuncBase::EI_SIN</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a19916d6858eb73c5cafdadb79ebde8ed">llvm::AMDGPULibFuncBase::EI_SINCOS</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3a2d19318cd15f1d0bc987640a6545419a">llvm::AMDGPULibFuncBase::EI_SQRT</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncbase/#a1142b2c02ac329c588bf4726b61f98d3aa3b8c714bac2150cd9742ec5dbc5f936">llvm::AMDGPULibFuncBase::EI_TAN</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#ab013e5e37e15eee5725a24b6a6df2416">llvm::AMDGPULibCalls::useNative</a>.</p>

</div>
</div>

### isKnownIntegral() {#a035312f0450b07253231a7a9a7153b74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isKnownIntegral (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF)</td>
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



<p>Definition at line 576 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#acd530d0571f320d47d37e7ae51cf70ff">llvm::Constant::getAggregateElement</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac62778065b99372cc62cf994b967e7e8">llvm::CallBase::getIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a1ab411da4fddde73bec70fd45762f2ad">llvm::ConstantFP::getValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ace4517dbbab7dbdefa0d31e29db55969">llvm::APFloat::isInteger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a24b69550d2c0e2d57f3886757ac41567">llvm::isKnownNeverInfinity</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a42c8f0b3d870c96030032b8ed8a2a1e3">llvm::isKnownNeverInfOrNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a39b529fcda9ee90b17a3e1fed732a22a">llvm::FastMathFlags::noInfs</a> and <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ac1d140361490d7847edf0c7503e3188a">llvm::FastMathFlags::noNaNs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#a615317b48f533b3087abb06d3a96319c">llvm::AMDGPULibCalls::fold</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### EnablePreLink {#a5a0fe8addf642e6ea7e18eac1159856b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnablePreLink("amdgpu-prelink", cl::desc("Enable pre-link mode optimizations"), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### tbl\_acos {#a485a1af9146353e6ef251cfa44f19ebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_acos[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {<a href="#ac58cbaeae310f551049f77b7c098599e">MATH_PI</a> / 2.0, 0.0},
  {<a href="#ac58cbaeae310f551049f77b7c098599e">MATH_PI</a> / 2.0, -0.0},
  {0.0, 1.0},
  {<a href="#ac58cbaeae310f551049f77b7c098599e">MATH_PI</a>, -1.0}
}
</div>
</dd>
</dl>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_acosh {#aac2c900ab03a2e77364bebaae0567a5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_acosh[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {0.0, 1.0}
}
</div>
</dd>
</dl>

<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_acospi {#a8bbd4dec56d1d11917fcd775f00430a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_acospi[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {0.5, 0.0},
  {0.5, -0.0},
  {0.0, 1.0},
  {1.0, -1.0}
}
</div>
</dd>
</dl>

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_asin {#a3e22b4d9a459ab49c9f45590243423cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_asin[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {0.0, 0.0},
  {-0.0, -0.0},
  {<a href="#ac58cbaeae310f551049f77b7c098599e">MATH_PI</a> / 2.0, 1.0},
  {-<a href="#ac58cbaeae310f551049f77b7c098599e">MATH_PI</a> / 2.0, -1.0}
}
</div>
</dd>
</dl>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_asinh {#a9ccd6c28dc46369bf80a034dd2a45fad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_asinh[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {0.0, 0.0},
  {-0.0, -0.0}
}
</div>
</dd>
</dl>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_asinpi {#a108f727742bcc3e5b6fbc403379cfc82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_asinpi[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {0.0, 0.0},
  {-0.0, -0.0},
  {0.5, 1.0},
  {-0.5, -1.0}
}
</div>
</dd>
</dl>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_atan {#a820b2dce80eec642eba8da3cc0ea5b0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_atan[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {0.0, 0.0},
  {-0.0, -0.0},
  {<a href="#ac58cbaeae310f551049f77b7c098599e">MATH_PI</a> / 4.0, 1.0},
  {-<a href="#ac58cbaeae310f551049f77b7c098599e">MATH_PI</a> / 4.0, -1.0}
}
</div>
</dd>
</dl>

<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_atanh {#a349bb0e3f56793141904c1a3b43f55bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_atanh[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {0.0, 0.0},
  {-0.0, -0.0}
}
</div>
</dd>
</dl>

<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_atanpi {#ac545c3b78483d21b8d21038f1698d195}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_atanpi[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {0.0, 0.0},
  {-0.0, -0.0},
  {0.25, 1.0},
  {-0.25, -1.0}
}
</div>
</dd>
</dl>

<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_cbrt {#ab622ede28608256150b7145a0d8d1ee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_cbrt[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {0.0, 0.0},
  {-0.0, -0.0},
  {1.0, 1.0},
  {-1.0, -1.0},
}
</div>
</dd>
</dl>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_cos {#a1ad9fe04c360c6d787b80dfb4ca8d4ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_cos[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {1.0, 0.0},
  {1.0, -0.0}
}
</div>
</dd>
</dl>

<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_cosh {#a3cf26f78ea7d450c740649838c482535}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_cosh[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {1.0, 0.0},
  {1.0, -0.0}
}
</div>
</dd>
</dl>

<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_cospi {#a538b8ec430e2d6e803cc96140566774d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_cospi[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {1.0, 0.0},
  {1.0, -0.0}
}
</div>
</dd>
</dl>

<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_erf {#ae442a92763e717102aa1e51e3d38b387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_erf[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {0.0, 0.0},
  {-0.0, -0.0}
}
</div>
</dd>
</dl>

<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_erfc {#af186e6038668ad764f408653c5282ab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_erfc[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {1.0, 0.0},
  {1.0, -0.0}
}
</div>
</dd>
</dl>

<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_exp {#ab5d72c4eecba0dfda21ef0722c43793d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_exp[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {1.0, 0.0},
  {1.0, -0.0},
  {<a href="#a9ee56816d83d03ce2644259a848f0ecb">MATH_E</a>, 1.0}
}
</div>
</dd>
</dl>

<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_exp10 {#a236f89de2094d638988432d695939089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_exp10[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {1.0, 0.0},
  {1.0, -0.0},
  {10.0, 1.0}
}
</div>
</dd>
</dl>

<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_exp2 {#af8a898865d0d526876504c10d513f55d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_exp2[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {1.0, 0.0},
  {1.0, -0.0},
  {2.0, 1.0}
}
</div>
</dd>
</dl>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_expm1 {#a0cdb18d6a65c06d295102a9491506e38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_expm1[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {0.0, 0.0},
  {-0.0, -0.0}
}
</div>
</dd>
</dl>

<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_log {#a04136401fac85c56db62dd265e9ae9c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_log[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {0.0, 1.0},
  {1.0, <a href="#a9ee56816d83d03ce2644259a848f0ecb">MATH_E</a>}
}
</div>
</dd>
</dl>

<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_log10 {#ae833a822abdcd8f374ddaa7981a8eaeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_log10[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {0.0, 1.0},
  {1.0, 10.0}
}
</div>
</dd>
</dl>

<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_log2 {#a849c7be8acb49b68ec7761835c307084}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_log2[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {0.0, 1.0},
  {1.0, 2.0}
}
</div>
</dd>
</dl>

<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_rsqrt {#a2fedc0046f6da24ed45a39d22abe3388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_rsqrt[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {1.0, 1.0},
  {<a href="#aeed2b305e2dd34973b9778caf212e7b9">MATH_SQRT1_2</a>, 2.0}
}
</div>
</dd>
</dl>

<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_sin {#a7f0b2a48ceb84fd2fafda433fc3c522b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_sin[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {0.0, 0.0},
  {-0.0, -0.0}
}
</div>
</dd>
</dl>

<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_sinh {#a48125913441f8e891f6baa0b88fe37e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_sinh[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {0.0, 0.0},
  {-0.0, -0.0}
}
</div>
</dd>
</dl>

<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_sinpi {#abe3d03ac758bedd9da8bff78125fb218}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_sinpi[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {0.0, 0.0},
  {-0.0, -0.0}
}
</div>
</dd>
</dl>

<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_sqrt {#a999479698290e297a1fe611710c7c8b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_sqrt[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {0.0, 0.0},
  {1.0, 1.0},
  {<a href="#a1b5b2c5357942d9380b41e7d9327bf9f">MATH_SQRT2</a>, 2.0}
}
</div>
</dd>
</dl>

<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_tan {#a52d3218a2cdf69a313aa12a363a3acad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_tan[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {0.0, 0.0},
  {-0.0, -0.0}
}
</div>
</dd>
</dl>

<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_tanh {#af78cd85b6d53037cd89f8a9c921470a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_tanh[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {0.0, 0.0},
  {-0.0, -0.0}
}
</div>
</dd>
</dl>

<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_tanpi {#a538e705d061f7e10b16014a106ef5dba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_tanpi[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {0.0, 0.0},
  {-0.0, -0.0}
}
</div>
</dd>
</dl>

<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### tbl\_tgamma {#a06e1ba4b579dbe07a541e578eff89b70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TableEntry tbl_tgamma[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {1.0, 1.0},
  {1.0, 2.0},
  {2.0, 3.0},
  {6.0, 4.0}
}
</div>
</dd>
</dl>

<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="#aa6775066b72a4aca1c78f5d73c4128c7">getOptTable</a>.</p>

</div>
</div>

### UseNative {#af1d374fe79be31cc3d1acd2a31a1ec01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::list&lt; std::string &gt; UseNative("amdgpu-use-native", cl::desc("Comma separated list of functions to replace with native, or all"), cl::CommaSeparated, cl::ValueOptional, cl::Hidden)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#a64b1fc9079cbd516aa873d15359a0c0b">llvm::AMDGPULibCalls::initNativeFuncs</a> and <a href="/web-llvm/docs/api/structs/llvm/amdgpuusenativecallspass/#a153430907ef218b9118d28f077a5dd78">llvm::AMDGPUUseNativeCallsPass::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"amdgpu-simplifylib"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### MATH\_E {#a9ee56816d83d03ce2644259a848f0ecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MATH_E&nbsp;&nbsp;&nbsp;numbers::e</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### MATH\_PI {#ac58cbaeae310f551049f77b7c098599e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MATH_PI&nbsp;&nbsp;&nbsp;numbers::pi</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### MATH\_SQRT1\_2 {#aeed2b305e2dd34973b9778caf212e7b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MATH_SQRT1_2&nbsp;&nbsp;&nbsp;numbers::inv_sqrt2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

### MATH\_SQRT2 {#a1b5b2c5357942d9380b41e7d9327bf9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MATH_SQRT2&nbsp;&nbsp;&nbsp;numbers::sqrt2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp">AMDGPULibCalls.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
