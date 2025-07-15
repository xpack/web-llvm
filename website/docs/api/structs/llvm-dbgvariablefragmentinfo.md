---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dbgvariablefragmentinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DbgVariableFragmentInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::DbgVariableFragmentInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dbgvariablefragmentinfo-h">llvm/IR/DbgVariableFragmentInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c235ba7e1d271d668371091802fc165">DbgVariableFragmentInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a829b2cbe0ddacc7f79c2fc6eaba1489c">DbgVariableFragmentInfo</a> (uint64_t SizeInBits, uint64_t OffsetInBits)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0627a69223128917db3ddbeec59d0bf9">startInBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the index of the first bit of the fragment. <a href="#a0627a69223128917db3ddbeec59d0bf9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada73d0382fc8c21c8c09a675a071e1a4">endInBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the index of the bit after the end of the fragment, e.g. <a href="#ada73d0382fc8c21c8c09a675a071e1a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af581a7bb056b2b642d6705cc4af65fa2">SizeInBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa448040bf5ec2ebafc3dbe0eb15b6d55">OffsetInBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/dbgvariablefragmentinfo">DbgVariableFragmentInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa86c07e6c797389355badf65a44276f8">intersect</a> (DbgVariableFragmentInfo A, DbgVariableFragmentInfo B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a zero-sized fragment if A and B don't intersect. <a href="#aa86c07e6c797389355badf65a44276f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dbgvariablefragmentinfo-h">DbgVariableFragmentInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DbgVariableFragmentInfo() {#a5c235ba7e1d271d668371091802fc165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DbgVariableFragmentInfo::DbgVariableFragmentInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dbgvariablefragmentinfo-h">DbgVariableFragmentInfo.h</a>.</p>


<p>Referenced by <a href="#aa86c07e6c797389355badf65a44276f8">intersect</a>.</p>

</div>
</div>

### DbgVariableFragmentInfo() {#a829b2cbe0ddacc7f79c2fc6eaba1489c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DbgVariableFragmentInfo::DbgVariableFragmentInfo (uint64_t SizeInBits, uint64_t OffsetInBits)</td>
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



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dbgvariablefragmentinfo-h">DbgVariableFragmentInfo.h</a>.</p>


<p>References <a href="#aa448040bf5ec2ebafc3dbe0eb15b6d55">OffsetInBits</a> and <a href="#af581a7bb056b2b642d6705cc4af65fa2">SizeInBits</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### endInBits() {#ada73d0382fc8c21c8c09a675a071e1a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DbgVariableFragmentInfo::endInBits ()</td>
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

<p>Return the index of the bit after the end of the fragment, e.g.</p>


<p>for fragment offset=16 and size=32 return their sum, 48.</p>


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dbgvariablefragmentinfo-h">DbgVariableFragmentInfo.h</a>.</p>


<p>References <a href="#aa448040bf5ec2ebafc3dbe0eb15b6d55">OffsetInBits</a> and <a href="#af581a7bb056b2b642d6705cc4af65fa2">SizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#ad959466c7f8b886a2caa4967c46d48db">removeRedundantDbgLocsUsingBackwardScan</a>.</p>

</div>
</div>

### startInBits() {#a0627a69223128917db3ddbeec59d0bf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DbgVariableFragmentInfo::startInBits ()</td>
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

<p>Return the index of the first bit of the fragment.</p>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dbgvariablefragmentinfo-h">DbgVariableFragmentInfo.h</a>.</p>


<p>Reference <a href="#aa448040bf5ec2ebafc3dbe0eb15b6d55">OffsetInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#ad959466c7f8b886a2caa4967c46d48db">removeRedundantDbgLocsUsingBackwardScan</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### OffsetInBits {#aa448040bf5ec2ebafc3dbe0eb15b6d55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DbgVariableFragmentInfo::OffsetInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dbgvariablefragmentinfo-h">DbgVariableFragmentInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a4ea8623be899e029827af260965c860d">llvm::DIExpression::calculateFragmentIntersect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a4c75a6c6ed9dedc2ff52927972587023">createOrReplaceFragment</a>, <a href="#a829b2cbe0ddacc7f79c2fc6eaba1489c">DbgVariableFragmentInfo</a>, <a href="#ada73d0382fc8c21c8c09a675a071e1a4">endInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a16b5a4db7225864cc5615c683d946f87">llvm::DbgVariableIntrinsic::getFragmentOrEntireVariable</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-3a192aca07a75a73a86480e72b0c1ee3/#ab83e8e892a9e81bd5461dffe49fcef59">llvm::DenseMapInfo&lt; DIExpression::FragmentInfo &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a0346c3f86c714b9ae84f5566a95e90ac">migrateDebugInfo</a>, <a href="#a0627a69223128917db3ddbeec59d0bf9">startInBits</a> and <a href="/web-llvm/docs/api/classes/anonymous-verifier-cpp-/verifier/#adc56b372a24fdcb01d805b457014efb1">anonymous{Verifier.cpp}::Verifier::verifyFragmentExpression</a>.</p>

</div>
</div>

### SizeInBits {#af581a7bb056b2b642d6705cc4af65fa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DbgVariableFragmentInfo::SizeInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dbgvariablefragmentinfo-h">DbgVariableFragmentInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a4ea8623be899e029827af260965c860d">llvm::DIExpression::calculateFragmentIntersect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a4c75a6c6ed9dedc2ff52927972587023">createOrReplaceFragment</a>, <a href="#a829b2cbe0ddacc7f79c2fc6eaba1489c">DbgVariableFragmentInfo</a>, <a href="#ada73d0382fc8c21c8c09a675a071e1a4">endInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a16b5a4db7225864cc5615c683d946f87">llvm::DbgVariableIntrinsic::getFragmentOrEntireVariable</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-3a192aca07a75a73a86480e72b0c1ee3/#ab83e8e892a9e81bd5461dffe49fcef59">llvm::DenseMapInfo&lt; DIExpression::FragmentInfo &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a0346c3f86c714b9ae84f5566a95e90ac">migrateDebugInfo</a> and <a href="/web-llvm/docs/api/classes/anonymous-verifier-cpp-/verifier/#adc56b372a24fdcb01d805b457014efb1">anonymous{Verifier.cpp}::Verifier::verifyFragmentExpression</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### intersect() {#aa86c07e6c797389355badf65a44276f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgVariableFragmentInfo llvm::DbgVariableFragmentInfo::intersect (<a href="/web-llvm/docs/api/structs/llvm/dbgvariablefragmentinfo">DbgVariableFragmentInfo</a> A, <a href="/web-llvm/docs/api/structs/llvm/dbgvariablefragmentinfo">DbgVariableFragmentInfo</a> B)</td>
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

<p>Returns a zero-sized fragment if A and B don't intersect.</p>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dbgvariablefragmentinfo-h">DbgVariableFragmentInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#a5c235ba7e1d271d668371091802fc165">DbgVariableFragmentInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a4ea8623be899e029827af260965c860d">llvm::DIExpression::calculateFragmentIntersect</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dbgvariablefragmentinfo-h">DbgVariableFragmentInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
