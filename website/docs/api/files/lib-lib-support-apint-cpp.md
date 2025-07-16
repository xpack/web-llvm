---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/apint-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `APInt.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">llvm/ADT/FoldingSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">llvm/ADT/Hashing.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bit-h">llvm/ADT/bit.h</a>"
#include "llvm/Config/llvm-config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">llvm/Support/Alignment.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cmath&gt;
#include &lt;optional&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af853fcc5930f7653d40c2637dc728bb5">getClearedMemory</a> (unsigned numWords)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A utility function for allocating memory, checking for allocation failures, and ensuring the contents are zeroed. <a href="#af853fcc5930f7653d40c2637dc728bb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9eab7a6f6e43c3a48731017dd24e746">getMemory</a> (unsigned numWords)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A utility function for allocating memory and checking for allocation failure. <a href="#ae9eab7a6f6e43c3a48731017dd24e746">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aced746e8db93cd749b6226df5350cc1d">getDigit</a> (char cdigit, uint8_t radix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A utility function that converts a character to a digit. <a href="#aced746e8db93cd749b6226df5350cc1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b409aa866bfa91f29f51fd35bb56003">tcComplement</a> (APInt::WordType *dst, unsigned parts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e85075a57f714ace735081ee4e4134e">rotateModulo</a> (unsigned BitWidth, const APInt &amp;rotateAmt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4b80b2d90bc4614ea242503aa88df37">KnuthDiv</a> (uint32_t *u, uint32_t *v, uint32_t *q, uint32_t *r, unsigned m, unsigned n)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementation of Knuth's Algorithm D (Division of nonnegative integers) from "Art of Computer Programming, Volume 2", section 4.3.1, p. <a href="#af4b80b2d90bc4614ea242503aa88df37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint/#a5221357e5b7511cb0c90c94044ba35cf">APInt::WordType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae876a1ecb46543fee1f374dd8c2fad13">lowBitMask</a> (unsigned bits)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint/#a5221357e5b7511cb0c90c94044ba35cf">APInt::WordType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17d47a818ea2835a5ad9fee50c239ac1">lowHalf</a> (APInt::WordType part)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the value of the lower half of PART. <a href="#a17d47a818ea2835a5ad9fee50c239ac1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint/#a5221357e5b7511cb0c90c94044ba35cf">APInt::WordType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74a725ce0eb6c9d51e4c3ddf54b0de8b">highHalf</a> (APInt::WordType part)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the value of the upper half of PART. <a href="#a74a725ce0eb6c9d51e4c3ddf54b0de8b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"apint"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a853b1f403275dde6db4c3a0b7a799f8f">DEBUG_KNUTH</a>(X)&nbsp;&nbsp;&nbsp;do {} <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a>(false)</td>
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

### getClearedMemory() {#af853fcc5930f7653d40c2637dc728bb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t * getClearedMemory (unsigned numWords)</td>
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

<p>A utility function for allocating memory, checking for allocation failures, and ensuring the contents are zeroed.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### getDigit() {#aced746e8db93cd749b6226df5350cc1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getDigit (char cdigit, uint8_t radix)</td>
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

<p>A utility function that converts a character to a digit.</p>

<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### getMemory() {#ae9eab7a6f6e43c3a48731017dd24e746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t * getMemory (unsigned numWords)</td>
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

<p>A utility function for allocating memory and checking for allocation failure.</p>


<p>The content is not zeroed.</p>


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apint/#a8affacda773b55e259f6dc4da77d948a">llvm::APInt::operator*</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aca8fce65eb69a82aa10a635e2e79877a">llvm::APInt::sext</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a317c64fd4cfebc88e79387b3821a629d">llvm::APInt::trunc</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>.</p>

</div>
</div>

### highHalf() {#a74a725ce0eb6c9d51e4c3ddf54b0de8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt::WordType highHalf (<a href="/web-llvm/docs/api/classes/llvm/apint/#a5221357e5b7511cb0c90c94044ba35cf">APInt::WordType</a> part)</td>
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

<p>Returns the value of the upper half of PART.</p>

<p>Definition at line 2308 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/apint/#aaf70a90533b469062634730e27f6577d">llvm::APInt::APINT_BITS_PER_WORD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apint/#aaf3bfaa5ac3f017c8d3b7336d8bd4678">llvm::APInt::tcMultiplyPart</a>.</p>

</div>
</div>

### KnuthDiv() {#af4b80b2d90bc4614ea242503aa88df37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void KnuthDiv (uint32_t * u, uint32_t * v, uint32_t * q, uint32_t * r, unsigned m, unsigned n)</td>
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

<p>Implementation of Knuth's Algorithm D (Division of nonnegative integers) from "Art of Computer Programming, Volume 2", section 4.3.1, p.</p>


<ol class="doxyList" type="1">
<li>The variables here have the same names as in the algorithm. Comments explain the algorithm and any deviation from it.</li>
</ol>

<p>Definition at line 1264 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a853b1f403275dde6db4c3a0b7a799f8f">DEBUG_KNUTH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b622c469acc130c9a500b85b1473ef3">llvm::Hi_32</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp/#a2762113571c7956c9818c452b2d256ae">isNeg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a901112c493d3827cda924430a6fbc9f4">llvm::Lo_32</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af54e0572ecf26033ac3fe4513016dfbe">llvm::Make_64</a>.</p>

</div>
</div>

### lowBitMask() {#ae876a1ecb46543fee1f374dd8c2fad13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt::WordType lowBitMask (unsigned bits)</td>
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



<p>Definition at line 2297 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#aaf70a90533b469062634730e27f6577d">llvm::APInt::APINT_BITS_PER_WORD</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a17d47a818ea2835a5ad9fee50c239ac1">lowHalf</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a2732964a6de928520d3d12be196a7a15">llvm::APInt::tcExtract</a>.</p>

</div>
</div>

### lowHalf() {#a17d47a818ea2835a5ad9fee50c239ac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt::WordType lowHalf (<a href="/web-llvm/docs/api/classes/llvm/apint/#a5221357e5b7511cb0c90c94044ba35cf">APInt::WordType</a> part)</td>
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

<p>Returns the value of the lower half of PART.</p>

<p>Definition at line 2303 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#aaf70a90533b469062634730e27f6577d">llvm::APInt::APINT_BITS_PER_WORD</a> and <a href="#ae876a1ecb46543fee1f374dd8c2fad13">lowBitMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apint/#aaf3bfaa5ac3f017c8d3b7336d8bd4678">llvm::APInt::tcMultiplyPart</a>.</p>

</div>
</div>

### rotateModulo() {#a6e85075a57f714ace735081ee4e4134e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned rotateModulo (unsigned BitWidth, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; rotateAmt)</td>
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



<p>Definition at line 1097 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ab01d8694a759a934e01f1c558c3ce862">llvm::APInt::getLimitedValue</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a104cae72182bec0ab951e3faea6ce509">LLVM_UNLIKELY</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a4e3a2187cacdec76028617a403c47d89">llvm::APInt::urem</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apint/#a65bc3d32a3f55045259fda31d9fffb28">llvm::APInt::rotl</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#acc8a2eb3a9949f9e26c2724ef3a109cd">llvm::APInt::rotr</a>.</p>

</div>
</div>

### tcComplement() {#a7b409aa866bfa91f29f51fd35bb56003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void tcComplement (<a href="/web-llvm/docs/api/classes/llvm/apint/#a5221357e5b7511cb0c90c94044ba35cf">APInt::WordType</a> * dst, unsigned parts)</td>
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



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apint/#abece2572a121bb1dd2c34621c1e13f76">llvm::APInt::tcNegate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_KNUTH {#a853b1f403275dde6db4c3a0b7a799f8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_KNUTH(X)&nbsp;&nbsp;&nbsp;do {} <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a>(false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1280 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>Referenced by <a href="#af4b80b2d90bc4614ea242503aa88df37">KnuthDiv</a>.</p>

</div>
</div>

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"apint"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
