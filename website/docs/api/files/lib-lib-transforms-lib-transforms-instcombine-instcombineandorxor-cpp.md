---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `InstCombineAndOrXor.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">InstCombineInternal.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cmpinstanalysis-h">llvm/Analysis/CmpInstAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionsimplify-h">llvm/Analysis/InstructionSimplify.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">llvm/IR/ConstantRange.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">llvm/Transforms/InstCombine/InstCombiner.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/local-h">llvm/Transforms/Utils/Local.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/intpart">IntPart</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MaskedICmpType { <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Classify (icmp eq (A &amp; B), C) and (icmp ne (A &amp; B), C) as matching patterns that can be simplified. <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89cfa00019cb17baa05532705ea198e0">getNewICmpValue</a> (unsigned Code, bool Sign, Value *LHS, Value *RHS, InstCombiner::BuilderTy &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the complement of getICmpCode, which turns an opcode and two operands into either a constant true or false, or a brand new ICmp instruction. <a href="#a89cfa00019cb17baa05532705ea198e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f470beafc2cabc85d7e9fd044c77977">getFCmpValue</a> (unsigned Code, Value *LHS, Value *RHS, InstCombiner::BuilderTy &amp;Builder, FMFSource FMF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the complement of getFCmpCode, which turns an opcode and two operands into either a FCmp instruction, or a true/false constant. <a href="#a0f470beafc2cabc85d7e9fd044c77977">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39257c6c73db3440e6d05b9eec5999a0">getMaskedICmpType</a> (Value *A, Value *B, Value *C, ICmpInst::Predicate Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the set of patterns (from <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1">MaskedICmpType</a>) that (icmp SCC (A &amp; B), C) satisfies. <a href="#a39257c6c73db3440e6d05b9eec5999a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09c36c07a47775cef8f8e93d8090d919">conjugateICmpMask</a> (unsigned Mask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert an analysis of a masked ICmp into its equivalent if all boolean operations had the opposite sense. <a href="#a09c36c07a47775cef8f8e93d8090d919">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69e1f8a031335ca798357c796ae7d061">decomposeBitTestICmp</a> (Value *Cond, CmpInst::Predicate &amp;Pred, Value *&amp;X, Value *&amp;Y, Value *&amp;Z)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; std::pair&lt; unsigned, unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeee622fb99bdc4c058a9ef179d0a0d09">getMaskedTypeForICmpPair</a> (Value *&amp;A, Value *&amp;B, Value *&amp;C, Value *&amp;D, Value *&amp;E, Value *LHS, Value *RHS, ICmpInst::Predicate &amp;PredL, ICmpInst::Predicate &amp;PredR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle (icmp(A &amp; B) ==/!= C) &amp;/| (icmp(A &amp; D) ==/!= E). <a href="#aeee622fb99bdc4c058a9ef179d0a0d09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7134dae528abf2cf2ef1bd1d92f9ce39">foldLogOpOfMaskedICmps_NotAllZeros_BMask_Mixed</a> (Value *LHS, Value *RHS, bool IsAnd, Value *A, Value *B, Value *D, Value *E, ICmpInst::Predicate PredL, ICmpInst::Predicate PredR, InstCombiner::BuilderTy &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to fold (icmp(A &amp; B) ==/!= C) &amp;/| (icmp(A &amp; D) ==/!= E) into a single (icmp(A &amp; X) ==/!= Y), where the left-hand side is of type Mask_NotAllZeros and the right hand side is of type BMask_Mixed. <a href="#a7134dae528abf2cf2ef1bd1d92f9ce39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e02c18bf8cc049ce1589b8f95618a0b">foldLogOpOfMaskedICmpsAsymmetric</a> (Value *LHS, Value *RHS, bool IsAnd, Value *A, Value *B, Value *C, Value *D, Value *E, ICmpInst::Predicate PredL, ICmpInst::Predicate PredR, unsigned LHSMask, unsigned RHSMask, InstCombiner::BuilderTy &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to fold (icmp(A &amp; B) ==/!= 0) &amp;/| (icmp(A &amp; D) ==/!= E) into a single (icmp(A &amp; X) ==/!= Y), where the left-hand side and the right hand side aren't of the common mask pattern type. <a href="#a2e02c18bf8cc049ce1589b8f95618a0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e3285faf503c1c0ab9615ef71bc7d96">foldLogOpOfMaskedICmps</a> (Value *LHS, Value *RHS, bool IsAnd, bool IsLogical, InstCombiner::BuilderTy &amp;Builder, const SimplifyQuery &amp;Q)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to fold (icmp(A &amp; B) ==/!= C) &amp;/| (icmp(A &amp; D) ==/!= E) into a single (icmp(A &amp; X) ==/!= Y). <a href="#a0e3285faf503c1c0ab9615ef71bc7d96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1497784bc56d64f953026632a186005">foldAndOrOfICmpsWithPow2AndWithZero</a> (InstCombiner::BuilderTy &amp;Builder, ICmpInst *LHS, ICmpInst *RHS, bool IsAnd, const SimplifyQuery &amp;Q)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f569ebf4402ad560d7c147f688ac05a">foldSignedTruncationCheck</a> (ICmpInst *ICmp0, ICmpInst *ICmp1, Instruction &amp;CxtI, InstCombiner::BuilderTy &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>General pattern: X &amp; Y. <a href="#a1f569ebf4402ad560d7c147f688ac05a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a034d63ecfce76136f23c28e698d7a720">foldIsPowerOf2OrZero</a> (ICmpInst *Cmp0, ICmpInst *Cmp1, bool IsAnd, InstCombiner::BuilderTy &amp;Builder, InstCombinerImpl &amp;IC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fold (icmp eq ctpop(X) 1) | (icmp eq X 0) into (icmp ult ctpop(X) 2) and fold (icmp ne ctpop(X) 1) &amp; (icmp ne X 0) into (icmp ugt ctpop(X) 1). <a href="#a034d63ecfce76136f23c28e698d7a720">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22b32bcfbb9aec8a8fcb9826f40a3955">foldIsPowerOf2</a> (ICmpInst *Cmp0, ICmpInst *Cmp1, bool JoinedByAnd, InstCombiner::BuilderTy &amp;Builder, InstCombinerImpl &amp;IC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reduce a pair of compares that check if a value has exactly 1 bit set. <a href="#a22b32bcfbb9aec8a8fcb9826f40a3955">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5532e05d5caa4fb5e2b8512aa3095f1e">foldNegativePower2AndShiftedMask</a> (Value *A, Value *B, Value *D, Value *E, ICmpInst::Predicate PredL, ICmpInst::Predicate PredR, InstCombiner::BuilderTy &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to fold (icmp(A &amp; B) == 0) &amp; (icmp(A &amp; D) != E) into (icmp A u&lt; D) iff B is a contiguous set of ones starting from the most significant bit (negative power of 2), D and E are equal, and D is a contiguous set of ones starting at the most significant zero bit in B. <a href="#a5532e05d5caa4fb5e2b8512aa3095f1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a609a05f40709dea74bb5cd248c5816fd">foldPowerOf2AndShiftedMask</a> (ICmpInst *Cmp0, ICmpInst *Cmp1, bool JoinedByAnd, InstCombiner::BuilderTy &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to fold ((icmp X u&lt; P) &amp; (icmp(X &amp; M) != M)) or ((icmp X s&gt; -1) &amp; (icmp(X &amp; M) != M)) into (icmp X u&lt; M). <a href="#a609a05f40709dea74bb5cd248c5816fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24dce8fa354f0f1d52209e805f0ae6a3">foldUnsignedUnderflowCheck</a> (ICmpInst *ZeroICmp, ICmpInst *UnsignedICmp, bool IsAnd, const SimplifyQuery &amp;Q, InstCombiner::BuilderTy &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Commuted variants are assumed to be handled by calling this function again with the parameters swapped. <a href="#a24dce8fa354f0f1d52209e805f0ae6a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/intpart">IntPart</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7662d7ee7f100c9455f4a2c7e4992929">matchIntPart</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match an extraction of bits from an integer. <a href="#a7662d7ee7f100c9455f4a2c7e4992929">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a940bbfdea38f2643d0b63c2cc5af4a82">extractIntPart</a> (const IntPart &amp;P, IRBuilderBase &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Materialize an extraction of bits from an integer in IR. <a href="#a940bbfdea38f2643d0b63c2cc5af4a82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afce22397c3eff1d8c0dc8e3d8c464829">foldAndOrOfICmpsWithConstEq</a> (ICmpInst *Cmp0, ICmpInst *Cmp1, bool IsAnd, bool IsLogical, InstCombiner::BuilderTy &amp;Builder, const SimplifyQuery &amp;Q)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reduce logic-of-compares with equality to a constant by substituting a common operand with the constant. <a href="#afce22397c3eff1d8c0dc8e3d8c464829">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67ccec2dd2fc482ea50af1764f1db598">stripSignOnlyFPOps</a> (Value *Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ignore all operations which only change the sign of a value, returning the underlying magnitude value. <a href="#a67ccec2dd2fc482ea50af1764f1db598">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e92e028c2dd81bf7d518dfc3960624a">matchIsNotNaN</a> (FCmpInst::Predicate P, Value *LHS, Value *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Matches canonical form of isnan, fcmp ord x, 0. <a href="#a9e92e028c2dd81bf7d518dfc3960624a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9977c80be67ea7e51bb37ee242d1cc4c">matchUnorderedInfCompare</a> (FCmpInst::Predicate P, Value *LHS, Value *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Matches fcmp u__ x, +/-inf. <a href="#a9977c80be67ea7e51bb37ee242d1cc4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5946d75decfd106d2b75af6d59009f34">matchIsFiniteTest</a> (InstCombiner::BuilderTy &amp;Builder, FCmpInst *LHS, FCmpInst *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>and (fcmp ord x, 0), (fcmp u* x, inf) -&gt; fcmp o* x, inf <a href="#a5946d75decfd106d2b75af6d59009f34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a151e95d3f063067aa27c74930296a25e">matchIsFPClassLikeFCmp</a> (Value *Op, Value *&amp;ClassVal, uint64_t &amp;ClassMask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match an fcmp against a special value that performs a test possible by llvm.is.fpclass. <a href="#a151e95d3f063067aa27c74930296a25e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8208d3cd3c60073f5c9ceefec06ab2e3">reassociateFCmps</a> (BinaryOperator &amp;BO, InstCombiner::BuilderTy &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This a limited reassociation for a special case (see above) where we are checking if two values are either both NAN (unordered) or not-NAN (ordered). <a href="#a8208d3cd3c60073f5c9ceefec06ab2e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d3ce43f7795a8f4f6925bffbcc90279">matchDeMorgansLaws</a> (BinaryOperator &amp;I, InstCombiner &amp;IC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match variations of De Morgan's Laws: (~A &amp; ~B) == (~(A | B)) (~A | ~B) == (~(A &amp; B)) <a href="#a2d3ce43f7795a8f4f6925bffbcc90279">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45705c727d8388c014471504b4ab0c4e">foldLogicCastConstant</a> (BinaryOperator &amp;Logic, CastInst *Cast, InstCombinerImpl &amp;IC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fold {and,or,xor} (cast X), C. <a href="#a45705c727d8388c014471504b4ab0c4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a385c1da88456d434ee18caa8f48018c2">foldAndToXor</a> (BinaryOperator &amp;I, InstCombiner::BuilderTy &amp;Builder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26257c73e483eab4b0e15d53340de986">foldOrToXor</a> (BinaryOperator &amp;I, InstCombiner::BuilderTy &amp;Builder)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f025ca3dbad2ca618ad4bf63fa51bb0">canNarrowShiftAmt</a> (Constant *C, unsigned BitWidth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a constant shift amount is always less than the specified bit-width. <a href="#a3f025ca3dbad2ca618ad4bf63fa51bb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab01a210491dcbefc8db253f4dbaa6497">foldComplexAndOrPatterns</a> (BinaryOperator &amp;I, InstCombiner::BuilderTy &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try folding relatively complex patterns for both And and Or operations with all And and Or swapped. <a href="#ab01a210491dcbefc8db253f4dbaa6497">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac80e92048884e85b87ddd733785e44d9">reassociateForUses</a> (BinaryOperator &amp;BO, InstCombinerImpl::BuilderTy &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to reassociate a pair of binops so that values with one use only are part of the same instruction. <a href="#ac80e92048884e85b87ddd733785e44d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b8ca6f7206a11fd57d6e194b2523ffe">canonicalizeLogicFirst</a> (BinaryOperator &amp;I, InstCombiner::BuilderTy &amp;Builder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3ba7f841807b297e7c28874c285f538">foldBitwiseLogicWithIntrinsics</a> (BinaryOperator &amp;I, InstCombiner::BuilderTy &amp;Builder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a50775521fbb289313bb39964dabae3">simplifyAndOrWithOpReplaced</a> (Value *V, Value *Op, Value *RepOp, bool SimplifyOnly, InstCombinerImpl &amp;IC, unsigned Depth=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac800cc10159d350923dc27446b9123f0">matchFunnelShift</a> (Instruction &amp;Or, InstCombinerImpl &amp;IC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match UB-safe variants of the funnel shift intrinsic. <a href="#ac800cc10159d350923dc27446b9123f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e6840885acb4ffa3e94e81a70b392fc">matchOrConcat</a> (Instruction &amp;Or, InstCombiner::BuilderTy &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to combine or(zext(x),shl(zext(y),bw/2) concat packing patterns. <a href="#a9e6840885acb4ffa3e94e81a70b392fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7934618280f5dc61a34615b689744d1">areInverseVectorBitmasks</a> (Constant *C1, Constant *C2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If all elements of two constant vectors are 0/-1 and inverses, return true. <a href="#aa7934618280f5dc61a34615b689744d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45ec897890074179e7de73b934798976">foldAndOrOfICmpEqConstantAndICmp</a> (ICmpInst *LHS, ICmpInst *RHS, bool IsAnd, bool IsLogical, IRBuilderBase &amp;Builder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcce404670629549d0278e1641807377">foldOrOfInversions</a> (BinaryOperator &amp;I, InstCombiner::BuilderTy &amp;Builder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b3df3036740dfcdeb37c3ad977b039a">foldXorToXor</a> (BinaryOperator &amp;I, InstCombiner::BuilderTy &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A ^ B can be specified using other logic ops in a variety of patterns. <a href="#a3b3df3036740dfcdeb37c3ad977b039a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ff7fad11ba04c97f0a4b679c74cb394">visitMaskedMerge</a> (BinaryOperator &amp;I, InstCombiner::BuilderTy &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If we have a masked merge, in the canonical form of: (assuming that A only has one use.) | A | |B| ((x ^ y) &amp; M) ^ y | D |. <a href="#a1ff7fad11ba04c97f0a4b679c74cb394">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e07326546257c169a5aff0d8b822a00">foldNotXor</a> (BinaryOperator &amp;I, InstCombiner::BuilderTy &amp;Builder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2280e030e66011e1715514cd6965be59">canonicalizeAbs</a> (BinaryOperator &amp;Xor, InstCombiner::BuilderTy &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Canonicalize a shifty way to code absolute value to the more common pattern that uses negation and select. <a href="#a2280e030e66011e1715514cd6965be59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fda26317fcc1b226ecc5a9a28bf68fc">canFreelyInvert</a> (InstCombiner &amp;IC, Value *Op, Instruction *IgnoredUser)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bf246a84f7e8596777a0231fa7d7bc9">freelyInvert</a> (InstCombinerImpl &amp;IC, Value *Op, Instruction *IgnoredUser)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"instcombine"</td>
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

## Enumerations

### MaskedICmpType {#aa9c705ecec80ebd584bb3d54b48f7ee1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum MaskedICmpType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Classify (icmp eq (A &amp; B), C) and (icmp ne (A &amp; B), C) as matching patterns that can be simplified.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMask_AllOnes<a id="aa9c705ecec80ebd584bb3d54b48f7ee1a7cc1609a568ad3b240cf86126370e24f"></a></td>
<td class="doxyEnumItemDescription"> (=     1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMask_NotAllOnes<a id="aa9c705ecec80ebd584bb3d54b48f7ee1a54ee032f1a4a27e3066fbb88346cd49a"></a></td>
<td class="doxyEnumItemDescription"> (=     2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BMask_AllOnes<a id="aa9c705ecec80ebd584bb3d54b48f7ee1a4357ae5a8ec7cec4162a1f25c69558ff"></a></td>
<td class="doxyEnumItemDescription"> (=     4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BMask_NotAllOnes<a id="aa9c705ecec80ebd584bb3d54b48f7ee1a2b00a345b6b0214f7aa5cbe8203aeb3e"></a></td>
<td class="doxyEnumItemDescription"> (=     8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mask_AllZeros<a id="aa9c705ecec80ebd584bb3d54b48f7ee1a37651a7acaf5871fb8a4d593749c06f4"></a></td>
<td class="doxyEnumItemDescription"> (=    16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mask_NotAllZeros<a id="aa9c705ecec80ebd584bb3d54b48f7ee1ac7606c30ddb7a593051b6e5ad209f30c"></a></td>
<td class="doxyEnumItemDescription"> (=    32)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMask_Mixed<a id="aa9c705ecec80ebd584bb3d54b48f7ee1ada8a0932439ca5f15218c4d7cd43d895"></a></td>
<td class="doxyEnumItemDescription"> (=    64)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AMask_NotMixed<a id="aa9c705ecec80ebd584bb3d54b48f7ee1a1ee37b18b82ef426e90d86a093d45334"></a></td>
<td class="doxyEnumItemDescription"> (=   128)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BMask_Mixed<a id="aa9c705ecec80ebd584bb3d54b48f7ee1a3f5a9337c05ff64ea433ed2d4e9d49d5"></a></td>
<td class="doxyEnumItemDescription"> (=   256)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BMask_NotMixed<a id="aa9c705ecec80ebd584bb3d54b48f7ee1a10e63e798489e9c5ad2dc2c5ed98ac10"></a></td>
<td class="doxyEnumItemDescription"> (=   512)</td>
</tr>

</table>
</dd>
</dl>


<p>One of A and B is considered the mask. The other is the value. This is described as the "AMask" or "BMask" part of the enum. If the enum contains only "Mask", then both A and B can be considered masks. If A is the mask, then it was proven that (A &amp; C) == C. This is trivial if C == A or C == 0. If both A and C are constants, this proof is also easy. For the following explanations, we assume that A is the mask.</p>


<p>"AllOnes" declares that the comparison is true only if (A &amp; B) == A or all bits of A are set in B. Example: (icmp eq (A &amp; 3), 3) -&gt; AMask_AllOnes</p>


<p>"AllZeros" declares that the comparison is true only if (A &amp; B) == 0 or all bits of A are cleared in B. Example: (icmp eq (A &amp; 3), 0) -&gt; Mask_AllZeroes</p>


<p>"Mixed" declares that (A &amp; B) == C and C might or might not contain any number of one bits and zero bits. Example: (icmp eq (A &amp; 3), 1) -&gt; AMask_Mixed</p>


<p>"Not" means that in above descriptions "==" should be replaced by "!=". Example: (icmp ne (A &amp; 3), 3) -&gt; AMask_NotAllOnes</p>


<p>If the mask A contains a single bit, then the following is equivalent: (icmp eq (A &amp; B), A) equals (icmp ne (A &amp; B), 0) (icmp ne (A &amp; B), A) equals (icmp eq (A &amp; B), 0)</p>


<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### areInverseVectorBitmasks() {#aa7934618280f5dc61a34615b689744d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool areInverseVectorBitmasks (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C1, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C2)</td>
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

<p>If all elements of two constant vectors are 0/-1 and inverses, return true.</p>

<p>Definition at line 3124 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#acd530d0571f320d47d37e7ae51cf70ff">llvm::Constant::getAggregateElement</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a00ef056813d120034e387417e9cde341">llvm::PatternMatch::m_AllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>

</div>
</div>

### canFreelyInvert() {#a4fda26317fcc1b226ecc5a9a28bf68fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool canFreelyInvert (<a href="/web-llvm/docs/api/classes/llvm/instcombiner">InstCombiner</a> &amp; IC, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IgnoredUser)</td>
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



<p>Definition at line 4369 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#ab0cf90f56e055b09227ab0f84acc4083">llvm::InstCombiner::canFreelyInvertAllUsersOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#a1f819cdc746560fd28977b1175030cff">llvm::InstCombiner::isFreeToInvert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4e2dd07eceeed7496e6c3df4d364c91e">llvm::InstCombinerImpl::sinkNotIntoLogicalOp</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8d44c548f74b3d233a248672402b5dd1">llvm::InstCombinerImpl::sinkNotIntoOtherHandOfLogicalOp</a>.</p>

</div>
</div>

### canNarrowShiftAmt() {#a3f025ca3dbad2ca618ad4bf63fa51bb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool canNarrowShiftAmt (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C, unsigned BitWidth)</td>
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

<p>Return true if a constant shift amount is always less than the specified bit-width.</p>


<p>If not, the shift could create poison in the narrower type.</p>


<p>Definition at line 1944 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#afd8ce417d0ae1bee23037a373487fe42">llvm::PatternMatch::m_SpecificInt_ICMP</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>

</div>
</div>

### canonicalizeAbs() {#a2280e030e66011e1715514cd6965be59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * canonicalizeAbs (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; Xor, InstCombiner::BuilderTy &amp; Builder)</td>
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

<p>Canonicalize a shifty way to code absolute value to the more common pattern that uses negation and select.</p>

<p>Definition at line 4337 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectinst/#a09d8760fa31a7b8739acf71a4d2ac9d9">llvm::SelectInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a925d3d4bfc5ca46ef574619a0700e6d5">llvm::IRBuilderBase::CreateIsNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a7704bf68951054ffeb3efe605750e2d9">llvm::IRBuilderBase::CreateNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a7c779ce2ba55bc94f52014fc25f3d520">llvm::Value::hasNUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0c94f3ca4234f78cf22840e79087f3f2">llvm::PatternMatch::m_AShr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a9167d23c7fc4727aef51733d009e3f45">llvm::PatternMatch::m_c_Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5be13f3abb6bddf7ad9747b077da5a0e">llvm::PatternMatch::m_OneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea76feb79109026728a20736a8c6504548">llvm::Xor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaf7b6cd7c3ceb4af17b610cba09648c9">llvm::InstCombinerImpl::visitXor</a>.</p>

</div>
</div>

### canonicalizeLogicFirst() {#a7b8ca6f7206a11fd57d6e194b2523ffe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * canonicalizeLogicFirst (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I, InstCombiner::BuilderTy &amp; Builder)</td>
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



<p>Definition at line 2168 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a83c7c9008ba213687483b60a658b4a13">llvm::APInt::countr_zero</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aba5d97f3a14427982c1b86dafd033320">llvm::IRBuilderBase::CreateBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#ac80f39cdc458ec63d7ff5f7490498230">llvm::BinaryOperator::CreateWithCopiedFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a062ccd76a126632721e9aa09775d6c0e">llvm::PatternMatch::m_Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5be13f3abb6bddf7ad9747b077da5a0e">llvm::PatternMatch::m_OneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaf7b6cd7c3ceb4af17b610cba09648c9">llvm::InstCombinerImpl::visitXor</a>.</p>

</div>
</div>

### conjugateICmpMask() {#a09c36c07a47775cef8f8e93d8090d919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned conjugateICmpMask (unsigned Mask)</td>
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

<p>Convert an analysis of a masked ICmp into its equivalent if all boolean operations had the opposite sense.</p>


<p>Since each "NotXXX" flag (recording !=) is adjacent to the corresponding normal flag (recording ==), this just involves swapping those bits over.</p>


<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a7cc1609a568ad3b240cf86126370e24f">AMask_AllOnes</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1ada8a0932439ca5f15218c4d7cd43d895">AMask_Mixed</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a54ee032f1a4a27e3066fbb88346cd49a">AMask_NotAllOnes</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a1ee37b18b82ef426e90d86a093d45334">AMask_NotMixed</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a4357ae5a8ec7cec4162a1f25c69558ff">BMask_AllOnes</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a3f5a9337c05ff64ea433ed2d4e9d49d5">BMask_Mixed</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a2b00a345b6b0214f7aa5cbe8203aeb3e">BMask_NotAllOnes</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a10e63e798489e9c5ad2dc2c5ed98ac10">BMask_NotMixed</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a37651a7acaf5871fb8a4d593749c06f4">Mask_AllZeros</a> and <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1ac7606c30ddb7a593051b6e5ad209f30c">Mask_NotAllZeros</a>.</p>


<p>Referenced by <a href="#a0e3285faf503c1c0ab9615ef71bc7d96">foldLogOpOfMaskedICmps</a> and <a href="#a2e02c18bf8cc049ce1589b8f95618a0b">foldLogOpOfMaskedICmpsAsymmetric</a>.</p>

</div>
</div>

### decomposeBitTestICmp() {#a69e1f8a031335ca798357c796ae7d061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool decomposeBitTestICmp (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> &amp; Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; X, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; Y, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; Z)</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52f6d6c3935516609ab7780082b27c86">llvm::decomposeBitTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### extractIntPart() {#a940bbfdea38f2643d0b63c2cc5af4a82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * extractIntPart (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/intpart">IntPart</a> &amp; P, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder)</td>
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

<p>Materialize an extraction of bits from an integer in IR.</p>

<p>Definition at line 1171 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a83725435ece9bc12c40ceb34dbd1727c">llvm::Type::getWithNewBitWidth</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### foldAndOrOfICmpEqConstantAndICmp() {#a45ec897890074179e7de73b934798976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * foldAndOrOfICmpEqConstantAndICmp (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * RHS, bool IsAnd, bool IsLogical, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder)</td>
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



<p>Definition at line 3263 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a563ec77bbc82ad22aab9621dd14c01cd">llvm::IRBuilderBase::CreateFreeze</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae0bd6c2fab2d18443038a8f3a2b64856">llvm::IRBuilderBase::CreateICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a92c83e803f2cf22906da0aaec44ff6d7">llvm::IRBuilderBase::CreateSub</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a34ee40bb2f4f5ece47ef19e5f1f57e3c">llvm::Type::isIntOrIntVectorTy</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a062ccd76a126632721e9aa09775d6c0e">llvm::PatternMatch::m_Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a59cab71d904ae725a5ef54bbf5490017">llvm::PatternMatch::m_APIntAllowPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3130e111d7afd5403267594141df2a46">llvm::PatternMatch::m_SpecificIntAllowPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### foldAndOrOfICmpsWithConstEq() {#afce22397c3eff1d8c0dc8e3d8c464829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * foldAndOrOfICmpsWithConstEq (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Cmp0, <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Cmp1, bool IsAnd, bool IsLogical, InstCombiner::BuilderTy &amp; Builder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q)</td>
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

<p>Reduce logic-of-compares with equality to a constant by substituting a common operand with the constant.</p>


<p>Callers are expected to call this with Cmp0/Cmp1 switched to handle logic op commutativity.</p>


<p>Definition at line 1270 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aba5d97f3a14427982c1b86dafd033320">llvm::IRBuilderBase::CreateBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae0bd6c2fab2d18443038a8f3a2b64856">llvm::IRBuilderBase::CreateICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#abb42f81be3350e8f94849e8e6aceabab">llvm::IRBuilderBase::CreateLogicalAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae1db5150fc798ca464de8923ba0b8e7f">llvm::IRBuilderBase::CreateLogicalOr</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab8a7ef433279aabf7f30fa5504a4d4ef">llvm::isGuaranteedNotToBeUndefOrPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a327f8dad1ecd68d640256e844d49f9ba">llvm::PatternMatch::m_c_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a16be5fe0cce90e51f8c0e0c4d6c589f6">llvm::PatternMatch::m_Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab86c85b47e09489dcda68fd91d082d77">llvm::PatternMatch::m_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83813cbf71633220ae57ad2b79498f77">llvm::simplifyICmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### foldAndOrOfICmpsWithPow2AndWithZero() {#ae1497784bc56d64f953026632a186005}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * foldAndOrOfICmpsWithPow2AndWithZero (InstCombiner::BuilderTy &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * RHS, bool IsAnd, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q)</td>
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



<p>Definition at line 771 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a928ce56952772d0e0f43cab3a489a6fe">llvm::SimplifyQuery::AC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eac33315685a0cba3ce53be378b3c7874b">llvm::And</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae0bd6c2fab2d18443038a8f3a2b64856">llvm::IRBuilderBase::CreateICmp</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a30647c42c8c40890c577ba5b4ab16468">llvm::SimplifyQuery::CxtI</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a0ffb6d79f6befe2030328bd1d7110feb">llvm::SimplifyQuery::DL</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a4776fa0f5a726bd5a8a444981c283c69">llvm::SimplifyQuery::DT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4036c3c75bcee1206cd199548b87f9ae">llvm::isKnownToBeAPowerOfTwo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a327f8dad1ecd68d640256e844d49f9ba">llvm::PatternMatch::m_c_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab86c85b47e09489dcda68fd91d082d77">llvm::PatternMatch::m_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3b3d2d8c64a7881acb82bc7467569aa9">llvm::PatternMatch::m_One</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5be13f3abb6bddf7ad9747b077da5a0e">llvm::PatternMatch::m_OneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### foldAndToXor() {#a385c1da88456d434ee18caa8f48018c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * foldAndToXor (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I, InstCombiner::BuilderTy &amp; Builder)</td>
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



<p>Definition at line 1882 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8578626ceb87974ed94fd56b56a37346">llvm::BinaryOperator::CreateNot</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#add2225af2af25968f26ed4cb0db94dbe">llvm::IRBuilderBase::CreateXor</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0698afabe907d2d3b87889d2e0349d47">llvm::PatternMatch::m_BinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1981217907f3dfb1d21e902d0396fb4d">llvm::PatternMatch::m_c_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae80cbfea2025ff7bd0770f30be6e050a">llvm::PatternMatch::m_c_Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a53fc7d443cf6412add6dfddd11652e5d">llvm::PatternMatch::m_Deferred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae44af1eeb2e5f7a1973a4ab78963a503">llvm::PatternMatch::m_Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>.</p>

</div>
</div>

### foldBitwiseLogicWithIntrinsics() {#ae3ba7f841807b297e7c28874c285f538}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * foldBitwiseLogicWithIntrinsics (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I, InstCombiner::BuilderTy &amp; Builder)</td>
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



<p>Definition at line 2256 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ace0bd40e4bee1851ebebb276178d65fc">llvm::APInt::byteSwap</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#aa04721251be00370fbde6d21f47fed1a">llvm::CallInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aba5d97f3a14427982c1b86dafd033320">llvm::IRBuilderBase::CreateBinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a7b8b4253b618610eb5cb497b4104ebc3">llvm::APInt::reverseBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaf7b6cd7c3ceb4af17b610cba09648c9">llvm::InstCombinerImpl::visitXor</a>.</p>

</div>
</div>

### foldComplexAndOrPatterns() {#ab01a210491dcbefc8db253f4dbaa6497}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * foldComplexAndOrPatterns (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I, InstCombiner::BuilderTy &amp; Builder)</td>
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

<p>Try folding relatively complex patterns for both And and Or operations with all And and Or swapped.</p>

<p>Definition at line 1992 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8f385eda0f71b4e8199b296fbc8e0da9">llvm::BinaryOperator::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aba5d97f3a14427982c1b86dafd033320">llvm::IRBuilderBase::CreateBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8578626ceb87974ed94fd56b56a37346">llvm::BinaryOperator::CreateNot</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a89f675aadae7232445c74ee4167ff591">llvm::IRBuilderBase::CreateNot</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#add2225af2af25968f26ed4cb0db94dbe">llvm::IRBuilderBase::CreateXor</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0698afabe907d2d3b87889d2e0349d47">llvm::PatternMatch::m_BinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab3021d22d00a294cb59bd5067bc5c4b2">llvm::PatternMatch::m_c_BinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a4e2ffa92003f2eca82197ea662b30f16">llvm::PatternMatch::m_c_Xor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a469c3ed35e782000933c996ccd2d2333">llvm::PatternMatch::m_CombineAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5be13f3abb6bddf7ad9747b077da5a0e">llvm::PatternMatch::m_OneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea76feb79109026728a20736a8c6504548">llvm::Xor</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>.</p>

</div>
</div>

### foldIsPowerOf2() {#a22b32bcfbb9aec8a8fcb9826f40a3955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * foldIsPowerOf2 (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Cmp0, <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Cmp1, bool JoinedByAnd, InstCombiner::BuilderTy &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl">InstCombinerImpl</a> &amp; IC)</td>
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

<p>Reduce a pair of compares that check if a value has exactly 1 bit set.</p>


<p>Also used for logical and/or, must be poison safe if range attributes are dropped.</p>


<p>Definition at line 967 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#ab86d58ae73173328360a32cbbb0d5b14">llvm::InstCombiner::addToWorklist</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8c75539a39f167f352b37ccdd788a7e4">llvm::IRBuilderBase::CreateICmpEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">llvm::CmpInst::getPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a6924ab881778c340b66e1e693154b1a8">llvm::PatternMatch::m_SpecificICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2471be3f1b50002f54bf45c590d8d41b">llvm::PatternMatch::m_SpecificInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a54d7212b9b2c57cced42037ae2fa7c61">llvm::PatternMatch::m_ZeroInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### foldIsPowerOf2OrZero() {#a034d63ecfce76136f23c28e698d7a720}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * foldIsPowerOf2OrZero (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Cmp0, <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Cmp1, bool IsAnd, InstCombiner::BuilderTy &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl">InstCombinerImpl</a> &amp; IC)</td>
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

<p>Fold (icmp eq ctpop(X) 1) | (icmp eq X 0) into (icmp ult ctpop(X) 2) and fold (icmp ne ctpop(X) 1) &amp; (icmp ne X 0) into (icmp ugt ctpop(X) 1).</p>


<p>Also used for logical and/or, must be poison safe if range attributes are dropped.</p>


<p>Definition at line 937 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#ab86d58ae73173328360a32cbbb0d5b14">llvm::InstCombiner::addToWorklist</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9aae53e43824240b104278fb6099ce12">llvm::IRBuilderBase::CreateICmpUGT</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a09b4daefdf5b73efba51ce7ae6cd45c5">llvm::IRBuilderBase::CreateICmpULT</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab86c85b47e09489dcda68fd91d082d77">llvm::PatternMatch::m_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2471be3f1b50002f54bf45c590d8d41b">llvm::PatternMatch::m_SpecificInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a54d7212b9b2c57cced42037ae2fa7c61">llvm::PatternMatch::m_ZeroInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### foldLogicCastConstant() {#a45705c727d8388c014471504b4ab0c4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * foldLogicCastConstant (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; Logic, <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> * Cast, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl">InstCombinerImpl</a> &amp; IC)</td>
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

<p>Fold {and,or,xor} (cast X), C.</p>

<p>Definition at line 1750 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#ae1d331bc844ecb92bdeb0b706ae04396">llvm::InstCombiner::Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aba5d97f3a14427982c1b86dafd033320">llvm::IRBuilderBase::CreateBinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaac3b18b5ff803a9ec320ae285be4122">llvm::InstCombinerImpl::getLosslessSignedTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a60fa7efbdcebf8c25c1dc58cc300a923">llvm::InstCombinerImpl::getLosslessUnsignedTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a31bf07f3f61525486633bc1d0bbaf029">llvm::BinaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a01cc70c1e8052996fb44f59fa63a015c">llvm::CastInst::getSrcTy</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5be13f3abb6bddf7ad9747b077da5a0e">llvm::PatternMatch::m_OneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a9ffe83e2db4b833b819ee721595c04dc">llvm::PatternMatch::m_SExtLike</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a6ba4022cd30993a84d111871dd0f6ba6">llvm::PatternMatch::m_ZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### foldLogOpOfMaskedICmps() {#a0e3285faf503c1c0ab9615ef71bc7d96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * foldLogOpOfMaskedICmps (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, bool IsAnd, bool IsLogical, InstCombiner::BuilderTy &amp; Builder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q)</td>
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

<p>Try to fold (icmp(A &amp; B) ==/!= C) &amp;/| (icmp(A &amp; D) ==/!= E) into a single (icmp(A &amp; X) ==/!= Y).</p>

<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a7cc1609a568ad3b240cf86126370e24f">AMask_AllOnes</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a54ee032f1a4a27e3066fbb88346cd49a">AMask_NotAllOnes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a4357ae5a8ec7cec4162a1f25c69558ff">BMask_AllOnes</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a3f5a9337c05ff64ea433ed2d4e9d49d5">BMask_Mixed</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a2b00a345b6b0214f7aa5cbe8203aeb3e">BMask_NotAllOnes</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a10e63e798489e9c5ad2dc2c5ed98ac10">BMask_NotMixed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#a09c36c07a47775cef8f8e93d8090d919">conjugateICmpMask</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a563ec77bbc82ad22aab9621dd14c01cd">llvm::IRBuilderBase::CreateFreeze</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae0bd6c2fab2d18443038a8f3a2b64856">llvm::IRBuilderBase::CreateICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a2e02c18bf8cc049ce1589b8f95618a0b">foldLogOpOfMaskedICmpsAsymmetric</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa2a54b545d237ecfe450fd1292f7675e">llvm::CmpInst::getInversePredicate</a>, <a href="#aeee622fb99bdc4c058a9ef179d0a0d09">getMaskedTypeForICmpPair</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#abe8988eef2e6fc2baba032cb22afedd7">llvm::ICmpInst::isEquality</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab8a7ef433279aabf7f30fa5504a4d4ef">llvm::isGuaranteedNotToBeUndefOrPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4036c3c75bcee1206cd199548b87f9ae">llvm::isKnownToBeAPowerOfTwo</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acfae9bdee6027ffa8ffe244cc22e3a76">llvm::APInt::isSubsetOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a37651a7acaf5871fb8a4d593749c06f4">Mask_AllZeros</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1ac7606c30ddb7a593051b6e5ad209f30c">Mask_NotAllZeros</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a205029ee514828d0fb4988399ef3ece4a6864311f985d160ad4bd46a9fbe4a4d4">llvm::Masked</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### foldLogOpOfMaskedICmps\_NotAllZeros\_BMask\_Mixed() {#a7134dae528abf2cf2ef1bd1d92f9ce39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * foldLogOpOfMaskedICmps_NotAllZeros_BMask_Mixed (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, bool IsAnd, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * A, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * B, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * D, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * E, ICmpInst::Predicate PredL, ICmpInst::Predicate PredR, InstCombiner::BuilderTy &amp; Builder)</td>
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

<p>Try to fold (icmp(A &amp; B) ==/!= C) &amp;/| (icmp(A &amp; D) ==/!= E) into a single (icmp(A &amp; X) ==/!= Y), where the left-hand side is of type Mask_NotAllZeros and the right hand side is of type BMask_Mixed.</p>


<p>For example, (icmp (A &amp; 12) != 0) &amp; (icmp (A &amp; 15) == 8) -&gt; (icmp (A &amp; 15) == 8). Also used for logical and/or, must be poison safe.</p>


<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af883359d8cdce0f853270b28d7bfc564">llvm::APInt::clearSignBit</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a168f682d44a3697eba421b802787f6bf">llvm::IRBuilderBase::CreateFCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae0bd6c2fab2d18443038a8f3a2b64856">llvm::IRBuilderBase::CreateICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa3213b645e029aba8bb1b85213607d5e">llvm::CmpInst::FCMP_ORD</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baf0159e4005258dc54f20b6fc227d19ed">llvm::CmpInst::FCMP_UNO</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ab35b08ed1345493af2c69fbb71e4d0c3">llvm::APFloat::getInf</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a60a6d6c205f483fa96597a960f3c093b">llvm::IRBuilderBase::GetInsertBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a1b4bf7c97cdc8159fd73d48063f0b250">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a75071440d60c24178371ca1299f4ef07">llvm::ConstantFP::getZero</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a6da514c588b2668280a861a59bfc9fa5">llvm::APInt::intersects</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aed04b081c4501c07d80fc69c308a0c23">llvm::PatternMatch::m_ElementWiseBitCast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#a2e02c18bf8cc049ce1589b8f95618a0b">foldLogOpOfMaskedICmpsAsymmetric</a>.</p>

</div>
</div>

### foldLogOpOfMaskedICmpsAsymmetric() {#a2e02c18bf8cc049ce1589b8f95618a0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * foldLogOpOfMaskedICmpsAsymmetric (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, bool IsAnd, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * A, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * B, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * C, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * D, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * E, ICmpInst::Predicate PredL, ICmpInst::Predicate PredR, unsigned LHSMask, unsigned RHSMask, InstCombiner::BuilderTy &amp; Builder)</td>
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

<p>Try to fold (icmp(A &amp; B) ==/!= 0) &amp;/| (icmp(A &amp; D) ==/!= E) into a single (icmp(A &amp; X) ==/!= Y), where the left-hand side and the right hand side aren't of the common mask pattern type.</p>


<p>Also used for logical and/or, must be poison safe.</p>


<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a3f5a9337c05ff64ea433ed2d4e9d49d5">BMask_Mixed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a09c36c07a47775cef8f8e93d8090d919">conjugateICmpMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a7134dae528abf2cf2ef1bd1d92f9ce39">foldLogOpOfMaskedICmps_NotAllZeros_BMask_Mixed</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#abe8988eef2e6fc2baba032cb22afedd7">llvm::ICmpInst::isEquality</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1ac7606c30ddb7a593051b6e5ad209f30c">Mask_NotAllZeros</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#a0e3285faf503c1c0ab9615ef71bc7d96">foldLogOpOfMaskedICmps</a>.</p>

</div>
</div>

### foldNegativePower2AndShiftedMask() {#a5532e05d5caa4fb5e2b8512aa3095f1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * foldNegativePower2AndShiftedMask (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * A, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * B, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * D, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * E, ICmpInst::Predicate PredL, ICmpInst::Predicate PredR, InstCombiner::BuilderTy &amp; Builder)</td>
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

<p>Try to fold (icmp(A &amp; B) == 0) &amp; (icmp(A &amp; D) != E) into (icmp A u&lt; D) iff B is a contiguous set of ones starting from the most significant bit (negative power of 2), D and E are equal, and D is a contiguous set of ones starting at the most significant zero bit in B.</p>


<p>Parameter B supports masking using undef/poison in either scalar or vector values.</p>


<p>Definition at line 1009 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3a2a335dd528474e41dcf609f79b0be2">llvm::APInt::countLeadingOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aa074b9f5a1efaa0fd8aa4522593f299a">llvm::APInt::countLeadingZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae0bd6c2fab2d18443038a8f3a2b64856">llvm::IRBuilderBase::CreateICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#abe8988eef2e6fc2baba032cb22afedd7">llvm::ICmpInst::isEquality</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a59cab71d904ae725a5ef54bbf5490017">llvm::PatternMatch::m_APIntAllowPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a832c789367b871a48dede765ac92ea5e">llvm::PatternMatch::m_NegatedPower2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a28286b39ef036b41eb449f209e745920">llvm::PatternMatch::m_ShiftedMask</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="#a609a05f40709dea74bb5cd248c5816fd">foldPowerOf2AndShiftedMask</a>.</p>

</div>
</div>

### foldNotXor() {#a0e07326546257c169a5aff0d8b822a00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * foldNotXor (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I, InstCombiner::BuilderTy &amp; Builder)</td>
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



<p>Definition at line 4303 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a89f675aadae7232445c74ee4167ff591">llvm::IRBuilderBase::CreateNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a014d851989a66ce781c4f89dfffb26b5">llvm::PatternMatch::m_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5be13f3abb6bddf7ad9747b077da5a0e">llvm::PatternMatch::m_OneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae44af1eeb2e5f7a1973a4ab78963a503">llvm::PatternMatch::m_Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1cacb72e897c55bdfd5c726d13d69af1">llvm::PatternMatch::m_Xor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### foldOrOfInversions() {#abcce404670629549d0278e1641807377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * foldOrOfInversions (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I, InstCombiner::BuilderTy &amp; Builder)</td>
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



<p>Definition at line 3532 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#add2225af2af25968f26ed4cb0db94dbe">llvm::IRBuilderBase::CreateXor</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9298a379e311818b5244bcb6b386953b">llvm::isKnownInversion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a014d851989a66ce781c4f89dfffb26b5">llvm::PatternMatch::m_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>.</p>

</div>
</div>

### foldOrToXor() {#a26257c73e483eab4b0e15d53340de986}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * foldOrToXor (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I, InstCombiner::BuilderTy &amp; Builder)</td>
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



<p>Definition at line 1908 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8578626ceb87974ed94fd56b56a37346">llvm::BinaryOperator::CreateNot</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#add2225af2af25968f26ed4cb0db94dbe">llvm::IRBuilderBase::CreateXor</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a014d851989a66ce781c4f89dfffb26b5">llvm::PatternMatch::m_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1981217907f3dfb1d21e902d0396fb4d">llvm::PatternMatch::m_c_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae80cbfea2025ff7bd0770f30be6e050a">llvm::PatternMatch::m_c_Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1cacb72e897c55bdfd5c726d13d69af1">llvm::PatternMatch::m_Xor</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>.</p>

</div>
</div>

### foldPowerOf2AndShiftedMask() {#a609a05f40709dea74bb5cd248c5816fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * foldPowerOf2AndShiftedMask (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Cmp0, <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Cmp1, bool JoinedByAnd, InstCombiner::BuilderTy &amp; Builder)</td>
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

<p>Try to fold ((icmp X u&lt; P) &amp; (icmp(X &amp; M) != M)) or ((icmp X s&gt; -1) &amp; (icmp(X &amp; M) != M)) into (icmp X u&lt; M).</p>


<p>Where P is a power of 2, M &lt; P, and M is a contiguous shifted mask starting at the right most significant zero bit in P. SGT is supported as when P is the largest representable power of 2, an earlier optimization converts the expression into (icmp X s&gt; -1). Parameter P supports masking using undef/poison in either scalar or vector values.</p>


<p>Definition at line 1075 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a2b00a345b6b0214f7aa5cbe8203aeb3e">BMask_NotAllOnes</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a10e63e798489e9c5ad2dc2c5ed98ac10">BMask_NotMixed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a5532e05d5caa4fb5e2b8512aa3095f1e">foldNegativePower2AndShiftedMask</a>, <a href="#aeee622fb99bdc4c058a9ef179d0a0d09">getMaskedTypeForICmpPair</a> and <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a37651a7acaf5871fb8a4d593749c06f4">Mask_AllZeros</a>.</p>

</div>
</div>

### foldSignedTruncationCheck() {#a1f569ebf4402ad560d7c147f688ac05a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * foldSignedTruncationCheck (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * ICmp0, <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * ICmp1, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; CxtI, InstCombiner::BuilderTy &amp; Builder)</td>
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

<p>General pattern: X &amp; Y.</p>


<p>Where Y is checking that all the high bits (covered by a mask 4294967168) are uniform, i.e. arg &amp; 4294967168 can be either 4294967168 or 0 <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a> can be one of: t = add i32 arg, 128 r = icmp ult i32 t, 256 Or t0 = shl i32 arg, 24 t1 = ashr i32 t0, 24 r = icmp eq i32 t1, arg Or t0 = trunc i32 arg to i8 t1 = sext i8 t0 to i32 r = icmp eq i32 t1, arg This pattern is a signed truncation check.</p>


<p>And X is checking that some bit in that same mask is zero. I.e. can be one of: r = icmp sgt i32 arg, -1 Or t = and i32 arg, 2147483648 r = icmp eq i32 t, 0</p>


<p>Since we are checking that all the bits in that mask are the same, and a particular bit is zero, what we are really checking is that all the masked bits are zero. So this should be transformed to: r = icmp ult i32 arg, 128</p>


<p>Definition at line 835 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a09b4daefdf5b73efba51ce7ae6cd45c5">llvm::IRBuilderBase::CreateICmpULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaf52bffe6dc4a6d5d5cf515aac2e4450">llvm::decomposeBitTestICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">llvm::CmpInst::getPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a6da514c588b2668280a861a59bfc9fa5">llvm::APInt::intersects</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad1b0513de876d1c85cf6268ca21b2c86">llvm::APInt::isPowerOf2</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acfae9bdee6027ffa8ffe244cc22e3a76">llvm::APInt::isSubsetOf</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a062ccd76a126632721e9aa09775d6c0e">llvm::PatternMatch::m_Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a014d851989a66ce781c4f89dfffb26b5">llvm::PatternMatch::m_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab86c85b47e09489dcda68fd91d082d77">llvm::PatternMatch::m_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a103f4e50bfeab3d598adc56e1235c241">llvm::PatternMatch::m_Power2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a6924ab881778c340b66e1e693154b1a8">llvm::PatternMatch::m_SpecificICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1b8442c10c9ed6e0e07160b54541450e">llvm::PatternMatch::m_Trunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acb9c55b6986369948507ca5241b4e411">llvm::APInt::shl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a954b694b93f10aba174cb5d0378975b2">llvm::APIntOps::umin</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>.</p>

</div>
</div>

### foldUnsignedUnderflowCheck() {#a24dce8fa354f0f1d52209e805f0ae6a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * foldUnsignedUnderflowCheck (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * ZeroICmp, <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * UnsignedICmp, bool IsAnd, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q, InstCombiner::BuilderTy &amp; Builder)</td>
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

<p>Commuted variants are assumed to be handled by calling this function again with the parameters swapped.</p>

<p>Definition at line 1107 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac613fa8e66fca464885c3f274fbeb834">llvm::IRBuilderBase::CreateICmpUGE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a09b4daefdf5b73efba51ce7ae6cd45c5">llvm::IRBuilderBase::CreateICmpULT</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a7704bf68951054ffeb3efe605750e2d9">llvm::IRBuilderBase::CreateNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#abe8988eef2e6fc2baba032cb22afedd7">llvm::ICmpInst::isEquality</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9893e3e4b14f8fa15d7c3c25a6a0b6f6">llvm::isKnownNonZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a9167d23c7fc4727aef51733d009e3f45">llvm::PatternMatch::m_c_Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a327f8dad1ecd68d640256e844d49f9ba">llvm::PatternMatch::m_c_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab86c85b47e09489dcda68fd91d082d77">llvm::PatternMatch::m_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### foldXorToXor() {#a3b3df3036740dfcdeb37c3ad977b039a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * foldXorToXor (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I, InstCombiner::BuilderTy &amp; Builder)</td>
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

<p>A ^ B can be specified using other logic ops in a variety of patterns.</p>


<p>We can fold these early and efficiently by morphing an existing instruction.</p>


<p>Definition at line 4082 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8578626ceb87974ed94fd56b56a37346">llvm::BinaryOperator::CreateNot</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#add2225af2af25968f26ed4cb0db94dbe">llvm::IRBuilderBase::CreateXor</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a014d851989a66ce781c4f89dfffb26b5">llvm::PatternMatch::m_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1981217907f3dfb1d21e902d0396fb4d">llvm::PatternMatch::m_c_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae80cbfea2025ff7bd0770f30be6e050a">llvm::PatternMatch::m_c_Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a4e2ffa92003f2eca82197ea662b30f16">llvm::PatternMatch::m_c_Xor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a53fc7d443cf6412add6dfddd11652e5d">llvm::PatternMatch::m_Deferred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae44af1eeb2e5f7a1973a4ab78963a503">llvm::PatternMatch::m_Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1cacb72e897c55bdfd5c726d13d69af1">llvm::PatternMatch::m_Xor</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaf7b6cd7c3ceb4af17b610cba09648c9">llvm::InstCombinerImpl::visitXor</a>.</p>

</div>
</div>

### freelyInvert() {#a6bf246a84f7e8596777a0231fa7d7bc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * freelyInvert (<a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl">InstCombinerImpl</a> &amp; IC, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IgnoredUser)</td>
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



<p>Definition at line 4376 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#ae1d331bc844ecb92bdeb0b706ae04396">llvm::InstCombiner::Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a89f675aadae7232445c74ee4167ff591">llvm::IRBuilderBase::CreateNot</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af8c1d39848b445bea8e307b53f81c481">llvm::InstCombinerImpl::freelyInvertAllUsersOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4e2dd07eceeed7496e6c3df4d364c91e">llvm::InstCombinerImpl::sinkNotIntoLogicalOp</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8d44c548f74b3d233a248672402b5dd1">llvm::InstCombinerImpl::sinkNotIntoOtherHandOfLogicalOp</a>.</p>

</div>
</div>

### getFCmpValue() {#a0f470beafc2cabc85d7e9fd044c77977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * getFCmpValue (unsigned Code, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, InstCombiner::BuilderTy &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/fmfsource">FMFSource</a> FMF)</td>
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

<p>This is the complement of getFCmpCode, which turns an opcode and two operands into either a FCmp instruction, or a true/false constant.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73a6bde6b865b34ec45b7bcd8e7cb4b8">llvm::IRBuilderBase::CreateFCmpFMF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a071d237c0318d336cc84124ec3a8d037">llvm::getPredForFCmpCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### getMaskedICmpType() {#a39257c6c73db3440e6d05b9eec5999a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getMaskedICmpType (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * A, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * B, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * C, ICmpInst::Predicate Pred)</td>
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

<p>Return the set of patterns (from <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1">MaskedICmpType</a>) that (icmp SCC (A &amp; B), C) satisfies.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a7cc1609a568ad3b240cf86126370e24f">AMask_AllOnes</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1ada8a0932439ca5f15218c4d7cd43d895">AMask_Mixed</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a54ee032f1a4a27e3066fbb88346cd49a">AMask_NotAllOnes</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a1ee37b18b82ef426e90d86a093d45334">AMask_NotMixed</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a4357ae5a8ec7cec4162a1f25c69558ff">BMask_AllOnes</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a3f5a9337c05ff64ea433ed2d4e9d49d5">BMask_Mixed</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a2b00a345b6b0214f7aa5cbe8203aeb3e">BMask_NotAllOnes</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a10e63e798489e9c5ad2dc2c5ed98ac10">BMask_NotMixed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad1b0513de876d1c85cf6268ca21b2c86">llvm::APInt::isPowerOf2</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acfae9bdee6027ffa8ffe244cc22e3a76">llvm::APInt::isSubsetOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1a37651a7acaf5871fb8a4d593749c06f4">Mask_AllZeros</a>, <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1ac7606c30ddb7a593051b6e5ad209f30c">Mask_NotAllZeros</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="#aeee622fb99bdc4c058a9ef179d0a0d09">getMaskedTypeForICmpPair</a>.</p>

</div>
</div>

### getMaskedTypeForICmpPair() {#aeee622fb99bdc4c058a9ef179d0a0d09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::pair&lt; unsigned, unsigned &gt; &gt; getMaskedTypeForICmpPair (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; A, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; B, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; C, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; D, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; E, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, ICmpInst::Predicate &amp; PredL, ICmpInst::Predicate &amp; PredR)</td>
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

<p>Handle (icmp(A &amp; B) ==/!= C) &amp;/| (icmp(A &amp; D) ==/!= E).</p>


<p>Return the pattern classes (from <a href="#aa9c705ecec80ebd584bb3d54b48f7ee1">MaskedICmpType</a>) for the left hand side and the right hand side as a pair. LHS and RHS are the left hand side and the right hand side ICmps and PredL and PredR are their predicates, respectively.</p>


<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaf52bffe6dc4a6d5d5cf515aac2e4450">llvm::decomposeBitTestICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="#a39257c6c73db3440e6d05b9eec5999a0">getMaskedICmpType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#abe8988eef2e6fc2baba032cb22afedd7">llvm::ICmpInst::isEquality</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a00ef056813d120034e387417e9cde341">llvm::PatternMatch::m_AllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a014d851989a66ce781c4f89dfffb26b5">llvm::PatternMatch::m_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h/#a9211f62d8e1e6de999eaa63ec0f6ae02">R2</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#a0e3285faf503c1c0ab9615ef71bc7d96">foldLogOpOfMaskedICmps</a> and <a href="#a609a05f40709dea74bb5cd248c5816fd">foldPowerOf2AndShiftedMask</a>.</p>

</div>
</div>

### getNewICmpValue() {#a89cfa00019cb17baa05532705ea198e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * getNewICmpValue (unsigned Code, bool Sign, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, InstCombiner::BuilderTy &amp; Builder)</td>
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

<p>This is the complement of getICmpCode, which turns an opcode and two operands into either a constant true or false, or a brand new ICmp instruction.</p>


<p>The sign is passed in to determine which kind of predicate to use in the new icmp instruction.</p>


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae0bd6c2fab2d18443038a8f3a2b64856">llvm::IRBuilderBase::CreateICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff210c52130b5778e2ef75dd74778afb">llvm::getPredForICmpCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### matchDeMorgansLaws() {#a2d3ce43f7795a8f4f6925bffbcc90279}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * matchDeMorgansLaws (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/instcombiner">InstCombiner</a> &amp; IC)</td>
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

<p>Match variations of De Morgan's Laws: (~A &amp; ~B) == (~(A | B)) (~A | ~B) == (~(A &amp; B))</p>

<p>Definition at line 1697 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#ae1d331bc844ecb92bdeb0b706ae04396">llvm::InstCombiner::Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8f385eda0f71b4e8199b296fbc8e0da9">llvm::BinaryOperator::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aba5d97f3a14427982c1b86dafd033320">llvm::IRBuilderBase::CreateBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8578626ceb87974ed94fd56b56a37346">llvm::BinaryOperator::CreateNot</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a89f675aadae7232445c74ee4167ff591">llvm::IRBuilderBase::CreateNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#a1f819cdc746560fd28977b1175030cff">llvm::InstCombiner::isFreeToInvert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab3021d22d00a294cb59bd5067bc5c4b2">llvm::PatternMatch::m_c_BinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5be13f3abb6bddf7ad9747b077da5a0e">llvm::PatternMatch::m_OneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>.</p>

</div>
</div>

### matchFunnelShift() {#ac800cc10159d350923dc27446b9123f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * matchFunnelShift (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Or, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl">InstCombinerImpl</a> &amp; IC)</td>
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

<p>Match UB-safe variants of the funnel shift intrinsic.</p>

<p>Definition at line 3060 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a52d249cc9856fb556e92d5a1b03e5e80">llvm::InstCombinerImpl::convertOrOfShiftsToFunnelShift</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#aa04721251be00370fbde6d21f47fed1a">llvm::CallInst::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a73b18943dffc9db671d3217c90b15a4f">foldGuardedFunnelShift</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>.</p>

</div>
</div>

### matchIntPart() {#a7662d7ee7f100c9455f4a2c7e4992929}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; IntPart &gt; matchIntPart (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Match an extraction of bits from an integer.</p>

<p>Definition at line 1153 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab8546ee1aaa68d6f4990e6241e24464c">llvm::PatternMatch::m_LShr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5be13f3abb6bddf7ad9747b077da5a0e">llvm::PatternMatch::m_OneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1b8442c10c9ed6e0e07160b54541450e">llvm::PatternMatch::m_Trunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aca14d9ec64ba4ab7fb2cef37c57d9ce4">llvm::APInt::ule</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### matchIsFiniteTest() {#a5946d75decfd106d2b75af6d59009f34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * matchIsFiniteTest (InstCombiner::BuilderTy &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/fcmpinst">FCmpInst</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/fcmpinst">FCmpInst</a> * RHS)</td>
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

<p>and (fcmp ord x, 0), (fcmp u* x, inf) -&gt; fcmp o* x, inf</p>


<p>Clang emits this pattern for doing an isfinite check in __builtin_isnormal.</p>


<p>Definition at line 1408 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73a6bde6b865b34ec45b7bcd8e7cb4b8">llvm::IRBuilderBase::CreateFCmpFMF</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#ab95f6ee8398d4632b27c25783f3339ec">llvm::CmpInst::getOrderedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/fmfsource/#af63b286b1615a2c0712b4bc0190ab999">llvm::FMFSource::intersect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="#a9e92e028c2dd81bf7d518dfc3960624a">matchIsNotNaN</a>, <a href="#a9977c80be67ea7e51bb37ee242d1cc4c">matchUnorderedInfCompare</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### matchIsFPClassLikeFCmp() {#a151e95d3f063067aa27c74930296a25e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool matchIsFPClassLikeFCmp (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; ClassVal, uint64_t &amp; ClassMask)</td>
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

<p>Match an fcmp against a special value that performs a test possible by llvm.is.fpclass.</p>

<p>Definition at line 1554 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9ef7edd1261f6570677d850b5cf2cfc">llvm::fcmpToClassTest</a>.</p>

</div>
</div>

### matchIsNotNaN() {#a9e92e028c2dd81bf7d518dfc3960624a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool matchIsNotNaN (FCmpInst::Predicate P, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS)</td>
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

<p>Matches canonical form of isnan, fcmp ord x, 0.</p>

<p>Definition at line 1395 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa3213b645e029aba8bb1b85213607d5e">llvm::CmpInst::FCMP_ORD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2c7e2b8240233bff5e5f1b38465420c1">llvm::PatternMatch::m_AnyZeroFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#a5946d75decfd106d2b75af6d59009f34">matchIsFiniteTest</a>.</p>

</div>
</div>

### matchOrConcat() {#a9e6840885acb4ffa3e94e81a70b392fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * matchOrConcat (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Or, InstCombiner::BuilderTy &amp; Builder)</td>
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

<p>Attempt to combine or(zext(x),shl(zext(y),bw/2) concat packing patterns.</p>

<p>Definition at line 3072 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b6a3be6451cf6a789d9305d90751c40">llvm::IRBuilderBase::CreateShl</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0eb993474e9ffa2056f664cdc2e14ad4">llvm::PatternMatch::m_BitReverse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae4e4b162282728d327227c5773592d65">llvm::PatternMatch::m_BSwap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5be13f3abb6bddf7ad9747b077da5a0e">llvm::PatternMatch::m_OneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ac1c7b78fe67245930be18441b77de500">llvm::PatternMatch::m_Shl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a6ba4022cd30993a84d111871dd0f6ba6">llvm::PatternMatch::m_ZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>.</p>

</div>
</div>

### matchUnorderedInfCompare() {#a9977c80be67ea7e51bb37ee242d1cc4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool matchUnorderedInfCompare (FCmpInst::Predicate P, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS)</td>
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

<p>Matches fcmp u__ x, +/-inf.</p>

<p>Definition at line 1400 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aae55ea42185b7528c0c149625b998968">llvm::CmpInst::isUnordered</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0d5f2a537875b12c29e04431fa4ac5bf">llvm::PatternMatch::m_Inf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#a5946d75decfd106d2b75af6d59009f34">matchIsFiniteTest</a>.</p>

</div>
</div>

### reassociateFCmps() {#a8208d3cd3c60073f5c9ceefec06ab2e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * reassociateFCmps (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; BO, InstCombiner::BuilderTy &amp; Builder)</td>
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

<p>This a limited reassociation for a special case (see above) where we are checking if two values are either both NAN (unordered) or not-NAN (ordered).</p>


<p>This could be handled more generally in '-reassociation', but it seems like an unlikely pattern for a large number of logic ops and fcmps.</p>


<p>Definition at line 1656 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8f385eda0f71b4e8199b296fbc8e0da9">llvm::BinaryOperator::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73a6bde6b865b34ec45b7bcd8e7cb4b8">llvm::IRBuilderBase::CreateFCmpFMF</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa3213b645e029aba8bb1b85213607d5e">llvm::CmpInst::FCMP_ORD</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baf0159e4005258dc54f20b6fc227d19ed">llvm::CmpInst::FCMP_UNO</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a31bf07f3f61525486633bc1d0bbaf029">llvm::BinaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/fmfsource/#af63b286b1615a2c0712b4bc0190ab999">llvm::FMFSource::intersect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2c7e2b8240233bff5e5f1b38465420c1">llvm::PatternMatch::m_AnyZeroFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0698afabe907d2d3b87889d2e0349d47">llvm::PatternMatch::m_BinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a08d5220c6f77428fcfd5bd1de5af2bbc">llvm::PatternMatch::m_FCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a92391061d5ab4f5b5d988aa7044a8260">llvm::PatternMatch::m_SpecificFCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>.</p>

</div>
</div>

### reassociateForUses() {#ac80e92048884e85b87ddd733785e44d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * reassociateForUses (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; BO, InstCombinerImpl::BuilderTy &amp; Builder)</td>
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

<p>Try to reassociate a pair of binops so that values with one use only are part of the same instruction.</p>


<p>This may enable folds that are limited with multi-use restrictions and makes it more likely to match other patterns that are looking for a common operand.</p>


<p>Definition at line 2135 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8f385eda0f71b4e8199b296fbc8e0da9">llvm::BinaryOperator::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aba5d97f3a14427982c1b86dafd033320">llvm::IRBuilderBase::CreateBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a31bf07f3f61525486633bc1d0bbaf029">llvm::BinaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0698afabe907d2d3b87889d2e0349d47">llvm::PatternMatch::m_BinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab3021d22d00a294cb59bd5067bc5c4b2">llvm::PatternMatch::m_c_BinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5be13f3abb6bddf7ad9747b077da5a0e">llvm::PatternMatch::m_OneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaf7b6cd7c3ceb4af17b610cba09648c9">llvm::InstCombinerImpl::visitXor</a>.</p>

</div>
</div>

### simplifyAndOrWithOpReplaced() {#a2a50775521fbb289313bb39964dabae3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * simplifyAndOrWithOpReplaced (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RepOp, bool SimplifyOnly, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl">InstCombinerImpl</a> &amp; IC, unsigned Depth=0)</td>
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



<p>Definition at line 2311 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#ae1d331bc844ecb92bdeb0b706ae04396">llvm::InstCombiner::Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aba5d97f3a14427982c1b86dafd033320">llvm::IRBuilderBase::CreateBinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#af56f7a148b00922368e55ab9c4948724">llvm::InstCombiner::getSimplifyQuery</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a505cdf903e17bf9be677769bf0980adc">llvm::SimplifyQuery::getWithInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a2a50775521fbb289313bb39964dabae3">simplifyAndOrWithOpReplaced</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa750395459fa1eb7130d6de8e3d074f6">llvm::simplifyBinOp</a>.</p>


<p>Referenced by <a href="#a2a50775521fbb289313bb39964dabae3">simplifyAndOrWithOpReplaced</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>.</p>

</div>
</div>

### stripSignOnlyFPOps() {#a67ccec2dd2fc482ea50af1764f1db598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * stripSignOnlyFPOps (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
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

<p>Ignore all operations which only change the sign of a value, returning the underlying magnitude value.</p>

<p>Definition at line 1387 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af128e5952aecdc6f5799a4118c8f58dc">llvm::PatternMatch::m_CopySign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af07397df05f8eb1838b6d79871791e38">llvm::PatternMatch::m_FAbs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aba7473bfa862dd9eadf04a6fefc6aa69">llvm::PatternMatch::m_FNeg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>

</div>
</div>

### visitMaskedMerge() {#a1ff7fad11ba04c97f0a4b679c74cb394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * visitMaskedMerge (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I, InstCombiner::BuilderTy &amp; Builder)</td>
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

<p>If we have a masked merge, in the canonical form of: (assuming that A only has one use.) | A | |B| ((x ^ y) &amp; M) ^ y | D |.</p>


<ul class="doxyList ">
<li>If M is inverted: | D | ((x ^ y) &amp; ~M) ^ y We can canonicalize by swapping the final xor operand to eliminate the 'not' of the mask. ((x ^ y) &amp; M) ^ x</li>
<li>If M is a constant, and D has one use, we transform to 'and' / 'or' ops because that shortens the dependency chain and improves analysis: (x &amp; M) | (y &amp; ~M)</li>
</ul>

<p>Definition at line 4270 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a89f675aadae7232445c74ee4167ff591">llvm::IRBuilderBase::CreateNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1981217907f3dfb1d21e902d0396fb4d">llvm::PatternMatch::m_c_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a4e2ffa92003f2eca82197ea662b30f16">llvm::PatternMatch::m_c_Xor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a469c3ed35e782000933c996ccd2d2333">llvm::PatternMatch::m_CombineAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a16be5fe0cce90e51f8c0e0c4d6c589f6">llvm::PatternMatch::m_Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a53fc7d443cf6412add6dfddd11652e5d">llvm::PatternMatch::m_Deferred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5be13f3abb6bddf7ad9747b077da5a0e">llvm::PatternMatch::m_OneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a174c8fd19771468c53842a7fde8ddce1">llvm::Constant::replaceUndefsWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaf7b6cd7c3ceb4af17b610cba09648c9">llvm::InstCombinerImpl::visitXor</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"instcombine"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp">InstCombineAndOrXor.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
