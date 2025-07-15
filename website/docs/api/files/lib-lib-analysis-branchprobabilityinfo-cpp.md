---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/branchprobabilityinfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `BranchProbabilityInfo.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">llvm/Analysis/BranchProbabilityInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/postorderiterator-h">llvm/ADT/PostOrderIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/scciterator-h">llvm/ADT/SCCIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/constantfolding-h">llvm/Analysis/ConstantFolding.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">llvm/Analysis/LoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/postdominators-h">llvm/Analysis/PostDominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cfg-h">llvm/IR/CFG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/profdatautils-h">llvm/IR/ProfDataUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">llvm/Support/BranchProbability.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;map&gt;
#include &lt;utility&gt;
</div>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98934762d122e5b344bafd36c369d35c">ProbabilityList</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ad5391b0e7ea29306fee576182dabbf">ProbabilityTable</a> = std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a>, <a href="#a98934762d122e5b344bafd36c369d35c">ProbabilityList</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">BlockExecWeight : std::uint32_t { <a href="#a0bab6cbda2c6f1e9dd352004a6b9f393">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of dedicated "absolute" execution weights for a block. <a href="#a0bab6cbda2c6f1e9dd352004a6b9f393">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c0db623aadd71d3caf0937e7c830691">INITIALIZE_PASS_BEGIN</a> (BranchProbabilityInfoWrapperPass, "branch-prob", "Branch Probability Analysis", false, true) INITIALIZE_PASS_END(BranchProbabilityInfoWrapperPass</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44f69d9faa72e970316989f65d054c59">PtrTakenProb</a> (PH_TAKEN_WEIGHT, PH_TAKEN_WEIGHT+PH_NONTAKEN_WEIGHT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f0d3e324489e13def109f268e27d5dc">PtrUntakenProb</a> (PH_NONTAKEN_WEIGHT, PH_TAKEN_WEIGHT+PH_NONTAKEN_WEIGHT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5be5ee158531203bf7471424e2ea4866">ZeroTakenProb</a> (ZH_TAKEN_WEIGHT, ZH_TAKEN_WEIGHT+ZH_NONTAKEN_WEIGHT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a202467d2d7ce0b47448bc909631c6950">ZeroUntakenProb</a> (ZH_NONTAKEN_WEIGHT, ZH_TAKEN_WEIGHT+ZH_NONTAKEN_WEIGHT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33a9f0b8ca86e37a2b9c2f3a0480727b">FPOrdTakenProb</a> (FPH_ORD_WEIGHT, FPH_ORD_WEIGHT+FPH_UNO_WEIGHT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5de2d80fbf11d57c77cb9a621441753b">FPOrdUntakenProb</a> (FPH_UNO_WEIGHT, FPH_ORD_WEIGHT+FPH_UNO_WEIGHT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75a205911ec3ff2d9cdd4017c2efc5d2">FPTakenProb</a> (FPH_TAKEN_WEIGHT, FPH_TAKEN_WEIGHT+FPH_NONTAKEN_WEIGHT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a188a295bab13e344682c59d4ce619a12">FPUntakenProb</a> (FPH_NONTAKEN_WEIGHT, FPH_TAKEN_WEIGHT+FPH_NONTAKEN_WEIGHT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade155905429b0a259a1030f418c04ad9">computeUnlikelySuccessors</a> (const BasicBlock *BB, Loop *L, SmallPtrSetImpl&lt; const BasicBlock * &gt; &amp;UnlikelyBlocks)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af17aeb0484c720fb1e197adf768961c7">PrintBranchProb</a>("print-bpi", cl::init(false), cl::Hidden, cl::desc("Print the branch probability info."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4ed89c6d8e92b055e0561a615dcbaf6">PrintBranchProbFuncName</a>("print-bpi-func-name", cl::Hidden, cl::desc("The option to specify the name of the function " "whose branch probability info is printed."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">branch</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bd4799263bb66b1eaf06927f08e7b64">prob</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">branch Branch Probability</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dd3f5f985cea603b3f6ea0df17409d5">Analysis</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">branch Branch Probability</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba35dee6889430a15098748f5ef5ec1d">false</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a205d7293fcfbe714464bceef72495dde">LBH_TAKEN_WEIGHT</a> = 124</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6c00f8033a3bf9ab5f49143e30d8c52">LBH_NONTAKEN_WEIGHT</a> = 4</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafc5237f3585710400d8a15b43ff0e5b">UR_TAKEN_PROB</a> = BranchProbability::getRaw(1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unreachable-terminating branch taken probability. <a href="#aafc5237f3585710400d8a15b43ff0e5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b89b3ae3e1706f0f437db6621986deb">PH_TAKEN_WEIGHT</a> = 20</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Heuristics and lookup tables for non-loop branches: Pointer Heuristics (PH) <a href="#a6b89b3ae3e1706f0f437db6621986deb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38a9f81723daa4bec614eaba36d40b85">PH_NONTAKEN_WEIGHT</a> = 12</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3ad5391b0e7ea29306fee576182dabbf">ProbabilityTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac81ca00b5db15ff5c054c569fadd72dd">PointerTable</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer comparisons: <a href="#ac81ca00b5db15ff5c054c569fadd72dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa5928aa2f68d1c15bd7dafa3745b0fa">ZH_TAKEN_WEIGHT</a> = 20</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Zero Heuristics (ZH) <a href="#aaa5928aa2f68d1c15bd7dafa3745b0fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2486cb22b39b4593d78671702f062b81">ZH_NONTAKEN_WEIGHT</a> = 12</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3ad5391b0e7ea29306fee576182dabbf">ProbabilityTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38332cb5dc3c73636aa6495114e7a5ab">ICmpWithZeroTable</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Integer compares with 0: <a href="#a38332cb5dc3c73636aa6495114e7a5ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3ad5391b0e7ea29306fee576182dabbf">ProbabilityTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b8ec1580eb2f1edaeb6257712dca6b5">ICmpWithMinusOneTable</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Integer compares with -1: <a href="#a2b8ec1580eb2f1edaeb6257712dca6b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3ad5391b0e7ea29306fee576182dabbf">ProbabilityTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8c67f6b4ae26d6e248b2b213f0b9217">ICmpWithOneTable</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Integer compares with 1: <a href="#aa8c67f6b4ae26d6e248b2b213f0b9217">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3ad5391b0e7ea29306fee576182dabbf">ProbabilityTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a275618493c15713c49bc2947a10fa12d">ICmpWithLibCallTable</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>strcmp and similar functions return zero, negative, or positive, if the first string is equal, less, or greater than the second. <a href="#a275618493c15713c49bc2947a10fa12d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16edcd8b45785ee12c576c73fe3218c9">FPH_TAKEN_WEIGHT</a> = 20</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadf81261b3ac34f57dc2d663bd8c2f4d">FPH_NONTAKEN_WEIGHT</a> = 12</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceb920a7c91b520ddbda086a10a8cfde">FPH_ORD_WEIGHT</a> = 1024 * 1024 - 1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the probability for an ordered floating point comparison. <a href="#aceb920a7c91b520ddbda086a10a8cfde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf1ae2fc274d3e7ef0204214943c017f">FPH_UNO_WEIGHT</a> = 1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the probability for an unordered floating point comparison, it means one or two of the operands are NaN. <a href="#adf1ae2fc274d3e7ef0204214943c017f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3ad5391b0e7ea29306fee576182dabbf">ProbabilityTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5ac9b2a71cf00215c4cd8f7914eedba">FCmpTable</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Floating-Point compares: <a href="#ac5ac9b2a71cf00215c4cd8f7914eedba">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"branch-prob"</td>
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

### ProbabilityList {#a98934762d122e5b344bafd36c369d35c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using ProbabilityList =  SmallVector&lt;BranchProbability&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### ProbabilityTable {#a3ad5391b0e7ea29306fee576182dabbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using ProbabilityTable =  std::map&lt;CmpInst::Predicate, ProbabilityList&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### BlockExecWeight {#a0bab6cbda2c6f1e9dd352004a6b9f393}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class BlockExecWeight : std::uint32_t</td>
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

<p>Set of dedicated "absolute" execution weights for a block.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZERO<a id="a0bab6cbda2c6f1e9dd352004a6b9f393a529e9e0beb5f85d1f132917c1a09860c"></a></td>
<td class="doxyEnumItemDescription">Special weight used for cases with exact zero probability (= 0x0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOWEST_NON_ZERO<a id="a0bab6cbda2c6f1e9dd352004a6b9f393a73be61fb26fc56377050ab1e85eab645"></a></td>
<td class="doxyEnumItemDescription">Minimal possible non zero weight (= 0x1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNREACHABLE<a id="a0bab6cbda2c6f1e9dd352004a6b9f393a58fd3b3b1f27606728077423eb21d8d6"></a></td>
<td class="doxyEnumItemDescription">Weight to an 'unreachable' block (= ZERO)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NORETURN<a id="a0bab6cbda2c6f1e9dd352004a6b9f393a25c263e3b7486f9453d37151d62ff7d1"></a></td>
<td class="doxyEnumItemDescription">Weight to a block containing non returning call (= LOWEST_NON_ZERO)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND<a id="a0bab6cbda2c6f1e9dd352004a6b9f393a37b88a87188456429fa6e6c31a6d2301"></a></td>
<td class="doxyEnumItemDescription">Weight to 'unwind' block of an invoke instruction (= LOWEST_NON_ZERO)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COLD<a id="a0bab6cbda2c6f1e9dd352004a6b9f393a3f7ff4daa99912d1b0c8c64340edb9fb"></a></td>
<td class="doxyEnumItemDescription">Weight to a 'cold' block (= 0xffff)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DEFAULT<a id="a0bab6cbda2c6f1e9dd352004a6b9f393a5b39c8b553c821e7cddc6da64b5bd2ee"></a></td>
<td class="doxyEnumItemDescription">Default weight is used in cases when there is no dedicated execution weight set (= 0xfffff)</td>
</tr>

</table>
</dd>
</dl>


<p>These weights are meaningful relative to each other and their derivatives only.</p>


<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### computeUnlikelySuccessors() {#ade155905429b0a259a1030f418c04ad9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void computeUnlikelySuccessors (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; UnlikelyBlocks)</td>
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



<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a964455f36837281d37f2a44e2fcb4cca">llvm::ConstantFoldBinaryOpOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3cd3a3ec28036937ecebe767498ba55d">llvm::ConstantFoldCompareInstOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aebd4af5642453ce3169094f08dd3d7b8">llvm::BranchInst::getCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a858cab21fd29000697171b2f5b4bde31">llvm::BasicBlock::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">llvm::CmpInst::getPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aa05da2b94b366573d1651d5b163c521e">llvm::BranchInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aef9e9fcf4c5dfce90276ca16d91b8e46">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a7e4be8b16fbd68c9045a388904044e01">llvm::BranchInst::isConditional</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>

</div>
</div>

### FPOrdTakenProb() {#a33a9f0b8ca86e37a2b9c2f3a0480727b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BranchProbability FPOrdTakenProb (<a href="#aceb920a7c91b520ddbda086a10a8cfde">FPH_ORD_WEIGHT</a>, <a href="#aceb920a7c91b520ddbda086a10a8cfde">FPH_ORD_WEIGHT</a>+ FPH_UNO_WEIGHT)</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>References <a href="#aceb920a7c91b520ddbda086a10a8cfde">FPH_ORD_WEIGHT</a> and <a href="#adf1ae2fc274d3e7ef0204214943c017f">FPH_UNO_WEIGHT</a>.</p>

</div>
</div>

### FPOrdUntakenProb() {#a5de2d80fbf11d57c77cb9a621441753b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BranchProbability FPOrdUntakenProb (<a href="#adf1ae2fc274d3e7ef0204214943c017f">FPH_UNO_WEIGHT</a>, <a href="#aceb920a7c91b520ddbda086a10a8cfde">FPH_ORD_WEIGHT</a>+ FPH_UNO_WEIGHT)</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>References <a href="#aceb920a7c91b520ddbda086a10a8cfde">FPH_ORD_WEIGHT</a> and <a href="#adf1ae2fc274d3e7ef0204214943c017f">FPH_UNO_WEIGHT</a>.</p>

</div>
</div>

### FPTakenProb() {#a75a205911ec3ff2d9cdd4017c2efc5d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BranchProbability FPTakenProb (<a href="#a16edcd8b45785ee12c576c73fe3218c9">FPH_TAKEN_WEIGHT</a>, <a href="#a16edcd8b45785ee12c576c73fe3218c9">FPH_TAKEN_WEIGHT</a>+ FPH_NONTAKEN_WEIGHT)</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>References <a href="#aadf81261b3ac34f57dc2d663bd8c2f4d">FPH_NONTAKEN_WEIGHT</a> and <a href="#a16edcd8b45785ee12c576c73fe3218c9">FPH_TAKEN_WEIGHT</a>.</p>

</div>
</div>

### FPUntakenProb() {#a188a295bab13e344682c59d4ce619a12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BranchProbability FPUntakenProb (<a href="#aadf81261b3ac34f57dc2d663bd8c2f4d">FPH_NONTAKEN_WEIGHT</a>, <a href="#a16edcd8b45785ee12c576c73fe3218c9">FPH_TAKEN_WEIGHT</a>+ FPH_NONTAKEN_WEIGHT)</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>References <a href="#aadf81261b3ac34f57dc2d663bd8c2f4d">FPH_NONTAKEN_WEIGHT</a> and <a href="#a16edcd8b45785ee12c576c73fe3218c9">FPH_TAKEN_WEIGHT</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#a2c0db623aadd71d3caf0937e7c830691}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (<a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfowrapperpass">BranchProbabilityInfoWrapperPass</a>, "branch-prob", "Branch Probability Analysis", false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### PtrTakenProb() {#a44f69d9faa72e970316989f65d054c59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BranchProbability PtrTakenProb (<a href="#a6b89b3ae3e1706f0f437db6621986deb">PH_TAKEN_WEIGHT</a>, <a href="#a6b89b3ae3e1706f0f437db6621986deb">PH_TAKEN_WEIGHT</a>+ PH_NONTAKEN_WEIGHT)</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>References <a href="#a38a9f81723daa4bec614eaba36d40b85">PH_NONTAKEN_WEIGHT</a> and <a href="#a6b89b3ae3e1706f0f437db6621986deb">PH_TAKEN_WEIGHT</a>.</p>

</div>
</div>

### PtrUntakenProb() {#a7f0d3e324489e13def109f268e27d5dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BranchProbability PtrUntakenProb (<a href="#a38a9f81723daa4bec614eaba36d40b85">PH_NONTAKEN_WEIGHT</a>, <a href="#a6b89b3ae3e1706f0f437db6621986deb">PH_TAKEN_WEIGHT</a>+ PH_NONTAKEN_WEIGHT)</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>References <a href="#a38a9f81723daa4bec614eaba36d40b85">PH_NONTAKEN_WEIGHT</a> and <a href="#a6b89b3ae3e1706f0f437db6621986deb">PH_TAKEN_WEIGHT</a>.</p>

</div>
</div>

### ZeroTakenProb() {#a5be5ee158531203bf7471424e2ea4866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BranchProbability ZeroTakenProb (<a href="#aaa5928aa2f68d1c15bd7dafa3745b0fa">ZH_TAKEN_WEIGHT</a>, <a href="#aaa5928aa2f68d1c15bd7dafa3745b0fa">ZH_TAKEN_WEIGHT</a>+ ZH_NONTAKEN_WEIGHT)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>References <a href="#a2486cb22b39b4593d78671702f062b81">ZH_NONTAKEN_WEIGHT</a> and <a href="#aaa5928aa2f68d1c15bd7dafa3745b0fa">ZH_TAKEN_WEIGHT</a>.</p>

</div>
</div>

### ZeroUntakenProb() {#a202467d2d7ce0b47448bc909631c6950}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BranchProbability ZeroUntakenProb (<a href="#a2486cb22b39b4593d78671702f062b81">ZH_NONTAKEN_WEIGHT</a>, <a href="#aaa5928aa2f68d1c15bd7dafa3745b0fa">ZH_TAKEN_WEIGHT</a>+ ZH_NONTAKEN_WEIGHT)</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>References <a href="#a2486cb22b39b4593d78671702f062b81">ZH_NONTAKEN_WEIGHT</a> and <a href="#aaa5928aa2f68d1c15bd7dafa3745b0fa">ZH_TAKEN_WEIGHT</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### Analysis {#a7dd3f5f985cea603b3f6ea0df17409d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">branch Branch Probability Analysis</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### false {#aba35dee6889430a15098748f5ef5ec1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">branch Branch Probability false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### FCmpTable {#ac5ac9b2a71cf00215c4cd8f7914eedba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ProbabilityTable FCmpTable</td>
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

<p>Floating-Point compares:</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
    {FCmpInst::FCMP_ORD, {<a href="#a33a9f0b8ca86e37a2b9c2f3a0480727b">FPOrdTakenProb</a>, <a href="#a5de2d80fbf11d57c77cb9a621441753b">FPOrdUntakenProb</a>}}, 
    {FCmpInst::FCMP_UNO, {<a href="#a5de2d80fbf11d57c77cb9a621441753b">FPOrdUntakenProb</a>, <a href="#a33a9f0b8ca86e37a2b9c2f3a0480727b">FPOrdTakenProb</a>}}, 
}
</div>
</dd>
</dl>

<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### FPH\_NONTAKEN\_WEIGHT {#aadf81261b3ac34f57dc2d663bd8c2f4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t FPH_NONTAKEN_WEIGHT = 12</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>Referenced by <a href="#a75a205911ec3ff2d9cdd4017c2efc5d2">FPTakenProb</a> and <a href="#a188a295bab13e344682c59d4ce619a12">FPUntakenProb</a>.</p>

</div>
</div>

### FPH\_ORD\_WEIGHT {#aceb920a7c91b520ddbda086a10a8cfde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t FPH_ORD_WEIGHT = 1024 * 1024 - 1</td>
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

<p>This is the probability for an ordered floating point comparison.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>Referenced by <a href="#a33a9f0b8ca86e37a2b9c2f3a0480727b">FPOrdTakenProb</a> and <a href="#a5de2d80fbf11d57c77cb9a621441753b">FPOrdUntakenProb</a>.</p>

</div>
</div>

### FPH\_TAKEN\_WEIGHT {#a16edcd8b45785ee12c576c73fe3218c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t FPH_TAKEN_WEIGHT = 20</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>Referenced by <a href="#a75a205911ec3ff2d9cdd4017c2efc5d2">FPTakenProb</a> and <a href="#a188a295bab13e344682c59d4ce619a12">FPUntakenProb</a>.</p>

</div>
</div>

### FPH\_UNO\_WEIGHT {#adf1ae2fc274d3e7ef0204214943c017f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t FPH_UNO_WEIGHT = 1</td>
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

<p>This is the probability for an unordered floating point comparison, it means one or two of the operands are NaN.</p>


<p>Usually it is used to test for an exceptional case, so the result is unlikely.</p>


<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>Referenced by <a href="#a33a9f0b8ca86e37a2b9c2f3a0480727b">FPOrdTakenProb</a> and <a href="#a5de2d80fbf11d57c77cb9a621441753b">FPOrdUntakenProb</a>.</p>

</div>
</div>

### ICmpWithLibCallTable {#a275618493c15713c49bc2947a10fa12d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ProbabilityTable ICmpWithLibCallTable</td>
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

<p>strcmp and similar functions return zero, negative, or positive, if the first string is equal, less, or greater than the second.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
    {CmpInst::ICMP_EQ, {<a href="#a202467d2d7ce0b47448bc909631c6950">ZeroUntakenProb</a>, <a href="#a5be5ee158531203bf7471424e2ea4866">ZeroTakenProb</a>}},
    {CmpInst::ICMP_NE, {<a href="#a5be5ee158531203bf7471424e2ea4866">ZeroTakenProb</a>, <a href="#a202467d2d7ce0b47448bc909631c6950">ZeroUntakenProb</a>}},
}
</div>
</dd>
</dl>


<p>We consider it likely that the strings are not equal, so a comparison with zero is probably false, but also a comparison with any other number is also probably false given that what exactly is returned for nonzero values is not specified. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> kind of comparison other than equality we know nothing about.</p>


<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### ICmpWithMinusOneTable {#a2b8ec1580eb2f1edaeb6257712dca6b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ProbabilityTable ICmpWithMinusOneTable</td>
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

<p>Integer compares with -1:</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
    {CmpInst::ICMP_EQ, {<a href="#a202467d2d7ce0b47448bc909631c6950">ZeroUntakenProb</a>, <a href="#a5be5ee158531203bf7471424e2ea4866">ZeroTakenProb</a>}},  
    {CmpInst::ICMP_NE, {<a href="#a5be5ee158531203bf7471424e2ea4866">ZeroTakenProb</a>, <a href="#a202467d2d7ce0b47448bc909631c6950">ZeroUntakenProb</a>}},  
    {CmpInst::ICMP_SGT, {<a href="#a5be5ee158531203bf7471424e2ea4866">ZeroTakenProb</a>, <a href="#a202467d2d7ce0b47448bc909631c6950">ZeroUntakenProb</a>}}, 
}
</div>
</dd>
</dl>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### ICmpWithOneTable {#aa8c67f6b4ae26d6e248b2b213f0b9217}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ProbabilityTable ICmpWithOneTable</td>
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

<p>Integer compares with 1:</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
    {CmpInst::ICMP_SLT, {<a href="#a202467d2d7ce0b47448bc909631c6950">ZeroUntakenProb</a>, <a href="#a5be5ee158531203bf7471424e2ea4866">ZeroTakenProb</a>}}, 
}
</div>
</dd>
</dl>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### ICmpWithZeroTable {#a38332cb5dc3c73636aa6495114e7a5ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ProbabilityTable ICmpWithZeroTable</td>
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

<p>Integer compares with 0:</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
    {CmpInst::ICMP_EQ, {<a href="#a202467d2d7ce0b47448bc909631c6950">ZeroUntakenProb</a>, <a href="#a5be5ee158531203bf7471424e2ea4866">ZeroTakenProb</a>}},  
    {CmpInst::ICMP_NE, {<a href="#a5be5ee158531203bf7471424e2ea4866">ZeroTakenProb</a>, <a href="#a202467d2d7ce0b47448bc909631c6950">ZeroUntakenProb</a>}},  
    {CmpInst::ICMP_SLT, {<a href="#a202467d2d7ce0b47448bc909631c6950">ZeroUntakenProb</a>, <a href="#a5be5ee158531203bf7471424e2ea4866">ZeroTakenProb</a>}}, 
    {CmpInst::ICMP_SGT, {<a href="#a5be5ee158531203bf7471424e2ea4866">ZeroTakenProb</a>, <a href="#a202467d2d7ce0b47448bc909631c6950">ZeroUntakenProb</a>}}, 
}
</div>
</dd>
</dl>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### LBH\_NONTAKEN\_WEIGHT {#ac6c00f8033a3bf9ab5f49143e30d8c52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t LBH_NONTAKEN_WEIGHT = 4</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### LBH\_TAKEN\_WEIGHT {#a205d7293fcfbe714464bceef72495dde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t LBH_TAKEN_WEIGHT = 124</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### PH\_NONTAKEN\_WEIGHT {#a38a9f81723daa4bec614eaba36d40b85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t PH_NONTAKEN_WEIGHT = 12</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>Referenced by <a href="#a44f69d9faa72e970316989f65d054c59">PtrTakenProb</a> and <a href="#a7f0d3e324489e13def109f268e27d5dc">PtrUntakenProb</a>.</p>

</div>
</div>

### PH\_TAKEN\_WEIGHT {#a6b89b3ae3e1706f0f437db6621986deb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t PH_TAKEN_WEIGHT = 20</td>
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

<p>Heuristics and lookup tables for non-loop branches: Pointer Heuristics (PH)</p>

<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>Referenced by <a href="#a44f69d9faa72e970316989f65d054c59">PtrTakenProb</a> and <a href="#a7f0d3e324489e13def109f268e27d5dc">PtrUntakenProb</a>.</p>

</div>
</div>

### PointerTable {#ac81ca00b5db15ff5c054c569fadd72dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ProbabilityTable PointerTable</td>
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

<p>Pointer comparisons:</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
    {ICmpInst::ICMP_NE, {<a href="#a44f69d9faa72e970316989f65d054c59">PtrTakenProb</a>, <a href="#a7f0d3e324489e13def109f268e27d5dc">PtrUntakenProb</a>}}, 
    {ICmpInst::ICMP_EQ, {<a href="#a7f0d3e324489e13def109f268e27d5dc">PtrUntakenProb</a>, <a href="#a44f69d9faa72e970316989f65d054c59">PtrTakenProb</a>}}, 
}
</div>
</dd>
</dl>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### PrintBranchProb {#af17aeb0484c720fb1e197adf768961c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PrintBranchProb("print-bpi", cl::init(false), cl::Hidden, cl::desc("Print the branch probability info."))</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo/#a54c3911cf4abbcd272fa99a303823942">llvm::BranchProbabilityInfo::calculate</a>.</p>

</div>
</div>

### PrintBranchProbFuncName {#ae4ed89c6d8e92b055e0561a615dcbaf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; PrintBranchProbFuncName("print-bpi-func-name", cl::Hidden, cl::desc("The option to specify the name of the function " "whose branch probability info is printed."))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo/#a54c3911cf4abbcd272fa99a303823942">llvm::BranchProbabilityInfo::calculate</a>.</p>

</div>
</div>

### prob {#a2bd4799263bb66b1eaf06927f08e7b64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">branch prob</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### UR\_TAKEN\_PROB {#aafc5237f3585710400d8a15b43ff0e5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BranchProbability UR_TAKEN_PROB = BranchProbability::getRaw(1)</td>
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

<p>Unreachable-terminating branch taken probability.</p>


<p>This is the probability for a branch being taken to a block that terminates (eventually) in unreachable. These are predicted as unlikely as possible. All reachable probability will proportionally share the remaining part.</p>


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### ZH\_NONTAKEN\_WEIGHT {#a2486cb22b39b4593d78671702f062b81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t ZH_NONTAKEN_WEIGHT = 12</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>Referenced by <a href="#a5be5ee158531203bf7471424e2ea4866">ZeroTakenProb</a> and <a href="#a202467d2d7ce0b47448bc909631c6950">ZeroUntakenProb</a>.</p>

</div>
</div>

### ZH\_TAKEN\_WEIGHT {#aaa5928aa2f68d1c15bd7dafa3745b0fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t ZH_TAKEN_WEIGHT = 20</td>
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

<p>Zero Heuristics (ZH)</p>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>


<p>Referenced by <a href="#a5be5ee158531203bf7471424e2ea4866">ZeroTakenProb</a> and <a href="#a202467d2d7ce0b47448bc909631c6950">ZeroUntakenProb</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"branch-prob"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp">BranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
