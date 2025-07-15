---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/constrainedfpintrinsic
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ConstrainedFPIntrinsic` Class Reference

<p>This is the common base class for constrained floating point intrinsics. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ConstrainedFPIntrinsic { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A wrapper class for inspecting calls to intrinsic functions. <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constrainedfpcmpintrinsic">ConstrainedFPCmpIntrinsic</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constrained floating point compare intrinsics. <a href="/web-llvm/docs/api/classes/llvm/constrainedfpcmpintrinsic/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ba9cd066476f18d59351934de5ee48d">getNonMetadataArgCount</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">RoundingMode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fc25c0fccec261829e187a058a772a9">getRoundingMode</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/fp/#a51c5e09b2604faec548aef87bd482630">fp::ExceptionBehavior</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00c4a5b0ef7928bc65dca7af9a5a2b37">getExceptionBehavior</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0db4d0198a89808c8eef748711aaedf">isDefaultFPEnvironment</a> () const</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addecfc8be63e264d66b907dcdf66d96d">classof</a> (const IntrinsicInst *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1205d6c025adba24b86955466d75a21">classof</a> (const Value *V)</td>
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

<p>This is the common base class for constrained floating point intrinsics.</p>

<p>Definition at line 723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getExceptionBehavior() {#a00c4a5b0ef7928bc65dca7af9a5a2b37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; fp::ExceptionBehavior &gt; ConstrainedFPIntrinsic::getExceptionBehavior ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 727 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>, definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsicinst-cpp">IntrinsicInst.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#adde2ea00dd2613ee41bfe91908e4e68e">llvm::CallBase::arg_size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab775fc8630b56ff01ffc4624fed3a87">llvm::convertStrToExceptionBehavior</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#af0db4d0198a89808c8eef748711aaedf">isDefaultFPEnvironment</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#ada64d8133e1ab5a7c5f739f22949ce93">anonymous{ConstantFolding.cpp}::mayFoldConstrained</a>.</p>

</div>
</div>

### getNonMetadataArgCount() {#a9ba9cd066476f18d59351934de5ee48d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ConstrainedFPIntrinsic::getNonMetadataArgCount ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 725 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>, definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsicinst-cpp">IntrinsicInst.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#adde2ea00dd2613ee41bfe91908e4e68e">llvm::CallBase::arg_size</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst/#a7ff64b3625b6f9020556ed05a5f72af4">llvm::IntrinsicInst::getIntrinsicID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a3dbd4447f1241859563534da87edfa1f">llvm::Intrinsic::hasConstrainedFPRoundingModeOperand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### getRoundingMode() {#a4fc25c0fccec261829e187a058a772a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; RoundingMode &gt; ConstrainedFPIntrinsic::getRoundingMode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 726 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>, definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsicinst-cpp">IntrinsicInst.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#adde2ea00dd2613ee41bfe91908e4e68e">llvm::CallBase::arg_size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac8070537f4f31ef2b969d570ee70d6fa">llvm::convertStrToRoundingMode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a8cde3eb8b8e3ef69d4a575babb071687">anonymous{ConstantFolding.cpp}::getEvaluationRoundingMode</a>, <a href="#af0db4d0198a89808c8eef748711aaedf">isDefaultFPEnvironment</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#ada64d8133e1ab5a7c5f739f22949ce93">anonymous{ConstantFolding.cpp}::mayFoldConstrained</a>.</p>

</div>
</div>

### isDefaultFPEnvironment() {#af0db4d0198a89808c8eef748711aaedf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstrainedFPIntrinsic::isDefaultFPEnvironment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 728 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>, definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsicinst-cpp">IntrinsicInst.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/fp/#a51c5e09b2604faec548aef87bd482630ad8009e7c0ce2967115e856052243ac62">llvm::fp::ebIgnore</a>, <a href="#a00c4a5b0ef7928bc65dca7af9a5a2b37">getExceptionBehavior</a>, <a href="#a4fc25c0fccec261829e187a058a772a9">getRoundingMode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7ca44467144e3b6bdac3e85ef6f90e7d832">llvm::NearestTiesToEven</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#addecfc8be63e264d66b907dcdf66d96d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstrainedFPIntrinsic::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * I)</td>
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



<p>Declaration at line 731 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>, definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsicinst-cpp">IntrinsicInst.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst/#afa22d4a80efeabdb45e6f1bdbbb24850">llvm::IntrinsicInst::IntrinsicInst</a> and <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a7ff2d64dca44822331bda0a0975ebd6d">llvm::Intrinsic::isConstrainedFPIntrinsic</a>.</p>


<p>Referenced by <a href="#ae1205d6c025adba24b86955466d75a21">classof</a>.</p>

</div>
</div>

### classof() {#ae1205d6c025adba24b86955466d75a21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstrainedFPIntrinsic::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 732 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#addecfc8be63e264d66b907dcdf66d96d">classof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsicinst-cpp">IntrinsicInst.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
