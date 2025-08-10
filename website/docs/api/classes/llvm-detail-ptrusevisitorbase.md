---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/detail/ptrusevisitorbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PtrUseVisitorBase` Class

<p>Implementation of non-dependent functionality for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor">PtrUseVisitor</a></span>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::detail::PtrUseVisitorBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ptrusevisitor-h">llvm/Analysis/PtrUseVisitor.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor">PtrUseVisitor&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A base class for visitors over the uses of a pointer value. <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor">PtrUseVisitor&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A base class for visitors over the uses of a pointer value. <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor">PtrUseVisitor&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A base class for visitors over the uses of a pointer value. <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor">PtrUseVisitor&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A base class for visitors over the uses of a pointer value. <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17dd1253e0ec2090980e7544fea1bd83">PtrUseVisitorBase</a> (const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Note that the constructor is protected because this class must be a base class, we can't create instances directly of this class. <a href="#a17dd1253e0ec2090980e7544fea1bd83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ea2fc89be409baf64d5a935f6b02f28">enqueueUsers</a> (Value &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enqueue the users of this instruction in the visit worklist. <a href="#a0ea2fc89be409baf64d5a935f6b02f28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64dcf542ea4428468c3250f5516eaad0">adjustOffsetForGEP</a> (GetElementPtrInst &amp;GEPI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Walk the operands of a GEP and adjust the offset as appropriate. <a href="#a64dcf542ea4428468c3250f5516eaad0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5b2513c27d0e8fe9a9214eb9fe99a7b">DL</a></td>
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

## Visitation infrastructure Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/ptrusevisitorbase/ptrinfo">PtrInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6847f1159ccc4f90e71099c76800f893">PI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The info collected about the pointer being visited thus far. <a href="#a6847f1159ccc4f90e71099c76800f893">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/detail/ptrusevisitorbase/usetovisit">UseToVisit</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25895eaaa828e3f424556096c2436470">Worklist</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The worklist of to-visit uses. <a href="#a25895eaaa828e3f424556096c2436470">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7e154950d853141249e15827b62d6e4">VisitedUses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A set of visited uses to break cycles in unreachable code. <a href="#af7e154950d853141249e15827b62d6e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Per-visit state Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1e78f8a1f204bed8ad26681199fa16b">U</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The use currently being visited. <a href="#ac1e78f8a1f204bed8ad26681199fa16b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a316979fc921154b24c0c323810c285b6">IsOffsetKnown</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if we have a known constant offset for the use currently being visited. <a href="#a316979fc921154b24c0c323810c285b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a082865790e32a27f3e3adf8db2c556e6">Offset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The constant offset of the use if that is known. <a href="#a082865790e32a27f3e3adf8db2c556e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Implementation of non-dependent functionality for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor">PtrUseVisitor</a></span>.</p>


<p>See <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor">PtrUseVisitor</a></span> for the public interface and detailed comments about usage. This class is just a helper base class which is not templated and contains all common code to be shared between different instantiations of <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor">PtrUseVisitor</a>.</p>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ptrusevisitor-h">PtrUseVisitor.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### PtrUseVisitorBase() {#a17dd1253e0ec2090980e7544fea1bd83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::PtrUseVisitorBase::PtrUseVisitorBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Note that the constructor is protected because this class must be a base class, we can't create instances directly of this class.</p>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ptrusevisitor-h">PtrUseVisitor.h</a>.</p>


<p>Reference <a href="#ac5b2513c27d0e8fe9a9214eb9fe99a7b">DL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a564995c967b0a398c32f31a41b4418c1">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::PtrUseVisitor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### adjustOffsetForGEP() {#a64dcf542ea4428468c3250f5516eaad0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool detail::PtrUseVisitorBase::adjustOffsetForGEP (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> &amp; GEPI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Walk the operands of a GEP and adjust the offset as appropriate.</p>


<p>This routine does the heavy lifting of the pointer walk by computing offsets and looking through GEPs.</p>


<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ptrusevisitor-h">PtrUseVisitor.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ptrusevisitor-cpp">PtrUseVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#acd203d07a075c5a33492609ef8f3643e">llvm::GetElementPtrInst::accumulateConstantOffset</a>, <a href="#ac5b2513c27d0e8fe9a9214eb9fe99a7b">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a316979fc921154b24c0c323810c285b6">IsOffsetKnown</a>, <a href="#a082865790e32a27f3e3adf8db2c556e6">Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a9b5fc98b47d44d1150d3610bdfab1430">llvm::APInt::sextOrTrunc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a9481f3ebdbe940c0b6fe67d1fe0e45a2">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitGetElementPtrInst</a>.</p>

</div>
</div>

### enqueueUsers() {#a0ea2fc89be409baf64d5a935f6b02f28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void detail::PtrUseVisitorBase::enqueueUsers (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enqueue the users of this instruction in the visit worklist.</p>


<p>This will visit the users with the same offset of the current visit (including an unknown offset if that is the current state).</p>


<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ptrusevisitor-h">PtrUseVisitor.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ptrusevisitor-cpp">PtrUseVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a316979fc921154b24c0c323810c285b6">IsOffsetKnown</a>, <a href="#a082865790e32a27f3e3adf8db2c556e6">Offset</a>, <a href="#ac1e78f8a1f204bed8ad26681199fa16b">U</a>, <a href="#af7e154950d853141249e15827b62d6e4">VisitedUses</a> and <a href="#a25895eaaa828e3f424556096c2436470">Worklist</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#aa7dac4f1adefec91c970ee7a0463dafb">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitAddrSpaceCastInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker/#a6d53db8820f5704f0678827ac5314fcb">anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitArgPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#ab5c883233fb1eca9c18759fb49863a6e">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitBitCastInst</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a9481f3ebdbe940c0b6fe67d1fe0e45a2">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker/#ab3aa1464b2b55295908eda7a46e640d2">anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitPHINode</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/anonymous-spillutils-cpp-/anonymous-spillutils-cpp-/allocausevisitor/#a9abec8287473e11d538af2bc9e1b47d5">llvm::coro::anonymous{SpillUtils.cpp}::anonymous{SpillUtils.cpp}::AllocaUseVisitor::visitPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a764cd98e9a2d1c1fdfb40aa63ef17385">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitPtr</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker/#ae80d67de5ce189482d9a9bbf0ad74f8a">anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitSelectInst</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/anonymous-spillutils-cpp-/anonymous-spillutils-cpp-/allocausevisitor/#a9243fbfd9f574d8a94c4469b3bba4967">llvm::coro::anonymous{SpillUtils.cpp}::anonymous{SpillUtils.cpp}::AllocaUseVisitor::visitSelectInst</a> and <a href="/web-llvm/docs/api/structs/llvm/coro/anonymous-spillutils-cpp-/anonymous-spillutils-cpp-/allocausevisitor/#ad71ead87ca8f3fc5edfb6173a970f792">llvm::coro::anonymous{SpillUtils.cpp}::anonymous{SpillUtils.cpp}::AllocaUseVisitor::visitStoreInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### DL {#ac5b2513c27d0e8fe9a9214eb9fe99a7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; llvm::detail::PtrUseVisitorBase::DL</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ptrusevisitor-h">PtrUseVisitor.h</a>.</p>


<p>Referenced by <a href="#a64dcf542ea4428468c3250f5516eaad0">adjustOffsetForGEP</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/anonymous-spillutils-cpp-/anonymous-spillutils-cpp-/allocausevisitor/#a5a7dd3f145f4927fa6bd942c6fcad594">llvm::coro::anonymous{SpillUtils.cpp}::anonymous{SpillUtils.cpp}::AllocaUseVisitor::AllocaUseVisitor</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker/#a71ebd297e9e7fcb4694823552638ca92">anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::ArgUseChecker</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a564995c967b0a398c32f31a41b4418c1">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::PtrUseVisitor</a>, <a href="#a17dd1253e0ec2090980e7544fea1bd83">PtrUseVisitorBase</a>, <a href="/web-llvm/docs/api/classes/allocaslices/slicebuilder/#a8a54eb11a6edc3c5411cbedcf76b2002">AllocaSlices::SliceBuilder::SliceBuilder</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker/#a6d53db8820f5704f0678827ac5314fcb">anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitArgPtr</a> and <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a764cd98e9a2d1c1fdfb40aa63ef17385">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitPtr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Visitation infrastructure

### PI {#a6847f1159ccc4f90e71099c76800f893}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PtrInfo llvm::detail::PtrUseVisitorBase::PI</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The info collected about the pointer being visited thus far.</p>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ptrusevisitor-h">PtrUseVisitor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/coro/anonymous-spillutils-cpp-/anonymous-spillutils-cpp-/allocausevisitor/#a9c6e21ecfcb258d3ec0f43046e5e5d29">llvm::coro::anonymous{SpillUtils.cpp}::anonymous{SpillUtils.cpp}::AllocaUseVisitor::visit</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker/#af391484de12c9ec8d52eb99a4b90ce22">anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitAddrSpaceCastInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker/#a6d53db8820f5704f0678827ac5314fcb">anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitArgPtr</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/anonymous-spillutils-cpp-/anonymous-spillutils-cpp-/allocausevisitor/#ac88e3e89148ab5849fc08d1eef269a84">llvm::coro::anonymous{SpillUtils.cpp}::anonymous{SpillUtils.cpp}::AllocaUseVisitor::visitCallBase</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a1320c1780d4b96711e44c8bb2735fe86">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitCallBase</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#adce253af48185f52c4b9d2e0088fd13e">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitIntrinsicInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker/#ac480d5ec4a2af976fb125994bd2f813b">anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitMemSetInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker/#a6a5d035377608cd4d4ac33d4bbd4ef19">anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitMemTransferInst</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a764cd98e9a2d1c1fdfb40aa63ef17385">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#ae2b78e730d1e5425d93f72989cfe0902">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitPtrToIntInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker/#a45fce26e764af6df64d6e3de8ade3e99">anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitStoreInst</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/anonymous-spillutils-cpp-/anonymous-spillutils-cpp-/allocausevisitor/#ad71ead87ca8f3fc5edfb6173a970f792">llvm::coro::anonymous{SpillUtils.cpp}::anonymous{SpillUtils.cpp}::AllocaUseVisitor::visitStoreInst</a> and <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#ac6692a6fe0bccaaa2867a7b3c60c4a71">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitStoreInst</a>.</p>

</div>
</div>

### VisitedUses {#af7e154950d853141249e15827b62d6e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Use *, 8&gt; llvm::detail::PtrUseVisitorBase::VisitedUses</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A set of visited uses to break cycles in unreachable code.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ptrusevisitor-h">PtrUseVisitor.h</a>.</p>


<p>Referenced by <a href="#a0ea2fc89be409baf64d5a935f6b02f28">enqueueUsers</a>.</p>

</div>
</div>

### Worklist {#a25895eaaa828e3f424556096c2436470}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;UseToVisit, 8&gt; llvm::detail::PtrUseVisitorBase::Worklist</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The worklist of to-visit uses.</p>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ptrusevisitor-h">PtrUseVisitor.h</a>.</p>


<p>Referenced by <a href="#a0ea2fc89be409baf64d5a935f6b02f28">enqueueUsers</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker/#a6d53db8820f5704f0678827ac5314fcb">anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitArgPtr</a> and <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a764cd98e9a2d1c1fdfb40aa63ef17385">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitPtr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Per-visit state



<p>This state is reset for each instruction visited.</p>


### IsOffsetKnown {#a316979fc921154b24c0c323810c285b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::PtrUseVisitorBase::IsOffsetKnown</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if we have a known constant offset for the use currently being visited.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ptrusevisitor-h">PtrUseVisitor.h</a>.</p>


<p>Referenced by <a href="#a64dcf542ea4428468c3250f5516eaad0">adjustOffsetForGEP</a>, <a href="#a0ea2fc89be409baf64d5a935f6b02f28">enqueueUsers</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker/#a6d53db8820f5704f0678827ac5314fcb">anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitArgPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a9481f3ebdbe940c0b6fe67d1fe0e45a2">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/anonymous-spillutils-cpp-/anonymous-spillutils-cpp-/allocausevisitor/#a96589b57eb052bdf4c82c7f6cb1e786d">llvm::coro::anonymous{SpillUtils.cpp}::anonymous{SpillUtils.cpp}::AllocaUseVisitor::visitIntrinsicInst</a> and <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a764cd98e9a2d1c1fdfb40aa63ef17385">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitPtr</a>.</p>

</div>
</div>

### Offset {#a082865790e32a27f3e3adf8db2c556e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::PtrUseVisitorBase::Offset</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The constant offset of the use if that is known.</p>

<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ptrusevisitor-h">PtrUseVisitor.h</a>.</p>


<p>Referenced by <a href="#a64dcf542ea4428468c3250f5516eaad0">adjustOffsetForGEP</a>, <a href="#a0ea2fc89be409baf64d5a935f6b02f28">enqueueUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a042a140d5a5c309fbc47a1a90eddedc6">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::InstVisitor&lt; DerivedT &gt;</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker/#a6d53db8820f5704f0678827ac5314fcb">anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitArgPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a9481f3ebdbe940c0b6fe67d1fe0e45a2">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/anonymous-spillutils-cpp-/anonymous-spillutils-cpp-/allocausevisitor/#a96589b57eb052bdf4c82c7f6cb1e786d">llvm::coro::anonymous{SpillUtils.cpp}::anonymous{SpillUtils.cpp}::AllocaUseVisitor::visitIntrinsicInst</a> and <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a764cd98e9a2d1c1fdfb40aa63ef17385">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitPtr</a>.</p>

</div>
</div>

### U {#ac1e78f8a1f204bed8ad26681199fa16b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use* llvm::detail::PtrUseVisitorBase::U</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The use currently being visited.</p>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ptrusevisitor-h">PtrUseVisitor.h</a>.</p>


<p>Referenced by <a href="#a0ea2fc89be409baf64d5a935f6b02f28">enqueueUsers</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker/#a6d53db8820f5704f0678827ac5314fcb">anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitArgPtr</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/anonymous-spillutils-cpp-/anonymous-spillutils-cpp-/allocausevisitor/#ac88e3e89148ab5849fc08d1eef269a84">llvm::coro::anonymous{SpillUtils.cpp}::anonymous{SpillUtils.cpp}::AllocaUseVisitor::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker/#a6a5d035377608cd4d4ac33d4bbd4ef19">anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitMemTransferInst</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a764cd98e9a2d1c1fdfb40aa63ef17385">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitPtr</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker/#a45fce26e764af6df64d6e3de8ade3e99">anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitStoreInst</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/anonymous-spillutils-cpp-/anonymous-spillutils-cpp-/allocausevisitor/#ad71ead87ca8f3fc5edfb6173a970f792">llvm::coro::anonymous{SpillUtils.cpp}::anonymous{SpillUtils.cpp}::AllocaUseVisitor::visitStoreInst</a> and <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#ac6692a6fe0bccaaa2867a7b3c60c4a71">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitStoreInst</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ptrusevisitor-h">PtrUseVisitor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/ptrusevisitor-cpp">PtrUseVisitor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
