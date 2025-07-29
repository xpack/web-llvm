---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `NVVMReflect.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptx-h">NVPTX.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/constantfolding-h">llvm/Analysis/ConstantFolding.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">llvm/CodeGen/CommandFlags.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/institerator-h">llvm/IR/InstIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "llvm/IR/IntrinsicsNVPTX.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/scalar-h">llvm/Transforms/Scalar.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">llvm/Transforms/Utils/BasicBlockUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/local-h">llvm/Transforms/Utils/Local.h</a>"
#include &lt;algorithm&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-nvvmreflect-cpp-">anonymous{NVVMReflect.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-nvvmreflect-cpp-/nvvmreflect">NVVMReflect</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e8a6638e7b64cc6aba0d05792f81d4d">INITIALIZE_PASS</a> (NVVMReflect, "nvvm-reflect", "Replace occurrences of __nvvm_reflect() calls with 0/1", false, false) static bool runNVVMReflect(Function &amp;F</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e6b4a6cee1775e7acdae3d727257f56">if</a> (F.getName()==NVVM_REFLECT_FUNCTION||F.getName()==NVVM_REFLECT_OCL_FUNCTION)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae25b1e577bcd72ebc8b84b83aca02662">for</a> (Instruction &amp;I :instructions(F))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a503c0214540e80733c0a0c53c067e6ee">while</a> (!ToSimplify.empty())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a3bf42baf773b375802538951c88d8e12">ToRemove</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a272de407838df85f0919b0640aa79f9d">erase</a> (NewLastIter, ToRemove.end())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbe3fa02a27f967fb4552e3e608be5ce">for</a> (Instruction *I :ToRemove) I -&gt; eraseFromParent()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">return <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a3bf42baf773b375802538951c88d8e12">ToRemove</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac934769d93af95250952646a3829df4c">size</a> () &gt; 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa16d1af934620e70377be760f578a537">NVVMReflectEnabled</a>("nvvm-reflect-enable", cl::init(true), cl::Hidden, cl::desc("NVVM reflection, enabled by default"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c160330a72be529187cf78f9bac59ae">SmVersion</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5fd4f6372956a853ddbffb2ecc18ec6">ToRemove</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7912e2c418da1b73d4e33dc5342f1990">ToSimplify</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c2de85692b8bbe77b6a14a6882ef978">NewLastIter</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a48f85da577c6ce7d9aed90437dc0d07c">llvm::unique</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a3bf42baf773b375802538951c88d8e12">ToRemove</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b49e58433399077293d346d94a5bacd">NVVM_REFLECT_FUNCTION</a>&nbsp;&nbsp;&nbsp;"__nvvm_reflect"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ecc6f9dcbb50864488f3a611034b14d">NVVM_REFLECT_OCL_FUNCTION</a>&nbsp;&nbsp;&nbsp;"__nvvm_reflect_ocl"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"nvptx-reflect"</td>
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

### erase() {#a272de407838df85f0919b0640aa79f9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ToRemove erase (<a href="#a0c2de85692b8bbe77b6a14a6882ef978">NewLastIter</a>, ToRemove. end=())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp">NVVMReflect.cpp</a>.</p>


<p>References <a href="#a0c2de85692b8bbe77b6a14a6882ef978">NewLastIter</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a3bf42baf773b375802538951c88d8e12">ToRemove</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a10ef544bc053ce8ddd44b8eb29c008ee">llvm::StringMap&lt; std::nullopt_t, AllocatorTy &gt;::erase</a>.</p>

</div>
</div>

### for() {#ae25b1e577bcd72ebc8b84b83aca02662}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">for (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>  :instructions=F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp">NVVMReflect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#a86397deb1d9d25f7a17ce22c4d66482f">llvm::mdconst::extract_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a8b49e58433399077293d346d94a5bacd">NVVM_REFLECT_FUNCTION</a>, <a href="#a4ecc6f9dcbb50864488f3a611034b14d">NVVM_REFLECT_OCL_FUNCTION</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="#a9c160330a72be529187cf78f9bac59ae">SmVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a3bf42baf773b375802538951c88d8e12">ToRemove</a> and <a href="#a7912e2c418da1b73d4e33dc5342f1990">ToSimplify</a>.</p>

</div>
</div>

### for() {#adbe3fa02a27f967fb4552e3e608be5ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">for (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> :<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a3bf42baf773b375802538951c88d8e12">ToRemove</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp">NVVMReflect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a3bf42baf773b375802538951c88d8e12">ToRemove</a>.</p>

</div>
</div>

### if() {#a0e6b4a6cee1775e7acdae3d727257f56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">if (F. getName=()==<a href="#a8b49e58433399077293d346d94a5bacd">NVVM_REFLECT_FUNCTION</a>||<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">F.getName</a>()==<a href="#a4ecc6f9dcbb50864488f3a611034b14d">NVVM_REFLECT_OCL_FUNCTION</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp">NVVMReflect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a8b49e58433399077293d346d94a5bacd">NVVM_REFLECT_FUNCTION</a> and <a href="#a4ecc6f9dcbb50864488f3a611034b14d">NVVM_REFLECT_OCL_FUNCTION</a>.</p>

</div>
</div>

### INITIALIZE\_PASS() {#a2e8a6638e7b64cc6aba0d05792f81d4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (NVVMReflect, "nvvm-reflect", "Replace occurrences of __nvvm_reflect() calls with 0/1", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp">NVVMReflect.cpp</a>.</p>

</div>
</div>

### size() {#ac934769d93af95250952646a3829df4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">return ToRemove size ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp">NVVMReflect.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a3bf42baf773b375802538951c88d8e12">ToRemove</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a4c63f26f6c18bccde67513ce760b613a">_rpmalloc_aligned_allocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a27aafcff5a8ed8f91ea6b53ac93a0fbf">_rpmalloc_aligned_reallocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a3bef7e16a625f1968110eaf331332eb2">_rpmalloc_allocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#abd2feafaa32ab4fd14728c6f1b27cb76">_rpmalloc_allocate_huge</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a8bdabec99c6c3fe43d727ccd713ac112">_rpmalloc_allocate_large</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ac615e23f8046310bb788e678b486b20a">_rpmalloc_allocate_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a3dd2306a260dcdc3e852a2898914cbc6">_rpmalloc_allocate_small</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#afb297c8e6c20ce017a62ea42b70be194">_rpmalloc_mmap</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a833da3799d95ff35eae22f00833538b9">_rpmalloc_mmap_os</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a66c4be5ac967e1374b25eb8ac80f68d9">_rpmalloc_set_name</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#abfbbb8e2f9b086d466fe2898a283c98d">_rpmalloc_unmap</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a693c463bae081b54b0b799e97bf84fb5">_rpmalloc_unmap_os</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession/#a277f859f380850343d58cdd740d822b4">llvm::pdb::NativeSession::addressForRVA</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#a971504411945012a55fb2b0896bd8bd1">llvm::SmallString&lt; 0 &gt;::append</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a404cacae16324605710710194e08e5ca">llvm::dwarf_linker::parallel::SectionDescriptor::applyIntVal</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a4c0cd7586ca23f44571c798723fee65f">llvm::dwarf_linker::parallel::SectionDescriptor::applySLEB128</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a4e237e34d55840912a54fbef648eea92">llvm::dwarf_linker::parallel::SectionDescriptor::applyULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a32ff799dcb39887a8d21322020f305ba">llvm::CanonicalLoopInfo::assertOK</a>, <a href="/web-llvm/docs/api/classes/anonymous-metadataloader-cpp-/bitcodereadermetadatalist/#ab34dfb4b3bc93b771338508e1cc0e562">anonymous{MetadataLoader.cpp}::BitcodeReaderMetadataList::assignValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#aaf7853428d9cb2b59fe268b757e3dc16">llvm::MutableArrayRef&lt; uint8_t &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5b6faabb08339ea1dd11e9d37a668634">llvm::StringRef::back</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a0e686f0d790f0fd925a036c4cb50199b">CalculateUnswitchCostMultiplier</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae0c6424784f132b91eb387a3ee0b57c9">llvm::StringRef::compare</a>, <a href="/web-llvm/docs/api/classes/llvm/valueenumerator/#aa64b4492783129ceac44b1cb75eaaac5">llvm::ValueEnumerator::computeBitsRequiredForTypeIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/legacylegalizerinfo/#a6b586580f1e35e04ae0f3186fadd6594">llvm::LegacyLegalizerInfo::computeTables</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a3d42f23852edcd240ef3a605fdc2bcec">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::concat</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a14180977794bfc2a37dbffeef3ca20de">llvm::StringRef::consume_back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ac5fd848165f133bf149f8f27618ce313">llvm::StringRef::consume_back_insensitive</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ac66731b70af2ad5aded1ce13a20acb29">llvm::StringRef::copy</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ac2c31b7b3c778d12aa176f9253511f37">llvm::StringRef::count</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instrbuilder/#afe394be08220c92f22489a0f952d39ee">llvm::mca::InstrBuilder::createInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ae53a8455d8df0ace36f281ea470736c6">llvm::orc::createJITLoaderGDBRegistrar</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a9202ca0a40ca22c6198342cf8b0dc050">llvm::StringRef::detectEOL</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aa713e2599e000adc01ced998c05502a7">llvm::ArrayRef&lt; llvm::cfg::Update&lt; MachineBasicBlock * &gt; &gt;::drop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#ad1acfeed5712da9a4ffafda05fac15ac">llvm::MutableArrayRef&lt; uint8_t &gt;::drop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae2705fd641fb3d1eefa2691b5117cf22">llvm::StringRef::drop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a55089293ebaccd683a82d97170041376">llvm::ArrayRef&lt; llvm::cfg::Update&lt; MachineBasicBlock * &gt; &gt;::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#a23489fd833f61022bf08dbe3ba9f1973">llvm::MutableArrayRef&lt; uint8_t &gt;::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/dxilbitcodewriter/#ade090ef88b076e918fd2e278692729d5">llvm::dxil::DXILBitcodeWriter::DXILBitcodeWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#aeb6b320000ce736d5ac68e606fcc3519">llvm::MipsSEFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa587d71d9d14ad035e31b99fc0c90802">llvm::RISCVFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/loopdepthtree/#abcbd121c0c4a872933dca6722d4da55e">anonymous{LoopFuse.cpp}::LoopDepthTree::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/enumeratedarray/#a02857734c7744f486e5abacc1c42c9af">llvm::EnumeratedArray&lt; ValueType, Enumeration, LargestEnum, IndexType, Size &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree/#af6d8dcfd526383fe146bf9c0cd1c2999">llvm::OutlinedHashTree::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap/#a4b33abb63149544bcaf0019c9889d7fb">llvm::StableFunctionMap::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/enumeratedarray/#ad66b8012f0670c77b38b883a8d84a6b3">llvm::EnumeratedArray&lt; ValueType, Enumeration, LargestEnum, IndexType, Size &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/enumeratedarray/#a704be463fa5f355a6c70f65c3d8b21d6">llvm::EnumeratedArray&lt; ValueType, Enumeration, LargestEnum, IndexType, Size &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#a9d959094f4544749c129c46034cbed67">llvm::MutableArrayRef&lt; uint8_t &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aca439bf65258d9d8d057812938b617c5">llvm::StringRef::ends_with</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ae5898edb3343d9868fcc1234e0e66fb7">enlarge</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae46058c90a3c703357331a6501b32f1c">llvm::StringRef::equals_insensitive</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirbasicblock/#a1b80ef1bd7a976b5fa4b95052cfeebba">llvm::VPIRBasicBlock::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8f6d92157833612e9b4cd0085e181b7e">llvm::LegalizerHelper::fewerElementsVectorMultiEltType</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a24d07ee06f50c285b723a97222619ff0">llvm::StringRef::find_if</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector/#a4c665da429b0ef0e774843d0829ffadb">llvm::DWARFUnitVector::finishedInfoUnits</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#a86b1638912d3f2fbeaf9edffdaa00c10">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::getAsStr</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialconstantvalues/#ac6c45f02f71621808dd33da72d73cb00">llvm::AAPotentialConstantValues::getAssumedConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a7b4dfdd596d675a34ee339b581424255">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::getCPEAlign</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a5077615197d034930b58d221032e96f0">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::getCPEAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#af0b0733da2d8693287bd3bb04ee6ab80">llvm::RuntimeDyldCOFF::getDLLImportOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a6e4cc243fb344193485e9e4fe79399c7">llvm::dwarf_linker::parallel::SectionDescriptor::getIntVal</a>, <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile/#ad79b94d312ad221c9d2b49357633a223">llvm::object::MinidumpFile::getMemory64List</a>, <a href="/web-llvm/docs/api/classes/anonymous-metadataloader-cpp-/bitcodereadermetadatalist/#a0d83ae7cd68298cd3f6a7b5b8aa67516">anonymous{MetadataLoader.cpp}::BitcodeReaderMetadataList::getMetadataFwdRef</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector/#a200eebec447ce4a311390379f322dd86">llvm::DWARFUnitVector::getNumInfoUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector/#a6e9ac3452a271b08374bac97a1290496">llvm::DWARFUnitVector::getNumTypesUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector/#a77655394de93c2b51bb4f32587e452a6">llvm::DWARFUnitVector::getNumUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#a005329aa15a8ea20232fa18fc2cba61d">llvm::cl::generic_parser_base::getOptionWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/bits/#a9c1bc79f9e32510408dd106c818e7290">llvm::cl::bits&lt; DataType, Storage, ParserClass &gt;::getPosition</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ac437e7230f2990fd60bf089f20ea2e78">llvm::X86TargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a1be43761db2568933db89648201ab15c">llvm::SIRegisterInfo::getSubRegFromChannel</a>, <a href="/web-llvm/docs/api/files/lib/lib/windowsdriver/msvcpaths-cpp/#a721a1e2b9fcfe5e633cb413a6eabed8b">getSystemRegistryString</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/vloperands/#a017e1ed67d6b197edc2e79bb8bbdd769">llvm::slpvectorizer::BoUpSLP::VLOperands::getVL</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#a0fef5db8f0b473292cb9770075050da5">llvm::SmallVectorBase&lt; Size_T &gt;::grow_pod</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registerset/#a7f1ed280a80d821d3b1ae74e61768cb6">anonymous{HexagonGenInsert.cpp}::RegisterSet::has</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9031658af970d96ad739450ec380d86a">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorloopcarriedreuse-cpp-/depchain/#aa56915b9a5d950216a08e31def005c52">anonymous{HexagonVectorLoopCarriedReuse.cpp}::DepChain::isIdentical</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#aded1d376d952f6c163f1020aca8a7d67">llvm::ShuffleVectorInst::isReplicationMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp/#a3e3ecc5f07c46d1e37b8d7cff83982e6">isRightAfterData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02e1ff75cab81386059f88d395054b1c">llvm::isSafeToUnrollAndJam</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a887f706b50e717186a63585e31bbab32">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isSingle</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorloopcarriedreuse-cpp-/depchain/#ab6e99743d79b323bc759b4764c457dda">anonymous{HexagonVectorLoopCarriedReuse.cpp}::DepChain::iterations</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ab8a7c054bcb1baa4c5445edff7c1580e">llvm::HexagonTargetLowering::LowerCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#af4911ff1c4fabd84b05d4529da80021e">llvm::SPIRVCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#ae22f2d3294d95f6cb262f8732eb0f479">llvm::X86CallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a4119a7f5d262af0d89332b5c2d30abbc">llvm::AMDGPUCallLowering::lowerFormalArgumentsKernel</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a5d35bdf8fd7ab1b1854b23c27795d6e4">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::lowerSpecialLDSVariables</a>, <a href="/web-llvm/docs/api/groups/llvmclto/#gaf4e64e6d599e7d40b3c05a169def0bdb">lto_input_get_dependent_library</a>, <a href="/web-llvm/docs/api/groups/llvmclto/#ga2221e1ea6d3053c540ccd3eb078ab749">lto_runtime_lib_symbols_list</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8265efd805e4ce0c9d3c18e78194324c">llvm::StringRef::ltrim</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#acd2e33f03956821cbf94c4cd5da01bdd">llvm::StringRef::ltrim</a>, <a href="/web-llvm/docs/api/classes/llvm/globalmergefunc/#a31ba90bd367677d2bf4065d6e51eca65">llvm::GlobalMergeFunc::merge</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase/#a75538db633297fb9c0b91ea5a16c5b72">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::ModuleBitcodeWriterBase</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/namestate/#a5ea3bdd076ba31ca6e06cb40948f11da">AbstractManglingParser&lt; Derived, Alloc &gt;::NameState::NameState</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/recyclingallocator-h/#adb9ea5e525d426a0a46be17f04de48a5">operator new</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ab9d50c6284d5976200ef42a076d3fb02">llvm::SmallString&lt; 0 &gt;::operator std::string</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aed45f95729e679cb0c160456fe94602b">llvm::StringRef::operator std::string_view</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a36ad912277e94ac8b0db66aae63e49ad">llvm::operator+=</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#ae24e16fd0d1360c87567b37969904d1a">llvm::StringMap&lt; std::nullopt_t, AllocatorTy &gt;::operator==</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registerset/#a2bc851bde979df6d33f160c57afb6416">anonymous{HexagonGenInsert.cpp}::RegisterSet::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#aaed2ef7ac9490f46b0eacddd11dd015d">llvm::MutableArrayRef&lt; uint8_t &gt;::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3ae8d94051e57dabbf8ffabfcbc9063d">llvm::StringRef::operator[]</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#aa91d3c1b093e3561b948794724961f4b">anonymous{AsmParser.cpp}::AsmParser::parseIdentifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#af6dea9845d70ac952115bdbe378dbea1">anonymous{MasmParser.cpp}::MasmParser::parseIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/r600schedstrategy/#a3351536ef89bb6fe156f754d2ee7c24c">llvm::R600SchedStrategy::pickNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlineorder-cpp-/priorityinlineorder/#a4b10225665f101095f9bc3e2dca97479">anonymous{InlineOrder.cpp}::PriorityInlineOrder&lt; PriorityT &gt;::pop</a>, <a href="/web-llvm/docs/api/classes/llvm/nodeset/#a2a59bac3131695df6254a8db3205caeb">llvm::NodeSet::print</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registerset/#a7d466728ce72f2c39e383cd2606d9042">anonymous{HexagonGenInsert.cpp}::RegisterSet::remove</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/vloperands/#ab3635230226f6d60dad04b8e83d848fd">llvm::slpvectorizer::BoUpSLP::VLOperands::reorder</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a97d45ce069c1a09ca84672df63acf096">llvm::StringRef::rfind</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a76c23d646a743db9d2576b599b3d01fc">rpaligned_alloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ae572e25a23de1a9793b4e5b1ec0550b1">rpaligned_calloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h/#afacba300cb4003f3f47f2e2ef5dd4085">rpaligned_calloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a4f191e772a1cda4fb5de7300bac4ea37">rpaligned_realloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a5627c7b5f1dc087ce096df1c787b5ecf">rpcalloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-h/#a6640211f01727c7df7fe2bd876dbfc70">rpcalloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2727f400656ed5d5857d7a6e1e05b61b">rpmalloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a61de67ff29b3d0e5d130ac9a7d0d2538">rpmemalign</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ae6f35022f9384e2a22ed2b96c00995b2">rpposix_memalign</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a8f9643796f1e94fcc804c5c97a7985e9">rprealloc</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a9b52404a8d2877d3b32ebb5d1f5c72ff">llvm::StringRef::rtrim</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#acf544fca0b0f46e00e4261bc925104e5">llvm::StringRef::rtrim</a>, <a href="/web-llvm/docs/api/classes/anonymous-armconstantislandpass-cpp-/armconstantislands/#aaf4297850ccff6052205f45bc2ba2f87">anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a931125c9821366d0a4f14a4f8e423f95">llvm::AMDGPUAsmPrinter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/abstractmanglingparser/scopedtemplateparamlist/#a702222f4cfb0fa82353225f0a8e88d9b">AbstractManglingParser&lt; Derived, Alloc &gt;::ScopedTemplateParamList::ScopedTemplateParamList</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#ad6c3837b7fc8ef9d70ddea519de3e06b">llvm::SplitEditor::selectIntv</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#add9d8e7cc38ac083f42ce6873a8defdd">separateNestedLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/legacylegalizerinfo/#a9ed946c9bc8e7367d6a31582048c8570">llvm::LegacyLegalizerInfo::setAction</a>, <a href="/web-llvm/docs/api/classes/llvm/legacylegalizerinfo/#ac118cc8e04f71fc897c5a84874595eb0">llvm::LegacyLegalizerInfo::setLegalizeScalarToDifferentSizeStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/legacylegalizerinfo/#ad67cd16a1da06553bb4936551f67c7d0">llvm::LegacyLegalizerInfo::setLegalizeVectorElementToDifferentSizeStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap/#ae1fb19692a65ccb8fbbc98a39ccf73a5">llvm::SmallDenseMap&lt; LocPair, CacheEntry, 8 &gt;::shrink_and_clear</a>, <a href="/web-llvm/docs/api/classes/anonymous-metadataloader-cpp-/bitcodereadermetadatalist/#acc739dbfdc649bee0330488d1e42a3f5">anonymous{MetadataLoader.cpp}::BitcodeReaderMetadataList::shrinkTo</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a4103353fd223c191f291d3ffaf5bfa4f">llvm::SIRegisterInfo::SIRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-278ceb76ae7482b6d9279b9275c5dc4a/#a3f91673fe731f5619c5cf2130870bc2e">llvm::orc::shared::SPSSerializationTraits&lt; SPSTuple&lt; SPSTagTs... &gt;, std::tuple&lt; Ts... &gt; &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/adl-detail/#a1645efd1749d8e268bce121463435964">llvm::adl_detail::size_impl</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; llvm::cfg::Update&lt; MachineBasicBlock * &gt; &gt;::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#a526a7f286fa3dbf805ff61fbb35d84f7">llvm::MutableArrayRef&lt; uint8_t &gt;::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#ae671f7b11f895cb673f6ee9a3c694359">llvm::MutableArrayRef&lt; uint8_t &gt;::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5d4c961b9b6f1da17df74b4496ecb30e">llvm::StringRef::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#af5dd7241878be5eed07736eb156bb10b">llvm::SmallString&lt; 0 &gt;::str</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac1f72f67a93986bb68c8b7f8a2dba4ba">llvm::ArrayRef&lt; llvm::cfg::Update&lt; MachineBasicBlock * &gt; &gt;::take_back</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#a2efcc9f83bc3a5da3fbfc9feb047a7a0">llvm::MutableArrayRef&lt; uint8_t &gt;::take_back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a9fe565cb0cc832480a9a9ed312dc2962">llvm::StringRef::take_back</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a33da2ddf6f447892591c86d9d3771b9c">llvm::ArrayRef&lt; llvm::cfg::Update&lt; MachineBasicBlock * &gt; &gt;::take_front</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#af7f90a0fd93435c0e075d55928d4320d">llvm::MutableArrayRef&lt; uint8_t &gt;::take_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aa28286a33491b5d9a936fb6ae853baee">llvm::StringRef::take_front</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodaghvx-cpp-/resultstack/#a63257c4adc136546e70b51f90de1b956">anonymous{HexagonISelDAGToDAGHVX.cpp}::ResultStack::top</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/dllimportdefinitiongenerator/#a28474a2103675aa30411c3cc01585b0c">llvm::orc::DLLImportDefinitionGenerator::tryToGenerate</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#a6aaeb440ac0f45225f89b6b83444db1a">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::updateImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#aabed4dadfe0a32d2cc856553788212ba">upgradeArmOrAarch64IntrinsicFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a3f77e2cab72167554d1d13c44fc9877d">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::verifyGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/wasm/writer/#a0c6b0217a29520ff740cb32952eac94f">llvm::objcopy::wasm::Writer::write</a> and <a href="/web-llvm/docs/api/structs/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/exprlinearizer/#a4cf50167dfbcc11002f483718ac75556">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::ExprLinearizer::writeFnName</a>.</p>

</div>
</div>

### while() {#a503c0214540e80733c0a0c53c067e6ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">while (!ToSimplify. empty=())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp">NVVMReflect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> and <a href="#a7912e2c418da1b73d4e33dc5342f1990">ToSimplify</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dagdeltaalgorithm-cpp-/dagdeltaalgorithmimpl/#adee0e07a9f4606d965c319cd0b62052c">anonymous{DAGDeltaAlgorithm.cpp}::DAGDeltaAlgorithmImpl::DAGDeltaAlgorithmImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvregularizer-cpp/#a70c9d5004bb64ce7c4ed2dab4acda63b">INITIALIZE_PASS</a> and <a href="/web-llvm/docs/api/classes/anonymous-tailduplication-cpp-/tailduplicatebaselegacy/#a78a8906bfe5ee3db7d500fa09d238b8b">anonymous{TailDuplication.cpp}::TailDuplicateBaseLegacy::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### NewLastIter {#a0c2de85692b8bbe77b6a14a6882ef978}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto NewLastIter = <a href="/web-llvm/docs/api/namespaces/llvm/#a48f85da577c6ce7d9aed90437dc0d07c">llvm::unique</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a3bf42baf773b375802538951c88d8e12">ToRemove</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp">NVVMReflect.cpp</a>.</p>


<p>Referenced by <a href="#a272de407838df85f0919b0640aa79f9d">erase</a>.</p>

</div>
</div>

### NVVMReflectEnabled {#aa16d1af934620e70377be760f578a537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; NVVMReflectEnabled("nvvm-reflect-enable", cl::init(true), cl::Hidden, cl::desc("NVVM reflection, enabled by default"))</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp">NVVMReflect.cpp</a>.</p>

</div>
</div>

### SmVersion {#a9c160330a72be529187cf78f9bac59ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SmVersion</td>
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
<div class="doxyVerbatim">{
  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (!<a href="#aa16d1af934620e70377be760f578a537">NVVMReflectEnabled</a>)
    return false
</div>
</dd>
</dl>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp">NVVMReflect.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aafb586a7c2ebc9a3f986906f1b479cc3">llvm::createNVPTXCtorDtorLoweringLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2846ea3beb3d5b3234de823a7765676d">llvm::createNVVMReflectPass</a>, <a href="#ae25b1e577bcd72ebc8b84b83aca02662">for</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae2780d9409416f3a9ba64201fd887888">PerformSETCCCombine</a>.</p>

</div>
</div>

### ToRemove {#ad5fd4f6372956a853ddbffb2ecc18ec6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Instruction *, 4&gt; ToRemove</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp">NVVMReflect.cpp</a>.</p>

</div>
</div>

### ToSimplify {#a7912e2c418da1b73d4e33dc5342f1990}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Instruction *, 4&gt; ToSimplify</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp">NVVMReflect.cpp</a>.</p>


<p>Referenced by <a href="#ae25b1e577bcd72ebc8b84b83aca02662">for</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/instsimplifypass-cpp/#a49359723de1a046072e8cc931068d43f">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinstsimplify-cpp/#ac7156f23f48b5eb96ead0522896d7574">simplifyLoopInst</a> and <a href="#a503c0214540e80733c0a0c53c067e6ee">while</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"nvptx-reflect"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp">NVVMReflect.cpp</a>.</p>

</div>
</div>

### NVVM\_REFLECT\_FUNCTION {#a8b49e58433399077293d346d94a5bacd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define NVVM_REFLECT_FUNCTION&nbsp;&nbsp;&nbsp;"__nvvm_reflect"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp">NVVMReflect.cpp</a>.</p>


<p>Referenced by <a href="#ae25b1e577bcd72ebc8b84b83aca02662">for</a> and <a href="#a0e6b4a6cee1775e7acdae3d727257f56">if</a>.</p>

</div>
</div>

### NVVM\_REFLECT\_OCL\_FUNCTION {#a4ecc6f9dcbb50864488f3a611034b14d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define NVVM_REFLECT_OCL_FUNCTION&nbsp;&nbsp;&nbsp;"__nvvm_reflect_ocl"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp">NVVMReflect.cpp</a>.</p>


<p>Referenced by <a href="#ae25b1e577bcd72ebc8b84b83aca02662">for</a> and <a href="#a0e6b4a6cee1775e7acdae3d727257f56">if</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
