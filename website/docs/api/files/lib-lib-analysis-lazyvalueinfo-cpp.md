---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/lazyvalueinfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `LazyValueInfo.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazyvalueinfo-h">llvm/Analysis/LazyValueInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/denseset-h">llvm/ADT/DenseSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">llvm/Analysis/AssumptionCache.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/constantfolding-h">llvm/Analysis/ConstantFolding.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionsimplify-h">llvm/Analysis/InstructionSimplify.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/passes-h">llvm/Analysis/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">llvm/Analysis/ValueLattice.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/assemblyannotationwriter-h">llvm/IR/AssemblyAnnotationWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cfg-h">llvm/IR/CFG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">llvm/IR/ConstantRange.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">llvm/IR/ValueHandle.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">llvm/Support/FormattedStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">llvm/Support/KnownBits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;optional&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-lazyvalueinfo-cpp-">anonymous{LazyValueInfo.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/anonymous-lazyvalueinfo-cpp-">anonymous{LazyValueInfo.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-lazyvalueinfo-cpp-/lvivaluehandle">LVIValueHandle</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-lazyvalueinfo-cpp-/lazyvalueinfocache">LazyValueInfoCache</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the cache kept by <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo">LazyValueInfo</a> which maintains information about queries across the clients' queries. <a href="/web-llvm/docs/api/classes/anonymous-lazyvalueinfo-cpp-/lazyvalueinfocache/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-lazyvalueinfo-cpp-/lazyvalueinfocache/blockcacheentry">BlockCacheEntry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is all of the cached information for one basic block. <a href="/web-llvm/docs/api/structs/anonymous-lazyvalueinfo-cpp-/lazyvalueinfocache/blockcacheentry/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/anonymous-lazyvalueinfo-cpp-/lazyvalueinfoannotatedwriter">LazyValueInfoAnnotatedWriter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An assembly annotator class to print LazyValueCache information in comments. <a href="/web-llvm/docs/api/classes/llvm/anonymous-lazyvalueinfo-cpp-/lazyvalueinfoannotatedwriter/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfoimpl">LazyValueInfoImpl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac62283130ff1d80a036fae76f36ed1f4">INITIALIZE_PASS_BEGIN</a> (LazyValueInfoWrapperPass, "lazy-value-info", "Lazy Value Information Analysis", false, true) INITIALIZE_PASS_END(LazyValueInfoWrapperPass</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59121faba668261cf400df39e3592637">hasSingleValue</a> (const ValueLatticeElement &amp;Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this lattice value represents at most one possible value. <a href="#a59121faba668261cf400df39e3592637">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa116214bf0f5cf6201935447b27334e8">getFromRangeMetadata</a> (Instruction *BBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83ab0f23301b354195c73654a6cbaba7">AddNonNullPointer</a> (Value *Ptr, NonNullPointerSet &amp;PtrSet)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57fe7ad4bdba0fb0a5f6cbe98fc7f146">AddNonNullPointersByInstruction</a> (Instruction *I, NonNullPointerSet &amp;PtrSet)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adef8cd15931effa7104867a65c0fd5ea">matchICmpOperand</a> (APInt &amp;Offset, Value *LHS, Value *Val, ICmpInst::Predicate Pred)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a587440f5e057e5ec16ccb30c878cb554">getRangeViaSLT</a> (CmpInst::Predicate Pred, APInt RHS, function_ref&lt; std::optional&lt; ConstantRange &gt;(const APInt &amp;)&gt; Fn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61c6720db574963baad9d12d32a3c6ad">getValueFromICmpCtpop</a> (ICmpInst::Predicate Pred, Value *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get value range for a "ctpop(Val) Pred RHS" condition. <a href="#a61c6720db574963baad9d12d32a3c6ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb6e73547764d0338afa32e54ad785cf">getValueFromOverflowCondition</a> (Value *Val, WithOverflowInst *WO, bool IsTrueDest)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7313a8e8cc1cfd30545ed00b1eb3a11d">usesOperand</a> (User *Usr, Value *Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0711d76da3cc5dafcb9370941e9c1817">isOperationFoldable</a> (User *Usr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7467c1c3eff398cd97c3d8a2b2cebac0">constantFoldUser</a> (User *Usr, Value *Op, const APInt &amp;OpConstVal, const DataLayout &amp;DL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad922c9d738ce5ff795e0b876b4ee30b0">isKnownNonConstant</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we can statically tell that this value will never be a "useful" constant. <a href="#ad922c9d738ce5ff795e0b876b4ee30b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4cfc0065b09dbea4311561f67c2e3ea">getPredicateResult</a> (CmpInst::Predicate Pred, Constant *C, const ValueLatticeElement &amp;Val, const DataLayout &amp;DL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a606f0f9e7e2731b55f11e30247033341">MaxProcessedPerValue</a> = 500</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">lazy value</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7f64bcc544dcefb2e068282af1c549d">info</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">lazy value Lazy <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp/#ad9c6bcebef21826e699aeb87ce0a578c">Information</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a665fd813b3d347f59e80e670babf2a57">Analysis</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">lazy value Lazy <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp/#ad9c6bcebef21826e699aeb87ce0a578c">Information</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41786f0a146a3541e1fd74d76eb4ebcd">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"lazy-value-info"</td>
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

### AddNonNullPointer() {#a83ab0f23301b354195c73654a6cbaba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AddNonNullPointer (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, NonNullPointerSet &amp; PtrSet)</td>
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



<p>Definition at line 625 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="#a57fe7ad4bdba0fb0a5f6cbe98fc7f146">AddNonNullPointersByInstruction</a>.</p>

</div>
</div>

### AddNonNullPointersByInstruction() {#a57fe7ad4bdba0fb0a5f6cbe98fc7f146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AddNonNullPointersByInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, NonNullPointerSet &amp; PtrSet)</td>
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



<p>Definition at line 631 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<p>References <a href="#a83ab0f23301b354195c73654a6cbaba7">AddNonNullPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### constantFoldUser() {#a7467c1c3eff398cd97c3d8a2b2cebac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueLatticeElement constantFoldUser (<a href="/web-llvm/docs/api/classes/llvm/user">User</a> * Usr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; OpConstVal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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



<p>Definition at line 1374 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#aeba3c4846ce91323f585f957963d8f67">llvm::CastInst::getDestTy</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a0154da1d06b29a1d5649607ae2dfc389">llvm::Constant::getIntegerValue</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a31bf07f3f61525486633bc1d0bbaf029">llvm::BinaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a3685b2128d8e6917000e4adc3b266ff6">llvm::CastInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#afa0befbad06a536ee25c232941a09856">llvm::ValueLatticeElement::getOverdefined</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a1fa37f9808504c2a3d588ec0aa1532ac">llvm::ValueLatticeElement::getRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a0711d76da3cc5dafcb9370941e9c1817">isOperationFoldable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa750395459fa1eb7130d6de8e3d074f6">llvm::simplifyBinOp</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a57b7707bae1b59648d9b09e7c3e1106c">llvm::simplifyCastInst</a>.</p>

</div>
</div>

### getFromRangeMetadata() {#aa116214bf0f5cf6201935447b27334e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueLatticeElement getFromRangeMetadata (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * BBI)</td>
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



<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5193c3535375c450b9430e5671cbeb2d">llvm::getConstantRangeFromMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6c09737e146b2d816c911a047ac67ba4">llvm::Instruction::getMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#afa0befbad06a536ee25c232941a09856">llvm::ValueLatticeElement::getOverdefined</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a407852423447c9c318189650976659fb">getRange</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a1fa37f9808504c2a3d588ec0aa1532ac">llvm::ValueLatticeElement::getRange</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfoimpl/#a6aef100d648e62bb628c87faf0ae9534">llvm::LazyValueInfoImpl::getValueAt</a>.</p>

</div>
</div>

### getPredicateResult() {#ac4cfc0065b09dbea4311561f67c2e3ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * getPredicateResult (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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



<p>Definition at line 1829 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3cd3a3ec28036937ecebe767498ba55d">llvm::ConstantFoldCompareInstOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#ab79de6040b9a8bacd648c5916fb36cd9">llvm::ValueLatticeElement::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a73e8c58e4d729c42b5f27e3d847c54f8">llvm::ValueLatticeElement::getConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa2a54b545d237ecfe450fd1292f7675e">llvm::CmpInst::getInversePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a908b087596156c6a6c61275c49bece7d">llvm::ValueLatticeElement::getNotConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a53f1dcccf8991c637acec7883aba7bfc">llvm::ConstantRange::icmp</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a62d37ceb318e78806df7e0a928b0eb1c">llvm::ValueLatticeElement::isConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a7ab774f05d02e4bbe7817798cdf19186">llvm::ValueLatticeElement::isConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a3e15dd37f1b32b64bf9ff7c7ad03d70d">llvm::ValueLatticeElement::isNotConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#ae4b6abe77abf42fb02081a6cc41a0132">llvm::Constant::isNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a0206e74dec02d952d1b620a7b63f5694">llvm::CmpInst::makeCmpResultType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo/#ad10df0e6ccca0fc951b845e3a007e385">llvm::LazyValueInfo::getPredicateAt</a> and <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo/#a30223a7e41ce3064f9d85b3fe3ee7005">llvm::LazyValueInfo::getPredicateOnEdge</a>.</p>

</div>
</div>

### getRangeViaSLT() {#a587440f5e057e5ec16ccb30c878cb554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ConstantRange &gt; getRangeViaSLT (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> RHS, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;)&gt; Fn)</td>
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



<p>Definition at line 1143 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa2a54b545d237ecfe450fd1292f7675e">llvm::CmpInst::getInversePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### getValueFromICmpCtpop() {#a61c6720db574963baad9d12d32a3c6ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueLatticeElement getValueFromICmpCtpop (ICmpInst::Predicate Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS)</td>
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

<p>Get value range for a "ctpop(Val) Pred RHS" condition.</p>

<p>Definition at line 1163 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#adcb96bd09d7c75c7669fa5f9d1190899">llvm::APInt::getHighBitsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ab01d8694a759a934e01f1c558c3ce862">llvm::APInt::getLimitedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad960e1ff48d25c382b6d28e7961f074e">llvm::APInt::getLowBitsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#acd8afecbb15ee69487d5339371f64a76">llvm::ConstantRange::getNonEmpty</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#afa0befbad06a536ee25c232941a09856">llvm::ValueLatticeElement::getOverdefined</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a1fa37f9808504c2a3d588ec0aa1532ac">llvm::ValueLatticeElement::getRange</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ab7f67c2ed8b2799c64ec64ca31d75c60">llvm::ConstantRange::getUnsignedMax</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a4d69e164b5fb0f73a15a07119c4302f7">llvm::ConstantRange::getUnsignedMin</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa89e9cec92a0b38d2f47a077bf12cc98">llvm::ConstantRange::makeExactICmpRegion</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### getValueFromOverflowCondition() {#acb6e73547764d0338afa32e54ad785cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueLatticeElement getValueFromOverflowCondition (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/withoverflowinst">WithOverflowInst</a> * WO, bool IsTrueDest)</td>
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



<p>Definition at line 1288 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryopintrinsic/#aa73e62aac1753cb7b3c3aaccef3df8b1">llvm::BinaryOpIntrinsic::getBinaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryopintrinsic/#abd530ffa05240e0728bf85169dc7abcc">llvm::BinaryOpIntrinsic::getLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryopintrinsic/#a3f8c92c02ddf72337cdd32207498e731">llvm::BinaryOpIntrinsic::getNoWrapKind</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#afa0befbad06a536ee25c232941a09856">llvm::ValueLatticeElement::getOverdefined</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a1fa37f9808504c2a3d588ec0aa1532ac">llvm::ValueLatticeElement::getRange</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryopintrinsic/#a0583d2d049d59cf53ccfd2b6f4e53c87">llvm::BinaryOpIntrinsic::getRHS</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aaaa2f5e2c6c3122d2b484f9e50950e18">llvm::ConstantRange::inverse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aeddb6f4f9ffcb9e893e5cb321b7a7f83">llvm::ConstantRange::makeExactNoWrapRegion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>

</div>
</div>

### hasSingleValue() {#a59121faba668261cf400df39e3592637}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasSingleValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement">ValueLatticeElement</a> &amp; Val)</td>
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

<p>Returns true if this lattice value represents at most one possible value.</p>


<p>This is as precise as any lattice value can get while still representing reachable code.</p>


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a73e8c58e4d729c42b5f27e3d847c54f8">llvm::ValueLatticeElement::getConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a62d37ceb318e78806df7e0a928b0eb1c">llvm::ValueLatticeElement::isConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a7ab774f05d02e4bbe7817798cdf19186">llvm::ValueLatticeElement::isConstantRange</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a91cf2c952ea87d701fe608fe4aaabfe4">llvm::ConstantRange::isSingleElement</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#ac62283130ff1d80a036fae76f36ed1f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (<a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfowrapperpass">LazyValueInfoWrapperPass</a>, "lazy-value-info", "Lazy <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp/#ad9c6bcebef21826e699aeb87ce0a578c">Information</a> Analysis", false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### isKnownNonConstant() {#ad922c9d738ce5ff795e0b876b4ee30b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isKnownNonConstant (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Returns true if we can statically tell that this value will never be a "useful" constant.</p>


<p>In practice, this means we've got something like an alloca or a malloc call for which a comparison against a constant can only be guarding dead code. Note that we are potentially giving up some precision in dead code (a constant result) in favour of avoiding a expensive search for a easily answered common query.</p>


<p>Definition at line 1756 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo/#a8da33528c75f7337a0a4b87118c63340">llvm::LazyValueInfo::getConstant</a>.</p>

</div>
</div>

### isOperationFoldable() {#a0711d76da3cc5dafcb9370941e9c1817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isOperationFoldable (<a href="/web-llvm/docs/api/classes/llvm/user">User</a> * Usr)</td>
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



<p>Definition at line 1366 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a7467c1c3eff398cd97c3d8a2b2cebac0">constantFoldUser</a>.</p>

</div>
</div>

### matchICmpOperand() {#adef8cd15931effa7104867a65c0fd5ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool matchICmpOperand (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Offset, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, ICmpInst::Predicate Pred)</td>
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



<p>Definition at line 1085 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a9670636a8101c675bd9ef6d40803afe3">llvm::PatternMatch::m_AddLike</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1981217907f3dfb1d21e902d0396fb4d">llvm::PatternMatch::m_c_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae80cbfea2025ff7bd0770f30be6e050a">llvm::PatternMatch::m_c_Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### usesOperand() {#a7313a8e8cc1cfd30545ed00b1eb3a11d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool usesOperand (<a href="/web-llvm/docs/api/classes/llvm/user">User</a> * Usr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op)</td>
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



<p>Definition at line 1358 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a0b931781aa589c6ebe64a76c1447e5b2">llvm::User::operands</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### Analysis {#a665fd813b3d347f59e80e670babf2a57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lazy value Lazy Value Information Analysis</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>

</div>
</div>

### false {#a41786f0a146a3541e1fd74d76eb4ebcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lazy value Lazy Value Information false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>

</div>
</div>

### info {#ad7f64bcc544dcefb2e068282af1c549d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lazy value info</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a66a4df49046ec16dd9c64d36ba3cb62c">ARM64EmitRuntimeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a6574f704d2fbd168f81e7552695170a8">ARM64EmitUnwindInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a0bd3fbe76161d42d7470f0dd7dd634de">ARM64EmitUnwindInfoForSegment</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a83e6ea9ad14301bc03c55827f0689dc0">ARM64FindSegmentsInFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#adaf1a735e35b87dee5107e5ccd874783">ARM64ProcessEpilogs</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a48d2597504af337577491cde138a142b">ARMEmitRuntimeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a01564c0b334eed6d8b36993f0ef70b73">checkARM64PackedEpilog</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a73622e67d89cdc5f662981287e16879f">checkARMPackedEpilog</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#aa186dddb4125136ff27007f97e26759a">EmitRuntimeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a5d75ea3f9831315ebdb816d70c58c30b">EmitUnwindInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/win64eh/arm64unwindemitter/#a23e988e2f737319fba0ad0f50b4791c3">llvm::Win64EH::ARM64UnwindEmitter::EmitUnwindInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/win64eh/armunwindemitter/#ae3581e58aa167be222e1d2b9c164b10a">llvm::Win64EH::ARMUnwindEmitter::EmitUnwindInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/win64eh/unwindemitter/#aaad7a7f0ae118b34d41f8ceed7136672">llvm::Win64EH::UnwindEmitter::EmitUnwindInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#ae4bde92835730133920c426289e5d59b">findLiveReferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a9e599e8d393ec15804b6efbc478393a3">FindMatchingEpilog</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a01395ad9f4628da9087d6dd936e63201">llvm::CCState::getInRegsParamInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a242f3e03f104dc030614c21db016e206">llvm::TargetLowering::getMultipleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a0f12063b62264c753e65abb8e9ff29d8">llvm::ARMTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a7bab53d05e5532f9b9d89f3427b1c5e7">llvm::AVRTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a685bfe474ca920468f17fc82cf4664e6">llvm::PPCTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a237a27aeef06752d11d7ab1dc1560239">llvm::SparcTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a900def112d7e109823a5bb89a3c01dd8">llvm::SystemZTargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#afaa66a325b7b8c5c79eb2c8e9822ffd2">llvm::TargetLowering::getSingleConstraintMatchWeight</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a864a2ad11bbf83cf2b910e43d461cd02">insertParsePoints</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a3b29f4fee068660e847497750070f564">llvm::opt::Option::Option</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a17d6db03c2e193f9d391dae5b3847edf">recomputeLiveInValues</a>, <a href="/web-llvm/docs/api/classes/anonymous-selectiondagbuilder-cpp-/sdiselasmoperandinfo/#a87befb4affba58089c58a8b811fccc7c">anonymous{SelectionDAGBuilder.cpp}::SDISelAsmOperandInfo::SDISelAsmOperandInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a6f479176a3ecfda8d65a409c53b5b3bf">llvm::MachO::swapStruct</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a5c6c18ec71fabe4422710878b3d9c128">tryARM64PackedUnwind</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a982dd5c343c1b1e191b5cc1d00fefaf6">tryARMPackedUnwind</a> and <a href="/web-llvm/docs/api/classes/anonymous-elfobjectwriter-cpp-/symboltablewriter/#a9b91d63de477829a841c50e79b34f52a">anonymous{ELFObjectWriter.cpp}::SymbolTableWriter::writeSymbol</a>.</p>

</div>
</div>

### MaxProcessedPerValue {#a606f0f9e7e2731b55f11e30247033341}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned MaxProcessedPerValue = 500</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"lazy-value-info"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
