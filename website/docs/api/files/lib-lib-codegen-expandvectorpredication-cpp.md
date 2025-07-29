---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/expandvectorpredication-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `ExpandVectorPredication.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/expandvectorpredication-h">llvm/CodeGen/ExpandVectorPredication.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">llvm/Analysis/VectorUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/looputils-h">llvm/Transforms/Utils/LoopUtils.h</a>"
#include &lt;optional&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-expandvectorpredication-cpp-">anonymous{ExpandVectorPredication.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander">CachingVPExpander</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bbe0bdae41c88a50d5776a8b6bd9d5c">VPLegalization</a> = <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/vplegalization">TargetTransformInfo::VPLegalization</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a959a09479efecb454e579e39bfe78688">VPTransform</a> = <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/vplegalization/#abf988827c40fdf90a1e08a8e2cddea0d">TargetTransformInfo::VPLegalization::VPTransform</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/vplegalization/#abf988827c40fdf90a1e08a8e2cddea0d">VPTransform</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1811ad3ea8f5c8a6db679268f78b8d48">parseOverrideOption</a> (const std::string &amp;TextOpt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f30d8251c1524af5380925febc3529c">anyExpandVPOverridesSet</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6634e0734365be98a758ed7e4e6cb62f">STATISTIC</a> (NumFoldedVL, "Number of folded vector length params")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f2fc62fdfccc78af58b10f3c7811d08">STATISTIC</a> (NumLoweredVPOps, "Number of folded vector predication operations")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c4f186bcff949009f515aaf53c681c9">isAllTrueMask</a> (Value *MaskVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac926076ad2d59de82321e2924a4186bd">getSafeDivisor</a> (Type *DivTy)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6be7df7547021dc38ef1d55fc8fb540f">transferDecorations</a> (Value &amp;NewVal, VPIntrinsic &amp;VPI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transfer operation properties from <span class="doxyComputerOutput">OldVPI</span> to <span class="doxyComputerOutput">NewVal</span>. <a href="#a6be7df7547021dc38ef1d55fc8fb540f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56afeeb4fb49342e6cbde202cacabdfc">replaceOperation</a> (Value &amp;NewOp, VPIntrinsic &amp;OldOp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transfer all properties from <span class="doxyComputerOutput">OldOp</span> to <span class="doxyComputerOutput">NewOp</span> and replace all uses. <a href="#a56afeeb4fb49342e6cbde202cacabdfc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabd8a84d1694dda293cbdce6bde5fc11">maySpeculateLanes</a> (VPIntrinsic &amp;VPI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44e0de2bb6a2154f5c6dbe2f8c47243c">EVLTransformOverride</a>("expandvp-override-evl-transform", cl::init(""), cl::Hidden, cl::desc("Options: <empty>" VPINTERNAL_VPLEGAL_CASES ". If non-empty, ignore " "TargetTransformInfo and " "always use this transformation for the %evl parameter (Used in " "testing)."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a268e4e732c0e3eb76cc3b297bbe1e98a">MaskTransformOverride</a>("expandvp-override-mask-transform", cl::init(""), cl::Hidden, cl::desc("Options: <empty>" VPINTERNAL_VPLEGAL_CASES ". If non-empty, Ignore " "TargetTransformInfo and " "always use this transformation for the %mask parameter (Used in " "testing)."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad26429b3ff5990beb2c028d56b628040">VPINTERNAL_VPLEGAL_CASES</a>&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28137538038fc11e76a6c7909c904b6c">VPINTERNAL_CASE</a>(X)&nbsp;&nbsp;&nbsp;"|" #<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59e2bcd3406179dd592c583c4a9a711a">VPINTERNAL_CASE</a>(X)&nbsp;&nbsp;&nbsp;.Case(#<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">VPLegalization::X</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"expandvp"</td>
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

### VPLegalization {#a8bbe0bdae41c88a50d5776a8b6bd9d5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using VPLegalization =  TargetTransformInfo::VPLegalization</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>

</div>
</div>

### VPTransform {#a959a09479efecb454e579e39bfe78688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using VPTransform =  TargetTransformInfo::VPLegalization::VPTransform</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### anyExpandVPOverridesSet() {#a9f30d8251c1524af5380925febc3529c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anyExpandVPOverridesSet ()</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="#a44e0de2bb6a2154f5c6dbe2f8c47243c">EVLTransformOverride</a> and <a href="#a268e4e732c0e3eb76cc3b297bbe1e98a">MaskTransformOverride</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#aaf7c6eba52a5555ce4c8695015bb4d8a">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::CachingVPExpander</a>.</p>

</div>
</div>

### getSafeDivisor() {#ac926076ad2d59de82321e2924a4186bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * getSafeDivisor (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DivTy)</td>
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
<dt>Returns</dt>
<dd><p>A non-excepting divisor constant for this type.</p></dd>
</dl>


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a34ee40bb2f4f5ece47ef19e5f1f57e3c">llvm::Type::isIntOrIntVectorTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a3eba8b3e2e38c997d14bc2ee850be29a">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInBinaryOperator</a>.</p>

</div>
</div>

### isAllTrueMask() {#a5c4f186bcff949009f515aaf53c681c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isAllTrueMask (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * MaskVal)</td>
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
<dt>Returns</dt>
<dd><p>Whether the vector mask <span class="doxyComputerOutput">MaskVal</span> has all lane bits set.</p></dd>
</dl>


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a48fc95f799e976fb8bf571d61e6337f5">llvm::getSplatValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a3eba8b3e2e38c997d14bc2ee850be29a">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInBinaryOperator</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a1f1f1359a986d8e4d1b107ae4c524a32">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInMemoryIntrinsic</a> and <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a2153c46ea6d560ce96b6ad7e822d2c70">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInReduction</a>.</p>

</div>
</div>

### maySpeculateLanes() {#aabd8a84d1694dda293cbdce6bde5fc11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool maySpeculateLanes (<a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; VPI)</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a89cda2218259523c41863fc1175d6907">llvm::Intrinsic::getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a0041f4dfa269c9da654f0e1d020da6ef">llvm::VPIntrinsic::getFunctionalIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#afdf77acc5c4eeed0da64226ffeb5389f">llvm::VPIntrinsic::getFunctionalOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a61054ea97168f709c1e46345f80c16a3">llvm::AttributeList::hasFnAttr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5e36553611d3def8cf698c722239718f">llvm::isSafeToSpeculativelyExecuteWithOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a3eba8b3e2e38c997d14bc2ee850be29a">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInBinaryOperator</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a5afd2ab39f4d739286d175f8babb8e6b">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInComparison</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a2153c46ea6d560ce96b6ad7e822d2c70">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInReduction</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a62f9944dba24143c8954964d7dff45b8">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationToFPCall</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-expandvectorpredication-cpp-/#aedba47828740c9315142ae92e6e901ae">anonymous{ExpandVectorPredication.cpp}::sanitizeStrategy</a>.</p>

</div>
</div>

### parseOverrideOption() {#a1811ad3ea8f5c8a6db679268f78b8d48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPTransform parseOverrideOption (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &amp; TextOpt)</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>Reference <a href="#ad26429b3ff5990beb2c028d56b628040">VPINTERNAL_VPLEGAL_CASES</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a8c2dd03c3f7b301cda6ac1ba9b31f113">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::getVPLegalizationStrategy</a>.</p>

</div>
</div>

### replaceOperation() {#a56afeeb4fb49342e6cbde202cacabdfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void replaceOperation (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; NewOp, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; OldOp)</td>
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

<p>Transfer all properties from <span class="doxyComputerOutput">OldOp</span> to <span class="doxyComputerOutput">NewOp</span> and replace all uses.</p>


<p>OldVP gets erased.</p>


<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a> and <a href="#a6be7df7547021dc38ef1d55fc8fb540f">transferDecorations</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#aee759d5807e7eb77e631717da4461426">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredication</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a3eba8b3e2e38c997d14bc2ee850be29a">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInBinaryOperator</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a5afd2ab39f4d739286d175f8babb8e6b">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInComparison</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a1f1f1359a986d8e4d1b107ae4c524a32">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInMemoryIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a2153c46ea6d560ce96b6ad7e822d2c70">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInReduction</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a5cd88dbe6fb8f2ddbd621296ca4ebd5f">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationToCastIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a62f9944dba24143c8954964d7dff45b8">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationToFPCall</a> and <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#ad2529fdcdfd78c5eccd6079fc3c74ad3">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationToIntCall</a>.</p>

</div>
</div>

### STATISTIC() {#a6634e0734365be98a758ed7e4e6cb62f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumFoldedVL, "Number of folded <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">vector</a> length params")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a9f2fc62fdfccc78af58b10f3c7811d08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumLoweredVPOps, "Number of folded <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">vector</a> predication operations")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>

</div>
</div>

### transferDecorations() {#a6be7df7547021dc38ef1d55fc8fb540f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void transferDecorations (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; NewVal, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic">VPIntrinsic</a> &amp; VPI)</td>
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

<p>Transfer operation properties from <span class="doxyComputerOutput">OldVPI</span> to <span class="doxyComputerOutput">NewVal</span>.</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a2153c46ea6d560ce96b6ad7e822d2c70">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInReduction</a> and <a href="#a56afeeb4fb49342e6cbde202cacabdfc">replaceOperation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### EVLTransformOverride {#a44e0de2bb6a2154f5c6dbe2f8c47243c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; EVLTransformOverride("expandvp-override-evl-transform", cl::init(""), cl::Hidden, cl::desc("Options: &lt;empty&gt;" VPINTERNAL_VPLEGAL_CASES ". If non-empty, ignore " "TargetTransformInfo and " "always use this transformation for the %evl parameter (Used in " "testing)."))</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>Referenced by <a href="#a9f30d8251c1524af5380925febc3529c">anyExpandVPOverridesSet</a> and <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a8c2dd03c3f7b301cda6ac1ba9b31f113">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::getVPLegalizationStrategy</a>.</p>

</div>
</div>

### MaskTransformOverride {#a268e4e732c0e3eb76cc3b297bbe1e98a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; MaskTransformOverride("expandvp-override-mask-transform", cl::init(""), cl::Hidden, cl::desc("Options: &lt;empty&gt;" VPINTERNAL_VPLEGAL_CASES ". If non-empty, Ignore " "TargetTransformInfo and " "always use this transformation for the %mask parameter (Used in " "testing)."))</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>Referenced by <a href="#a9f30d8251c1524af5380925febc3529c">anyExpandVPOverridesSet</a> and <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a8c2dd03c3f7b301cda6ac1ba9b31f113">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::getVPLegalizationStrategy</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"expandvp"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>

</div>
</div>

### VPINTERNAL\_CASE {#a28137538038fc11e76a6c7909c904b6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VPINTERNAL_CASE(X)&nbsp;&nbsp;&nbsp;"|" #<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>

</div>
</div>

### VPINTERNAL\_CASE {#a59e2bcd3406179dd592c583c4a9a711a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VPINTERNAL_CASE(X)&nbsp;&nbsp;&nbsp;.Case(#<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">VPLegalization::X</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>

</div>
</div>

### VPINTERNAL\_VPLEGAL\_CASES {#ad26429b3ff5990beb2c028d56b628040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VPINTERNAL_VPLEGAL_CASES&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="#a28137538038fc11e76a6c7909c904b6c">VPINTERNAL_CASE</a>(Legal)                                                       \
  <a href="#a28137538038fc11e76a6c7909c904b6c">VPINTERNAL_CASE</a>(Discard)                                                     \
  <a href="#a28137538038fc11e76a6c7909c904b6c">VPINTERNAL_CASE</a>(Convert)
</div>
</dd>
</dl>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp">ExpandVectorPredication.cpp</a>.</p>


<p>Referenced by <a href="#a1811ad3ea8f5c8a6db679268f78b8d48">parseOverrideOption</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
