---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-separateconstoffsetfromgep-cpp-/constantoffsetextractor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ConstantOffsetExtractor` Class Reference

<p>A helper class for separating a constant offset from a GEP index. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{SeparateConstOffsetFromGEP.cpp}::ConstantOffsetExtractor { ... }
</div>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30c61b0081d8d8eb75beb4d5193c5e89">ConstantOffsetExtractor</a> (BasicBlock::iterator InsertionPt)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b43ed82204cf5a8d8508f6caa62f71e">find</a> (Value *V, bool SignExtended, bool ZeroExtended, bool NonNegative)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Searches the expression that computes V for a non-zero constant C s.t. <a href="#a7b43ed82204cf5a8d8508f6caa62f71e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57fabe3822ccf25985ef25e631ee3ccd">findInEitherOperand</a> (BinaryOperator *BO, bool SignExtended, bool ZeroExtended)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper function to look into both operands of a binary operator. <a href="#a57fabe3822ccf25985ef25e631ee3ccd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78959368b08ec9f83d62069638155baf">rebuildWithoutConstOffset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>After finding the constant offset C from the GEP index I, we build a new index I' s.t. <a href="#a78959368b08ec9f83d62069638155baf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a865a2e6eb480b162bfa814a81e1a8568">distributeExtsAndCloneChain</a> (unsigned ChainIndex)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>After the first step of rebuilding the GEP index without the constant offset, distribute s/zext to the operands of all operators in UserChain. <a href="#a865a2e6eb480b162bfa814a81e1a8568">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2694526eb3294698abfd547a63429a32">removeConstOffset</a> (unsigned ChainIndex)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reassociates the GEP index to the form I' + C and returns I'. <a href="#a2694526eb3294698abfd547a63429a32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d18d46ccd1e656e6b3611358e1d83aa">applyExts</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper function to apply ExtInsts, a list of s/zext, to value V. <a href="#a0d18d46ccd1e656e6b3611358e1d83aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b504895b92395669bf978ee919c33a4">CanTraceInto</a> (bool SignExtended, bool ZeroExtended, BinaryOperator *BO, bool NonNegative)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper function that returns whether we can trace into the operands of binary operator BO for a constant offset. <a href="#a6b504895b92395669bf978ee919c33a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/user">User</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0114f230694b36b1e009ab3424bc216">UserChain</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The path from the constant offset to the old GEP index. <a href="#ad0114f230694b36b1e009ab3424bc216">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3e3847ac4a5a018d2152ac912c1e28d">ExtInsts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A data structure used in rebuildWithoutConstOffset. <a href="#af3e3847ac4a5a018d2152ac912c1e28d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa948ae88ae245e1e9cd2b674a41743e0">IP</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insertion position of cloned instructions. <a href="#aa948ae88ae245e1e9cd2b674a41743e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dcfbde4b78703662d54658387268cfc">DL</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a867434c3e87f84340731c31c5e1b863d">Extract</a> (Value *Idx, GetElementPtrInst *GEP, User *&amp;UserChainTail)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extracts a constant offset from the given GEP index. <a href="#a867434c3e87f84340731c31c5e1b863d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaffc55116f7466c3676d8852dc95175d">Find</a> (Value *Idx, GetElementPtrInst *GEP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks for a constant offset from the given GEP index without extracting it. <a href="#aaffc55116f7466c3676d8852dc95175d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A helper class for separating a constant offset from a GEP index.</p>


<p>In real programs, a GEP index may be more complicated than a simple addition of something and a constant integer which can be trivially splitted. For example, to split ((a &lt;&lt; 3) | 5) + b, we need to search deeper for the constant offset, so that we can separate the index to (a &lt;&lt; 3) + b and 5.</p>


<p>Therefore, this class looks into the expression that computes a given GEP index, and tries to find a constant integer that can be hoisted to the outermost level of the expression as an addition. Not every constant in an expression can jump out. e.g., we cannot transform (b * (a + 5)) to (b * a + 5); nor can we transform (3 * (a + 5)) to (3 * a + 5), however in this case, -instcombine probably already optimized (3 * (a + 5)) to (3 * a + 15).</p>


<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### ConstantOffsetExtractor() {#a30c61b0081d8d8eb75beb4d5193c5e89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SeparateConstOffsetFromGEP.cpp}::ConstantOffsetExtractor::ConstantOffsetExtractor (<a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> InsertionPt)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### applyExts() {#a0d18d46ccd1e656e6b3611358e1d83aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * ConstantOffsetExtractor::applyExts (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A helper function to apply ExtInsts, a list of s/zext, to value V.</p>


<p>e.g., if ExtInsts = [sext i32 to i64, zext i16 to i32], this function returns "sext i32 (zext i16 V to i32) to i64".</p>


<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### CanTraceInto() {#a6b504895b92395669bf978ee919c33a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantOffsetExtractor::CanTraceInto (bool SignExtended, bool ZeroExtended, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * BO, bool NonNegative)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A helper function that returns whether we can trace into the operands of binary operator BO for a constant offset.</p>


<p><span class="doxyComputerOutput">SignExtended</span> Whether BO is surrounded by sext <span class="doxyComputerOutput">ZeroExtended</span> Whether BO is surrounded by zext <span class="doxyComputerOutput">NonNegative</span> Whether BO is known to be non-negative, e.g., an in-bound array index.</p>


<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### distributeExtsAndCloneChain() {#a865a2e6eb480b162bfa814a81e1a8568}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * ConstantOffsetExtractor::distributeExtsAndCloneChain (unsigned ChainIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>After the first step of rebuilding the GEP index without the constant offset, distribute s/zext to the operands of all operators in UserChain.</p>


<p>e.g., zext(sext(a + (b + 5)) (assuming no overflow) =&gt; zext(sext(a)) + (zext(sext(b)) + zext(sext(5))).</p>


<p>The function also updates UserChain to point to new subexpressions after distributing s/zext. e.g., the old UserChain of the above example is 5 -&gt; b + 5 -&gt; a + (b + 5) -&gt; sext(...) -&gt; zext(sext(...)), and the new UserChain is zext(sext(5)) -&gt; zext(sext(b)) + zext(sext(5)) -&gt; zext(sext(a)) + (zext(sext(b)) + zext(sext(5))</p>


<p><span class="doxyComputerOutput">ChainIndex</span> The index to UserChain. ChainIndex is initially UserChain.size() - 1, and is decremented during the recursion.</p>


<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### find() {#a7b43ed82204cf5a8d8508f6caa62f71e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt ConstantOffsetExtractor::find (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, bool SignExtended, bool ZeroExtended, bool NonNegative)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Searches the expression that computes V for a non-zero constant C s.t.</p>


<p>V can be reassociated into the form V' + C. If the searching is successful, returns C and update UserChain as a def-use chain from C to V; otherwise, UserChain is empty.</p>


<p><span class="doxyComputerOutput">V</span> The given expression <span class="doxyComputerOutput">SignExtended</span> Whether V will be sign-extended in the computation of the GEP index <span class="doxyComputerOutput">ZeroExtended</span> Whether V will be zero-extended in the computation of the GEP index <span class="doxyComputerOutput">NonNegative</span> Whether V is guaranteed to be non-negative. For example, an index of an inbounds GEP is guaranteed to be non-negative. Levaraging this, we can better split inbounds GEPs.</p>


<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### findInEitherOperand() {#a57fabe3822ccf25985ef25e631ee3ccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt ConstantOffsetExtractor::findInEitherOperand (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * BO, bool SignExtended, bool ZeroExtended)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A helper function to look into both operands of a binary operator.</p>

<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### rebuildWithoutConstOffset() {#a78959368b08ec9f83d62069638155baf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * ConstantOffsetExtractor::rebuildWithoutConstOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>After finding the constant offset C from the GEP index I, we build a new index I' s.t.</p>


<p>I' + C = I. This function builds and returns the new index I' according to UserChain produced by function "find".</p>


<p>The building conceptually takes two steps: 1) iteratively distribute s/zext towards the leaves of the expression tree that computes I 2) reassociate the expression tree to the form I' + C.</p>


<p>For example, to extract the 5 from sext(a + (b + 5)), we first distribute sext to a, b and 5 so that we have sext(a) + (sext(b) + 5). Then, we reassociate it to (sext(a) + sext(b)) + 5. Given this form, we know I' is sext(a) + sext(b).</p>


<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### removeConstOffset() {#a2694526eb3294698abfd547a63429a32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * ConstantOffsetExtractor::removeConstOffset (unsigned ChainIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reassociates the GEP index to the form I' + C and returns I'.</p>

<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DL {#a6dcfbde4b78703662d54658387268cfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; anonymous{SeparateConstOffsetFromGEP.cpp}::ConstantOffsetExtractor::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### ExtInsts {#af3e3847ac4a5a018d2152ac912c1e28d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;CastInst *, 16&gt; anonymous{SeparateConstOffsetFromGEP.cpp}::ConstantOffsetExtractor::ExtInsts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A data structure used in rebuildWithoutConstOffset.</p>


<p>Contains all sext/zext instructions along UserChain.</p>


<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### IP {#aa948ae88ae245e1e9cd2b674a41743e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock::iterator anonymous{SeparateConstOffsetFromGEP.cpp}::ConstantOffsetExtractor::IP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insertion position of cloned instructions.</p>

<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

### UserChain {#ad0114f230694b36b1e009ab3424bc216}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;User *, 8&gt; anonymous{SeparateConstOffsetFromGEP.cpp}::ConstantOffsetExtractor::UserChain</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The path from the constant offset to the old GEP index.</p>


<p>e.g., if the GEP index is "a * b + (c + 5)". After running function find, UserChain[0] will be the constant 5, UserChain[1] will be the subexpression "c + 5", and UserChain[2] will be the entire expression "a * b + (c + 5)".</p>


<p>This path helps to rebuild the new GEP index.</p>


<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Extract() {#a867434c3e87f84340731c31c5e1b863d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * ConstantOffsetExtractor::Extract (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Idx, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> * GEP, <a href="/web-llvm/docs/api/classes/llvm/user">User</a> *&amp; UserChainTail)</td>
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

<p>Extracts a constant offset from the given GEP index.</p>


<p>It returns the new index representing the remainder (equal to the original index minus the constant offset), or nullptr if we cannot extract a constant offset. <span class="doxyComputerOutput">Idx</span> The given GEP index <span class="doxyComputerOutput">GEP</span> The given GEP <span class="doxyComputerOutput">UserChainTail</span> Outputs the tail of UserChain so that we can garbage-collect unused instructions in UserChain.</p>


<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>.</p>

</div>
</div>

### Find() {#aaffc55116f7466c3676d8852dc95175d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t ConstantOffsetExtractor::Find (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Idx, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> * GEP)</td>
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

<p>Looks for a constant offset from the given GEP index without extracting it.</p>


<p>It returns the numeric value of the extracted constant offset (0 if failed). The meaning of the arguments are the same as Extract.</p>


<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp">SeparateConstOffsetFromGEP.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
