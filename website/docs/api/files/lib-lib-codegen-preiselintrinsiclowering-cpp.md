---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/preiselintrinsiclowering-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `PreISelIntrinsicLowering.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/preiselintrinsiclowering-h">llvm/CodeGen/PreISelIntrinsicLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcinstkind-h">llvm/Analysis/ObjCARCInstKind.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcutil-h">llvm/Analysis/ObjCARCUtil.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/expandvectorpredication-h">llvm/CodeGen/ExpandVectorPredication.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">llvm/IR/Use.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/lowerconstantintrinsics-h">llvm/Transforms/Scalar/LowerConstantIntrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/lowermemintrinsics-h">llvm/Transforms/Utils/LowerMemIntrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/lowervectorintrinsics-h">llvm/Transforms/Utils/LowerVectorIntrinsics.h</a>"
#include "llvm/IR/VPIntrinsics.def"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-preiselintrinsiclowering-cpp-">anonymous{PreISelIntrinsicLowering.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-preiselintrinsiclowering-cpp-/preiselintrinsiclowering">PreISelIntrinsicLowering</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-preiselintrinsiclowering-cpp-/preiselintrinsicloweringlegacypass">PreISelIntrinsicLoweringLegacyPass</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a57e48e140e75da173a7ec5c681a1f2cc">forEachCall</a> (Function &amp;Intrin, T Callback)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed95721a1abb7ab2af1b35f3f282b1fe">lowerLoadRelative</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/callinst/#ad682514c13f12f1a8d759d422fce6aef">CallInst::TailCallKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb2a072710efb912aaf56e5eee9e1b4d">getOverridingTailCallKind</a> (const Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5369c9d1c15e1c2fe5106461ae89334">lowerObjCCall</a> (Function &amp;F, const char *NewFn, bool setNonLazyBind=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3ab61efb16b5365178039250c68aa89">canEmitLibcall</a> (const TargetMachine *TM, Function *F, RTLIB::Libcall LC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae273d5c59199105d9ef76fea7930c491">INITIALIZE_PASS_BEGIN</a> (PreISelIntrinsicLoweringLegacyPass, "pre-isel-intrinsic-lowering", "Pre-ISel Intrinsic Lowering", false, false) INITIALIZE_PASS_END(PreISelIntrinsicLoweringLegacyPass</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09580b94a258009643d4ddb3d2426a8d">MemIntrinsicExpandSizeThresholdOpt</a>("mem-intrinsic-expand-size", cl::desc("Set minimum mem intrinsic size to expand in IR"), cl::init(-1), cl::Hidden)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Threshold to leave statically sized memory intrinsic calls. <a href="#a09580b94a258009643d4ddb3d2426a8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">pre <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#a1bcea9a90cf7291ab18e2df09099b9ad">isel</a> intrinsic</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a318f165fe87d0ea66c808a9bf55d030c">lowering</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">pre <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#a1bcea9a90cf7291ab18e2df09099b9ad">isel</a> intrinsic Pre ISel Intrinsic</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77cabd8c10802136c4ab03db0156e41e">Lowering</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">pre <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#a1bcea9a90cf7291ab18e2df09099b9ad">isel</a> intrinsic Pre ISel Intrinsic</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d2896bcea05226e8bc5ea4ca165a98e">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4112c34d12beefd99e1759d16b92acf8">BEGIN_REGISTER_VP_INTRINSIC</a>(VPID, MASKPOS, VLENPOS)&nbsp;&nbsp;&nbsp;  case Intrinsic::VPID:</td>
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

## Functions

### canEmitLibcall() {#ab3ab61efb16b5365178039250c68aa89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool canEmitLibcall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> * TM, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a> LC)</td>
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



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp">PreISelIntrinsicLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ae365cf8f9a6844685be3fd9f12956c33">llvm::TargetLoweringBase::getLibcallName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-preiselintrinsiclowering-cpp-/preiselintrinsiclowering/#a6399ae03a799911dd8f5adcdff15dc8f">anonymous{PreISelIntrinsicLowering.cpp}::PreISelIntrinsicLowering::expandMemIntrinsicUses</a>.</p>

</div>
</div>

### forEachCall() {#a57e48e140e75da173a7ec5c681a1f2cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool forEachCall (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Intrin, T Callback)</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp">PreISelIntrinsicLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a413abcab8dbc3900fc2fde96a5d8fca6">llvm::Value::use_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-preiselintrinsiclowering-cpp-/preiselintrinsiclowering/#a333bc33c92a4288cf0b3e4514f4cb075">anonymous{PreISelIntrinsicLowering.cpp}::PreISelIntrinsicLowering::lowerIntrinsics</a>.</p>

</div>
</div>

### getOverridingTailCallKind() {#abb2a072710efb912aaf56e5eee9e1b4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst::TailCallKind getOverridingTailCallKind (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp">PreISelIntrinsicLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a4e557a8b99ad5d09e3018b1f3e02a08f">llvm::objcarc::GetFunctionClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a392f31f4801522bd6062e369302d83a1">llvm::objcarc::IsAlwaysTail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a38d5511a0458d8611ae8194db9f31e34">llvm::objcarc::IsNeverTail</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#ad682514c13f12f1a8d759d422fce6aefa28bea809e15b48558c89910b7fb924b6">llvm::CallInst::TCK_None</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#ad682514c13f12f1a8d759d422fce6aefa876f2a1fd3dd74831f85634cb14b72fe">llvm::CallInst::TCK_NoTail</a> and <a href="/web-llvm/docs/api/classes/llvm/callinst/#ad682514c13f12f1a8d759d422fce6aefa49f500a89cba35f060bbeb57c39c6e66">llvm::CallInst::TCK_Tail</a>.</p>


<p>Referenced by <a href="#aa5369c9d1c15e1c2fe5106461ae89334">lowerObjCCall</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#ae273d5c59199105d9ef76fea7930c491}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (PreISelIntrinsicLoweringLegacyPass, "pre-<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#a1bcea9a90cf7291ab18e2df09099b9ad">isel</a>-intrinsic-lowering", "Pre-ISel Intrinsic Lowering", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp">PreISelIntrinsicLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a74ce8276b89067e806f67c45a6d92575">INITIALIZE_PASS_END</a>.</p>

</div>
</div>

### lowerLoadRelative() {#aed95721a1abb7ab2af1b35f3f282b1fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool lowerLoadRelative (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp">PreISelIntrinsicLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23f9ec4bb2576ca8738f3edc9c4f5cdf">llvm::Int32Ty</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-preiselintrinsiclowering-cpp-/preiselintrinsiclowering/#a333bc33c92a4288cf0b3e4514f4cb075">anonymous{PreISelIntrinsicLowering.cpp}::PreISelIntrinsicLowering::lowerIntrinsics</a>.</p>

</div>
</div>

### lowerObjCCall() {#aa5369c9d1c15e1c2fe5106461ae89334}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool lowerObjCCall (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * NewFn, bool setNonLazyBind=false)</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp">PreISelIntrinsicLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ae5d05ec2b9a60806746addff3f2a71a9">llvm::CallBase::addParamAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a0174304150a18968bb6e6436f5c675f2">llvm::objcarc::getAttachedARCFunctionKind</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncallee/#ac5d8da677233fa2e1e7039508ed56e0e">llvm::FunctionCallee::getCallee</a>, <a href="#abb2a072710efb912aaf56e5eee9e1b4d">getOverridingTailCallKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst/#a04df6c03772f85899d30bdcd06cbcd06">llvm::IntrinsicInst::mayLowerToFunctionCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2aa1226b5450384ce6ea5ed47c317303ee">llvm::objcarc::RetainRV</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp/#a6d3aac6350d77104c41caca1e4bd63cf">setNonLazyBind</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#a68573712cd73746e416002907c9af79b">llvm::CallInst::setTailCallKind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2ae490705e8a3fd75e76afa1108289c24a">llvm::objcarc::UnsafeClaimRV</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-preiselintrinsiclowering-cpp-/preiselintrinsiclowering/#a333bc33c92a4288cf0b3e4514f4cb075">anonymous{PreISelIntrinsicLowering.cpp}::PreISelIntrinsicLowering::lowerIntrinsics</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### false {#a8d2896bcea05226e8bc5ea4ca165a98e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pre isel intrinsic Pre ISel Intrinsic false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp">PreISelIntrinsicLowering.cpp</a>.</p>

</div>
</div>

### lowering {#a318f165fe87d0ea66c808a9bf55d030c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pre isel intrinsic lowering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp">PreISelIntrinsicLowering.cpp</a>.</p>

</div>
</div>

### Lowering {#a77cabd8c10802136c4ab03db0156e41e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pre isel intrinsic Pre ISel Intrinsic Lowering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp">PreISelIntrinsicLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a6d38e4f90c68ce910c9f3c303fcb5b9e">EnsureStackAlignment</a> and <a href="/web-llvm/docs/api/classes/anonymous-preiselintrinsiclowering-cpp-/preiselintrinsicloweringlegacypass/#a5092e99089883790c3496c84f7628904">anonymous{PreISelIntrinsicLowering.cpp}::PreISelIntrinsicLoweringLegacyPass::runOnModule</a>.</p>

</div>
</div>

### MemIntrinsicExpandSizeThresholdOpt {#a09580b94a258009643d4ddb3d2426a8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int64_t &gt; MemIntrinsicExpandSizeThresholdOpt("mem-intrinsic-expand-size", cl::desc("Set minimum mem intrinsic size to expand in IR"), cl::init(-1), cl::Hidden)</td>
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

<p>Threshold to leave statically sized memory intrinsic calls.</p>


<p>Calls of known size larger than this will be expanded by the pass. Calls of unknown or lower size will be left for expansion in codegen.</p>


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp">PreISelIntrinsicLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-preiselintrinsiclowering-cpp-/preiselintrinsiclowering/#a44581a73bfff282e515ff1df662ee1cf">anonymous{PreISelIntrinsicLowering.cpp}::PreISelIntrinsicLowering::shouldExpandMemIntrinsicWithSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### BEGIN\_REGISTER\_VP\_INTRINSIC {#a4112c34d12beefd99e1759d16b92acf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define BEGIN_REGISTER_VP_INTRINSIC(VPID, MASKPOS, VLENPOS)&nbsp;&nbsp;&nbsp;  case Intrinsic::VPID:</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp">PreISelIntrinsicLowering.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
