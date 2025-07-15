---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ArgUseChecker` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker { ... }
</div>

## Base struct

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

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a895be97a8cb624e00e70d05b39a8d361">Base</a> = <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor">PtrUseVisitor</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker">ArgUseChecker</a> &gt;</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71ebd297e9e7fcb4694823552638ca92">ArgUseChecker</a> (const DataLayout &amp;DL, bool IsGridConstant)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/ptrusevisitorbase/ptrinfo">PtrInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d53db8820f5704f0678827ac5314fcb">visitArgPtr</a> (Argument &amp;A)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45fce26e764af6df64d6e3de8ade3e99">visitStoreInst</a> (StoreInst &amp;SI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af391484de12c9ec8d52eb99a4b90ce22">visitAddrSpaceCastInst</a> (AddrSpaceCastInst &amp;ASC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a876f482276907d12303b1db1e9200e02">visitPtrToIntInst</a> (PtrToIntInst &amp;I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67721dec81dc366665a65387da349242">visitPHINodeOrSelectInst</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3aa1464b2b55295908eda7a46e640d2">visitPHINode</a> (PHINode &amp;PN)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae80d67de5ce189482d9a9bbf0ad74f8a">visitSelectInst</a> (SelectInst &amp;SI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a5d035377608cd4d4ac33d4bbd4ef19">visitMemTransferInst</a> (MemTransferInst &amp;II)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac480d5ec4a2af976fb125994bd2f813b">visitMemSetInst</a> (MemSetInst &amp;II)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f58beabc4f17530f3748090b20e74aa">IsGridConstant</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e73a9be556065c7409760ee5c835391">Conditionals</a></td>
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


<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp">NVPTXLowerArgs.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Base {#a895be97a8cb624e00e70d05b39a8d361}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::Base =  PtrUseVisitor&lt;ArgUseChecker&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp">NVPTXLowerArgs.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ArgUseChecker() {#a71ebd297e9e7fcb4694823552638ca92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::ArgUseChecker (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, bool IsGridConstant)</td>
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



<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp">NVPTXLowerArgs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/detail/ptrusevisitorbase/#ac5b2513c27d0e8fe9a9214eb9fe99a7b">llvm::detail::PtrUseVisitorBase::DL</a>, <a href="#a7f58beabc4f17530f3748090b20e74aa">IsGridConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a564995c967b0a398c32f31a41b4418c1">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::PtrUseVisitor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### visitAddrSpaceCastInst() {#af391484de12c9ec8d52eb99a4b90ce22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitAddrSpaceCastInst (<a href="/web-llvm/docs/api/classes/llvm/addrspacecastinst">AddrSpaceCastInst</a> &amp; ASC)</td>
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



<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp">NVPTXLowerArgs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/nvptxas/#ad7d00b71af84502be65ae2de3f8d91dca145cc11601487c71350537df3e7c3a12">llvm::NVPTXAS::ADDRESS_SPACE_PARAM</a>, <a href="/web-llvm/docs/api/classes/llvm/addrspacecastinst/#ac9234105b582bbe087981c231eb7b292">llvm::AddrSpaceCastInst::getDestAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ptrusevisitorbase/#a6847f1159ccc4f90e71099c76800f893">llvm::detail::PtrUseVisitorBase::PI</a> and <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#aa7dac4f1adefec91c970ee7a0463dafb">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitAddrSpaceCastInst</a>.</p>

</div>
</div>

### visitArgPtr() {#a6d53db8820f5704f0678827ac5314fcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PtrInfo anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitArgPtr (<a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> &amp; A)</td>
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



<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp">NVPTXLowerArgs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a8e73a9be556065c7409760ee5c835391">Conditionals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ptrusevisitorbase/#ac5b2513c27d0e8fe9a9214eb9fe99a7b">llvm::detail::PtrUseVisitorBase::DL</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ptrusevisitorbase/#a0ea2fc89be409baf64d5a935f6b02f28">llvm::detail::PtrUseVisitorBase::enqueueUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a90b790ccb1af4ea5ccd69db4b8cd2d81">llvm::IntegerType::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/pointerintpair/#ac8b55437ca130fe0c826e94e669e5d99">llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::getPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ptrusevisitorbase/#a316979fc921154b24c0c323810c285b6">llvm::detail::PtrUseVisitorBase::IsOffsetKnown</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ptrusevisitorbase/#a082865790e32a27f3e3adf8db2c556e6">llvm::detail::PtrUseVisitorBase::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ptrusevisitorbase/#a6847f1159ccc4f90e71099c76800f893">llvm::detail::PtrUseVisitorBase::PI</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ptrusevisitorbase/#ac1e78f8a1f204bed8ad26681199fa16b">llvm::detail::PtrUseVisitorBase::U</a>, <a href="/web-llvm/docs/api/structs/llvm/detail/ptrusevisitorbase/usetovisit/#a28f946ac353f6118bb637201ff1d5658">llvm::detail::PtrUseVisitorBase::UseToVisit::UseAndIsOffsetKnown</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a6352e72d11377a9c62f24434ae869bf0">llvm::InstVisitor&lt; SubClass, RetTy &gt;::visit</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/ptrusevisitorbase/#a25895eaaa828e3f424556096c2436470">llvm::detail::PtrUseVisitorBase::Worklist</a>.</p>

</div>
</div>

### visitMemSetInst() {#ac480d5ec4a2af976fb125994bd2f813b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitMemSetInst (<a href="/web-llvm/docs/api/classes/llvm/memsetinst">MemSetInst</a> &amp; II)</td>
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



<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp">NVPTXLowerArgs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#a7f58beabc4f17530f3748090b20e74aa">IsGridConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/ptrusevisitorbase/#a6847f1159ccc4f90e71099c76800f893">llvm::detail::PtrUseVisitorBase::PI</a>.</p>

</div>
</div>

### visitMemTransferInst() {#a6a5d035377608cd4d4ac33d4bbd4ef19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitMemTransferInst (<a href="/web-llvm/docs/api/classes/llvm/memtransferinst">MemTransferInst</a> &amp; II)</td>
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



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp">NVPTXLowerArgs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#a7f58beabc4f17530f3748090b20e74aa">IsGridConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ptrusevisitorbase/#a6847f1159ccc4f90e71099c76800f893">llvm::detail::PtrUseVisitorBase::PI</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/ptrusevisitorbase/#ac1e78f8a1f204bed8ad26681199fa16b">llvm::detail::PtrUseVisitorBase::U</a>.</p>

</div>
</div>

### visitPHINode() {#ab3aa1464b2b55295908eda7a46e640d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitPHINode (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> &amp; PN)</td>
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



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp">NVPTXLowerArgs.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/detail/ptrusevisitorbase/#a0ea2fc89be409baf64d5a935f6b02f28">llvm::detail::PtrUseVisitorBase::enqueueUsers</a>.</p>

</div>
</div>

### visitPHINodeOrSelectInst() {#a67721dec81dc366665a65387da349242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitPHINodeOrSelectInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp">NVPTXLowerArgs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### visitPtrToIntInst() {#a876f482276907d12303b1db1e9200e02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitPtrToIntInst (<a href="/web-llvm/docs/api/classes/llvm/ptrtointinst">PtrToIntInst</a> &amp; I)</td>
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



<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp">NVPTXLowerArgs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a7f58beabc4f17530f3748090b20e74aa">IsGridConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#ae2b78e730d1e5425d93f72989cfe0902">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitPtrToIntInst</a>.</p>

</div>
</div>

### visitSelectInst() {#ae80d67de5ce189482d9a9bbf0ad74f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitSelectInst (<a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> &amp; SI)</td>
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



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp">NVPTXLowerArgs.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/detail/ptrusevisitorbase/#a0ea2fc89be409baf64d5a935f6b02f28">llvm::detail::PtrUseVisitorBase::enqueueUsers</a>.</p>

</div>
</div>

### visitStoreInst() {#a45fce26e764af6df64d6e3de8ade3e99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitStoreInst (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> &amp; SI)</td>
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



<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp">NVPTXLowerArgs.cpp</a>.</p>


<p>References <a href="#a7f58beabc4f17530f3748090b20e74aa">IsGridConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ptrusevisitorbase/#a6847f1159ccc4f90e71099c76800f893">llvm::detail::PtrUseVisitorBase::PI</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/ptrusevisitorbase/#ac1e78f8a1f204bed8ad26681199fa16b">llvm::detail::PtrUseVisitorBase::U</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Conditionals {#a8e73a9be556065c7409760ee5c835391}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Instruction *, 4&gt; anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::Conditionals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp">NVPTXLowerArgs.cpp</a>.</p>


<p>Referenced by <a href="#a6d53db8820f5704f0678827ac5314fcb">visitArgPtr</a>.</p>

</div>
</div>

### IsGridConstant {#a7f58beabc4f17530f3748090b20e74aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::IsGridConstant</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp">NVPTXLowerArgs.cpp</a>.</p>


<p>Referenced by <a href="#a71ebd297e9e7fcb4694823552638ca92">ArgUseChecker</a>, <a href="#ac480d5ec4a2af976fb125994bd2f813b">visitMemSetInst</a>, <a href="#a6a5d035377608cd4d4ac33d4bbd4ef19">visitMemTransferInst</a>, <a href="#a876f482276907d12303b1db1e9200e02">visitPtrToIntInst</a> and <a href="#a45fce26e764af6df64d6e3de8ade3e99">visitStoreInst</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp">NVPTXLowerArgs.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
