---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/openmpoptpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `OpenMPOptPass` Class

<p>OpenMP optimizations pass. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::OpenMPOptPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/openmpopt-h">llvm/Transforms/IPO/OpenMPOpt.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/passinfomixin">PassInfoMixin&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CRTP mix-in to automatically provide informational APIs needed for passes. <a href="/web-llvm/docs/api/structs/llvm/passinfomixin/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e205c05ecd8b5b57528ffb52af704cf">OpenMPOptPass</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3501db0efa36723a1d74969684e067d">OpenMPOptPass</a> (ThinOrFullLTOPhase LTOPhase)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">PreservedAnalyses</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0812a5ba88f8645505134a108f639b2">run</a> (Module &amp;M, ModuleAnalysisManager &amp;AM)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13a2e9cd422f4450eec0fc7809e77f45">LTOPhase</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49a6adf97f83acf6453d4a6a4b1070f3754">ThinOrFullLTOPhase::None</a></td>
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

<p>OpenMP optimizations pass.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/openmpopt-h">OpenMPOpt.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OpenMPOptPass() {#a1e205c05ecd8b5b57528ffb52af704cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OpenMPOptPass::OpenMPOptPass ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/openmpopt-h">OpenMPOpt.h</a>.</p>

</div>
</div>

### OpenMPOptPass() {#ac3501db0efa36723a1d74969684e067d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OpenMPOptPass::OpenMPOptPass (<a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a> LTOPhase)</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/openmpopt-h">OpenMPOpt.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#ad0812a5ba88f8645505134a108f639b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses OpenMPOptPass::run (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/openmpopt-h">OpenMPOpt.h</a>, definition at line 5720 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp/#afcd49aae15dbb66f17ece9770f8b5ae1">AlwaysInlineDeviceFunctions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a1a039c806c0a203f470ea11b6932402c">llvm::omp::containsOpenMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorconfig/#af5d73bb34e01f98a095edeaff5338ecc">llvm::AttributorConfig::DefaultInitializeLiveInternals</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp/#a93bcae1c327d0ef50b484423a73f8e34">DisableInternalization</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp/#aa921a7bcb01b3bfed8108a254d624164">DisableOpenMPOptimizations</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49a7757dfb07e9ac64f8c7076644e2deac1">llvm::FullLTOPostLink</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a7f2eade374bf61ed94ab98b04803a079">llvm::omp::getDeviceKernels</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#aaab1fad63e4f3b8679469720a873fedd">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getResult</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorconfig/#a04ea2fc0b7c81a7bb90ced540e3b075a">llvm::AttributorConfig::InitializationCallback</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#af85fe4610a8ddd0d57149e73008f32fb">llvm::Attributor::internalizeFunctions</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorconfig/#ae035d742240265c163de74c1f6f07082">llvm::AttributorConfig::IPOAmendableCB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a312bc8ef3e9761ec87b3b6d05d6e2420">llvm::Attributor::isInternalizable</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorconfig/#af398ef0df0e0b9d6840d7d8c9ef0be53">llvm::AttributorConfig::IsModulePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a138a1ab10971c55c181b7f23b60e4582">llvm::omp::isOpenMPDevice</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0b2ca98dc28c61793ff5c90d23e5f14e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::lookup</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorconfig/#a068d18c1fc465f017895d6512d47467b">llvm::AttributorConfig::MaxFixpointIterations</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorconfig/#a584c356b083da5f7ca5ece1765a7e206">llvm::AttributorConfig::OREGetter</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorconfig/#a3ffd7d836cc546feb2fb671fd3cf0b73">llvm::AttributorConfig::PassName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp/#a241cffd0739529f752c42e184a306084">PrintModuleAfterOptimizations</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp/#a8597d35eccb44dd4d2aa7f28c05180b4">PrintModuleBeforeOptimizations</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/openmpopt/#a370b5637d8494d95fb8867b813fa71d8">anonymous{OpenMPOpt.cpp}::OpenMPOpt::registerAAsForFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorconfig/#a3df192ae0cdf572691dd5ff490278739">llvm::AttributorConfig::RewriteSignatures</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#ae508a1e427389fe8dc7af78bcf47722b">SetFixpointIterations</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp/#a01dcc1d7b3fe71c031ab52a3ee7e02f0">TAG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49ad94cc56b0a9155d607f2609b0f5c39d3">llvm::ThinLTOPreLink</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LTOPhase {#a13a2e9cd422f4450eec0fc7809e77f45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ThinOrFullLTOPhase llvm::OpenMPOptPass::LTOPhase = <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49a6adf97f83acf6453d4a6a4b1070f3754">ThinOrFullLTOPhase::None</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/openmpopt-h">OpenMPOpt.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/openmpopt-h">OpenMPOpt.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
