---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/omp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `omp` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::omp { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/omp/assumptionclausemappinginfo">AssumptionClauseMappingInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to describe assume clauses. <a href="/web-llvm/docs/api/structs/llvm/omp/assumptionclausemappinginfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/omp/variantmatchinfo">VariantMatchInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Variant match information describes the required traits and how they are scored (via the ScoresMap). <a href="/web-llvm/docs/api/structs/llvm/omp/variantmatchinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/omp/ompcontext">OMPContext</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The context for a source location is made up of active property traits, e.g., device={kind(host)}, and constructs traits which describe the nesting in OpenMP constructs at the location. <a href="/web-llvm/docs/api/structs/llvm/omp/ompcontext/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/omp/gv">GV</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Defines various target-specific GPU grid values that must be consistent between host RTL (plugin), device RTL, and clang. <a href="/web-llvm/docs/api/structs/llvm/omp/gv/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab07e7d76494438d05bf51cd36ba5a795">Kernel</a> = <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Summary of a kernel (=entry point for target offloading). <a href="#ab07e7d76494438d05bf51cd36ba5a795">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9934fab566f410c639070bf0d60f10f">KernelSet</a> = <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="#ab07e7d76494438d05bf51cd36ba5a795">Kernel</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of kernels in the module. <a href="#aa9934fab566f410c639070bf0d60f10f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">InternalControlVar { <a href="#a4608c581e6f18962661f7fc39ea88da2">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IDs for all Internal Control Variables (ICVs). <a href="#a4608c581e6f18962661f7fc39ea88da2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ICVInitValue { <a href="#a58b53550e1be2a034095e3e31fc82d66">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">RuntimeFunction { <a href="#a4c503140c7f851151906d85b515330e9">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IDs for all omp runtime library (RTL) functions. <a href="#a4c503140c7f851151906d85b515330e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DefaultKind { <a href="#adb7b881301debe51ac707e2e08e25035">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IDs for the different default kinds. <a href="#adb7b881301debe51ac707e2e08e25035">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">IdentFlag { <a href="#a0e821d8251c97d66ca185efe2f8ffde2">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IDs for all omp runtime library ident_t flag encodings (see their defintion in openmp/runtime/src/kmp.h). <a href="#a0e821d8251c97d66ca185efe2f8ffde2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OMPScheduleType { <a href="#a231ea6a9a0009e38969a20d4293119c7">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">OpenMPOffloadMappingFlags : uint64_t { <a href="#a02d7a52c47f2d71a111aef9d4fb70ecb">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Values for bit flags used to specify the mapping type for offloading. <a href="#a02d7a52c47f2d71a111aef9d4fb70ecb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OpenMPOffloadingReservedDeviceIDs { <a href="#a032f350e065d895f441c08affb57c2be">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">AddressSpace : unsigned { <a href="#a8c6f525466cc262e00c409c31f9a4272">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">OMPInteropType { <a href="#afeaad9a7fc12d9246c2e42578fddc718">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">OMPAtomicCompareOp : unsigned { <a href="#acb593a387130148478f3c30af0d322df">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Atomic compare operations. Currently OpenMP only supports ==, &gt;, and &lt;. <a href="#acb593a387130148478f3c30af0d322df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">RTLDependInfoFields { <a href="#a16d7c5f77008a84ae20bf4a5c41e51f0">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fields ids in kmp_depend_info record. <a href="#a16d7c5f77008a84ae20bf4a5c41e51f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">RTLDependenceKindTy { <a href="#a3623ee2be26dfee55ab285d3066dca60">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> kind for RTL. <a href="#a3623ee2be26dfee55ab285d3066dca60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">WorksharingLoopType { <a href="#ab6fb146c332fd3f3d677ee65081fe669">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A type of worksharing loop construct. <a href="#ab6fb146c332fd3f3d677ee65081fe669">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TraitSet { <a href="#ac053ab007366c857887d939adbeea976">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OpenMP Context related IDs and helpers. <a href="#ac053ab007366c857887d939adbeea976">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TraitSelector { <a href="#aca4e3fef9c14d0817ff403bcc1ccd403">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IDs for all OpenMP context selector trait (device={kind/isa...}/...). <a href="#aca4e3fef9c14d0817ff403bcc1ccd403">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TraitProperty { <a href="#aed19c754b6dc51a7f084d621b4043788">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IDs for all OpenMP context trait properties (host/gpu/bsc/llvm/...) <a href="#aed19c754b6dc51a7f084d621b4043788">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OMPTgtExecModeFlags : unsigned char { <a href="#aa0c0d79dafb0d22308ce48808689f430">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae75c7313e5efcab9a8a684a1a0b8b3e6">getLeafConstructs</a> (Directive D)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaadc3f38b9cc1d217d85fbd4085574a4">getLeafConstructsOrSelf</a> (Directive D)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a433702fa6f12e3710e21ed0fde2a69b0">getLeafOrCompositeConstructs</a> (Directive D, SmallVectorImpl&lt; Directive &gt; &amp;Output)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9205d579e79767f52c5af57c94d2be74">getCompoundConstruct</a> (ArrayRef&lt; Directive &gt; Parts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9db106bceba28187ada1879719bfbfff">isLeafConstruct</a> (Directive D)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61ef13844d0a136295d9a3acfcf51363">isCompositeConstruct</a> (Directive D)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1476d3d3c5a52a8d7ed817cf86bd835c">isCombinedConstruct</a> (Directive D)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a593088dc872abe1e628c49f8e0b45359">canHaveIterator</a> (Clause C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Can clause C have an iterator-modifier. <a href="#a593088dc872abe1e628c49f8e0b45359">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b170907f3cef11ef1e5d5f9b692edd4">getOpenMPVersions</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7e099354c93867323bca88df83c40b2">prettifyFunctionName</a> (StringRef FunctionName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a nicer version of a function name for humans to look at. <a href="#ad7e099354c93867323bca88df83c40b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36c152217dc69b5295561b2f99c52c17">deconstructOpenMPKernelName</a> (StringRef KernelName, unsigned &amp;LineNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deconstruct an OpenMP kernel name into the parent function name and the line number. <a href="#a36c152217dc69b5295561b2f99c52c17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae88215d4ed5233e9eb893fded3634787">getAllAssumeClauseOptions</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f05e02abd566f6ed4177e35d547e6cb">LLVM_ENABLE_BITMASK_ENUMS_IN_NAMESPACE</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac053ab007366c857887d939adbeea976">TraitSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfc882779f1a9040b8127ccfbed46f71">getOpenMPContextTraitSetKind</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse <span class="doxyComputerOutput">Str</span> and return the trait set it matches or TraitSet::invalid. <a href="#adfc882779f1a9040b8127ccfbed46f71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac053ab007366c857887d939adbeea976">TraitSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a4968175aed3fd3117b6c374012c8b7">getOpenMPContextTraitSetForSelector</a> (TraitSelector Selector)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the trait set for which <span class="doxyComputerOutput">Selector</span> is a selector. <a href="#a5a4968175aed3fd3117b6c374012c8b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac053ab007366c857887d939adbeea976">TraitSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ab910ced9f2e14f0c3b7a176ab5fe45">getOpenMPContextTraitSetForProperty</a> (TraitProperty Property)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the trait set for which <span class="doxyComputerOutput">Property</span> is a property. <a href="#a6ab910ced9f2e14f0c3b7a176ab5fe45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88d499b1533b1970641f7459a35ec40f">getOpenMPContextTraitSetName</a> (TraitSet Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a textual representation of the trait set <span class="doxyComputerOutput">Kind</span>. <a href="#a88d499b1533b1970641f7459a35ec40f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aca4e3fef9c14d0817ff403bcc1ccd403">TraitSelector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab11968aae3de226efd5e696f3e301489">getOpenMPContextTraitSelectorKind</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse <span class="doxyComputerOutput">Str</span> and return the trait set it matches or TraitSelector::invalid. <a href="#ab11968aae3de226efd5e696f3e301489">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aca4e3fef9c14d0817ff403bcc1ccd403">TraitSelector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1fa08b331c261d3acc12d3821b77b2f">getOpenMPContextTraitSelectorForProperty</a> (TraitProperty Property)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the trait selector for which <span class="doxyComputerOutput">Property</span> is a property. <a href="#ac1fa08b331c261d3acc12d3821b77b2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac9deff370f461cf45ef50d6c3bc1485">getOpenMPContextTraitSelectorName</a> (TraitSelector Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a textual representation of the trait selector <span class="doxyComputerOutput">Kind</span>. <a href="#aac9deff370f461cf45ef50d6c3bc1485">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aed19c754b6dc51a7f084d621b4043788">TraitProperty</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa858eb81861028c735e0b1df1800cc41">getOpenMPContextTraitPropertyKind</a> (TraitSet Set, TraitSelector Selector, StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse <span class="doxyComputerOutput">Str</span> and return the trait property it matches in the set <span class="doxyComputerOutput">Set</span> and selector <span class="doxyComputerOutput">Selector</span> or TraitProperty::invalid. <a href="#aa858eb81861028c735e0b1df1800cc41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aed19c754b6dc51a7f084d621b4043788">TraitProperty</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2fc3a53ac7c2cad1be2ce939074d2cc">getOpenMPContextTraitPropertyForSelector</a> (TraitSelector Selector)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the trait property for a singleton selector <span class="doxyComputerOutput">Selector</span>. <a href="#ac2fc3a53ac7c2cad1be2ce939074d2cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9716757628bb15b0930b25325b5edb10">getOpenMPContextTraitPropertyName</a> (TraitProperty Kind, StringRef RawString)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a textual representation of the trait property <span class="doxyComputerOutput">Kind</span>, which might be the raw string we parsed (<span class="doxyComputerOutput">RawString</span>) if we do not translate the property into a (distinct) enum. <a href="#a9716757628bb15b0930b25325b5edb10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2291dd056f533b117fc595f727cda8e4">getOpenMPContextTraitPropertyFullName</a> (TraitProperty Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a textual representation of the trait property <span class="doxyComputerOutput">Kind</span> with selector and set name included. <a href="#a2291dd056f533b117fc595f727cda8e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a087c007cbe4348d47c1d535dfba371e3">listOpenMPContextTraitSets</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a string listing all trait sets. <a href="#a087c007cbe4348d47c1d535dfba371e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4c992ba9c000aebf3cd1e92727a1338">listOpenMPContextTraitSelectors</a> (TraitSet Set)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a string listing all trait selectors for <span class="doxyComputerOutput">Set</span>. <a href="#ab4c992ba9c000aebf3cd1e92727a1338">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7fd2cc7189961b174f666feadb691fb">listOpenMPContextTraitProperties</a> (TraitSet Set, TraitSelector Selector)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a string listing all trait properties for <span class="doxyComputerOutput">Set</span> and <span class="doxyComputerOutput">Selector</span>. <a href="#af7fd2cc7189961b174f666feadb691fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32fcac928737340d2c5702ea9f2706cc">isValidTraitSelectorForTraitSet</a> (TraitSelector Selector, TraitSet Set, bool &amp;AllowsTraitScore, bool &amp;RequiresProperty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#a32fcac928737340d2c5702ea9f2706cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af453d24ec3a64b23168a46d49aadfc7f">isValidTraitPropertyForTraitSetAndSelector</a> (TraitProperty Property, TraitSelector Selector, TraitSet Set)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">Property</span> can be nested in <span class="doxyComputerOutput">Selector</span> and <span class="doxyComputerOutput">Set</span>. <a href="#af453d24ec3a64b23168a46d49aadfc7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af416d75b9a8863d8e262d00743dc66f7">isVariantApplicableInContext</a> (const VariantMatchInfo &amp;VMI, const OMPContext &amp;Ctx, bool DeviceSetOnly=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">VMI</span> is applicable in <span class="doxyComputerOutput">Ctx</span>, that is, all traits required by <span class="doxyComputerOutput">VMI</span> are available in the OpenMP context <span class="doxyComputerOutput">Ctx</span>. <a href="#af416d75b9a8863d8e262d00743dc66f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fe8accb4198eb111067fe7c4bb544dd">getBestVariantMatchForContext</a> (const SmallVectorImpl&lt; VariantMatchInfo &gt; &amp;VMIs, const OMPContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the index (into <span class="doxyComputerOutput">VMIs</span>) of the variant with the highest score from the ones applicble in <span class="doxyComputerOutput">Ctx</span>. <a href="#a7fe8accb4198eb111067fe7c4bb544dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned wavesize&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/omp/gv">GV</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a54d82933792ec7eef3f24eb847c6acd9">getAMDGPUGridValues</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a039c806c0a203f470ea11b6932402c">containsOpenMP</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to determine if <span class="doxyComputerOutput">M</span> contains OpenMP. <a href="#a1a039c806c0a203f470ea11b6932402c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a138a1ab10971c55c181b7f23b60e4582">isOpenMPDevice</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to determine if <span class="doxyComputerOutput">M</span> is a OpenMP target offloading device module. <a href="#a138a1ab10971c55c181b7f23b60e4582">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbaec5588449adc75116f4cad3997a03">isOpenMPKernel</a> (Function &amp;Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true iff <span class="doxyComputerOutput">Fn</span> is an OpenMP GPU kernel; <span class="doxyComputerOutput">Fn</span> has the "kernel" attribute. <a href="#adbaec5588449adc75116f4cad3997a03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa9934fab566f410c639070bf0d60f10f">KernelSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f2eade374bf61ed94ab98b04803a079">getDeviceKernels</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get OpenMP device kernels in <span class="doxyComputerOutput">M</span>. <a href="#a7f2eade374bf61ed94ab98b04803a079">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/omp/assumptionclausemappinginfo">AssumptionClauseMappingInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0b1d3bf5e80bea8b3b6180586e1c96b">AssumptionClauseMappings</a>[] = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All known assume clauses. <a href="#ad0b1d3bf5e80bea8b3b6180586e1c96b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/omp/gv">GV</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34b491de92222a321fa120eb158b22b9">AMDGPUGridValues64</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> GPUs. <a href="#a34b491de92222a321fa120eb158b22b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/omp/gv">GV</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43060ccb6734ae95b07c8baf6ab37910">AMDGPUGridValues32</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/omp/gv">GV</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82196e4d5e3224c1cdd60f16e40af476">NVPTXGridValues</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For Nvidia GPUs. <a href="#a82196e4d5e3224c1cdd60f16e40af476">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Typedefs

### Kernel {#ab07e7d76494438d05bf51cd36ba5a795}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::omp::Kernel =  Function *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Summary of a kernel (=entry point for target offloading).</p>

<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/openmpopt-h">OpenMPOpt.h</a>.</p>

</div>
</div>

### KernelSet {#aa9934fab566f410c639070bf0d60f10f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::omp::KernelSet =  SetVector&lt;Kernel&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of kernels in the module.</p>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/openmpopt-h">OpenMPOpt.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### AddressSpace {#a8c6f525466cc262e00c409c31f9a4272}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::omp::AddressSpace : unsigned</td>
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
<td class="doxyEnumItemName">Generic<a id="a8c6f525466cc262e00c409c31f9a4272a8045a0a6c688b0635e3caccc408a1446"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Global<a id="a8c6f525466cc262e00c409c31f9a4272a4cc6684df7b4a92b1dec6fce3264fac8"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Shared<a id="a8c6f525466cc262e00c409c31f9a4272aa6156ea9d66fef24e87e841fbabf7cca"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Constant<a id="a8c6f525466cc262e00c409c31f9a4272acb17869fe51048b5a5c4c6106551a255"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Local<a id="a8c6f525466cc262e00c409c31f9a4272a509820290d57f333403f490dde7316f4"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompconstants-h">OMPConstants.h</a>.</p>

</div>
</div>

### DefaultKind {#adb7b881301debe51ac707e2e08e25035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::omp::DefaultKind </td>
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

<p>IDs for the different default kinds.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompconstants-h">OMPConstants.h</a>.</p>

</div>
</div>

### ICVInitValue {#a58b53550e1be2a034095e3e31fc82d66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::omp::ICVInitValue </td>
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


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompconstants-h">OMPConstants.h</a>.</p>

</div>
</div>

### IdentFlag {#a0e821d8251c97d66ca185efe2f8ffde2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::omp::IdentFlag </td>
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

<p>IDs for all omp runtime library ident_t flag encodings (see their defintion in openmp/runtime/src/kmp.h).</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompconstants-h">OMPConstants.h</a>.</p>

</div>
</div>

### InternalControlVar {#a4608c581e6f18962661f7fc39ea88da2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::omp::InternalControlVar </td>
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

<p>IDs for all Internal Control Variables (ICVs).</p>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompconstants-h">OMPConstants.h</a>.</p>

</div>
</div>

### OMPAtomicCompareOp {#acb593a387130148478f3c30af0d322df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::omp::OMPAtomicCompareOp : unsigned</td>
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

<p>Atomic compare operations. Currently OpenMP only supports ==, &gt;, and &lt;.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EQ<a id="acb593a387130148478f3c30af0d322dfa2dcbad7477fd40561e8b8198f173bd47"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MIN<a id="acb593a387130148478f3c30af0d322dface31e2a082d17e038fcc6e3006166653"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAX<a id="acb593a387130148478f3c30af0d322dfa26a4b44a837bf97b972628509912b4a5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompconstants-h">OMPConstants.h</a>.</p>

</div>
</div>

### OMPInteropType {#afeaad9a7fc12d9246c2e42578fddc718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::omp::OMPInteropType </td>
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
<td class="doxyEnumItemName">Unknown<a id="afeaad9a7fc12d9246c2e42578fddc718a88183b946cc5f0e8c96b2e66e1c74a7e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Target<a id="afeaad9a7fc12d9246c2e42578fddc718ac41a31890959544c6523af684561abe5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TargetSync<a id="afeaad9a7fc12d9246c2e42578fddc718a61661015b3c5569b2ffa9118086c9679"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>



:::info
<p>This needs to be kept in sync with interop.h enum kmp_interop_type_t.:</p>
:::


<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompconstants-h">OMPConstants.h</a>.</p>

</div>
</div>

### OMPScheduleType {#a231ea6a9a0009e38969a20d4293119c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::omp::OMPScheduleType </td>
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
<td class="doxyEnumItemName">None<a id="a231ea6a9a0009e38969a20d4293119c7a6adf97f83acf6453d4a6a4b1070f3754"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseStaticChunked<a id="a231ea6a9a0009e38969a20d4293119c7af54e7eea282c868aa67914573df2558f"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseStatic<a id="a231ea6a9a0009e38969a20d4293119c7aecba1cdf984063a67c869dbb94d19dd3"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseDynamicChunked<a id="a231ea6a9a0009e38969a20d4293119c7a9e8280caae3ba6110d4f0061ad3dce1c"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseGuidedChunked<a id="a231ea6a9a0009e38969a20d4293119c7aa9e644958c4830585ae78527092ea4fd"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseRuntime<a id="a231ea6a9a0009e38969a20d4293119c7afd0872ecd4e82f3caa0ea44584a05144"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseAuto<a id="a231ea6a9a0009e38969a20d4293119c7a377f624764cdf5386a71e8efa9a1033d"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseTrapezoidal<a id="a231ea6a9a0009e38969a20d4293119c7a2d93fb340b6b58d28771b570fc68da84"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseGreedy<a id="a231ea6a9a0009e38969a20d4293119c7abb6d65fa62198a898f0b36eba922ede5"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseBalanced<a id="a231ea6a9a0009e38969a20d4293119c7a3c09d00199d64e2f7eb08082a7b6b598"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseGuidedIterativeChunked<a id="a231ea6a9a0009e38969a20d4293119c7a6097a8774ee56bd544db5668747dbef3"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseGuidedAnalyticalChunked<a id="a231ea6a9a0009e38969a20d4293119c7a8df314abcb15d43d59d8a3ea7c54cb10"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseSteal<a id="a231ea6a9a0009e38969a20d4293119c7ab9dd338a9e4b4d1c74191892dd28abe2"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseStaticBalancedChunked<a id="a231ea6a9a0009e38969a20d4293119c7a3f4e265045794ed0323bcb579c3269f2"></a></td>
<td class="doxyEnumItemDescription"> (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseGuidedSimd<a id="a231ea6a9a0009e38969a20d4293119c7acecd17ad7e1609e795c3d82c6317325b"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseRuntimeSimd<a id="a231ea6a9a0009e38969a20d4293119c7ab8e66c863338f428b072f163e43f65e8"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseDistributeChunked<a id="a231ea6a9a0009e38969a20d4293119c7ac70adae3024fca0135080345bdb2c4e7"></a></td>
<td class="doxyEnumItemDescription"> (= 27)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseDistribute<a id="a231ea6a9a0009e38969a20d4293119c7aa58114c7aed29634af74ede768ccc43d"></a></td>
<td class="doxyEnumItemDescription"> (= 28)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ModifierUnordered<a id="a231ea6a9a0009e38969a20d4293119c7ab20e79b6bbe8e4d736ed588ad5f3c9c7"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 5))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ModifierOrdered<a id="a231ea6a9a0009e38969a20d4293119c7a00614ac33e4c92484ae08314d48cf8b8"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 6))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ModifierNomerge<a id="a231ea6a9a0009e38969a20d4293119c7ac27c2b6bec1b62700061fe2a196d8d97"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 7))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ModifierMonotonic<a id="a231ea6a9a0009e38969a20d4293119c7a0f712a4e8c3670472ef75bdbfde786f8"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 29))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ModifierNonmonotonic<a id="a231ea6a9a0009e38969a20d4293119c7adab874a059e33d5599603a11894ab29e"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 30))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OrderingMask<a id="a231ea6a9a0009e38969a20d4293119c7a24aa47f8f30b2c6f7ebf19c2432e14c1"></a></td>
<td class="doxyEnumItemDescription"> (= ModifierUnordered | ModifierOrdered | ModifierNomerge)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MonotonicityMask<a id="a231ea6a9a0009e38969a20d4293119c7a5690795030711d5682365ed61cbe81b6"></a></td>
<td class="doxyEnumItemDescription"> (= ModifierMonotonic | ModifierNonmonotonic)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ModifierMask<a id="a231ea6a9a0009e38969a20d4293119c7a4aabfa64277fa15805937e3812fa1161"></a></td>
<td class="doxyEnumItemDescription"> (= OrderingMask | MonotonicityMask)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnorderedStaticChunked<a id="a231ea6a9a0009e38969a20d4293119c7adfd02d2fed222f2c28301f5ac837f2b2"></a></td>
<td class="doxyEnumItemDescription"> (= BaseStaticChunked | ModifierUnordered)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnorderedStatic<a id="a231ea6a9a0009e38969a20d4293119c7a5ced2def0c3f656428eb2144b4aaf6fb"></a></td>
<td class="doxyEnumItemDescription"> (= BaseStatic | ModifierUnordered)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnorderedDynamicChunked<a id="a231ea6a9a0009e38969a20d4293119c7aeb07fdc72df93e1f129f8ef0fa6cdaa2"></a></td>
<td class="doxyEnumItemDescription"> (= BaseDynamicChunked | ModifierUnordered)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnorderedGuidedChunked<a id="a231ea6a9a0009e38969a20d4293119c7ad7cb643189718fba3760db5bcb5e9856"></a></td>
<td class="doxyEnumItemDescription"> (= BaseGuidedChunked | ModifierUnordered)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnorderedRuntime<a id="a231ea6a9a0009e38969a20d4293119c7a3766f17f591a16552940e68a9206a109"></a></td>
<td class="doxyEnumItemDescription"> (= BaseRuntime | ModifierUnordered)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnorderedAuto<a id="a231ea6a9a0009e38969a20d4293119c7ace336b30276699c8ad3f28c7296ae69c"></a></td>
<td class="doxyEnumItemDescription"> (= BaseAuto | ModifierUnordered)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnorderedTrapezoidal<a id="a231ea6a9a0009e38969a20d4293119c7ae046186587a5833e23d9270c35af85b1"></a></td>
<td class="doxyEnumItemDescription"> (= BaseTrapezoidal | ModifierUnordered)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnorderedGreedy<a id="a231ea6a9a0009e38969a20d4293119c7a38a9fe7b93a08dd2fdb40710633ff20e"></a></td>
<td class="doxyEnumItemDescription"> (= BaseGreedy | ModifierUnordered)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnorderedBalanced<a id="a231ea6a9a0009e38969a20d4293119c7ab0ca5a5d5a0a48d1d0d7128090747b9b"></a></td>
<td class="doxyEnumItemDescription"> (= BaseBalanced | ModifierUnordered)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnorderedGuidedIterativeChunked<a id="a231ea6a9a0009e38969a20d4293119c7a39599fc5486afadef41009e1fb27600e"></a></td>
<td class="doxyEnumItemDescription">
 (=
      BaseGuidedIterativeChunked | ModifierUnordered)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnorderedGuidedAnalyticalChunked<a id="a231ea6a9a0009e38969a20d4293119c7a1cc61e9c8ede152165c582e6cdb49b5e"></a></td>
<td class="doxyEnumItemDescription">
 (=
      BaseGuidedAnalyticalChunked | ModifierUnordered)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnorderedSteal<a id="a231ea6a9a0009e38969a20d4293119c7a79f54709b96f9cf497c239ceeedfccb8"></a></td>
<td class="doxyEnumItemDescription"> (= BaseSteal | ModifierUnordered)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnorderedStaticBalancedChunked<a id="a231ea6a9a0009e38969a20d4293119c7a8a3ce6661aad31cc29e3c986d95c3b80"></a></td>
<td class="doxyEnumItemDescription">
 (=
      BaseStaticBalancedChunked | ModifierUnordered)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnorderedGuidedSimd<a id="a231ea6a9a0009e38969a20d4293119c7a6102400852d050aeb45f54e39cd6dbbc"></a></td>
<td class="doxyEnumItemDescription"> (= BaseGuidedSimd | ModifierUnordered)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnorderedRuntimeSimd<a id="a231ea6a9a0009e38969a20d4293119c7a4bc5b1133831ba3fc59a2359a81a049a"></a></td>
<td class="doxyEnumItemDescription"> (= BaseRuntimeSimd | ModifierUnordered)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OrderedStaticChunked<a id="a231ea6a9a0009e38969a20d4293119c7a45e59530303d8f21b9f68d067b700046"></a></td>
<td class="doxyEnumItemDescription"> (= BaseStaticChunked | ModifierOrdered)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OrderedStatic<a id="a231ea6a9a0009e38969a20d4293119c7a921ff3d852775c7d08ef3e8ab71fd827"></a></td>
<td class="doxyEnumItemDescription"> (= BaseStatic | ModifierOrdered)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OrderedDynamicChunked<a id="a231ea6a9a0009e38969a20d4293119c7ab4930c214ad4ac5c3d1c75d267eb38a4"></a></td>
<td class="doxyEnumItemDescription"> (= BaseDynamicChunked | ModifierOrdered)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OrderedGuidedChunked<a id="a231ea6a9a0009e38969a20d4293119c7a0d889968e05ad491297781c12f044670"></a></td>
<td class="doxyEnumItemDescription"> (= BaseGuidedChunked | ModifierOrdered)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OrderedRuntime<a id="a231ea6a9a0009e38969a20d4293119c7ac9213ec16587c17730f2d8e7723f692d"></a></td>
<td class="doxyEnumItemDescription"> (= BaseRuntime | ModifierOrdered)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OrderedAuto<a id="a231ea6a9a0009e38969a20d4293119c7a89d1cc67c0e0820b5ed851176567e17c"></a></td>
<td class="doxyEnumItemDescription"> (= BaseAuto | ModifierOrdered)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OrderdTrapezoidal<a id="a231ea6a9a0009e38969a20d4293119c7abd79f878aa88119d9feabd482bbdb1ca"></a></td>
<td class="doxyEnumItemDescription"> (= BaseTrapezoidal | ModifierOrdered)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OrderedDistributeChunked<a id="a231ea6a9a0009e38969a20d4293119c7ab32d50fad87058c7739867aa6c7f05b0"></a></td>
<td class="doxyEnumItemDescription"> (= BaseDistributeChunked | ModifierOrdered)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OrderedDistribute<a id="a231ea6a9a0009e38969a20d4293119c7ac1d5528b6ced491ba685b8d29ce649c2"></a></td>
<td class="doxyEnumItemDescription"> (= BaseDistribute | ModifierOrdered)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NomergeUnorderedStaticChunked<a id="a231ea6a9a0009e38969a20d4293119c7abe272c1e3dfad2cfd9e94438ac753094"></a></td>
<td class="doxyEnumItemDescription">
 (=
      BaseStaticChunked | ModifierUnordered | ModifierNomerge)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NomergeUnorderedStatic<a id="a231ea6a9a0009e38969a20d4293119c7a7dadea7f8d895bea2f79d77bc784b532"></a></td>
<td class="doxyEnumItemDescription">
 (=
      BaseStatic | ModifierUnordered | ModifierNomerge)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NomergeUnorderedDynamicChunked<a id="a231ea6a9a0009e38969a20d4293119c7af9fd0011f843a54b100f1410a42c525a"></a></td>
<td class="doxyEnumItemDescription">
 (=
      BaseDynamicChunked | ModifierUnordered | ModifierNomerge)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NomergeUnorderedGuidedChunked<a id="a231ea6a9a0009e38969a20d4293119c7aee4b149cf5ae41603e163ae581365f98"></a></td>
<td class="doxyEnumItemDescription">
 (=
      BaseGuidedChunked | ModifierUnordered | ModifierNomerge)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NomergeUnorderedRuntime<a id="a231ea6a9a0009e38969a20d4293119c7a0262be002813b7ad31cc7d6200804759"></a></td>
<td class="doxyEnumItemDescription">
 (=
      BaseRuntime | ModifierUnordered | ModifierNomerge)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NomergeUnorderedAuto<a id="a231ea6a9a0009e38969a20d4293119c7a711e6dab1b42b1c5451a7aafe2c1e21e"></a></td>
<td class="doxyEnumItemDescription"> (= BaseAuto | ModifierUnordered | ModifierNomerge)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NomergeUnorderedTrapezoidal<a id="a231ea6a9a0009e38969a20d4293119c7a44a9325b9b228081d8841907454a44ef"></a></td>
<td class="doxyEnumItemDescription">
 (=
      BaseTrapezoidal | ModifierUnordered | ModifierNomerge)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NomergeUnorderedGreedy<a id="a231ea6a9a0009e38969a20d4293119c7a0158fb808d882c7853b20bf3d759238a"></a></td>
<td class="doxyEnumItemDescription">
 (=
      BaseGreedy | ModifierUnordered | ModifierNomerge)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NomergeUnorderedBalanced<a id="a231ea6a9a0009e38969a20d4293119c7a1d024db3d31d3f2afbc0f8d7d2647ef9"></a></td>
<td class="doxyEnumItemDescription">
 (=
      BaseBalanced | ModifierUnordered | ModifierNomerge)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NomergeUnorderedGuidedIterativeChunked<a id="a231ea6a9a0009e38969a20d4293119c7a86d90f56bf34bf9eed31f6676cfe2200"></a></td>
<td class="doxyEnumItemDescription">
 (=
      BaseGuidedIterativeChunked | ModifierUnordered | ModifierNomerge)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NomergeUnorderedGuidedAnalyticalChunked<a id="a231ea6a9a0009e38969a20d4293119c7a6b0f13196284756141d7a1fb003c7ad7"></a></td>
<td class="doxyEnumItemDescription">
 (=
      BaseGuidedAnalyticalChunked | ModifierUnordered | ModifierNomerge)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NomergeUnorderedSteal<a id="a231ea6a9a0009e38969a20d4293119c7a57c8ef07508f364479cb0df759e9aa9d"></a></td>
<td class="doxyEnumItemDescription">
 (=
      BaseSteal | ModifierUnordered | ModifierNomerge)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NomergeOrderedStaticChunked<a id="a231ea6a9a0009e38969a20d4293119c7a8a8a4a010edce2d7bbcea890feb6890d"></a></td>
<td class="doxyEnumItemDescription">
 (=
      BaseStaticChunked | ModifierOrdered | ModifierNomerge)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NomergeOrderedStatic<a id="a231ea6a9a0009e38969a20d4293119c7a514f0e7b2d577f06c98896a8a094d09e"></a></td>
<td class="doxyEnumItemDescription"> (= BaseStatic | ModifierOrdered | ModifierNomerge)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NomergeOrderedDynamicChunked<a id="a231ea6a9a0009e38969a20d4293119c7a88acf78220be4f9cba9d504348338434"></a></td>
<td class="doxyEnumItemDescription">
 (=
      BaseDynamicChunked | ModifierOrdered | ModifierNomerge)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NomergeOrderedGuidedChunked<a id="a231ea6a9a0009e38969a20d4293119c7a8d3bdcd26e9de2b98205ae5774042717"></a></td>
<td class="doxyEnumItemDescription">
 (=
      BaseGuidedChunked | ModifierOrdered | ModifierNomerge)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NomergeOrderedRuntime<a id="a231ea6a9a0009e38969a20d4293119c7a8f0d655fb83490a9e75782c6402110d8"></a></td>
<td class="doxyEnumItemDescription">
 (=
      BaseRuntime | ModifierOrdered | ModifierNomerge)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NomergeOrderedAuto<a id="a231ea6a9a0009e38969a20d4293119c7a0caa7abe8bdddedc4178cd73a4ac40b6"></a></td>
<td class="doxyEnumItemDescription"> (= BaseAuto | ModifierOrdered | ModifierNomerge)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NomergeOrderedTrapezoidal<a id="a231ea6a9a0009e38969a20d4293119c7a46f4e9d5112df3ad08bc51fcff86bbca"></a></td>
<td class="doxyEnumItemDescription">
 (=
      BaseTrapezoidal | ModifierOrdered | ModifierNomerge)
</td>
</tr>

</table>
</dd>
</dl>



:::info
<p>This needs to be kept in sync with kmp.h enum sched_type. Todo: Update kmp.h to include this file, and remove the enums in kmp.h</p>
:::


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompconstants-h">OMPConstants.h</a>.</p>

</div>
</div>

### OMPTgtExecModeFlags {#aa0c0d79dafb0d22308ce48808689f430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::omp::OMPTgtExecModeFlags : unsigned char</td>
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
<td class="doxyEnumItemName">OMP_TGT_EXEC_MODE_GENERIC<a id="aa0c0d79dafb0d22308ce48808689f430afa583a38ff705195c9bce9dec0c5eff8"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_TGT_EXEC_MODE_SPMD<a id="aa0c0d79dafb0d22308ce48808689f430a338c51f37ed4e4b2c9973a383c566c19"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_TGT_EXEC_MODE_GENERIC_SPMD<a id="aa0c0d79dafb0d22308ce48808689f430a3a7132dd26b3986109b8fffccd140f41"></a></td>
<td class="doxyEnumItemDescription">
 (=
      OMP_TGT_EXEC_MODE_GENERIC | OMP_TGT_EXEC_MODE_SPMD)
</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompdeviceconstants-h">OMPDeviceConstants.h</a>.</p>

</div>
</div>

### OpenMPOffloadingReservedDeviceIDs {#a032f350e065d895f441c08affb57c2be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::omp::OpenMPOffloadingReservedDeviceIDs </td>
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
<td class="doxyEnumItemName">OMP_DEVICEID_UNDEF<a id="a032f350e065d895f441c08affb57c2bea1e9b5a418e27440a8248a21894ff2932"></a></td>
<td class="doxyEnumItemDescription">Device <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> if the device was not defined, runtime should get it from environment variables in the spec (= -1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompconstants-h">OMPConstants.h</a>.</p>

</div>
</div>

### OpenMPOffloadMappingFlags {#a02d7a52c47f2d71a111aef9d4fb70ecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::omp::OpenMPOffloadMappingFlags : uint64_t</td>
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

<p>Values for bit flags used to specify the mapping type for offloading.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_MAP_NONE<a id="a02d7a52c47f2d71a111aef9d4fb70ecbabfda9a63c9b7f11edcad1dc82149b98e"></a></td>
<td class="doxyEnumItemDescription">No flags (= 0x0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_MAP_TO<a id="a02d7a52c47f2d71a111aef9d4fb70ecba07cc0a659e39b41fe392c86bc11cd0ac"></a></td>
<td class="doxyEnumItemDescription">Allocate memory on the device and move data from host to device (= 0x01)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_MAP_FROM<a id="a02d7a52c47f2d71a111aef9d4fb70ecbad7002643132cb21f2109913d4c7d7c92"></a></td>
<td class="doxyEnumItemDescription">Allocate memory on the device and move data from device to host (= 0x02)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_MAP_ALWAYS<a id="a02d7a52c47f2d71a111aef9d4fb70ecbacdf40f046e81e20bed803a99988b9b69"></a></td>
<td class="doxyEnumItemDescription">Always perform the requested mapping action on the element, even if it was already mapped before (= 0x04)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_MAP_DELETE<a id="a02d7a52c47f2d71a111aef9d4fb70ecbab4f086d24865ba8bfb2761e61ff7699c"></a></td>
<td class="doxyEnumItemDescription">Delete the element from the device environment, ignoring the current reference count associated with the element (= 0x08)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_MAP_PTR_AND_OBJ<a id="a02d7a52c47f2d71a111aef9d4fb70ecba67bb5754d8a930a0abad5e820064be2d"></a></td>
<td class="doxyEnumItemDescription">The element being mapped is a pointer-pointee pair; both the pointer and the pointee should be mapped (= 0x10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_MAP_TARGET_PARAM<a id="a02d7a52c47f2d71a111aef9d4fb70ecba732ea9b86ca290313731e1222052ce1b"></a></td>
<td class="doxyEnumItemDescription">This flags signals that the base address of an entry should be passed to the target kernel as an argument (= 0x20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_MAP_RETURN_PARAM<a id="a02d7a52c47f2d71a111aef9d4fb70ecba5809336cf30db5e602df51986460f649"></a></td>
<td class="doxyEnumItemDescription">Signal that the runtime library has to return the device pointer in the current position for the data being mapped (= 0x40)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_MAP_PRIVATE<a id="a02d7a52c47f2d71a111aef9d4fb70ecba9a9d48223bc0be9fc043db7cf39c5a70"></a></td>
<td class="doxyEnumItemDescription">This flag signals that the reference being passed is a pointer to private data (= 0x80)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_MAP_LITERAL<a id="a02d7a52c47f2d71a111aef9d4fb70ecba4cff2314e49d9ee10b2b509340185a09"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> the element to the device by value (= 0x100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_MAP_IMPLICIT<a id="a02d7a52c47f2d71a111aef9d4fb70ecba9afda0bbc74e0b0a52a4a4ee6d8d6bae"></a></td>
<td class="doxyEnumItemDescription">Implicit map (= 0x200)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_MAP_CLOSE<a id="a02d7a52c47f2d71a111aef9d4fb70ecba8221e00e56f2d3110db685d1724a67c0"></a></td>
<td class="doxyEnumItemDescription">Close is a hint to the runtime to allocate memory close to the target device (= 0x400)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_MAP_PRESENT<a id="a02d7a52c47f2d71a111aef9d4fb70ecba7760c660d78f028453fcb93a578d33bb"></a></td>
<td class="doxyEnumItemDescription">0x800 is reserved for compatibility with XLC (= 0x1000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_MAP_OMPX_HOLD<a id="a02d7a52c47f2d71a111aef9d4fb70ecba36a26f3f149ebca46d73370d0a982cdf"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_MAP_NON_CONTIG<a id="a02d7a52c47f2d71a111aef9d4fb70ecba2d02fcb9be426561e88eefb10b43523a"></a></td>
<td class="doxyEnumItemDescription">Signal that the runtime library should use args as an array of descriptor_dim pointers and use args_size as dims (= 0x100000000000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_MAP_MEMBER_OF<a id="a02d7a52c47f2d71a111aef9d4fb70ecbaa450a4e59275b4081714a7a28f217e6c"></a></td>
<td class="doxyEnumItemDescription">The 16 MSBs of the flags indicate whether the entry is member of some struct/class (= 0xffff000000000000)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompconstants-h">OMPConstants.h</a>.</p>

</div>
</div>

### RTLDependenceKindTy {#a3623ee2be26dfee55ab285d3066dca60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::omp::RTLDependenceKindTy </td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a> kind for RTL.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DepUnknown<a id="a3623ee2be26dfee55ab285d3066dca60a3d366df3664d3884176801dc8bf196e0"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DepIn<a id="a3623ee2be26dfee55ab285d3066dca60af8744a9f712caccc107a51d7f240c854"></a></td>
<td class="doxyEnumItemDescription"> (= 0x01)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DepInOut<a id="a3623ee2be26dfee55ab285d3066dca60a2be171e8c6766e8a6914267236e17ade"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DepMutexInOutSet<a id="a3623ee2be26dfee55ab285d3066dca60a6e8dfb39471e996776ce3f17fce2df0b"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DepInOutSet<a id="a3623ee2be26dfee55ab285d3066dca60ae7312468c4773eaf2b440b60991980d8"></a></td>
<td class="doxyEnumItemDescription"> (= 0x8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DepOmpAllMem<a id="a3623ee2be26dfee55ab285d3066dca60af9f57ddaa7ffbba5a1652120e7aa7950"></a></td>
<td class="doxyEnumItemDescription"> (= 0x80)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompconstants-h">OMPConstants.h</a>.</p>

</div>
</div>

### RTLDependInfoFields {#a16d7c5f77008a84ae20bf4a5c41e51f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::omp::RTLDependInfoFields </td>
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

<p>Fields ids in kmp_depend_info record.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BaseAddr<a id="a16d7c5f77008a84ae20bf4a5c41e51f0a4a795cf4295903cb3e7dee5f6496e9b2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Len<a id="a16d7c5f77008a84ae20bf4a5c41e51f0ae88b4464fe326a51e6e6dfae28dd536d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Flags<a id="a16d7c5f77008a84ae20bf4a5c41e51f0a4ea7801f17a4e5485e8b050c052fb443"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompconstants-h">OMPConstants.h</a>.</p>

</div>
</div>

### RuntimeFunction {#a4c503140c7f851151906d85b515330e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::omp::RuntimeFunction </td>
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

<p>IDs for all omp runtime library (RTL) functions.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompconstants-h">OMPConstants.h</a>.</p>

</div>
</div>

### TraitProperty {#aed19c754b6dc51a7f084d621b4043788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::omp::TraitProperty </td>
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

<p>IDs for all OpenMP context trait properties (host/gpu/bsc/llvm/...)</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>.</p>

</div>
</div>

### TraitSelector {#aca4e3fef9c14d0817ff403bcc1ccd403}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::omp::TraitSelector </td>
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

<p>IDs for all OpenMP context selector trait (device={kind/isa...}/...).</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>.</p>

</div>
</div>

### TraitSet {#ac053ab007366c857887d939adbeea976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::omp::TraitSet </td>
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

<p>OpenMP Context related IDs and helpers.</p>


<p>{ IDs for all OpenMP context selector trait sets (construct/device/...).</p>


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>.</p>

</div>
</div>

### WorksharingLoopType {#ab6fb146c332fd3f3d677ee65081fe669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::omp::WorksharingLoopType </td>
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

<p>A type of worksharing loop construct.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ForStaticLoop<a id="ab6fb146c332fd3f3d677ee65081fe669a45663d75b039e00b6412fb82fed8c306"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DistributeStaticLoop<a id="ab6fb146c332fd3f3d677ee65081fe669a8bc669efea4991eb2ae512e9a52c1160"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DistributeForStaticLoop<a id="ab6fb146c332fd3f3d677ee65081fe669ac18623f28e0536cf69308157fa9b3dd0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompconstants-h">OMPConstants.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### canHaveIterator() {#a593088dc872abe1e628c49f8e0b45359}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr bool llvm::omp::canHaveIterator (<a href="/web-llvm/docs/api/classes/llvm/clause">Clause</a> C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Can clause C have an iterator-modifier.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/omp-h">OMP.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### containsOpenMP() {#a1a039c806c0a203f470ea11b6932402c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::omp::containsOpenMP (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to determine if <span class="doxyComputerOutput">M</span> contains OpenMP.</p>

<p>Declaration at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/openmpopt-h">OpenMPOpt.h</a>, definition at line 5957 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpoptcgsccpass/#a9d4366d9c2f6de53d6f2edce548577ab">llvm::OpenMPOptCGSCCPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpoptpass/#ad0812a5ba88f8645505134a108f639b2">llvm::OpenMPOptPass::run</a>.</p>

</div>
</div>

### deconstructOpenMPKernelName() {#a36c152217dc69b5295561b2f99c52c17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::omp::deconstructOpenMPKernelName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> KernelName, unsigned &amp; LineNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deconstruct an OpenMP kernel name into the parent function name and the line number.</p>

<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/omp-cpp">OMP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab996639d406a5466d5c8a1586fb4a9d8">llvm::demangle</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo/#a3e78748236396089e6a27766e44407f9">llvm::TargetRegionEntryInfo::KernelNamePrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a97d45ce069c1a09ca84672df63acf096">llvm::StringRef::rfind</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>


<p>Referenced by <a href="#ad7e099354c93867323bca88df83c40b2">prettifyFunctionName</a>.</p>

</div>
</div>

### getAllAssumeClauseOptions() {#ae88215d4ed5233e9eb893fded3634787}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::omp::getAllAssumeClauseOptions ()</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompassume-h">OMPAssume.h</a>.</p>


<p>Reference <a href="#ad0b1d3bf5e80bea8b3b6180586e1c96b">AssumptionClauseMappings</a>.</p>

</div>
</div>

### getAMDGPUGridValues() {#a54d82933792ec7eef3f24eb847c6acd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned wavesize&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GV &amp; llvm::omp::getAMDGPUGridValues ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompgridvalues-h">OMPGridValues.h</a>.</p>


<p>References <a href="#a43060ccb6734ae95b07c8baf6ab37910">AMDGPUGridValues32</a> and <a href="#a34b491de92222a321fa120eb158b22b9">AMDGPUGridValues64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#ad52342fdd467389643191fdac7abcd40">getGridValue</a>.</p>

</div>
</div>

### getBestVariantMatchForContext() {#a7fe8accb4198eb111067fe7c4bb544dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::omp::getBestVariantMatchForContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/omp/variantmatchinfo">VariantMatchInfo</a> &gt; &amp; VMIs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/omp/ompcontext">OMPContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the index (into <span class="doxyComputerOutput">VMIs</span>) of the variant with the highest score from the ones applicble in <span class="doxyComputerOutput">Ctx</span>.</p>


<p>See llvm::isVariantApplicableInContext.</p>


<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>, definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a6e17f9e532ca4a61804f28091b10b522">llvm::APInt::eq</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#a0776bd50b7c822627400a43977db933b">getVariantMatchScore</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#a05d88c62bda0d2e90b00e2407db9b556">isStrictSubset</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#ad468a923807a048c8f7379f087507651">isVariantApplicableInContextHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a545e8d5dfa1688acea0d0e275b03682f">llvm::APInt::ult</a>.</p>

</div>
</div>

### getCompoundConstruct() {#a9205d579e79767f52c5af57c94d2be74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Directive llvm::omp::getCompoundConstruct (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> &gt; Parts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/omp-cpp">OMP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a7b68be12c974b6b70bc86062f221a344">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="#ae75c7313e5efcab9a8a684a1a0b8b3e6">getLeafConstructs</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a433702fa6f12e3710e21ed0fde2a69b0">getLeafOrCompositeConstructs</a>.</p>

</div>
</div>

### getDeviceKernels() {#a7f2eade374bf61ed94ab98b04803a079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KernelSet llvm::omp::getDeviceKernels (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get OpenMP device kernels in <span class="doxyComputerOutput">M</span>.</p>

<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/openmpopt-h">OpenMPOpt.h</a>, definition at line 5919 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#a2d40c0621205b0cbd5f642d970cbb896">llvm::mdconst::dyn_extract_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#ae44259d9edd71181ea8b89d18f27a967">llvm::MDString::getString</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp/#a70e111a9922abf998a3d7588bf5d8432">isKernelCC</a> and <a href="#adbaec5588449adc75116f4cad3997a03">isOpenMPKernel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpoptcgsccpass/#a9d4366d9c2f6de53d6f2edce548577ab">llvm::OpenMPOptCGSCCPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpoptpass/#ad0812a5ba88f8645505134a108f639b2">llvm::OpenMPOptPass::run</a>.</p>

</div>
</div>

### getLeafConstructs() {#ae75c7313e5efcab9a8a684a1a0b8b3e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Directive &gt; llvm::omp::getLeafConstructs (<a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/omp-cpp">OMP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>.</p>


<p>Referenced by <a href="#a9205d579e79767f52c5af57c94d2be74">getCompoundConstruct</a>, <a href="#aaadc3f38b9cc1d217d85fbd4085574a4">getLeafConstructsOrSelf</a>, <a href="#a1476d3d3c5a52a8d7ed817cf86bd835c">isCombinedConstruct</a> and <a href="#a9db106bceba28187ada1879719bfbfff">isLeafConstruct</a>.</p>

</div>
</div>

### getLeafConstructsOrSelf() {#aaadc3f38b9cc1d217d85fbd4085574a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Directive &gt; llvm::omp::getLeafConstructsOrSelf (<a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/omp-cpp">OMP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> and <a href="#ae75c7313e5efcab9a8a684a1a0b8b3e6">getLeafConstructs</a>.</p>


<p>Referenced by <a href="#a433702fa6f12e3710e21ed0fde2a69b0">getLeafOrCompositeConstructs</a> and <a href="#a61ef13844d0a136295d9a3acfcf51363">isCompositeConstruct</a>.</p>

</div>
</div>

### getLeafOrCompositeConstructs() {#a433702fa6f12e3710e21ed0fde2a69b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Directive &gt; llvm::omp::getLeafOrCompositeConstructs (<a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> D, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> &gt; &amp; Output)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/omp-cpp">OMP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="#a9205d579e79767f52c5af57c94d2be74">getCompoundConstruct</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/omp-cpp/#a50a4b76a4e856e2e4b0e5fe36e7d5e09">getFirstCompositeRange</a>, <a href="#aaadc3f38b9cc1d217d85fbd4085574a4">getLeafConstructsOrSelf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>

</div>
</div>

### getOpenMPContextTraitPropertyForSelector() {#ac2fc3a53ac7c2cad1be2ce939074d2cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TraitProperty llvm::omp::getOpenMPContextTraitPropertyForSelector (<a href="#aca4e3fef9c14d0817ff403bcc1ccd403">TraitSelector</a> Selector)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the trait property for a singleton selector <span class="doxyComputerOutput">Selector</span>.</p>

<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>, definition at line 455 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a> and <a href="#aac9deff370f461cf45ef50d6c3bc1485">getOpenMPContextTraitSelectorName</a>.</p>

</div>
</div>

### getOpenMPContextTraitPropertyFullName() {#a2291dd056f533b117fc595f727cda8e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::omp::getOpenMPContextTraitPropertyFullName (<a href="#aed19c754b6dc51a7f084d621b4043788">TraitProperty</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a textual representation of the trait property <span class="doxyComputerOutput">Kind</span> with selector and set name included.</p>

<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>, definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/omp/ompcontext/#a4d6214c1b52e5b83b8c96f868cfb14f2">llvm::omp::OMPContext::OMPContext</a>.</p>

</div>
</div>

### getOpenMPContextTraitPropertyKind() {#aa858eb81861028c735e0b1df1800cc41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TraitProperty llvm::omp::getOpenMPContextTraitPropertyKind (<a href="#ac053ab007366c857887d939adbeea976">TraitSet</a> Set, <a href="#aca4e3fef9c14d0817ff403bcc1ccd403">TraitSelector</a> Selector, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse <span class="doxyComputerOutput">Str</span> and return the trait property it matches in the set <span class="doxyComputerOutput">Set</span> and selector <span class="doxyComputerOutput">Selector</span> or TraitProperty::invalid.</p>

<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>, definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

### getOpenMPContextTraitPropertyName() {#a9716757628bb15b0930b25325b5edb10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::omp::getOpenMPContextTraitPropertyName (<a href="#aed19c754b6dc51a7f084d621b4043788">TraitProperty</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RawString)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a textual representation of the trait property <span class="doxyComputerOutput">Kind</span>, which might be the raw string we parsed (<span class="doxyComputerOutput">RawString</span>) if we do not translate the property into a (distinct) enum.</p>

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>, definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#ad468a923807a048c8f7379f087507651">isVariantApplicableInContextHelper</a>.</p>

</div>
</div>

### getOpenMPContextTraitSelectorForProperty() {#ac1fa08b331c261d3acc12d3821b77b2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TraitSelector llvm::omp::getOpenMPContextTraitSelectorForProperty (<a href="#aed19c754b6dc51a7f084d621b4043788">TraitProperty</a> Property)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the trait selector for which <span class="doxyComputerOutput">Property</span> is a property.</p>

<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>, definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#a0776bd50b7c822627400a43977db933b">getVariantMatchScore</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#ad468a923807a048c8f7379f087507651">isVariantApplicableInContextHelper</a>.</p>

</div>
</div>

### getOpenMPContextTraitSelectorKind() {#ab11968aae3de226efd5e696f3e301489}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TraitSelector llvm::omp::getOpenMPContextTraitSelectorKind (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse <span class="doxyComputerOutput">Str</span> and return the trait set it matches or TraitSelector::invalid.</p>

<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>, definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>.</p>

</div>
</div>

### getOpenMPContextTraitSelectorName() {#aac9deff370f461cf45ef50d6c3bc1485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::omp::getOpenMPContextTraitSelectorName (<a href="#aca4e3fef9c14d0817ff403bcc1ccd403">TraitSelector</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a textual representation of the trait selector <span class="doxyComputerOutput">Kind</span>.</p>

<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>, definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#ac2fc3a53ac7c2cad1be2ce939074d2cc">getOpenMPContextTraitPropertyForSelector</a>.</p>

</div>
</div>

### getOpenMPContextTraitSetForProperty() {#a6ab910ced9f2e14f0c3b7a176ab5fe45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TraitSet llvm::omp::getOpenMPContextTraitSetForProperty (<a href="#aed19c754b6dc51a7f084d621b4043788">TraitProperty</a> Property)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the trait set for which <span class="doxyComputerOutput">Property</span> is a property.</p>

<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>, definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/omp/ompcontext/#aac40967ddf150d36c5256e322bfe3ed3">llvm::omp::OMPContext::addTrait</a>, <a href="/web-llvm/docs/api/structs/llvm/omp/variantmatchinfo/#a33a4b99974af9aad9644042639286bf3">llvm::omp::VariantMatchInfo::addTrait</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#a0776bd50b7c822627400a43977db933b">getVariantMatchScore</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#ad468a923807a048c8f7379f087507651">isVariantApplicableInContextHelper</a>.</p>

</div>
</div>

### getOpenMPContextTraitSetForSelector() {#a5a4968175aed3fd3117b6c374012c8b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TraitSet llvm::omp::getOpenMPContextTraitSetForSelector (<a href="#aca4e3fef9c14d0817ff403bcc1ccd403">TraitSelector</a> Selector)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the trait set for which <span class="doxyComputerOutput">Selector</span> is a selector.</p>

<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>, definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getOpenMPContextTraitSetKind() {#adfc882779f1a9040b8127ccfbed46f71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TraitSet llvm::omp::getOpenMPContextTraitSetKind (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse <span class="doxyComputerOutput">Str</span> and return the trait set it matches or TraitSet::invalid.</p>

<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>, definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>.</p>

</div>
</div>

### getOpenMPContextTraitSetName() {#a88d499b1533b1970641f7459a35ec40f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::omp::getOpenMPContextTraitSetName (<a href="#ac053ab007366c857887d939adbeea976">TraitSet</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a textual representation of the trait set <span class="doxyComputerOutput">Kind</span>.</p>

<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>, definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getOpenMPVersions() {#a0b170907f3cef11ef1e5d5f9b692edd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; unsigned &gt; llvm::omp::getOpenMPVersions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/omp-cpp">OMP.cpp</a>.</p>

</div>
</div>

### isCombinedConstruct() {#a1476d3d3c5a52a8d7ed817cf86bd835c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::omp::isCombinedConstruct (<a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/omp-cpp">OMP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#ae75c7313e5efcab9a8a684a1a0b8b3e6">getLeafConstructs</a> and <a href="#a61ef13844d0a136295d9a3acfcf51363">isCompositeConstruct</a>.</p>

</div>
</div>

### isCompositeConstruct() {#a61ef13844d0a136295d9a3acfcf51363}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::omp::isCompositeConstruct (<a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/omp-cpp">OMP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/omp-cpp/#a50a4b76a4e856e2e4b0e5fe36e7d5e09">getFirstCompositeRange</a>, <a href="#aaadc3f38b9cc1d217d85fbd4085574a4">getLeafConstructsOrSelf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#a1476d3d3c5a52a8d7ed817cf86bd835c">isCombinedConstruct</a>.</p>

</div>
</div>

### isLeafConstruct() {#a9db106bceba28187ada1879719bfbfff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::omp::isLeafConstruct (<a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/omp-cpp">OMP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> and <a href="#ae75c7313e5efcab9a8a684a1a0b8b3e6">getLeafConstructs</a>.</p>

</div>
</div>

### isOpenMPDevice() {#a138a1ab10971c55c181b7f23b60e4582}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::omp::isOpenMPDevice (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to determine if <span class="doxyComputerOutput">M</span> is a OpenMP target offloading device module.</p>

<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/openmpopt-h">OpenMPOpt.h</a>, definition at line 5965 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/ompinformationcache/#af72800a43846823ae6cd2d57ac8b886c">anonymous{OpenMPOpt.cpp}::OMPInformationCache::initializeRuntimeFunctions</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/ompinformationcache/#aa4654342457e24974e89aeb382212159">anonymous{OpenMPOpt.cpp}::OMPInformationCache::OMPInformationCache</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpoptcgsccpass/#a9d4366d9c2f6de53d6f2edce548577ab">llvm::OpenMPOptCGSCCPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpoptpass/#ad0812a5ba88f8645505134a108f639b2">llvm::OpenMPOptPass::run</a>.</p>

</div>
</div>

### isOpenMPKernel() {#adbaec5588449adc75116f4cad3997a03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::omp::isOpenMPKernel (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true iff <span class="doxyComputerOutput">Fn</span> is an OpenMP GPU kernel; <span class="doxyComputerOutput">Fn</span> has the "kernel" attribute.</p>

<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/openmpopt-h">OpenMPOpt.h</a>, definition at line 5904 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ae4b9f7a4322b4668f7fd018deef3e839">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::changeToSPMDMode</a>, <a href="#a7f2eade374bf61ed94ab98b04803a079">getDeviceKernels</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#ad567ae138977391ddcc0d292749aecc8">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::handleCallees</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a665e880cc41e9fd97416741590e2e0d0">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/openmpopt/#a555390458cd46cf273eeea30447a86dc">anonymous{OpenMPOpt.cpp}::OpenMPOpt::printKernels</a> and <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a53429c521770c95bf0380a74711dd451">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::updateImpl</a>.</p>

</div>
</div>

### isValidTraitPropertyForTraitSetAndSelector() {#af453d24ec3a64b23168a46d49aadfc7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::omp::isValidTraitPropertyForTraitSetAndSelector (<a href="#aed19c754b6dc51a7f084d621b4043788">TraitProperty</a> Property, <a href="#aca4e3fef9c14d0817ff403bcc1ccd403">TraitSelector</a> Selector, <a href="#ac053ab007366c857887d939adbeea976">TraitSet</a> Set)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <span class="doxyComputerOutput">Property</span> can be nested in <span class="doxyComputerOutput">Selector</span> and <span class="doxyComputerOutput">Set</span>.</p>

<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>, definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### isValidTraitSelectorForTraitSet() {#a32fcac928737340d2c5702ea9f2706cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::omp::isValidTraitSelectorForTraitSet (<a href="#aca4e3fef9c14d0817ff403bcc1ccd403">TraitSelector</a> Selector, <a href="#ac053ab007366c857887d939adbeea976">TraitSet</a> Set, bool &amp; AllowsTraitScore, bool &amp; RequiresProperty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>}</p>


<p>Return true if <span class="doxyComputerOutput">Selector</span> can be nested in <span class="doxyComputerOutput">Set</span>. Also sets <span class="doxyComputerOutput">AllowsTraitScore</span> and <span class="doxyComputerOutput">RequiresProperty</span> to true/false if the user can specify a score for properties in <span class="doxyComputerOutput">Selector</span> and if the <span class="doxyComputerOutput">Selector</span> requires at least one property.</p>


<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>, definition at line 487 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### isVariantApplicableInContext() {#af416d75b9a8863d8e262d00743dc66f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::omp::isVariantApplicableInContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/omp/variantmatchinfo">VariantMatchInfo</a> &amp; VMI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/omp/ompcontext">OMPContext</a> &amp; Ctx, bool DeviceSetOnly=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <span class="doxyComputerOutput">VMI</span> is applicable in <span class="doxyComputerOutput">Ctx</span>, that is, all traits required by <span class="doxyComputerOutput">VMI</span> are available in the OpenMP context <span class="doxyComputerOutput">Ctx</span>.</p>


<p>If <span class="doxyComputerOutput">DeviceSetOnly</span> is true, only the device selector set, if present, are checked. Note that we still honor extension traits provided by the user.</p>


<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>, definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#ad468a923807a048c8f7379f087507651">isVariantApplicableInContextHelper</a>.</p>

</div>
</div>

### listOpenMPContextTraitProperties() {#af7fd2cc7189961b174f666feadb691fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::omp::listOpenMPContextTraitProperties (<a href="#ac053ab007366c857887d939adbeea976">TraitSet</a> Set, <a href="#aca4e3fef9c14d0817ff403bcc1ccd403">TraitSelector</a> Selector)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a string listing all trait properties for <span class="doxyComputerOutput">Set</span> and <span class="doxyComputerOutput">Selector</span>.</p>

<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>, definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

### listOpenMPContextTraitSelectors() {#ab4c992ba9c000aebf3cd1e92727a1338}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::omp::listOpenMPContextTraitSelectors (<a href="#ac053ab007366c857887d939adbeea976">TraitSet</a> Set)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a string listing all trait selectors for <span class="doxyComputerOutput">Set</span>.</p>

<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>, definition at line 524 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

### listOpenMPContextTraitSets() {#a087c007cbe4348d47c1d535dfba371e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::omp::listOpenMPContextTraitSets ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a string listing all trait sets.</p>

<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>, definition at line 514 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a>.</p>

</div>
</div>

### LLVM\_ENABLE\_BITMASK\_ENUMS\_IN\_NAMESPACE() {#a5f05e02abd566f6ed4177e35d547e6cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::omp::LLVM_ENABLE_BITMASK_ENUMS_IN_NAMESPACE ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompconstants-h">OMPConstants.h</a>.</p>

</div>
</div>

### prettifyFunctionName() {#ad7e099354c93867323bca88df83c40b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::omp::prettifyFunctionName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FunctionName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a nicer version of a function name for humans to look at.</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/omp-cpp">OMP.cpp</a>.</p>


<p>References <a href="#a36c152217dc69b5295561b2f99c52c17">deconstructOpenMPKernelName</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae2705fd641fb3d1eefa2691b5117cf22">llvm::StringRef::drop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aca439bf65258d9d8d057812938b617c5">llvm::StringRef::ends_with</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AMDGPUGridValues32 {#a43060ccb6734ae95b07c8baf6ab37910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GV llvm::omp::AMDGPUGridValues32</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
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
    256,       
    32,        
    (1 &lt;&lt; 16), 
    440,       
    896,       
    1024,      
    256,       
}
</div>
</dd>
</dl>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompgridvalues-h">OMPGridValues.h</a>.</p>


<p>Referenced by <a href="#a54d82933792ec7eef3f24eb847c6acd9">getAMDGPUGridValues</a>.</p>

</div>
</div>

### AMDGPUGridValues64 {#a34b491de92222a321fa120eb158b22b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GV llvm::omp::AMDGPUGridValues64</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> GPUs.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    256,       
    64,        
    (1 &lt;&lt; 16), 
    440,       
    896,       
    1024,      
    256,       
}
</div>
</dd>
</dl>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompgridvalues-h">OMPGridValues.h</a>.</p>


<p>Referenced by <a href="#a54d82933792ec7eef3f24eb847c6acd9">getAMDGPUGridValues</a>.</p>

</div>
</div>

### AssumptionClauseMappings {#ad0b1d3bf5e80bea8b3b6180586e1c96b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionClauseMappingInfo llvm::omp::AssumptionClauseMappings[]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All known assume clauses.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
#define <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompassume-h/#abe8793b9178c02e0e42cbc286595a1ec">OMP_ASSUME_CLAUSE</a>(Identifier, StartsWith, HasDirectiveList,            HasExpression)                                       
                                                                               \
}
</div>
</dd>
</dl>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompassume-h">OMPAssume.h</a>.</p>


<p>Referenced by <a href="#ae88215d4ed5233e9eb893fded3634787">getAllAssumeClauseOptions</a>.</p>

</div>
</div>

### NVPTXGridValues {#a82196e4d5e3224c1cdd60f16e40af476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GV llvm::omp::NVPTXGridValues</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For Nvidia GPUs.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    256,       
    32,        
    (1 &lt;&lt; 16), 
    3200,      
    896,       
    1024,      
    128,       
}
</div>
</dd>
</dl>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompgridvalues-h">OMPGridValues.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#ad52342fdd467389643191fdac7abcd40">getGridValue</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/omp-h">OMP.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompassume-h">OMPAssume.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompconstants-h">OMPConstants.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompdeviceconstants-h">OMPDeviceConstants.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompgridvalues-h">OMPGridValues.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/openmpopt-h">OpenMPOpt.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/omp-cpp">OMP.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp">OMPContext.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
