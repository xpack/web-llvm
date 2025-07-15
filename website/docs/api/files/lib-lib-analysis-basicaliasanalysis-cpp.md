---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/basicaliasanalysis-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `BasicAliasAnalysis.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/basicaliasanalysis-h">llvm/Analysis/BasicAliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/scopeexit-h">llvm/ADT/ScopeExit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">llvm/Analysis/AliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">llvm/Analysis/AssumptionCache.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfg-h">llvm/Analysis/CFG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/capturetracking-h">llvm/Analysis/CaptureTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">llvm/Analysis/MemoryBuiltins.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">llvm/Analysis/MemoryLocation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">llvm/IR/Argument.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constant-h">llvm/IR/Constant.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">llvm/IR/ConstantRange.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/getelementptrtypeiterator-h">llvm/IR/GetElementPtrTypeIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">llvm/IR/GlobalAlias.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">llvm/IR/GlobalVariable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">llvm/IR/Operator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">llvm/IR/User.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">llvm/Support/KnownBits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/saveandrestore-h">llvm/Support/SaveAndRestore.h</a>"
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;cstdlib&gt;
#include &lt;optional&gt;
#include &lt;utility&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-basicaliasanalysis-cpp-">anonymous{BasicAliasAnalysis.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/castedvalue">CastedValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents zext(sext(trunc(V))). <a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/castedvalue/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/linearexpression">LinearExpression</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents zext(sext(trunc(V))) * Scale + Offset. <a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/linearexpression/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/variablegepindex">VariableGEPIndex</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/basicaaresult/decomposedgep">DecomposedGEP</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a399bf1a0cd818337a59f27a9aacd595b">STATISTIC</a> (SearchLimitReached, "Number of times the limit to " "decompose GEPs is reached")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SearchLimitReached / SearchTimes shows how often the limit of to decompose GEPs is reached. <a href="#a399bf1a0cd818337a59f27a9aacd595b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48cf5613525a741f9d2f28261cb87329">STATISTIC</a> (SearchTimes, "Number of times a GEP is decomposed")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bb1cb40cf03b28fb4fac792966ab7b2">getObjectSize</a> (const Value *V, const DataLayout &amp;DL, const TargetLibraryInfo &amp;TLI, bool NullIsValidLoc, bool RoundToAlign=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the size of the object specified by V or UnknownSize if unknown. <a href="#a8bb1cb40cf03b28fb4fac792966ab7b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3713f361008d447bb146d39efd8cac15">isObjectSmallerThan</a> (const Value *V, TypeSize Size, const DataLayout &amp;DL, const TargetLibraryInfo &amp;TLI, bool NullIsValidLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we can prove that the object specified by V is smaller than Size. <a href="#a3713f361008d447bb146d39efd8cac15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f69c05b63d549b2e51069b6edaf73c6">getMinimalExtentFrom</a> (const Value &amp;V, const LocationSize &amp;LocSize, const DataLayout &amp;DL, bool NullIsValidLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the minimal extent from <span class="doxyComputerOutput">V</span> to the end of the underlying object, assuming the result is used in an aliasing query. <a href="#a8f69c05b63d549b2e51069b6edaf73c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e77a69539f17c5de8fcd7922ff596e6">isObjectSize</a> (const Value *V, TypeSize Size, const DataLayout &amp;DL, const TargetLibraryInfo &amp;TLI, bool NullIsValidLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we can prove that the object specified by V has size Size. <a href="#a5e77a69539f17c5de8fcd7922ff596e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cc11e92e9ee5cddfc6ebc8070f3ad29">areBothVScale</a> (const Value *V1, const Value *V2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if both V1 and V2 are VScale. <a href="#a8cc11e92e9ee5cddfc6ebc8070f3ad29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a878ce10ca89edf5ebef798cc4871b6bf">isNotInCycle</a> (const Instruction *I, const DominatorTree *DT, const LoopInfo *LI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static LinearExpression</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cc161dacc7e9566effd785f3d851c20">GetLinearExpression</a> (const CastedValue &amp;Val, const DataLayout &amp;DL, unsigned Depth, AssumptionCache *AC, DominatorTree *DT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyzes the specified value as a linear expression: "A*V + B", where A and B are constant integers. <a href="#a7cc161dacc7e9566effd785f3d851c20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accae7d75b860b14d28facd90a9e8465e">isIntrinsicCall</a> (const CallBase *Call, Intrinsic::ID IID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b8850f1ed44c12bc3501175a71c251c">getParent</a> (const Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75bdc7a047c6fe9cd26342a3819e2b25">notDifferentParent</a> (const Value *O1, const Value *O2)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/aliasresult">AliasResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f870dd8d68f3aa2160bcdb056fd89cb">MergeAliasResults</a> (AliasResult A, AliasResult B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f78a461faf84de1eca1d5333177ff96">INITIALIZE_PASS_BEGIN</a> (BasicAAWrapperPass, "basic-aa", "Basic Alias Analysis (stateless AA impl)", true, true) INITIALIZE_PASS_END(BasicAAWrapperPass</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">basic Basic Alias</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac347a7d5282f06ffeffdfa76a5907a90">Analysis</a> (stateless AA impl)"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0088a0a965b0502b3492582b1a4a47ae">EnableRecPhiAnalysis</a>("basic-aa-recphi", cl::Hidden, cl::init(true))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable analysis of recursive PHI nodes. <a href="#a0088a0a965b0502b3492582b1a4a47ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a21f0a76a963fbf5f03491885d5e70a">EnableSeparateStorageAnalysis</a>("basic-aa-separate-storage", cl::Hidden, cl::init(true))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af78df0c316edaaff2ccded54c6975501">MaxLookupSearchDepth</a> = 6</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">basic</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbb014e3a571577d8e3de66fe6c33009">aa</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">basic Basic Alias</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"basicaa"</td>
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

### Analysis() {#ac347a7d5282f06ffeffdfa76a5907a90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">basic Basic Alias Analysis (stateless AA impl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1983 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Reference <a href="#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

### areBothVScale() {#a8cc11e92e9ee5cddfc6ebc8070f3ad29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool areBothVScale (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2)</td>
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

<p>Return true if both V1 and V2 are VScale.</p>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aa16d8f8fe394a4a8a2fd9c0a97c616d2">llvm::PatternMatch::m_VScale</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>

</div>
</div>

### GetLinearExpression() {#a7cc161dacc7e9566effd785f3d851c20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinearExpression GetLinearExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> CastedValue &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, unsigned Depth, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT)</td>
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

<p>Analyzes the specified value as a linear expression: "A*V + B", where A and B are constant integers.</p>

<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a7cc161dacc7e9566effd785f3d851c20">GetLinearExpression</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#a7cc161dacc7e9566effd785f3d851c20">GetLinearExpression</a>.</p>

</div>
</div>

### getMinimalExtentFrom() {#a8f69c05b63d549b2e51069b6edaf73c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize getMinimalExtentFrom (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a> &amp; LocSize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, bool NullIsValidLoc)</td>
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

<p>Return the minimal extent from <span class="doxyComputerOutput">V</span> to the end of the underlying object, assuming the result is used in an aliasing query.</p>


<p>E.g., we do use the query location size and the fact that null pointers cannot alias here.</p>


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a935a116f6c8690449f4eddd56a99504b">llvm::LocationSize::getValue</a> and <a href="/web-llvm/docs/api/classes/llvm/locationsize/#aa9addaa6f7dd437922a57401cb192031">llvm::LocationSize::isPrecise</a>.</p>

</div>
</div>

### getObjectSize() {#a8bb1cb40cf03b28fb4fac792966ab7b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; TypeSize &gt; getObjectSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI, bool NullIsValidLoc, bool RoundToAlign=false)</td>
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

<p>Returns the size of the object specified by V or UnknownSize if unknown.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62ba0e5ee2d86f663c6de4efda6082a7">llvm::getObjectSize</a>, <a href="/web-llvm/docs/api/structs/llvm/objectsizeopts/#a0229c5396522e5a903a277fda4c3659c">llvm::ObjectSizeOpts::NullIsUnknownSize</a>, <a href="/web-llvm/docs/api/structs/llvm/objectsizeopts/#a53a625d57d29696ca5cc6dd7a5ee94ee">llvm::ObjectSizeOpts::RoundToAlign</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### getParent() {#a1b8850f1ed44c12bc3501175a71c251c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function * getParent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 863 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64instrinfo-cpp-/aarch64pipelinerloopinfo/#acd56984ddb7e33b9503b761c7083a335">anonymous{AArch64InstrInfo.cpp}::AArch64PipelinerLoopInfo::AArch64PipelinerLoopInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600packetizer-cpp-/r600packetizerlist/#abfcc0b59be9882aca9a246d1ee6a1eb0">anonymous{R600Packetizer.cpp}::R600PacketizerList::addToPacket</a>, <a href="/web-llvm/docs/api/structs/anonymous-dfajumpthreading-cpp-/allswitchpaths/#a3d1af2c1cf6d3ead7429dc9136038f70">anonymous{DFAJumpThreading.cpp}::AllSwitchPaths::AllSwitchPaths</a>, <a href="/web-llvm/docs/api/classes/anonymous-armfastisel-cpp-/armfastisel/#ac8e1ee94bced949e039028f65dc5784d">anonymous{ARMFastISel.cpp}::ARMFastISel::ARMFastISel</a>, <a href="/web-llvm/docs/api/classes/anonymous-armbaseinstrinfo-cpp-/armpipelinerloopinfo/#a6b8dcd3ecccd4399d6c45473c2f0c511">anonymous{ARMBaseInstrInfo.cpp}::ARMPipelinerLoopInfo::ARMPipelinerLoopInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a32ff799dcb39887a8d21322020f305ba">llvm::CanonicalLoopInfo::assertOK</a>, <a href="/web-llvm/docs/api/classes/anonymous-coroelide-cpp-/coroidelider/#adb122f608fe469bd24f486598a4bc881">anonymous{CoroElide.cpp}::CoroIdElider::canCoroBeginEscape</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a0ac5df8f0304981180d602dacb13512c">llvm::LoopVectorizationCostModel::collectValuesToIgnore</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7524dbb403a24e9e73d4bca80baa768d">llvm::JumpThreadingPass::computeValueKnownInPredecessorsImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonloopidiomrecognition-cpp-/simplifier/context/#a263dfd80d929880960b5d3406d21d1d8">anonymous{HexagonLoopIdiomRecognition.cpp}::Simplifier::Context::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/datadependencegraph/#a022224fd4758654fcf0a633743c029bc">llvm::DataDependenceGraph::DataDependenceGraph</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a48f061a53492f73dc9d82812f4350b44">detectPopcountIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfomiroptimization/#a4d8ba0921d348dc62437d2fd3ce00061">llvm::DiagnosticInfoMIROptimization::DiagnosticInfoMIROptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfomisexpect/#abdd6bad61c38d00ca2dceda536cd15f9">llvm::DiagnosticInfoMisExpect::DiagnosticInfoMisExpect</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationfailure/#a11b5ef0c89ca056e53c24affefe7d3cc">llvm::DiagnosticInfoOptimizationFailure::DiagnosticInfoOptimizationFailure</a>, <a href="/web-llvm/docs/api/structs/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/remarkgenerator/#afa50ad465c63aba4cc83c1e37248a860">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::RemarkGenerator::emitRemarks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a5bb62631ba6a4be0ae02f7365ee4a7d7">ensureValueAvailableInSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a305d2f13922c7da4206b299861370a80">llvm::VPBasicBlock::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#af950841a4443ffb7aff66ae75fee8442">foldURemOfLoopIncrement</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesupdater/#a1ba00e4f051e690dfe2e14625ce165d3">llvm::FunctionPropertiesUpdater::FunctionPropertiesUpdater</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a22469895240423b61ee2b39822d5c0af">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::FunctionStackPoisoner</a>, <a href="/web-llvm/docs/api/classes/llvm/regionbase/#a5fca772610b91c67ec95e34b91c87d7f">llvm::RegionBase&lt; Tr &gt;::getDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a7ce23b4d08f0bd28ea1f676d527ae1d3">llvm::VPBasicBlock::getEnclosingLoopRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#ab50e16f0f40598ab5128093a78cd6a05">llvm::VPBasicBlock::getEnclosingLoopRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp/#a1963b19fa044bc9d72adfbe280b13abd">getLocalFunctionMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getLoopLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo/#ad10df0e6ccca0fc951b845e3a007e385">llvm::LazyValueInfo::getPredicateAt</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoninstrinfo-cpp-/hexagonpipelinerloopinfo/#a6907f6a41468c8a1f73099a44238ab21">anonymous{HexagonInstrInfo.cpp}::HexagonPipelinerLoopInfo::HexagonPipelinerLoopInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a8500015965ef1b86e39cd83fd2fc8dff">llvm::InlineAdvice::InlineAdvice</a>, <a href="/web-llvm/docs/api/structs/arminstructionselector/insertinfo/#ad7539b5e1d3afd907c8656e3e6624343">ARMInstructionSelector::InsertInfo::InsertInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#add888de4c361e3791a2aba0cb578aa53">llvm::InstrEmitter::InstrEmitter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#a5a7fe53bda3cbce584280a177a18d5ab">isBlockValidForExtraction</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a12a188073b910647564952c1ca195386">llvm::PHINode::isComplete</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#ac59be503a3e1f9368dc05abada300664">llvm::VPBasicBlock::isExiting</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a97acf4298b4ca1010c06af4741609a89">isOnlyUsedInEntryBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/functionloweringinfo-cpp/#aec1de31cd4bfbbbf00d2903ecae5cbba">isUsedOutsideOfDefiningBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/kerneloperandinfo/#a0780dfcb3a517ab51f5f973dae9e1edb">anonymous{ModuloSchedule.cpp}::KernelOperandInfo::KernelOperandInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/kernelrewriter/#ab21e77ad66bbad9ba8a9d999c7414c35">anonymous{ModuloSchedule.cpp}::KernelRewriter::KernelRewriter</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluebasicblock/#ga94bcbe957389c2c2219d6a02e72691ef">LLVMGetBasicBlockParent</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantglobals/#ga357d4822f340f1d51edcc3a6e2c71d31">LLVMGetGlobalParent</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueinstruction/#gaf4c7e1e9f8fbb478a2957fbd47f9cb11">LLVMGetInstructionParent</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluefunctionparameters/#ga81dc96cc6ae8314a858ab41cdf35c763">LLVMGetParamParent</a>, <a href="/web-llvm/docs/api/classes/llvm/loopconstrainer/#a1267203588d084fe0a37dacd6cad5a70">llvm::LoopConstrainer::LoopConstrainer</a>, <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#aff890ddd726ba815dfa456b4a5b6f432">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::LowOverheadLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a7d5d8e859928cc003454a2ba18372a71">llvm::MachineIRBuilder::MachineIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleslottracker/#ad46f7561b1384a882cfabf8ef2b7326c">llvm::MachineModuleSlotTracker::MachineModuleSlotTracker</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkanalysis/#a23badf68951303c8ef0664e24f181100">llvm::MachineOptimizationRemarkAnalysis::MachineOptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/mibundlebuilder/#ad7d1c198f2d3cc0e6030a27a656c138e">llvm::MIBundleBuilder::MIBundleBuilder</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86pretileconfig-cpp-/miref/#a33776740182a7fe32463c975eced3893">anonymous{X86PreTileConfig.cpp}::MIRef::MIRef</a>, <a href="#a75bdc7a047c6fe9cd26342a3819e2b25">notDifferentParent</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/openmpopt/#a3431967647082e12eb2569a580d143d9">anonymous{OpenMPOpt.cpp}::OpenMPOpt::OpenMPOpt</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremark/#a940829469e382e9dea15a5c8645a8387">llvm::OptimizationRemark::OptimizationRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremark/#a2ad3eae0e100b9e6eca74ee28144ba1d">llvm::OptimizationRemark::OptimizationRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#ab4fa4fd4a389f0d81f5f413d21b2c4c4">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#a7d0a9378ede1f0821eb273c8e797df06">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#ad3c742fcad66bf2ca0afe6d1b58b6c8b">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkmissed/#a95945fd7efc21c965b5bce7cb8a5685c">llvm::OptimizationRemarkMissed::OptimizationRemarkMissed</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkmissed/#a23879092a3f056766816230baa431981">llvm::OptimizationRemarkMissed::OptimizationRemarkMissed</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcinstrinfo-cpp-/ppcpipelinerloopinfo/#a1298bb460643c2ca39e7a85c028b6c68">anonymous{PPCInstrInfo.cpp}::PPCPipelinerLoopInfo::PPCPipelinerLoopInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4232efd6f56912332e8631bd828eca21">llvm::BasicBlock::print</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#ad24a1b510b43c0dc48de0d37e6fff061">llvm::DbgMarker::print</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5b8c4fb5c4e648b5e893b3db122bdf6c">llvm::Function::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad9c9c8915579c517eff56e638c1a643c">llvm::MachineFunction::print</a>, <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#a66312117826bfdbd0e36aef38081b9a4">llvm::NamedMDNode::print</a>, <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#a267435660ce6b53b9d83d84f8f257241">llvm::NamedMDNode::print</a>, <a href="/web-llvm/docs/api/classes/llvm/prologepilogsgprspillbuilder/#ac0408410d87175417891e8e6f0718200">llvm::PrologEpilogSGPRSpillBuilder::PrologEpilogSGPRSpillBuilder</a>, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg/#a721c66ae31a226c5f4244f7827ddbba2">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::PromoteMem2Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ae7d61f8763322c1d7c8181f00798d9c5">redirectValuesFromPredecessorsToPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache/#a23187618f079555e127ba0e7b4581530">llvm::AssumptionCache::registerAssumption</a>, <a href="/web-llvm/docs/api/classes/llvm/verifyinstrumentation/#abfec9362909844b463ec07ef82233199">llvm::VerifyInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/structs/remarkinfo/#a1b5cf8ba776df7b10906174971d7225e">RemarkInfo::RemarkInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/looprotatepass/#aa87b74697e2ab3e760eddd32b866c508">llvm::LoopRotatePass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-blockextractor-cpp-/blockextractor/#ab929be069dc417044c41ddeca9bec3b7">anonymous{BlockExtractor.cpp}::BlockExtractor::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppclowermassventries-cpp-/ppclowermassventries/#afc7b9162f72717ab77864ee9b4b48030">anonymous{PPCLowerMASSVEntries.cpp}::PPCLowerMASSVEntries::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a5d7e71cf32573e6b1762b5a1d82a1cf5">llvm::ScheduleDAGMI::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a1583ce23a69e8a1b4af8065e2019c75f">llvm::ScheduleDAGMILive::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a543aa30430f7e566cc4baa20b271f377">llvm::SIScheduleDAGMI::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#ad25e72e64bc7ed157b69c60e85b4061e">llvm::VLIWMachineScheduler::schedule</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a4a1143f3929f3258aebb54b4bef12082">llvm::SGPRSpillBuilder::SGPRSpillBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/slottracker/#afef03e847bbe9f04ab85632415cd907c">llvm::SlotTracker::SlotTracker</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#afad0de1026bed50eff308033f7cd132b">splitCallSite</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycle/#a4cc24eca5caee29bd57f43e84c285ee3">llvm::GenericCycle&lt; ContextT &gt;::verifyCycle</a>, <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/modelledphi/#a737711cb6f02ce642903b3fe73864645">anonymous{GVNSink.cpp}::ModelledPHI::verifyModelledPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/vloperands/#a3c3378c4b4191797dc4125fc8d2b4029">llvm::slpvectorizer::BoUpSLP::VLOperands::VLOperands</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#aba677aadf1abee0a03e3e5744b9724cd">anonymous{SimplifyIndVar.cpp}::WidenIV::WidenIV</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#a8f78a461faf84de1eca1d5333177ff96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (<a href="/web-llvm/docs/api/classes/llvm/basicaawrapperpass">BasicAAWrapperPass</a>, "basic-aa", "Basic Alias <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a> (stateless AA <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#abd1ccb1bf511e1965414eb1d2e137302">impl</a>)", <a href="#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1977 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### isIntrinsicCall() {#accae7d75b860b14d28facd90a9e8465e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isIntrinsicCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IID)</td>
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



<p>Definition at line 809 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/arcopt/#ga9c9cf6ad55eb23d77d083a184e416c09">Call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/basicaaresult/#a43a53dbe445a968ef8851f1a257d4d7c">llvm::BasicAAResult::getModRefInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/basicaaresult/#a250327477f3c748e335f60bda0dbfac7">llvm::BasicAAResult::getModRefInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a108729701911f7eb27a9416311f7d9f4">isPreserveArrayIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a6ea70179d4841714f066deb7f391884b">isPreserveStructIndex</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a0b67e279289d23c13f9a32e82a3b7816">isPreserveUnionIndex</a>.</p>

</div>
</div>

### isNotInCycle() {#a878ce10ca89edf5ebef798cc4871b6bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isNotInCycle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI)</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a221abdd995f70342428e87e9c809c2ff">llvm::isPotentiallyReachableFromMany</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/earliestescapeanalysis/#a7c3074603b84ea51ddaa985117ebce55">llvm::EarliestEscapeAnalysis::isNotCapturedBefore</a>.</p>

</div>
</div>

### isObjectSize() {#a5e77a69539f17c5de8fcd7922ff596e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isObjectSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> Size, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI, bool NullIsValidLoc)</td>
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

<p>Returns true if we can prove that the object specified by V has size Size.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62ba0e5ee2d86f663c6de4efda6082a7">llvm::getObjectSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### isObjectSmallerThan() {#a3713f361008d447bb146d39efd8cac15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isObjectSmallerThan (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> Size, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI, bool NullIsValidLoc)</td>
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

<p>Returns true if we can prove that the object specified by V is smaller than Size.</p>


<p>Bails out early unless the root object is passed as the first parameter.</p>


<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62ba0e5ee2d86f663c6de4efda6082a7">llvm::getObjectSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed2c5dd2a303159f87771db83f54352b">llvm::isIdentifiedObject</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a83e6442f8ebefccdb5e089732fe397ac">llvm::details::FixedOrScalableQuantity&lt; TypeSize, uint64_t &gt;::isKnownLT</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### MergeAliasResults() {#a8f870dd8d68f3aa2160bcdb056fd89cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasResult MergeAliasResults (<a href="/web-llvm/docs/api/classes/llvm/aliasresult">AliasResult</a> A, <a href="/web-llvm/docs/api/classes/llvm/aliasresult">AliasResult</a> B)</td>
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



<p>Definition at line 1378 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57a0916b614598c673c1e6a59c7312a1409">llvm::AliasResult::MayAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57ac1a99a1af9a4778a61e5cc3e1d622180">llvm::AliasResult::MustAlias</a> and <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57a9e724bc94de38c6ca77508f19c246c0c">llvm::AliasResult::PartialAlias</a>.</p>

</div>
</div>

### notDifferentParent() {#a75bdc7a047c6fe9cd26342a3819e2b25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool notDifferentParent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * O1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * O2)</td>
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



<p>Definition at line 876 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Reference <a href="#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/basicaaresult/#aedf3cfa2d4fc19037cb678766d31d738">llvm::BasicAAResult::alias</a> and <a href="/web-llvm/docs/api/classes/llvm/basicaaresult/#a43a53dbe445a968ef8851f1a257d4d7c">llvm::BasicAAResult::getModRefInfo</a>.</p>

</div>
</div>

### STATISTIC() {#a399bf1a0cd818337a59f27a9aacd595b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (SearchLimitReached, "Number of times the limit to " "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#abe3945bfefe671a9a34f864d493d5fe7">decompose</a> GEPs is reached")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SearchLimitReached / SearchTimes shows how often the limit of to decompose GEPs is reached.</p>


<p>It will affect the precision of basic alias analysis.</p>


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a48cf5613525a741f9d2f28261cb87329}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (SearchTimes, "Number of times a <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a> is decomposed")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### aa {#abbb014e3a571577d8e3de66fe6c33009}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">basic aa</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1982 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>

</div>
</div>

### EnableRecPhiAnalysis {#a0088a0a965b0502b3492582b1a4a47ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableRecPhiAnalysis("basic-aa-recphi", cl::Hidden, cl::init(true))</td>
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

<p>Enable analysis of recursive PHI nodes.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>

</div>
</div>

### EnableSeparateStorageAnalysis {#a6a21f0a76a963fbf5f03491885d5e70a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableSeparateStorageAnalysis("basic-aa-separate-storage", cl::Hidden, cl::init(true))</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>

</div>
</div>

### MaxLookupSearchDepth {#af78df0c316edaaff2ccded54c6975501}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned MaxLookupSearchDepth = 6</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>

</div>
</div>

### true {#af6d5cafbdfc5313e65d990120021a3ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">print machine Print Machine Uniformity Info true</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1983 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64elfobjectwriter-cpp-/aarch64elfobjectwriter/#a8c264e897c2ed126d553e7240ef474b4">anonymous{AArch64ELFObjectWriter.cpp}::AArch64ELFObjectWriter::AArch64ELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#a1bc852ad7149319b7a54dccd62e77b8f">anonymous{AArch64FastISel.cpp}::AArch64FastISel::AArch64FastISel</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ae70dcb78318ff84a4d89d68f2f1e2c70">llvm::AArch64FrameLowering::AArch64FrameLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64letargetmachine/#ac62bb19fc05412e738292cde1d3fb2c3">llvm::AArch64leTargetMachine::AArch64leTargetMachine</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangecallsitereturned/#a4f11b04e697cb5a04bd6467069f73178">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeCallSiteReturned::AAValueConstantRangeCallSiteReturned</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/addressable/#a8f6eaaa04510bb103228732edfcaf9c8">llvm::jitlink::Addressable::Addressable</a>, <a href="/web-llvm/docs/api/structs/llvm/user/allocinfo/#add4e011c3c9b8aad3202f51fcb453eb5">llvm::User::AllocInfo::AllocInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-alwaysinliner-cpp-/alwaysinlinerlegacypass/#a31285b795a0ba5f921134b6e1539b2da">anonymous{AlwaysInliner.cpp}::AlwaysInlinerLegacyPass::AlwaysInlinerLegacyPass</a>, <a href="#ac347a7d5282f06ffeffdfa76a5907a90">Analysis</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a71b4f8481895096ec305970353ad8c56">llvm::APFixedPoint::APFixedPoint</a>, <a href="/web-llvm/docs/api/classes/anonymous-acceltable-cpp-/appleacceltablewriter/#a83227e4651c7d8881ea5eff7450dd607">anonymous{AccelTable.cpp}::AppleAccelTableWriter::AppleAccelTableWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/armletargetmachine/#ae82a61b1e94127c575e157c9a0ee9e6e">llvm::ARMLETargetMachine::ARMLETargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a66d1a7fb69c6ee8e272ede2e29448a50">anonymous{AsmParser.cpp}::AsmParser::AsmParser</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a83a17242ac80912325857beaabddc006">llvm::AsmToken::AsmToken</a>, <a href="/web-llvm/docs/api/classes/llvm/avrelfobjectwriter/#a25bc1199b9b97ff8e27b7b793b913f68">llvm::AVRELFObjectWriter::AVRELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblocksectionsprofilereader/#ad35626a3c499abcf5f053b94068a850c">llvm::BasicBlockSectionsProfileReader::BasicBlockSectionsProfileReader</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a1f110ef2940ded67984bb61231099377">llvm::BitCodeAbbrevOp::BitCodeAbbrevOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/bitsimplification/#a0a75d848a28b86d55efb76e4269b384c">anonymous{HexagonBitSimplify.cpp}::BitSimplification::BitSimplification</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfelfobjectwriter-cpp-/bpfelfobjectwriter/#ac0f96d7058684da68aa071165c685f14">anonymous{BPFELFObjectWriter.cpp}::BPFELFObjectWriter::BPFELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a2c6578835c232d441544863a86c04728">llvm::BTFDebug::BTFDebug</a>, <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a68800712c29d721bd730efc13f6836be">llvm::FastISel::CallLoweringInfo::CallLoweringInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#af35bb64b495f2a61199dda4a3b9ec4b2">llvm::TargetLowering::CallLoweringInfo::CallLoweringInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/cgdataostream/#a7368481693c6319965392398015055b4">llvm::CGDataOStream::CGDataOStream</a>, <a href="/web-llvm/docs/api/classes/llvm/circular-raw-ostream/#a42664fb7b2765468ff290e0b46cbb079">llvm::circular_raw_ostream::circular_raw_ostream</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/coffaarch64asmbackend/#a34c8883a9b07137d3e809cb2cf4b51b8">anonymous{AArch64AsmBackend.cpp}::COFFAArch64AsmBackend::COFFAArch64AsmBackend</a>, <a href="/web-llvm/docs/api/classes/coffopttable/#a4d6536c5ac6c0b4fe87e97555a7aa93b">COFFOptTable::COFFOptTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/constgeneration/#a877410d6fb6bbfde5ae4519892284c1b">anonymous{HexagonBitSimplify.cpp}::ConstGeneration::ConstGeneration</a>, <a href="/web-llvm/docs/api/structs/llvm/potentialvaluesstate/#a3879fa9aa3f95bc17f51bf17cfedadda">llvm::PotentialValuesState&lt; APInt &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/copygeneration/#abfa763a3bdbca3a29f00217b7349c950">anonymous{HexagonBitSimplify.cpp}::CopyGeneration::CopyGeneration</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/countedregion/#a646c15f9f114086b0a3d8d035b6bf81d">llvm::coverage::CountedRegion::CountedRegion</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/coveragesegment/#a9f5383042b75067f97e1ca42e89df98e">llvm::coverage::CoverageSegment::CoverageSegment</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8240180b602f60980be558e3cd44b460">llvm::IRBuilderBase::CreateGlobalStringPtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyelfobjectwriter-cpp-/cskyelfobjectwriter/#ac36af2b9b75f5c30a0885f97b4043e7d">anonymous{CSKYELFObjectWriter.cpp}::CSKYELFObjectWriter::CSKYELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/darwinaarch64asmbackend/#ac945b0d8be66879fb12fd546993c8a12">anonymous{AArch64AsmBackend.cpp}::DarwinAArch64AsmBackend::DarwinAArch64AsmBackend</a>, <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgop/#a71f5001e487e43d4dd4471e2155722c7">LiveDebugValues::DbgOp::DbgOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvalueloc/#a4984f5b9bd958ecd81e6434f02d1177b">llvm::DbgValueLoc::DbgValueLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/debugobjectmanagerplugin/#ac6859199292075b7a74f94aef8bd0a1c">llvm::orc::DebugObjectManagerPlugin::DebugObjectManagerPlugin</a>, <a href="/web-llvm/docs/api/structs/llvm/df-ext-iterator/#a5a8f0dc0a80b6969ed92905ba34bf6c6">llvm::df_ext_iterator&lt; T, SetTy &gt;::df_ext_iterator</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#af852c191e3bb0f814b1436ace8d7485e">llvm::DomTreeNodeBase&lt; BlockT &gt;::DominatorTreeBase&lt; NodeT, false &gt;</a>, <a href="/web-llvm/docs/api/structs/llvm/domonlyprinter/#a0575606bc805c370055bfaaa69b32cb7">llvm::DomOnlyPrinter::DomOnlyPrinter</a>, <a href="/web-llvm/docs/api/structs/llvm/domonlyviewer/#aee6c3489835c9e57af0c86bd9f0df1d2">llvm::DomOnlyViewer::DomOnlyViewer</a>, <a href="/web-llvm/docs/api/structs/anonymous-domprinter-cpp-/domonlyviewerwrapperpass/#ad98d8b8836cfc50842f0f41e4f655298">anonymous{DomPrinter.cpp}::DomOnlyViewerWrapperPass::DomOnlyViewerWrapperPass</a>, <a href="/web-llvm/docs/api/structs/llvm/genericdomtreeupdater/domtreeupdate/#a6daf208abe1f70c391a4b8cdbd1eb7c2">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::DomTreeUpdate::DomTreeUpdate</a>, <a href="/web-llvm/docs/api/structs/llvm/dependence/dventry/#a0414b0b54d38ad7fdc3c8f967ad7a93a">llvm::Dependence::DVEntry::DVEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinelicm-cpp-/earlymachinelicm/#a60f02363b12b88b573993eea977b930a">anonymous{MachineLICM.cpp}::EarlyMachineLICM::EarlyMachineLICM</a>, <a href="/web-llvm/docs/api/classes/anonymous-tailduplication-cpp-/earlytailduplicatelegacy/#a51dd9218edc389d659f792521eb6ac28">anonymous{TailDuplication.cpp}::EarlyTailDuplicateLegacy::EarlyTailDuplicateLegacy</a>, <a href="/web-llvm/docs/api/classes/llvm/erroror/#a2cad52048a7d41edabe8c195f17d96f4">llvm::ErrorOr&lt; T &gt;::ErrorOr</a>, <a href="/web-llvm/docs/api/classes/llvm/erroror/#a0b9b6eb49cc512af35f805069a24dfa7">llvm::ErrorOr&lt; T &gt;::ErrorOr</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a88c9308b16c3935bc567d76748a30e05">llvm::Expected&lt; std::unique_ptr&lt; InFlightAlloc &gt; &gt;::Expected</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a4f8d24ff610fcb7ad32c767d167be350">llvm::Expected&lt; std::unique_ptr&lt; InFlightAlloc &gt; &gt;::Expected</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a79dce2d3eafaf25bf0df59f56caf9712">file</a>, <a href="/web-llvm/docs/api/classes/llvm/foldingsetbucketiterator/#a5013a4bf990cc499195989bdd445f34b">llvm::FoldingSetBucketIterator&lt; T &gt;::FoldingSetBucketIterator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate/#a0a8bbbf9ec7c7e88b08172862188e530">anonymous{LoopFuse.cpp}::FusionCandidate::FusionCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnscheduledagmilive/#a586d595322e6cb11cc1663b937d9aca7">llvm::GCNScheduleDAGMILive::GCNScheduleDAGMILive</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0df98b068b652d32c3529381db723b9c">llvm::PPCInstrInfo::getFMAPatterns</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonelfobjectwriter-cpp-/hexagonelfobjectwriter/#a41f88fd90ff25b85f0800d948db49644">anonymous{HexagonELFObjectWriter.cpp}::HexagonELFObjectWriter::HexagonELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a5907981c158ef4c895f1418c281e53d6">llvm::HexagonFrameLowering::HexagonFrameLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/identifyingpassptr/#ac3722e53f3d4351495b304a28b57f198">llvm::IdentifyingPassPtr::IdentifyingPassPtr</a>, <a href="/web-llvm/docs/api/structs/llvm/idf-ext-iterator/#a8f09fbc96b9fd66d6759f4f61579e29f">llvm::idf_ext_iterator&lt; T, SetTy &gt;::idf_ext_iterator</a>, <a href="/web-llvm/docs/api/structs/llvm/idf-ext-iterator/#a341a7c4b3537c508dc74132a4f27f430">llvm::idf_ext_iterator&lt; T, SetTy &gt;::idf_ext_iterator</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvalueassigner/#a13b43a063ba0bd7c472e835dc34f0a95">llvm::CallLowering::IncomingValueAssigner::IncomingValueAssigner</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvaluehandler/#af7ca7bf1f0eb34e567785c99196e6329">llvm::CallLowering::IncomingValueHandler::IncomingValueHandler</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/irprintingpasses-cpp/#a777c2e701b2f140458b558974bfbde55">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a3665d0519d66c7dcd9df0f43548f560e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp/#a3503a7cbe1d709c109b2c4e25e790f7e">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecycleanalysis-cpp/#a6d03c71c069635597085addf14df21ee">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineuniformityanalysis-cpp/#a64125f99a2aa1a1f82e3a21f7191554d">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacksafetyanalysis-cpp/#ae03f82d6e49a61523c78050b29420f68">INITIALIZE_PASS_BEGIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reg2mem-cpp/#a965e91729ab517bcb1f93f10f100f95c">INITIALIZE_PASS_DEPENDENCY</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#af70e33de5e351fc22288a3130b0428b6">llvm::InstCombiner::InstCombiner</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/instdesc/#a48e0d025a17fdda208837263749dbb18">llvm::RecurrenceDescriptor::InstDesc::InstDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instrbuilder/#a54e306500b1968dcb5c02cb0570675bf">llvm::mca::InstrBuilder::InstrBuilder</a>, <a href="/web-llvm/docs/api/structs/llvm/intrusivebacklistnode/#a3ac211af5be9eb8639dbdef853e2ce80">llvm::IntrusiveBackListNode::IntrusiveBackListNode</a>, <a href="/web-llvm/docs/api/structs/llvm/ipo-ext-iterator/#a21d25b8906c0fe6cb058610c2bda4730">llvm::ipo_ext_iterator&lt; T, SetType &gt;::ipo_ext_iterator</a>, <a href="/web-llvm/docs/api/structs/llvm/ipo-ext-iterator/#a4238d9bc4c7f1034448dcdc273d66e69">llvm::ipo_ext_iterator&lt; T, SetType &gt;::ipo_ext_iterator</a>, <a href="/web-llvm/docs/api/classes/llvm/irchangedtester/#a83ff87c5899efeb4e34d12b749b50799">llvm::IRChangedTester::IRChangedTester</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaielfobjectwriter-cpp-/lanaielfobjectwriter/#a34797922e5e9ac24ab1a46c7923891a4">anonymous{LanaiELFObjectWriter.cpp}::LanaiELFObjectWriter::LanaiELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-libdriver-cpp-/libopttable/#a7115a3469f779dde2dd3b0f0253a0b4c">anonymous{LibDriver.cpp}::LibOptTable::LibOptTable</a>, <a href="/web-llvm/docs/api/structs/llvm/licmoptions/#a584d2ab522631bbe6bd1a91285003a00">llvm::LICMOptions::LICMOptions</a>, <a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/linearexpression/#aebdb60203b916f2447dad3c400d526aa">anonymous{BasicAliasAnalysis.cpp}::LinearExpression::LinearExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block/#acff959e1f59ad4d940708fe62a722cf2">llvm::jitlink::Block::LinkGraph</a>, <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo/#aeab085bec726d772b2654028eb61fa05">llvm::FunctionLoweringInfo::LiveOutInfo::LiveOutInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/loadclustermutation/#a9317a15c0a4f218e7f7ea4fe01f61223">anonymous{MachineScheduler.cpp}::LoadClusterMutation::LoadClusterMutation</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchelfobjectwriter-cpp-/loongarchelfobjectwriter/#a5566d58c413e66fba4f9ac1f944a48bd">anonymous{LoongArchELFObjectWriter.cpp}::LoongArchELFObjectWriter::LoongArchELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#a699fa07bf5290218677fc2a1e69e0781">llvm::X86CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/lowertypetestspass/#a0da2382d9008c7a7b6f9c77f7282a0a0">llvm::LowerTypeTestsPass::LowerTypeTestsPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmbackend-cpp-/m68kasmbackend/#ae383806b34d576f56784449c9eda24d5">anonymous{M68kAsmBackend.cpp}::M68kAsmBackend::M68kAsmBackend</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kelfobjectwriter-cpp-/m68kelfobjectwriter/#a36550a4f62bc3fc2d82150afb3417f6b">anonymous{M68kELFObjectWriter.cpp}::M68kELFObjectWriter::M68kELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolentry/#ad055d6c5c902869c04a999ccd3ed794f">llvm::MachineConstantPoolEntry::MachineConstantPoolEntry</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/makelibcalloptions/#aff3cc82d02c80fafcd898a122601ade2">llvm::TargetLowering::MakeLibCallOptions::MakeLibCallOptions</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/gcstandregmatch/#a23af950b66bcb325cd214e286a8426ff">llvm::MIPatternMatch::GCstAndRegMatch::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/gfcstandregmatch/#af0058d532d86b7f68d63bfebaf1df2bb">llvm::MIPatternMatch::GFCstAndRegMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a265a1edd4b8035734cda280bb91b390d">matchIntrinsicType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionspirv/#a7862d2f746209c16291d7139dab55e00">llvm::MCSectionSPIRV::MCContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9ad1da683a018add519fd96cd22cc785">llvm::MCObjectStreamer::MCObjectStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment/#a897d99e7810a92145cae33f858d63651">llvm::MCRelaxableFragment::MCRelaxableFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions/#ae66d32a696f11369da4e9a7c2bbd41e5">llvm::MCTargetOptions::MCTargetOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/mipseltargetmachine/#aa2901f24bea76973c976cdbad5ac892a">llvm::MipselTargetMachine::MipselTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsprelegalizercombiner-cpp-/mipsprelegalizercombinerimpl/#a896e195bc452bdbe7ffececf1a10ac41">anonymous{MipsPreLegalizerCombiner.cpp}::MipsPreLegalizerCombinerImpl::MipsPreLegalizerCombinerImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-mipsprelegalizercombiner-cpp-/mipsprelegalizercombinerinfo/#a9cea4fcdb705d5e757a450dab79e2da2">anonymous{MipsPreLegalizerCombiner.cpp}::MipsPreLegalizerCombinerInfo::MipsPreLegalizerCombinerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget/#ae7b263db1194beb382f8ebc755238b77">llvm::MipsSubtarget::MipsSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#ad51f80b3e6e2aaa02181cff60e90f6d4">llvm::MipsTargetStreamer::MipsTargetStreamer</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430elfobjectwriter-cpp-/msp430elfobjectwriter/#ae1edec5452fea7d8e986de1273495c5c">anonymous{MSP430ELFObjectWriter.cpp}::MSP430ELFObjectWriter::MSP430ELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativetypefunctionsig/#a026eed033e9e8c0aa6094e2d30b93d79">llvm::pdb::NativeTypeFunctionSig::NativeTypeFunctionSig</a>, <a href="/web-llvm/docs/api/classes/llvm/nodeset/#a802a019a7c7dbb3c15f7ce000c74fae4">llvm::NodeSet::NodeSet</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/nomeminstr/#a5ac26db9ad4a8926b281baa3fdcd32c8">anonymous{MipsDelaySlotFiller.cpp}::NoMemInstr::NoMemInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetmachine64/#a36ca05d7cdde12b565049da7ab71a837">llvm::NVPTXTargetMachine64::NVPTXTargetMachine64</a>, <a href="/web-llvm/docs/api/classes/llvm/scopedhandle/#af632db7ffc4f4fb87308982c72bfd972">llvm::ScopedHandle&lt; CommonHandleTraits &gt;::operator bool</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/blockfreqquery/#af8c521993231c6aa85baba8f8c23b828">llvm::orc::BlockFreqQuery::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/oprofilewrapper/#ab55220d896b5ef2850bc4e5abf721113">llvm::OProfileWrapper::OProfileWrapper</a>, <a href="/web-llvm/docs/api/structs/llvm/reassociate/overflowtracking/#a7ce5644b671ead336c9e8ddfbb964215">llvm::reassociate::OverflowTracking::OverflowTracking</a>, <a href="/web-llvm/docs/api/classes/llvm/pagedvector/#a8d0d4219201ac3a28aa03fde24f19651">llvm::PagedVector&lt; T, PageSize &gt;::PagedVector</a>, <a href="/web-llvm/docs/api/structs/llvm/po-ext-iterator/#a5e17c72dbdf5cdcf73599907e9db1478">llvm::po_ext_iterator&lt; T, SetType &gt;::po_ext_iterator</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a27414aac7f6b0da5342d78c77c7d6135">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::populateSwLDSAttributeAndMetadata</a>, <a href="/web-llvm/docs/api/structs/llvm/postdomonlyprinter/#a10bcf0e3127ea9cb73dc7275470cde89">llvm::PostDomOnlyPrinter::PostDomOnlyPrinter</a>, <a href="/web-llvm/docs/api/structs/llvm/postdomonlyviewer/#ad0a494284a770b38fb00ce2928cbbfaf">llvm::PostDomOnlyViewer::PostDomOnlyViewer</a>, <a href="/web-llvm/docs/api/structs/anonymous-domprinter-cpp-/postdomonlyviewerwrapperpass/#ae7893486019ad40a008acf6afcdd8c96">anonymous{DomPrinter.cpp}::PostDomOnlyViewerWrapperPass::PostDomOnlyViewerWrapperPass</a>, <a href="/web-llvm/docs/api/structs/llvm/potentialvaluesstate/#a4d7b659d05b7e90c30dada185f3cb8b2">llvm::PotentialValuesState&lt; APInt &gt;::PotentialValuesState</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcelfobjectwriter-cpp-/ppcelfobjectwriter/#a73354500a951b97d15e8eca925bc1217">anonymous{PPCELFObjectWriter.cpp}::PPCELFObjectWriter::PPCELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/profostream/#af75ffd6173485c71c44b00cbd90d5b37">llvm::ProfOStream::ProfOStream</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a65aa4de0a6a0f21de4233170c7b012d5">llvm::raw_fd_ostream::raw_fd_ostream</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream/#ac9a76e6fdfee784d51393f12ce7c5256">llvm::raw_fd_stream::raw_fd_stream</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-socket-stream/#a86d8427648f496899f5aeb5e92ea6e81">llvm::raw_socket_stream::raw_socket_stream</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/readstate/#ac10e29a79384158a08244929e5b7caf4">llvm::mca::ReadState::ReadState</a>, <a href="/web-llvm/docs/api/structs/llvm/detail/recordkeeperimpl/#af84c49c869ad907f891c5c1c81440b4f">llvm::detail::RecordKeeperImpl::RecordKeeperImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/redundantinstrelimination/#aee884901a4bad6e0e83df32395854f3e">anonymous{HexagonBitSimplify.cpp}::RedundantInstrElimination::RedundantInstrElimination</a>, <a href="/web-llvm/docs/api/structs/anonymous-regionprinter-cpp-/regiononlyprinter/#a247c12d1dd17b2cfb3ef91d59c209e8d">anonymous{RegionPrinter.cpp}::RegionOnlyPrinter::RegionOnlyPrinter</a>, <a href="/web-llvm/docs/api/structs/anonymous-regionprinter-cpp-/regiononlyviewer/#afc4e1d6a2e67ed8c45bf320eeb390880">anonymous{RegionPrinter.cpp}::RegionOnlyViewer::RegionOnlyViewer</a>, <a href="/web-llvm/docs/api/classes/llvm/regorconstant/#a152c34e1735ab8d760da7aadf306f6c2">llvm::RegOrConstant::RegOrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a542eddcb7089b3159051d9a1c60eb872">llvm::RegPressureTracker::RegPressureTracker</a>, <a href="/web-llvm/docs/api/classes/anonymous-lockfilemanager-cpp-/removeuniquelockfileonsignal/#a2808d6ab8eaca1641b199df415589d0c">anonymous{LockFileManager.cpp}::RemoveUniqueLockFileOnSignal::RemoveUniqueLockFileOnSignal</a>, <a href="/web-llvm/docs/api/structs/llvm/spirv/requirements/#aeab31b3ffa3defb1ff662bd838b9d1bb">llvm::SPIRV::Requirements::Requirements</a>, <a href="/web-llvm/docs/api/structs/livedebugvalues/resolveddbgop/#a169c1c7183328f95d04af9d400a04278">LiveDebugValues::ResolvedDbgOp::ResolvedDbgOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvelfobjectwriter-cpp-/riscvelfobjectwriter/#acabdeb8444e704a8b8ec0704048c4d0b">anonymous{RISCVELFObjectWriter.cpp}::RISCVELFObjectWriter::RISCVELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#ae1ad9b9cc567a789627f8230ddeee241">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::RopePieceBTreeLeaf</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a86fc272b516cc390141710ff1b16b74b">llvm::SCEVExpander::SCEVExpander</a>, <a href="/web-llvm/docs/api/structs/llvm/setstate/#a7fd1b43ac6fa7cdee1ab2b8292fa63a2">llvm::SetState&lt; BaseTy &gt;::SetState</a>, <a href="/web-llvm/docs/api/structs/llvm/setstate/#ac9c7cb23606080e728c9cec128089a16">llvm::SetState&lt; BaseTy &gt;::SetState</a>, <a href="/web-llvm/docs/api/structs/llvm/simoderegisterdefaults/#a5c51e7c717aeeb4ea130f6a95f8d7d6a">llvm::SIModeRegisterDefaults::SIModeRegisterDefaults</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint/#a7ccd6b8cee73c66735677d1044f3121f">llvm::detail::SlowDynamicAPInt::SlowDynamicAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a3a09740ee84a5cf14da589c2217286b1">llvm::SmallPtrSetImplBase::SmallPtrSetImplBase</a>, <a href="/web-llvm/docs/api/classes/llvm/smallsetiterator/#ad90691b19097c1ecda1672715a0fdee9">llvm::SmallSetIterator&lt; T, N, C &gt;::SmallSetIterator</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcelfobjectwriter-cpp-/sparcelfobjectwriter/#a8f5e0d70b3d66db689282ab31963af33">anonymous{SparcELFObjectWriter.cpp}::SparcELFObjectWriter::SparcELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcv9targetmachine/#a51b1965862d7ee12bf2f35b4d011acd3">llvm::SparcV9TargetMachine::SparcV9TargetMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a>, <a href="/web-llvm/docs/api/classes/anonymous-stacksafetyanalysis-cpp-/stacksafetylocalanalysis/#a01512ae36dc3d3026dc85bcfe8758e87">anonymous{StackSafetyAnalysis.cpp}::StackSafetyLocalAnalysis::StackSafetyLocalAnalysis</a>, <a href="/web-llvm/docs/api/structs/llvm/object/windowsresourceparser/stringorid/#a5362183134493622cb2454a8b6d571d7">llvm::object::WindowsResourceParser::StringOrID::StringOrID</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a516a65564958ed71cc1e66256604ae44">llvm::SUnit::SUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ab6f654823b1290408013a587551746aa">llvm::SUnit::SUnit</a>, <a href="/web-llvm/docs/api/structs/llvm/symbolinfoty/#a268f8502696297743a34f43225dcf722">llvm::SymbolInfoTy::SymbolInfoTy</a>, <a href="/web-llvm/docs/api/structs/llvm/symbolinfoty/#a3ce41f3958ca76dd48665c9e419b9d46">llvm::SymbolInfoTy::SymbolInfoTy</a>, <a href="/web-llvm/docs/api/structs/llvm/pdb/symbollistwrapper/#a4d2e126de50f0e2d37145402349d9c98">llvm::pdb::SymbolListWrapper::SymbolListWrapper</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzelfobjectwriter-cpp-/systemzelfobjectwriter/#a9f6f30d3ae5b4fb7f08acb1308f5a268">anonymous{SystemZELFObjectWriter.cpp}::SystemZELFObjectWriter::SystemZELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#af0f3705b7e516b390c0e162bac07f31c">llvm::TargetOptions::TargetOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/textcodegendatareader/#ae69f5c7f0c299614d5f4889b180df61a">llvm::TextCodeGenDataReader::TextCodeGenDataReader</a>, <a href="/web-llvm/docs/api/classes/llvm/textinstrprofreader/#a695aae8d351cd41d0b6ae8400dc864b3">llvm::TextInstrProfReader::TextInstrProfReader</a>, <a href="/web-llvm/docs/api/classes/anonymous-trierawhashmap-cpp-/triesubtrie/#ad54871b3c817ff398c171e1e7fbc0978">anonymous{TrieRawHashMap.cpp}::TrieSubtrie::TrieSubtrie</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/valueiterator/#ab068e1ab5d665c69e39a07054933d9db">llvm::DWARFDebugNames::ValueIterator::ValueIterator</a>, <a href="/web-llvm/docs/api/classes/anonymous-veelfobjectwriter-cpp-/veelfobjectwriter/#a68ab80ae191d28db0fbacb3ce5e85716">anonymous{VEELFObjectWriter.cpp}::VEELFObjectWriter::VEELFObjectWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#a4fafd300d1f91dde5d25088bdd016a48">llvm::VersionTuple::VersionTuple</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#a17cefd8047b48e93204f487c3a8ccd35">llvm::VersionTuple::VersionTuple</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#a11e84ec3d50c411590ee1f544f925526">llvm::VersionTuple::VersionTuple</a>, <a href="/web-llvm/docs/api/classes/anonymous-wasmobjectwriter-cpp-/wasmobjectwriter/#a479ab369806e07577a69b69be2bc575e">anonymous{WasmObjectWriter.cpp}::WasmObjectWriter::WasmObjectWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyfastisel-cpp-/webassemblyfastisel/#a6e71c29d48aa6b75ec5a0ab52b28e67d">anonymous{WebAssemblyFastISel.cpp}::WebAssemblyFastISel::WebAssemblyFastISel</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#a074ebe9dba71f028e4f3f2ea8d7482ea">llvm::WebAssemblyFrameLowering::WebAssemblyFrameLowering</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtpass/#a814f3a3099ffb2aee02929c0c790a326">llvm::WholeProgramDevirtPass::WholeProgramDevirtPass</a>, <a href="/web-llvm/docs/api/classes/llvm/withcache/#a74630a9dd47263a96aa560fb905ed58a">llvm::WithCache&lt; Arg &gt;::WithCache</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#aac7b6f011839cfcf4d25443e735b57a5">llvm::X86RegisterInfo::X86RegisterInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoffobjectwriter-cpp-/xcoffwriter/#a120cd2ed610d49b8b5549ca0868442c0">anonymous{XCOFFObjectWriter.cpp}::XCOFFWriter::XCOFFWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-xtensaelfobjectwriter-cpp-/xtensaobjectwriter/#a27efb67b78e1b86fc08ffdd0eeff507c">anonymous{XtensaELFObjectWriter.cpp}::XtensaObjectWriter::XtensaObjectWriter</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensatargetmachine/#a64e6168e76349ecff07a940de2e285a5">llvm::XtensaTargetMachine::XtensaTargetMachine</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"basicaa"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
