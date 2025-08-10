---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/ir/constantrange-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `ConstantRange.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">llvm/IR/ConstantRange.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "llvm/Config/llvm-config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">llvm/IR/Operator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">llvm/Support/KnownBits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;optional&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e7e5e776b7f30a4522e2d415efe1dfb">makeExactMulNUWRegion</a> (const APInt &amp;V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Exact mul nuw region for single element RHS. <a href="#a7e7e5e776b7f30a4522e2d415efe1dfb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa69e07fa7ca7953d971574873d5ec5c2">makeExactMulNSWRegion</a> (const APInt &amp;V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Exact mul nsw region for single element RHS. <a href="#aa69e07fa7ca7953d971574873d5ec5c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9d811df7ac170e0bcf950a650479e47">getPreferredRange</a> (const ConstantRange &amp;CR1, const ConstantRange &amp;CR2, ConstantRange::PreferredRangeType Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a437967d8acddbcdb8cb345412f22f9dd">estimateBitMaskedAndLowerBound</a> (const ConstantRange &amp;LHS, const ConstantRange &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Estimate the 'bit-masked AND' operation's lower bound. <a href="#a437967d8acddbcdb8cb345412f22f9dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a618caf6a690e2208acbfa1b7668df3a2">computeShlNUW</a> (const ConstantRange &amp;LHS, const ConstantRange &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a843e5745d85df82681dadbe26ce86ca2">computeShlNSWWithNNegLHS</a> (const APInt &amp;LHSMin, const APInt &amp;LHSMax, unsigned RHSMin, unsigned RHSMax)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4bd08b53da1b6b69766e5abf2462cc0">computeShlNSWWithNegLHS</a> (const APInt &amp;LHSMin, const APInt &amp;LHSMax, unsigned RHSMin, unsigned RHSMax)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a685bd53265606ced2a0cbabcf8dbd54b">computeShlNSW</a> (const ConstantRange &amp;LHS, const ConstantRange &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6e0521392f7c7e8a1daa7511a533201">getUnsignedCountTrailingZerosRange</a> (const APInt &amp;Lower, const APInt &amp;Upper)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a623310118173612285ce605149f43264">getUnsignedPopCountRange</a> (const APInt &amp;Lower, const APInt &amp;Upper)</td>
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

### computeShlNSW() {#a685bd53265606ced2a0cbabcf8dbd54b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange computeShlNSW (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; RHS)</td>
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



<p>Definition at line 1748 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#af4bd08b53da1b6b69766e5abf2462cc0">computeShlNSWWithNegLHS</a>, <a href="#a843e5745d85df82681dadbe26ce86ca2">computeShlNSWWithNNegLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a6804d9caf15411f55e7b9e9f397f0422">llvm::APInt::isNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac8c0157adbe12649beac0009c2f6ad8d">llvm::APInt::isNonNegative</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a0e6f2069000829208cbac185a07d8082a8260f3d302e2463fd93753dfd0de6ec1">llvm::ConstantRange::Signed</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa81521f99442a5c30f9061b8c6ce795e">llvm::ConstantRange::unionWith</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa3896afe885ae893809f7de1b23c8d7b">llvm::ConstantRange::shlWithNoWrap</a>.</p>

</div>
</div>

### computeShlNSWWithNegLHS() {#af4bd08b53da1b6b69766e5abf2462cc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange computeShlNSWWithNegLHS (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; LHSMin, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; LHSMax, unsigned RHSMin, unsigned RHSMax)</td>
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



<p>Definition at line 1729 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3a2a335dd528474e41dcf609f79b0be2">llvm::APInt::countLeadingOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#acd8afecbb15ee69487d5339371f64a76">llvm::ConstantRange::getNonEmpty</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a1e6f0d8dfed0ab631b488a3e6317718e">llvm::APInt::getSignMask</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acb9c55b6986369948507ca5241b4e411">llvm::APInt::shl</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a36e003ab14cb859152427b64b665e691">llvm::APInt::sshl_ov</a>.</p>


<p>Referenced by <a href="#a685bd53265606ced2a0cbabcf8dbd54b">computeShlNSW</a>.</p>

</div>
</div>

### computeShlNSWWithNNegLHS() {#a843e5745d85df82681dadbe26ce86ca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange computeShlNSWWithNNegLHS (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; LHSMin, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; LHSMax, unsigned RHSMin, unsigned RHSMax)</td>
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



<p>Definition at line 1708 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aa074b9f5a1efaa0fd8aa4522593f299a">llvm::APInt::countLeadingZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a46ceedee591f92727b85641794a96061">llvm::APInt::getBitsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#acd8afecbb15ee69487d5339371f64a76">llvm::ConstantRange::getNonEmpty</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a36e003ab14cb859152427b64b665e691">llvm::APInt::sshl_ov</a> and <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ad790c9bc3f8cce98f4d714041f2e4589">llvm::APIntOps::umax</a>.</p>


<p>Referenced by <a href="#a685bd53265606ced2a0cbabcf8dbd54b">computeShlNSW</a>.</p>

</div>
</div>

### computeShlNUW() {#a618caf6a690e2208acbfa1b7668df3a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange computeShlNUW (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; RHS)</td>
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



<p>Definition at line 1685 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aa074b9f5a1efaa0fd8aa4522593f299a">llvm::APInt::countLeadingZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#adcb96bd09d7c75c7669fa5f9d1190899">llvm::APInt::getHighBitsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#acd8afecbb15ee69487d5339371f64a76">llvm::ConstantRange::getNonEmpty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ad790c9bc3f8cce98f4d714041f2e4589">llvm::APIntOps::umax</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a97419fdddc400a50c7c40ef5c35903cd">llvm::APInt::ushl_ov</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa3896afe885ae893809f7de1b23c8d7b">llvm::ConstantRange::shlWithNoWrap</a>.</p>

</div>
</div>

### estimateBitMaskedAndLowerBound() {#a437967d8acddbcdb8cb345412f22f9dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt estimateBitMaskedAndLowerBound (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; RHS)</td>
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

<p>Estimate the 'bit-masked AND' operation's lower bound.</p>


<p>E.g., given two ranges as follows (single quotes are separators and have no meaning here),</p>


<p>LHS = [10'00101'1, ; LLo 10'10000'0] ; LHi RHS = [10'11111'0, ; RLo 10'11111'1] ; RHi</p>


<p>we know that the higher 2 bits of the result is always 10; and we also notice that RHS[1:6] are always 1, so the result[1:6] cannot be less than LHS[1:6] (i.e., 00101). Thus, the lower bound is 10'00101'0.</p>


<p>The algorithm is as follows,</p>


<ol class="doxyList" type="1">
<li>we first calculate a mask to find the higher common bits by Mask = ~((LLo ^ LHi) | (RLo ^ RHi) | (LLo ^ RLo)); Mask = clear all non-leading-ones bits in Mask; in the example, the Mask is set to 11'00000'0;</li>
<li>calculate a new mask by setting all common leading bits to 1 in RHS, and keeping the longest leading ones (i.e., 11'11111'0 in the example);</li>
<li>return (LLo &amp; new mask) as the lower bound;</li>
<li>repeat the step 2 and 3 with LHS and RHS swapped, and update the lower bound with the larger one.</li>
</ol>

<p>Definition at line 1547 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ad790c9bc3f8cce98f4d714041f2e4589">llvm::APIntOps::umax</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aac5f27f8d0ff473183fff55780e5796c">llvm::ConstantRange::binaryAnd</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ae3a906a72244158de8ae4a764e861d79">llvm::ConstantRange::binaryOr</a>.</p>

</div>
</div>

### getPreferredRange() {#aa9d811df7ac170e0bcf950a650479e47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange getPreferredRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR2, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a0e6f2069000829208cbac185a07d8082">ConstantRange::PreferredRangeType</a> Type)</td>
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



<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a66d4b4c9a335549fc329921f27ac67fc">llvm::ConstantRange::isSignWrappedSet</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#af656a14964b9cf9e049c1064b5f30c2b">llvm::ConstantRange::isSizeStrictlySmallerThan</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a76bca22a9253d0962fd07031c89b98e7">llvm::ConstantRange::isWrappedSet</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a0e6f2069000829208cbac185a07d8082a8260f3d302e2463fd93753dfd0de6ec1">llvm::ConstantRange::Signed</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a0e6f2069000829208cbac185a07d8082ade1662f5186fd8852b4dcce8eb6563bc">llvm::ConstantRange::Unsigned</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ac098fe4f07549fb029fbf950dbe78fd3">llvm::ConstantRange::intersectWith</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa81521f99442a5c30f9061b8c6ce795e">llvm::ConstantRange::unionWith</a>.</p>

</div>
</div>

### getUnsignedCountTrailingZerosRange() {#ae6e0521392f7c7e8a1daa7511a533201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange getUnsignedCountTrailingZerosRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Lower, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Upper)</td>
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



<p>Definition at line 2023 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0ab75fcdd2d72d9e000beab48622402d93">llvm::Lower</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0a19de5b94f7b83900d4b296d9fa491aec">llvm::Upper</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantrange/#acc1e6bafefba3a5989e135575377032d">llvm::ConstantRange::cttz</a>.</p>

</div>
</div>

### getUnsignedPopCountRange() {#a623310118173612285ce605149f43264}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange getUnsignedPopCountRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Lower, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Upper)</td>
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



<p>Definition at line 2091 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0ab75fcdd2d72d9e000beab48622402d93">llvm::Lower</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0a19de5b94f7b83900d4b296d9fa491aec">llvm::Upper</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantrange/#acde7e3c58a91a9ba77071d8a84626184">llvm::ConstantRange::ctpop</a>.</p>

</div>
</div>

### makeExactMulNSWRegion() {#aa69e07fa7ca7953d971574873d5ec5c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange makeExactMulNSWRegion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; V)</td>
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

<p>Exact mul nsw region for single element RHS.</p>

<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3a0519ef55bfe3d07f8fb2eafb5cdbbdac4e0e4e3118472beeb2ae75827450f1f">llvm::APInt::DOWN</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#acd8afecbb15ee69487d5339371f64a76">llvm::ConstantRange::getNonEmpty</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a562c9513409b74f02cb3a5c9bae672ea">llvm::APInt::getSignedMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0ab75fcdd2d72d9e000beab48622402d93">llvm::Lower</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a59d1e0778623481e8a1599800d892946">llvm::APIntOps::RoundingSDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3a0519ef55bfe3d07f8fb2eafb5cdbbdafbaedde498cdead4f2780217646e9ba1">llvm::APInt::UP</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0a19de5b94f7b83900d4b296d9fa491aec">llvm::Upper</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ace208c0bd1d845fe49f319be6a954764">llvm::ConstantRange::makeGuaranteedNoWrapRegion</a>.</p>

</div>
</div>

### makeExactMulNUWRegion() {#a7e7e5e776b7f30a4522e2d415efe1dfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange makeExactMulNUWRegion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; V)</td>
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

<p>Exact mul nuw region for single element RHS.</p>

<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp">ConstantRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3a0519ef55bfe3d07f8fb2eafb5cdbbdac4e0e4e3118472beeb2ae75827450f1f">llvm::APInt::DOWN</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a331d69b5f93e47e7c596062b77dd5913">llvm::APInt::getMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a65a6479206acd4113b8aa1c0fbc2158c">llvm::APInt::getMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#acd8afecbb15ee69487d5339371f64a76">llvm::ConstantRange::getNonEmpty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a1c533fb6a26fce38d9cec2b51a7a90b0">llvm::APIntOps::RoundingUDiv</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a3a0519ef55bfe3d07f8fb2eafb5cdbbdafbaedde498cdead4f2780217646e9ba1">llvm::APInt::UP</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ace208c0bd1d845fe49f319be6a954764">llvm::ConstantRange::makeGuaranteedNoWrapRegion</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
