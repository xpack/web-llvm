---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `AArch64PromoteConstant.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64-h">AArch64.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constant-h">llvm/IR/Constant.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">llvm/IR/GlobalValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">llvm/IR/GlobalVariable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/institerator-h">llvm/IR/InstIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
#include &lt;utility&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-aarch64promoteconstant-cpp-">anonymous{AArch64PromoteConstant.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-aarch64promoteconstant-cpp-/aarch64promoteconstant">AArch64PromoteConstant</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Promotes interesting constant into global variables. <a href="/web-llvm/docs/api/classes/anonymous-aarch64promoteconstant-cpp-/aarch64promoteconstant/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-aarch64promoteconstant-cpp-/aarch64promoteconstant/promotedconstant">PromotedConstant</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-aarch64promoteconstant-cpp-/aarch64promoteconstant/updaterecord">UpdateRecord</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55ebb20f2bc5c5a8638bba9ec50b0a61">STATISTIC</a> (NumPromoted, "Number of promoted constants")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a133efe6d5a6151cfb0c7d45047920524">STATISTIC</a> (NumPromotedUses, "Number of promoted constants uses")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acddbaf5fc5a8735431a050af39909d9f">INITIALIZE_PASS_BEGIN</a> (AArch64PromoteConstant, "aarch64-promote-const", "AArch64 Promote Constant Pass", false, false) INITIALIZE_PASS_END(AArch64PromoteConstant</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a93639bd72c9cc80cf001e17599ff87">isConstantUsingVectorTy</a> (const Type *CstTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the given type uses a vector type. <a href="#a1a93639bd72c9cc80cf001e17599ff87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94b1b5e9307f524668a97d9628b3de2a">containsOnlyConstantData</a> (const Constant *C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff43b1c529b1af47195587ca0090f7ec">shouldConvertUse</a> (const Constant *Cst, const Instruction *Instr, unsigned OpIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the given use (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> + OpIdx) of Cst should be converted into a load of a global variable initialized with Cst. <a href="#aff43b1c529b1af47195587ca0090f7ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6a1350b26889cb5eebc75372ab4d3f5">shouldConvertImpl</a> (const Constant *Cst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the given Cst should be converted into a load of a global variable initialized with Cst. <a href="#af6a1350b26889cb5eebc75372ab4d3f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada41eab274cc944643f8b6a74dc1e8a0">shouldConvert</a> (Constant &amp;C, AArch64PromoteConstant::PromotionCacheTy &amp;PromotionCache)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5c7f0f9f87d69820d8e4d8b31f4b0ff">ensurePromotedGV</a> (Function &amp;F, Constant &amp;C, AArch64PromoteConstant::PromotedConstant &amp;PC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2894a28a533f577c4252eae792e3358">Stress</a>("aarch64-stress-promote-const", cl::Hidden, cl::desc("Promote all vector constants"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">aarch64 promote</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90f8350fecae261c25be85d38b451bff">const</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">aarch64 promote AArch64 Promote <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a099cf45c11df5059934a293e57614b7c">Pass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">aarch64 promote AArch64 Promote <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60ff0978cee670022cdc8743945e0eae">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"aarch64-promote-const"</td>
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

### containsOnlyConstantData() {#a94b1b5e9307f524668a97d9628b3de2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool containsOnlyConstantData (<a href="#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### ensurePromotedGV() {#ab5c7f0f9f87d69820d8e4d8b31f4b0ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ensurePromotedGV (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> &amp; C, <a href="/web-llvm/docs/api/structs/anonymous-aarch64promoteconstant-cpp-/aarch64promoteconstant/promotedconstant">AArch64PromoteConstant::PromotedConstant</a> &amp; PC)</td>
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



<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64promoteconstant-cpp-/aarch64promoteconstant/promotedconstant/#a1aff3b665cce8bf73903e00a6f87e9be">anonymous{AArch64PromoteConstant.cpp}::AArch64PromoteConstant::PromotedConstant::GV</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">llvm::GlobalValue::NotThreadLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a1e56c814d11206720cc23059b871128d">llvm::Value::print</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a095f8f031d99ce3c0b25478713293dea">llvm::GlobalVariable::setInitializer</a> and <a href="/web-llvm/docs/api/structs/anonymous-aarch64promoteconstant-cpp-/aarch64promoteconstant/promotedconstant/#af5057fe4659dae804a6517b5a3cfa707">anonymous{AArch64PromoteConstant.cpp}::AArch64PromoteConstant::PromotedConstant::ShouldConvert</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#acddbaf5fc5a8735431a050af39909d9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (AArch64PromoteConstant, "aarch64-promote-const", "AArch64 Promote <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> Pass", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### isConstantUsingVectorTy() {#a1a93639bd72c9cc80cf001e17599ff87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isConstantUsingVectorTy (<a href="#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * CstTy)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the given type uses a vector type.</p>

<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a3fb19a71e602dce8ff646c3ac2f4ca0f">llvm::Type::getArrayElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a15d34f8dc07013df378e0fb3d0134c08">llvm::Type::getStructElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a58e54adaa7672bbf72091254a5391137">llvm::Type::getStructNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a2a394517076e7dd2bdcd7dde33dfcb7d">llvm::Type::isArrayTy</a>, <a href="#a1a93639bd72c9cc80cf001e17599ff87">isConstantUsingVectorTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a81eef9d7336f7ee43be79630d8e8ec86">llvm::Type::isStructTy</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>.</p>


<p>Referenced by <a href="#a1a93639bd72c9cc80cf001e17599ff87">isConstantUsingVectorTy</a> and <a href="#af6a1350b26889cb5eebc75372ab4d3f5">shouldConvertImpl</a>.</p>

</div>
</div>

### shouldConvert() {#ada41eab274cc944643f8b6a74dc1e8a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool shouldConvert (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> &amp; C, <a href="/web-llvm/docs/api/classes/anonymous-aarch64promoteconstant-cpp-/aarch64promoteconstant/#a4e357c8b7364d5898a8085b69bf2191c">AArch64PromoteConstant::PromotionCacheTy</a> &amp; PromotionCache)</td>
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



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a> and <a href="#af6a1350b26889cb5eebc75372ab4d3f5">shouldConvertImpl</a>.</p>

</div>
</div>

### shouldConvertImpl() {#af6a1350b26889cb5eebc75372ab4d3f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool shouldConvertImpl (<a href="#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Cst)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the given Cst should be converted into a load of a global variable initialized with Cst.</p>


<p>A constant should be converted if it is likely that the materialization of the constant will be tricky. Thus, we give up on zero or undef values.</p>


<div class="doxyXrefSect">
<dl class="doxyXrefSectList">
<dt class="doxyXrefSectTitle"><a href=/web-llvm/docs/api/pages/todo/#_todo000004>Todo</a></dt>
<dd class="doxyXrefSectDescription">
<p>Currently, accept only vector related types. Also we give up on all simple vector type to keep the existing behavior. Otherwise, we should push here all the check of the lowering of BUILD_VECTOR. By giving up, we lose the potential benefit of merging constant via global merge and the fact that the same constant is stored only once with this method (versus, as many function that uses the constant for the regular approach, even for float). Again, the simplest solution would be to promote every constant and rematerialize them when they are actually cheap to create.</p>
</dd>
</dl>
</div>

<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a1a93639bd72c9cc80cf001e17599ff87">isConstantUsingVectorTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#ad97fc23e85a854a19101bf8e861356aa">llvm::Constant::isZeroValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp/#ab03b4c4121954359c7380f0e60888bf5">Stress</a>.</p>


<p>Referenced by <a href="#ada41eab274cc944643f8b6a74dc1e8a0">shouldConvert</a>.</p>

</div>
</div>

### shouldConvertUse() {#aff43b1c529b1af47195587ca0090f7ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool shouldConvertUse (<a href="#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Cst, <a href="#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Instr, unsigned OpIdx)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the given use (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> + OpIdx) of Cst should be converted into a load of a global variable initialized with Cst.</p>


<p>A use should be converted if it is legal to do so. For instance, it is not legal to turn the mask operand of a shuffle vector into a load of a global variable.</p>


<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#a018f0394a375233d538109968b76a05a">llvm::CallBase::isInlineAsm</a>.</p>

</div>
</div>

### STATISTIC() {#a55ebb20f2bc5c5a8638bba9ec50b0a61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumPromoted, "Number of promoted constants")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a133efe6d5a6151cfb0c7d45047920524}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumPromotedUses, "Number of promoted constants uses")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### const {#a90f8350fecae261c25be85d38b451bff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">aarch64 promote const</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuimageintrinsicoptimizer-cpp/#a4c4959b067827b56c5e14e445afb87ff">addInstToMergeableList</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputtiimpl/#a533f86b6ec57f81f1a6b40bc3792cbec">llvm::AMDGPUTTIImpl::AMDGPUTTIImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#a0906254a905f4d1c0a68dd54c3eb65e8">llvm::object::ArchiveMemberHeader::ArchiveMemberHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/arcttiimpl/#ad63892278810aafdcce23f910f101d3a">llvm::ARCTTIImpl::ARCTTIImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/anonymous-aarch32-cpp-/armrelocation/#a9a8448b41e31094cc663302462ca285e">llvm::jitlink::aarch32::anonymous{aarch32.cpp}::ArmRelocation::ArmRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#ab6cf194b594fa748bf8cd72df35d6479">llvm::object::ELFFile&lt; ELF32LE &gt;::base</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#ae54b3190e013b4c17e9dd0e82fb8ec2e">llvm::object::BigArchiveMemberHeader::BigArchiveMemberHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a854df6024334d02ea223f70a543940fc">blockPrologueInterferes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonnewvaluejump-cpp/#a8d3e918d874e8e80cf9a403e8ea59e32">canBeFeederToNewValueJump</a>, <a href="/web-llvm/docs/api/classes/llvm/argument/#ad904765991a90849720e14565ceca7d5">llvm::Argument::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/btf/arraytype/#ac3d8e699aabe6a38c4fa52cb2cb38ef1">llvm::BTF::ArrayType::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/btf/enum64type/#ab299b3a3f955e416c236ff93bb6034b2">llvm::BTF::Enum64Type::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/btf/enumtype/#a19023f691aa2df14f24d427f6fc901b0">llvm::BTF::EnumType::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/btf/structtype/#ac1f17ec09840983c7c7e84ccb76f072f">llvm::BTF::StructType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a644afe0cf8a4816171b3384098325dc2">llvm::Instruction::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vpactivelanemaskphirecipe/#a32354b1cd2ce53a609b8e4e837c55130">llvm::VPActiveLaneMaskPHIRecipe::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#a568e7be2bddeae465781cd63c76564c3">llvm::VPCanonicalIVPHIRecipe::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vpevlbasedivphirecipe/#a3d45d04fecce555d9abeda535442a35c">llvm::VPEVLBasedIVPHIRecipe::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/vpfirstorderrecurrencephirecipe/#abf255079aef43722bfb39b1aea028ee3">llvm::VPFirstOrderRecurrencePHIRecipe::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionphirecipe/#adbdd829708c7d8dc1da022001477c6a6">llvm::VPReductionPHIRecipe::classof</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a182c2c1a3860b0bc1c8c0d7918ee3c">llvm::createAMDGPULowerModuleLDSLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08b0db116677d9d685f7a07e73a914af">llvm::createCFGSimplificationPass</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8240180b602f60980be558e3cd44b460">llvm::IRBuilderBase::CreateGlobalStringPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/cvrecord/#a83850e3b015408edc6c9b1278aaf642e">llvm::codeview::CVRecord&lt; TypeLeafKind &gt;::CVRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a80db7425f3e992ef519e25179f94fb56">llvm::DataExtractor::DataExtractor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a31d2138e4e8a3d618d9841a3b13c5609">decodeVersionImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a869eb0ec1821f8576c98ced8745b1f30">DecodeVGPR_16RegisterClass</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchaddhandler/#a32c81722d001c17b29f4d06408286da7">llvm::sandboxir::CatchSwitchAddHandler::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/genericsetter/#a78cf03974174777527608b3254bd260a">llvm::sandboxir::GenericSetter&lt; GetterFn, SetterFn &gt;::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/genericsetterwithidx/#a3f784d0bef994cdedb3580cd80370cd6">llvm::sandboxir::GenericSetterWithIdx&lt; GetterFn, SetterFn &gt;::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a9c4e8cde73237ab00ac91c380ff95f38">llvm::DWARFDataExtractor::DWARFDataExtractor</a>, <a href="/web-llvm/docs/api/classes/llvm/object/dynamicrelocref/#af62bcfea8c669f8936ff1c2c1aa9f32b">llvm::object::DynamicRelocRef::DynamicRelocRef</a>, <a href="/web-llvm/docs/api/classes/llvm/exitonerror/#a61844d7b46c48c5cb899661736bf0288">llvm::ExitOnError::ExitOnError</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsseframelowering-cpp-/expandpseudo/#ac702ea08eee585ce29e0815d2fb87d82">anonymous{MipsSEFrameLowering.cpp}::ExpandPseudo::ExpandPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regusageinfopropagate-cpp/#adec6387d9efa774210234dda2047d795">findCalledFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangeshrink-cpp/#a75ee109226025aaaf7373a0dca56341a">FindDominatedInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvevptblockpass-cpp/#ab65fd688ebdc8951019a8d796ebcdae5">findVCMPToFoldIntoVPST</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#adb1fcba65d61d145b053ee0217b3dee7">fixupReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-dxilprettyprinter-cpp-/formatbindingid/#a2d7e241ecb54492444c2a493c5cd4883">anonymous{DXILPrettyPrinter.cpp}::FormatBindingID::FormatBindingID</a>, <a href="/web-llvm/docs/api/structs/anonymous-dxilprettyprinter-cpp-/formatbindinglocation/#a7719d1f8efaa729d4461c1db01cd70e5">anonymous{DXILPrettyPrinter.cpp}::FormatBindingLocation::FormatBindingLocation</a>, <a href="/web-llvm/docs/api/structs/anonymous-dxilprettyprinter-cpp-/formatbindingsize/#aab2ecb6491e5404b2a324a3c5c14e17a">anonymous{DXILPrettyPrinter.cpp}::FormatBindingSize::FormatBindingSize</a>, <a href="/web-llvm/docs/api/structs/anonymous-dxilprettyprinter-cpp-/formatresourcedimension/#ac719f0f929437f6a7dd3fbb8bafdcbe4">anonymous{DXILPrettyPrinter.cpp}::FormatResourceDimension::FormatResourceDimension</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a19dce49c9c18898b9f4ca348fa3c89ec">llvm::GCNTTIImpl::GCNTTIImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silatebranchlowering-cpp/#a2fa9fe1bc3c4ca4168ea98c54c5090e2">generateEndPgm</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariable/#aaa88dad357fd3d66122495f97f4c8088">llvm::DbgVariable::get</a>, <a href="/web-llvm/docs/api/structs/llvm/spirvmoduleanalysis/#afe9d9cf2f96394c702e785deb75af8c4">llvm::SPIRVModuleAnalysis::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/structs/llvm/object/elf-verdef-impl/#a77618d3d85df86263cc0d39bf3b9041d">llvm::object::Elf_Verdef_Impl&lt; ELFType&lt; E, Is64 &gt; &gt;::getAux</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycle/#aa22ae5fa624a5c3d5d22aa3f4538e675">llvm::GenericCycle&lt; ContextT &gt;::getCyclePredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycle/#a8d9a9cbd5e36d720192616db3d068dc9">llvm::GenericCycle&lt; ContextT &gt;::getCyclePreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a8cbf634a57382636ca0dbbcf779655ae">llvm::Module::getFunctionList</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4d0a7baab8d078065b2de10e3460892a">llvm::Function::getIntrinsicID</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfo-cpp/#a84b611106739b9bc347338219f73be29">getLocCookie</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonloadstorewidening-cpp/#abef29ef0fe3e5fab1eb42d05e496291b">getMemTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/singlellvminstructionimpl/#afa53e9f580e933d74db578d6f567e7b5">llvm::sandboxir::SingleLLVMInstructionImpl&lt; LLVMT &gt;::getNumOfIRInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/unreachableinst/#abf7a748539909a11bc4632aa959e69ef">llvm::sandboxir::UnreachableInst::getNumOfIRInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/argument/#ad3da5e0b4c0c86ff3f7da94396931523">llvm::Argument::getParamAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcompare/#a696ac03c4b406b53e93dbf80e5b82742">llvm::logicalview::LVCompare::getPassTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/fixupstatepointcallersaved-cpp/#abdbbbd165ab5fb16364c6f6b2a920664">getRegisterSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#ade1f2320fe436fd570559a11f1167746">getRegLiveThroughMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#a7fcb99675ac619b90ab5d7c2eec0a482">getRegOpRC</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a0bd4071843f49d48f53401da3603c0e9">llvm::HexagonPacketizerList::HexagonPacketizerList</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ab0f312a890f3aa47e480f40c67df30fe">llvm::HexagonTargetLowering::HexagonTargetLowering</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#abce174abc78cf2fe5987af1aaaa46c60">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::HexagonVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#a3841d5fcdb3b56a8d1f5a9df25fc2b1e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64deadregisterdefinitionspass-cpp/#a0fb33ddf5cf6eccb986131394311419e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp/#a82123100de61eeb10ee4fde2a11c1bec">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuresourceusageanalysis-cpp/#a582bb67c741ffedbb01e6a569a0e457f">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#abec8974056ca245b67d77584056c3be0">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a2a1cbb86e54ced362532165285bfd094">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcmetadata-cpp/#ad9f86f2ac1dc507b89292cb66fec0ef6">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonearlyifconv-cpp/#ae52f88c3e384e9ffa4a6e13f8d6ac9e2">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a0c644c1ec65bfe3ab19a7ac9d5e0aeab">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp/#ade408e36e63dd452948c1b257730c4b4">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp/#a40fc2b366deab619c7f93f2245cd51a2">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/postdominators-cpp/#a3b65784e88b4b016ebfbec32d19e0418">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/postraschedulerlist-cpp/#a6e98a635acc74fb470e68e8f15f9f228">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/irprintingpasses-cpp/#a777c2e701b2f140458b558974bfbde55">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp/#a2499f81c6db72dcb3371cb598199e8d2">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp/#ad49d5358eb2049a14a99665fc936acf9">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertwritevxrm-cpp/#a1ac1073e8585097c12551ee7971f44eb">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmovemerger-cpp/#ae773254afe874b8a24c576bb7fc1dfed">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvectorpeephole-cpp/#af4707f2d4fe8e86f046089a400af7e72">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/sjljehprepare-cpp/#a6f028fb180c2a9618d9afdacfbb98ae7">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitintrinsics-cpp/#affd8ae584b7efc3df925b549d644b849">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2sizereduction-cpp/#a12eb51750eb0905d14d6437772638c1f">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#a5b111dc93b0f18920f5656c9e5f8c539">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/initllvm/#ad726129411eea56337b97032b86b4ead">llvm::InitLLVM::InitLLVM</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonrdfopt-cpp-/hexagoncp/#afbd23f1436bf2680a83324a63b37dbe4">anonymous{HexagonRDFOpt.cpp}::HexagonCP::interpretAsCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#aed37527b97744cc3570d09ed4d53fa51">isIntImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a026121a7546e6370b59fc4b70af584d7">isLegalMaskCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#aaeffdea43602557f6c520f6b9501a491">isMoveInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a2e2ab800c636979b14ada45510861743">llvm::Function::llvm::ilist_node_with_parent&lt; llvm::BasicBlock, llvm::Function &gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4e1c5961974e47ac42e9c34efa0792b3">llvm::BasicBlock::LLVM_DEPRECATED</a>, <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga67a4d14fa2dd7a2908b0888dc1ffbd8d">LLVMRemarkParserCreateYAML</a>, <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga0486d7fbdef367b47c2f6c2edbfaac16">LLVMRemarkStringGetData</a>, <a href="/web-llvm/docs/api/classes/llvm/loadstoreopt/#a7ae5b3f0f09b54338a470c68e36e5322">llvm::LoadStoreOpt::LoadStoreOpt</a>, <a href="/web-llvm/docs/api/classes/llvm/loadstoreopt/#a24597ce933b1850a13eee882d9335fc4">llvm::LoadStoreOpt::LoadStoreOpt</a>, <a href="/web-llvm/docs/api/classes/llvm/localizer/#a62ba443c3e6872953f937aaca117c8ba">llvm::Localizer::Localizer</a>, <a href="/web-llvm/docs/api/classes/llvm/localizer/#a6ed62833729b6206b3bb80e3349ae642">llvm::Localizer::Localizer</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#a3f9c8da99e854c59b91a4c6237f6b85b">llvm::MachinePointerInfo::MachinePointerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae6189d19092044a37414c05526874a06">llvm::Instruction::moveAfter</a>, <a href="/web-llvm/docs/api/classes/anonymous-codeviewerror-cpp-/codeviewerrorcategory/#a4d2d0a1fb9e518571bb143a4705161fb">anonymous{CodeViewError.cpp}::CodeViewErrorCategory::name</a>, <a href="/web-llvm/docs/api/classes/anonymous-error-cpp-/-object-error-category/#af63ed9b2ad8bdf72c0ae870d2262269f">anonymous{Error.cpp}::_object_error_category::name</a>, <a href="/web-llvm/docs/api/classes/anonymous-genericerror-cpp-/pdberrorcategory/#a8e2b8b7e31b2a0ed195fd951c9c6175d">anonymous{GenericError.cpp}::PDBErrorCategory::name</a>, <a href="/web-llvm/docs/api/classes/anonymous-jitlink-cpp-/jitlinkererrorcategory/#a015737c3cf9d303820ee1ee47f603116">anonymous{JITLink.cpp}::JITLinkerErrorCategory::name</a>, <a href="/web-llvm/docs/api/classes/anonymous-msferror-cpp-/msferrorcategory/#a7e2b768b75a1a749ad1a2bfd7381eb98">anonymous{MSFError.cpp}::MSFErrorCategory::name</a>, <a href="/web-llvm/docs/api/classes/anonymous-orcerror-cpp-/orcerrorcategory/#ac1a33e3f64922e5023b78134a4cc60eb">anonymous{OrcError.cpp}::OrcErrorCategory::name</a>, <a href="/web-llvm/docs/api/classes/anonymous-rawerror-cpp-/rawerrorcategory/#a3a28f35fffccc242c3adbd0bd4090112">anonymous{RawError.cpp}::RawErrorCategory::name</a>, <a href="/web-llvm/docs/api/classes/anonymous-runtimedyld-cpp-/runtimedylderrorcategory/#a69369a6de3d79f76905469d2c67e6dfb">anonymous{RuntimeDyld.cpp}::RuntimeDyldErrorCategory::name</a>, <a href="/web-llvm/docs/api/classes/diaerrorcategory/#af49be328f7f6c18809a6712ab84d2a57">DIAErrorCategory::name</a>, <a href="/web-llvm/docs/api/classes/llvm/json/objectkey/#a48e2b30eeaeb0ebf30bc480b9124820c">llvm::json::ObjectKey::ObjectKey</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hvxidioms/#aef05d2673ec790b5724976bfdac1790c">anonymous{HexagonVectorCombine.cpp}::HvxIdioms::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad57d1fc17dcfc3311765b76933fe768b">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9886ffbea21782fa0ac67f5d0e952f39">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4e65f7a7ca172622a3018653e4088b56">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/erasefromparent/#a573ed9bac5c1b27d7d6f393955c7403d">llvm::sandboxir::EraseFromParent::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a162c90bc179a6359438d060722bee35f">llvm::operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/r600ttiimpl/#ab93330bd3223afb926c2d8f0a0fd6b76">llvm::R600TTIImpl::R600TTIImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/rawinstrprofreader/#a0416876c379b6138a7ee65ec3b7359df">llvm::RawInstrProfReader&lt; uint32_t &gt;::RawInstrProfReader</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#a32ce353011ca5bcaf6112536aec4c098">reportTranslationError</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#aaaff4f2206ebf29a0a8e629835ca1973">restoreSSA</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scatterer/#a61c4fd4066c48391e3ca55e84c4a102d">anonymous{Scalarizer.cpp}::Scatterer::Scatterer</a>, <a href="/web-llvm/docs/api/structs/scopedscavengeorspill/#ab0ac2a9aa1075f3e566bf2e74dafa8b7">ScopedScavengeOrSpill::ScopedScavengeOrSpill</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a5ed109e1cb014423460d747d1bad657c">llvm::HexagonDAGToDAGISel::SelectIndexedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzpostraschedstrategy/#ae7cf55944f14abe03fa718a60f2fafe1">llvm::SystemZPostRASchedStrategy::SystemZPostRASchedStrategy</a>, <a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/anonymous-aarch32-cpp-/thumbrelocation/#ab0298428d998a704d58710e2b3b7e77f">llvm::jitlink::aarch32::anonymous{aarch32.cpp}::ThumbRelocation::ThumbRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#a26a8b66384eac1604e4ce7bd35bb6878">llvm::object::ELFObjectFile&lt; ELF32LE &gt;::toSectionRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2itblockpass-cpp/#adc8d1d32a1860d5e21f283b913ac0880">TrackDefUses</a>, <a href="/web-llvm/docs/api/classes/llvm/unique-function-77f83113ddf6765c0d3030de74df0cd1/#aec7783fd5f7e9ca0b6b0b35e8ded1de1">llvm::unique_function&lt; R(P...) const &gt;::unique_function</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a927aecb431f82466a89596d4ef11608e">updateBranches</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/argument/#aad9974dafadc102c607acae06ceaeb55">llvm::sandboxir::Argument::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function/#acee180f03b5947c8f371e5b02445d298">llvm::sandboxir::Function::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/singlellvminstructionimpl/#abf3808e6f94bcec8e66656e163c8b6e5">llvm::sandboxir::SingleLLVMInstructionImpl&lt; LLVMT &gt;::verify</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp/#a5fe4041db3281600b33fbb1bde23f0d2">wrap</a>.</p>

</div>
</div>

### false {#a60ff0978cee670022cdc8743945e0eae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">aarch64 promote AArch64 Promote Constant false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>

</div>
</div>

### Pass {#a099cf45c11df5059934a293e57614b7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">aarch64 promote AArch64 Promote Constant Pass</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>

</div>
</div>

### Stress {#af2894a28a533f577c4252eae792e3358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; Stress("aarch64-stress-promote-const", cl::Hidden, cl::desc("Promote all vector constants"))</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"aarch64-promote-const"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp">AArch64PromoteConstant.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
