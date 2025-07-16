---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/targetlibraryinfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `TargetLibraryInfo.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include "llvm/Analysis/TargetLibraryInfo.def"
#include "llvm/Analysis/VecFuncs.def"
</div>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::array&lt; <a href="#aca185e6d0e9f423dbb24440206454872">FuncArgTypeID</a>, 8 &gt; <a href="#ae1a3328bb21843e9ed20b54a8105937c">FuncProtoTy</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FuncArgTypeID : char { <a href="#aca185e6d0e9f423dbb24440206454872">...</a> }</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a022ce4695b2561ef81ae09fe93dbc742">hasSinCosPiStret</a> (const Triple &amp;T)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e7e340b15b3028c40f6fc8de267004d">hasBcmp</a> (const Triple &amp;TT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99b2775600f9f190f98b0f08f36870b3">isCallingConvCCompatible</a> (CallingConv::ID CC, StringRef TT, FunctionType *FuncTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a641b5e25f1fd3d03c418a5a2aefd4b55">initializeBase</a> (TargetLibraryInfoImpl &amp;TLI, const Triple &amp;T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a201c313701e8c03b7fd137205154ce37">initializeLibCalls</a> (TargetLibraryInfoImpl &amp;TLI, const Triple &amp;T, ArrayRef&lt; StringLiteral &gt; StandardNames)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the set of available library functions based on the specified target triple. <a href="#a201c313701e8c03b7fd137205154ce37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19d27915595e7f0a0ef271448bcdac6f">initialize</a> (TargetLibraryInfoImpl &amp;TLI, const Triple &amp;T, ArrayRef&lt; StringLiteral &gt; StandardNames)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the set of available library functions based on the specified target triple. <a href="#a19d27915595e7f0a0ef271448bcdac6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a147437aa3b97e99609ae28aa1ee2eb32">sanitizeFunctionName</a> (StringRef funcName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa528cdb113dc770c1c34b1fa22a43eb">buildIndexMap</a> (ArrayRef&lt; StringLiteral &gt; StandardNames)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c31886b94c082d37269155b9186a3cf">matchType</a> (FuncArgTypeID ArgTy, const Type *Ty, unsigned IntBits, unsigned SizeTBits)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb3e0c28998ff9684b75e9efa0697919">isValidProtoForSizeReturningNew</a> (const FunctionType &amp;FTy, LibFunc F, const Module &amp;M, int SizeTSizeBits)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79b4e70735dd5b20124a6e2deb08554e">compareByScalarFnName</a> (const VecDesc &amp;LHS, const VecDesc &amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86bd45de852039d3b7488453d737364a">compareByVectorFnName</a> (const VecDesc &amp;LHS, const VecDesc &amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea274b410e29fa114414f15aed1b6126">compareWithScalarFnName</a> (const VecDesc &amp;LHS, StringRef S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#abec3cb7868d54c3e24de1dcbc499ffd0">TargetLibraryInfoImpl::VectorLibrary</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0906a1189434b7f140fb9439faf7dd0">ClVectorLibrary</a>("vector-library", cl::Hidden, cl::desc("Vector functions library"), cl::init(TargetLibraryInfoImpl::NoLibrary), cl::values(clEnumValN(TargetLibraryInfoImpl::NoLibrary, "none", "No vector functions library"), clEnumValN(TargetLibraryInfoImpl::Accelerate, "Accelerate", "Accelerate framework"), clEnumValN(TargetLibraryInfoImpl::DarwinLibSystemM, "Darwin_libsystem_m", "Darwin libsystem_m"), clEnumValN(TargetLibraryInfoImpl::LIBMVEC_X86, "LIBMVEC-X86", "GLIBC Vector Math library"), clEnumValN(TargetLibraryInfoImpl::MASSV, "MASSV", "IBM MASS vector library"), clEnumValN(TargetLibraryInfoImpl::SVML, "SVML", "Intel SVML library"), clEnumValN(TargetLibraryInfoImpl::SLEEFGNUABI, "sleefgnuabi", "SIMD Library for Evaluating Elementary Functions"), clEnumValN(TargetLibraryInfoImpl::ArmPL, "ArmPL", "Arm Performance Libraries"), clEnumValN(TargetLibraryInfoImpl::AMDLIBM, "AMDLIBM", "AMD vector math library")))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae1a3328bb21843e9ed20b54a8105937c">FuncProtoTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8efadc1e398432637936757b43272daa">Signatures</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af17c5f2cd95fecfd78453bb3d6105cfd">VecFuncs_Accelerate</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acad27f01498f4940adaf11039f80f736">VecFuncs_DarwinLibSystemM</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac144d58061674e2d303867113dc0f6a2">VecFuncs_LIBMVEC_X86</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c23ee38c4d1bd844c40c2629913419c">VecFuncs_MASSV</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbccc26273cd15a1fa46a10b67064498">VecFuncs_SVML</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5598458647d40357efc9e50b0394a93a">VecFuncs_SLEEFGNUABI_VF2</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87860e9e51aaa5d9b98b584128651616">VecFuncs_SLEEFGNUABI_VF4</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae80d5658c79a70f7f7798946340a1f29">VecFuncs_SLEEFGNUABI_VFScalable</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8f742526c2732949ecec896c0137123">VecFuncs_SLEEFGNUABI_VFScalableRISCV</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99f444f3a78984f61a904239bcca012b">VecFuncs_ArmPL</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8f604cc3655a0f11ecdd458b39f089a">VecFuncs_AMDLIBM</a>[] = ...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a970358d390596d6015cd0eae4228a062">TLI_DEFINE_STRING</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71bfd683f3fa071bdbde88307b2faff2">TLI_DEFINE_SIG</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e47abd6e31beb69bf0464343c39d727">TLI_DEFINE_ACCELERATE_VECFUNCS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4754a4f26e7b5261aea4edadf1d0380e">TLI_DEFINE_DARWIN_LIBSYSTEM_M_VECFUNCS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7db04c63adc1ea109aa4405161eb7e43">TLI_DEFINE_LIBMVEC_X86_VECFUNCS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec25928b70c7b655c9be05fda9e315e5">TLI_DEFINE_MASSV_VECFUNCS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a87f8d3f987be5d3a4f4629719a995e">TLI_DEFINE_SVML_VECFUNCS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa7e1fe59190525ca9495bf266da93f3">TLI_DEFINE_SLEEFGNUABI_VF2_VECFUNCS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad39d0066ff9816ac402a679d98b9a594">TLI_DEFINE_VECFUNC</a>(SCAL, VEC, VF, VABI_PREFIX)&nbsp;&nbsp;&nbsp;  {SCAL, VEC, VF, /* MASK = */ false, VABI_PREFIX},</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5d390b6073c799f532281a7154c716b">TLI_DEFINE_SLEEFGNUABI_VF4_VECFUNCS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab01ee1383c0a3968f4b3d41d5a10606b">TLI_DEFINE_VECFUNC</a>(SCAL, VEC, VF, VABI_PREFIX)&nbsp;&nbsp;&nbsp;  {SCAL, VEC, VF, /* MASK = */ false, VABI_PREFIX},</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c1abea970981b9315fa7673b9ee57cd">TLI_DEFINE_SLEEFGNUABI_SCALABLE_VECFUNCS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc0d1d89ba91c0e0531b9812bcce33a9">TLI_DEFINE_VECFUNC</a>(SCAL, VEC, VF, MASK, VABI_PREFIX)&nbsp;&nbsp;&nbsp;  {SCAL, VEC, VF, MASK, VABI_PREFIX},</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d9c16c2ac21e542ce1d8b7cd46e3df6">TLI_DEFINE_SLEEFGNUABI_SCALABLE_VECFUNCS_RISCV</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1fc126e9bcb8562837692c1af096aa4">TLI_DEFINE_VECFUNC</a>(SCAL, VEC, VF, MASK, VABI_PREFIX)&nbsp;&nbsp;&nbsp;  {SCAL, VEC, VF, MASK, VABI_PREFIX},</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab30a212811774a2406505b3ed7eac897">TLI_DEFINE_ARMPL_VECFUNCS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9645087b4aafa578c73788b0cec4046">TLI_DEFINE_VECFUNC</a>(SCAL, VEC, VF, MASK, VABI_PREFIX)&nbsp;&nbsp;&nbsp;  {SCAL, VEC, VF, MASK, VABI_PREFIX},</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fe47ca8f81b812b5067c3818f1afda8">TLI_DEFINE_AMDLIBM_VECFUNCS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a248ada79cca5079ac31930b344b3faa3">TLI_DEFINE_VECFUNC</a>(SCAL, VEC, VF, MASK, VABI_PREFIX)&nbsp;&nbsp;&nbsp;  {SCAL, VEC, VF, MASK, VABI_PREFIX},</td>
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

## Typedefs

### FuncProtoTy {#ae1a3328bb21843e9ed20b54a8105937c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::array&lt;FuncArgTypeID, 8&gt; FuncProtoTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### FuncArgTypeID {#aca185e6d0e9f423dbb24440206454872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum FuncArgTypeID : char</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Void<a id="aca185e6d0e9f423dbb24440206454872a8ce14d8b0fc90289ee23848f6de11c47"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Bool<a id="aca185e6d0e9f423dbb24440206454872a29dcc89db32a1eead61fe67cff38c060"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Int16<a id="aca185e6d0e9f423dbb24440206454872a150558aeaa819431aeb9729d26b2ac9f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Int32<a id="aca185e6d0e9f423dbb24440206454872a788a72ddbf1bd572b3fcd7a5e7ec8cff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Int<a id="aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IntPlus<a id="aca185e6d0e9f423dbb24440206454872a3bbd27529d01e024c526896dcd5f6a5e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Long<a id="aca185e6d0e9f423dbb24440206454872afbe5087b942deaaa3202c7ca87dbc327"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IntX<a id="aca185e6d0e9f423dbb24440206454872a52fc06c8638074204be3a7f9a35d65b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Int64<a id="aca185e6d0e9f423dbb24440206454872ada475947399b8ab4d13d40fea50f950c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLong<a id="aca185e6d0e9f423dbb24440206454872a9cec0e2f2afd661509a20c3cf054abda"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SizeT<a id="aca185e6d0e9f423dbb24440206454872a9db720c78340455edd11227589989ea2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSizeT<a id="aca185e6d0e9f423dbb24440206454872a8388b5a41ed174169eea5ef989712695"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Flt<a id="aca185e6d0e9f423dbb24440206454872a11534cddb9d36ce7b049eefacc295a96"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Dbl<a id="aca185e6d0e9f423dbb24440206454872a79e4ec69e83555caf8889be4fad6d361"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LDbl<a id="aca185e6d0e9f423dbb24440206454872aba2f71e41b94b5fc82ea91e5335a264a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Floating<a id="aca185e6d0e9f423dbb24440206454872a4815677a428e37e90c6f71f94ddd7b65"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Ptr<a id="aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Struct<a id="aca185e6d0e9f423dbb24440206454872a763a932e166ac85a6d2d1606e8649993"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Ellip<a id="aca185e6d0e9f423dbb24440206454872a6cfc5007f8bf84204e051b3c79815b0f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Same<a id="aca185e6d0e9f423dbb24440206454872a0e0d4848f799861d016ae63c8fdc41e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### buildIndexMap() {#afa528cdb113dc770c1c34b1fa22a43eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt; StringRef, LibFunc &gt; buildIndexMap (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> &gt; StandardNames)</td>
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



<p>Definition at line 995 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154ea389502cf750cbd7c05b635f4c76855ee">llvm::NumLibFuncs</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#ae292a4b96e7f74eb95a4176ddba7b821">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::reserve</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a0f382b34dc924b235282157869cb3771">llvm::TargetLibraryInfoImpl::getLibFunc</a>.</p>

</div>
</div>

### compareByScalarFnName() {#a79b4e70735dd5b20124a6e2deb08554e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool compareByScalarFnName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a> &amp; RHS)</td>
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



<p>Definition at line 1256 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a48a7797f18b04db2cf63dfb1c2bdbea4">llvm::TargetLibraryInfoImpl::addVectorizableFunctions</a>.</p>

</div>
</div>

### compareByVectorFnName() {#a86bd45de852039d3b7488453d737364a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool compareByVectorFnName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a> &amp; RHS)</td>
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



<p>Definition at line 1260 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a48a7797f18b04db2cf63dfb1c2bdbea4">llvm::TargetLibraryInfoImpl::addVectorizableFunctions</a>.</p>

</div>
</div>

### compareWithScalarFnName() {#aea274b410e29fa114414f15aed1b6126}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool compareWithScalarFnName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vecdesc">VecDesc</a> &amp; LHS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
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



<p>Definition at line 1264 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a4c36c8f36fd0fe73e2936da5f1479691">llvm::TargetLibraryInfoImpl::getVectorMappingInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a15113486c66611b76318afc2c37352c3">llvm::TargetLibraryInfoImpl::getWidestVF</a> and <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a798028b6fc917a63c65f97cb29ab6b69">llvm::TargetLibraryInfoImpl::isFunctionVectorizable</a>.</p>

</div>
</div>

### hasBcmp() {#a3e7e340b15b3028c40f6fc8de267004d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasBcmp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Referenced by <a href="#a201c313701e8c03b7fd137205154ce37">initializeLibCalls</a>.</p>

</div>
</div>

### hasSinCosPiStret() {#a022ce4695b2561ef81ae09fe93dbc742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasSinCosPiStret (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">llvm::Triple::x86</a>.</p>


<p>Referenced by <a href="#a201c313701e8c03b7fd137205154ce37">initializeLibCalls</a>.</p>

</div>
</div>

### initialize() {#a19d27915595e7f0a0ef271448bcdac6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void initialize (<a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl">TargetLibraryInfoImpl</a> &amp; TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> &gt; StandardNames)</td>
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

<p>Initialize the set of available library functions based on the specified target triple.</p>


<p>This should be carefully written so that a missing target triple gets a sane set of defaults.</p>


<p>Definition at line 917 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="#a641b5e25f1fd3d03c418a5a2aefd4b55">initializeBase</a>, <a href="#a201c313701e8c03b7fd137205154ce37">initializeLibCalls</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-codelayout-cpp-/cdsortimpl/#a68a9823d565755fe71d5a54fb0262947">anonymous{CodeLayout.cpp}::CDSortImpl::CDSortImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-codelayout-cpp-/exttspimpl/#a47333daefb26df0fb055e84fc9a77d9d">anonymous{CodeLayout.cpp}::ExtTSPImpl::ExtTSPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/oprofilewrapper/#a8b250a24143710b280bb480210a31bcf">llvm::OProfileWrapper::op_close_agent</a>, <a href="/web-llvm/docs/api/classes/llvm/oprofilewrapper/#ad73d8440953a2a32714c7e99151b5cc9">llvm::OProfileWrapper::op_major_version</a>, <a href="/web-llvm/docs/api/classes/llvm/oprofilewrapper/#ad56a244a605b066fd37756f8bcf5e2f9">llvm::OProfileWrapper::op_minor_version</a>, <a href="/web-llvm/docs/api/classes/llvm/oprofilewrapper/#a5429b9da01b158fac3e5da48a72010bc">llvm::OProfileWrapper::op_open_agent</a>, <a href="/web-llvm/docs/api/classes/llvm/oprofilewrapper/#a6dbe6059e3d02647966bd2e6e54a9aba">llvm::OProfileWrapper::op_unload_native_code</a>, <a href="/web-llvm/docs/api/classes/llvm/oprofilewrapper/#abf54432b7e558fe9cc479ce12abfa249">llvm::OProfileWrapper::op_write_debug_line_info</a>, <a href="/web-llvm/docs/api/classes/llvm/oprofilewrapper/#a24f0da9d90ea20da52b527394d248aab">llvm::OProfileWrapper::op_write_native_code</a>, <a href="/web-llvm/docs/api/classes/anonymous-oprofilejiteventlistener-cpp-/oprofilejiteventlistener/#a3ef5532a760aeae0c1cb85bf461b0a1f">anonymous{OProfileJITEventListener.cpp}::OProfileJITEventListener::OProfileJITEventListener</a>, <a href="/web-llvm/docs/api/structs/anonymous-bpfmichecking-cpp-/bpfmipreemitchecking/#a0be432668109bc140ae58cd602fe5f42">anonymous{BPFMIChecking.cpp}::BPFMIPreEmitChecking::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-bpfmipeephole-cpp-/bpfmipeephole/#a0bf22c66fb6d17415d1306b6eda5c9b2">anonymous{BPFMIPeephole.cpp}::BPFMIPeephole::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-bpfmipeephole-cpp-/bpfmipreemitpeephole/#addcc5b382526d54ff85515e6b9951e05">anonymous{BPFMIPeephole.cpp}::BPFMIPreEmitPeephole::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-bpfmisimplifypatchable-cpp-/bpfmisimplifypatchable/#aa6b6aa1082626484a5ca6d0084b4a94f">anonymous{BPFMISimplifyPatchable.cpp}::BPFMISimplifyPatchable::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcmipeephole-cpp-/ppcmipeephole/#a835b87b88f0868fb797ae3d27da54081">anonymous{PPCMIPeephole.cpp}::PPCMIPeephole::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcreducecrlogicals-cpp-/ppcreducecrlogicals/#a6bec670bfb8a6c8cc0cc29c248ed8a54">anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxswapremoval-cpp-/ppcvsxswapremoval/#a9ddff289404aac49861d6bacccbbb057">anonymous{PPCVSXSwapRemoval.cpp}::PPCVSXSwapRemoval::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-threadsanitizer-cpp-/threadsanitizer/#a41fe353d57c56ba3f43b66143ff436b0">anonymous{ThreadSanitizer.cpp}::ThreadSanitizer::sanitizeFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-siannotatecontrolflow-cpp-/siannotatecontrolflow/#a06730d3cea389903a2ddb36a9afac5fe">anonymous{SIAnnotateControlFlow.cpp}::SIAnnotateControlFlow::SIAnnotateControlFlow</a> and <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a2039d7fdda0459345ad2b721b0045e6c">llvm::TargetLibraryInfoImpl::TargetLibraryInfoImpl</a>.</p>

</div>
</div>

### initializeBase() {#a641b5e25f1fd3d03c418a5a2aefd4b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void initializeBase (<a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl">TargetLibraryInfoImpl</a> &amp; TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#abbec53ddcfefcaaecad3227ecf1335e9">llvm::TargetLibraryInfo::initExtensionsForTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a364eae125640314f23d8c74bebc87062">llvm::TargetLibraryInfoImpl::setIntSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a0af42e0d2f497ae6b8a119353cda2045">llvm::TargetLibraryInfoImpl::setShouldExtI32Param</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a0c0279b5745ccf4a95fde99be709cdf9">llvm::TargetLibraryInfoImpl::setShouldExtI32Return</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a22e9150ba078ca50c2abde31e5f73a09">llvm::TargetLibraryInfoImpl::setShouldSignExtI32Param</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a871062b7cfb1949703c308ae3ec0da76">llvm::TargetLibraryInfoImpl::setShouldSignExtI32Return</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a19d27915595e7f0a0ef271448bcdac6f">initialize</a> and <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a0a808f8afa53cb0a981fb9e6bec75fb4">llvm::TargetLibraryInfoImpl::TargetLibraryInfoImpl</a>.</p>

</div>
</div>

### initializeLibCalls() {#a201c313701e8c03b7fd137205154ce37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void initializeLibCalls (<a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl">TargetLibraryInfoImpl</a> &amp; TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> &gt; StandardNames)</td>
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

<p>Initialize the set of available library functions based on the specified target triple.</p>


<p>This should be carefully written so that a missing target triple gets a sane set of defaults.</p>


<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a32cf61958e13a95aaf8686f4c55aa873">llvm::TargetLibraryInfoImpl::addVectorizableFunctionsFromVecLib</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">llvm::Triple::arm</a>, <a href="#ae0906a1189434b7f140fb9439faf7dd0">ClVectorLibrary</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda0824a8c56de913d60c6f55edc0ac3148">llvm::Triple::Darwin</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a9a288c0a7ef4bdf0b93570ca74fe9557">llvm::TargetLibraryInfoImpl::disableAllFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdae7c70b9eb6106c04f131eca1e3be44ac">llvm::Triple::Emscripten</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda64fc6929b84f845ced55d3313ebcf423">llvm::Triple::FreeBSD</a>, <a href="#a3e7e340b15b3028c40f6fc8de267004d">hasBcmp</a>, <a href="#a022ce4695b2561ef81ae09fe93dbc742">hasSinCosPiStret</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdafad6e6763679be1478d9283a7344d243">llvm::Triple::IOS</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda76d4dd8dc67e3a11d975743f6d63a9df">llvm::Triple::Linux</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda690ddf3bb28281cc7afa9c7de4ff4075">llvm::Triple::MacOSX</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#affe6e31638cfdceea39f7057043c22fc">llvm::TargetLibraryInfoImpl::setAvailable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a27e3c60feefa1643f8c8dafe485a1e1f">llvm::TargetLibraryInfoImpl::setAvailableWithName</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#ae6596de0b1e303f7ba18ddc0f779ddbf">llvm::TargetLibraryInfoImpl::setUnavailable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ad7837c42372169017a6e5ff3eaa42d1d">llvm::Triple::tce</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda2838cf6df0f09591c50d752d46c4350d">llvm::Triple::TvOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda87a3c8454473c64f6d605ebd757759ad">llvm::Triple::WatchOS</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">llvm::Triple::x86</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a1e3f00d3a8c8c59f0f95fd80f1d3ba53">llvm::Triple::xcore</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdabb5225659a201976ce2594df579e3623">llvm::Triple::XROS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-updatecompilerused-cpp-/preservelibcallsandasmused/#a141a9f26d14fdfbae8dc42c43af92685">anonymous{UpdateCompilerUsed.cpp}::PreserveLibCallsAndAsmUsed::findInModule</a> and <a href="#a19d27915595e7f0a0ef271448bcdac6f">initialize</a>.</p>

</div>
</div>

### isCallingConvCCompatible() {#a99b2775600f9f190f98b0f08f36870b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isCallingConvCCompatible (CallingConv::ID CC, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TT, <a href="/web-llvm/docs/api/classes/functiontype">FunctionType</a> * FuncTy)</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca6460922e7050fc0dcff22631e4bc7fdb">llvm::CallingConv::ARM_AAPCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caf5725080d76d25fff371be12a0bf29f4">llvm::CallingConv::ARM_AAPCS_VFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca39e4f9a6d108588930a09d779d4e812f">llvm::CallingConv::ARM_APCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>.</p>

</div>
</div>

### isValidProtoForSizeReturningNew() {#abb3e0c28998ff9684b75e9efa0697919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isValidProtoForSizeReturningNew (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/functiontype">FunctionType</a> &amp; FTy, <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, int SizeTSizeBits)</td>
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



<p>Definition at line 1068 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">llvm::PointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a18fc4545474c6ebb6f7c547f64f4fb31">llvm::StructType::get</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#acaf8e4c3e40e01e848c1fad5f05b81cd">llvm::Type::getIntNTy</a>.</p>

</div>
</div>

### matchType() {#a2c31886b94c082d37269155b9186a3cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool matchType (<a href="#aca185e6d0e9f423dbb24440206454872">FuncArgTypeID</a> ArgTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned IntBits, unsigned SizeTBits)</td>
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



<p>Definition at line 1021 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="#aca185e6d0e9f423dbb24440206454872a29dcc89db32a1eead61fe67cff38c060">Bool</a>, <a href="#aca185e6d0e9f423dbb24440206454872a79e4ec69e83555caf8889be4fad6d361">Dbl</a>, <a href="#aca185e6d0e9f423dbb24440206454872a4815677a428e37e90c6f71f94ddd7b65">Floating</a>, <a href="#aca185e6d0e9f423dbb24440206454872a11534cddb9d36ce7b049eefacc295a96">Flt</a>, <a href="#aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01">Int</a>, <a href="#aca185e6d0e9f423dbb24440206454872a150558aeaa819431aeb9729d26b2ac9f">Int16</a>, <a href="#aca185e6d0e9f423dbb24440206454872a788a72ddbf1bd572b3fcd7a5e7ec8cff">Int32</a>, <a href="#aca185e6d0e9f423dbb24440206454872ada475947399b8ab4d13d40fea50f950c">Int64</a>, <a href="#aca185e6d0e9f423dbb24440206454872a3bbd27529d01e024c526896dcd5f6a5e">IntPlus</a>, <a href="#aca185e6d0e9f423dbb24440206454872a52fc06c8638074204be3a7f9a35d65b1">IntX</a>, <a href="#aca185e6d0e9f423dbb24440206454872aba2f71e41b94b5fc82ea91e5335a264a">LDbl</a>, <a href="#aca185e6d0e9f423dbb24440206454872a9cec0e2f2afd661509a20c3cf054abda">LLong</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#aca185e6d0e9f423dbb24440206454872afbe5087b942deaaa3202c7ca87dbc327">Long</a>, <a href="#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="#aca185e6d0e9f423dbb24440206454872a9db720c78340455edd11227589989ea2">SizeT</a>, <a href="#aca185e6d0e9f423dbb24440206454872a8388b5a41ed174169eea5ef989712695">SSizeT</a>, <a href="#aca185e6d0e9f423dbb24440206454872a763a932e166ac85a6d2d1606e8649993">Struct</a> and <a href="#aca185e6d0e9f423dbb24440206454872a8ce14d8b0fc90289ee23848f6de11c47">Void</a>.</p>

</div>
</div>

### sanitizeFunctionName() {#a147437aa3b97e99609ae28aa1ee2eb32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef sanitizeFunctionName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> funcName)</td>
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



<p>Definition at line 983 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a83a294111af6d4412163b209725ca556">llvm::StringRef::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3e999e4bb7297d284f931638721840e5">llvm::GlobalValue::dropLLVMManglingEscape</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a0f382b34dc924b235282157869cb3771">llvm::TargetLibraryInfoImpl::getLibFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a4c36c8f36fd0fe73e2936da5f1479691">llvm::TargetLibraryInfoImpl::getVectorMappingInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a15113486c66611b76318afc2c37352c3">llvm::TargetLibraryInfoImpl::getWidestVF</a> and <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a798028b6fc917a63c65f97cb29ab6b69">llvm::TargetLibraryInfoImpl::isFunctionVectorizable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ClVectorLibrary {#ae0906a1189434b7f140fb9439faf7dd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; TargetLibraryInfoImpl::VectorLibrary &gt; ClVectorLibrary("vector-library", cl::Hidden, cl::desc("Vector functions library"), cl::init(TargetLibraryInfoImpl::NoLibrary), cl::values(clEnumValN(TargetLibraryInfoImpl::NoLibrary, "none", "No vector functions library"), clEnumValN(TargetLibraryInfoImpl::Accelerate, "Accelerate", "Accelerate framework"), clEnumValN(TargetLibraryInfoImpl::DarwinLibSystemM, "Darwin_libsystem_m", "Darwin libsystem_m"), clEnumValN(TargetLibraryInfoImpl::LIBMVEC_X86, "LIBMVEC-X86", "GLIBC Vector Math library"), clEnumValN(TargetLibraryInfoImpl::MASSV, "MASSV", "IBM MASS vector library"), clEnumValN(TargetLibraryInfoImpl::SVML, "SVML", "Intel SVML library"), clEnumValN(TargetLibraryInfoImpl::SLEEFGNUABI, "sleefgnuabi", "SIMD Library for Evaluating Elementary Functions"), clEnumValN(TargetLibraryInfoImpl::ArmPL, "ArmPL", "Arm Performance Libraries"), clEnumValN(TargetLibraryInfoImpl::AMDLIBM, "AMDLIBM", "AMD vector math library")))</td>
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



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Referenced by <a href="#a201c313701e8c03b7fd137205154ce37">initializeLibCalls</a>.</p>

</div>
</div>

### Signatures {#a8efadc1e398432637936757b43272daa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FuncProtoTy Signatures[]</td>
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
#define <a href="#a71bfd683f3fa071bdbde88307b2faff2">TLI_DEFINE_SIG</a>
}
</div>
</dd>
</dl>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#adcb7e087ebdb7b3e360160af660827c7">constructEntryMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#acd3a382f7ecb233b53ad4e1b44db01e3">emitEntryMD</a>, <a href="/web-llvm/docs/api/classes/llvm/balancedpartitioning/#a238d245e46593cc4a4f912a2bc53984f">llvm::BalancedPartitioning::moveGain</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a52ad1f2fa223473029d3b3535029d7e5">translateMetadata</a>.</p>

</div>
</div>

### VecFuncs\_Accelerate {#af17c5f2cd95fecfd78453bb3d6105cfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VecDesc VecFuncs_Accelerate[]</td>
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
#define <a href="#a2e47abd6e31beb69bf0464343c39d727">TLI_DEFINE_ACCELERATE_VECFUNCS</a>
}
</div>
</dd>
</dl>

<p>Definition at line 1276 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a32cf61958e13a95aaf8686f4c55aa873">llvm::TargetLibraryInfoImpl::addVectorizableFunctionsFromVecLib</a>.</p>

</div>
</div>

### VecFuncs\_AMDLIBM {#ab8f604cc3655a0f11ecdd458b39f089a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VecDesc VecFuncs_AMDLIBM[]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
#define <a href="#a4fe47ca8f81b812b5067c3818f1afda8">TLI_DEFINE_AMDLIBM_VECFUNCS</a>
#define <a href="#ad39d0066ff9816ac402a679d98b9a594">TLI_DEFINE_VECFUNC</a>(SCAL, VEC, VF, MASK, VABI_PREFIX)                   \
}
</div>
</dd>
</dl>

<p>Definition at line 1344 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a32cf61958e13a95aaf8686f4c55aa873">llvm::TargetLibraryInfoImpl::addVectorizableFunctionsFromVecLib</a>.</p>

</div>
</div>

### VecFuncs\_ArmPL {#a99f444f3a78984f61a904239bcca012b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VecDesc VecFuncs_ArmPL[]</td>
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
#define <a href="#ab30a212811774a2406505b3ed7eac897">TLI_DEFINE_ARMPL_VECFUNCS</a>
#define <a href="#ad39d0066ff9816ac402a679d98b9a594">TLI_DEFINE_VECFUNC</a>(SCAL, VEC, VF, MASK, VABI_PREFIX)                   \
}
</div>
</dd>
</dl>

<p>Definition at line 1336 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a32cf61958e13a95aaf8686f4c55aa873">llvm::TargetLibraryInfoImpl::addVectorizableFunctionsFromVecLib</a>.</p>

</div>
</div>

### VecFuncs\_DarwinLibSystemM {#acad27f01498f4940adaf11039f80f736}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VecDesc VecFuncs_DarwinLibSystemM[]</td>
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
#define <a href="#a4754a4f26e7b5261aea4edadf1d0380e">TLI_DEFINE_DARWIN_LIBSYSTEM_M_VECFUNCS</a>
}
</div>
</dd>
</dl>

<p>Definition at line 1282 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a32cf61958e13a95aaf8686f4c55aa873">llvm::TargetLibraryInfoImpl::addVectorizableFunctionsFromVecLib</a>.</p>

</div>
</div>

### VecFuncs\_LIBMVEC\_X86 {#ac144d58061674e2d303867113dc0f6a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VecDesc VecFuncs_LIBMVEC_X86[]</td>
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
#define <a href="#a7db04c63adc1ea109aa4405161eb7e43">TLI_DEFINE_LIBMVEC_X86_VECFUNCS</a>
}
</div>
</dd>
</dl>

<p>Definition at line 1288 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a32cf61958e13a95aaf8686f4c55aa873">llvm::TargetLibraryInfoImpl::addVectorizableFunctionsFromVecLib</a>.</p>

</div>
</div>

### VecFuncs\_MASSV {#a1c23ee38c4d1bd844c40c2629913419c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VecDesc VecFuncs_MASSV[]</td>
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
#define <a href="#aec25928b70c7b655c9be05fda9e315e5">TLI_DEFINE_MASSV_VECFUNCS</a>
}
</div>
</dd>
</dl>

<p>Definition at line 1294 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a32cf61958e13a95aaf8686f4c55aa873">llvm::TargetLibraryInfoImpl::addVectorizableFunctionsFromVecLib</a>.</p>

</div>
</div>

### VecFuncs\_SLEEFGNUABI\_VF2 {#a5598458647d40357efc9e50b0394a93a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VecDesc VecFuncs_SLEEFGNUABI_VF2[]</td>
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
#define <a href="#afa7e1fe59190525ca9495bf266da93f3">TLI_DEFINE_SLEEFGNUABI_VF2_VECFUNCS</a>
#define <a href="#ad39d0066ff9816ac402a679d98b9a594">TLI_DEFINE_VECFUNC</a>(SCAL, VEC, VF, VABI_PREFIX)                         \
}
</div>
</dd>
</dl>

<p>Definition at line 1306 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a32cf61958e13a95aaf8686f4c55aa873">llvm::TargetLibraryInfoImpl::addVectorizableFunctionsFromVecLib</a>.</p>

</div>
</div>

### VecFuncs\_SLEEFGNUABI\_VF4 {#a87860e9e51aaa5d9b98b584128651616}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VecDesc VecFuncs_SLEEFGNUABI_VF4[]</td>
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
#define <a href="#aa5d390b6073c799f532281a7154c716b">TLI_DEFINE_SLEEFGNUABI_VF4_VECFUNCS</a>
#define <a href="#ad39d0066ff9816ac402a679d98b9a594">TLI_DEFINE_VECFUNC</a>(SCAL, VEC, VF, VABI_PREFIX)                         \
}
</div>
</dd>
</dl>

<p>Definition at line 1313 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a32cf61958e13a95aaf8686f4c55aa873">llvm::TargetLibraryInfoImpl::addVectorizableFunctionsFromVecLib</a>.</p>

</div>
</div>

### VecFuncs\_SLEEFGNUABI\_VFScalable {#ae80d5658c79a70f7f7798946340a1f29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VecDesc VecFuncs_SLEEFGNUABI_VFScalable[]</td>
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
#define <a href="#a0c1abea970981b9315fa7673b9ee57cd">TLI_DEFINE_SLEEFGNUABI_SCALABLE_VECFUNCS</a>
#define <a href="#ad39d0066ff9816ac402a679d98b9a594">TLI_DEFINE_VECFUNC</a>(SCAL, VEC, VF, MASK, VABI_PREFIX)                   \
}
</div>
</dd>
</dl>

<p>Definition at line 1320 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a32cf61958e13a95aaf8686f4c55aa873">llvm::TargetLibraryInfoImpl::addVectorizableFunctionsFromVecLib</a>.</p>

</div>
</div>

### VecFuncs\_SLEEFGNUABI\_VFScalableRISCV {#af8f742526c2732949ecec896c0137123}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VecDesc VecFuncs_SLEEFGNUABI_VFScalableRISCV[]</td>
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
#define <a href="#a9d9c16c2ac21e542ce1d8b7cd46e3df6">TLI_DEFINE_SLEEFGNUABI_SCALABLE_VECFUNCS_RISCV</a>
#define <a href="#ad39d0066ff9816ac402a679d98b9a594">TLI_DEFINE_VECFUNC</a>(SCAL, VEC, VF, MASK, VABI_PREFIX)                   \
}
</div>
</dd>
</dl>

<p>Definition at line 1328 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a32cf61958e13a95aaf8686f4c55aa873">llvm::TargetLibraryInfoImpl::addVectorizableFunctionsFromVecLib</a>.</p>

</div>
</div>

### VecFuncs\_SVML {#adbccc26273cd15a1fa46a10b67064498}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VecDesc VecFuncs_SVML[]</td>
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
#define <a href="#a0a87f8d3f987be5d3a4f4629719a995e">TLI_DEFINE_SVML_VECFUNCS</a>
}
</div>
</dd>
</dl>

<p>Definition at line 1300 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a32cf61958e13a95aaf8686f4c55aa873">llvm::TargetLibraryInfoImpl::addVectorizableFunctionsFromVecLib</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### TLI\_DEFINE\_ACCELERATE\_VECFUNCS {#a2e47abd6e31beb69bf0464343c39d727}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TLI_DEFINE_ACCELERATE_VECFUNCS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1277 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

### TLI\_DEFINE\_AMDLIBM\_VECFUNCS {#a4fe47ca8f81b812b5067c3818f1afda8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TLI_DEFINE_AMDLIBM_VECFUNCS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1345 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

### TLI\_DEFINE\_ARMPL\_VECFUNCS {#ab30a212811774a2406505b3ed7eac897}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TLI_DEFINE_ARMPL_VECFUNCS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1337 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

### TLI\_DEFINE\_DARWIN\_LIBSYSTEM\_M\_VECFUNCS {#a4754a4f26e7b5261aea4edadf1d0380e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TLI_DEFINE_DARWIN_LIBSYSTEM_M_VECFUNCS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1283 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

### TLI\_DEFINE\_LIBMVEC\_X86\_VECFUNCS {#a7db04c63adc1ea109aa4405161eb7e43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TLI_DEFINE_LIBMVEC_X86_VECFUNCS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1289 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

### TLI\_DEFINE\_MASSV\_VECFUNCS {#aec25928b70c7b655c9be05fda9e315e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TLI_DEFINE_MASSV_VECFUNCS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1295 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

### TLI\_DEFINE\_SIG {#a71bfd683f3fa071bdbde88307b2faff2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TLI_DEFINE_SIG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

### TLI\_DEFINE\_SLEEFGNUABI\_SCALABLE\_VECFUNCS {#a0c1abea970981b9315fa7673b9ee57cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TLI_DEFINE_SLEEFGNUABI_SCALABLE_VECFUNCS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1321 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

### TLI\_DEFINE\_SLEEFGNUABI\_SCALABLE\_VECFUNCS\_RISCV {#a9d9c16c2ac21e542ce1d8b7cd46e3df6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TLI_DEFINE_SLEEFGNUABI_SCALABLE_VECFUNCS_RISCV</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1329 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

### TLI\_DEFINE\_SLEEFGNUABI\_VF2\_VECFUNCS {#afa7e1fe59190525ca9495bf266da93f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TLI_DEFINE_SLEEFGNUABI_VF2_VECFUNCS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1307 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

### TLI\_DEFINE\_SLEEFGNUABI\_VF4\_VECFUNCS {#aa5d390b6073c799f532281a7154c716b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TLI_DEFINE_SLEEFGNUABI_VF4_VECFUNCS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1314 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

### TLI\_DEFINE\_STRING {#a970358d390596d6015cd0eae4228a062}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TLI_DEFINE_STRING</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

### TLI\_DEFINE\_SVML\_VECFUNCS {#a0a87f8d3f987be5d3a4f4629719a995e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TLI_DEFINE_SVML_VECFUNCS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1301 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

### TLI\_DEFINE\_VECFUNC {#ad39d0066ff9816ac402a679d98b9a594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TLI_DEFINE_VECFUNC(SCAL, VEC, VF, VABI_PREFIX)&nbsp;&nbsp;&nbsp;  {SCAL, VEC, VF, /* MASK = */ false, VABI_PREFIX},</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1308 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

### TLI\_DEFINE\_VECFUNC {#ab01ee1383c0a3968f4b3d41d5a10606b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TLI_DEFINE_VECFUNC(SCAL, VEC, VF, VABI_PREFIX)&nbsp;&nbsp;&nbsp;  {SCAL, VEC, VF, /* MASK = */ false, VABI_PREFIX},</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1315 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

### TLI\_DEFINE\_VECFUNC {#abc0d1d89ba91c0e0531b9812bcce33a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TLI_DEFINE_VECFUNC(SCAL, VEC, VF, MASK, VABI_PREFIX)&nbsp;&nbsp;&nbsp;  {SCAL, VEC, VF, MASK, VABI_PREFIX},</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1322 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

### TLI\_DEFINE\_VECFUNC {#ac1fc126e9bcb8562837692c1af096aa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TLI_DEFINE_VECFUNC(SCAL, VEC, VF, MASK, VABI_PREFIX)&nbsp;&nbsp;&nbsp;  {SCAL, VEC, VF, MASK, VABI_PREFIX},</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1330 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

### TLI\_DEFINE\_VECFUNC {#af9645087b4aafa578c73788b0cec4046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TLI_DEFINE_VECFUNC(SCAL, VEC, VF, MASK, VABI_PREFIX)&nbsp;&nbsp;&nbsp;  {SCAL, VEC, VF, MASK, VABI_PREFIX},</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1338 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

### TLI\_DEFINE\_VECFUNC {#a248ada79cca5079ac31930b344b3faa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TLI_DEFINE_VECFUNC(SCAL, VEC, VF, MASK, VABI_PREFIX)&nbsp;&nbsp;&nbsp;  {SCAL, VEC, VF, MASK, VABI_PREFIX},</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1346 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp">TargetLibraryInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
