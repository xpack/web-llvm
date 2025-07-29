---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/openmpirbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `OpenMPIRBuilder` Class

<p>An interface to create LLVM-IR for OpenMP directives. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::OpenMPIRBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">llvm/Frontend/OpenMP/OMPIRBuilder.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> = <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt;::InsertPoint</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> used throughout for insertion points. <a href="#aafc1886793b898052f87edd7e9fdbaa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> used to represent an insertion point or an error value. <a href="#af24d1c61cec57095ced3b08a6dd99ee8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c571620ff53fdb78e7404f5261dbd23">FinalizeCallbackTy</a> = std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>(<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback type for variable finalization (think destructors). <a href="#a0c571620ff53fdb78e7404f5261dbd23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>(<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback type for body (=inner region) code generation. <a href="#a49e35e3ee470add16efcde1ab5d5556b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a761a2c853c1d16b33e4e8c565ce0ca45">StorableBodyGenCallbackTy</a> = std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>(<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP)&gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a296d2e28bddf1051d614f48b61005899">LoopBodyGenCallbackTy</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>(<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *IndVar)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback type for loop body code generation. <a href="#a296d2e28bddf1051d614f48b61005899">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71b5ba020f68829f5a1fd99f48b63d42">PrivatizeCallbackTy</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a>( <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp;Original, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp;Inner, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp;ReplVal)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback type for variable privatization (think copy &amp; default constructor). <a href="#a71b5ba020f68829f5a1fd99f48b63d42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad324bf833c1de81f7dfdbd943660e9bc">FileIdentifierInfoCallbackTy</a> = std::function&lt; std::tuple&lt; std::string, uint64_t &gt;()&gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20304a012a6cc83d8114222bb0337228">ReductionGenClangCBTy</a> = std::function&lt; <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a>(<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> **<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> **<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *CurFn)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReductionGen CallBack for Clang. <a href="#a20304a012a6cc83d8114222bb0337228">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aadc019775907d5ff516545c5d2bfc8">ReductionGenCBTy</a> = std::function&lt; <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a>( <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp;Res)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReductionGen CallBack for MLIR. <a href="#a3aadc019775907d5ff516545c5d2bfc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab81d602b13a50807afdda254fe16aecf">ReductionGenAtomicCBTy</a> = std::function&lt; <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a>( <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Functions used to generate atomic reductions. <a href="#ab81d602b13a50807afdda254fe16aecf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83dc195f27cf9d455f808cd6d0d17e57">MapValuesArrayTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 4 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a751d216ddce395dc7fa49fcf8e0a82c0">MapDeviceInfoArrayTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a5fd26a28fedc9044dd6939648d55c429">DeviceInfoTy</a>, 4 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62976e7f4bbb16d15c3483044afe20e7">MapFlagsArrayTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a02d7a52c47f2d71a111aef9d4fb70ecb">omp::OpenMPOffloadMappingFlags</a>, 4 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ab7cfa9fab97684d498b889987bcc74">MapNamesArrayTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *, 4 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44f261ea64dfab54a32fedf028c7c33f">MapDimArrayTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint64_t, 4 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a708e1a451b8b9f851317bbd2ab0d9118">MapNonContiguousArrayTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a83dc195f27cf9d455f808cd6d0d17e57">MapValuesArrayTy</a>, 4 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8be6d9636392371c1467984a429573a4">EmitFallbackCallbackTy</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a>(<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a>)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback function type for functions emitting the host fallback code that is executed when the kernel launch fails. <a href="#a8be6d9636392371c1467984a429573a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f44f79e28451e12a142140450888ecd">TargetTaskBodyCallbackTy</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>(<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *DeviceID, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *RTLoc, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/insertpoint">IRBuilderBase::InsertPoint</a> TargetTaskAllocaIP)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback type for generating the bodies of device directives that require outer target tasks (e.g. <a href="#a5f44f79e28451e12a142140450888ecd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af45ce5586729bfa3160eaa9cec64e0f5">EmitMetadataErrorReportFunctionTy</a> = std::function&lt; void(<a href="#affb389ba6facf4b5854565f9db5bc90b">EmitMetadataErrorKind</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a>)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback function type. <a href="#af45ce5586729bfa3160eaa9cec64e0f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05c4178639e79ab4749063b330cff5da">FunctionGenCallback</a> = std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt;(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FunctionName)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Functions used to generate a function with the given name. <a href="#a05c4178639e79ab4749063b330cff5da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a249878a72f57b4634ae65800060983f5">GenMapInfoCallbackTy</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty">MapInfosTy</a> &amp;(<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback type for creating the map infos for the kernel parameters. <a href="#a249878a72f57b4634ae65800060983f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73e20c5fd6145c56d7ce35c2ccd99e5b">TargetBodyGenCallbackTy</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a>( <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP)&gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ad579ff0c72b56f5ebc91bf2d747bc2">TargetGenArgAccessorsCallbackTy</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a>( <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> &amp;Arg, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *<a href="/web-llvm/docs/api/classes/input">Input</a>, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp;RetVal, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP)&gt;</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab08e2c502864d33cabeb9b78dfe3cc02">AtomicUpdateCallbackTy</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;(<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *XOld, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp;IRB)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback type for Atomic <a href="/web-llvm/docs/api/classes/llvm/expression">Expression</a> update ex: <a href="#ab08e2c502864d33cabeb9b78dfe3cc02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ReductionGenCBKind { <a href="#a07f00f83b415baecc1af353eed43d123">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enum class for the RedctionGen CallBack type to be used. <a href="#a07f00f83b415baecc1af353eed43d123">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">EvalKind { <a href="#a0f3b3f2ce3e462711213b2ecb34e904c">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enum class for reduction evaluation types scalar, complex and aggregate. <a href="#a0f3b3f2ce3e462711213b2ecb34e904c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CopyAction : unsigned { <a href="#a204d79d34d33ba7563337995bb481318">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DeviceInfoTy { <a href="#a5fd26a28fedc9044dd6939648d55c429">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">EmitMetadataErrorKind { <a href="#affb389ba6facf4b5854565f9db5bc90b">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The kind of errors that can occur when emitting the offload entries and metadata. <a href="#affb389ba6facf4b5854565f9db5bc90b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">BodyGenTy { <a href="#ae620d2ad309b2b4959c64edd1e040fdf">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of BodyGen to use for region codegen. <a href="#ae620d2ad309b2b4959c64edd1e040fdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AtomicKind { <a href="#aa014f633c701cbd3313b654114f15d09">...</a> }</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1a990c96a3ebf58698901d09c5b4378">OpenMPIRBuilder</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder">OpenMPIRBuilder</a> operating on the given module <span class="doxyComputerOutput">M</span>. <a href="#ae1a990c96a3ebf58698901d09c5b4378">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad66949e2e846451e61d9c8f34014ea31">~OpenMPIRBuilder</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1af99f6f33b0db83a3e941fcb819fa29">initialize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the internal state, this will put structures types and potentially other helpers into the underlying module. <a href="#a1af99f6f33b0db83a3e941fcb819fa29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cf3a832c89fb823f696ce21ecf37b9b">setConfig</a> (OpenMPIRBuilderConfig C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a784adc2347b72f745ff1239aef3a3c26">finalize</a> (Function *Fn=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize the underlying module, e.g., by outlining regions. <a href="#a784adc2347b72f745ff1239aef3a3c26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50c6490cf353f064946c4e32673ac098">addAttributes</a> (omp::RuntimeFunction FnID, Function &amp;Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add attributes known for <span class="doxyComputerOutput">FnID</span> to <span class="doxyComputerOutput">Fn</span>. <a href="#a50c6490cf353f064946c4e32673ac098">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a488c861f8a68e5f78ceca8b57acd8be5">createPlatformSpecificName</a> (ArrayRef&lt; StringRef &gt; Parts) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the create a name using the platform specific separators. <a href="#a488c861f8a68e5f78ceca8b57acd8be5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a977f2477d245a9d554642492fedd049a">pushFinalizationCB</a> (const FinalizationInfo &amp;FI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Push a finalization callback on the finalization stack. <a href="#a977f2477d245a9d554642492fedd049a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2e7210874149ecbd52c8ce44ca4f416">popFinalizationCB</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pop the last finalization callback from the finalization stack. <a href="#af2e7210874149ecbd52c8ce44ca4f416">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abca6530c9099bd1b1c3e0a5c32381f07">createBarrier</a> (const LocationDescription &amp;Loc, omp::Directive Kind, bool ForceSimpleCall=false, bool CheckCancelFlag=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emitter methods for OpenMP directives. <a href="#abca6530c9099bd1b1c3e0a5c32381f07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04285415a321e48322c08f3b9185540e">createCancel</a> (const LocationDescription &amp;Loc, Value *IfCondition, omp::Directive CanceledDirective)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> cancel'. <a href="#a04285415a321e48322c08f3b9185540e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f81b9940e1869e146636dc533455929">createParallel</a> (const LocationDescription &amp;Loc, InsertPointTy AllocaIP, BodyGenCallbackTy BodyGenCB, PrivatizeCallbackTy PrivCB, FinalizeCallbackTy FiniCB, Value *IfCondition, Value *NumThreads, omp::ProcBindKind ProcBind, bool IsCancellable)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> parallel'. <a href="#a4f81b9940e1869e146636dc533455929">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0287686a5ffe03bc264972c862726ea">createCanonicalLoop</a> (const LocationDescription &amp;Loc, LoopBodyGenCallbackTy BodyGenCB, Value *TripCount, const Twine &amp;Name="loop")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for the control flow structure of an OpenMP canonical loop. <a href="#ae0287686a5ffe03bc264972c862726ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac669acbd0f638c6ef32977575362052e">createCanonicalLoop</a> (const LocationDescription &amp;Loc, LoopBodyGenCallbackTy BodyGenCB, Value *Start, Value *Stop, Value *Step, bool IsSigned, bool InclusiveStop, InsertPointTy ComputeIP={}, const Twine &amp;Name="loop")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for the control flow structure of an OpenMP canonical loop. <a href="#ac669acbd0f638c6ef32977575362052e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08610118e213de1b759470f0eafb9b18">collapseLoops</a> (DebugLoc DL, ArrayRef&lt; CanonicalLoopInfo * &gt; Loops, InsertPointTy ComputeIP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collapse a loop nest into a single loop. <a href="#a08610118e213de1b759470f0eafb9b18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdc1b8675a946ce055c64607ba75af3a">getAddrOfDeclareTargetVar</a> (OffloadEntriesInfoManager::OMPTargetGlobalVarEntryKind CaptureClause, OffloadEntriesInfoManager::OMPTargetDeviceClauseKind DeviceClause, bool IsDeclaration, bool IsExternallyVisible, TargetRegionEntryInfo EntryInfo, StringRef MangledName, std::vector&lt; GlobalVariable * &gt; &amp;GeneratedRefs, bool OpenMPSIMD, std::vector&lt; Triple &gt; TargetTriple, Type *LlvmPtrTy, std::function&lt; Constant *()&gt; GlobalInitializer, std::function&lt; GlobalValue::LinkageTypes()&gt; VariableLinkage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve (or create if non-existent) the address of a declare target variable, used in conjunction with registerTargetGlobalVariable to create declare target global variables. <a href="#afdc1b8675a946ce055c64607ba75af3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae327be8503a76bd4dccfff4713a38553">registerTargetGlobalVariable</a> (OffloadEntriesInfoManager::OMPTargetGlobalVarEntryKind CaptureClause, OffloadEntriesInfoManager::OMPTargetDeviceClauseKind DeviceClause, bool IsDeclaration, bool IsExternallyVisible, TargetRegionEntryInfo EntryInfo, StringRef MangledName, std::vector&lt; GlobalVariable * &gt; &amp;GeneratedRefs, bool OpenMPSIMD, std::vector&lt; Triple &gt; TargetTriple, std::function&lt; Constant *()&gt; GlobalInitializer, std::function&lt; GlobalValue::LinkageTypes()&gt; VariableLinkage, Type *LlvmPtrTy, Constant *Addr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Registers a target variable for device or host. <a href="#ae327be8503a76bd4dccfff4713a38553">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac86b562509588cbc00fbdc441c615bd3">getFlagMemberOffset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the offset of the OMP_MAP_MEMBER_OF field. <a href="#ac86b562509588cbc00fbdc441c615bd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/omp/#a02d7a52c47f2d71a111aef9d4fb70ecb">omp::OpenMPOffloadMappingFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f82182a8cc23f854efdbd453f685086">getMemberOfFlag</a> (unsigned Position)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get OMP_MAP_MEMBER_OF flag with extra bits reserved based on the position given. <a href="#a4f82182a8cc23f854efdbd453f685086">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeea5a3df7d0266470cd04bb721db70e">setCorrectMemberOfFlag</a> (omp::OpenMPOffloadMappingFlags &amp;Flags, omp::OpenMPOffloadMappingFlags MemberOfFlag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an initial flag set, this function modifies it to contain the passed in MemberOfFlag generated from the getMemberOfFlag function. <a href="#abeea5a3df7d0266470cd04bb721db70e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaa14806d128ad33bdc48d2bfc46870c">applyWorkshareLoop</a> (DebugLoc DL, CanonicalLoopInfo *CLI, InsertPointTy AllocaIP, bool NeedsBarrier, llvm::omp::ScheduleKind SchedKind=llvm::omp::OMP_SCHEDULE_Default, Value *ChunkSize=nullptr, bool HasSimdModifier=false, bool HasMonotonicModifier=false, bool HasNonmonotonicModifier=false, bool HasOrderedClause=false, omp::WorksharingLoopType LoopType=omp::WorksharingLoopType::ForStaticLoop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Modifies the canonical loop to be a workshare loop. <a href="#adaa14806d128ad33bdc48d2bfc46870c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76e12ec076e7af4be7b8b77a5d53d3fc">tileLoops</a> (DebugLoc DL, ArrayRef&lt; CanonicalLoopInfo * &gt; Loops, ArrayRef&lt; Value * &gt; TileSizes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tile a loop nest. <a href="#a76e12ec076e7af4be7b8b77a5d53d3fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28a2a9806d828609fe107f766d2dd569">unrollLoopFull</a> (DebugLoc DL, CanonicalLoopInfo *Loop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fully unroll a loop. <a href="#a28a2a9806d828609fe107f766d2dd569">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ca0068cb6a50615c74ecdb8f23839e0">unrollLoopHeuristic</a> (DebugLoc DL, CanonicalLoopInfo *Loop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fully or partially unroll a loop. <a href="#a4ca0068cb6a50615c74ecdb8f23839e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e2b7ac5f48193117a340aa15b085719">unrollLoopPartial</a> (DebugLoc DL, CanonicalLoopInfo *Loop, int32_t Factor, CanonicalLoopInfo **UnrolledCLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Partially unroll a loop. <a href="#a5e2b7ac5f48193117a340aa15b085719">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd1fbb2df257f945afda92919be322f3">applySimd</a> (CanonicalLoopInfo *Loop, MapVector&lt; Value *, Value * &gt; AlignedVars, Value *IfCond, omp::OrderKind Order, ConstantInt *Simdlen, ConstantInt *Safelen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add metadata to simd-ize a loop. <a href="#acd1fbb2df257f945afda92919be322f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc2cc623eda981e1b3fbb61a44e80ef8">createFlush</a> (const LocationDescription &amp;Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> flush'. <a href="#afc2cc623eda981e1b3fbb61a44e80ef8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a419ffad9e4d59275e299ce1ad3c73cd4">createTaskwait</a> (const LocationDescription &amp;Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> taskwait'. <a href="#a419ffad9e4d59275e299ce1ad3c73cd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b0ed7f600549e4239bf10b5b85de66c">createTaskyield</a> (const LocationDescription &amp;Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> taskyield'. <a href="#a0b0ed7f600549e4239bf10b5b85de66c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0af3c7a02c1325c04c59f857604bd4f3">createTask</a> (const LocationDescription &amp;Loc, InsertPointTy AllocaIP, BodyGenCallbackTy BodyGenCB, bool Tied=true, Value *Final=nullptr, Value *IfCondition=nullptr, SmallVector&lt; DependData &gt; Dependencies={}, bool Mergeable=false, Value *EventHandle=nullptr, Value *Priority=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for <span class="doxyComputerOutput">#omp task</span> <a href="#a0af3c7a02c1325c04c59f857604bd4f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f8b732c2f951d56302d4431f00f16bd">createTaskgroup</a> (const LocationDescription &amp;Loc, InsertPointTy AllocaIP, BodyGenCallbackTy BodyGenCB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for the taskgroup construct. <a href="#a1f8b732c2f951d56302d4431f00f16bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa655ca8bca40c564d0b7c81ebaf8ff9">createReductionsGPU</a> (const LocationDescription &amp;Loc, InsertPointTy AllocaIP, InsertPointTy CodeGenIP, ArrayRef&lt; ReductionInfo &gt; ReductionInfos, bool IsNoWait=false, bool IsTeamsReduction=false, bool HasDistribute=false, ReductionGenCBKind ReductionGenCBKind=ReductionGenCBKind::MLIR, std::optional&lt; omp::GV &gt; GridValue={}, unsigned ReductionBufNum=1024, Value *SrcLocInfo=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Design of OpenMP reductions on the GPU. <a href="#aaa655ca8bca40c564d0b7c81ebaf8ff9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0996924f219129d8de3cc1b8830f768">createReductions</a> (const LocationDescription &amp;Loc, InsertPointTy AllocaIP, ArrayRef&lt; ReductionInfo &gt; ReductionInfos, ArrayRef&lt; bool &gt; IsByRef, bool IsNoWait=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> reduction'. <a href="#ab0996924f219129d8de3cc1b8830f768">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa26124809eff11c5f244027439751c50">getInsertionPoint</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#aa26124809eff11c5f244027439751c50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a> (const LocationDescription &amp;Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the internal location to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span>. <a href="#afad4662affec545adea91dfb62f11829">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a034dc6253a2a36f78ac071a7c12d5c27">getOrCreateRuntimeFunction</a> (Module &amp;M, omp::RuntimeFunction FnID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the function declaration for the runtime function with <span class="doxyComputerOutput">FnID</span>. <a href="#a034dc6253a2a36f78ac071a7c12d5c27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a> (omp::RuntimeFunction FnID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a> (StringRef LocStr, uint32_t &amp;SrcLocStrSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the (LLVM-IR) string describing the source location <span class="doxyComputerOutput">LocStr</span>. <a href="#a55a39962245dd2e0938194dd3b4438e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac35a35b620a34821da2801ebf452a9a0">getOrCreateDefaultSrcLocStr</a> (uint32_t &amp;SrcLocStrSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the (LLVM-IR) string describing the default source location. <a href="#ac35a35b620a34821da2801ebf452a9a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a061144e3e490f8917de9c53163ef8c01">getOrCreateSrcLocStr</a> (StringRef FunctionName, StringRef FileName, unsigned Line, unsigned Column, uint32_t &amp;SrcLocStrSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the (LLVM-IR) string describing the source location identified by the arguments. <a href="#a061144e3e490f8917de9c53163ef8c01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b8c05f635a1b8e5a66eeec4704bf291">getOrCreateSrcLocStr</a> (DebugLoc DL, uint32_t &amp;SrcLocStrSize, Function *F=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the (LLVM-IR) string describing the <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> <span class="doxyComputerOutput">DL</span>. <a href="#a9b8c05f635a1b8e5a66eeec4704bf291">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4950d59a5a139f25fa75e82a948537fc">getOrCreateSrcLocStr</a> (const LocationDescription &amp;Loc, uint32_t &amp;SrcLocStrSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the (LLVM-IR) string describing the source location <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span>. <a href="#a4950d59a5a139f25fa75e82a948537fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a> (Constant *SrcLocStr, uint32_t SrcLocStrSize, omp::IdentFlag Flags=omp::IdentFlag(0), unsigned Reserve2Flags=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an ident_t* encoding the source location <span class="doxyComputerOutput">SrcLocStr</span> and <span class="doxyComputerOutput">Flags</span>. <a href="#a02cae9681b22a06e7738a4c1f3de233e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada8d44774af63e8cab5f9b2a088121fe">createGlobalFlag</a> (unsigned Value, StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a hidden global flag <span class="doxyComputerOutput">Name</span> in the module with initial value <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span>. <a href="#ada8d44774af63e8cab5f9b2a088121fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bb33831dbcaa836f630ed1dc986b5c2">emitUsed</a> (StringRef Name, ArrayRef&lt; llvm::WeakTrackingVH &gt; List)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the llvm.used metadata. <a href="#a3bb33831dbcaa836f630ed1dc986b5c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1943d078483c15aa78cb00f7fff2590c">emitKernelExecutionMode</a> (StringRef KernelName, omp::OMPTgtExecModeFlags Mode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the kernel execution mode. <a href="#a1943d078483c15aa78cb00f7fff2590c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98b55a0d95b3926151545101e4f2aef9">emitCancelationCheckImpl</a> (Value *CancelFlag, omp::Directive CanceledDirective, FinalizeCallbackTy ExitCB={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate control flow and cleanup for cancellation. <a href="#a98b55a0d95b3926151545101e4f2aef9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad48c785749c7160070b39be42c67d2b7">emitTargetKernel</a> (const LocationDescription &amp;Loc, InsertPointTy AllocaIP, Value *&amp;Return, Value *Ident, Value *DeviceID, Value *NumTeams, Value *NumThreads, Value *HostPtr, ArrayRef&lt; Value * &gt; KernelArgs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate a target region entry call. <a href="#ad48c785749c7160070b39be42c67d2b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a4b97bb7670d306c756cdbd5ee9b560">emitFlush</a> (const LocationDescription &amp;Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate a flush runtime call. <a href="#a2a4b97bb7670d306c756cdbd5ee9b560">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad44e60b9d264f6ceb54e6cd660e859fb">isLastFinalizationInfoCancellable</a> (omp::Directive DK)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the last entry in the finalization stack is of kind <span class="doxyComputerOutput">DK</span> and cancellable. <a href="#ad44e60b9d264f6ceb54e6cd660e859fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a177df2c9d7d8692ed214018f420c3de6">emitTaskwaitImpl</a> (const LocationDescription &amp;Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate a taskwait runtime call. <a href="#a177df2c9d7d8692ed214018f420c3de6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6383328cfcdbbd56502b92f9e2415432">emitTaskyieldImpl</a> (const LocationDescription &amp;Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate a taskyield runtime call. <a href="#a6383328cfcdbbd56502b92f9e2415432">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a> (Value *Ident)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the current thread <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#a9607f501333d84917dc48f5d263e9b6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5610e0ef8f016e84694778d8ce1c9479">addOutlineInfo</a> (OutlineInfo &amp;&amp;OI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new region that will be outlined later. <a href="#a5610e0ef8f016e84694778d8ce1c9479">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae19488d3493945579ed3987ce14c6ff2">getSizeInBytes</a> (Value *BasePtr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the size of type in bytes. <a href="#ae19488d3493945579ed3987ce14c6ff2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c977097cc5c8d9c7c049e8fc988fdcf">emitBranch</a> (BasicBlock *Target)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9199bb920d3966ef9c614a623c7af495">emitBlock</a> (BasicBlock *BB, Function *CurFn, bool IsFinished=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39b12e3ad8afd4183a2cd63f1b1b8746">emitIfClause</a> (Value *Cond, BodyGenCallbackTy ThenGen, BodyGenCallbackTy ElseGen, InsertPointTy AllocaIP={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits code for OpenMP 'if' clause using specified <em><a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a></em> Here is the logic: if (Cond) { ThenGen(); } else { ElseGen(); }. <a href="#a39b12e3ad8afd4183a2cd63f1b1b8746">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad56f71598b251a0f66e590c94d01c67b">createOffloadMaptypes</a> (SmallVectorImpl&lt; uint64_t &gt; &amp;Mappings, std::string VarName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the global variable holding the offload mappings information. <a href="#ad56f71598b251a0f66e590c94d01c67b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1aa0d632549db4855d6412f4d2d44ae">createOffloadMapnames</a> (SmallVectorImpl&lt; llvm::Constant * &gt; &amp;Names, std::string VarName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the global variable holding the offload names information. <a href="#ab1aa0d632549db4855d6412f4d2d44ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a544a84c75ac55356516cc7365cbe6f02">createMapperAllocas</a> (const LocationDescription &amp;Loc, InsertPointTy AllocaIP, unsigned NumOperands, struct MapperAllocas &amp;MapperAllocas)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the allocas instruction used in call to mapper functions. <a href="#a544a84c75ac55356516cc7365cbe6f02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a654b33adee2ae78ce74ecbe6aa5e5282">emitMapperCall</a> (const LocationDescription &amp;Loc, Function *MapperFunc, Value *SrcLocInfo, Value *MaptypesArg, Value *MapnamesArg, struct MapperAllocas &amp;MapperAllocas, int64_t DeviceID, unsigned NumOperands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the call for the target mapper function. <a href="#a654b33adee2ae78ce74ecbe6aa5e5282">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f09d4b7d64e71987be7bb45d8694ffe">emitKernelLaunch</a> (const LocationDescription &amp;Loc, Value *OutlinedFnID, EmitFallbackCallbackTy EmitTargetCallFallbackCB, TargetKernelArgs &amp;Args, Value *DeviceID, Value *RTLoc, InsertPointTy AllocaIP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate a target region entry call and host fallback call. <a href="#a9f09d4b7d64e71987be7bb45d8694ffe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2841680b34ec9c2c7185a877f8f8b4c8">emitTargetTask</a> (TargetTaskBodyCallbackTy TaskBodyCB, Value *DeviceID, Value *RTLoc, OpenMPIRBuilder::InsertPointTy AllocaIP, const SmallVector&lt; llvm::OpenMPIRBuilder::DependData &gt; &amp;Dependencies, bool HasNoWait)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate a target-task for the target construct. <a href="#a2841680b34ec9c2c7185a877f8f8b4c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb95f78638066c9b6ccba6e3a7d335da">emitOffloadingArraysArgument</a> (IRBuilderBase &amp;Builder, OpenMPIRBuilder::TargetDataRTArgs &amp;RTArgs, OpenMPIRBuilder::TargetDataInfo &amp;Info, bool ForEndCall=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the arguments to be passed to the runtime library based on the arrays of base pointers, pointers, sizes, map types, and mappers. <a href="#adb95f78638066c9b6ccba6e3a7d335da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a827b80924bcd29f32b772a4ed162fb68">emitNonContiguousDescriptor</a> (InsertPointTy AllocaIP, InsertPointTy CodeGenIP, MapInfosTy &amp;CombinedInfo, TargetDataInfo &amp;Info)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an array of struct descriptors to be assigned to the offload args. <a href="#a827b80924bcd29f32b772a4ed162fb68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a752e863c1af5fe463d0f08574492c12f">emitOffloadingArrays</a> (InsertPointTy AllocaIP, InsertPointTy CodeGenIP, MapInfosTy &amp;CombinedInfo, TargetDataInfo &amp;Info, bool IsNonContiguous=false, function_ref&lt; void(unsigned int, Value *)&gt; DeviceAddrCB=nullptr, function_ref&lt; Value *(unsigned int)&gt; CustomMapperCB=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the arrays used to pass the captures and map information to the offloading runtime library. <a href="#a752e863c1af5fe463d0f08574492c12f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a966e441c1e3f27fce994c360b55abae9">emitOffloadingArraysAndArgs</a> (InsertPointTy AllocaIP, InsertPointTy CodeGenIP, TargetDataInfo &amp;Info, TargetDataRTArgs &amp;RTArgs, MapInfosTy &amp;CombinedInfo, bool IsNonContiguous=false, bool ForEndCall=false, function_ref&lt; void(unsigned int, Value *)&gt; DeviceAddrCB=nullptr, function_ref&lt; Value *(unsigned int)&gt; CustomMapperCB=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocates memory for and populates the arrays required for offloading (offload_{baseptrs|ptrs|mappers|sizes|maptypes|mapnames}). <a href="#a966e441c1e3f27fce994c360b55abae9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5805e4c7f00be338494407152cf34aa">createOffloadEntry</a> (Constant *ID, Constant *Addr, uint64_t Size, int32_t Flags, GlobalValue::LinkageTypes, StringRef Name="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates offloading entry for the provided entry <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> <em><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></em>, address <em>Addr</em>, size <em>Size</em>, and flags <em>Flags</em>. <a href="#ac5805e4c7f00be338494407152cf34aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc290ce16055813d4ee68af4c8023a09">createOffloadEntriesAndInfoMetadata</a> (EmitMetadataErrorReportFunctionTy &amp;ErrorReportFunction)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2808c704c935cee35e9529907b59b1c">createCopyPrivate</a> (const LocationDescription &amp;Loc, llvm::Value *BufSize, llvm::Value *CpyBuf, llvm::Value *CpyFn, llvm::Value *DidIt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for __kmpc_copyprivate. <a href="#af2808c704c935cee35e9529907b59b1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e1a0b27abb4d57e2293c46802eee89d">createSingle</a> (const LocationDescription &amp;Loc, BodyGenCallbackTy BodyGenCB, FinalizeCallbackTy FiniCB, bool IsNowait, ArrayRef&lt; llvm::Value * &gt; CPVars={}, ArrayRef&lt; llvm::Function * &gt; CPFuncs={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> single'. <a href="#a3e1a0b27abb4d57e2293c46802eee89d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a970cc920a6bae8d641ac63fb33afb40b">createMaster</a> (const LocationDescription &amp;Loc, BodyGenCallbackTy BodyGenCB, FinalizeCallbackTy FiniCB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> master'. <a href="#a970cc920a6bae8d641ac63fb33afb40b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf9f105d93a1a09d5307dc14e77293f1">createMasked</a> (const LocationDescription &amp;Loc, BodyGenCallbackTy BodyGenCB, FinalizeCallbackTy FiniCB, Value *Filter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> masked'. <a href="#adf9f105d93a1a09d5307dc14e77293f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac379895c55a89804f49f1a775828c235">createCritical</a> (const LocationDescription &amp;Loc, BodyGenCallbackTy BodyGenCB, FinalizeCallbackTy FiniCB, StringRef CriticalName, Value *HintInst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> critical'. <a href="#ac379895c55a89804f49f1a775828c235">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e2bd6420d3d12339e32d4d1b3ba1394">createOrderedDepend</a> (const LocationDescription &amp;Loc, InsertPointTy AllocaIP, unsigned NumLoops, ArrayRef&lt; llvm::Value * &gt; StoreValues, const Twine &amp;Name, bool IsDependSource)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> ordered depend (source | sink)'. <a href="#a6e2bd6420d3d12339e32d4d1b3ba1394">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a012d736828ba67916f7e5a3e9ff1d68f">createOrderedThreadsSimd</a> (const LocationDescription &amp;Loc, BodyGenCallbackTy BodyGenCB, FinalizeCallbackTy FiniCB, bool IsThreads)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> ordered [threads | simd]'. <a href="#a012d736828ba67916f7e5a3e9ff1d68f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af36172c1f538b7305b44760997d5a3c2">createSections</a> (const LocationDescription &amp;Loc, InsertPointTy AllocaIP, ArrayRef&lt; StorableBodyGenCallbackTy &gt; SectionCBs, PrivatizeCallbackTy PrivCB, FinalizeCallbackTy FiniCB, bool IsCancellable, bool IsNowait)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> sections'. <a href="#af36172c1f538b7305b44760997d5a3c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8565ee3d1c387153e57cd65a96390dfa">createSection</a> (const LocationDescription &amp;Loc, BodyGenCallbackTy BodyGenCB, FinalizeCallbackTy FiniCB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> section'. <a href="#a8565ee3d1c387153e57cd65a96390dfa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f603d822817256077c95e6573f2b14a">createTeams</a> (const LocationDescription &amp;Loc, BodyGenCallbackTy BodyGenCB, Value *NumTeamsLower=nullptr, Value *NumTeamsUpper=nullptr, Value *ThreadLimit=nullptr, Value *IfExpr=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for <span class="doxyComputerOutput">#omp teams</span> <a href="#a3f603d822817256077c95e6573f2b14a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70356a38271d388e7c4b477cef0d7b2c">createCopyinClauseBlocks</a> (InsertPointTy IP, Value *MasterAddr, Value *PrivateAddr, llvm::IntegerType *IntPtrTy, bool BranchtoEnd=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate conditional branch and relevant BasicBlocks through which private threads copy the 'copyin' variables from Master copy to threadprivate copies. <a href="#a70356a38271d388e7c4b477cef0d7b2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81bc7a57bd0332843aed6275ba47bee0">createOMPAlloc</a> (const LocationDescription &amp;Loc, Value *Size, Value *Allocator, std::string Name="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a runtime call for kmpc_Alloc. <a href="#a81bc7a57bd0332843aed6275ba47bee0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a807c913d5889a80440269b74d5755d6c">createOMPFree</a> (const LocationDescription &amp;Loc, Value *Addr, Value *Allocator, std::string Name="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a runtime call for kmpc_free. <a href="#a807c913d5889a80440269b74d5755d6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad89dcb3cd8a39ae57a69487c2988dace">createCachedThreadPrivate</a> (const LocationDescription &amp;Loc, llvm::Value *Pointer, llvm::ConstantInt *Size, const llvm::Twine &amp;Name=Twine(""))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a runtime call for kmpc_threadprivate_cached. <a href="#ad89dcb3cd8a39ae57a69487c2988dace">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7709370a0f6564aa772ce20caa45337e">createOMPInteropInit</a> (const LocationDescription &amp;Loc, Value *InteropVar, omp::OMPInteropType InteropType, Value *Device, Value *NumDependences, Value *DependenceAddress, bool HaveNowaitClause)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a runtime call for __tgt_interop_init. <a href="#a7709370a0f6564aa772ce20caa45337e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38345e93229faed92e719f1793807bb1">createOMPInteropDestroy</a> (const LocationDescription &amp;Loc, Value *InteropVar, Value *Device, Value *NumDependences, Value *DependenceAddress, bool HaveNowaitClause)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a runtime call for __tgt_interop_destroy. <a href="#a38345e93229faed92e719f1793807bb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaef3fb3339c2ade5ffffccdd177e465c">createOMPInteropUse</a> (const LocationDescription &amp;Loc, Value *InteropVar, Value *Device, Value *NumDependences, Value *DependenceAddress, bool HaveNowaitClause)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a runtime call for __tgt_interop_use. <a href="#aaef3fb3339c2ade5ffffccdd177e465c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7db9daa323dee69eb9ecc380ce6edae8">createTargetInit</a> (const LocationDescription &amp;Loc, const llvm::OpenMPIRBuilder::TargetKernelDefaultAttrs &amp;Attrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <span class="doxyComputerOutput">omp target</span> interface. <a href="#a7db9daa323dee69eb9ecc380ce6edae8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e1e2695745252cae26a9843b4d8daa3">createTargetDeinit</a> (const LocationDescription &amp;Loc, int32_t TeamsReductionDataSize=0, int32_t TeamsReductionBufferLength=1024)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a runtime call for kmpc_target_deinit. <a href="#a1e1e2695745252cae26a9843b4d8daa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a567502d7244077ed45e0c9471d31ba4c">emitTargetRegionFunction</a> (TargetRegionEntryInfo &amp;EntryInfo, FunctionGenCallback &amp;GenerateFunctionCallback, bool IsOffloadEntry, Function *&amp;OutlinedFn, Constant *&amp;OutlinedFnID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a unique name for the entry function using the source location information of the current target region. <a href="#a567502d7244077ed45e0c9471d31ba4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17c7f65c3ce26b3b0de6774c0d3c723f">registerTargetRegionFunction</a> (TargetRegionEntryInfo &amp;EntryInfo, Function *OutlinedFunction, StringRef EntryFnName, StringRef EntryFnIDName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Registers the given function and sets up the attribtues of the function Returns the FunctionID. <a href="#a17c7f65c3ce26b3b0de6774c0d3c723f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad01bd2643d37f64f9d9a2933b8ddfc2">emitUserDefinedMapper</a> (function_ref&lt; MapInfosTy &amp;(InsertPointTy CodeGenIP, llvm::Value *PtrPHI, llvm::Value *BeginArg)&gt; PrivAndGenMapInfoCB, llvm::Type *ElemTy, StringRef FuncName, function_ref&lt; bool(unsigned int, Function **)&gt; CustomMapperCB=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the user-defined mapper function. <a href="#aad01bd2643d37f64f9d9a2933b8ddfc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae54a581ccf494afe52ae45af317bbd58">createTargetData</a> (const LocationDescription &amp;Loc, InsertPointTy AllocaIP, InsertPointTy CodeGenIP, Value *DeviceID, Value *IfCond, TargetDataInfo &amp;Info, GenMapInfoCallbackTy GenMapInfoCB, omp::RuntimeFunction *MapperFunc=nullptr, function_ref&lt; InsertPointOrErrorTy(InsertPointTy CodeGenIP, BodyGenTy BodyGenType)&gt; BodyGenCB=nullptr, function_ref&lt; void(unsigned int, Value *)&gt; DeviceAddrCB=nullptr, function_ref&lt; Value *(unsigned int)&gt; CustomMapperCB=nullptr, Value *SrcLocInfo=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> target data'. <a href="#ae54a581ccf494afe52ae45af317bbd58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4d3157abd79d79562db3feb088706f4">createTarget</a> (const LocationDescription &amp;Loc, bool IsOffloadEntry, OpenMPIRBuilder::InsertPointTy AllocaIP, OpenMPIRBuilder::InsertPointTy CodeGenIP, TargetRegionEntryInfo &amp;EntryInfo, const TargetKernelDefaultAttrs &amp;DefaultAttrs, const TargetKernelRuntimeAttrs &amp;RuntimeAttrs, Value *IfCond, SmallVectorImpl&lt; Value * &gt; &amp;Inputs, GenMapInfoCallbackTy GenMapInfoCB, TargetBodyGenCallbackTy BodyGenCB, TargetGenArgAccessorsCallbackTy ArgAccessorFuncCB, SmallVector&lt; DependData &gt; Dependencies={}, bool HasNowait=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> target'. <a href="#aa4d3157abd79d79562db3feb088706f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8191e2fd322236b59afb070919f0d6af">createForStaticInitFunction</a> (unsigned IVSize, bool IVSigned, bool IsGPUDistribute)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns __kmpc_for_static_init_* runtime function for the specified size <em>IVSize</em> and sign <em>IVSigned</em>. <a href="#a8191e2fd322236b59afb070919f0d6af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac7493b7e13af08014a1c49dcdecbf20">createDispatchInitFunction</a> (unsigned IVSize, bool IVSigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns __kmpc_dispatch_init_* runtime function for the specified size <em>IVSize</em> and sign <em>IVSigned</em>. <a href="#aac7493b7e13af08014a1c49dcdecbf20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49dbf0af8f3e1314b3b60222651b6fc2">createDispatchNextFunction</a> (unsigned IVSize, bool IVSigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns __kmpc_dispatch_next_* runtime function for the specified size <em>IVSize</em> and sign <em>IVSigned</em>. <a href="#a49dbf0af8f3e1314b3b60222651b6fc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5946a2c7130bcf42add273f83cb6e257">createDispatchFiniFunction</a> (unsigned IVSize, bool IVSigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns __kmpc_dispatch_fini_* runtime function for the specified size <em>IVSize</em> and sign <em>IVSigned</em>. <a href="#a5946a2c7130bcf42add273f83cb6e257">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2d016504f27bd96960ace8645073d63">createDispatchDeinitFunction</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns __kmpc_dispatch_deinit runtime function. <a href="#ae2d016504f27bd96960ace8645073d63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a388d5a62753f4e7ff4b72e54c1233fbc">createAtomicRead</a> (const LocationDescription &amp;Loc, AtomicOpValue &amp;X, AtomicOpValue &amp;V, AtomicOrdering AO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit atomic Read for : V = X — Only Scalar data types. <a href="#a388d5a62753f4e7ff4b72e54c1233fbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e2de2c034e3083d006b92ddf14b8bcf">createAtomicWrite</a> (const LocationDescription &amp;Loc, AtomicOpValue &amp;X, Value *Expr, AtomicOrdering AO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit atomic write for : X = Expr — Only Scalar data types. <a href="#a0e2de2c034e3083d006b92ddf14b8bcf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae75c4b44f208011259ee93497c2cb411">createAtomicUpdate</a> (const LocationDescription &amp;Loc, InsertPointTy AllocaIP, AtomicOpValue &amp;X, Value *Expr, AtomicOrdering AO, AtomicRMWInst::BinOp RMWOp, AtomicUpdateCallbackTy &amp;UpdateOp, bool IsXBinopExpr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit atomic update for constructs: X = X BinOp Expr ,or X = Expr BinOp X For complex Operations: X = UpdateOp(X) =&gt; CmpExch X, old_X, UpdateOp(X) Only Scalar data types. <a href="#ae75c4b44f208011259ee93497c2cb411">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc340cf5dc46cf45eb6f784577cadbd">createAtomicCapture</a> (const LocationDescription &amp;Loc, InsertPointTy AllocaIP, AtomicOpValue &amp;X, AtomicOpValue &amp;V, Value *Expr, AtomicOrdering AO, AtomicRMWInst::BinOp RMWOp, AtomicUpdateCallbackTy &amp;UpdateOp, bool UpdateExpr, bool IsPostfixUpdate, bool IsXBinopExpr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit atomic update for constructs: — Only Scalar data types V = X; X = X BinOp Expr , X = X BinOp Expr; V = X, V = X; X = Expr BinOp X, X = Expr BinOp X; V = X, V = X; X = UpdateOp(X), X = UpdateOp(X); V = X,. <a href="#a6cc340cf5dc46cf45eb6f784577cadbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c4eeba23c6f192892487de272e8ce72">createAtomicCompare</a> (const LocationDescription &amp;Loc, AtomicOpValue &amp;X, AtomicOpValue &amp;V, AtomicOpValue &amp;R, Value *E, Value *D, AtomicOrdering AO, omp::OMPAtomicCompareOp Op, bool IsXBinopExpr, bool IsPostfixUpdate, bool IsFailOnly)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit atomic compare for constructs: — Only scalar data types cond-expr-stmt: x = x ordop expr ? <a href="#a6c4eeba23c6f192892487de272e8ce72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab84af206a9a08b9bf97eaadc87874c6c">createAtomicCompare</a> (const LocationDescription &amp;Loc, AtomicOpValue &amp;X, AtomicOpValue &amp;V, AtomicOpValue &amp;R, Value *E, Value *D, AtomicOrdering AO, omp::OMPAtomicCompareOp Op, bool IsXBinopExpr, bool IsPostfixUpdate, bool IsFailOnly, AtomicOrdering Failure)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a445fa52d77040bccb16bfea111234a2e">createLoopSkeleton</a> (DebugLoc DL, Value *TripCount, Function *F, BasicBlock *PreInsertBefore, BasicBlock *PostInsertBefore, const Twine &amp;Name={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the control flow structure of a canonical OpenMP loop. <a href="#a445fa52d77040bccb16bfea111234a2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2242b144e54fa6203dae5c5b27fff17c">loadOffloadInfoMetadata</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads all the offload entries information from the host IR metadata. <a href="#a2242b144e54fa6203dae5c5b27fff17c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6293b7ea84a4deac85481dd10dad437">loadOffloadInfoMetadata</a> (StringRef HostFilePath)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads all the offload entries information from the host IR metadata read from the file passed in as the HostFilePath argument. <a href="#ac6293b7ea84a4deac85481dd10dad437">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5ef00e5a7487cc6c5bfed0f301fa1cc">getOrCreateInternalVariable</a> (Type *Ty, const StringRef &amp;Name, unsigned AddressSpace=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets (if variable with the given name already exist) or creates internal global variable with the specified Name. <a href="#aa5ef00e5a7487cc6c5bfed0f301fa1cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3614ae5b7da8dfc1d3b6e74e3b114ae8">applyWorkshareLoopTarget</a> (DebugLoc DL, CanonicalLoopInfo *CLI, InsertPointTy AllocaIP, omp::WorksharingLoopType LoopType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Modifies the canonical loop to be a statically-scheduled workshare loop which is executed on the device. <a href="#a3614ae5b7da8dfc1d3b6e74e3b114ae8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4844b18964505b7687f7261c6eccde30">applyStaticWorkshareLoop</a> (DebugLoc DL, CanonicalLoopInfo *CLI, InsertPointTy AllocaIP, bool NeedsBarrier)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Modifies the canonical loop to be a statically-scheduled workshare loop. <a href="#a4844b18964505b7687f7261c6eccde30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5ac7c7120c51e85a0a9b107b278773f">applyStaticChunkedWorkshareLoop</a> (DebugLoc DL, CanonicalLoopInfo *CLI, InsertPointTy AllocaIP, bool NeedsBarrier, Value *ChunkSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Modifies the canonical loop a statically-scheduled workshare loop with a user-specified chunk size. <a href="#ae5ac7c7120c51e85a0a9b107b278773f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a040fad70b742c2d5fb4df1006b8e2fe4">applyDynamicWorkshareLoop</a> (DebugLoc DL, CanonicalLoopInfo *CLI, InsertPointTy AllocaIP, omp::OMPScheduleType SchedType, bool NeedsBarrier, Value *Chunk=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Modifies the canonical loop to be a dynamically-scheduled workshare loop. <a href="#a040fad70b742c2d5fb4df1006b8e2fe4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af94ce0ccebe00cffe61b5a50ba679eb8">createIfVersion</a> (CanonicalLoopInfo *Loop, Value *IfCond, ValueToValueMapTy &amp;VMap, const Twine &amp;NamePrefix="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create alternative version of the loop to support if clause. <a href="#af94ce0ccebe00cffe61b5a50ba679eb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a009f425138ea4040d027b23d083390">getGPUThreadID</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Supporting functions for Reductions CodeGen. <a href="#a2a009f425138ea4040d027b23d083390">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af903623c40d9e3c2ab371d7591d41bac">getGPUWarpSize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the GPU warp size. <a href="#af903623c40d9e3c2ab371d7591d41bac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94f57a8823240d7bc68dd7c32c0dd882">getNVPTXWarpID</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the id of the warp in the block. <a href="#a94f57a8823240d7bc68dd7c32c0dd882">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a9e43b0db2fb1ca6bee29b4f11130cc">getNVPTXLaneID</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the id of the current lane in the Warp. <a href="#a2a9e43b0db2fb1ca6bee29b4f11130cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cb6bfe878702e37e95e0380de07134c">castValueToType</a> (InsertPointTy AllocaIP, Value *From, Type *ToType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cast value to the specified type. <a href="#a1cb6bfe878702e37e95e0380de07134c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d88ee325115ec9b60143c76f1d52dd6">createRuntimeShuffleFunction</a> (InsertPointTy AllocaIP, Value *Element, Type *ElementType, Value *Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function creates calls to one of two shuffle functions to copy variables between lanes in a warp. <a href="#a0d88ee325115ec9b60143c76f1d52dd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ab8f7d26b196b4d0cff794943f8aea9">shuffleAndStore</a> (InsertPointTy AllocaIP, Value *SrcAddr, Value *DstAddr, Type *ElementType, Value *Offset, Type *ReductionArrayTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> to shuffle over the value from the remote lane. <a href="#a0ab8f7d26b196b4d0cff794943f8aea9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e4dd18eb0b858f2905a2f5f9d12960a">emitReductionListCopy</a> (InsertPointTy AllocaIP, CopyAction Action, Type *ReductionArrayTy, ArrayRef&lt; ReductionInfo &gt; ReductionInfos, Value *SrcBase, Value *DestBase, CopyOptionsTy CopyOptions={nullptr, nullptr, nullptr})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit instructions to copy a Reduce list, which contains partially aggregated values, in the specified direction. <a href="#a2e4dd18eb0b858f2905a2f5f9d12960a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac0d4846664b3da00ab8601767c90a0a">emitShuffleAndReduceFunction</a> (ArrayRef&lt; OpenMPIRBuilder::ReductionInfo &gt; ReductionInfos, Function *ReduceFn, AttributeList FuncAttrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a helper that reduces data across two OpenMP threads (lanes) in the same warp. <a href="#aac0d4846664b3da00ab8601767c90a0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2b92df8e0b82feb2e05a5bb228ff1fc">emitInterWarpCopyFunction</a> (const LocationDescription &amp;Loc, ArrayRef&lt; ReductionInfo &gt; ReductionInfos, AttributeList FuncAttrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function emits a helper that gathers Reduce lists from the first lane of every active warp to lanes in the first warp. <a href="#af2b92df8e0b82feb2e05a5bb228ff1fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a44a77d29e591a2a0c4202074c68e80">emitListToGlobalCopyFunction</a> (ArrayRef&lt; ReductionInfo &gt; ReductionInfos, Type *ReductionsBufferTy, AttributeList FuncAttrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function emits a helper that copies all the reduction variables from the team into the provided global buffer for the reduction variables. <a href="#a9a44a77d29e591a2a0c4202074c68e80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e59efece640b939c81eaf81fa02ab32">emitGlobalToListCopyFunction</a> (ArrayRef&lt; ReductionInfo &gt; ReductionInfos, Type *ReductionsBufferTy, AttributeList FuncAttrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function emits a helper that copies all the reduction variables from the team into the provided global buffer for the reduction variables. <a href="#a2e59efece640b939c81eaf81fa02ab32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89a9562bf041f9579c3a632035c32090">emitListToGlobalReduceFunction</a> (ArrayRef&lt; ReductionInfo &gt; ReductionInfos, Function *ReduceFn, Type *ReductionsBufferTy, AttributeList FuncAttrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function emits a helper that reduces all the reduction variables from the team into the provided global buffer for the reduction variables. <a href="#a89a9562bf041f9579c3a632035c32090">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6401106579001ad5ac42a7332bfffd37">emitGlobalToListReduceFunction</a> (ArrayRef&lt; ReductionInfo &gt; ReductionInfos, Function *ReduceFn, Type *ReductionsBufferTy, AttributeList FuncAttrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function emits a helper that reduces all the reduction variables from the team into the provided global buffer for the reduction variables. <a href="#a6401106579001ad5ac42a7332bfffd37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eea64b337e04e34f135fe9294eeb941">getReductionFuncName</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the function name of a reduction function. <a href="#a6eea64b337e04e34f135fe9294eeb941">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad623afd8ebb3dfc080662cb43391b856">createReductionFunction</a> (StringRef ReducerName, ArrayRef&lt; ReductionInfo &gt; ReductionInfos, ReductionGenCBKind ReductionGenCBKind=ReductionGenCBKind::MLIR, AttributeList FuncAttrs={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits reduction function. <a href="#ad623afd8ebb3dfc080662cb43391b856">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace5c16ccd45a0ce550055164ab081b5a">setOutlinedTargetRegionFunctionAttributes</a> (Function *OutlinedFn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#ace5c16ccd45a0ce550055164ab081b5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b89b3ff925ab192f9ae19165b342f83">createOutlinedFunctionID</a> (Function *OutlinedFn, StringRef EntryFnIDName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1713e12dd45c8fe0066bc7294cb18e7a">createTargetRegionEntryAddr</a> (Function *OutlinedFunction, StringRef EntryFnName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c12e64fffe008109723c3ca4618f988">emitUDMapperArrayInitOrDel</a> (Function *MapperFn, llvm::Value *MapperHandle, llvm::Value *Base, llvm::Value *Begin, llvm::Value *Size, llvm::Value *MapType, llvm::Value *MapName, TypeSize ElementSize, llvm::BasicBlock *ExitBB, bool IsInit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the array initialization or deletion portion for user-defined mapper code generation. <a href="#a9c12e64fffe008109723c3ca4618f988">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b69d9afaff34536b7ccc2ec990ae656">initializeTypes</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#a6b69d9afaff34536b7ccc2ec990ae656">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4f8d828d3259d777583fd581935f8e9">emitCommonDirectiveEntry</a> (omp::Directive OMPD, Value *EntryCall, BasicBlock *ExitBB, bool Conditional=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common interface for generating entry calls for OMP Directives. <a href="#af4f8d828d3259d777583fd581935f8e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a229ff4e9eef9f328f8200b1cf14ac699">emitCommonDirectiveExit</a> (omp::Directive OMPD, InsertPointTy FinIP, Instruction *ExitCall, bool HasFinalize=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common interface to finalize the region. <a href="#a229ff4e9eef9f328f8200b1cf14ac699">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a233f727933cae11ca5eed3ba2142bf41">EmitOMPInlinedRegion</a> (omp::Directive OMPD, Instruction *EntryCall, Instruction *ExitCall, BodyGenCallbackTy BodyGenCB, FinalizeCallbackTy FiniCB, bool Conditional=false, bool HasFinalize=true, bool IsCancellable=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common Interface to generate OMP inlined regions. <a href="#a233f727933cae11ca5eed3ba2142bf41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4910b0d2c5749629437e9c52bc639c7f">getOMPCriticalRegionLock</a> (StringRef CriticalName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns corresponding lock object for the specified critical region name. <a href="#a4910b0d2c5749629437e9c52bc639c7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9851d43b78a60e8de23a05bc9728e9b">checkAndEmitFlushAfterAtomic</a> (const LocationDescription &amp;Loc, AtomicOrdering AO, AtomicKind AK)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether to emit flush or not. <a href="#ad9851d43b78a60e8de23a05bc9728e9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6d8ea685a6567c8b8747c7ac1545788">emitAtomicUpdate</a> (InsertPointTy AllocaIP, Value *X, Type *XElemTy, Value *Expr, AtomicOrdering AO, AtomicRMWInst::BinOp RMWOp, AtomicUpdateCallbackTy &amp;UpdateOp, bool VolatileX, bool IsXBinopExpr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit atomic update for constructs: X = X BinOp Expr ,or X = Expr BinOp X For complex Operations: X = UpdateOp(X) =&gt; CmpExch X, old_X, UpdateOp(X) Only Scalar data types. <a href="#aa6d8ea685a6567c8b8747c7ac1545788">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a145de1d8971dac0fcc64919ecc758f3e">emitRMWOpAsInstruction</a> (Value *Src1, Value *Src2, AtomicRMWInst::BinOp RMWOp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the binary op. <a href="#a145de1d8971dac0fcc64919ecc758f3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/finalizationinfo">FinalizationInfo</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75f3209cae3f3f2700c6bc6e9623f841">FinalizationStack</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The finalization stack made up of finalize callbacks currently in-flight, wrapped into <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/finalizationinfo">FinalizationInfo</a> objects that reference also the finalization target block and the kind of cancellable directive. <a href="#a75f3209cae3f3f2700c6bc6e9623f841">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/openmpirbuilderconfig">OpenMPIRBuilderConfig</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a355507f9e59388e467dc9288e4f82c3d">Config</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder">OpenMPIRBuilder</a> Configuration. <a href="#a355507f9e59388e467dc9288e4f82c3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a535304630869bfe0b7c0a81bb3c44497">M</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The underlying LLVM-IR module. <a href="#a535304630869bfe0b7c0a81bb3c44497">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The LLVM-IR Builder used to create IR. <a href="#ad90c28bb43cb3cee06cb2f1686784b40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a539b79b038631cce06319250c09f8cfd">SrcLocStrMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map to remember source location strings. <a href="#a539b79b038631cce06319250c09f8cfd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *, uint64_t &gt;, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a801d4c8626e9914c0bc6b756c64c0730">IdentMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map to remember existing ident_t*. <a href="#a801d4c8626e9914c0bc6b756c64c0730">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager">OffloadEntriesInfoManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed2a8b469e9884788eef400fbc892dd3">OffloadInfoManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Info manager to keep track of target regions. <a href="#aed2a8b469e9884788eef400fbc892dd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f3588f949f4fb51454b0b8c6194ca75">T</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The target triple of the underlying module. <a href="#a7f3588f949f4fb51454b0b8c6194ca75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo">OutlineInfo</a>, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79e8ec8cdc9299c9bab67b625e6578c5">OutlineInfos</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection of regions that need to be outlined during finalization. <a href="#a79e8ec8cdc9299c9bab67b625e6578c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebfa8e874069dcc7e02ea471d941d9ca">ConstantAllocaRaiseCandidates</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A collection of candidate target functions that's constant allocas will attempt to be raised on a call of finalize after all currently enqueued outline info's have been processed. <a href="#aebfa8e874069dcc7e02ea471d941d9ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::forward_list&lt; <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a418fd65883c81897f472643208a988b4">LoopInfos</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection of owned canonical loop objects that eventually need to be free'd. <a href="#a418fd65883c81897f472643208a988b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa58c09ca23b31b6bebfa825111dc3923">InternalVars</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An ordered map of auto-generated variables to their unique names. <a href="#aa58c09ca23b31b6bebfa825111dc3923">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefadc356da16598ff8c210dafbf4a2b7">ompOffloadInfoName</a> = "omp_offload.info"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OMP Offload Info <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> name string. <a href="#aefadc356da16598ff8c210dafbf4a2b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5b407054e7727d04053af9c3f1a5568">getOpenMPDefaultSimdAlign</a> (const Triple &amp;TargetTriple, const StringMap&lt; bool &gt; &amp;Features)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the default alignment value for given target. <a href="#ac5b407054e7727d04053af9c3f1a5568">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12b066e3e9cc61240457d12df75df64b">getTargetEntryUniqueInfo</a> (FileIdentifierInfoCallbackTy CallBack, StringRef ParentName="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a unique info for a target entry when provided a filename and line number from. <a href="#a12b066e3e9cc61240457d12df75df64b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49e1f0512e7d7b37dfcecc0b25dd875b">getKernelArgsVector</a> (TargetKernelArgs &amp;KernelArgs, IRBuilderBase &amp;Builder, SmallVector&lt; Value * &gt; &amp;ArgsVector)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the kernel args vector used by emitTargetKernel. <a href="#a49e1f0512e7d7b37dfcecc0b25dd875b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; int32_t, int32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a321704fa9e503d47cab3eec5492f35ba">readThreadBoundsForKernel</a> (const Triple &amp;T, Function &amp;Kernel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#a321704fa9e503d47cab3eec5492f35ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ea31ab1f2b7d1f5585df18b0528fcf3">writeThreadBoundsForKernel</a> (const Triple &amp;T, Function &amp;Kernel, int32_t LB, int32_t UB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; int32_t, int32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed359885b0e344d18e4921011813748b">readTeamBoundsForKernel</a> (const Triple &amp;T, Function &amp;Kernel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read/write a bounds on teams for <span class="doxyComputerOutput">Kernel</span>. <a href="#aed359885b0e344d18e4921011813748b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab79b6d86df13a709eee10c4c7d39c644">writeTeamsForKernel</a> (const Triple &amp;T, Function &amp;Kernel, int32_t LB, int32_t UB)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad724b3adf53754848d6f9ac6818ef34e">getNameWithSeparators</a> (ArrayRef&lt; StringRef &gt; Parts, StringRef FirstSeparator, StringRef Separator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the platform-specific name separator. <a href="#ad724b3adf53754848d6f9ac6818ef34e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>An interface to create LLVM-IR for OpenMP directives.</p>


<p>Each OpenMP directive has a corresponding public generator method.</p>


<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BodyGenCallbackTy {#a49e35e3ee470add16efcde1ab5d5556b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::BodyGenCallbackTy = 
      function_ref&lt;Error(InsertPointTy AllocaIP, InsertPointTy CodeGenIP)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback type for body (=inner region) code generation.</p>


<p>The callback takes code locations as arguments, each describing a location where additional instructions can be inserted.</p>


<p>The CodeGenIP may be in the middle of a basic block or point to the end of it. The basic block may have a terminator or be degenerate. The callback function may just insert instructions at that position, but also split the block (without the Before argument of <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a52c990590792c91dd20b6d45acebe359">BasicBlock::splitBasicBlock</a> such that the identify of the split predecessor block is preserved) and insert additional control flow, including branches that do not lead back to what follows the CodeGenIP. Note that since the callback is allowed to split the block, callers must assume that InsertPoints to positions in the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> after CodeGenIP including CodeGenIP itself are invalidated. If such InsertPoints need to be preserved, it can split the block itself before calling the callback.</p>


<p>AllocaIP and CodeGenIP must not point to the same position.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>is the insertion point at which new alloca instructions should be placed. The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> it is pointing to must not be split.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CodeGenIP</td>
<td class="doxyParamItemDescription"><p>is the insertion point at which the body code should be placed.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an error, if any were triggered during execution.</p></dd>
</dl>


<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### EmitFallbackCallbackTy {#a8be6d9636392371c1467984a429573a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::EmitFallbackCallbackTy = 
      function_ref&lt;InsertPointOrErrorTy(InsertPointTy)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback function type for functions emitting the host fallback code that is executed when the kernel launch fails.</p>


<p>It takes an insertion point as parameter where the code should be emitted. It returns an insertion point that points right after after the emitted code.</p>


<p>Definition at line 2405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### EmitMetadataErrorReportFunctionTy {#af45ce5586729bfa3160eaa9cec64e0f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::EmitMetadataErrorReportFunctionTy = 
      std::function&lt;void(EmitMetadataErrorKind, TargetRegionEntryInfo)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback function type.</p>

<p>Definition at line 2508 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### FileIdentifierInfoCallbackTy {#ad324bf833c1de81f7dfdbd943660e9bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::FileIdentifierInfoCallbackTy = 
      std::function&lt;std::tuple&lt;std::string, uint64_t&gt;()&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### FinalizeCallbackTy {#a0c571620ff53fdb78e7404f5261dbd23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::FinalizeCallbackTy =  std::function&lt;Error(InsertPointTy CodeGenIP)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback type for variable finalization (think destructors).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CodeGenIP</td>
<td class="doxyParamItemDescription"><p>is the insertion point at which the finalization code should be placed.</p></td>
</tr>
</table>
</dd>
</dl>

<p>A finalize callback knows about all objects that need finalization, e.g. destruction, when the scope of the currently generated construct is left at the time, and location, the callback is invoked.</p>


<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### FunctionGenCallback {#a05c4178639e79ab4749063b330cff5da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::FunctionGenCallback = 
      std::function&lt;Expected&lt;Function *&gt;(StringRef FunctionName)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Functions used to generate a function with the given name.</p>

<p>Definition at line 2826 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### GenMapInfoCallbackTy {#a249878a72f57b4634ae65800060983f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::GenMapInfoCallbackTy = 
      function_ref&lt;MapInfosTy &amp;(InsertPointTy CodeGenIP)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback type for creating the map infos for the kernel parameters.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CodeGenIP</td>
<td class="doxyParamItemDescription"><p>is the insertion point where code should be generated, if any.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 2894 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### InsertPointOrErrorTy {#af24d1c61cec57095ced3b08a6dd99ee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::InsertPointOrErrorTy =  Expected&lt;InsertPointTy&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> used to represent an insertion point or an error value.</p>

<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### InsertPointTy {#aafc1886793b898052f87edd7e9fdbaa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::InsertPointTy =  IRBuilder&lt;&gt;::InsertPoint</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> used throughout for insertion points.</p>

<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### LoopBodyGenCallbackTy {#a296d2e28bddf1051d614f48b61005899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::LoopBodyGenCallbackTy = 
      function_ref&lt;Error(InsertPointTy CodeGenIP, Value *IndVar)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback type for loop body code generation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CodeGenIP</td>
<td class="doxyParamItemDescription"><p>is the insertion point where the loop's body code must be placed. This will be a dedicated <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> with a conditional branch from the loop condition check and terminated with an unconditional branch to the loop latch.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IndVar</td>
<td class="doxyParamItemDescription"><p>is the induction variable usable at the insertion point.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an error, if any were triggered during execution.</p></dd>
</dl>


<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### MapDeviceInfoArrayTy {#a751d216ddce395dc7fa49fcf8e0a82c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::MapDeviceInfoArrayTy =  SmallVector&lt;DeviceInfoTy, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### MapDimArrayTy {#a44f261ea64dfab54a32fedf028c7c33f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::MapDimArrayTy =  SmallVector&lt;uint64_t, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### MapFlagsArrayTy {#a62976e7f4bbb16d15c3483044afe20e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::MapFlagsArrayTy =  SmallVector&lt;omp::OpenMPOffloadMappingFlags, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### MapNamesArrayTy {#a4ab7cfa9fab97684d498b889987bcc74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::MapNamesArrayTy =  SmallVector&lt;Constant *, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### MapNonContiguousArrayTy {#a708e1a451b8b9f851317bbd2ab0d9118}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::MapNonContiguousArrayTy =  SmallVector&lt;MapValuesArrayTy, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### MapValuesArrayTy {#a83dc195f27cf9d455f808cd6d0d17e57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::MapValuesArrayTy =  SmallVector&lt;Value *, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### PrivatizeCallbackTy {#a71b5ba020f68829f5a1fd99f48b63d42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::PrivatizeCallbackTy =  function_ref&lt;InsertPointOrErrorTy(
      InsertPointTy AllocaIP, InsertPointTy CodeGenIP, Value &amp;Original,
      Value &amp;Inner, Value *&amp;ReplVal)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback type for variable privatization (think copy &amp; default constructor).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>is the insertion point at which new alloca instructions should be placed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CodeGenIP</td>
<td class="doxyParamItemDescription"><p>is the insertion point at which the privatization code should be placed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Original</td>
<td class="doxyParamItemDescription"><p>The value being copied/created, should not be used in the generated IR.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Inner</td>
<td class="doxyParamItemDescription"><p>The equivalent of <span class="doxyComputerOutput">Original</span> that should be used in the generated IR; this is equal to <span class="doxyComputerOutput">Original</span> if the value is a pointer and can thus be passed directly, otherwise it is an equivalent but different value.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReplVal</td>
<td class="doxyParamItemDescription"><p>The replacement value, thus a copy or new created version of <span class="doxyComputerOutput">Inner</span>.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The new insertion point where code generation continues and <span class="doxyComputerOutput">ReplVal</span> the replacement value.</p></dd>
</dl>


<p>Definition at line 639 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### ReductionGenAtomicCBTy {#ab81d602b13a50807afdda254fe16aecf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::ReductionGenAtomicCBTy =  std::function&lt;InsertPointOrErrorTy(
      InsertPointTy, Type *, Value *, Value *)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Functions used to generate atomic reductions.</p>


<p>Such functions take two Values representing pointers to LHS and RHS of the reduction, as well as the element type of these pointers. They are expected to atomically update the LHS to the reduced value.</p>


<p>Definition at line 1328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### ReductionGenCBTy {#a3aadc019775907d5ff516545c5d2bfc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::ReductionGenCBTy =  std::function&lt;InsertPointOrErrorTy(
      InsertPointTy CodeGenIP, Value *LHS, Value *RHS, Value *&amp;Res)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ReductionGen CallBack for MLIR.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CodeGenIP</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/irbuilder">InsertPoint</a> for CodeGen.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LHS</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> in the LHS <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to be used for CodeGen.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RHS</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> in the RHS <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to be used for CodeGen.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### ReductionGenClangCBTy {#a20304a012a6cc83d8114222bb0337228}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::ReductionGenClangCBTy = 
      std::function&lt;InsertPointTy(InsertPointTy CodeGenIP, unsigned Index,
                                  Value **LHS, Value **RHS, Function *CurFn)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ReductionGen CallBack for Clang.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CodeGenIP</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/irbuilder">InsertPoint</a> for CodeGen.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Index</td>
<td class="doxyParamItemDescription"><p>Index of the <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/reductioninfo">ReductionInfo</a> to generate code for.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LHSPtr</td>
<td class="doxyParamItemDescription"><p>Optionally used by Clang to return the LHSPtr it used for codegen, used for fixup later.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RHSPtr</td>
<td class="doxyParamItemDescription"><p>Optionally used by Clang to return the RHSPtr it used for codegen, used for fixup later.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CurFn</td>
<td class="doxyParamItemDescription"><p>Optionally used by Clang to pass in the Current <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> as Clang context may be old.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### StorableBodyGenCallbackTy {#a761a2c853c1d16b33e4e8c565ce0ca45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::StorableBodyGenCallbackTy = 
      std::function&lt;Error(InsertPointTy AllocaIP, InsertPointTy CodeGenIP)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an error, if any were triggered during execution.</p></dd>
</dl>


<p>Definition at line 605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### TargetBodyGenCallbackTy {#a73e20c5fd6145c56d7ce35c2ccd99e5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::TargetBodyGenCallbackTy =  function_ref&lt;InsertPointOrErrorTy(
      InsertPointTy AllocaIP, InsertPointTy CodeGenIP)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2987 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### TargetGenArgAccessorsCallbackTy {#a3ad579ff0c72b56f5ebc91bf2d747bc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::TargetGenArgAccessorsCallbackTy =  function_ref&lt;InsertPointOrErrorTy(
      Argument &amp;Arg, Value *Input, Value *&amp;RetVal, InsertPointTy AllocaIP,
      InsertPointTy CodeGenIP)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2990 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### TargetTaskBodyCallbackTy {#a5f44f79e28451e12a142140450888ecd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::TargetTaskBodyCallbackTy = 
      function_ref&lt;Error(Value *DeviceID, Value *RTLoc,
                         IRBuilderBase::InsertPoint TargetTaskAllocaIP)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback type for generating the bodies of device directives that require outer target tasks (e.g.</p>


<p>in case of having <span class="doxyComputerOutput">nowait</span> or <span class="doxyComputerOutput">depend</span> clauses).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DeviceID</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the device on which the target region will execute.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RTLoc</td>
<td class="doxyParamItemDescription"><p>Source location identifier \Param TargetTaskAllocaIP Insertion point for the alloca block of the generated task.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an error, if any were triggered during execution.</p></dd>
</dl>


<p>Definition at line 2434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### AtomicUpdateCallbackTy {#ab08e2c502864d33cabeb9b78dfe3cc02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::AtomicUpdateCallbackTy = 
      const function_ref&lt;Expected&lt;Value *&gt;(Value *XOld, IRBuilder&lt;&gt; &amp;IRB)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback type for Atomic <a href="/web-llvm/docs/api/classes/llvm/expression">Expression</a> update ex:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea9dd4e461268c8034f5c8564e155c67a6">x</a> = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#pragma omp atomic update</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea9dd4e461268c8034f5c8564e155c67a6">x</a> = Expr(x_old);  </span><span class="doxyHighlightComment">//Expr() is any legal operation</span></span></div>

</div>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">XOld</td>
<td class="doxyParamItemDescription"><p>the value of the atomic memory address to use for update</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IRB</td>
<td class="doxyParamItemDescription"><p>reference to the <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a> to use</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to update X to.</p></dd>
</dl>


<p>Definition at line 3155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### AtomicKind {#aa014f633c701cbd3313b654114f15d09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::OpenMPIRBuilder::AtomicKind </td>
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
<td class="doxyEnumItemName">Read<a id="aa014f633c701cbd3313b654114f15d09aee5b082c4c048b7f5e407831b1fb9bb2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Write<a id="aa014f633c701cbd3313b654114f15d09abadd6a9c3354fb40c14976ced7341346"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Update<a id="aa014f633c701cbd3313b654114f15d09a6465ba3aabe647694318a6a352119155"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Capture<a id="aa014f633c701cbd3313b654114f15d09a6a3278e06e29ac7975fca075bee3a268"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Compare<a id="aa014f633c701cbd3313b654114f15d09a0f65573ec76317550c7a2c4171207e4d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 3159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### BodyGenTy {#ae620d2ad309b2b4959c64edd1e040fdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::OpenMPIRBuilder::BodyGenTy </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of BodyGen to use for region codegen.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Priv<a id="ae620d2ad309b2b4959c64edd1e040fdfa69cba2948bbfa254aa9dbd932f56756b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DupNoPriv<a id="ae620d2ad309b2b4959c64edd1e040fdfac713c54bd088154d1f8a01438eebd845"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoPriv<a id="ae620d2ad309b2b4959c64edd1e040fdfa7b1cf924c5bb380dcfd0245879230285"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>Priv: If device pointer privatization is required, emit the body of the region here. It will have to be duplicated: with and without privatization. DupNoPriv: If we need device pointer privatization, we need to emit the body of the region with no privatization in the 'else' branch of the conditional. NoPriv: If we don't require privatization of device pointers, we emit the body in between the runtime calls. This avoids duplicating the body code.</p>


<p>Definition at line 2889 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### CopyAction {#a204d79d34d33ba7563337995bb481318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::OpenMPIRBuilder::CopyAction : unsigned</td>
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


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RemoteLaneToThread<a id="a204d79d34d33ba7563337995bb481318a60e9ee6dc3ddffbfde1967f74796fe30"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ThreadCopy<a id="a204d79d34d33ba7563337995bb481318ac6da974386a468413b3378af0d755553"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### DeviceInfoTy {#a5fd26a28fedc9044dd6939648d55c429}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::OpenMPIRBuilder::DeviceInfoTy </td>
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


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">None<a id="a5fd26a28fedc9044dd6939648d55c429a6adf97f83acf6453d4a6a4b1070f3754"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer<a id="a5fd26a28fedc9044dd6939648d55c429a61cf8510205077b6f5491d38cd44c0f7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Address<a id="a5fd26a28fedc9044dd6939648d55c429add7bf230fde8d4836917806aff6a6b27"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 2353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### EmitMetadataErrorKind {#affb389ba6facf4b5854565f9db5bc90b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::OpenMPIRBuilder::EmitMetadataErrorKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The kind of errors that can occur when emitting the offload entries and metadata.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EMIT_MD_TARGET_REGION_ERROR<a id="affb389ba6facf4b5854565f9db5bc90baf5ff390a87124f22662146233ca4ff72"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EMIT_MD_DECLARE_TARGET_ERROR<a id="affb389ba6facf4b5854565f9db5bc90ba2ff4496ec84c0d33c078284970aa331c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EMIT_MD_GLOBAL_VAR_LINK_ERROR<a id="affb389ba6facf4b5854565f9db5bc90ba6c60cf0594c5dae6dfab7b5abbdea97d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 2501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### EvalKind {#a0f3b3f2ce3e462711213b2ecb34e904c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::OpenMPIRBuilder::EvalKind </td>
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

<p>Enum class for reduction evaluation types scalar, complex and aggregate.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Scalar<a id="a0f3b3f2ce3e462711213b2ecb34e904caf60357a8d17e45793298323f1b372a74"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Complex<a id="a0f3b3f2ce3e462711213b2ecb34e904ca10b4eb76294b70d7fd6df997ff06edb1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Aggregate<a id="a0f3b3f2ce3e462711213b2ecb34e904ca2ee34178bb8415b7d7234cd27b83aed6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### ReductionGenCBKind {#a07f00f83b415baecc1af353eed43d123}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::OpenMPIRBuilder::ReductionGenCBKind </td>
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

<p>Enum class for the RedctionGen CallBack type to be used.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Clang<a id="a07f00f83b415baecc1af353eed43d123a9375884cf4ed31c834a626c324dddc67"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MLIR<a id="a07f00f83b415baecc1af353eed43d123a1744373124bab4b9336c0d19a141a1d1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### OpenMPIRBuilder() {#ae1a990c96a3ebf58698901d09c5b4378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OpenMPIRBuilder::OpenMPIRBuilder (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder">OpenMPIRBuilder</a> operating on the given module <span class="doxyComputerOutput">M</span>.</p>


<p>This will not have an effect on <span class="doxyComputerOutput">M</span> (see initialize)</p>


<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="#aed2a8b469e9884788eef400fbc892dd3">OffloadInfoManager</a> and <a href="#a7f3588f949f4fb51454b0b8c6194ca75">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~OpenMPIRBuilder() {#ad66949e2e846451e61d9c8f34014ea31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::~OpenMPIRBuilder ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 845 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a79e8ec8cdc9299c9bab67b625e6578c5">OutlineInfos</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAttributes() {#a50c6490cf353f064946c4e32673ac098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::addAttributes (<a href="/web-llvm/docs/api/namespaces/llvm/omp/#a4c503140c7f851151906d85b515330e9">omp::RuntimeFunction</a> FnID, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add attributes known for <span class="doxyComputerOutput">FnID</span> to <span class="doxyComputerOutput">Fn</span>.</p>

<p>Declaration at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributeset/#af2b9418751d1f1f1b99e5b05d0ed7efa">llvm::AttributeSet::addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a46f189c4026ace551d70a16566e641b1">llvm::AttributeSet::addAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#ac6baa801e4aea800984e760d5460662f">llvm::Function::arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a7477aafbbe989ad35b96fac186d8e9fd">llvm::Function::getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a> and <a href="#a7f3588f949f4fb51454b0b8c6194ca75">T</a>.</p>


<p>Referenced by <a href="#a034dc6253a2a36f78ac071a7c12d5c27">getOrCreateRuntimeFunction</a>.</p>

</div>
</div>

### addOutlineInfo() {#a5610e0ef8f016e84694778d8ce1c9479}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::OpenMPIRBuilder::addOutlineInfo (<a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo">OutlineInfo</a> &amp;&amp; OI)</td>
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

<p>Add a new region that will be outlined later.</p>

<p>Definition at line 2134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Reference <a href="#a79e8ec8cdc9299c9bab67b625e6578c5">OutlineInfos</a>.</p>


<p>Referenced by <a href="#a4f81b9940e1869e146636dc533455929">createParallel</a>, <a href="#a0af3c7a02c1325c04c59f857604bd4f3">createTask</a>, <a href="#a3f603d822817256077c95e6573f2b14a">createTeams</a> and <a href="#a2841680b34ec9c2c7185a877f8f8b4c8">emitTargetTask</a>.</p>

</div>
</div>

### applySimd() {#acd1fbb2df257f945afda92919be322f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::applySimd (<a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * Loop, <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; AlignedVars, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * IfCond, omp::OrderKind Order, <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * Simdlen, <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * Safelen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add metadata to simd-ize a loop.</p>


<p>If IfCond is not nullptr, the loop is cloned. The metadata which prevents vectorization is added to to the cloned loop. The cloned loop is executed when ifCond is evaluated to false.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/loop"&gt;Loop&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The loop to simd-ize.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignedVars</td>
<td class="doxyParamItemDescription"><p>The map which containts pairs of the pointer and its corresponding alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IfCond</td>
<td class="doxyParamItemDescription"><p>The value which corresponds to the if clause condition.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Order</td>
<td class="doxyParamItemDescription"><p>The enum to map order clause.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Simdlen</td>
<td class="doxyParamItemDescription"><p>The Simdlen length to apply to the simd loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Safelen</td>
<td class="doxyParamItemDescription"><p>The Safelen length to apply to the simd loop.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5342 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#ac36177cea684b1e36fdbc92d692f69d0">addBasicBlockMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#adf813540e363817b85e9eecef51269b5">addLoopMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a545cc7eb4f94d0957ba9960a69b10a90">addSimdMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#acb5b5b136597312e0d5df6b746a7e6db">llvm::CanonicalLoopInfo::getCond</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a21a975fd58c287a6ca3f1c89c048e7d3">llvm::MDNode::getDistinct</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a9592feb460b27d417f42a41aabfe253a">llvm::CanonicalLoopInfo::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a01c4471afa921c4962d7138cfcef4942">llvm::CanonicalLoopInfo::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#ac37a6cf77f6f82b6bb28af4d9c8626d0">llvm::CanonicalLoopInfo::getLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#a62ee7ece4986606d41363bc1f70d5ab2">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getNextNode</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/valuemap/#a15f92579a5fc316dab8cd1fad51015ef">llvm::ValueMap&lt; KeyT, ValueT, Config &gt;::lookup</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/loopanalysis/#aea38b668f2d98b7e9f64b8b3c2e524dc">llvm::LoopAnalysis::run</a> and <a href="/web-llvm/docs/api/classes/llvm/mapvector/#acf4c09e1f30cdd4e0b5b1b8a236ead34">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::size</a>.</p>

</div>
</div>

### applyWorkshareLoop() {#adaa14806d128ad33bdc48d2bfc46870c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::applyWorkshareLoop (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * CLI, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, bool NeedsBarrier, llvm::omp::ScheduleKind SchedKind=llvm::omp::OMP_SCHEDULE_Default, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ChunkSize=nullptr, bool HasSimdModifier=false, bool HasMonotonicModifier=false, bool HasNonmonotonicModifier=false, bool HasOrderedClause=false, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#ab6fb146c332fd3f3d677ee65081fe669">omp::WorksharingLoopType</a> LoopType=<a href="/web-llvm/docs/api/namespaces/llvm/omp/#ab6fb146c332fd3f3d677ee65081fe669a45663d75b039e00b6412fb82fed8c306">omp::WorksharingLoopType::ForStaticLoop</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Modifies the canonical loop to be a workshare loop.</p>


<p>This takes a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a></span> representing a canonical loop, such as the one created by <span class="doxyComputerOutput">createCanonicalLoop</span> and emits additional instructions to turn it into a workshare loop. In particular, it calls to an OpenMP runtime function in the preheader to obtain the loop bounds to be used in the current thread, updates the relevant instructions in the canonical loop and calls to an OpenMP runtime finalization function after the loop.</p>


<p>The concrete transformation is done by applyStaticWorkshareLoop, applyStaticChunkedWorkshareLoop, or applyDynamicWorkshareLoop, depending on the value of <span class="doxyComputerOutput">SchedKind</span> and <span class="doxyComputerOutput">ChunkSize</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug location for instructions added for the workshare-loop construct itself.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CLI</td>
<td class="doxyParamItemDescription"><p>A descriptor of the canonical loop to workshare.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>An insertion point for Alloca instructions usable in the preheader of the loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NeedsBarrier</td>
<td class="doxyParamItemDescription"><p>Indicates whether a barrier must be insterted after the loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SchedKind</td>
<td class="doxyParamItemDescription"><p>Scheduling algorithm to use.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ChunkSize</td>
<td class="doxyParamItemDescription"><p>The chunk size for the inner loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HasSimdModifier</td>
<td class="doxyParamItemDescription"><p>Whether the simd modifier is present in the schedule clause.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HasMonotonicModifier</td>
<td class="doxyParamItemDescription"><p>Whether the monotonic modifier is present in the schedule clause.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HasNonmonotonicModifier</td>
<td class="doxyParamItemDescription"><p>Whether the nonmonotonic modifier is present in the schedule clause.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HasOrderedClause</td>
<td class="doxyParamItemDescription"><p>Whether the (parameterless) ordered clause is present.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LoopType</td>
<td class="doxyParamItemDescription"><p>Information about type of loop worksharing. It corresponds to type of loop workshare OpenMP pragma.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Point where to insert code after the workshare construct.</p></dd>
</dl>


<p>Declaration at line 1107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 4621 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a554000c782275642b783964853720bee">computeOpenMPScheduleType</a>, <a href="#a355507f9e59388e467dc9288e4f82c3d">Config</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### collapseLoops() {#a08610118e213de1b759470f0eafb9b18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CanonicalLoopInfo * OpenMPIRBuilder::collapseLoops (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * &gt; Loops, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> ComputeIP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collapse a loop nest into a single loop.</p>


<p>Merges loops of a loop nest into a single CanonicalLoopNest representation that has the same number of innermost loop iterations as the origin loop nest. The induction variables of the input loops are derived from the collapsed loop's induction variable. This is intended to be used to implement OpenMP's collapse clause. Before applying a directive, collapseLoops normalizes a loop nest to contain only a single loop and the directive's implementation does not need to handle multiple loops itself. This does not remove the need to handle all loop nest handling by directives, such as the ordered(&lt;n&gt;) clause or the simd schedule-clause modifier of the worksharing-loop directive.</p>


<p>Example:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = 0; i &lt; 7; ++i) </span><span class="doxyHighlightComment">// Canonical loop "i"</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> j = 0; <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea363b122c528f54df4a0446b6bab05515">j</a> &lt; 9; ++<a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea363b122c528f54df4a0446b6bab05515">j</a>) </span><span class="doxyHighlightComment">// Canonical loop "j"</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    body(i, j);</span></span></div>

</div>


<p>After collapsing with Loops={i,j}, the loop is changed to</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ij = 0; ij &lt; 63; ++ij) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = ij / 9;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea363b122c528f54df4a0446b6bab05515">j</a> = ij % 9;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  body(i, j);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>In the current implementation, the following limitations apply:</p>


<ul class="doxyList ">
<li>All input loops have an induction variable of the same type.</li>
<li>The collapsed loop will have the same trip count integer type as the input loops. Therefore it is possible that the collapsed loop cannot represent all iterations of the input loops. For instance, assuming a 32 bit integer type, and two input loops both iterating 2^16 times, the theoretical trip count of the collapsed loop would be 2^32 iteration, which cannot be represented in an 32-bit integer. Behavior is undefined in this case.</li>
<li>The trip counts of every input loop must be available at <span class="doxyComputerOutput">ComputeIP</span>. Non-rectangular loops are not yet supported.</li>
<li>At each nest level, code between a surrounding loop and its nested loop is hoisted into the loop body, and such code will be executed more often than before collapsing (or not at all if any inner loop iteration has a trip count of 0). This is permitted by the OpenMP specification.</li>
</ul>

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug location for instructions added for collapsing, such as instructions to compute/derive the input loop's induction variables.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Loops</td>
<td class="doxyParamItemDescription"><p>Loops in the loop nest to collapse. Loops are specified from outermost-to-innermost and every control flow of a loop's body must pass through its directly nested loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ComputeIP</td>
<td class="doxyParamItemDescription"><p>Where additional instruction that compute the collapsed trip count. If not set, defaults to before the generated loop.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> object representing the collapsed loop.</p></dd>
</dl>


<p>Declaration at line 842 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 4887 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#a445fa52d77040bccb16bfea111234a2e">createLoopSkeleton</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a92d8bce979891dc43b6573e8cca2e58c">llvm::CanonicalLoopInfo::getAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a47521ec347ef7b522745bf89e2e2d19a">llvm::CanonicalLoopInfo::getBody</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#ac37a6cf77f6f82b6bb28af4d9c8626d0">llvm::CanonicalLoopInfo::getLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#a62ee7ece4986606d41363bc1f70d5ab2">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getNextNode</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#ad50eb30e70ff2a9ea7f220547e2b6f6d">llvm::CanonicalLoopInfo::getPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#ac72ebc430ef7dcf1791c66080ddedd9d">llvm::CanonicalLoopInfo::getPreheaderIP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/insertpoint/#a85b9635b21610f18b51007437bcc26cf">llvm::IRBuilderBase::InsertPoint::isSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp/#ada7c1594a393ede3ce32602d64d7ddb2">Loops</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#abdcdbfc178873f5055fbcf98bad92f53">redirectAllPredecessorsTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3057c2b7e1e25de160497b1ef3985c2a">redirectTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af0ce60c4a958016f62ce78f1eda423af">removeUnusedBlocksFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>.</p>

</div>
</div>

### createAtomicCapture() {#a6cc340cf5dc46cf45eb6f784577cadbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createAtomicCapture (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/atomicopvalue">AtomicOpValue</a> &amp; X, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/atomicopvalue">AtomicOpValue</a> &amp; V, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Expr, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> AO, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615">AtomicRMWInst::BinOp</a> RMWOp, <a href="/web-llvm/docs/api/classes/llvm/function-ref">AtomicUpdateCallbackTy</a> &amp; UpdateOp, bool UpdateExpr, bool IsPostfixUpdate, bool IsXBinopExpr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit atomic update for constructs: — Only Scalar data types V = X; X = X BinOp Expr , X = X BinOp Expr; V = X, V = X; X = Expr BinOp X, X = Expr BinOp X; V = X, V = X; X = UpdateOp(X), X = UpdateOp(X); V = X,.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion point to be used for alloca instructions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">X</td>
<td class="doxyParamItemDescription"><p>The target atomic pointer to be updated</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">V</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> address where to store captured value</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Expr</td>
<td class="doxyParamItemDescription"><p>The value to update X with.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AO</td>
<td class="doxyParamItemDescription"><p>Atomic ordering of the generated atomic instructions</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RMWOp</td>
<td class="doxyParamItemDescription"><p>The binary operation used for update. If operation is not supported by atomicRMW, or belong to {FADD, FSUB, BAD_BINOP}. Then a cmpExch based atomic will be generated.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UpdateOp</td>
<td class="doxyParamItemDescription"><p>Code generator for complex expressions that cannot be expressed through atomicrmw instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UpdateExpr</td>
<td class="doxyParamItemDescription"><p>true if X is an in place update of the form X = X BinOp Expr or X = Expr BinOp X</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsXBinopExpr</td>
<td class="doxyParamItemDescription"><p>true if X is Left H.S. in Right H.S. part of the update expression, false otherwise. (e.g. true for X = X BinOp Expr)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsPostfixUpdate</td>
<td class="doxyParamItemDescription"><p>true if original value of 'x' must be stored in 'v', not an updated one.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Insertion point after generated atomic capture IR.</p></dd>
</dl>


<p>Declaration at line 3299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 8793 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a91b7eb2a05d10c788413bec7977f3474">emitImplicitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa1184a7e35e94d162a2d40f2b11beeb2">llvm::AtomicRMWInst::Max</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a39edb6e51c1ad37244e8b32a2af4077d">llvm::AtomicRMWInst::Min</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615afc870a548088c5b7a93a34f648889d77">llvm::AtomicRMWInst::Xchg</a>.</p>

</div>
</div>

### createAtomicCompare() {#a6c4eeba23c6f192892487de272e8ce72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointTy OpenMPIRBuilder::createAtomicCompare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/atomicopvalue">AtomicOpValue</a> &amp; X, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/atomicopvalue">AtomicOpValue</a> &amp; V, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/atomicopvalue">AtomicOpValue</a> &amp; R, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * E, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * D, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> AO, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#acb593a387130148478f3c30af0d322df">omp::OMPAtomicCompareOp</a> Op, bool IsXBinopExpr, bool IsPostfixUpdate, bool IsFailOnly)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit atomic compare for constructs: — Only scalar data types cond-expr-stmt: x = x ordop expr ?</p>


<p>expr : x; x = expr ordop x ? expr : x; x = x == e ? d : x; x = e == x ? d : x; (this one is not in the spec) cond-update-stmt: if (x ordop expr) { x = expr; } if (expr ordop x) { x = expr; } if (x == e) { x = d; } if (e == x) { x = d; } (this one is not in the spec) conditional-update-capture-atomic: v = x; cond-update-stmt; (IsPostfixUpdate=true, IsFailOnly=false) cond-update-stmt; v = x; (IsPostfixUpdate=false, IsFailOnly=false) if (x == e) { x = d; } else { v = x; } (IsPostfixUpdate=false, IsFailOnly=true) r = x == e; if (r) { x = d; } (IsPostfixUpdate=false, IsFailOnly=false) r = x == e; if (r) { x = d; } else { v = x; } (IsPostfixUpdate=false, IsFailOnly=true)</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">X</td>
<td class="doxyParamItemDescription"><p>The target atomic pointer to be updated.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">V</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> address where to store captured value (for compare capture only).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">R</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> address where to store comparison result (for compare capture with '==' only).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">E</td>
<td class="doxyParamItemDescription"><p>The expected value ('e') for forms that use an equality comparison or an expression ('expr') for forms that use 'ordop' (logically an atomic maximum or minimum).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">D</td>
<td class="doxyParamItemDescription"><p>The desired value for forms that use an equality comparison. If forms that use 'ordop', it should be <span class="doxyComputerOutput">nullptr</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AO</td>
<td class="doxyParamItemDescription"><p>Atomic ordering of the generated atomic instructions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6"&gt;Op&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>Atomic compare operation. It can only be ==, &lt;, or &gt;.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsXBinopExpr</td>
<td class="doxyParamItemDescription"><p>True if the conditional statement is in the form where x is on LHS. It only matters for &lt; or &gt;.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsPostfixUpdate</td>
<td class="doxyParamItemDescription"><p>True if original value of 'x' must be stored in 'v', not an updated one (for compare capture only).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsFailOnly</td>
<td class="doxyParamItemDescription"><p>True if the original value of 'x' is stored to 'v' only when the comparison fails. This is only valid for the case the comparison is '=='.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Insertion point after generated atomic capture IR.</p></dd>
</dl>


<p>Declaration at line 3351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 8831 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#a6c4eeba23c6f192892487de272e8ce72">createAtomicCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a7ce03ab5b2a6006ebcdfe804e4c8f1a1">llvm::AtomicCmpXchgInst::getStrongestFailureOrdering</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#a6c4eeba23c6f192892487de272e8ce72">createAtomicCompare</a>.</p>

</div>
</div>

### createAtomicCompare() {#ab84af206a9a08b9bf97eaadc87874c6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointTy OpenMPIRBuilder::createAtomicCompare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/atomicopvalue">AtomicOpValue</a> &amp; X, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/atomicopvalue">AtomicOpValue</a> &amp; V, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/atomicopvalue">AtomicOpValue</a> &amp; R, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * E, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * D, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> AO, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#acb593a387130148478f3c30af0d322df">omp::OMPAtomicCompareOp</a> Op, bool IsXBinopExpr, bool IsPostfixUpdate, bool IsFailOnly, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Failure)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 3355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 8842 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8">llvm::CmpInst::FCMP_OGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8">llvm::CmpInst::FCMP_OLT</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615acce124326ba87b0127b36c412bf555fd">llvm::AtomicRMWInst::FMax</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615abd5e733a10a36f3572105b1a67538e18">llvm::AtomicRMWInst::FMin</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa1184a7e35e94d162a2d40f2b11beeb2">llvm::AtomicRMWInst::Max</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a39edb6e51c1ad37244e8b32a2af4077d">llvm::AtomicRMWInst::Min</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a52c990590792c91dd20b6d45acebe359">llvm::BasicBlock::splitBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615abe171d96ba8de66fb30e08c00211591e">llvm::AtomicRMWInst::UMax</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa53854e09143f57d2ff2ad6ac89dc55d">llvm::AtomicRMWInst::UMin</a>, <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### createAtomicRead() {#a388d5a62753f4e7ff4b72e54c1233fbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointTy OpenMPIRBuilder::createAtomicRead (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/atomicopvalue">AtomicOpValue</a> &amp; X, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/atomicopvalue">AtomicOpValue</a> &amp; V, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> AO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit atomic Read for : V = X — Only Scalar data types.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">X</td>
<td class="doxyParamItemDescription"><p>The target pointer to be atomically read</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">V</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> address where to store atomically read value</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AO</td>
<td class="doxyParamItemDescription"><p>Atomic ordering of the generated atomic instructions.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Insertion point after generated atomic read IR.</p></dd>
</dl>


<p>Declaration at line 3226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 8489 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#a5df935e7c87e3e1dc8b3d7e1870ee1c9">llvm::AtomicInfo::EmitAtomicLoadLibcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a91b7eb2a05d10c788413bec7977f3474">emitImplicitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#af51c113a039c82f6870df5dc9666b5e3">llvm::LoadInst::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#abcbe492bce3ccc16e0bbb50292576c5c">llvm::Module::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4ba3a5be6c0e9b9e8a525de055836733">llvm::Instruction::getModule</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a2d1ff28d6923802e165905b8d1766e76">llvm::LoadInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#acfcd22eb38dbfe1acbf138754297437a">llvm::DataLayout::getTypeStoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a81eef9d7336f7ee43be79630d8e8ec86">llvm::Type::isStructTy</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a6ae88dc44b078c80ce3a25401fd4b05b">llvm::LoadInst::setAtomic</a>, <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### createAtomicUpdate() {#ae75c4b44f208011259ee93497c2cb411}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createAtomicUpdate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/atomicopvalue">AtomicOpValue</a> &amp; X, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Expr, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> AO, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615">AtomicRMWInst::BinOp</a> RMWOp, <a href="/web-llvm/docs/api/classes/llvm/function-ref">AtomicUpdateCallbackTy</a> &amp; UpdateOp, bool IsXBinopExpr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit atomic update for constructs: X = X BinOp Expr ,or X = Expr BinOp X For complex Operations: X = UpdateOp(X) =&gt; CmpExch X, old_X, UpdateOp(X) Only Scalar data types.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion point to be used for alloca instructions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">X</td>
<td class="doxyParamItemDescription"><p>The target atomic pointer to be updated</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Expr</td>
<td class="doxyParamItemDescription"><p>The value to update X with.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AO</td>
<td class="doxyParamItemDescription"><p>Atomic ordering of the generated atomic instructions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RMWOp</td>
<td class="doxyParamItemDescription"><p>The binary operation used for update. If operation is not supported by atomicRMW, or belong to {FADD, FSUB, BAD_BINOP}. Then a <span class="doxyComputerOutput">cmpExch</span> based atomic will be generated.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UpdateOp</td>
<td class="doxyParamItemDescription"><p>Code generator for complex expressions that cannot be expressed through atomicrmw instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsXBinopExpr</td>
<td class="doxyParamItemDescription"><p>true if <em>X</em> is Left H.S. in Right H.S. part of the update expression, false otherwise. (e.g. true for X = X BinOp Expr)</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Insertion point after generated atomic update IR.</p></dd>
</dl>


<p>Declaration at line 3264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 8574 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a756b28f370cd5a39bc0ee3e5333b9c9b">isConflictIP</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa1184a7e35e94d162a2d40f2b11beeb2">llvm::AtomicRMWInst::Max</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a39edb6e51c1ad37244e8b32a2af4077d">llvm::AtomicRMWInst::Min</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615abe171d96ba8de66fb30e08c00211591e">llvm::AtomicRMWInst::UMax</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa53854e09143f57d2ff2ad6ac89dc55d">llvm::AtomicRMWInst::UMin</a>, <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### createAtomicWrite() {#a0e2de2c034e3083d006b92ddf14b8bcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointTy OpenMPIRBuilder::createAtomicWrite (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/atomicopvalue">AtomicOpValue</a> &amp; X, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Expr, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> AO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit atomic write for : X = Expr — Only Scalar data types.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">X</td>
<td class="doxyParamItemDescription"><p>The target pointer to be atomically written to</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Expr</td>
<td class="doxyParamItemDescription"><p>The value to store.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AO</td>
<td class="doxyParamItemDescription"><p>Atomic ordering of the generated atomic instructions.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Insertion point after generated atomic Write IR.</p></dd>
</dl>


<p>Declaration at line 3239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 8544 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#aff28bd42ac76fc3e1c0e4db7f9e06f2d">llvm::StoreInst::setAtomic</a>, <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### createBarrier() {#abca6530c9099bd1b1c3e0a5c32381f07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createBarrier (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, omp::Directive Kind, bool ForceSimpleCall=false, bool CheckCancelFlag=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emitter methods for OpenMP directives.</p>


<p>{ Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> barrier'</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the barrier directive was encountered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Kind</td>
<td class="doxyParamItemDescription"><p>The kind of directive that caused the barrier.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ForceSimpleCall</td>
<td class="doxyParamItemDescription"><p>Flag to force a simple (=non-cancellation) barrier.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CheckCancelFlag</td>
<td class="doxyParamItemDescription"><p>Flag to indicate a cancel barrier return value should be checked and acted upon.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ThreadID</td>
<td class="doxyParamItemDescription"><p>Optional parameter to pass in any existing ThreadID value.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion point after the barrier.</p></dd>
</dl>


<p>Declaration at line 669 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 1007 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#a98b55a0d95b3926151545101e4f2aef9">emitCancelationCheckImpl</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a>, <a href="#ad44e60b9d264f6ceb54e6cd660e859fb">isLastFinalizationInfoCancellable</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>


<p>Referenced by <a href="#a04285415a321e48322c08f3b9185540e">createCancel</a> and <a href="#a3e1a0b27abb4d57e2293c46802eee89d">createSingle</a>.</p>

</div>
</div>

### createCachedThreadPrivate() {#ad89dcb3cd8a39ae57a69487c2988dace}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * OpenMPIRBuilder::createCachedThreadPrivate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * Pointer, <a href="/web-llvm/docs/api/classes/llvm/constantint">llvm::ConstantInt</a> * Size, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">llvm::Twine</a> &amp; Name=<a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a>(""))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a runtime call for kmpc_threadprivate_cached.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Pointer</td>
<td class="doxyParamItemDescription"><p>pointer to data to be cached</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>size of data to be cached</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Name of call <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> for callinst</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> to the thread private cache call.</p></dd>
</dl>


<p>Declaration at line 2708 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6171 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#aa5ef00e5a7487cc6c5bfed0f301fa1cc">getOrCreateInternalVariable</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a>, <a href="#a5fd26a28fedc9044dd6939648d55c429a61cf8510205077b6f5491d38cd44c0f7">Pointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createCancel() {#a04285415a321e48322c08f3b9185540e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createCancel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * IfCondition, omp::Directive CanceledDirective)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> cancel'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the directive was encountered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IfCondition</td>
<td class="doxyParamItemDescription"><p>The evaluated 'if' clause expression, if any.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CanceledDirective</td>
<td class="doxyParamItemDescription"><p>The kind of directive that is cancled.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion point after the barrier.</p></dd>
</dl>


<p>Declaration at line 681 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 1060 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#abca6530c9099bd1b1c3e0a5c32381f07">createBarrier</a>, <a href="#a98b55a0d95b3926151545101e4f2aef9">emitCancelationCheckImpl</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7ac00229d8c59902686f52ed061cdc80">llvm::SplitBlockAndInsertIfThenElse</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createCanonicalLoop() {#ae0287686a5ffe03bc264972c862726ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; CanonicalLoopInfo * &gt; OpenMPIRBuilder::createCanonicalLoop (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#a296d2e28bddf1051d614f48b61005899">LoopBodyGenCallbackTy</a> BodyGenCB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * TripCount, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="loop")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for the control flow structure of an OpenMP canonical loop.</p>


<p>This generator operates on the logical iteration space of the loop, i.e. the caller only has to provide a loop trip count of the loop as defined by base language semantics. The trip count is interpreted as an unsigned integer. The induction variable passed to <span class="doxyComputerOutput">BodyGenCB</span> will be of the same type and run from 0 to <span class="doxyComputerOutput">TripCount</span> - 1. It is up to the callback to convert the logical iteration variable to the loop counter variable in the loop body.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. The insert location can be between two instructions or the end of a degenerate block (e.g. a BB under construction).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the loop body code.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TripCount</td>
<td class="doxyParamItemDescription"><p>Number of iterations the loop body is executed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Base name used to derive BB and instruction names.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An object representing the created control flow structure which can be used for loop-associated directives.</p></dd>
</dl>


<p>Declaration at line 725 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 4025 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa7bfcadb5535fe8aad5032762b7bfe159">After</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a32ff799dcb39887a8d21322020f305ba">llvm::CanonicalLoopInfo::assertOK</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#a445fa52d77040bccb16bfea111234a2e">createLoopSkeleton</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a92d8bce979891dc43b6573e8cca2e58c">llvm::CanonicalLoopInfo::getAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a8031442528bff99473596a0de4aa0422">llvm::CanonicalLoopInfo::getBodyIP</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#af4131f5f461f1138483addfd7cd7f579">llvm::CanonicalLoopInfo::getIndVar</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#a62ee7ece4986606d41363bc1f70d5ab2">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getNextNode</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#ad50eb30e70ff2a9ea7f220547e2b6f6d">llvm::CanonicalLoopInfo::getPreheader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a78e14f66d8a8405c6882b5ff6a3b7617">llvm::spliceBB</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>


<p>Referenced by <a href="#ac669acbd0f638c6ef32977575362052e">createCanonicalLoop</a> and <a href="#af36172c1f538b7305b44760997d5a3c2">createSections</a>.</p>

</div>
</div>

### createCanonicalLoop() {#ac669acbd0f638c6ef32977575362052e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; CanonicalLoopInfo * &gt; OpenMPIRBuilder::createCanonicalLoop (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#a296d2e28bddf1051d614f48b61005899">LoopBodyGenCallbackTy</a> BodyGenCB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Start, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Stop, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Step, bool IsSigned, bool InclusiveStop, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> ComputeIP={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="loop")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for the control flow structure of an OpenMP canonical loop.</p>


<p>Instead of a logical iteration space, this allows specifying user-defined loop counter values using increment, upper- and lower bounds. To disambiguate the terminology when counting downwards, instead of lower bounds we use <span class="doxyComputerOutput">Start</span> for the loop counter value in the first body iteration.</p>


<p>Consider the following limitations:</p>


<ul class="doxyList ">
<li>A loop counter space over all integer values of its bit-width cannot be represented. E.g using uint8_t, its loop trip count of 256 cannot be stored into an 8 bit integer):

DO I = 0, 255, 1</li>
<li>Unsigned wrapping is only supported when wrapping only "once"; E.g. effectively counting downwards:

for (uint8_t i = 100u; i &gt; 0; i += 127u)</li>
</ul>

<p>TODO: May need to add additional parameters to represent:</p>


<ul class="doxyList ">
<li>Allow representing downcounting with unsigned integers.</li>
<li>Sign of the step and the comparison operator might disagree:

for (int i = 0; i &lt; 42; i -= 1u)

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the loop body code.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Start</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of the loop counter for the first iterations.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Stop</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> counter values past this will stop the loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Step</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> counter increment after each iteration; negative means counting down.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsSigned</td>
<td class="doxyParamItemDescription"><p>Whether Start, Stop and Step are signed integers.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InclusiveStop</td>
<td class="doxyParamItemDescription"><p>Whether <span class="doxyComputerOutput">Stop</span> itself is a valid value for the loop counter.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ComputeIP</td>
<td class="doxyParamItemDescription"><p>Insertion point for instructions computing the trip count. Can be used to ensure the trip count is available at the outermost loop of a loop nest. If not set, defaults to the preheader of the generated loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Base name used to derive BB and instruction names.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An object representing the created control flow structure which can be used for loop-associated directives.</p></dd>
</dl></li>
</ul>

<p>Declaration at line 777 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 4055 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ae0287686a5ffe03bc264972c862726ea">createCanonicalLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/insertpoint/#a85b9635b21610f18b51007437bcc26cf">llvm::IRBuilderBase::InsertPoint::isSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createCopyinClauseBlocks() {#a70356a38271d388e7c4b477cef0d7b2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointTy OpenMPIRBuilder::createCopyinClauseBlocks (<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> IP, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * MasterAddr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * PrivateAddr, <a href="/web-llvm/docs/api/classes/llvm/integertype">llvm::IntegerType</a> * IntPtrTy, bool BranchtoEnd=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate conditional branch and relevant BasicBlocks through which private threads copy the 'copyin' variables from Master copy to threadprivate copies.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">IP</td>
<td class="doxyParamItemDescription"><p>insertion block for copyin conditional</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MasterVarPtr</td>
<td class="doxyParamItemDescription"><p>a pointer to the master variable</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PrivateVarPtr</td>
<td class="doxyParamItemDescription"><p>a pointer to the threadprivate variable</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IntPtrTy</td>
<td class="doxyParamItemDescription"><p>Pointer size type</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BranchtoEnd</td>
<td class="doxyParamItemDescription"><p>Create a branch between the copyin.not.master blocks</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion point where copying operation to be emitted.</p></dd>
</dl>


<p>Declaration at line 2673 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6005 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/insertpoint/#a3d072f8ac5e1b0724c4bb5a77adae9da">llvm::IRBuilderBase::InsertPoint::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4956305191cdba7f9995569d011a5ab7">llvm::isa_and_nonnull</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/insertpoint/#a85b9635b21610f18b51007437bcc26cf">llvm::IRBuilderBase::InsertPoint::isSet</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a52c990590792c91dd20b6d45acebe359">llvm::BasicBlock::splitBasicBlock</a>.</p>

</div>
</div>

### createCopyPrivate() {#af2808c704c935cee35e9529907b59b1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointTy OpenMPIRBuilder::createCopyPrivate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * BufSize, <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * CpyBuf, <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * CpyFn, <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * DidIt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for __kmpc_copyprivate.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BufSize</td>
<td class="doxyParamItemDescription"><p>Number of elements in the buffer.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CpyBuf</td>
<td class="doxyParamItemDescription"><p>List of pointers to data to be copied.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CpyFn</td>
<td class="doxyParamItemDescription"><p>function to call for copying data.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DidIt</td>
<td class="doxyParamItemDescription"><p>flag variable; 1 for 'single' thread, 0 otherwise.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion position <em>after</em> the CopyPrivate call.</p></dd>
</dl>


<p>Declaration at line 2532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5681 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>


<p>Referenced by <a href="#a3e1a0b27abb4d57e2293c46802eee89d">createSingle</a>.</p>

</div>
</div>

### createCritical() {#ac379895c55a89804f49f1a775828c235}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createCritical (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> BodyGenCB, <a href="#a0c571620ff53fdb78e7404f5261dbd23">FinalizeCallbackTy</a> FiniCB, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CriticalName, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * HintInst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> critical'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region body code.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FiniCB</td>
<td class="doxyParamItemDescription"><p>Callback to finalize variable copies.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CriticalName</td>
<td class="doxyParamItemDescription"><p>name of the lock used by the critical directive</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HintInst</td>
<td class="doxyParamItemDescription"><p>Hint <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> for hint clause associated with critical</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion position <em>after</em> the critical.</p></dd>
</dl>


<p>Declaration at line 2583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5777 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createDispatchDeinitFunction() {#ae2d016504f27bd96960ace8645073d63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee OpenMPIRBuilder::createDispatchDeinitFunction ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns __kmpc_dispatch_deinit runtime function.</p>

<p>Declaration at line 3046 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6803 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#a034dc6253a2a36f78ac071a7c12d5c27">getOrCreateRuntimeFunction</a> and <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>.</p>

</div>
</div>

### createDispatchFiniFunction() {#a5946a2c7130bcf42add273f83cb6e257}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee OpenMPIRBuilder::createDispatchFiniFunction (unsigned IVSize, bool IVSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns __kmpc_dispatch_fini_* runtime function for the specified size <em>IVSize</em> and sign <em>IVSigned</em>.</p>

<p>Declaration at line 3043 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6790 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a034dc6253a2a36f78ac071a7c12d5c27">getOrCreateRuntimeFunction</a> and <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>.</p>

</div>
</div>

### createDispatchInitFunction() {#aac7493b7e13af08014a1c49dcdecbf20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee OpenMPIRBuilder::createDispatchInitFunction (unsigned IVSize, bool IVSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns __kmpc_dispatch_init_* runtime function for the specified size <em>IVSize</em> and sign <em>IVSigned</em>.</p>

<p>Declaration at line 3035 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6764 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a034dc6253a2a36f78ac071a7c12d5c27">getOrCreateRuntimeFunction</a> and <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>.</p>

</div>
</div>

### createDispatchNextFunction() {#a49dbf0af8f3e1314b3b60222651b6fc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee OpenMPIRBuilder::createDispatchNextFunction (unsigned IVSize, bool IVSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns __kmpc_dispatch_next_* runtime function for the specified size <em>IVSize</em> and sign <em>IVSigned</em>.</p>

<p>Declaration at line 3039 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6777 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a034dc6253a2a36f78ac071a7c12d5c27">getOrCreateRuntimeFunction</a> and <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>.</p>

</div>
</div>

### createFlush() {#afc2cc623eda981e1b3fbb61a44e80ef8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::createFlush (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> flush'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the flush directive was encountered</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 1766 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#a2a4b97bb7670d306c756cdbd5ee9b560">emitFlush</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createForStaticInitFunction() {#a8191e2fd322236b59afb070919f0d6af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee OpenMPIRBuilder::createForStaticInitFunction (unsigned IVSize, bool IVSigned, bool IsGPUDistribute)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns __kmpc_for_static_init_* runtime function for the specified size <em>IVSize</em> and sign <em>IVSigned</em>.</p>


<p>Will create a distribute call __kmpc_distribute_static_init* if <em>IsGPUDistribute</em> is set.</p>


<p>Declaration at line 3030 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6744 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a034dc6253a2a36f78ac071a7c12d5c27">getOrCreateRuntimeFunction</a> and <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>.</p>

</div>
</div>

### createGlobalFlag() {#ada8d44774af63e8cab5f9b2a088121fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalValue * OpenMPIRBuilder::createGlobalFlag (unsigned Value, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a hidden global flag <span class="doxyComputerOutput">Name</span> in the module with initial value <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span>.</p>

<p>Declaration at line 2013 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 849 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a7eade123587a08e674f2ca72e2443771">llvm::GlobalValue::HiddenVisibility</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca696bb1c9b0b0e76bb70c61f68866452a">llvm::GlobalValue::WeakODRLinkage</a>.</p>

</div>
</div>

### createLoopSkeleton() {#a445fa52d77040bccb16bfea111234a2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CanonicalLoopInfo * OpenMPIRBuilder::createLoopSkeleton (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * TripCount, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * PreInsertBefore, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * PostInsertBefore, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create the control flow structure of a canonical OpenMP loop.</p>


<p>The emitted loop will be disconnected, i.e. no edge to the loop's preheader and no terminator in the AfterBB. The <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder">OpenMPIRBuilder</a>'s <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a> location is not preserved.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> used for the instructions in the skeleton.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TripCount</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to be used for the trip count.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">F</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> in which to insert the BasicBlocks.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PreInsertBefore</td>
<td class="doxyParamItemDescription"><p>Where to insert BBs that execute before the body, typically the body itself.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PostInsertBefore</td>
<td class="doxyParamItemDescription"><p>Where to insert BBs that execute after the body.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Base name used to derive BB and instruction names.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> that represents the emitted loop.</p></dd>
</dl>


<p>Declaration at line 3379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 3958 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa7bfcadb5535fe8aad5032762b7bfe159">After</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a32ff799dcb39887a8d21322020f305ba">llvm::CanonicalLoopInfo::assertOK</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a418fd65883c81897f472643208a988b4">LoopInfos</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>.</p>


<p>Referenced by <a href="#a08610118e213de1b759470f0eafb9b18">collapseLoops</a>, <a href="#ae0287686a5ffe03bc264972c862726ea">createCanonicalLoop</a> and <a href="#a76e12ec076e7af4be7b8b77a5d53d3fc">tileLoops</a>.</p>

</div>
</div>

### createMapperAllocas() {#a544a84c75ac55356516cc7365cbe6f02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::createMapperAllocas (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, unsigned NumOperands, struct <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapperallocas">MapperAllocas</a> &amp; MapperAllocas)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create the allocas instruction used in call to mapper functions.</p>

<p>Declaration at line 2183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 7699 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapperallocas/#aa90c5e272864414356fbeede370d5053">llvm::OpenMPIRBuilder::MapperAllocas::Args</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapperallocas/#a9d27bf73f53ec62c72ffd3137f47efde">llvm::OpenMPIRBuilder::MapperAllocas::ArgsBase</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapperallocas/#ad41f11a634af5e69560ac0279c74b100">llvm::OpenMPIRBuilder::MapperAllocas::ArgSizes</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872ada475947399b8ab4d13d40fea50f950c">Int64</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createMasked() {#adf9f105d93a1a09d5307dc14e77293f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createMasked (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> BodyGenCB, <a href="#a0c571620ff53fdb78e7404f5261dbd23">FinalizeCallbackTy</a> FiniCB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Filter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> masked'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region code.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FiniCB</td>
<td class="doxyParamItemDescription"><p>Callback to finialize variable copies.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion position <em>after</em> the masked.</p></dd>
</dl>


<p>Declaration at line 2570 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 3934 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaee5189b9c4db9ad666a88abaf1ee0c4ad7778d0c64b6ba21494c97f77a66885a">llvm::Filter</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createMaster() {#a970cc920a6bae8d641ac63fb33afb40b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createMaster (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> BodyGenCB, <a href="#a0c571620ff53fdb78e7404f5261dbd23">FinalizeCallbackTy</a> FiniCB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> master'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region code.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FiniCB</td>
<td class="doxyParamItemDescription"><p>Callback to finalize variable copies.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion position <em>after</em> the master.</p></dd>
</dl>


<p>Declaration at line 2559 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 3910 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createOffloadEntriesAndInfoMetadata() {#acc290ce16055813d4ee68af4c8023a09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::createOffloadEntriesAndInfoMetadata (<a href="#af45ce5586729bfa3160eaa9cec64e0f5">EmitMetadataErrorReportFunctionTy</a> &amp; ErrorReportFunction)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2518 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9241 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#ae917c72e5b8e15491cd0dbdd44d818f2">llvm::NamedMDNode::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a355507f9e59388e467dc9288e4f82c3d">Config</a>, <a href="#ac5805e4c7f00be338494407152cf34aa">createOffloadEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#affb389ba6facf4b5854565f9db5bc90ba2ff4496ec84c0d33c078284970aa331c">EMIT_MD_DECLARE_TARGET_ERROR</a>, <a href="#affb389ba6facf4b5854565f9db5bc90ba6c60cf0594c5dae6dfab7b5abbdea97d">EMIT_MD_GLOBAL_VAR_LINK_ERROR</a>, <a href="#affb389ba6facf4b5854565f9db5bc90baf5ff390a87124f22662146233ca4ff72">EMIT_MD_TARGET_REGION_ERROR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a4b79b6c874e2b55eb4dda2ae96867f84">llvm::offloading::emitOffloadingEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="#aed2a8b469e9884788eef400fbc892dd3">OffloadInfoManager</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a92b4561998310fbcfbeaeb7c449bad6aaf8060971587bf244fd04e657d00529ff">llvm::object::OFK_OpenMP</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#ab9575c71365de4083a7be6ef6572d534ab16880c5ddd7886e422bf6dc1e670cca">llvm::OffloadEntriesInfoManager::OMPTargetGlobalRegisterRequires</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#ab9575c71365de4083a7be6ef6572d534a1b9b415348a31bfeaa94e778e0421ddf">llvm::OffloadEntriesInfoManager::OMPTargetGlobalVarEntryEnter</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#ab9575c71365de4083a7be6ef6572d534aba847264872ebbdaf660316167b89e15">llvm::OffloadEntriesInfoManager::OMPTargetGlobalVarEntryIndirect</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#ab9575c71365de4083a7be6ef6572d534abe3a7916fb5f7a79d6aea6c0356e71a6">llvm::OffloadEntriesInfoManager::OMPTargetGlobalVarEntryLink</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#ab9575c71365de4083a7be6ef6572d534acf96797e65a60ff4302eb2bbdbbd8880">llvm::OffloadEntriesInfoManager::OMPTargetGlobalVarEntryTo</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo/#a89525afb0a8095beeb2dc7b083491942">llvm::TargetRegionEntryInfo::ParentName</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca8d13a9bcecfac72febceb1103afa048f">llvm::GlobalValue::WeakAnyLinkage</a>.</p>


<p>Referenced by <a href="#a784adc2347b72f745ff1239aef3a3c26">finalize</a>.</p>

</div>
</div>

### createOffloadEntry() {#ac5805e4c7f00be338494407152cf34aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::createOffloadEntry (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * ID, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Addr, uint64_t Size, int32_t Flags, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates offloading entry for the provided entry <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> <em><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></em>, address <em>Addr</em>, size <em>Size</em>, and flags <em>Flags</em>.</p>

<p>Declaration at line 2495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9216 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a01875e4204852069dd4b7938cab4140b">llvm::Function::addFnAttr</a>, <a href="#a355507f9e59388e467dc9288e4f82c3d">Config</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a4b79b6c874e2b55eb4dda2ae96867f84">llvm::offloading::emitOffloadingEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a92b4561998310fbcfbeaeb7c449bad6aaf8060971587bf244fd04e657d00529ff">llvm::object::OFK_OpenMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#a7f3588f949f4fb51454b0b8c6194ca75">T</a>.</p>


<p>Referenced by <a href="#acc290ce16055813d4ee68af4c8023a09">createOffloadEntriesAndInfoMetadata</a>.</p>

</div>
</div>

### createOffloadMapnames() {#ab1aa0d632549db4855d6412f4d2d44ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * OpenMPIRBuilder::createOffloadMapnames (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">llvm::Constant</a> * &gt; &amp; Names, std::string VarName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create the global variable holding the offload names information.</p>

<p>Declaration at line 2173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9165 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantarray/#a0900dacdc7ad8e3ea0cc92993c7fd422">llvm::ConstantArray::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca04ed141708c0fd16723d212502b046ae">llvm::GlobalValue::PrivateLinkage</a>.</p>


<p>Referenced by <a href="#a752e863c1af5fe463d0f08574492c12f">emitOffloadingArrays</a>.</p>

</div>
</div>

### createOffloadMaptypes() {#ad56f71598b251a0f66e590c94d01c67b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * OpenMPIRBuilder::createOffloadMaptypes (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Mappings, std::string VarName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create the global variable holding the offload mappings information.</p>

<p>Declaration at line 2168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 7687 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a4a1000e5803e731e9dcc572042a98a0b">llvm::ConstantDataArray::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ae8df4be75bfc50b1eadd74e85c25fa45a4cc6684df7b4a92b1dec6fce3264fac8">llvm::GlobalValue::Global</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca04ed141708c0fd16723d212502b046ae">llvm::GlobalValue::PrivateLinkage</a>.</p>


<p>Referenced by <a href="#a752e863c1af5fe463d0f08574492c12f">emitOffloadingArrays</a>.</p>

</div>
</div>

### createOMPAlloc() {#a81bc7a57bd0332843aed6275ba47bee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * OpenMPIRBuilder::createOMPAlloc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Size, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Allocator, std::string Name="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a runtime call for kmpc_Alloc.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>Size of allocated memory space</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Allocator</td>
<td class="doxyParamItemDescription"><p>Allocator information instruction</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Name of call <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> for OMP_alloc</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> to the OMP_Alloc call</p></dd>
</dl>


<p>Declaration at line 2686 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6055 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createOMPFree() {#a807c913d5889a80440269b74d5755d6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * OpenMPIRBuilder::createOMPFree (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Allocator, std::string Name="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a runtime call for kmpc_free.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Addr</td>
<td class="doxyParamItemDescription"><p>Address of memory space to be freed</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Allocator</td>
<td class="doxyParamItemDescription"><p>Allocator information instruction</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Name of call <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> for OMP_Free</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> to the OMP_Free call</p></dd>
</dl>


<p>Declaration at line 2697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6072 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createOMPInteropDestroy() {#a38345e93229faed92e719f1793807bb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * OpenMPIRBuilder::createOMPInteropDestroy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * InteropVar, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Device, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NumDependences, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * DependenceAddress, bool HaveNowaitClause)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a runtime call for __tgt_interop_destroy.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InteropVar</td>
<td class="doxyParamItemDescription"><p>variable to be allocated</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Device</td>
<td class="doxyParamItemDescription"><p>devide to which offloading will occur</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumDependences</td>
<td class="doxyParamItemDescription"><p>number of dependence variables</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DependenceAddress</td>
<td class="doxyParamItemDescription"><p>pointer to dependence variables</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HaveNowaitClause</td>
<td class="doxyParamItemDescription"><p>does nowait clause exist</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> to the __tgt_interop_destroy call</p></dd>
</dl>


<p>Declaration at line 2741 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6116 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpointernull/#a96f5c85e4022e369266541b2db3fda69">llvm::ConstantPointerNull::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a788a72ddbf1bd572b3fcd7a5e7ec8cff">Int32</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createOMPInteropInit() {#a7709370a0f6564aa772ce20caa45337e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * OpenMPIRBuilder::createOMPInteropInit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * InteropVar, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#afeaad9a7fc12d9246c2e42578fddc718">omp::OMPInteropType</a> InteropType, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Device, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NumDependences, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * DependenceAddress, bool HaveNowaitClause)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a runtime call for __tgt_interop_init.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InteropVar</td>
<td class="doxyParamItemDescription"><p>variable to be allocated</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InteropType</td>
<td class="doxyParamItemDescription"><p>type of interop operation</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Device</td>
<td class="doxyParamItemDescription"><p>devide to which offloading will occur</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumDependences</td>
<td class="doxyParamItemDescription"><p>number of dependence variables</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DependenceAddress</td>
<td class="doxyParamItemDescription"><p>pointer to dependence variables</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HaveNowaitClause</td>
<td class="doxyParamItemDescription"><p>does nowait clause exist</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> to the __tgt_interop_init call</p></dd>
</dl>


<p>Declaration at line 2724 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6087 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpointernull/#a96f5c85e4022e369266541b2db3fda69">llvm::ConstantPointerNull::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a788a72ddbf1bd572b3fcd7a5e7ec8cff">Int32</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createOMPInteropUse() {#aaef3fb3339c2ade5ffffccdd177e465c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * OpenMPIRBuilder::createOMPInteropUse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * InteropVar, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Device, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NumDependences, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * DependenceAddress, bool HaveNowaitClause)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a runtime call for __tgt_interop_use.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InteropVar</td>
<td class="doxyParamItemDescription"><p>variable to be allocated</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Device</td>
<td class="doxyParamItemDescription"><p>devide to which offloading will occur</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumDependences</td>
<td class="doxyParamItemDescription"><p>number of dependence variables</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DependenceAddress</td>
<td class="doxyParamItemDescription"><p>pointer to dependence variables</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HaveNowaitClause</td>
<td class="doxyParamItemDescription"><p>does nowait clause exist</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> to the __tgt_interop_use call</p></dd>
</dl>


<p>Declaration at line 2757 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6143 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpointernull/#a96f5c85e4022e369266541b2db3fda69">llvm::ConstantPointerNull::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a788a72ddbf1bd572b3fcd7a5e7ec8cff">Int32</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createOrderedDepend() {#a6e2bd6420d3d12339e32d4d1b3ba1394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointTy OpenMPIRBuilder::createOrderedDepend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, unsigned NumLoops, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * &gt; StoreValues, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, bool IsDependSource)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> ordered depend (source | sink)'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion point to be used for alloca instructions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumLoops</td>
<td class="doxyParamItemDescription"><p>The number of loops in depend clause.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">StoreValues</td>
<td class="doxyParamItemDescription"><p>The value will be stored in vector address.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>The name of alloca instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsDependSource</td>
<td class="doxyParamItemDescription"><p>If true, depend source; otherwise, depend sink.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion position <em>after</em> the ordered.</p></dd>
</dl>


<p>Declaration at line 2598 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5812 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872ada475947399b8ab4d13d40fea50f950c">Int64</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#af3bb24b322533dbe8a63c84b18568fe1">llvm::AllocaInst::setAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#a55195fa18cf783fe74de0cced1ca6eb3">llvm::StoreInst::setAlignment</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createOrderedThreadsSimd() {#a012d736828ba67916f7e5a3e9ff1d68f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createOrderedThreadsSimd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> BodyGenCB, <a href="#a0c571620ff53fdb78e7404f5261dbd23">FinalizeCallbackTy</a> FiniCB, bool IsThreads)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> ordered [threads | simd]'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region code.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FiniCB</td>
<td class="doxyParamItemDescription"><p>Callback to finalize variable copies.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsThreads</td>
<td class="doxyParamItemDescription"><p>If true, with threads clause or without clause; otherwise, with simd clause;</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion position <em>after</em> the ordered.</p></dd>
</dl>


<p>Declaration at line 2612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5858 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createParallel() {#a4f81b9940e1869e146636dc533455929}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createParallel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> BodyGenCB, <a href="#a71b5ba020f68829f5a1fd99f48b63d42">PrivatizeCallbackTy</a> PrivCB, <a href="#a0c571620ff53fdb78e7404f5261dbd23">FinalizeCallbackTy</a> FiniCB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * IfCondition, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NumThreads, omp::ProcBindKind ProcBind, bool IsCancellable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> parallel'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion points to be used for alloca instructions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region code.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PrivCB</td>
<td class="doxyParamItemDescription"><p>Callback to copy a given variable (think copy constructor).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FiniCB</td>
<td class="doxyParamItemDescription"><p>Callback to finalize variable copies.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IfCondition</td>
<td class="doxyParamItemDescription"><p>The evaluated 'if' clause expression, if any.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumThreads</td>
<td class="doxyParamItemDescription"><p>The evaluated 'num_threads' clause expression, if any.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ProcBind</td>
<td class="doxyParamItemDescription"><p>The value of the 'proc_bind' clause (see ProcBindKind).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsCancellable</td>
<td class="doxyParamItemDescription"><p>Flag to indicate a cancellable parallel region.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion position <em>after</em> the parallel.</p></dd>
</dl>


<p>Declaration at line 699 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 1427 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#a5610e0ef8f016e84694778d8ce1c9479">addOutlineInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#a218bc49443ef1f05fc8074d872d41fcd">llvm::OpenMPIRBuilder::OutlineInfo::collectBlocks</a>, <a href="#a355507f9e59388e467dc9288e4f82c3d">Config</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#ac178f4fc4e4a0642610c374256b9fb27">llvm::SetVector&lt; T, Vector, Set, N &gt;::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#adc0b48022847ca44b3868d058cb98686">llvm::OpenMPIRBuilder::OutlineInfo::EntryBB</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#a5abe93575e72c30376079d2fb31b40f8">llvm::OpenMPIRBuilder::OutlineInfo::ExcludeArgsFromAggregate</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#adb6b79680b86167fd4ec4f32346e9e58">llvm::OpenMPIRBuilder::OutlineInfo::ExitBB</a>, <a href="#a75f3209cae3f3f2700c6bc6e9623f841">FinalizationStack</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/insertpoint/#a3d072f8ac5e1b0724c4bb5a77adae9da">llvm::IRBuilderBase::InsertPoint::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncallee/#ac5d8da677233fa2e1e7039508ed56e0e">llvm::FunctionCallee::getCallee</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a161fd4e9fa5367f64c2a4c9e921c3ad3">llvm::BasicBlock::getFirstInsertionPt</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#a62ee7ece4986606d41363bc1f70d5ab2">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getNextNode</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#afffa0ff2e1527ab545cef33be915c656">hostParallelCallback</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af09e4096de244d2fb345891328714a63">llvm::Instruction::insertAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a788a72ddbf1bd572b3fcd7a5e7ec8cff">Int32</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a756b28f370cd5a39bc0ee3e5333b9c9b">isConflictIP</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#aed0779b309d9a705e9b78adacc839875">llvm::OpenMPIRBuilder::OutlineInfo::OuterAllocaBB</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#a0b8f73f7987421a24a842d3e2633278d">llvm::OpenMPIRBuilder::OutlineInfo::PostOutlineCB</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a14d9be6f03ca789eb7489fa89273aa40">llvm::SetVector&lt; T, Vector, Set, N &gt;::remove_if</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a52c990590792c91dd20b6d45acebe359">llvm::BasicBlock::splitBasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac6c9ffe7979754415f4ca0d677174bc2">llvm::SplitBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af7668ce8080668a4f0ceac24e70c9f00">targetParallelCallback</a>, <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp/#a0b427ca665b192edbeb8d6ca3c8f19fd">Uses</a>.</p>

</div>
</div>

### createPlatformSpecificName() {#a488c861f8a68e5f78ceca8b57acd8be5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string OpenMPIRBuilder::createPlatformSpecificName (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Parts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the create a name using the platform specific separators.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Parts</td>
<td class="doxyParamItemDescription"><p>parts of the final name that needs separation The created name has a first separator between the first and second part and a second separator between all other parts. E.g. with FirstSeparator "$" and Separator "." and parts: "p1", "p2", "p3", "p4" The resulting name is "p1$p2.p3.p4" The separators are retrieved from the <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilderconfig">OpenMPIRBuilderConfig</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 7636 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a355507f9e59388e467dc9288e4f82c3d">Config</a>.</p>


<p>Referenced by <a href="#a752e863c1af5fe463d0f08574492c12f">emitOffloadingArrays</a>, <a href="#a567502d7244077ed45e0c9471d31ba4c">emitTargetRegionFunction</a> and <a href="#ae327be8503a76bd4dccfff4713a38553">registerTargetGlobalVariable</a>.</p>

</div>
</div>

### createReductions() {#ab0996924f219129d8de3cc1b8830f768}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createReductions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/reductioninfo">ReductionInfo</a> &gt; ReductionInfos, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; bool &gt; IsByRef, bool IsNoWait=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> reduction'.</p>


<p>Emits the IR instructing the runtime to perform the specific kind of reductions. Expects reduction variables to have been privatized and initialized to reduction-neutral values separately. Emits the calls to runtime functions as well as the reduction function and the basic blocks performing the reduction atomically and non-atomically.</p>


<p>The code emitted for the following:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">     type var_1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">     type var_2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">     #pragma omp &lt;directive&gt; reduction(reduction-op:var_1,var_2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightComment">/* body *&amp;zwj;/;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*  </span></span></div>

</div>


<p>corresponds to the following sketch.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> _outlined_par() {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightComment">// N is the number of different reductions.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> *red_array[] = {privatized_var_1, privatized_var_2, ...};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(__kmpc_reduce(..., <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, </span><span class="doxyHighlightComment">/*size of data in red array*&amp;zwj;/, red_array,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*                         _omp_reduction_func,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*                         _gomp_critical_user.reduction.var)) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*    case 1: {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*      var_1 = var_1 &lt;reduction-op&gt; privatized_var_1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*      var_2 = var_2 &lt;reduction-op&gt; privatized_var_2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*      // ...</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*     __kmpc_end_reduce(...);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*      break;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*    case 2: {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*      _Atomic&lt;ReductionOp&gt;(var_1, privatized_var_1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*      _Atomic&lt;ReductionOp&gt;(var_2, privatized_var_2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*      // ...</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*      break;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*    default: break;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">* </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*  void _omp_reduction_func(void **lhs, void **rhs) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">     *(type *)lhs[0] = *(type *)lhs[0] &lt;reduction-op&gt; *(type *)rhs[0];</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">     *(type *)lhs[1] = *(type *)lhs[1] &lt;reduction-op&gt; *(type *)rhs[1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*    // ...</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*  </span></span></div>

</div>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the reduction was encountered. Must be within the associate directive and after the last local access to the reduction variables.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>An insertion point suitable for allocas usable in reductions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionInfos</td>
<td class="doxyParamItemDescription"><p>A list of info on each reduction variable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsNoWait</td>
<td class="doxyParamItemDescription"><p>A flag set if the reduction is marked as nowait.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsByRef</td>
<td class="doxyParamItemDescription"><p>A flag set if the reduction is using reference or direct value.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1960 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 3731 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/reductioninfo/#a3c969fa43d5f18e4237461ba967a16ae">llvm::OpenMPIRBuilder::ReductionInfo::AtomicReductionGen</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/reductioninfo/#a808df20c6281c68ce8be2a89aaba392a">llvm::OpenMPIRBuilder::ReductionInfo::ElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aecf2b6d6f052a378dd8f69fd1bb700b1">llvm::Function::getArg</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/insertpoint/#a3d072f8ac5e1b0724c4bb5a77adae9da">llvm::IRBuilderBase::InsertPoint::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a0beddb53641a541e2238617c5fac4be7">llvm::Module::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#abcbe492bce3ccc16e0bbb50292576c5c">llvm::Module::getDataLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a669fae0a15d7219ef3ca3f3b16e3f5a0">getFreshReductionFunc</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/reductioninfo/#a63498704b583a96137c70ed7172f1ec3">llvm::OpenMPIRBuilder::ReductionInfo::PrivateVariable</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/reductioninfo/#a3fa70db8a68df256973daa02f87133b1">llvm::OpenMPIRBuilder::ReductionInfo::ReductionGen</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a52c990590792c91dd20b6d45acebe359">llvm::BasicBlock::splitBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a> and <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/reductioninfo/#a5a2adb59d172175dafdc9466d436e198">llvm::OpenMPIRBuilder::ReductionInfo::Variable</a>.</p>

</div>
</div>

### createReductionsGPU() {#aaa655ca8bca40c564d0b7c81ebaf8ff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createReductionsGPU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/reductioninfo">ReductionInfo</a> &gt; ReductionInfos, bool IsNoWait=false, bool IsTeamsReduction=false, bool HasDistribute=false, <a href="#a07f00f83b415baecc1af353eed43d123">ReductionGenCBKind</a> ReductionGenCBKind=<a href="#a07f00f83b415baecc1af353eed43d123a1744373124bab4b9336c0d19a141a1d1">ReductionGenCBKind::MLIR</a>, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/omp/gv">omp::GV</a> &gt; GridValue={}, unsigned ReductionBufNum=1024, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SrcLocInfo=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Design of OpenMP reductions on the GPU.</p>


<p>Consider a typical OpenMP program with one or more reduction clauses:</p>


<p>float foo; double bar; #pragma omp target teams distribute parallel for \ reduction(+:foo) <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/straightlinestrengthreduce-cpp/#a7b51b9df5e7db582597e8556087c71ce">reduction(*:bar)</a> for (int i = 0; i &lt; N; i++) { foo += A[i]; bar *= B[i]; }</p>


<p>where 'foo' and 'bar' are reduced across all OpenMP threads in all teams. In our OpenMP implementation on the <a href="/web-llvm/docs/api/namespaces/llvm/nvptx">NVPTX</a> device an OpenMP team is mapped to a CUDA threadblock and OpenMP threads within a team are mapped to CUDA threads within a threadblock. Our goal is to efficiently aggregate values across all OpenMP threads such that:</p>


<ul class="doxyList ">
<li>the compiler and runtime are logically concise, and</li>
<li>the reduction is performed efficiently in a hierarchical manner as follows: within OpenMP threads in the same warp, across warps in a threadblock, and finally across teams on the <a href="/web-llvm/docs/api/namespaces/llvm/nvptx">NVPTX</a> device.</li>
</ul>

<p>Introduction to Decoupling</p>


<p>We would like to decouple the compiler and the runtime so that the latter is ignorant of the reduction variables (number, data types) and the reduction operators. This allows a simpler interface and implementation while still attaining good performance.</p>


<p>Pseudocode for the aforementioned OpenMP program generated by the compiler is as follows:</p>


<ol class="doxyList" type="1">
<li>Create private copies of reduction variables on each OpenMP thread: 'foo_private', 'bar_private'</li>
<li>Each OpenMP thread reduces the chunk of 'A' and 'B' assigned to it and writes the result in 'foo_private' and 'bar_private' respectively.</li>
<li>Call the OpenMP runtime on the GPU to reduce within a team and store the result on the team master:

__kmpc_nvptx_parallel_reduce_nowait_v2(...,
       reduceData, shuffleReduceFn, interWarpCpyFn)

where: struct ReduceData { double *foo; double *bar; } reduceData reduceData.foo = &amp;foo_private reduceData.bar = &amp;bar_private

'shuffleReduceFn' and 'interWarpCpyFn' are pointers to two auxiliary functions generated by the compiler that operate on variables of type 'ReduceData'. They aid the runtime perform algorithmic steps in a data agnostic manner.

'shuffleReduceFn' is a pointer to a function that reduces data of type 'ReduceData' across two OpenMP threads (lanes) in the same warp. It takes the following arguments as input:

a. variable of type 'ReduceData' on the calling lane, b. its lane_id, c. an offset relative to the current lane_id to generate a remote_lane_id. The remote lane contains the second variable of type 'ReduceData' that is to be reduced. d. an algorithm version parameter determining which reduction algorithm to use.

'shuffleReduceFn' retrieves data from the remote lane using efficient GPU shuffle intrinsics and reduces, using the algorithm specified by the 4th parameter, the two operands element-wise. The result is written to the first operand.

Different reduction algorithms are implemented in different runtime functions, all calling 'shuffleReduceFn' to perform the essential reduction step. Therefore, based on the 4th parameter, this function behaves slightly differently to cooperate with the runtime to ensure correctness under different circumstances.

'InterWarpCpyFn' is a pointer to a function that transfers reduced variables across warps. It tunnels, through CUDA shared memory, the thread-private data of type 'ReduceData' from lane 0 of each warp to a lane in the first warp.</li>
<li>Call the OpenMP runtime on the GPU to reduce across teams. The last team writes the global reduced value to memory.

ret = __kmpc_nvptx_teams_reduce_nowait(...,
            reduceData, shuffleReduceFn, interWarpCpyFn,
            scratchpadCopyFn, loadAndReduceFn)

'scratchpadCopyFn' is a helper that stores reduced data from the team master to a scratchpad array in global memory.

'loadAndReduceFn' is a helper that loads data from the scratchpad array and reduces it with the input operand.

These compiler generated functions hide address calculation and alignment information from the runtime.</li>
<li>if ret == 1: The team master of the last team stores the reduced result to the globals in memory. foo += reduceData.foo; bar *= reduceData.bar</li>
</ol>

<p>Warp Reduction Algorithms</p>


<p>On the warp level, we have three algorithms implemented in the OpenMP runtime depending on the number of active lanes:</p>


<p>Full Warp Reduction</p>


<p>The reduce algorithm within a warp where all lanes are active is implemented in the runtime as follows:</p>


<p>full_warp_reduce(void *reduce_data,
                 kmp_ShuffleReductFctPtr ShuffleReduceFn) { for (int offset = WARPSIZE/2; offset &gt; 0; offset /= 2) ShuffleReduceFn(reduce_data, 0, offset, 0); }</p>


<p>The algorithm completes in log(2, WARPSIZE) steps.</p>


<p>'ShuffleReduceFn' is used here with lane_id set to 0 because it is not used therefore we save instructions by not retrieving lane_id from the corresponding special registers. The 4th parameter, which represents the version of the algorithm being used, is set to 0 to signify full warp reduction.</p>


<p>In this version, 'ShuffleReduceFn' behaves, per element, as follows:</p>


<p>#reduce_elem refers to an element in the local lane's data structure #remote_elem is retrieved from a remote lane remote_elem = shuffle_down(reduce_elem, offset, WARPSIZE); reduce_elem = reduce_elem REDUCE_OP remote_elem;</p>


<p>Contiguous Partial Warp Reduction</p>


<p>This reduce algorithm is used within a warp where only the first 'n' (n &lt;= WARPSIZE) lanes are active. It is typically used when the number of OpenMP threads in a parallel region is not a multiple of WARPSIZE. The algorithm is implemented in the runtime as follows:</p>


<p>void contiguous_partial_reduce(void *reduce_data,
                          kmp_ShuffleReductFctPtr ShuffleReduceFn,
                          int size, int lane_id) { int curr_size; int offset; curr_size = size; mask = curr_size/2; while (offset&gt;0) { ShuffleReduceFn(reduce_data, lane_id, offset, 1); curr_size = (curr_size+1)/2; offset = curr_size/2; } }</p>


<p>In this version, 'ShuffleReduceFn' behaves, per element, as follows:</p>


<p>remote_elem = shuffle_down(reduce_elem, offset, WARPSIZE); if (lane_id &lt; offset) reduce_elem = reduce_elem REDUCE_OP remote_elem else reduce_elem = remote_elem</p>


<p>This algorithm assumes that the data to be reduced are located in a contiguous subset of lanes starting from the first. When there is an odd number of active lanes, the data in the last lane is not aggregated with any other lane's dat but is instead copied over.</p>


<p>Dispersed Partial Warp Reduction</p>


<p>This algorithm is used within a warp when any discontiguous subset of lanes are active. It is used to implement the reduction operation across lanes in an OpenMP simd region or in a nested parallel region.</p>


<p>void dispersed_partial_reduce(void *reduce_data,
                         kmp_ShuffleReductFctPtr ShuffleReduceFn) { int size, remote_id; int logical_lane_id = number_of_active_lanes_before_me() * 2; do { remote_id = next_active_lane_id_right_after_me();</p>


## the above function returns 0 of no active lane {#autotoc_md33}


## is present right after the current lane {#autotoc_md34}


<p>size = number_of_active_lanes_in_this_warp(); logical_lane_id /= 2; ShuffleReduceFn(reduce_data, logical_lane_id, remote_id-1-threadIdx.x, 2); } while (logical_lane_id % 2 == 0 &amp;&amp; size &gt; 1); }</p>


<p>There is no assumption made about the initial state of the reduction. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> number of lanes (&gt;=1) could be active at any position. The reduction result is returned in the first active lane.</p>


<p>In this version, 'ShuffleReduceFn' behaves, per element, as follows:</p>


<p>remote_elem = shuffle_down(reduce_elem, offset, WARPSIZE); if (lane_id % 2 == 0 &amp;&amp; offset &gt; 0) reduce_elem = reduce_elem REDUCE_OP remote_elem else reduce_elem = remote_elem</p>


<p>Intra-Team Reduction</p>


<p>This function, as implemented in the runtime call '__kmpc_nvptx_parallel_reduce_nowait_v2', aggregates data across OpenMP threads in a team. It first reduces within a warp using the aforementioned algorithms. We then proceed to gather all such reduced values at the first warp.</p>


<p>The runtime makes use of the function 'InterWarpCpyFn', which copies data from each of the "warp master" (zeroth lane of each warp, where warp-reduced data is held) to the zeroth warp. This step reduces (in a mathematical sense) the problem of reduction across warp masters in a block to the problem of warp reduction.</p>


<p>Inter-Team Reduction</p>


<p>Once a team has reduced its data to a single value, it is stored in a global scratchpad array. Since each team has a distinct slot, this can be done without locking.</p>


<p>The last team to write to the scratchpad array proceeds to reduce the scratchpad array. One or more workers in the last team use the helper 'loadAndReduceDataFn' to load and reduce values from the array, i.e., the k'th worker reduces every k'th element.</p>


<p>Finally, a call is made to '__kmpc_nvptx_parallel_reduce_nowait_v2' to reduce across workers and compute a globally reduced value.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the reduction was encountered. Must be within the associate directive and after the last local access to the reduction variables.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>An insertion point suitable for allocas usable in reductions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CodeGenIP</td>
<td class="doxyParamItemDescription"><p>An insertion point suitable for code generation.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionInfos</td>
<td class="doxyParamItemDescription"><p>A list of info on each reduction variable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsNoWait</td>
<td class="doxyParamItemDescription"><p>Optional flag set if the reduction is marked as nowait.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsTeamsReduction</td>
<td class="doxyParamItemDescription"><p>Optional flag set if it is a teams reduction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HasDistribute</td>
<td class="doxyParamItemDescription"><p>Optional flag set if it is a distribute reduction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GridValue</td>
<td class="doxyParamItemDescription"><p>Optional GPU grid value.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionBufNum</td>
<td class="doxyParamItemDescription"><p>Optional OpenMPCUDAReductionBufNumValue to be used for teams reduction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SrcLocInfo</td>
<td class="doxyParamItemDescription"><p>Source location information global.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1888 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 3534 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a59d23ba2e7eac46cbc6cd3086e013b49">llvm::AttrBuilder::addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a5d7d1a9d74e14b7535745a80fbc51f70">llvm::AttributeList::addFnAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a75e12544ba3cf3438ac62e2065e4941d">checkReductionInfos</a>, <a href="#a07f00f83b415baecc1af353eed43d123a9375884cf4ed31c834a626c324dddc67">Clang</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="#a355507f9e59388e467dc9288e4f82c3d">Config</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a82648246c07eb8a33f628eea28cb988c">llvm::StructType::create</a>, <a href="#a9199bb920d3966ef9c614a623c7af495">emitBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a7477aafbbe989ad35b96fac186d8e9fd">llvm::Function::getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a1cf553641e8527095ae4c8ec88a2cd92">llvm::AttributeList::getFnAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#ad52342fdd467389643191fdac7abcd40">getGridValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/reductioninfo/#a63498704b583a96137c70ed7172f1ec3">llvm::OpenMPIRBuilder::ReductionInfo::PrivateVariable</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/reductioninfo/#a6a824a78a70fdb0c3b258f3d93ffa071">llvm::OpenMPIRBuilder::ReductionInfo::ReductionGenClang</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#aa63e528eeff5082f6920b10244143920">llvm::AttrBuilder::removeAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a7e8dad1701aa6445be4a29f654b0473c">llvm::Value::replaceUsesWithIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="#a7f3588f949f4fb51454b0b8c6194ca75">T</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a> and <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/reductioninfo/#a5a2adb59d172175dafdc9466d436e198">llvm::OpenMPIRBuilder::ReductionInfo::Variable</a>.</p>

</div>
</div>

### createSection() {#a8565ee3d1c387153e57cd65a96390dfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> BodyGenCB, <a href="#a0c571620ff53fdb78e7404f5261dbd23">FinalizeCallbackTy</a> FiniCB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> section'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region body code.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FiniCB</td>
<td class="doxyParamItemDescription"><p>Callback to finalize variable copies.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion position <em>after</em> the section.</p></dd>
</dl>


<p>Declaration at line 2640 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 2314 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createSections() {#af36172c1f538b7305b44760997d5a3c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createSections (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="#a761a2c853c1d16b33e4e8c565ce0ca45">StorableBodyGenCallbackTy</a> &gt; SectionCBs, <a href="#a71b5ba020f68829f5a1fd99f48b63d42">PrivatizeCallbackTy</a> PrivCB, <a href="#a0c571620ff53fdb78e7404f5261dbd23">FinalizeCallbackTy</a> FiniCB, bool IsCancellable, bool IsNowait)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> sections'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion points to be used for alloca instructions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SectionCBs</td>
<td class="doxyParamItemDescription"><p>Callbacks that will generate body of each section.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PrivCB</td>
<td class="doxyParamItemDescription"><p>Callback to copy a given variable (think copy constructor).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FiniCB</td>
<td class="doxyParamItemDescription"><p>Callback to finalize variable copies.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsCancellable</td>
<td class="doxyParamItemDescription"><p>Flag to indicate a cancellable parallel region.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsNowait</td>
<td class="doxyParamItemDescription"><p>If true, barrier - to ensure all sections are executed before moving forward will not be generated.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion position <em>after</em> the sections.</p></dd>
</dl>


<p>Declaration at line 2629 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 2210 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/switchinst/#a62abc2475d09c01d583ba24a487898fd">llvm::SwitchInst::addCase</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada72881d16e555ca8525a916364048f9a69820949e2fb6d1d719487d27f0df883">llvm::Continue</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="#ae0287686a5ffe03bc264972c862726ea">createCanonicalLoop</a>, <a href="#a75f3209cae3f3f2700c6bc6e9623f841">FinalizationStack</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a756b28f370cd5a39bc0ee3e5333b9c9b">isConflictIP</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a03f30f48490558525cd5458201d13afe">llvm::splitBBWithSuffix</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createSingle() {#a3e1a0b27abb4d57e2293c46802eee89d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createSingle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> BodyGenCB, <a href="#a0c571620ff53fdb78e7404f5261dbd23">FinalizeCallbackTy</a> FiniCB, bool IsNowait, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * &gt; CPVars={}, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a> * &gt; CPFuncs={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> single'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region code.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FiniCB</td>
<td class="doxyParamItemDescription"><p>Callback to finalize variable copies.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsNowait</td>
<td class="doxyParamItemDescription"><p>If false, a barrier is emitted.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CPVars</td>
<td class="doxyParamItemDescription"><p>copyprivate variables.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CPFuncs</td>
<td class="doxyParamItemDescription"><p>copy functions to use for each copyprivate variable.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion position <em>after</em> the single call.</p></dd>
</dl>


<p>Declaration at line 2546 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5702 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#abca6530c9099bd1b1c3e0a5c32381f07">createBarrier</a>, <a href="#af2808c704c935cee35e9529907b59b1c">createCopyPrivate</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872ada475947399b8ab4d13d40fea50f950c">Int64</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createTarget() {#aa4d3157abd79d79562db3feb088706f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createTarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, bool IsOffloadEntry, <a href="#aafc1886793b898052f87edd7e9fdbaa3">OpenMPIRBuilder::InsertPointTy</a> AllocaIP, <a href="#aafc1886793b898052f87edd7e9fdbaa3">OpenMPIRBuilder::InsertPointTy</a> CodeGenIP, <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a> &amp; EntryInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetkerneldefaultattrs">TargetKernelDefaultAttrs</a> &amp; DefaultAttrs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetkernelruntimeattrs">TargetKernelRuntimeAttrs</a> &amp; RuntimeAttrs, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * IfCond, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; Inputs, <a href="#a249878a72f57b4634ae65800060983f5">GenMapInfoCallbackTy</a> GenMapInfoCB, <a href="#a73e20c5fd6145c56d7ce35c2ccd99e5b">TargetBodyGenCallbackTy</a> CBFunc, <a href="#a3ad579ff0c72b56f5ebc91bf2d747bc2">TargetGenArgAccessorsCallbackTy</a> ArgAccessorFuncCB, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/dependdata">DependData</a> &gt; Dependencies={}, bool HasNowait=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> target'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>where the target data construct was encountered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsOffloadEntry</td>
<td class="doxyParamItemDescription"><p>whether it is an offload entry.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CodeGenIP</td>
<td class="doxyParamItemDescription"><p>The insertion point where the call to the outlined function should be emitted.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryInfo</td>
<td class="doxyParamItemDescription"><p>The entry information about the function.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DefaultAttrs</td>
<td class="doxyParamItemDescription"><p>Structure containing the default attributes, including numbers of threads and teams to launch the kernel with.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RuntimeAttrs</td>
<td class="doxyParamItemDescription"><p>Structure containing the runtime numbers of threads and teams to launch the kernel with.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IfCond</td>
<td class="doxyParamItemDescription"><p>value of the <span class="doxyComputerOutput">if</span> clause.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Inputs</td>
<td class="doxyParamItemDescription"><p>The input values to the region that will be passed. as arguments to the outlined function.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region code.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ArgAccessorFuncCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate accessors instructions for passed in target arguments where neccessary</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Dependencies</td>
<td class="doxyParamItemDescription"><p>A vector of <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/dependdata">DependData</a> objects that carry dependency information as passed in the depend clause</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HasNowait</td>
<td class="doxyParamItemDescription"><p>Whether the target construct has a <span class="doxyComputerOutput">nowait</span> clause or not.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 3015 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 7587 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#a355507f9e59388e467dc9288e4f82c3d">Config</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a9acb4faf91112542d5ecf41230e9b64a">emitTargetCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#aa33db5ef74d376fb331f9549fb3cd9b3">emitTargetOutlinedFunction</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createTargetData() {#ae54a581ccf494afe52ae45af317bbd58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createTargetData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * DeviceID, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * IfCond, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/targetdatainfo">TargetDataInfo</a> &amp; Info, <a href="#a249878a72f57b4634ae65800060983f5">GenMapInfoCallbackTy</a> GenMapInfoCB, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a4c503140c7f851151906d85b515330e9">omp::RuntimeFunction</a> * MapperFunc=nullptr, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a>(<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP, <a href="#ae620d2ad309b2b4959c64edd1e040fdf">BodyGenTy</a> BodyGenType)&gt; BodyGenCB=nullptr, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(unsigned int, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *)&gt; DeviceAddrCB=nullptr, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *(unsigned int)&gt; CustomMapperCB=nullptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SrcLocInfo=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> target data'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the target data construct was encountered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion points to be used for alloca instructions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CodeGenIP</td>
<td class="doxyParamItemDescription"><p>The insertion point at which the target directive code should be placed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsBegin</td>
<td class="doxyParamItemDescription"><p>If true then emits begin mapper call otherwise emits end mapper call.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DeviceID</td>
<td class="doxyParamItemDescription"><p>Stores the DeviceID from the device clause.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IfCond</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> which corresponds to the if clause condition.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Info</td>
<td class="doxyParamItemDescription"><p>Stores all information realted to the <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Data directive.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GenMapInfoCB</td>
<td class="doxyParamItemDescription"><p>Callback that populates the MapInfos and returns.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Optional Callback to generate the region code.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DeviceAddrCB</td>
<td class="doxyParamItemDescription"><p>Optional callback to generate code related to use_device_ptr and use_device_addr.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CustomMapperCB</td>
<td class="doxyParamItemDescription"><p>Optional callback to generate code related to custom mappers.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 2975 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6546 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs/#aa998b8b179dd186fe4b5a1f6b6e25327">llvm::OpenMPIRBuilder::TargetDataRTArgs::BasePointersArray</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="#a355507f9e59388e467dc9288e4f82c3d">Config</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="#ae620d2ad309b2b4959c64edd1e040fdfac713c54bd088154d1f8a01438eebd845">DupNoPriv</a>, <a href="#a9199bb920d3966ef9c614a623c7af495">emitBlock</a>, <a href="#a39b12e3ad8afd4183a2cd63f1b1b8746">emitIfClause</a>, <a href="#a752e863c1af5fe463d0f08574492c12f">emitOffloadingArrays</a>, <a href="#adb95f78638066c9b6ccba6e3a7d335da">emitOffloadingArraysArgument</a>, <a href="#a2841680b34ec9c2c7185a877f8f8b4c8">emitTargetTask</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a788a72ddbf1bd572b3fcd7a5e7ec8cff">Int32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs/#aff8f3378279256a13c9938a109ef38fe">llvm::OpenMPIRBuilder::TargetDataRTArgs::MapNamesArray</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs/#a4b54534e64cdf22a09f26ddacebe69ac">llvm::OpenMPIRBuilder::TargetDataRTArgs::MappersArray</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs/#abfc59185affff631915c34412a350c8c">llvm::OpenMPIRBuilder::TargetDataRTArgs::MapTypesArray</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/#a87b3b8488a8b835c326ac389bed33f14">llvm::OpenMPIRBuilder::MapInfosTy::Names</a>, <a href="#ae620d2ad309b2b4959c64edd1e040fdfa7b1cf924c5bb380dcfd0245879230285">NoPriv</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs/#a44027c71c6a6a9a4111594eeb16da30e">llvm::OpenMPIRBuilder::TargetDataRTArgs::PointersArray</a>, <a href="#ae620d2ad309b2b4959c64edd1e040fdfa69cba2948bbfa254aa9dbd932f56756b">Priv</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs/#a00635325d57af0b95f0b797f63ee6df6">llvm::OpenMPIRBuilder::TargetDataRTArgs::SizesArray</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createTargetDeinit() {#a1e1e2695745252cae26a9843b4d8daa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::createTargetDeinit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, int32_t TeamsReductionDataSize=0, int32_t TeamsReductionBufferLength=1024)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a runtime call for kmpc_target_deinit.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TeamsReductionDataSize</td>
<td class="doxyParamItemDescription"><p>The maximal size of all the reduction data for teams reduction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TeamsReductionBufferLength</td>
<td class="doxyParamItemDescription"><p>The number of elements (each of up to <span class="doxyComputerOutput">TeamsReductionDataSize</span> size), in the teams reduction buffer.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 2785 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6330 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad7fa9b738742521d0a684cec016ef47e">llvm::ConstantFoldInsertValueInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae2705fd641fb3d1eefa2691b5117cf22">llvm::StringRef::drop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aca439bf65258d9d8d057812938b617c5">llvm::StringRef::ends_with</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a788a72ddbf1bd572b3fcd7a5e7ec8cff">Int32</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a>.</p>

</div>
</div>

### createTargetInit() {#a7db9daa323dee69eb9ecc380ce6edae8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointTy OpenMPIRBuilder::createTargetInit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetkerneldefaultattrs">llvm::OpenMPIRBuilder::TargetKernelDefaultAttrs</a> &amp; Attrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <span class="doxyComputerOutput">omp target</span> interface.</p>


<p>For more information about the usage of this interface,</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>openmp/libomptarget/deviceRTLs/common/include/target.h</p></dd>
</dl>


<p>{ Create a runtime call for kmpc_target_init</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Attrs</td>
<td class="doxyParamItemDescription"><p>Structure containing the default attributes, including numbers of threads and teams to launch the kernel with.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 2774 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6191 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae2705fd641fb3d1eefa2691b5117cf22">llvm::StringRef::drop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aca439bf65258d9d8d057812938b617c5">llvm::StringRef::ends_with</a>, <a href="/web-llvm/docs/api/classes/llvm/constantstruct/#a54fcfa620deb80373f489ba2fdad7643">llvm::ConstantStruct::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#acac8bfd6018661b40690c621bece1540">llvm::ConstantExpr::getAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aecf2b6d6f052a378dd8f69fd1bb700b1">llvm::Function::getArg</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aa286a0f7f5d38488d593bb7ef0ba183e">llvm::BasicBlock::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a3275c50993afaf4fdd723640c2c3ca0f">llvm::Function::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a161fd4e9fa5367f64c2a4c9e921c3ad3">llvm::BasicBlock::getFirstInsertionPt</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#ad52342fdd467389643191fdac7abcd40">getGridValue</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a9ad53d2a00a6fb861b3a048c6592b742">llvm::ConstantInt::getSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a913a5d4b2cddde762446bd494e81a3f2">llvm::GlobalValue::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a150558aeaa819431aeb9729d26b2ac9f">Int16</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a788a72ddbf1bd572b3fcd7a5e7ec8cff">Int32</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcorelowerthreadlocal-cpp/#aa5ae01d4881f7ebccb4f8738541721ca">MaxThreads</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">llvm::GlobalValue::NotThreadLocal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#aa0c0d79dafb0d22308ce48808689f430a338c51f37ed4e4b2c9973a383c566c19">llvm::omp::OMP_TGT_EXEC_MODE_SPMD</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195ae1cc9a390520055573d459de25747caa">llvm::GlobalValue::ProtectedVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aa242d8ab89216c14beab812e07009b2a">llvm::GlobalValue::setVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a52c990590792c91dd20b6d45acebe359">llvm::BasicBlock::splitBasicBlock</a>, <a href="#a7f3588f949f4fb51454b0b8c6194ca75">T</a>, <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca696bb1c9b0b0e76bb70c61f68866452a">llvm::GlobalValue::WeakODRLinkage</a>, <a href="#ab79b6d86df13a709eee10c4c7d39c644">writeTeamsForKernel</a> and <a href="#a0ea31ab1f2b7d1f5585df18b0528fcf3">writeThreadBoundsForKernel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a>.</p>

</div>
</div>

### createTask() {#a0af3c7a02c1325c04c59f857604bd4f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createTask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> BodyGenCB, bool Tied=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Final=nullptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * IfCondition=nullptr, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/dependdata">DependData</a> &gt; Dependencies={}, bool Mergeable=false, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * EventHandle=nullptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Priority=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for <span class="doxyComputerOutput">#omp task</span></p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the task construct was encountered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion point to be used for alloca instructions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region code.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Tied</td>
<td class="doxyParamItemDescription"><p>True if the task is tied, false if the task is untied.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Final</td>
<td class="doxyParamItemDescription"><p>i1 value which is <span class="doxyComputerOutput">true</span> if the task is final, <span class="doxyComputerOutput">false</span> if the task is not final.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IfCondition</td>
<td class="doxyParamItemDescription"><p>i1 value. If it evaluates to <span class="doxyComputerOutput">false</span>, an undeferred task is generated, and the encountering thread must suspend the current task region, for which execution cannot be resumed until execution of the structured block that is associated with the generated task is completed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EventHandle</td>
<td class="doxyParamItemDescription"><p>If present, signifies the event handle as part of the detach clause</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Mergeable</td>
<td class="doxyParamItemDescription"><p>If the given task is <span class="doxyComputerOutput">mergeable</span></p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">priority</td>
<td class="doxyParamItemDescription"><p>‘priority-value` specifies the execution order of the tasks that is generated by the construct</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 1877 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#a5610e0ef8f016e84694778d8ce1c9479">addOutlineInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#adde2ea00dd2613ee41bfe91908e4e68e">llvm::CallBase::arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#afbc181ceecaec94bd0ea2eab8f23cbd8">llvm::BasicBlock::back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a35409dbaffc2cf38fefec12e3cf9094d">createFakeIntVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9dda4472ee0b7ea92ab49eedf6e13d50">llvm::divideCeil</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#adc0b48022847ca44b3868d058cb98686">llvm::OpenMPIRBuilder::OutlineInfo::EntryBB</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#a5abe93575e72c30376079d2fb31b40f8">llvm::OpenMPIRBuilder::OutlineInfo::ExcludeArgsFromAggregate</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#adb6b79680b86167fd4ec4f32346e9e58">llvm::OpenMPIRBuilder::OutlineInfo::ExitBB</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpointernull/#a96f5c85e4022e369266541b2db3fda69">llvm::ConstantPointerNull::get</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a18fc4545474c6ebb6f7c547f64f4fb31">llvm::StructType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a9b5ec84ea363eca9e35ddca20a5313af">llvm::AllocaInst::getAllocatedType</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/insertpoint/#a3d072f8ac5e1b0724c4bb5a77adae9da">llvm::IRBuilderBase::InsertPoint::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a169f0c26ef46161741fdd120a806f853">llvm::Function::getEntryBlock</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a47f5c74e1b14ba4a61db057400644acc">llvm::Value::getPointerAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23f9ec4bb2576ca8738f3edc9c4f5cdf">llvm::Int32Ty</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#aed0779b309d9a705e9b78adacc839875">llvm::OpenMPIRBuilder::OutlineInfo::OuterAllocaBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#a0b8f73f7987421a24a842d3e2633278d">llvm::OpenMPIRBuilder::OutlineInfo::PostOutlineCB</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a85ee70791795fa2ddb07694182f783b2">llvm::splitBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7ac00229d8c59902686f52ed061cdc80">llvm::SplitBlockAndInsertIfThenElse</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createTaskgroup() {#a1f8b732c2f951d56302d4431f00f16bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createTaskgroup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> BodyGenCB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for the taskgroup construct.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the taskgroup construct was encountered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion point to be used for alloca instructions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region code.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 2181 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a85ee70791795fa2ddb07694182f783b2">llvm::splitBB</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createTaskwait() {#a419ffad9e4d59275e299ce1ad3c73cd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::createTaskwait (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> taskwait'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the taskwait directive was encountered.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 1785 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#a177df2c9d7d8692ed214018f420c3de6">emitTaskwaitImpl</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createTaskyield() {#a0b0ed7f600549e4239bf10b5b85de66c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::createTaskyield (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> taskyield'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the taskyield directive was encountered.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 1803 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#a6383328cfcdbbd56502b92f9e2415432">emitTaskyieldImpl</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### createTeams() {#a3f603d822817256077c95e6573f2b14a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createTeams (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> BodyGenCB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NumTeamsLower=nullptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NumTeamsUpper=nullptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ThreadLimit=nullptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * IfExpr=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for <span class="doxyComputerOutput">#omp teams</span></p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the teams construct was encountered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region code.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumTeamsLower</td>
<td class="doxyParamItemDescription"><p>Lower bound on number of teams. If this is nullptr, it is as if lower bound is specified as equal to upperbound. If this is non-null, then upperbound must also be non-null.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumTeamsUpper</td>
<td class="doxyParamItemDescription"><p>Upper bound on the number of teams.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ThreadLimit</td>
<td class="doxyParamItemDescription"><p>on the number of threads that may participate in a contention group created by each team.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IfExpr</td>
<td class="doxyParamItemDescription"><p>is the integer argument value of the if condition on the teams clause.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 2657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9020 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#a5610e0ef8f016e84694778d8ce1c9479">addOutlineInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#adde2ea00dd2613ee41bfe91908e4e68e">llvm::CallBase::arg_size</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#ac6baa801e4aea800984e760d5460662f">llvm::Function::arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a355507f9e59388e467dc9288e4f82c3d">Config</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a35409dbaffc2cf38fefec12e3cf9094d">createFakeIntVal</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#adc0b48022847ca44b3868d058cb98686">llvm::OpenMPIRBuilder::OutlineInfo::EntryBB</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#a5abe93575e72c30376079d2fb31b40f8">llvm::OpenMPIRBuilder::OutlineInfo::ExcludeArgsFromAggregate</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#adb6b79680b86167fd4ec4f32346e9e58">llvm::OpenMPIRBuilder::OutlineInfo::ExitBB</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aecf2b6d6f052a378dd8f69fd1bb700b1">llvm::Function::getArg</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a169f0c26ef46161741fdd120a806f853">llvm::Function::getEntryBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#aba0055050d741f60b6e0523507a2c79f">llvm::Value::getNumUses</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a3cc05cd6e06dd1976f88ed7d808ac0a1">Int1</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#aed0779b309d9a705e9b78adacc839875">llvm::OpenMPIRBuilder::OutlineInfo::OuterAllocaBB</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#a0b8f73f7987421a24a842d3e2633278d">llvm::OpenMPIRBuilder::OutlineInfo::PostOutlineCB</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a85ee70791795fa2ddb07694182f783b2">llvm::splitBB</a>, <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a46db903db2484e1ef5062d094d6b0854">llvm::Value::user_back</a>.</p>

</div>
</div>

### emitBlock() {#a9199bb920d3966ef9c614a623c7af495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::emitBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * CurFn, bool IsFinished=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 8368 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#a0c977097cc5c8d9c7c049e8fc988fdcf">emitBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#ae4ca2261b8b901e415fda7feac5051ea">llvm::Function::end</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a8dd327a937563afdb08250abc43820b0">llvm::BasicBlock::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aaab8110aafc070c83bc701b13d2260df">llvm::Function::insert</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a>.</p>


<p>Referenced by <a href="#aaa655ca8bca40c564d0b7c81ebaf8ff9">createReductionsGPU</a>, <a href="#ae54a581ccf494afe52ae45af317bbd58">createTargetData</a>, <a href="#a39b12e3ad8afd4183a2cd63f1b1b8746">emitIfClause</a>, <a href="#a9f09d4b7d64e71987be7bb45d8694ffe">emitKernelLaunch</a> and <a href="#aad01bd2643d37f64f9d9a2933b8ddfc2">emitUserDefinedMapper</a>.</p>

</div>
</div>

### emitBranch() {#a0c977097cc5c8d9c7c049e8fc988fdcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::emitBranch (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Target)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 8354 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>.</p>


<p>Referenced by <a href="#a9199bb920d3966ef9c614a623c7af495">emitBlock</a>, <a href="#a39b12e3ad8afd4183a2cd63f1b1b8746">emitIfClause</a> and <a href="#a9f09d4b7d64e71987be7bb45d8694ffe">emitKernelLaunch</a>.</p>

</div>
</div>

### emitCancelationCheckImpl() {#a98b55a0d95b3926151545101e4f2aef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error OpenMPIRBuilder::emitCancelationCheckImpl (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * CancelFlag, omp::Directive CanceledDirective, <a href="#a0c571620ff53fdb78e7404f5261dbd23">FinalizeCallbackTy</a> ExitCB={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate control flow and cleanup for cancellation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CancelFlag</td>
<td class="doxyParamItemDescription"><p>Flag indicating if the cancellation is performed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CanceledDirective</td>
<td class="doxyParamItemDescription"><p>The kind of directive that is cancled.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ExitCB</td>
<td class="doxyParamItemDescription"><p>Extra code to be generated in the exit block.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an error, if any were triggered during execution.</p></dd>
</dl>


<p>Declaration at line 2029 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 1209 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="#a75f3209cae3f3f2700c6bc6e9623f841">FinalizationStack</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aa286a0f7f5d38488d593bb7ef0ba183e">llvm::BasicBlock::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="#ad44e60b9d264f6ceb54e6cd660e859fb">isLastFinalizationInfoCancellable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac6c9ffe7979754415f4ca0d677174bc2">llvm::SplitBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#abca6530c9099bd1b1c3e0a5c32381f07">createBarrier</a> and <a href="#a04285415a321e48322c08f3b9185540e">createCancel</a>.</p>

</div>
</div>

### emitFlush() {#a2a4b97bb7670d306c756cdbd5ee9b560}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::emitFlush (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate a flush runtime call.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location at which the request originated and is fulfilled.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 2053 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 1757 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a> and <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>.</p>


<p>Referenced by <a href="#afc2cc623eda981e1b3fbb61a44e80ef8">createFlush</a>.</p>

</div>
</div>

### emitIfClause() {#a39b12e3ad8afd4183a2cd63f1b1b8746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error OpenMPIRBuilder::emitIfClause (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond, <a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> ThenGen, <a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> ElseGen, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits code for OpenMP 'if' clause using specified <em><a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a></em> Here is the logic: if (Cond) { ThenGen(); } else { ElseGen(); }.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an error, if any were triggered during execution.</p></dd>
</dl>


<p>Declaration at line 2164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 8389 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a9199bb920d3966ef9c614a623c7af495">emitBlock</a>, <a href="#a0c977097cc5c8d9c7c049e8fc988fdcf">emitBranch</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#ae54a581ccf494afe52ae45af317bbd58">createTargetData</a>.</p>

</div>
</div>

### emitKernelExecutionMode() {#a1943d078483c15aa78cb00f7fff2590c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * OpenMPIRBuilder::emitKernelExecutionMode (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> KernelName, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#aa0c0d79dafb0d22308ce48808689f430">omp::OMPTgtExecModeFlags</a> Mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the kernel execution mode.</p>

<p>Declaration at line 2019 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 882 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195ae1cc9a390520055573d459de25747caa">llvm::GlobalValue::ProtectedVisibility</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca8d13a9bcecfac72febceb1103afa048f">llvm::GlobalValue::WeakAnyLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a>.</p>

</div>
</div>

### emitKernelLaunch() {#a9f09d4b7d64e71987be7bb45d8694ffe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::emitKernelLaunch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OutlinedFnID, <a href="#a8be6d9636392371c1467984a429573a4">EmitFallbackCallbackTy</a> EmitTargetCallFallbackCB, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetkernelargs">TargetKernelArgs</a> &amp; Args, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * DeviceID, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RTLoc, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate a target region entry call and host fallback call.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location at which the request originated and is fulfilled.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OutlinedFnID</td>
<td class="doxyParamItemDescription"><p>The ooulined function <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EmitTargetCallFallbackCB</td>
<td class="doxyParamItemDescription"><p>Call back function to generate host fallback code.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Args</td>
<td class="doxyParamItemDescription"><p>Data structure holding information about the kernel arguments.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DeviceID</td>
<td class="doxyParamItemDescription"><p>Identifier for the device via the 'device' clause.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RTLoc</td>
<td class="doxyParamItemDescription"><p>Source location identifier</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion point to be used for alloca instructions.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 2419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 1145 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="#a9199bb920d3966ef9c614a623c7af495">emitBlock</a>, <a href="#a0c977097cc5c8d9c7c049e8fc988fdcf">emitBranch</a>, <a href="#ad48c785749c7160070b39be42c67d2b7">emitTargetKernel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2cd7b2e49608a96ba42f59f642cf99ac">llvm::Failed</a>, <a href="#a49e1f0512e7d7b37dfcecc0b25dd875b">getKernelArgsVector</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### emitMapperCall() {#a654b33adee2ae78ce74ecbe6aa5e5282}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::emitMapperCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * MapperFunc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SrcLocInfo, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * MaptypesArg, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * MapnamesArg, struct <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapperallocas">MapperAllocas</a> &amp; MapperAllocas, int64_t DeviceID, unsigned NumOperands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create the call for the target mapper function.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MapperFunc</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> to be called.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SrcLocInfo</td>
<td class="doxyParamItemDescription"><p>Source location information global.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaptypesArg</td>
<td class="doxyParamItemDescription"><p>The argument types.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MapnamesArg</td>
<td class="doxyParamItemDescription"><p>The argument names.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapperallocas"&gt;MapperAllocas&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> used for the call.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DeviceID</td>
<td class="doxyParamItemDescription"><p>Device <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the call.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumOperands</td>
<td class="doxyParamItemDescription"><p>Number of operands in the call.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 2196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 7721 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapperallocas/#aa90c5e272864414356fbeede370d5053">llvm::OpenMPIRBuilder::MapperAllocas::Args</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapperallocas/#a9d27bf73f53ec62c72ffd3137f47efde">llvm::OpenMPIRBuilder::MapperAllocas::ArgsBase</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapperallocas/#ad41f11a634af5e69560ac0279c74b100">llvm::OpenMPIRBuilder::MapperAllocas::ArgSizes</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872ada475947399b8ab4d13d40fea50f950c">Int64</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>

</div>
</div>

### emitNonContiguousDescriptor() {#a827b80924bcd29f32b772a4ed162fb68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::emitNonContiguousDescriptor (<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty">MapInfosTy</a> &amp; CombinedInfo, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/targetdatainfo">TargetDataInfo</a> &amp; Info)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit an array of struct descriptors to be assigned to the offload args.</p>

<p>Declaration at line 2464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 7806 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/structnoncontiguousinfo/#a91a7ec15dbfee1518848d8c415e8ec1b">llvm::OpenMPIRBuilder::MapInfosTy::StructNonContiguousInfo::Counts</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a82648246c07eb8a33f628eea28cb988c">llvm::StructType::create</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/structnoncontiguousinfo/#a455750a6772d7b4dbf49c6e2a6892bee">llvm::OpenMPIRBuilder::MapInfosTy::StructNonContiguousInfo::Dims</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a9b5ec84ea363eca9e35ddca20a5313af">llvm::AllocaInst::getAllocatedType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/#add3dff2ccb3dbfbc0659e74acec6c421">llvm::OpenMPIRBuilder::MapInfosTy::NonContigInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/structnoncontiguousinfo/#a279b64a58a905fae32a957b2e0036b6a">llvm::OpenMPIRBuilder::MapInfosTy::StructNonContiguousInfo::Offsets</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/structnoncontiguousinfo/#ae4726949bede9ff73a4defca2a4e00d7">llvm::OpenMPIRBuilder::MapInfosTy::StructNonContiguousInfo::Strides</a>.</p>


<p>Referenced by <a href="#a752e863c1af5fe463d0f08574492c12f">emitOffloadingArrays</a>.</p>

</div>
</div>

### emitOffloadingArrays() {#a752e863c1af5fe463d0f08574492c12f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::emitOffloadingArrays (<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty">MapInfosTy</a> &amp; CombinedInfo, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/targetdatainfo">TargetDataInfo</a> &amp; Info, bool IsNonContiguous=false, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(unsigned int, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *)&gt; DeviceAddrCB=nullptr, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *(unsigned int)&gt; CustomMapperCB=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the arrays used to pass the captures and map information to the offloading runtime library.</p>


<p>If there is no map or capture information, return nullptr by reference. Accepts a reference to a <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty">MapInfosTy</a> object that contains information generated for mappable clauses, including base pointers, pointers, sizes, map types, user-defined mappers.</p>


<p>Declaration at line 2474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 8163 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#a5fd26a28fedc9044dd6939648d55c429add7bf230fde8d4836917806aff6a6b27">Address</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a8cfcd92a373cdd7deefb939dd76b83e3">llvm::SmallBitVector::all</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#ab06e25d03b0091f03f2a25118933236b">llvm::SmallBitVector::any</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/#a7f0b33fc6977b91af2e3a595430af816">llvm::OpenMPIRBuilder::MapInfosTy::BasePointers</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#ab1aa0d632549db4855d6412f4d2d44ae">createOffloadMapnames</a>, <a href="#ad56f71598b251a0f66e590c94d01c67b">createOffloadMaptypes</a>, <a href="#a488c861f8a68e5f78ceca8b57acd8be5">createPlatformSpecificName</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/#a71a5c5757b7d47dac50e0cdd270e52ae">llvm::OpenMPIRBuilder::MapInfosTy::DevicePointers</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/structnoncontiguousinfo/#a455750a6772d7b4dbf49c6e2a6892bee">llvm::OpenMPIRBuilder::MapInfosTy::StructNonContiguousInfo::Dims</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a827b80924bcd29f32b772a4ed162fb68">emitNonContiguousDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantarray/#a0900dacdc7ad8e3ea0cc92993c7fd422">llvm::ConstantArray::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpointernull/#a96f5c85e4022e369266541b2db3fda69">llvm::ConstantPointerNull::get</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a9b5ec84ea363eca9e35ddca20a5313af">llvm::AllocaInst::getAllocatedType</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#ad92f6c67d55ced3de1569ee791c38679">llvm::AllocaInst::getAllocationSize</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a5d19f3955a23e8eb2a974efcc8fb19da">llvm::AllocaInst::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ae8df4be75bfc50b1eadd74e85c25fa45a4cc6684df7b4a92b1dec6fce3264fac8">llvm::GlobalValue::Global</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/#a87b3b8488a8b835c326ac389bed33f14">llvm::OpenMPIRBuilder::MapInfosTy::Names</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/#add3dff2ccb3dbfbc0659e74acec6c421">llvm::OpenMPIRBuilder::MapInfosTy::NonContigInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/structnoncontiguousinfo/#a279b64a58a905fae32a957b2e0036b6a">llvm::OpenMPIRBuilder::MapInfosTy::StructNonContiguousInfo::Offsets</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a5fd26a28fedc9044dd6939648d55c429a61cf8510205077b6f5491d38cd44c0f7">Pointer</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/#ac3fbb78e0f7d3e62a8dc557721b761c2">llvm::OpenMPIRBuilder::MapInfosTy::Pointers</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca04ed141708c0fd16723d212502b046ae">llvm::GlobalValue::PrivateLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a18e2d7efe05987370dc6b5c54797fcf5">llvm::SmallBitVector::set</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#af3bb24b322533dbe8a63c84b18568fe1">llvm::AllocaInst::setAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/#aae351998f1a0107dc5b8f4ea32fe0c60">llvm::OpenMPIRBuilder::MapInfosTy::Sizes</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a585f149dd8c344a40c53b1694d3161ed">llvm::SmallBitVector::test</a> and <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/#a81575ee2bccba5b439ed4d436ffa53ed">llvm::OpenMPIRBuilder::MapInfosTy::Types</a>.</p>


<p>Referenced by <a href="#ae54a581ccf494afe52ae45af317bbd58">createTargetData</a> and <a href="#a966e441c1e3f27fce994c360b55abae9">emitOffloadingArraysAndArgs</a>.</p>

</div>
</div>

### emitOffloadingArraysAndArgs() {#a966e441c1e3f27fce994c360b55abae9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::emitOffloadingArraysAndArgs (<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/targetdatainfo">TargetDataInfo</a> &amp; Info, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs">TargetDataRTArgs</a> &amp; RTArgs, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty">MapInfosTy</a> &amp; CombinedInfo, bool IsNonContiguous=false, bool ForEndCall=false, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(unsigned int, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *)&gt; DeviceAddrCB=nullptr, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *(unsigned int)&gt; CustomMapperCB=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocates memory for and populates the arrays required for offloading (offload_{baseptrs|ptrs|mappers|sizes|maptypes|mapnames}).</p>


<p>Then, it emits their base addresses as arguments to be passed to the runtime library. In essence, this function is a combination of emitOffloadingArrays and emitOffloadingArraysArgument and should arguably be preferred by clients of <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder">OpenMPIRBuilder</a>.</p>


<p>Declaration at line 2486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 7393 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#a752e863c1af5fe463d0f08574492c12f">emitOffloadingArrays</a> and <a href="#adb95f78638066c9b6ccba6e3a7d335da">emitOffloadingArraysArgument</a>.</p>

</div>
</div>

### emitOffloadingArraysArgument() {#adb95f78638066c9b6ccba6e3a7d335da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::emitOffloadingArraysArgument (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs">OpenMPIRBuilder::TargetDataRTArgs</a> &amp; RTArgs, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/targetdatainfo">OpenMPIRBuilder::TargetDataInfo</a> &amp; Info, bool ForEndCall=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the arguments to be passed to the runtime library based on the arrays of base pointers, pointers, sizes, map types, and mappers.</p>


<p>If ForEndCall, emit map types to be passed for the end of the region instead of the beginning.</p>


<p>Declaration at line 2458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 7748 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs/#aa998b8b179dd186fe4b5a1f6b6e25327">llvm::OpenMPIRBuilder::TargetDataRTArgs::BasePointersArray</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpointernull/#a96f5c85e4022e369266541b2db3fda69">llvm::ConstantPointerNull::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs/#aff8f3378279256a13c9938a109ef38fe">llvm::OpenMPIRBuilder::TargetDataRTArgs::MapNamesArray</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs/#a4b54534e64cdf22a09f26ddacebe69ac">llvm::OpenMPIRBuilder::TargetDataRTArgs::MappersArray</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs/#abfc59185affff631915c34412a350c8c">llvm::OpenMPIRBuilder::TargetDataRTArgs::MapTypesArray</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs/#a44027c71c6a6a9a4111594eeb16da30e">llvm::OpenMPIRBuilder::TargetDataRTArgs::PointersArray</a> and <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs/#a00635325d57af0b95f0b797f63ee6df6">llvm::OpenMPIRBuilder::TargetDataRTArgs::SizesArray</a>.</p>


<p>Referenced by <a href="#ae54a581ccf494afe52ae45af317bbd58">createTargetData</a> and <a href="#a966e441c1e3f27fce994c360b55abae9">emitOffloadingArraysAndArgs</a>.</p>

</div>
</div>

### emitTargetKernel() {#ad48c785749c7160070b39be42c67d2b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointTy OpenMPIRBuilder::emitTargetKernel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; Return, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ident, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * DeviceID, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NumTeams, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NumThreads, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * HostPtr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; KernelArgs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate a target region entry call.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location at which the request originated and is fulfilled.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion point to be used for alloca instructions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Return</td>
<td class="doxyParamItemDescription"><p>Return value of the created function returned by reference.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DeviceID</td>
<td class="doxyParamItemDescription"><p>Identifier for the device via the 'device' clause.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumTeams</td>
<td class="doxyParamItemDescription"><p>Numer of teams for the region via the 'num_teams' clause or 0 if unspecified and -1 if there is no 'teams' clause.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumThreads</td>
<td class="doxyParamItemDescription"><p>Number of threads via the 'thread_limit' clause.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HostPtr</td>
<td class="doxyParamItemDescription"><p>Pointer to the host-side pointer of the target kernel.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">KernelArgs</td>
<td class="doxyParamItemDescription"><p>Array of arguments to the kernel.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 2044 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 1115 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#a034dc6253a2a36f78ac071a7c12d5c27">getOrCreateRuntimeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a>.</p>


<p>Referenced by <a href="#a9f09d4b7d64e71987be7bb45d8694ffe">emitKernelLaunch</a>.</p>

</div>
</div>

### emitTargetRegionFunction() {#a567502d7244077ed45e0c9471d31ba4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error OpenMPIRBuilder::emitTargetRegionFunction (<a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a> &amp; EntryInfo, <a href="#a05c4178639e79ab4749063b330cff5da">FunctionGenCallback</a> &amp; GenerateFunctionCallback, bool IsOffloadEntry, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *&amp; OutlinedFn, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *&amp; OutlinedFnID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a unique name for the entry function using the source location information of the current target region.</p>


<p>The name will be something like:</p>


<p>__omp_offloading_DD_FFFF_PP_lBB[_CC]</p>


<p>where DD_FFFF is an <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> unique to the file (device and file IDs), PP is the mangled name of the function that encloses the target region and BB is the line number of the target region. CC is a count added when more than one region is located at the same location.</p>


<p>If this target outline function is not an offload entry, we don't need to register it. This may happen if it is guarded by an if clause that is false at compile time, or no target archs have been specified.</p>


<p>The created target region <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> is used by the runtime library to identify the current target region, so it only has to be unique and not necessarily point to anything. It could be the pointer to the outlined function that implements the target region, but we aren't using that so that the compiler doesn't need to keep that, and could therefore inline the host function if proven worthwhile during optimization. In the other hand, if emitting code for the device, the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> has to be the function address so that it can retrieved from the offloading entry and launched by the runtime library. We also mark the outlined function to have external linkage in case we are emitting code for the device, because these functions will be entry points to the device.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">InfoManager</td>
<td class="doxyParamItemDescription"><p>The info manager keeping track of the offload entries</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryInfo</td>
<td class="doxyParamItemDescription"><p>The entry information about the function</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GenerateFunctionCallback</td>
<td class="doxyParamItemDescription"><p>The callback function to generate the code</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OutlinedFunction</td>
<td class="doxyParamItemDescription"><p>Pointer to the outlined function</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryFnIDName</td>
<td class="doxyParamItemDescription"><p>Name of the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> o be created</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 2860 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6500 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#a355507f9e59388e467dc9288e4f82c3d">Config</a>, <a href="#a488c861f8a68e5f78ceca8b57acd8be5">createPlatformSpecificName</a>, <a href="#aed2a8b469e9884788eef400fbc892dd3">OffloadInfoManager</a>, <a href="#a17c7f65c3ce26b3b0de6774c0d3c723f">registerTargetRegionFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#aa33db5ef74d376fb331f9549fb3cd9b3">emitTargetOutlinedFunction</a>.</p>

</div>
</div>

### emitTargetTask() {#a2841680b34ec9c2c7185a877f8f8b4c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::emitTargetTask (<a href="#a5f44f79e28451e12a142140450888ecd">TargetTaskBodyCallbackTy</a> TaskBodyCB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * DeviceID, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RTLoc, <a href="#aafc1886793b898052f87edd7e9fdbaa3">OpenMPIRBuilder::InsertPointTy</a> AllocaIP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/dependdata">llvm::OpenMPIRBuilder::DependData</a> &gt; &amp; Dependencies, bool HasNoWait)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate a target-task for the target construct.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TaskBodyCB</td>
<td class="doxyParamItemDescription"><p>Callback to generate the actual body of the target task.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DeviceID</td>
<td class="doxyParamItemDescription"><p>Identifier for the device via the 'device' clause.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RTLoc</td>
<td class="doxyParamItemDescription"><p>Source location identifier</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion point to be used for alloca instructions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Dependencies</td>
<td class="doxyParamItemDescription"><p>Vector of <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/dependdata">DependData</a> objects holding information of dependencies as specified by the 'depend' clause.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HasNoWait</td>
<td class="doxyParamItemDescription"><p>True if the target construct had 'nowait' on it, false otherwise</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 2448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 7113 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#a5610e0ef8f016e84694778d8ce1c9479">addOutlineInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#adde2ea00dd2613ee41bfe91908e4e68e">llvm::CallBase::arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a35409dbaffc2cf38fefec12e3cf9094d">createFakeIntVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3fb4884285f5bcb9a37d9378d1e33cd5">emitTargetTaskProxyFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a9702d30c99a5459e9565631adf1fdf1b">emitTaskDependencies</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#adc0b48022847ca44b3868d058cb98686">llvm::OpenMPIRBuilder::OutlineInfo::EntryBB</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#a5abe93575e72c30376079d2fb31b40f8">llvm::OpenMPIRBuilder::OutlineInfo::ExcludeArgsFromAggregate</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#adb6b79680b86167fd4ec4f32346e9e58">llvm::OpenMPIRBuilder::OutlineInfo::ExitBB</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpointernull/#a96f5c85e4022e369266541b2db3fda69">llvm::ConstantPointerNull::get</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/insertpoint/#a3d072f8ac5e1b0724c4bb5a77adae9da">llvm::IRBuilderBase::InsertPoint::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#aba0055050d741f60b6e0523507a2c79f">llvm::Value::getNumUses</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a47f5c74e1b14ba4a61db057400644acc">llvm::Value::getPointerAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#aed0779b309d9a705e9b78adacc839875">llvm::OpenMPIRBuilder::OutlineInfo::OuterAllocaBB</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#a0b8f73f7987421a24a842d3e2633278d">llvm::OpenMPIRBuilder::OutlineInfo::PostOutlineCB</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a85ee70791795fa2ddb07694182f783b2">llvm::splitBB</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a46db903db2484e1ef5062d094d6b0854">llvm::Value::user_back</a>.</p>


<p>Referenced by <a href="#ae54a581ccf494afe52ae45af317bbd58">createTargetData</a>.</p>

</div>
</div>

### emitTaskwaitImpl() {#a177df2c9d7d8692ed214018f420c3de6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::emitTaskwaitImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate a taskwait runtime call.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location at which the request originated and is fulfilled.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 2071 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 1772 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a> and <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a>.</p>


<p>Referenced by <a href="#a419ffad9e4d59275e299ce1ad3c73cd4">createTaskwait</a>.</p>

</div>
</div>

### emitTaskyieldImpl() {#a6383328cfcdbbd56502b92f9e2415432}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::emitTaskyieldImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate a taskyield runtime call.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location at which the request originated and is fulfilled.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 2076 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 1791 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a788a72ddbf1bd572b3fcd7a5e7ec8cff">Int32</a>.</p>


<p>Referenced by <a href="#a0b0ed7f600549e4239bf10b5b85de66c">createTaskyield</a>.</p>

</div>
</div>

### emitUsed() {#a3bb33831dbcaa836f630ed1dc986b5c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::emitUsed (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">llvm::WeakTrackingVH</a> &gt; List)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the llvm.used metadata.</p>

<p>Declaration at line 2016 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 860 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca96ad6314ba9210b223b93dc3e15baf99">llvm::GlobalValue::AppendingLinkage</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantarray/#a0900dacdc7ad8e3ea0cc92993c7fd422">llvm::ConstantArray::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a28bf8984fbfb08fd27df435e631e6832">llvm::ConstantExpr::getPointerBitCastOrAddrSpaceCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a> and <a href="#a784adc2347b72f745ff1239aef3a3c26">finalize</a>.</p>

</div>
</div>

### emitUserDefinedMapper() {#aad01bd2643d37f64f9d9a2933b8ddfc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * OpenMPIRBuilder::emitUserDefinedMapper (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty">MapInfosTy</a> &amp;(<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP, <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> *PtrPHI, <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> *BeginArg)&gt; PrivAndGenMapInfoCB, <a href="/web-llvm/docs/api/classes/llvm/type">llvm::Type</a> * ElemTy, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncName, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(unsigned int, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> **)&gt; CustomMapperCB=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the user-defined mapper function.</p>


<p>The code generation follows the pattern in the example below.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> .omp_mapper.&lt;type_name&gt;.&lt;mapper_id&gt;.(void *rt_mapper_handle,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> *base, </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> *<a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a2798f80ce7d64ebc7049d1231e675137">begin</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                                          int64_t <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, int64_t type,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Allocate space for an array section first or add a base/begin for</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// pointer dereference.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> &gt; 1 || (base != begin &amp;&amp; maptype.IsPtrAndObj)) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      !maptype.IsDelete)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    __tgt_push_mapper_component(rt_mapper_handle, base, begin,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                                <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>*</span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(Ty), clearToFromMember(type));</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Map members.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> i = 0; i &lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>; i++) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// For each component specified by this mapper:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> c : begin[i]-&gt;all_components) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c.hasMapper())</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        (*c.Mapper())(rt_mapper_handle, c.arg_base, c.arg_begin,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        c.arg_size,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                      c.arg_type, c.arg_name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        __tgt_push_mapper_component(rt_mapper_handle, c.arg_base,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                                    c.arg_begin, c.arg_size, c.arg_type,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                                    c.arg_name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Delete the array section.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> &gt; 1 &amp;&amp; maptype.IsDelete)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    __tgt_push_mapper_component(rt_mapper_handle, base, begin,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                                <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>*</span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(Ty), clearToFromMember(type));</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">PrivAndGenMapInfoCB</td>
<td class="doxyParamItemDescription"><p>Callback that privatizes code and populates the MapInfos and returns.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ElemTy</td>
<td class="doxyParamItemDescription"><p>DeclareMapper element type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FuncName</td>
<td class="doxyParamItemDescription"><p>Optional param to specify mapper function name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CustomMapperCB</td>
<td class="doxyParamItemDescription"><p>Optional callback to generate code related to custom mappers.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 2951 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 7943 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a01875e4204852069dd4b7938cab4140b">llvm::Function::addFnAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aa5087b607af833220d9ebab0c88c83c1">llvm::Function::addParamAttr</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a05d7aedbbdc0fd24e8bc27edfe9c603f">llvm::Function::Create</a>, <a href="#a9199bb920d3966ef9c614a623c7af495">emitBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aecf2b6d6f052a378dd8f69fd1bb700b1">llvm::Function::getArg</a>, <a href="#ac86b562509588cbc00fbdc441c615bd3">getFlagMemberOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="#a034dc6253a2a36f78ac071a7c12d5c27">getOrCreateRuntimeFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### finalize() {#a784adc2347b72f745ff1239aef3a3c26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::finalize (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Fn=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finalize the underlying module, e.g., by outlining regions.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fn</td>
<td class="doxyParamItemDescription"><p>The function to be finalized. If not used, all functions are finalized.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 701 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a01875e4204852069dd4b7938cab4140b">llvm::Function::addFnAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a16413f1a88d8baca228d0a1b4cc0bfc6">llvm::SmallPtrSetImplBase::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="#a355507f9e59388e467dc9288e4f82c3d">Config</a>, <a href="#aebfa8e874069dcc7e02ea471d941d9ca">ConstantAllocaRaiseCandidates</a>, <a href="#acc290ce16055813d4ee68af4c8023a09">createOffloadEntriesAndInfoMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a3bb33831dbcaa836f630ed1dc986b5c2">emitUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a266367eb01c634406b32f816d2d9c6bf">llvm::BasicBlock::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a8dd327a937563afdb08250abc43820b0">llvm::BasicBlock::eraseFromParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a169f0c26ef46161741fdd120a806f853">llvm::Function::getEntryBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4c319db4fe05c27cfe55bd133a87414d">llvm::Function::getFnAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a8743c58384e11cb6228f6f871304ad35">llvm::Function::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#aba0055050d741f60b6e0523507a2c79f">llvm::Value::getNumUses</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#acdd05db170cbfee8a0fcbc047b8504e5">llvm::Function::getReturnType</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a57f1945911ca1e95d0f51d7c3516b529">llvm::BasicBlock::getUniqueSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ae8eaa0b4eeac52a2b2282cb1bfd981ae">llvm::Type::isVoidTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="#aed2a8b469e9884788eef400fbc892dd3">OffloadInfoManager</a>, <a href="#a79e8ec8cdc9299c9bab67b625e6578c5">OutlineInfos</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a6e4c46869d9d198562f7b8628814e407">raiseUserConstantDataAllocasToEntryBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a1c2af7a9e501d399f06ca7e10eef46e4">llvm::BasicBlock::rbegin</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a29e0a562beb4b5d20eb0c426b363ceed">llvm::Function::removeFromParent</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a9237251072bf6816163abc2d053212ee">llvm::BasicBlock::rend</a>.</p>

</div>
</div>

### getAddrOfDeclareTargetVar() {#afdc1b8675a946ce055c64607ba75af3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * OpenMPIRBuilder::getAddrOfDeclareTargetVar (<a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#ab9575c71365de4083a7be6ef6572d534">OffloadEntriesInfoManager::OMPTargetGlobalVarEntryKind</a> CaptureClause, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#a2dc9d099b77ee3b8db3b00ad9273823d">OffloadEntriesInfoManager::OMPTargetDeviceClauseKind</a> DeviceClause, bool IsDeclaration, bool IsExternallyVisible, <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a> EntryInfo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> MangledName, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt; &amp; GeneratedRefs, bool OpenMPSIMD, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &gt; TargetTriple, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * LlvmPtrTy, std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *()&gt; GlobalInitializer, std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a>()&gt; VariableLinkage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieve (or create if non-existent) the address of a declare target variable, used in conjunction with registerTargetGlobalVariable to create declare target global variables.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CaptureClause</td>
<td class="doxyParamItemDescription"><p>- enumerator corresponding to the OpenMP capture clause used in conjunction with the variable being registered (link, to, enter).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DeviceClause</td>
<td class="doxyParamItemDescription"><p>- enumerator corresponding to the OpenMP capture clause used in conjunction with the variable being registered (nohost, host, any)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsDeclaration</td>
<td class="doxyParamItemDescription"><p>- boolean stating if the variable being registered is a declaration-only and not a definition</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsExternallyVisible</td>
<td class="doxyParamItemDescription"><p>- boolean stating if the variable is externally visible</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryInfo</td>
<td class="doxyParamItemDescription"><p>- Unique entry information for the value generated using getTargetEntryUniqueInfo, used to name generated pointer references to the declare target variable</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MangledName</td>
<td class="doxyParamItemDescription"><p>- the mangled name of the variable being registered</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GeneratedRefs</td>
<td class="doxyParamItemDescription"><p>- references generated by invocations of registerTargetGlobalVariable invoked from getAddrOfDeclareTargetVar, these are required by Clang for book keeping.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OpenMPSIMD</td>
<td class="doxyParamItemDescription"><p>- if OpenMP SIMD mode is currently enabled</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TargetTriple</td>
<td class="doxyParamItemDescription"><p>- The OpenMP device target triple we are compiling for</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LlvmPtrTy</td>
<td class="doxyParamItemDescription"><p>- The type of the variable we are generating or retrieving an address for</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GlobalInitializer</td>
<td class="doxyParamItemDescription"><p>- a lambda function which creates a constant used for initializing a pointer reference to the variable in certain cases. If a nullptr is passed, it will default to utilising the original variable to initialize the pointer reference.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VariableLinkage</td>
<td class="doxyParamItemDescription"><p>- a lambda function which returns the variables linkage type, if unspecified and a nullptr is given, it will instead utilise the linkage stored on the existing global variable in the LLVMModule.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 887 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9475 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a355507f9e59388e467dc9288e4f82c3d">Config</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo/#a80293a526ecd17ee44ce5b982dff1ca1">llvm::TargetRegionEntryInfo::FileID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#aa5ef00e5a7487cc6c5bfed0f301fa1cc">getOrCreateInternalVariable</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#ab9575c71365de4083a7be6ef6572d534a1b9b415348a31bfeaa94e778e0421ddf">llvm::OffloadEntriesInfoManager::OMPTargetGlobalVarEntryEnter</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#ab9575c71365de4083a7be6ef6572d534abe3a7916fb5f7a79d6aea6c0356e71a6">llvm::OffloadEntriesInfoManager::OMPTargetGlobalVarEntryLink</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#ab9575c71365de4083a7be6ef6572d534acf96797e65a60ff4302eb2bbdbbd8880">llvm::OffloadEntriesInfoManager::OMPTargetGlobalVarEntryTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="#ae327be8503a76bd4dccfff4713a38553">registerTargetGlobalVariable</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca8d13a9bcecfac72febceb1103afa048f">llvm::GlobalValue::WeakAnyLinkage</a>.</p>


<p>Referenced by <a href="#ae327be8503a76bd4dccfff4713a38553">registerTargetGlobalVariable</a>.</p>

</div>
</div>

### getFlagMemberOffset() {#ac86b562509588cbc00fbdc441c615bd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned OpenMPIRBuilder::getFlagMemberOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the offset of the OMP_MAP_MEMBER_OF field.</p>

<p>Declaration at line 943 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9439 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a02d7a52c47f2d71a111aef9d4fb70ecbaa450a4e59275b4081714a7a28f217e6c">llvm::omp::OMP_MAP_MEMBER_OF</a>.</p>


<p>Referenced by <a href="#aad01bd2643d37f64f9d9a2933b8ddfc2">emitUserDefinedMapper</a> and <a href="#a4f82182a8cc23f854efdbd453f685086">getMemberOfFlag</a>.</p>

</div>
</div>

### getInsertionPoint() {#aa26124809eff11c5f244027439751c50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InsertPointTy llvm::OpenMPIRBuilder::getInsertionPoint ()</td>
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

<p>}</p>


<p>Return the insertion point used by the underlying <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>.</p>


<p>Definition at line 1969 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Reference <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>.</p>

</div>
</div>

### getMemberOfFlag() {#a4f82182a8cc23f854efdbd453f685086}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">omp::OpenMPOffloadMappingFlags OpenMPIRBuilder::getMemberOfFlag (unsigned Position)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get OMP_MAP_MEMBER_OF flag with extra bits reserved based on the position given.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Position</td>
<td class="doxyParamItemDescription"><p>- A value indicating the position of the parent of the member in the kernel argument structure, often retrieved by the parents position in the combined information vectors used to generate the structure itself. Multiple children (member's of) with the same parent will use the same returned member flag.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 952 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9450 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>Reference <a href="#ac86b562509588cbc00fbdc441c615bd3">getFlagMemberOffset</a>.</p>

</div>
</div>

### getOrCreateDefaultSrcLocStr() {#ac35a35b620a34821da2801ebf452a9a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * OpenMPIRBuilder::getOrCreateDefaultSrcLocStr (uint32_t &amp; SrcLocStrSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the (LLVM-IR) string describing the default source location.</p>

<p>Declaration at line 1988 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 972 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>.</p>


<p>Referenced by <a href="#a9b8c05f635a1b8e5a66eeec4704bf291">getOrCreateSrcLocStr</a>.</p>

</div>
</div>

### getOrCreateIdent() {#a02cae9681b22a06e7738a4c1f3de233e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * OpenMPIRBuilder::getOrCreateIdent (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * SrcLocStr, uint32_t SrcLocStrSize, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a0e821d8251c97d66ca185efe2f8ffde2">omp::IdentFlag</a> Flags=<a href="/web-llvm/docs/api/namespaces/llvm/omp/#a0e821d8251c97d66ca185efe2f8ffde2">omp::IdentFlag</a>(0), unsigned Reserve2Flags=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an ident_t* encoding the source location <span class="doxyComputerOutput">SrcLocStr</span> and <span class="doxyComputerOutput">Flags</span>.</p>


<p>TODO: Create a enum class for the Reserve2Flags</p>


<p>Declaration at line 2007 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 892 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantstruct/#a54fcfa620deb80373f489ba2fdad7643">llvm::ConstantStruct::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a28bf8984fbfb08fd27df435e631e6832">llvm::ConstantExpr::getPointerBitCastOrAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ae8df4be75bfc50b1eadd74e85c25fa45a4cc6684df7b4a92b1dec6fce3264fac8">llvm::GlobalValue::Global</a>, <a href="#a801d4c8626e9914c0bc6b756c64c0730">IdentMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a788a72ddbf1bd572b3fcd7a5e7ec8cff">Int32</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">llvm::GlobalValue::NotThreadLocal</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca04ed141708c0fd16723d212502b046ae">llvm::GlobalValue::PrivateLinkage</a>.</p>


<p>Referenced by <a href="#abca6530c9099bd1b1c3e0a5c32381f07">createBarrier</a>, <a href="#ad89dcb3cd8a39ae57a69487c2988dace">createCachedThreadPrivate</a>, <a href="#a04285415a321e48322c08f3b9185540e">createCancel</a>, <a href="#af2808c704c935cee35e9529907b59b1c">createCopyPrivate</a>, <a href="#ac379895c55a89804f49f1a775828c235">createCritical</a>, <a href="#adf9f105d93a1a09d5307dc14e77293f1">createMasked</a>, <a href="#a970cc920a6bae8d641ac63fb33afb40b">createMaster</a>, <a href="#a81bc7a57bd0332843aed6275ba47bee0">createOMPAlloc</a>, <a href="#a807c913d5889a80440269b74d5755d6c">createOMPFree</a>, <a href="#a38345e93229faed92e719f1793807bb1">createOMPInteropDestroy</a>, <a href="#a7709370a0f6564aa772ce20caa45337e">createOMPInteropInit</a>, <a href="#aaef3fb3339c2ade5ffffccdd177e465c">createOMPInteropUse</a>, <a href="#a6e2bd6420d3d12339e32d4d1b3ba1394">createOrderedDepend</a>, <a href="#a012d736828ba67916f7e5a3e9ff1d68f">createOrderedThreadsSimd</a>, <a href="#a4f81b9940e1869e146636dc533455929">createParallel</a>, <a href="#ab0996924f219129d8de3cc1b8830f768">createReductions</a>, <a href="#aaa655ca8bca40c564d0b7c81ebaf8ff9">createReductionsGPU</a>, <a href="#a3e1a0b27abb4d57e2293c46802eee89d">createSingle</a>, <a href="#ae54a581ccf494afe52ae45af317bbd58">createTargetData</a>, <a href="#a7db9daa323dee69eb9ecc380ce6edae8">createTargetInit</a>, <a href="#a0af3c7a02c1325c04c59f857604bd4f3">createTask</a>, <a href="#a1f8b732c2f951d56302d4431f00f16bd">createTaskgroup</a>, <a href="#a3f603d822817256077c95e6573f2b14a">createTeams</a>, <a href="#a2a4b97bb7670d306c756cdbd5ee9b560">emitFlush</a>, <a href="#a2841680b34ec9c2c7185a877f8f8b4c8">emitTargetTask</a>, <a href="#a177df2c9d7d8692ed214018f420c3de6">emitTaskwaitImpl</a> and <a href="#a6383328cfcdbbd56502b92f9e2415432">emitTaskyieldImpl</a>.</p>

</div>
</div>

### getOrCreateInternalVariable() {#aa5ef00e5a7487cc6c5bfed0f301fa1cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * OpenMPIRBuilder::getOrCreateInternalVariable (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Name, unsigned AddressSpace=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets (if variable with the given name already exist) or creates internal global variable with the specified Name.</p>


<p>The created variable has linkage CommonLinkage by default and is initialized by null value.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of the global variable. If it is exist already the type must be the same.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Name of the variable.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 3410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 7642 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca08c6a63ca3d9cdb39fb584655bf5c501">llvm::GlobalValue::CommonLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="#aa58c09ca23b31b6bebfa825111dc3923">InternalVars</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">llvm::GlobalValue::NotThreadLocal</a>.</p>


<p>Referenced by <a href="#ad89dcb3cd8a39ae57a69487c2988dace">createCachedThreadPrivate</a>, <a href="#afdc1b8675a946ce055c64607ba75af3a">getAddrOfDeclareTargetVar</a> and <a href="#ae327be8503a76bd4dccfff4713a38553">registerTargetGlobalVariable</a>.</p>

</div>
</div>

### getOrCreateRuntimeFunction() {#a034dc6253a2a36f78ac071a7c12d5c27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee OpenMPIRBuilder::getOrCreateRuntimeFunction (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a4c503140c7f851151906d85b515330e9">omp::RuntimeFunction</a> FnID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the function declaration for the runtime function with <span class="doxyComputerOutput">FnID</span>.</p>

<p>Declaration at line 1979 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 613 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#a50c6490cf353f064946c4e32673ac098">addAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#aa1b0638c63ba711320b3bb9c69367ed6">llvm::GlobalObject::addMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a1d51e11adfffd05afe252d3398f50d4e">llvm::MDBuilder::createCallbackEncoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a21075305f0e463b24aafc2fb99514ace">llvm::Function::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a1f496e54accb2cbe919fb456cb703f1a">llvm::GlobalObject::hasMetadata</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>.</p>


<p>Referenced by <a href="#ae2d016504f27bd96960ace8645073d63">createDispatchDeinitFunction</a>, <a href="#a5946a2c7130bcf42add273f83cb6e257">createDispatchFiniFunction</a>, <a href="#aac7493b7e13af08014a1c49dcdecbf20">createDispatchInitFunction</a>, <a href="#a49dbf0af8f3e1314b3b60222651b6fc2">createDispatchNextFunction</a>, <a href="#a8191e2fd322236b59afb070919f0d6af">createForStaticInitFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#acae95016bcdeb105bcbcaaa872893f5f">createTargetLoopWorkshareCall</a>, <a href="#ad48c785749c7160070b39be42c67d2b7">emitTargetKernel</a>, <a href="#aad01bd2643d37f64f9d9a2933b8ddfc2">emitUserDefinedMapper</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3d17252beff7921e40622170990c89ab">getKmpcForDynamicFiniForType</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a7a68322ba864bccb8736e42fbc915a8a">getKmpcForDynamicInitForType</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a74bf2240e1da04168d57a7534c9613f7">getKmpcForDynamicNextForType</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#ac04904b32ea7f45e108b8752b1a940e7">getKmpcForStaticInitForType</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#aca27639a720491c7c7ea13c2bbe8c162">getKmpcForStaticLoopForType</a> and <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>.</p>

</div>
</div>

### getOrCreateRuntimeFunctionPtr() {#a7a0ce50dfb1a164ee67119899992c75b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * OpenMPIRBuilder::getOrCreateRuntimeFunctionPtr (<a href="/web-llvm/docs/api/namespaces/llvm/omp/#a4c503140c7f851151906d85b515330e9">omp::RuntimeFunction</a> FnID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1982 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 669 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncallee/#ac5d8da677233fa2e1e7039508ed56e0e">llvm::FunctionCallee::getCallee</a>, <a href="#a034dc6253a2a36f78ac071a7c12d5c27">getOrCreateRuntimeFunction</a> and <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>.</p>


<p>Referenced by <a href="#abca6530c9099bd1b1c3e0a5c32381f07">createBarrier</a>, <a href="#ad89dcb3cd8a39ae57a69487c2988dace">createCachedThreadPrivate</a>, <a href="#a04285415a321e48322c08f3b9185540e">createCancel</a>, <a href="#af2808c704c935cee35e9529907b59b1c">createCopyPrivate</a>, <a href="#ac379895c55a89804f49f1a775828c235">createCritical</a>, <a href="#adf9f105d93a1a09d5307dc14e77293f1">createMasked</a>, <a href="#a970cc920a6bae8d641ac63fb33afb40b">createMaster</a>, <a href="#a81bc7a57bd0332843aed6275ba47bee0">createOMPAlloc</a>, <a href="#a807c913d5889a80440269b74d5755d6c">createOMPFree</a>, <a href="#a38345e93229faed92e719f1793807bb1">createOMPInteropDestroy</a>, <a href="#a7709370a0f6564aa772ce20caa45337e">createOMPInteropInit</a>, <a href="#aaef3fb3339c2ade5ffffccdd177e465c">createOMPInteropUse</a>, <a href="#a6e2bd6420d3d12339e32d4d1b3ba1394">createOrderedDepend</a>, <a href="#a012d736828ba67916f7e5a3e9ff1d68f">createOrderedThreadsSimd</a>, <a href="#a4f81b9940e1869e146636dc533455929">createParallel</a>, <a href="#ab0996924f219129d8de3cc1b8830f768">createReductions</a>, <a href="#aaa655ca8bca40c564d0b7c81ebaf8ff9">createReductionsGPU</a>, <a href="#a3e1a0b27abb4d57e2293c46802eee89d">createSingle</a>, <a href="#ae54a581ccf494afe52ae45af317bbd58">createTargetData</a>, <a href="#a1e1e2695745252cae26a9843b4d8daa3">createTargetDeinit</a>, <a href="#a7db9daa323dee69eb9ecc380ce6edae8">createTargetInit</a>, <a href="#a0af3c7a02c1325c04c59f857604bd4f3">createTask</a>, <a href="#a1f8b732c2f951d56302d4431f00f16bd">createTaskgroup</a>, <a href="#a3f603d822817256077c95e6573f2b14a">createTeams</a>, <a href="#a2a4b97bb7670d306c756cdbd5ee9b560">emitFlush</a>, <a href="#a2841680b34ec9c2c7185a877f8f8b4c8">emitTargetTask</a>, <a href="#a177df2c9d7d8692ed214018f420c3de6">emitTaskwaitImpl</a>, <a href="#a6383328cfcdbbd56502b92f9e2415432">emitTaskyieldImpl</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#afffa0ff2e1527ab545cef33be915c656">hostParallelCallback</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af7668ce8080668a4f0ceac24e70c9f00">targetParallelCallback</a>.</p>

</div>
</div>

### getOrCreateSrcLocStr() {#a55a39962245dd2e0938194dd3b4438e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * OpenMPIRBuilder::getOrCreateSrcLocStr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LocStr, uint32_t &amp; SrcLocStrSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the (LLVM-IR) string describing the source location <span class="doxyComputerOutput">LocStr</span>.</p>

<p>Declaration at line 1985 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 932 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a1f469b1f703519ae25ce564c8704310f">llvm::ConstantExpr::getPointerCast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a3edef3fa47c611d3d10606591213e57b">llvm::ConstantDataArray::getString</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="#a539b79b038631cce06319250c09f8cfd">SrcLocStrMap</a>.</p>


<p>Referenced by <a href="#abca6530c9099bd1b1c3e0a5c32381f07">createBarrier</a>, <a href="#ad89dcb3cd8a39ae57a69487c2988dace">createCachedThreadPrivate</a>, <a href="#a04285415a321e48322c08f3b9185540e">createCancel</a>, <a href="#af2808c704c935cee35e9529907b59b1c">createCopyPrivate</a>, <a href="#ac379895c55a89804f49f1a775828c235">createCritical</a>, <a href="#adf9f105d93a1a09d5307dc14e77293f1">createMasked</a>, <a href="#a970cc920a6bae8d641ac63fb33afb40b">createMaster</a>, <a href="#a81bc7a57bd0332843aed6275ba47bee0">createOMPAlloc</a>, <a href="#a807c913d5889a80440269b74d5755d6c">createOMPFree</a>, <a href="#a38345e93229faed92e719f1793807bb1">createOMPInteropDestroy</a>, <a href="#a7709370a0f6564aa772ce20caa45337e">createOMPInteropInit</a>, <a href="#aaef3fb3339c2ade5ffffccdd177e465c">createOMPInteropUse</a>, <a href="#a6e2bd6420d3d12339e32d4d1b3ba1394">createOrderedDepend</a>, <a href="#a012d736828ba67916f7e5a3e9ff1d68f">createOrderedThreadsSimd</a>, <a href="#a4f81b9940e1869e146636dc533455929">createParallel</a>, <a href="#ab0996924f219129d8de3cc1b8830f768">createReductions</a>, <a href="#aaa655ca8bca40c564d0b7c81ebaf8ff9">createReductionsGPU</a>, <a href="#a3e1a0b27abb4d57e2293c46802eee89d">createSingle</a>, <a href="#ae54a581ccf494afe52ae45af317bbd58">createTargetData</a>, <a href="#a7db9daa323dee69eb9ecc380ce6edae8">createTargetInit</a>, <a href="#a0af3c7a02c1325c04c59f857604bd4f3">createTask</a>, <a href="#a1f8b732c2f951d56302d4431f00f16bd">createTaskgroup</a>, <a href="#a3f603d822817256077c95e6573f2b14a">createTeams</a>, <a href="#a2a4b97bb7670d306c756cdbd5ee9b560">emitFlush</a>, <a href="#a2841680b34ec9c2c7185a877f8f8b4c8">emitTargetTask</a>, <a href="#a177df2c9d7d8692ed214018f420c3de6">emitTaskwaitImpl</a>, <a href="#a6383328cfcdbbd56502b92f9e2415432">emitTaskyieldImpl</a>, <a href="#ac35a35b620a34821da2801ebf452a9a0">getOrCreateDefaultSrcLocStr</a>, <a href="#a4950d59a5a139f25fa75e82a948537fc">getOrCreateSrcLocStr</a>, <a href="#a9b8c05f635a1b8e5a66eeec4704bf291">getOrCreateSrcLocStr</a> and <a href="#a061144e3e490f8917de9c53163ef8c01">getOrCreateSrcLocStr</a>.</p>

</div>
</div>

### getOrCreateSrcLocStr() {#a061144e3e490f8917de9c53163ef8c01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * OpenMPIRBuilder::getOrCreateSrcLocStr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FunctionName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName, unsigned Line, unsigned Column, uint32_t &amp; SrcLocStrSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the (LLVM-IR) string describing the source location identified by the arguments.</p>

<p>Declaration at line 1992 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 953 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ac22cf1a1c08b7ccaefc51508536312a4">llvm::SmallString&lt; InternalLen &gt;::append</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallstring/#af5dd7241878be5eed07736eb156bb10b">llvm::SmallString&lt; InternalLen &gt;::str</a>.</p>

</div>
</div>

### getOrCreateSrcLocStr() {#a9b8c05f635a1b8e5a66eeec4704bf291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * OpenMPIRBuilder::getOrCreateSrcLocStr (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, uint32_t &amp; SrcLocStrSize, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the (LLVM-IR) string describing the <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> <span class="doxyComputerOutput">DL</span>.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <span class="doxyComputerOutput">F</span> as fallback if <span class="doxyComputerOutput">DL</span> does not specify the function name.</p>


<p>Declaration at line 1998 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 977 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a1d8eb3054fd49a89ff41bc22a48f87e7">llvm::Function::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ac35a35b620a34821da2801ebf452a9a0">getOrCreateDefaultSrcLocStr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a> and <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>.</p>

</div>
</div>

### getOrCreateSrcLocStr() {#a4950d59a5a139f25fa75e82a948537fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * OpenMPIRBuilder::getOrCreateSrcLocStr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, uint32_t &amp; SrcLocStrSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the (LLVM-IR) string describing the source location <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span>.</p>

<p>Declaration at line 2002 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 994 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>.</p>

</div>
</div>

### getOrCreateThreadID() {#a9607f501333d84917dc48f5d263e9b6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * OpenMPIRBuilder::getOrCreateThreadID (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ident)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the current thread <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ident</td>
<td class="doxyParamItemDescription"><p>The ident (ident_t*) describing the query origin.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 2081 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 1000 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a> and <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>.</p>


<p>Referenced by <a href="#abca6530c9099bd1b1c3e0a5c32381f07">createBarrier</a>, <a href="#ad89dcb3cd8a39ae57a69487c2988dace">createCachedThreadPrivate</a>, <a href="#a04285415a321e48322c08f3b9185540e">createCancel</a>, <a href="#af2808c704c935cee35e9529907b59b1c">createCopyPrivate</a>, <a href="#ac379895c55a89804f49f1a775828c235">createCritical</a>, <a href="#adf9f105d93a1a09d5307dc14e77293f1">createMasked</a>, <a href="#a970cc920a6bae8d641ac63fb33afb40b">createMaster</a>, <a href="#a81bc7a57bd0332843aed6275ba47bee0">createOMPAlloc</a>, <a href="#a807c913d5889a80440269b74d5755d6c">createOMPFree</a>, <a href="#a38345e93229faed92e719f1793807bb1">createOMPInteropDestroy</a>, <a href="#a7709370a0f6564aa772ce20caa45337e">createOMPInteropInit</a>, <a href="#aaef3fb3339c2ade5ffffccdd177e465c">createOMPInteropUse</a>, <a href="#a6e2bd6420d3d12339e32d4d1b3ba1394">createOrderedDepend</a>, <a href="#a012d736828ba67916f7e5a3e9ff1d68f">createOrderedThreadsSimd</a>, <a href="#a4f81b9940e1869e146636dc533455929">createParallel</a>, <a href="#ab0996924f219129d8de3cc1b8830f768">createReductions</a>, <a href="#a3e1a0b27abb4d57e2293c46802eee89d">createSingle</a>, <a href="#a0af3c7a02c1325c04c59f857604bd4f3">createTask</a>, <a href="#a1f8b732c2f951d56302d4431f00f16bd">createTaskgroup</a>, <a href="#a3f603d822817256077c95e6573f2b14a">createTeams</a>, <a href="#a2841680b34ec9c2c7185a877f8f8b4c8">emitTargetTask</a>, <a href="#a177df2c9d7d8692ed214018f420c3de6">emitTaskwaitImpl</a> and <a href="#a6383328cfcdbbd56502b92f9e2415432">emitTaskyieldImpl</a>.</p>

</div>
</div>

### getSizeInBytes() {#ae19488d3493945579ed3987ce14c6ff2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * OpenMPIRBuilder::getSizeInBytes (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * BasePtr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Computes the size of type in bytes.</p>

<p>Declaration at line 2144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 7676 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260abbb93ef26e3c101ff11cdd21cab08a94">llvm::Null</a>.</p>

</div>
</div>

### initialize() {#a1af99f6f33b0db83a3e941fcb819fa29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::initialize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize the internal state, this will put structures types and potentially other helpers into the underlying module.</p>


<p>Must be called before any other method and only once! This internal state includes types used in the <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder">OpenMPIRBuilder</a> generated from OMPKinds.def.</p>


<p>Declaration at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 676 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>.</p>

</div>
</div>

### isLastFinalizationInfoCancellable() {#ad44e60b9d264f6ceb54e6cd660e859fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OpenMPIRBuilder::isLastFinalizationInfoCancellable (omp::Directive DK)</td>
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

<p>Return true if the last entry in the finalization stack is of kind <span class="doxyComputerOutput">DK</span> and cancellable.</p>

<p>Definition at line 2062 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Reference <a href="#a75f3209cae3f3f2700c6bc6e9623f841">FinalizationStack</a>.</p>


<p>Referenced by <a href="#abca6530c9099bd1b1c3e0a5c32381f07">createBarrier</a> and <a href="#a98b55a0d95b3926151545101e4f2aef9">emitCancelationCheckImpl</a>.</p>

</div>
</div>

### loadOffloadInfoMetadata() {#a2242b144e54fa6203dae5c5b27fff17c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::loadOffloadInfoMetadata (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Loads all the offload entries information from the host IR metadata.</p>


<p>This function is only meant to be used with device code generation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">M</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> to load <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> info from. <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> passed maybe loaded from bitcode file, i.e, different from <a href="#a535304630869bfe0b7c0a81bb3c44497">OpenMPIRBuilder::M</a> module.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 3393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9612 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="#aed2a8b469e9884788eef400fbc892dd3">OffloadInfoManager</a>, <a href="#aefadc356da16598ff8c210dafbf4a2b7">ompOffloadInfoName</a> and <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#adc55e223d70c06a924fd5cb248052d9d">llvm::NamedMDNode::operands</a>.</p>


<p>Referenced by <a href="#ac6293b7ea84a4deac85481dd10dad437">loadOffloadInfoMetadata</a>.</p>

</div>
</div>

### loadOffloadInfoMetadata() {#ac6293b7ea84a4deac85481dd10dad437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::loadOffloadInfoMetadata (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> HostFilePath)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Loads all the offload entries information from the host IR metadata read from the file passed in as the HostFilePath argument.</p>


<p>This function is only meant to be used with device code generation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">HostFilePath</td>
<td class="doxyParamItemDescription"><p>The path to the host IR file, used to load in offload metadata for the device, allowing host and device to maintain the same metadata mapping.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 3402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9658 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4891d521956b735baba56d4dc193f5cd">llvm::expectedToErrorOrAndEmitErrors</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa98611beefe78f907beeee7305cc8174">llvm::MemoryBuffer::getFile</a>, <a href="#a2242b144e54fa6203dae5c5b27fff17c">loadOffloadInfoMetadata</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a170525c5f5e06bd2555d40a0499b8b6d">llvm::parseBitcodeFile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### popFinalizationCB() {#af2e7210874149ecbd52c8ce44ca4f416}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::OpenMPIRBuilder::popFinalizationCB ()</td>
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

<p>Pop the last finalization callback from the finalization stack.</p>


<p>NOTE: Temporary solution until Clang CG is gone.</p>


<p>Definition at line 568 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Reference <a href="#a75f3209cae3f3f2700c6bc6e9623f841">FinalizationStack</a>.</p>

</div>
</div>

### pushFinalizationCB() {#a977f2477d245a9d554642492fedd049a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::OpenMPIRBuilder::pushFinalizationCB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/finalizationinfo">FinalizationInfo</a> &amp; FI)</td>
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

<p>Push a finalization callback on the finalization stack.</p>


<p>NOTE: Temporary solution until Clang CG is gone.</p>


<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Reference <a href="#a75f3209cae3f3f2700c6bc6e9623f841">FinalizationStack</a>.</p>

</div>
</div>

### registerTargetGlobalVariable() {#ae327be8503a76bd4dccfff4713a38553}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::registerTargetGlobalVariable (<a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#ab9575c71365de4083a7be6ef6572d534">OffloadEntriesInfoManager::OMPTargetGlobalVarEntryKind</a> CaptureClause, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#a2dc9d099b77ee3b8db3b00ad9273823d">OffloadEntriesInfoManager::OMPTargetDeviceClauseKind</a> DeviceClause, bool IsDeclaration, bool IsExternallyVisible, <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a> EntryInfo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> MangledName, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt; &amp; GeneratedRefs, bool OpenMPSIMD, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &gt; TargetTriple, std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *()&gt; GlobalInitializer, std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a>()&gt; VariableLinkage, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * LlvmPtrTy, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Registers a target variable for device or host.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CaptureClause</td>
<td class="doxyParamItemDescription"><p>- enumerator corresponding to the OpenMP capture clause used in conjunction with the variable being registered (link, to, enter).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DeviceClause</td>
<td class="doxyParamItemDescription"><p>- enumerator corresponding to the OpenMP capture clause used in conjunction with the variable being registered (nohost, host, any)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsDeclaration</td>
<td class="doxyParamItemDescription"><p>- boolean stating if the variable being registered is a declaration-only and not a definition</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsExternallyVisible</td>
<td class="doxyParamItemDescription"><p>- boolean stating if the variable is externally visible</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryInfo</td>
<td class="doxyParamItemDescription"><p>- Unique entry information for the value generated using getTargetEntryUniqueInfo, used to name generated pointer references to the declare target variable</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MangledName</td>
<td class="doxyParamItemDescription"><p>- the mangled name of the variable being registered</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GeneratedRefs</td>
<td class="doxyParamItemDescription"><p>- references generated by invocations of registerTargetGlobalVariable these are required by Clang for book keeping.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OpenMPSIMD</td>
<td class="doxyParamItemDescription"><p>- if OpenMP SIMD mode is currently enabled</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TargetTriple</td>
<td class="doxyParamItemDescription"><p>- The OpenMP device target triple we are compiling for</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GlobalInitializer</td>
<td class="doxyParamItemDescription"><p>- a lambda function which creates a constant used for initializing a pointer reference to the variable in certain cases. If a nullptr is passed, it will default to utilising the original variable to initialize the pointer reference.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VariableLinkage</td>
<td class="doxyParamItemDescription"><p>- a lambda function which returns the variables linkage type, if unspecified and a nullptr is given, it will instead utilise the linkage stored on the existing global variable in the LLVMModule.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LlvmPtrTy</td>
<td class="doxyParamItemDescription"><p>- The type of the variable we are generating or retrieving an address for</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Addr</td>
<td class="doxyParamItemDescription"><p>- the original llvm value (addr) of the variable to be registered</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 931 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9531 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a355507f9e59388e467dc9288e4f82c3d">Config</a>, <a href="#a488c861f8a68e5f78ceca8b57acd8be5">createPlatformSpecificName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9dda4472ee0b7ea92ab49eedf6e13d50">llvm::divideCeil</a>, <a href="#afdc1b8675a946ce055c64607ba75af3a">getAddrOfDeclareTargetVar</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3547d58a060ee2e4a29cbea85bef91af">llvm::GlobalValue::getLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="#aa5ef00e5a7487cc6c5bfed0f301fa1cc">getOrCreateInternalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caf2b592edf18170e7aff4e8f3bae3360c">llvm::GlobalValue::LinkOnceODRLinkage</a>, <a href="#a535304630869bfe0b7c0a81bb3c44497">M</a>, <a href="#aed2a8b469e9884788eef400fbc892dd3">OffloadInfoManager</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#a2dc9d099b77ee3b8db3b00ad9273823da168f6569c38da7979aa5e36d0a21b871">llvm::OffloadEntriesInfoManager::OMPTargetDeviceClauseAny</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#ab9575c71365de4083a7be6ef6572d534a1b9b415348a31bfeaa94e778e0421ddf">llvm::OffloadEntriesInfoManager::OMPTargetGlobalVarEntryEnter</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#ab9575c71365de4083a7be6ef6572d534abe3a7916fb5f7a79d6aea6c0356e71a6">llvm::OffloadEntriesInfoManager::OMPTargetGlobalVarEntryLink</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#ab9575c71365de4083a7be6ef6572d534acf96797e65a60ff4302eb2bbdbbd8880">llvm::OffloadEntriesInfoManager::OMPTargetGlobalVarEntryTo</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca8d13a9bcecfac72febceb1103afa048f">llvm::GlobalValue::WeakAnyLinkage</a>.</p>


<p>Referenced by <a href="#afdc1b8675a946ce055c64607ba75af3a">getAddrOfDeclareTargetVar</a>.</p>

</div>
</div>

### registerTargetRegionFunction() {#a17c7f65c3ce26b3b0de6774c0d3c723f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * OpenMPIRBuilder::registerTargetRegionFunction (<a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a> &amp; EntryInfo, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * OutlinedFunction, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> EntryFnName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> EntryFnIDName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Registers the given function and sets up the attribtues of the function Returns the FunctionID.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">InfoManager</td>
<td class="doxyParamItemDescription"><p>The info manager keeping track of the offload entries</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryInfo</td>
<td class="doxyParamItemDescription"><p>The entry information about the function</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OutlinedFunction</td>
<td class="doxyParamItemDescription"><p>Pointer to the outlined function</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryFnName</td>
<td class="doxyParamItemDescription"><p>Name of the outlined function</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryFnIDName</td>
<td class="doxyParamItemDescription"><p>Name of the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> o be created</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 2873 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6533 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#aed2a8b469e9884788eef400fbc892dd3">OffloadInfoManager</a> and <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#a4e85049eada7d6cc3bedde1433ce4a7ba1e2537a111117d2cebad779b6de1856b">llvm::OffloadEntriesInfoManager::OMPTargetRegionEntryTargetRegion</a>.</p>


<p>Referenced by <a href="#a567502d7244077ed45e0c9471d31ba4c">emitTargetRegionFunction</a>.</p>

</div>
</div>

### setConfig() {#a3cf3a832c89fb823f696ce21ecf37b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::OpenMPIRBuilder::setConfig (<a href="/web-llvm/docs/api/classes/llvm/openmpirbuilderconfig">OpenMPIRBuilderConfig</a> C)</td>
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



<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a355507f9e59388e467dc9288e4f82c3d">Config</a>.</p>

</div>
</div>

### setCorrectMemberOfFlag() {#abeea5a3df7d0266470cd04bb721db70e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::setCorrectMemberOfFlag (<a href="/web-llvm/docs/api/namespaces/llvm/omp/#a02d7a52c47f2d71a111aef9d4fb70ecb">omp::OpenMPOffloadMappingFlags</a> &amp; Flags, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a02d7a52c47f2d71a111aef9d4fb70ecb">omp::OpenMPOffloadMappingFlags</a> MemberOfFlag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an initial flag set, this function modifies it to contain the passed in MemberOfFlag generated from the getMemberOfFlag function.</p>


<p>The results are dependent on the existing flag bits set in the original flag set.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>- The original set of flags to be modified with the passed in MemberOfFlag.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MemberOfFlag</td>
<td class="doxyParamItemDescription"><p>- A modified OMP_MAP_MEMBER_OF flag, adjusted slightly based on the getMemberOfFlag which adjusts the flag bits based on the members position in its parent.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 963 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9456 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a02d7a52c47f2d71a111aef9d4fb70ecbaa450a4e59275b4081714a7a28f217e6c">llvm::omp::OMP_MAP_MEMBER_OF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a02d7a52c47f2d71a111aef9d4fb70ecba67bb5754d8a930a0abad5e820064be2d">llvm::omp::OMP_MAP_PTR_AND_OBJ</a>.</p>

</div>
</div>

### tileLoops() {#a76e12ec076e7af4be7b8b77a5d53d3fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; CanonicalLoopInfo * &gt; OpenMPIRBuilder::tileLoops (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * &gt; Loops, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; TileSizes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tile a loop nest.</p>


<p>Tiles the loops of <span class="doxyComputerOutput">Loops</span> by the tile sizes in <span class="doxyComputerOutput">TileSizes</span>. Loops in <span class="doxyComputerOutput"></span>/ Loops must be perfectly nested, from outermost to innermost loop (i.e. Loops.front() is the outermost loop). The trip count <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> of every loop and every tile sizes must be usable in the outermost loop's preheader. This implies that the loop nest is rectangular.</p>


<p>Example:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = 0; i &lt; 15; ++i) </span><span class="doxyHighlightComment">// Canonical loop "i"</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> j = 0; <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea363b122c528f54df4a0446b6bab05515">j</a> &lt; 14; ++<a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea363b122c528f54df4a0446b6bab05515">j</a>) </span><span class="doxyHighlightComment">// Canonical loop "j"</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      body(i, j);</span></span></div>

</div>


<p>After tiling with Loops={i,j} and TileSizes={5,7}, the loop is changed to</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i1 = 0; i1 &lt; 3; ++i1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> j1 = 0; j1 &lt; 2; ++j1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i2 = 0; i2 &lt; 5; ++i2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> j2 = 0; j2 &lt; 7; ++j2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        body(i1*3+i2, j1*3+j2);</span></span></div>

</div>


<p>The returned vector are the loops {i1,j1,i2,j2}. The loops i1 and j1 are referred to the floor, and the loops i2 and j2 are the tiles. Tiling also handles non-constant trip counts, non-constant tile sizes and trip counts that are not multiples of the tile size. In the latter case the tile loop of the last floor-loop iteration will have fewer iterations than specified as its tile size.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug location for instructions added by tiling, for instance the floor- and tile trip count computation.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Loops</td>
<td class="doxyParamItemDescription"><p>Loops to tile. The <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> objects are invalidated by this method, i.e. should not used after tiling.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TileSizes</td>
<td class="doxyParamItemDescription"><p>For each loop in <span class="doxyComputerOutput">Loops</span>, the tile size for that dimensions.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A list of generated loops. Contains twice as many loops as the input loop nest; the first half are the floor loops and the second half are the tile loops.</p></dd>
</dl>


<p>Declaration at line 1161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5015 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada72881d16e555ca8525a916364048f9a69820949e2fb6d1d719487d27f0df883">llvm::Continue</a>, <a href="#a445fa52d77040bccb16bfea111234a2e">createLoopSkeleton</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a92d8bce979891dc43b6573e8cca2e58c">llvm::CanonicalLoopInfo::getAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a47521ec347ef7b522745bf89e2e2d19a">llvm::CanonicalLoopInfo::getBody</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#ad3bf46daef8ce8176a68bcec0320dfd3">llvm::CanonicalLoopInfo::getExit</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#af4131f5f461f1138483addfd7cd7f579">llvm::CanonicalLoopInfo::getIndVar</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#ac37a6cf77f6f82b6bb28af4d9c8626d0">llvm::CanonicalLoopInfo::getLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#ad50eb30e70ff2a9ea7f220547e2b6f6d">llvm::CanonicalLoopInfo::getPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#ac72ebc430ef7dcf1791c66080ddedd9d">llvm::CanonicalLoopInfo::getPreheaderIP</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp/#ada7c1594a393ede3ce32602d64d7ddb2">Loops</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#abdcdbfc178873f5055fbcf98bad92f53">redirectAllPredecessorsTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3057c2b7e1e25de160497b1ef3985c2a">redirectTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af0ce60c4a958016f62ce78f1eda423af">removeUnusedBlocksFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#af1138294df67ee063ee3b7632a2f843f">TileSize</a>.</p>


<p>Referenced by <a href="#a5e2b7ac5f48193117a340aa15b085719">unrollLoopPartial</a>.</p>

</div>
</div>

### unrollLoopFull() {#a28a2a9806d828609fe107f766d2dd569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::unrollLoopFull (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * Loop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fully unroll a loop.</p>


<p>Instead of unrolling the loop immediately (and duplicating its body instructions), it is deferred to LLVM's <a href="/web-llvm/docs/api/classes/llvm/loopunrollpass">LoopUnrollPass</a> by adding loop metadata.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug location for instructions added by unrolling.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/loop"&gt;Loop&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The loop to unroll. The loop will be invalidated.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5254 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#adf813540e363817b85e9eecef51269b5">addLoopMetadata</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>.</p>

</div>
</div>

### unrollLoopHeuristic() {#a4ca0068cb6a50615c74ecdb8f23839e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::unrollLoopHeuristic (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * Loop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fully or partially unroll a loop.</p>


<p>How the loop is unrolled is determined using LLVM's <a href="/web-llvm/docs/api/classes/llvm/loopunrollpass">LoopUnrollPass</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug location for instructions added by unrolling.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/loop"&gt;Loop&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The loop to unroll. The loop will be invalidated.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5261 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#adf813540e363817b85e9eecef51269b5">addLoopMetadata</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>.</p>

</div>
</div>

### unrollLoopPartial() {#a5e2b7ac5f48193117a340aa15b085719}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::unrollLoopPartial (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * Loop, int32_t Factor, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> ** UnrolledCLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Partially unroll a loop.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> of the unrolled loop for use with chained loop-associated directive can be requested using <span class="doxyComputerOutput">UnrolledCLI</span>. Not needing the <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> allows more efficient code generation by deferring the actual unrolling to the <a href="/web-llvm/docs/api/classes/llvm/loopunrollpass">LoopUnrollPass</a> using loop metadata. A loop-associated directive applied to the unrolled loop needs to know the new trip count which means that if using a heuristically determined unroll factor (<span class="doxyComputerOutput">Factor</span> == 0), that factor must be computed immediately. We are using the same logic as the <a href="/web-llvm/docs/api/classes/llvm/loopunrollpass">LoopUnrollPass</a> to derived the unroll factor, but which assumes that some canonicalization has taken place (e.g. Mem2Reg, LICM, GVN, Inlining, etc.). That is, the heuristic will perform better when the unrolled loop's <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> is not needed.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug location for instructions added by unrolling.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/loop"&gt;Loop&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The loop to unroll. The loop will be invalidated.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Factor</td>
<td class="doxyParamItemDescription"><p>The factor to unroll the loop by. A factor of 0 indicates that a heuristic should be used to determine the unroll-factor.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UnrolledCLI</td>
<td class="doxyParamItemDescription"><p>If non-null, receives the <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> of the partially unrolled loop. Otherwise, uses loop metadata to defer unrolling to the <a href="/web-llvm/docs/api/classes/llvm/loopunrollpass">LoopUnrollPass</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5612 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#adf813540e363817b85e9eecef51269b5">addLoopMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a946282957319b8c23ab9f169abb504c4">computeHeuristicUnrollFactor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a13e877ef779ba7a0688081079f4f9b03">llvm::Type::getIntegerBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a76e12ec076e7af4be7b8b77a5d53d3fc">tileLoops</a>.</p>

</div>
</div>

### updateToLocation() {#afad4662affec545adea91dfb62f11829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OpenMPIRBuilder::updateToLocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc)</td>
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

<p>Update the internal location to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span>.</p>

<p>Definition at line 1972 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Reference <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>.</p>


<p>Referenced by <a href="#a6cc340cf5dc46cf45eb6f784577cadbd">createAtomicCapture</a>, <a href="#ab84af206a9a08b9bf97eaadc87874c6c">createAtomicCompare</a>, <a href="#a388d5a62753f4e7ff4b72e54c1233fbc">createAtomicRead</a>, <a href="#ae75c4b44f208011259ee93497c2cb411">createAtomicUpdate</a>, <a href="#a0e2de2c034e3083d006b92ddf14b8bcf">createAtomicWrite</a>, <a href="#abca6530c9099bd1b1c3e0a5c32381f07">createBarrier</a>, <a href="#ad89dcb3cd8a39ae57a69487c2988dace">createCachedThreadPrivate</a>, <a href="#a04285415a321e48322c08f3b9185540e">createCancel</a>, <a href="#ac669acbd0f638c6ef32977575362052e">createCanonicalLoop</a>, <a href="#ae0287686a5ffe03bc264972c862726ea">createCanonicalLoop</a>, <a href="#af2808c704c935cee35e9529907b59b1c">createCopyPrivate</a>, <a href="#ac379895c55a89804f49f1a775828c235">createCritical</a>, <a href="#afc2cc623eda981e1b3fbb61a44e80ef8">createFlush</a>, <a href="#a544a84c75ac55356516cc7365cbe6f02">createMapperAllocas</a>, <a href="#adf9f105d93a1a09d5307dc14e77293f1">createMasked</a>, <a href="#a970cc920a6bae8d641ac63fb33afb40b">createMaster</a>, <a href="#a81bc7a57bd0332843aed6275ba47bee0">createOMPAlloc</a>, <a href="#a807c913d5889a80440269b74d5755d6c">createOMPFree</a>, <a href="#a38345e93229faed92e719f1793807bb1">createOMPInteropDestroy</a>, <a href="#a7709370a0f6564aa772ce20caa45337e">createOMPInteropInit</a>, <a href="#aaef3fb3339c2ade5ffffccdd177e465c">createOMPInteropUse</a>, <a href="#a6e2bd6420d3d12339e32d4d1b3ba1394">createOrderedDepend</a>, <a href="#a012d736828ba67916f7e5a3e9ff1d68f">createOrderedThreadsSimd</a>, <a href="#a4f81b9940e1869e146636dc533455929">createParallel</a>, <a href="#ab0996924f219129d8de3cc1b8830f768">createReductions</a>, <a href="#aaa655ca8bca40c564d0b7c81ebaf8ff9">createReductionsGPU</a>, <a href="#a8565ee3d1c387153e57cd65a96390dfa">createSection</a>, <a href="#af36172c1f538b7305b44760997d5a3c2">createSections</a>, <a href="#a3e1a0b27abb4d57e2293c46802eee89d">createSingle</a>, <a href="#aa4d3157abd79d79562db3feb088706f4">createTarget</a>, <a href="#ae54a581ccf494afe52ae45af317bbd58">createTargetData</a>, <a href="#a1e1e2695745252cae26a9843b4d8daa3">createTargetDeinit</a>, <a href="#a7db9daa323dee69eb9ecc380ce6edae8">createTargetInit</a>, <a href="#a0af3c7a02c1325c04c59f857604bd4f3">createTask</a>, <a href="#a1f8b732c2f951d56302d4431f00f16bd">createTaskgroup</a>, <a href="#a419ffad9e4d59275e299ce1ad3c73cd4">createTaskwait</a>, <a href="#a0b0ed7f600549e4239bf10b5b85de66c">createTaskyield</a>, <a href="#a3f603d822817256077c95e6573f2b14a">createTeams</a>, <a href="#a9f09d4b7d64e71987be7bb45d8694ffe">emitKernelLaunch</a>, <a href="#a654b33adee2ae78ce74ecbe6aa5e5282">emitMapperCall</a> and <a href="#ad48c785749c7160070b39be42c67d2b7">emitTargetKernel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### applyDynamicWorkshareLoop() {#a040fad70b742c2d5fb4df1006b8e2fe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::applyDynamicWorkshareLoop (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * CLI, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a231ea6a9a0009e38969a20d4293119c7">omp::OMPScheduleType</a> SchedType, bool NeedsBarrier, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Chunk=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Modifies the canonical loop to be a dynamically-scheduled workshare loop.</p>


<p>This takes a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a></span> representing a canonical loop, such as the one created by <span class="doxyComputerOutput">createCanonicalLoop</span> and emits additional instructions to turn it into a workshare loop. In particular, it calls to an OpenMP runtime function in the preheader to obtain, and then in each iteration to update the loop counter.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug location for instructions added for the workshare-loop construct itself.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CLI</td>
<td class="doxyParamItemDescription"><p>A descriptor of the canonical loop to workshare.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>An insertion point for Alloca instructions usable in the preheader of the loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SchedType</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of scheduling to be passed to the init function.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NeedsBarrier</td>
<td class="doxyParamItemDescription"><p>Indicates whether a barrier must be insterted after the loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Chunk</td>
<td class="doxyParamItemDescription"><p>The size of loop chunk considered as a unit when scheduling. If <span class="doxyComputerOutput">nullptr</span>, defaults to 1.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Point where to insert code after the workshare construct.</p></dd>
</dl>


<p>Declaration at line 1051 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 4723 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### applyStaticChunkedWorkshareLoop() {#ae5ac7c7120c51e85a0a9b107b278773f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::applyStaticChunkedWorkshareLoop (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * CLI, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, bool NeedsBarrier, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ChunkSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Modifies the canonical loop a statically-scheduled workshare loop with a user-specified chunk size.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug location for instructions added for the workshare-loop construct itself.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CLI</td>
<td class="doxyParamItemDescription"><p>A descriptor of the canonical loop to workshare.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>An insertion point for Alloca instructions usable in the preheader of the loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NeedsBarrier</td>
<td class="doxyParamItemDescription"><p>Indicates whether a barrier must be inserted after the loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ChunkSize</td>
<td class="doxyParamItemDescription"><p>The user-specified chunk size.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Point where to insert code after the workshare construct.</p></dd>
</dl>


<p>Declaration at line 1025 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 4235 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### applyStaticWorkshareLoop() {#a4844b18964505b7687f7261c6eccde30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::applyStaticWorkshareLoop (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * CLI, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, bool NeedsBarrier)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Modifies the canonical loop to be a statically-scheduled workshare loop.</p>


<p>This takes a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a></span> representing a canonical loop, such as the one created by <span class="doxyComputerOutput">createCanonicalLoop</span> and emits additional instructions to turn it into a workshare loop. In particular, it calls to an OpenMP runtime function in the preheader to obtain the loop bounds to be used in the current thread, updates the relevant instructions in the canonical loop and calls to an OpenMP runtime finalization function after the loop.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug location for instructions added for the workshare-loop construct itself.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CLI</td>
<td class="doxyParamItemDescription"><p>A descriptor of the canonical loop to workshare.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>An insertion point for Alloca instructions usable in the preheader of the loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NeedsBarrier</td>
<td class="doxyParamItemDescription"><p>Indicates whether a barrier must be inserted after the loop.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Point where to insert code after the workshare construct.</p></dd>
</dl>


<p>Declaration at line 1007 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 4143 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### applyWorkshareLoopTarget() {#a3614ae5b7da8dfc1d3b6e74e3b114ae8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointTy OpenMPIRBuilder::applyWorkshareLoopTarget (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * CLI, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#ab6fb146c332fd3f3d677ee65081fe669">omp::WorksharingLoopType</a> LoopType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Modifies the canonical loop to be a statically-scheduled workshare loop which is executed on the device.</p>


<p>This takes a <span class="doxyComputerOutput">CLI</span> representing a canonical loop, such as the one created by</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#ae0287686a5ffe03bc264972c862726ea">createCanonicalLoop</a> and emits additional <a href="/web-llvm/docs/api/namespaces/llvm/#a7e3e687ddfdcbacd404bcf17b917dd88">instructions</a> to turn it into a workshare loop. In particular, it calls to an OpenMP runtime <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> in the <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#aecea88f231914d2a6dc7ecf19a57f583">preheader</a> to call OpenMP device rtl <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> which handles worksharing of loop body interations.</p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug location for instructions added for the workshare-loop construct itself.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CLI</td>
<td class="doxyParamItemDescription"><p>A descriptor of the canonical loop to workshare.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>An insertion point for Alloca instructions usable in the preheader of the loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LoopType</td>
<td class="doxyParamItemDescription"><p>Information about type of loop worksharing. It corresponds to type of loop workshare OpenMP pragma.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Point where to insert code after the workshare construct.</p></dd>
</dl>


<p>Declaration at line 985 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 4528 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### castValueToType() {#a1cb6bfe878702e37e95e0380de07134c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * OpenMPIRBuilder::castValueToType (<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * From, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ToType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cast value to the specified type.</p>

<p>Declaration at line 1411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 2379 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### checkAndEmitFlushAfterAtomic() {#ad9851d43b78a60e8de23a05bc9728e9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool OpenMPIRBuilder::checkAndEmitFlushAfterAtomic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> AO, AtomicKind AK)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine whether to emit flush or not.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AO</td>
<td class="doxyParamItemDescription"><p>The required atomic ordering</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AK</td>
<td class="doxyParamItemDescription"><p>The OpenMP atomic operation kind used.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>wether a flush was emitted or not</p></dd>
</dl>


<p>Declaration at line 3168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 8427 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### createIfVersion() {#af94ce0ccebe00cffe61b5a50ba679eb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::createIfVersion (<a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * Loop, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * IfCond, <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp; VMap, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; NamePrefix="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create alternative version of the loop to support if clause.</p>


<p>OpenMP if clause can require to generate second loop. This loop will be executed when if clause condition is not met. createIfVersion adds branch instruction to the copied loop if <span class="doxyComputerOutput">ifCond</span> is not met.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/loop"&gt;Loop&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>Original loop which should be versioned.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IfCond</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> which corresponds to if clause condition</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VMap</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to value map to define relation between original and copied loop values and loop blocks.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NamePrefix</td>
<td class="doxyParamItemDescription"><p>Optional name prefix for if.then if.else blocks.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1069 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5269 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### createOutlinedFunctionID() {#a6b89b3ff925ab192f9ae19165b342f83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * OpenMPIRBuilder::createOutlinedFunctionID (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * OutlinedFn, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> EntryFnIDName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2817 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6476 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### createReductionFunction() {#ad623afd8ebb3dfc080662cb43391b856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; Function * &gt; OpenMPIRBuilder::createReductionFunction (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ReducerName, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/reductioninfo">ReductionInfo</a> &gt; ReductionInfos, <a href="#a07f00f83b415baecc1af353eed43d123">ReductionGenCBKind</a> ReductionGenCBKind=<a href="#a07f00f83b415baecc1af353eed43d123a1744373124bab4b9336c0d19a141a1d1">ReductionGenCBKind::MLIR</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> FuncAttrs={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits reduction function.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReducerName</td>
<td class="doxyParamItemDescription"><p>Name of the function calling the reduction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionInfos</td>
<td class="doxyParamItemDescription"><p>Array type containing the ReductionOps.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="#a07f00f83b415baecc1af353eed43d123"&gt;ReductionGenCBKind&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>Optional param to specify Clang or MLIR CodeGenCB kind.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FuncAttrs</td>
<td class="doxyParamItemDescription"><p>Optional param to specify any function attributes that need to be copied to the new function.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The reduction function.</p></dd>
</dl>


<p>Declaration at line 1621 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 3412 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### createRuntimeShuffleFunction() {#a0d88ee325115ec9b60143c76f1d52dd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * OpenMPIRBuilder::createRuntimeShuffleFunction (<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Element, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementType, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function creates calls to one of two shuffle functions to copy variables between lanes in a warp.</p>

<p>Declaration at line 1415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 2403 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### createTargetRegionEntryAddr() {#a1713e12dd45c8fe0066bc7294cb18e7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * OpenMPIRBuilder::createTargetRegionEntryAddr (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * OutlinedFunction, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> EntryFnName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6488 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### emitAtomicUpdate() {#aa6d8ea685a6567c8b8747c7ac1545788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::pair&lt; Value *, Value * &gt; &gt; OpenMPIRBuilder::emitAtomicUpdate (<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * X, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * XElemTy, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Expr, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> AO, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615">AtomicRMWInst::BinOp</a> RMWOp, <a href="/web-llvm/docs/api/classes/llvm/function-ref">AtomicUpdateCallbackTy</a> &amp; UpdateOp, bool VolatileX, bool IsXBinopExpr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit atomic update for constructs: X = X BinOp Expr ,or X = Expr BinOp X For complex Operations: X = UpdateOp(X) =&gt; CmpExch X, old_X, UpdateOp(X) Only Scalar data types.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion point to be used for alloca instructions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">X</td>
<td class="doxyParamItemDescription"><p>The target atomic pointer to be updated</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">XElemTy</td>
<td class="doxyParamItemDescription"><p>The element type of the atomic pointer.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Expr</td>
<td class="doxyParamItemDescription"><p>The value to update X with.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AO</td>
<td class="doxyParamItemDescription"><p>Atomic ordering of the generated atomic instructions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RMWOp</td>
<td class="doxyParamItemDescription"><p>The binary operation used for update. If operation is not supported by atomicRMW, or belong to {FADD, FSUB, BAD_BINOP}. Then a <span class="doxyComputerOutput">cmpExch</span> based atomic will be generated.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UpdateOp</td>
<td class="doxyParamItemDescription"><p>Code generator for complex expressions that cannot be expressed through atomicrmw instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VolatileX</td>
<td class="doxyParamItemDescription"><p>true if <em>X</em> volatile?</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsXBinopExpr</td>
<td class="doxyParamItemDescription"><p>true if <em>X</em> is Left H.S. in Right H.S. part of the update expression, false otherwise. (e.g. true for X = X BinOp Expr)</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A pair of the old value of X before the update, and the value used for the update.</p></dd>
</dl>


<p>Declaration at line 3196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 8639 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### emitCommonDirectiveEntry() {#af4f8d828d3259d777583fd581935f8e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointTy OpenMPIRBuilder::emitCommonDirectiveEntry (omp::Directive OMPD, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * EntryCall, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * ExitBB, bool Conditional=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Common interface for generating entry calls for OMP Directives.</p>


<p>if the directive has a region/body, It will set the insertion point to the body</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OMPD</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> to generate entry blocks for</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryCall</td>
<td class="doxyParamItemDescription"><p>Call to the entry OMP Runtime <a href="/web-llvm/docs/api/classes/llvm/function">Function</a></p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ExitBB</td>
<td class="doxyParamItemDescription"><p>block where the region ends.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Conditional</td>
<td class="doxyParamItemDescription"><p>indicate if the entry call result will be used to evaluate a conditional of whether a thread will execute body code or not.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion position in exit block</p></dd>
</dl>


<p>Declaration at line 3085 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5940 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### emitCommonDirectiveExit() {#a229ff4e9eef9f328f8200b1cf14ac699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::emitCommonDirectiveExit (omp::Directive OMPD, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> FinIP, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * ExitCall, bool HasFinalize=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Common interface to finalize the region.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OMPD</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> to generate exiting code for</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FinIP</td>
<td class="doxyParamItemDescription"><p>Insertion point for emitting Finalization code and exit call</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ExitCall</td>
<td class="doxyParamItemDescription"><p>Call to the ending OMP Runtime <a href="/web-llvm/docs/api/classes/llvm/function">Function</a></p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HasFinalize</td>
<td class="doxyParamItemDescription"><p>indicate if the directive will require finalization and has a finalization callback in the stack that should be called.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion position in exit block</p></dd>
</dl>


<p>Declaration at line 3099 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5970 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### emitGlobalToListCopyFunction() {#a2e59efece640b939c81eaf81fa02ab32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * OpenMPIRBuilder::emitGlobalToListCopyFunction (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/reductioninfo">ReductionInfo</a> &gt; ReductionInfos, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ReductionsBufferTy, <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> FuncAttrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function emits a helper that copies all the reduction variables from the team into the provided global buffer for the reduction variables.</p>


<p>void list_to_global_copy_func(void *buffer, int Idx, void *reduce_data) For all data entries D in reduce_data: Copy buffer.D[Idx] to local D;</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionInfos</td>
<td class="doxyParamItemDescription"><p>Array type containing the ReductionOps.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionsBufferTy</td>
<td class="doxyParamItemDescription"><p>The StructTy for the reductions buffer.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FuncAttrs</td>
<td class="doxyParamItemDescription"><p>Optional param to specify any function attributes that need to be copied to the new function.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The GlobalToList function.</p></dd>
</dl>


<p>Declaration at line 1561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 3215 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### emitGlobalToListReduceFunction() {#a6401106579001ad5ac42a7332bfffd37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * OpenMPIRBuilder::emitGlobalToListReduceFunction (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/reductioninfo">ReductionInfo</a> &gt; ReductionInfos, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * ReduceFn, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ReductionsBufferTy, <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> FuncAttrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function emits a helper that reduces all the reduction variables from the team into the provided global buffer for the reduction variables.</p>


<p>void global_to_list_reduce_func(void &lt;em&gt;buffer, int Idx, void *reduce_data) void *GlobPtrs[]; GlobPtrs[0] = (void)&amp;buffer.D0[Idx]; ... GlobPtrs[N] = (void*)&amp;buffer.DN[Idx]; reduce_function(reduce_data, GlobPtrs);</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionInfos</td>
<td class="doxyParamItemDescription"><p>Array type containing the ReductionOps.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReduceFn</td>
<td class="doxyParamItemDescription"><p>The reduction function.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionsBufferTy</td>
<td class="doxyParamItemDescription"><p>The StructTy for the reductions buffer.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FuncAttrs</td>
<td class="doxyParamItemDescription"><p>Optional param to specify any function attributes that need to be copied to the new function.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The GlobalToListReduce function.</p></dd>
</dl>


<p>Declaration at line 1605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 3323 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### emitInterWarpCopyFunction() {#af2b92df8e0b82feb2e05a5bb228ff1fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; Function * &gt; OpenMPIRBuilder::emitInterWarpCopyFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/reductioninfo">ReductionInfo</a> &gt; ReductionInfos, <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> FuncAttrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function emits a helper that gathers Reduce lists from the first lane of every active warp to lanes in the first warp.</p>


<p>void inter_warp_copy_func(void* reduce_data, num_warps) shared smem[warp_size]; For all data entries D in reduce_data: sync If (I am the first lane in each warp) Copy my local D to smem[warp_id] sync if (I am the first warp) Copy smem[thread_id] to my local D</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionInfos</td>
<td class="doxyParamItemDescription"><p>Array type containing the ReductionOps.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FuncAttrs</td>
<td class="doxyParamItemDescription"><p>Optional param to specify any function attributes that need to be copied to the new function.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The InterWarpCopy function.</p></dd>
</dl>


<p>Declaration at line 1527 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 2622 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### emitListToGlobalCopyFunction() {#a9a44a77d29e591a2a0c4202074c68e80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * OpenMPIRBuilder::emitListToGlobalCopyFunction (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/reductioninfo">ReductionInfo</a> &gt; ReductionInfos, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ReductionsBufferTy, <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> FuncAttrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function emits a helper that copies all the reduction variables from the team into the provided global buffer for the reduction variables.</p>


<p>void list_to_global_copy_func(void *buffer, int Idx, void *reduce_data) For all data entries D in reduce_data: Copy local D to buffer.D[Idx]</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionInfos</td>
<td class="doxyParamItemDescription"><p>Array type containing the ReductionOps.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionsBufferTy</td>
<td class="doxyParamItemDescription"><p>The StructTy for the reductions buffer.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FuncAttrs</td>
<td class="doxyParamItemDescription"><p>Optional param to specify any function attributes that need to be copied to the new function.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The ListToGlobalCopy function.</p></dd>
</dl>


<p>Declaration at line 1544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 3022 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### emitListToGlobalReduceFunction() {#a89a9562bf041f9579c3a632035c32090}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * OpenMPIRBuilder::emitListToGlobalReduceFunction (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/reductioninfo">ReductionInfo</a> &gt; ReductionInfos, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * ReduceFn, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ReductionsBufferTy, <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> FuncAttrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function emits a helper that reduces all the reduction variables from the team into the provided global buffer for the reduction variables.</p>


<p>void list_to_global_reduce_func(void &lt;em&gt;buffer, int Idx, void *reduce_data) void *GlobPtrs[]; GlobPtrs[0] = (void)&amp;buffer.D0[Idx]; ... GlobPtrs[N] = (void*)&amp;buffer.DN[Idx]; reduce_function(GlobPtrs, reduce_data);</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionInfos</td>
<td class="doxyParamItemDescription"><p>Array type containing the ReductionOps.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReduceFn</td>
<td class="doxyParamItemDescription"><p>The reduction function.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionsBufferTy</td>
<td class="doxyParamItemDescription"><p>The StructTy for the reductions buffer.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FuncAttrs</td>
<td class="doxyParamItemDescription"><p>Optional param to specify any function attributes that need to be copied to the new function.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The ListToGlobalReduce function.</p></dd>
</dl>


<p>Declaration at line 1583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 3132 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### EmitOMPInlinedRegion() {#a233f727933cae11ca5eed3ba2142bf41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::EmitOMPInlinedRegion (omp::Directive OMPD, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * EntryCall, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * ExitCall, <a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> BodyGenCB, <a href="#a0c571620ff53fdb78e7404f5261dbd23">FinalizeCallbackTy</a> FiniCB, bool Conditional=false, bool HasFinalize=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool IsCancellable=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Common Interface to generate OMP inlined regions.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OMPD</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> to generate inlined region for</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryCall</td>
<td class="doxyParamItemDescription"><p>Call to the entry OMP Runtime <a href="/web-llvm/docs/api/classes/llvm/function">Function</a></p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ExitCall</td>
<td class="doxyParamItemDescription"><p>Call to the ending OMP Runtime <a href="/web-llvm/docs/api/classes/llvm/function">Function</a></p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Body code generation callback.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FiniCB</td>
<td class="doxyParamItemDescription"><p>Finalization Callback. Will be called when finalizing region</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Conditional</td>
<td class="doxyParamItemDescription"><p>indicate if the entry call result will be used to evaluate a conditional of whether a thread will execute body code or not.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HasFinalize</td>
<td class="doxyParamItemDescription"><p>indicate if the directive will require finalization and has a finalization callback in the stack that should be called.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsCancellable</td>
<td class="doxyParamItemDescription"><p>if HasFinalize is set to true, indicate if the the directive should be cancellable.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion point after the region</p></dd>
</dl>


<p>Declaration at line 3121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5887 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### emitReductionListCopy() {#a2e4dd18eb0b858f2905a2f5f9d12960a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::emitReductionListCopy (<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#a204d79d34d33ba7563337995bb481318">CopyAction</a> Action, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ReductionArrayTy, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/reductioninfo">ReductionInfo</a> &gt; ReductionInfos, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SrcBase, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * DestBase, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/copyoptionsty">CopyOptionsTy</a> CopyOptions={nullptr, nullptr, nullptr})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit instructions to copy a Reduce list, which contains partially aggregated values, in the specified direction.</p>

<p>Declaration at line 1425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 2509 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### emitRMWOpAsInstruction() {#a145de1d8971dac0fcc64919ecc758f3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * OpenMPIRBuilder::emitRMWOpAsInstruction (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Src1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Src2, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615">AtomicRMWInst::BinOp</a> RMWOp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the binary op.</p>


<p>described by <span class="doxyComputerOutput">RMWOp</span>, using <span class="doxyComputerOutput">Src1</span> and <span class="doxyComputerOutput">Src2</span> .</p>


<p>\Return The instruction</p>


<p>Declaration at line 3204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 8605 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### emitShuffleAndReduceFunction() {#aac0d4846664b3da00ab8601767c90a0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * OpenMPIRBuilder::emitShuffleAndReduceFunction (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/reductioninfo">OpenMPIRBuilder::ReductionInfo</a> &gt; ReductionInfos, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * ReduceFn, <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> FuncAttrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a helper that reduces data across two OpenMP threads (lanes) in the same warp.</p>


<p>It uses shuffle instructions to copy over data from a remote lane's stack. The reduction algorithm performed is specified by the fourth parameter.</p>


<p>Algorithm Versions. Full Warp Reduce (argument value 0): This algorithm assumes that all 32 lanes are active and gathers data from these 32 lanes, producing a single resultant value. Contiguous Partial Warp Reduce (argument value 1): This algorithm assumes that only a <em>contiguous</em> subset of lanes are active. This happens for the last warp in a parallel region when the user specified num_threads is not an integer multiple of</p>


<ol class="doxyList" type="1">
<li>This contiguous subset always starts with the zeroth lane. Partial Warp Reduce (argument value 2): This algorithm gathers data from any number of lanes at any position. All reduced values are stored in the lowest possible lane. The set of problems every algorithm addresses is a super set of those addressable by algorithms with a lower version number. Overhead increases as algorithm version increases.</li>
</ol>

<p>Terminology Reduce element: Reduce element refers to the individual data field with primitive data types to be combined and reduced across threads. Reduce list: Reduce list refers to a collection of local, thread-private reduce elements. Remote Reduce list: Remote Reduce list refers to a collection of remote (relative to the current thread) reduce elements.</p>


<p>We distinguish between three states of threads that are important to the implementation of this function. Alive threads: Threads in a warp executing the SIMT instruction, as distinguished from threads that are inactive due to divergent control flow. Active threads: The minimal set of threads that has to be alive upon entry to this function. The computation is correct iff active threads are alive. Some threads are alive but they are not active because they do not contribute to the computation in any useful manner. Turning them off may introduce control flow overheads without any tangible benefits. Effective threads: In order to comply with the argument requirements of the shuffle function, we must keep all lanes holding data alive. But at most half of them perform value aggregation; we refer to this half of threads as effective. The other half is simply handing off their data.</p>


<p>Procedure <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> shuffle: In this step active threads transfer data from higher lane positions in the warp to lower lane positions, creating Remote Reduce list. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> aggregation: In this step, effective threads combine their thread local Reduce list with Remote Reduce list and store the result in the thread local Reduce list. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> copy: In this step, we deal with the assumption made by algorithm 2 (i.e. contiguity assumption). When we have an odd number of lanes active, say 2k+1, only k threads will be effective and therefore k new values will be produced. However, the Reduce list owned by the (2k+1)th thread is ignored in the value aggregation. Therefore we copy the Reduce list from the (2k+1)th lane to (k+1)th lane so that the contiguity assumption still holds.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionInfos</td>
<td class="doxyParamItemDescription"><p>Array type containing the ReductionOps.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReduceFn</td>
<td class="doxyParamItemDescription"><p>The reduction function.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FuncAttrs</td>
<td class="doxyParamItemDescription"><p>Optional param to specify any function attributes that need to be copied to the new function.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The ShuffleAndReduce function.</p></dd>
</dl>


<p>Declaration at line 1503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 2857 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### emitUDMapperArrayInitOrDel() {#a9c12e64fffe008109723c3ca4618f988}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::emitUDMapperArrayInitOrDel (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * MapperFn, <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * MapperHandle, <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * Base, <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * Begin, <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * Size, <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * MapType, <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * MapName, <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> ElementSize, <a href="/web-llvm/docs/api/classes/llvm/basicblock">llvm::BasicBlock</a> * ExitBB, bool IsInit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the array initialization or deletion portion for user-defined mapper code generation.</p>


<p>First, it evaluates whether an array section is mapped and whether the <em>MapType</em> instructs to delete this section. If <em>IsInit</em> is true, and <em>MapType</em> indicates to not delete this array, array initialization code is generated. If <em>IsInit</em> is false, and <em>MapType</em> indicates to delete this array, array deletion code is generated.</p>


<p>Declaration at line 2904 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 7874 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### getGPUThreadID() {#a2a009f425138ea4040d027b23d083390}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * OpenMPIRBuilder::getGPUThreadID ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Supporting functions for Reductions CodeGen.</p>


<p>Get the id of the current thread on the GPU.</p>


<p>Declaration at line 1395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 2354 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### getGPUWarpSize() {#af903623c40d9e3c2ab371d7591d41bac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * OpenMPIRBuilder::getGPUWarpSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the GPU warp size.</p>

<p>Declaration at line 1398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 2361 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### getNVPTXLaneID() {#a2a9e43b0db2fb1ca6bee29b4f11130cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * OpenMPIRBuilder::getNVPTXLaneID ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the id of the current lane in the Warp.</p>


<p>We assume that the warp size is 32, which is always the case on the <a href="/web-llvm/docs/api/namespaces/llvm/nvptx">NVPTX</a> device, to generate more efficient code.</p>


<p>Declaration at line 1408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 2371 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### getNVPTXWarpID() {#a94f57a8823240d7bc68dd7c32c0dd882}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * OpenMPIRBuilder::getNVPTXWarpID ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the id of the warp in the block.</p>


<p>We assume that the warp size is 32, which is always the case on the <a href="/web-llvm/docs/api/namespaces/llvm/nvptx">NVPTX</a> device, to generate more efficient code.</p>


<p>Declaration at line 1403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 2366 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### getOMPCriticalRegionLock() {#a4910b0d2c5749629437e9c52bc639c7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * OpenMPIRBuilder::getOMPCriticalRegionLock (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CriticalName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns corresponding lock object for the specified critical region name.</p>


<p>If the lock object does not exist it is created, otherwise the reference to the existing copy is returned.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CriticalName</td>
<td class="doxyParamItemDescription"><p>Name of the critical region.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 3141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 7670 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### getReductionFuncName() {#a6eea64b337e04e34f135fe9294eeb941}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string OpenMPIRBuilder::getReductionFuncName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the function name of a reduction function.</p>

<p>Declaration at line 1610 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 3406 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### initializeTypes() {#a6b69d9afaff34536b7ccc2ec990ae656}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::initializeTypes (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>}</p>


<p>Create all simple and struct types exposed by the runtime and remember the llvm::PointerTypes of them for easy access later.</p>


<p>Declaration at line 3071 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9180 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### setOutlinedTargetRegionFunctionAttributes() {#ace5c16ccd45a0ce550055164ab081b5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::setOutlinedTargetRegionFunctionAttributes (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * OutlinedFn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>}</p>

<p>Declaration at line 2812 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6462 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### shuffleAndStore() {#a0ab8f7d26b196b4d0cff794943f8aea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::shuffleAndStore (<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SrcAddr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * DstAddr, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementType, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Offset, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ReductionArrayTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> to shuffle over the value from the remote lane.</p>

<p>Declaration at line 1419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 2425 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Builder {#ad90c28bb43cb3cee06cb2f1686784b40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRBuilder llvm::OpenMPIRBuilder::Builder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The LLVM-IR Builder used to create IR.</p>

<p>Definition at line 2090 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#acd1fbb2df257f945afda92919be322f3">applySimd</a>, <a href="#a08610118e213de1b759470f0eafb9b18">collapseLoops</a>, <a href="#a6cc340cf5dc46cf45eb6f784577cadbd">createAtomicCapture</a>, <a href="#ab84af206a9a08b9bf97eaadc87874c6c">createAtomicCompare</a>, <a href="#a388d5a62753f4e7ff4b72e54c1233fbc">createAtomicRead</a>, <a href="#ae75c4b44f208011259ee93497c2cb411">createAtomicUpdate</a>, <a href="#a0e2de2c034e3083d006b92ddf14b8bcf">createAtomicWrite</a>, <a href="#abca6530c9099bd1b1c3e0a5c32381f07">createBarrier</a>, <a href="#ad89dcb3cd8a39ae57a69487c2988dace">createCachedThreadPrivate</a>, <a href="#a04285415a321e48322c08f3b9185540e">createCancel</a>, <a href="#ac669acbd0f638c6ef32977575362052e">createCanonicalLoop</a>, <a href="#ae0287686a5ffe03bc264972c862726ea">createCanonicalLoop</a>, <a href="#a70356a38271d388e7c4b477cef0d7b2c">createCopyinClauseBlocks</a>, <a href="#af2808c704c935cee35e9529907b59b1c">createCopyPrivate</a>, <a href="#ac379895c55a89804f49f1a775828c235">createCritical</a>, <a href="#a445fa52d77040bccb16bfea111234a2e">createLoopSkeleton</a>, <a href="#a544a84c75ac55356516cc7365cbe6f02">createMapperAllocas</a>, <a href="#adf9f105d93a1a09d5307dc14e77293f1">createMasked</a>, <a href="#a970cc920a6bae8d641ac63fb33afb40b">createMaster</a>, <a href="#acc290ce16055813d4ee68af4c8023a09">createOffloadEntriesAndInfoMetadata</a>, <a href="#a81bc7a57bd0332843aed6275ba47bee0">createOMPAlloc</a>, <a href="#a807c913d5889a80440269b74d5755d6c">createOMPFree</a>, <a href="#a38345e93229faed92e719f1793807bb1">createOMPInteropDestroy</a>, <a href="#a7709370a0f6564aa772ce20caa45337e">createOMPInteropInit</a>, <a href="#aaef3fb3339c2ade5ffffccdd177e465c">createOMPInteropUse</a>, <a href="#a6e2bd6420d3d12339e32d4d1b3ba1394">createOrderedDepend</a>, <a href="#a012d736828ba67916f7e5a3e9ff1d68f">createOrderedThreadsSimd</a>, <a href="#a4f81b9940e1869e146636dc533455929">createParallel</a>, <a href="#ab0996924f219129d8de3cc1b8830f768">createReductions</a>, <a href="#aaa655ca8bca40c564d0b7c81ebaf8ff9">createReductionsGPU</a>, <a href="#a8565ee3d1c387153e57cd65a96390dfa">createSection</a>, <a href="#af36172c1f538b7305b44760997d5a3c2">createSections</a>, <a href="#a3e1a0b27abb4d57e2293c46802eee89d">createSingle</a>, <a href="#aa4d3157abd79d79562db3feb088706f4">createTarget</a>, <a href="#ae54a581ccf494afe52ae45af317bbd58">createTargetData</a>, <a href="#a1e1e2695745252cae26a9843b4d8daa3">createTargetDeinit</a>, <a href="#a7db9daa323dee69eb9ecc380ce6edae8">createTargetInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#acae95016bcdeb105bcbcaaa872893f5f">createTargetLoopWorkshareCall</a>, <a href="#a0af3c7a02c1325c04c59f857604bd4f3">createTask</a>, <a href="#a1f8b732c2f951d56302d4431f00f16bd">createTaskgroup</a>, <a href="#a3f603d822817256077c95e6573f2b14a">createTeams</a>, <a href="#a9199bb920d3966ef9c614a623c7af495">emitBlock</a>, <a href="#a0c977097cc5c8d9c7c049e8fc988fdcf">emitBranch</a>, <a href="#a98b55a0d95b3926151545101e4f2aef9">emitCancelationCheckImpl</a>, <a href="#a2a4b97bb7670d306c756cdbd5ee9b560">emitFlush</a>, <a href="#a39b12e3ad8afd4183a2cd63f1b1b8746">emitIfClause</a>, <a href="#a1943d078483c15aa78cb00f7fff2590c">emitKernelExecutionMode</a>, <a href="#a9f09d4b7d64e71987be7bb45d8694ffe">emitKernelLaunch</a>, <a href="#a654b33adee2ae78ce74ecbe6aa5e5282">emitMapperCall</a>, <a href="#a827b80924bcd29f32b772a4ed162fb68">emitNonContiguousDescriptor</a>, <a href="#a752e863c1af5fe463d0f08574492c12f">emitOffloadingArrays</a>, <a href="#a966e441c1e3f27fce994c360b55abae9">emitOffloadingArraysAndArgs</a>, <a href="#adb95f78638066c9b6ccba6e3a7d335da">emitOffloadingArraysArgument</a>, <a href="#ad48c785749c7160070b39be42c67d2b7">emitTargetKernel</a>, <a href="#a2841680b34ec9c2c7185a877f8f8b4c8">emitTargetTask</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a9702d30c99a5459e9565631adf1fdf1b">emitTaskDependencies</a>, <a href="#a177df2c9d7d8692ed214018f420c3de6">emitTaskwaitImpl</a>, <a href="#a6383328cfcdbbd56502b92f9e2415432">emitTaskyieldImpl</a>, <a href="#a3bb33831dbcaa836f630ed1dc986b5c2">emitUsed</a>, <a href="#aad01bd2643d37f64f9d9a2933b8ddfc2">emitUserDefinedMapper</a>, <a href="#a784adc2347b72f745ff1239aef3a3c26">finalize</a>, <a href="#aa26124809eff11c5f244027439751c50">getInsertionPoint</a>, <a href="#a49e1f0512e7d7b37dfcecc0b25dd875b">getKernelArgsVector</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a9607f501333d84917dc48f5d263e9b6c">getOrCreateThreadID</a>, <a href="#ae19488d3493945579ed3987ce14c6ff2">getSizeInBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#afffa0ff2e1527ab545cef33be915c656">hostParallelCallback</a>, <a href="#ae1a990c96a3ebf58698901d09c5b4378">OpenMPIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af7668ce8080668a4f0ceac24e70c9f00">targetParallelCallback</a>, <a href="#a76e12ec076e7af4be7b8b77a5d53d3fc">tileLoops</a>, <a href="#a28a2a9806d828609fe107f766d2dd569">unrollLoopFull</a>, <a href="#a4ca0068cb6a50615c74ecdb8f23839e0">unrollLoopHeuristic</a>, <a href="#afad4662affec545adea91dfb62f11829">updateToLocation</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#aa2a5199bf39360e25f40b93cd5f9468a">workshareLoopTargetCallback</a>.</p>

</div>
</div>

### Config {#a355507f9e59388e467dc9288e4f82c3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilderConfig llvm::OpenMPIRBuilder::Config</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder">OpenMPIRBuilder</a> Configuration.</p>

<p>Definition at line 2084 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#adaa14806d128ad33bdc48d2bfc46870c">applyWorkshareLoop</a>, <a href="#acc290ce16055813d4ee68af4c8023a09">createOffloadEntriesAndInfoMetadata</a>, <a href="#ac5805e4c7f00be338494407152cf34aa">createOffloadEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a>, <a href="#a4f81b9940e1869e146636dc533455929">createParallel</a>, <a href="#a488c861f8a68e5f78ceca8b57acd8be5">createPlatformSpecificName</a>, <a href="#aaa655ca8bca40c564d0b7c81ebaf8ff9">createReductionsGPU</a>, <a href="#aa4d3157abd79d79562db3feb088706f4">createTarget</a>, <a href="#ae54a581ccf494afe52ae45af317bbd58">createTargetData</a>, <a href="#a3f603d822817256077c95e6573f2b14a">createTeams</a>, <a href="#a567502d7244077ed45e0c9471d31ba4c">emitTargetRegionFunction</a>, <a href="#a784adc2347b72f745ff1239aef3a3c26">finalize</a>, <a href="#afdc1b8675a946ce055c64607ba75af3a">getAddrOfDeclareTargetVar</a>, <a href="#ae327be8503a76bd4dccfff4713a38553">registerTargetGlobalVariable</a> and <a href="#a3cf3a832c89fb823f696ce21ecf37b9b">setConfig</a>.</p>

</div>
</div>

### ConstantAllocaRaiseCandidates {#aebfa8e874069dcc7e02ea471d941d9ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;llvm::Function *, 16&gt; llvm::OpenMPIRBuilder::ConstantAllocaRaiseCandidates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A collection of candidate target functions that's constant allocas will attempt to be raised on a call of finalize after all currently enqueued outline info's have been processed.</p>

<p>Definition at line 2127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a> and <a href="#a784adc2347b72f745ff1239aef3a3c26">finalize</a>.</p>

</div>
</div>

### FinalizationStack {#a75f3209cae3f3f2700c6bc6e9623f841}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;FinalizationInfo, 8&gt; llvm::OpenMPIRBuilder::FinalizationStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The finalization stack made up of finalize callbacks currently in-flight, wrapped into <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/finalizationinfo">FinalizationInfo</a> objects that reference also the finalization target block and the kind of cancellable directive.</p>

<p>Definition at line 2058 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a4f81b9940e1869e146636dc533455929">createParallel</a>, <a href="#af36172c1f538b7305b44760997d5a3c2">createSections</a>, <a href="#a98b55a0d95b3926151545101e4f2aef9">emitCancelationCheckImpl</a>, <a href="#ad44e60b9d264f6ceb54e6cd660e859fb">isLastFinalizationInfoCancellable</a>, <a href="#af2e7210874149ecbd52c8ce44ca4f416">popFinalizationCB</a> and <a href="#a977f2477d245a9d554642492fedd049a">pushFinalizationCB</a>.</p>

</div>
</div>

### IdentMap {#a801d4c8626e9914c0bc6b756c64c0730}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;Constant *, uint64_t&gt;, Constant *&gt; llvm::OpenMPIRBuilder::IdentMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map to remember existing ident_t*.</p>

<p>Definition at line 2096 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>.</p>

</div>
</div>

### InternalVars {#aa58c09ca23b31b6bebfa825111dc3923}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;GlobalVariable *, BumpPtrAllocator&gt; llvm::OpenMPIRBuilder::InternalVars</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An ordered map of auto-generated variables to their unique names.</p>


<p>It stores variables with the following names: 1) ".gomp_critical_user_" + &lt;critical_section_name&gt; + ".var" for "omp critical" directives; 2) &lt;mangled_name_for_global_var&gt; + ".cache." for cache for threadprivate variables.</p>


<p>Definition at line 2141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#aa5ef00e5a7487cc6c5bfed0f301fa1cc">getOrCreateInternalVariable</a>.</p>

</div>
</div>

### LoopInfos {#a418fd65883c81897f472643208a988b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::forward_list&lt;CanonicalLoopInfo&gt; llvm::OpenMPIRBuilder::LoopInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collection of owned canonical loop objects that eventually need to be free'd.</p>

<p>Definition at line 2131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a445fa52d77040bccb16bfea111234a2e">createLoopSkeleton</a>.</p>

</div>
</div>

### M {#a535304630869bfe0b7c0a81bb3c44497}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module&amp; llvm::OpenMPIRBuilder::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The underlying LLVM-IR module.</p>

<p>Definition at line 2087 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#ab84af206a9a08b9bf97eaadc87874c6c">createAtomicCompare</a>, <a href="#a388d5a62753f4e7ff4b72e54c1233fbc">createAtomicRead</a>, <a href="#a0e2de2c034e3083d006b92ddf14b8bcf">createAtomicWrite</a>, <a href="#a70356a38271d388e7c4b477cef0d7b2c">createCopyinClauseBlocks</a>, <a href="#ae2d016504f27bd96960ace8645073d63">createDispatchDeinitFunction</a>, <a href="#a5946a2c7130bcf42add273f83cb6e257">createDispatchFiniFunction</a>, <a href="#aac7493b7e13af08014a1c49dcdecbf20">createDispatchInitFunction</a>, <a href="#a49dbf0af8f3e1314b3b60222651b6fc2">createDispatchNextFunction</a>, <a href="#a8191e2fd322236b59afb070919f0d6af">createForStaticInitFunction</a>, <a href="#ada8d44774af63e8cab5f9b2a088121fe">createGlobalFlag</a>, <a href="#a445fa52d77040bccb16bfea111234a2e">createLoopSkeleton</a>, <a href="#acc290ce16055813d4ee68af4c8023a09">createOffloadEntriesAndInfoMetadata</a>, <a href="#ac5805e4c7f00be338494407152cf34aa">createOffloadEntry</a>, <a href="#ab1aa0d632549db4855d6412f4d2d44ae">createOffloadMapnames</a>, <a href="#ad56f71598b251a0f66e590c94d01c67b">createOffloadMaptypes</a>, <a href="#a38345e93229faed92e719f1793807bb1">createOMPInteropDestroy</a>, <a href="#a7709370a0f6564aa772ce20caa45337e">createOMPInteropInit</a>, <a href="#aaef3fb3339c2ade5ffffccdd177e465c">createOMPInteropUse</a>, <a href="#a4f81b9940e1869e146636dc533455929">createParallel</a>, <a href="#aaa655ca8bca40c564d0b7c81ebaf8ff9">createReductionsGPU</a>, <a href="#af36172c1f538b7305b44760997d5a3c2">createSections</a>, <a href="#a1e1e2695745252cae26a9843b4d8daa3">createTargetDeinit</a>, <a href="#a7db9daa323dee69eb9ecc380ce6edae8">createTargetInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#acae95016bcdeb105bcbcaaa872893f5f">createTargetLoopWorkshareCall</a>, <a href="#a0af3c7a02c1325c04c59f857604bd4f3">createTask</a>, <a href="#a39b12e3ad8afd4183a2cd63f1b1b8746">emitIfClause</a>, <a href="#a1943d078483c15aa78cb00f7fff2590c">emitKernelExecutionMode</a>, <a href="#a827b80924bcd29f32b772a4ed162fb68">emitNonContiguousDescriptor</a>, <a href="#a752e863c1af5fe463d0f08574492c12f">emitOffloadingArrays</a>, <a href="#adb95f78638066c9b6ccba6e3a7d335da">emitOffloadingArraysArgument</a>, <a href="#ad48c785749c7160070b39be42c67d2b7">emitTargetKernel</a>, <a href="#a2841680b34ec9c2c7185a877f8f8b4c8">emitTargetTask</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3fb4884285f5bcb9a37d9378d1e33cd5">emitTargetTaskProxyFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a9702d30c99a5459e9565631adf1fdf1b">emitTaskDependencies</a>, <a href="#a3bb33831dbcaa836f630ed1dc986b5c2">emitUsed</a>, <a href="#aad01bd2643d37f64f9d9a2933b8ddfc2">emitUserDefinedMapper</a>, <a href="#a784adc2347b72f745ff1239aef3a3c26">finalize</a>, <a href="#afdc1b8675a946ce055c64607ba75af3a">getAddrOfDeclareTargetVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#aca27639a720491c7c7ea13c2bbe8c162">getKmpcForStaticLoopForType</a>, <a href="#a02cae9681b22a06e7738a4c1f3de233e">getOrCreateIdent</a>, <a href="#aa5ef00e5a7487cc6c5bfed0f301fa1cc">getOrCreateInternalVariable</a>, <a href="#a034dc6253a2a36f78ac071a7c12d5c27">getOrCreateRuntimeFunction</a>, <a href="#a7a0ce50dfb1a164ee67119899992c75b">getOrCreateRuntimeFunctionPtr</a>, <a href="#a9b8c05f635a1b8e5a66eeec4704bf291">getOrCreateSrcLocStr</a>, <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>, <a href="#a1af99f6f33b0db83a3e941fcb819fa29">initialize</a>, <a href="#a2242b144e54fa6203dae5c5b27fff17c">loadOffloadInfoMetadata</a>, <a href="#ac6293b7ea84a4deac85481dd10dad437">loadOffloadInfoMetadata</a>, <a href="#ae1a990c96a3ebf58698901d09c5b4378">OpenMPIRBuilder</a> and <a href="#ae327be8503a76bd4dccfff4713a38553">registerTargetGlobalVariable</a>.</p>

</div>
</div>

### OffloadInfoManager {#aed2a8b469e9884788eef400fbc892dd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffloadEntriesInfoManager llvm::OpenMPIRBuilder::OffloadInfoManager</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Info manager to keep track of target regions.</p>

<p>Definition at line 2099 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#acc290ce16055813d4ee68af4c8023a09">createOffloadEntriesAndInfoMetadata</a>, <a href="#a567502d7244077ed45e0c9471d31ba4c">emitTargetRegionFunction</a>, <a href="#a784adc2347b72f745ff1239aef3a3c26">finalize</a>, <a href="#a2242b144e54fa6203dae5c5b27fff17c">loadOffloadInfoMetadata</a>, <a href="#ae1a990c96a3ebf58698901d09c5b4378">OpenMPIRBuilder</a>, <a href="#ae327be8503a76bd4dccfff4713a38553">registerTargetGlobalVariable</a> and <a href="#a17c7f65c3ce26b3b0de6774c0d3c723f">registerTargetRegionFunction</a>.</p>

</div>
</div>

### ompOffloadInfoName {#aefadc356da16598ff8c210dafbf4a2b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string llvm::OpenMPIRBuilder::ompOffloadInfoName = "omp_offload.info"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OMP Offload Info <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> name string.</p>

<p>Definition at line 3385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a2242b144e54fa6203dae5c5b27fff17c">loadOffloadInfoMetadata</a>.</p>

</div>
</div>

### OutlineInfos {#a79e8ec8cdc9299c9bab67b625e6578c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;OutlineInfo, 16&gt; llvm::OpenMPIRBuilder::OutlineInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collection of regions that need to be outlined during finalization.</p>

<p>Definition at line 2122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a5610e0ef8f016e84694778d8ce1c9479">addOutlineInfo</a>, <a href="#a784adc2347b72f745ff1239aef3a3c26">finalize</a> and <a href="#ad66949e2e846451e61d9c8f34014ea31">~OpenMPIRBuilder</a>.</p>

</div>
</div>

### SrcLocStrMap {#a539b79b038631cce06319250c09f8cfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;Constant *&gt; llvm::OpenMPIRBuilder::SrcLocStrMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map to remember source location strings.</p>

<p>Definition at line 2093 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a55a39962245dd2e0938194dd3b4438e5">getOrCreateSrcLocStr</a>.</p>

</div>
</div>

### T {#a7f3588f949f4fb51454b0b8c6194ca75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Triple llvm::OpenMPIRBuilder::T</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The target triple of the underlying module.</p>

<p>Definition at line 2102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a50c6490cf353f064946c4e32673ac098">addAttributes</a>, <a href="#ac5805e4c7f00be338494407152cf34aa">createOffloadEntry</a>, <a href="#aaa655ca8bca40c564d0b7c81ebaf8ff9">createReductionsGPU</a>, <a href="#a7db9daa323dee69eb9ecc380ce6edae8">createTargetInit</a>, <a href="#ae1a990c96a3ebf58698901d09c5b4378">OpenMPIRBuilder</a>, <a href="#a321704fa9e503d47cab3eec5492f35ba">readThreadBoundsForKernel</a>, <a href="#ab79b6d86df13a709eee10c4c7d39c644">writeTeamsForKernel</a> and <a href="#a0ea31ab1f2b7d1f5585df18b0528fcf3">writeThreadBoundsForKernel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getKernelArgsVector() {#a49e1f0512e7d7b37dfcecc0b25dd875b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::getKernelArgsVector (<a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetkernelargs">TargetKernelArgs</a> &amp; KernelArgs, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; ArgsVector)</td>
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

<p>Create the kernel args vector used by emitTargetKernel.</p>


<p>This function creates various constant values that are used in the resulting args vector.</p>


<p>Declaration at line 2303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs/#aa998b8b179dd186fe4b5a1f6b6e25327">llvm::OpenMPIRBuilder::TargetDataRTArgs::BasePointersArray</a>, <a href="#ad90c28bb43cb3cee06cb2f1686784b40">Builder</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetkernelargs/#a54507f6f762774d59326a2145ae440f9">llvm::OpenMPIRBuilder::TargetKernelArgs::DynCGGroupMem</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetkernelargs/#abb0aaa97617824c208f95e218b9fcf6c">llvm::OpenMPIRBuilder::TargetKernelArgs::HasNoWait</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23f9ec4bb2576ca8738f3edc9c4f5cdf">llvm::Int32Ty</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs/#aff8f3378279256a13c9938a109ef38fe">llvm::OpenMPIRBuilder::TargetDataRTArgs::MapNamesArray</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs/#a4b54534e64cdf22a09f26ddacebe69ac">llvm::OpenMPIRBuilder::TargetDataRTArgs::MappersArray</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs/#abfc59185affff631915c34412a350c8c">llvm::OpenMPIRBuilder::TargetDataRTArgs::MapTypesArray</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetkernelargs/#a9289b4e3e6193c6848534421a1f6d325">llvm::OpenMPIRBuilder::TargetKernelArgs::NumIterations</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetkernelargs/#ab406e5f23f9a8061483e9d879708e58b">llvm::OpenMPIRBuilder::TargetKernelArgs::NumTargetItems</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetkernelargs/#ac5718af182d3976468a66ffef21caefd">llvm::OpenMPIRBuilder::TargetKernelArgs::NumTeams</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetkernelargs/#a565226b20a62efa516b5f5b69af983dc">llvm::OpenMPIRBuilder::TargetKernelArgs::NumThreads</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompconstants-h/#a893a8cf8f1e26701b29719386c42c9a7">OMP_KERNEL_ARG_VERSION</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs/#a44027c71c6a6a9a4111594eeb16da30e">llvm::OpenMPIRBuilder::TargetDataRTArgs::PointersArray</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetkernelargs/#a5a05e86ad780f78491ca53c7cade2629">llvm::OpenMPIRBuilder::TargetKernelArgs::RTArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs/#a00635325d57af0b95f0b797f63ee6df6">llvm::OpenMPIRBuilder::TargetDataRTArgs::SizesArray</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="#a9f09d4b7d64e71987be7bb45d8694ffe">emitKernelLaunch</a>.</p>

</div>
</div>

### getOpenMPDefaultSimdAlign() {#ac5b407054e7727d04053af9c3f1a5568}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned OpenMPIRBuilder::getOpenMPDefaultSimdAlign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TargetTriple, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; bool &gt; &amp; Features)</td>
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

<p>Get the default alignment value for given target.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TargetTriple</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> triple</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Features</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a> which describes extra CPU features</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 850 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5326 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a0338eabc8ab4dff6368bdfae6ec94cbc">llvm::Triple::isPPC</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#acf7f07dbe7dd1f7edd291b75005280bb">llvm::Triple::isWasm</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a31d94b95418472bb1179f7c130ad3667">llvm::Triple::isX86</a> and <a href="/web-llvm/docs/api/classes/llvm/stringmap/#aa6528965c64b379c2cb311599babdd66">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::lookup</a>.</p>

</div>
</div>

### getTargetEntryUniqueInfo() {#a12b066e3e9cc61240457d12df75df64b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetRegionEntryInfo OpenMPIRBuilder::getTargetEntryUniqueInfo (<a href="#ad324bf833c1de81f7dfdbd943660e9bc">FileIdentifierInfoCallbackTy</a> CallBack, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ParentName="")</td>
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

<p>Creates a unique info for a target entry when provided a filename and line number from.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CallBack</td>
<td class="doxyParamItemDescription"><p>A callback function which should return filename the entry resides in as well as the line number for the target entry</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ParentName</td>
<td class="doxyParamItemDescription"><p>The name of the parent the target entry resides in, if any.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9424 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a7e0dd3b9d03107bf25def8333283d822">llvm::sys::fs::getUniqueID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### readTeamBoundsForKernel() {#aed359885b0e344d18e4921011813748b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; int32_t, int32_t &gt; OpenMPIRBuilder::readTeamBoundsForKernel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Kernel)</td>
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

<p>Read/write a bounds on teams for <span class="doxyComputerOutput">Kernel</span>.</p>


<p>Read will return 0 if none is set.</p>


<p>Declaration at line 2804 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6446 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ac5c4384a376959ec882f7650e427dbb5">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::initialize</a>.</p>

</div>
</div>

### readThreadBoundsForKernel() {#a321704fa9e503d47cab3eec5492f35ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; int32_t, int32_t &gt; OpenMPIRBuilder::readThreadBoundsForKernel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Kernel)</td>
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

<p>}</p>


<p>Helpers to read/write kernel annotations from the IR.</p>


<p>{ Read/write a bounds on threads for <span class="doxyComputerOutput">Kernel</span>. Read will return 0 if none is set.</p>


<p>Declaration at line 2798 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6405 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a749d7f5580e6a5b6214d911bad2a0b36">getNVPTXMDNode</a> and <a href="#a7f3588f949f4fb51454b0b8c6194ca75">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ac5c4384a376959ec882f7650e427dbb5">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::initialize</a>.</p>

</div>
</div>

### writeTeamsForKernel() {#ab79b6d86df13a709eee10c4c7d39c644}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::writeTeamsForKernel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Kernel, int32_t LB, int32_t UB)</td>
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



<p>Declaration at line 2806 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6451 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#a7f3588f949f4fb51454b0b8c6194ca75">T</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a457f42a32df73079ac4526c572a2d7fd">updateNVPTXMetadata</a>.</p>


<p>Referenced by <a href="#a7db9daa323dee69eb9ecc380ce6edae8">createTargetInit</a>.</p>

</div>
</div>

### writeThreadBoundsForKernel() {#a0ea31ab1f2b7d1f5585df18b0528fcf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::writeThreadBoundsForKernel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Kernel, int32_t LB, int32_t UB)</td>
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



<p>Declaration at line 2799 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 6431 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#a7f3588f949f4fb51454b0b8c6194ca75">T</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a457f42a32df73079ac4526c572a2d7fd">updateNVPTXMetadata</a>.</p>


<p>Referenced by <a href="#a7db9daa323dee69eb9ecc380ce6edae8">createTargetInit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getNameWithSeparators() {#ad724b3adf53754848d6f9ac6818ef34e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string OpenMPIRBuilder::getNameWithSeparators (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Parts, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FirstSeparator, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Separator)</td>
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

<p>Get the platform-specific name separator.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Parts</td>
<td class="doxyParamItemDescription"><p>different parts of the final name that needs separation</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FirstSeparator</td>
<td class="doxyParamItemDescription"><p>First separator used between the initial two parts of the name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Separator</td>
<td class="doxyParamItemDescription"><p>separator used between all of the rest consecutive parts of the name</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 3132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 7622 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
