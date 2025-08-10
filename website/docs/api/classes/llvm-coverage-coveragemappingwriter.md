---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/coverage/coveragemappingwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CoverageMappingWriter` Class

<p>Writer for instrumentation based coverage mapping data. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::coverage::CoverageMappingWriter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingwriter-h">llvm/ProfileData/Coverage/CoverageMappingWriter.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9387a1b774e1e4f5044864a01d880b00">CoverageMappingWriter</a> (ArrayRef&lt; unsigned &gt; VirtualFileMapping, ArrayRef&lt; CounterExpression &gt; Expressions, MutableArrayRef&lt; CounterMappingRegion &gt; MappingRegions)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb6fdb4ef8ee00e2c8b013def460e864">write</a> (raw_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write encoded coverage mapping data to the given output stream. <a href="#aeb6fdb4ef8ee00e2c8b013def460e864">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedf2f72d4342689cba40e63479911031">VirtualFileMapping</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/counterexpression">CounterExpression</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad20dba5c90c2b87f429f4ed51ccc01fb">Expressions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion">CounterMappingRegion</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1e9b6264fb11f3957f7fcbc9d2f91ed">MappingRegions</a></td>
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

## Description {#details}

<p>Writer for instrumentation based coverage mapping data.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingwriter-h">CoverageMappingWriter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CoverageMappingWriter() {#a9387a1b774e1e4f5044864a01d880b00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::CoverageMappingWriter::CoverageMappingWriter (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; VirtualFileMapping, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/counterexpression">CounterExpression</a> &gt; Expressions, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion">CounterMappingRegion</a> &gt; MappingRegions)</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingwriter-h">CoverageMappingWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### write() {#aeb6fdb4ef8ee00e2c8b013def460e864}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CoverageMappingWriter::write (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write encoded coverage mapping data to the given output stream.</p>

<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingwriter-h">CoverageMappingWriter.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingwriter-cpp">CoverageMappingWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion/#aef1b165905dc77f7b575797c890e9493ac60b903b2cf9a177ae32a0fda7f2f84f">llvm::coverage::CounterMappingRegion::BranchRegion</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion/#aef1b165905dc77f7b575797c890e9493ad1c0402f0bac0395dcc0cd8b0a5c43d4">llvm::coverage::CounterMappingRegion::CodeRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/counter/#a905393dc1b8fba71fedae97f1cf7cb20">llvm::coverage::Counter::EncodingCounterTagAndExpansionRegionTagBits</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/counter/#a195beefec055a20e88e7fade73e9c32f">llvm::coverage::Counter::EncodingTagBits</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion/#a0d72303e63966eeeec120113fa0a0235">llvm::coverage::CounterMappingRegion::endLoc</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion/#aef1b165905dc77f7b575797c890e9493a185ca3ad8ff2f6fefd469d805a2657fc">llvm::coverage::CounterMappingRegion::ExpansionRegion</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion/#aef1b165905dc77f7b575797c890e9493ac031257b3294c6d8ae4afab2dd9e6edf">llvm::coverage::CounterMappingRegion::GapRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion/#aef1b165905dc77f7b575797c890e9493a6b21d2e2f1eb9318cc7c562ac13639ca">llvm::coverage::CounterMappingRegion::MCDCBranchRegion</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion/#aef1b165905dc77f7b575797c890e9493a38dd41138c2bf6c5c260dd9eac4d19a8">llvm::coverage::CounterMappingRegion::MCDCDecisionRegion</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion/#aef1b165905dc77f7b575797c890e9493abbe924008d232ccec58896a8d143db42">llvm::coverage::CounterMappingRegion::SkippedRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion/#ab4defb0015a143b8f393c537400153ec">llvm::coverage::CounterMappingRegion::startLoc</a> and <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingwriter-cpp/#a338457350c63c707e699e315a98baae5">writeCounter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Expressions {#ad20dba5c90c2b87f429f4ed51ccc01fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;CounterExpression&gt; llvm::coverage::CoverageMappingWriter::Expressions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingwriter-h">CoverageMappingWriter.h</a>.</p>

</div>
</div>

### MappingRegions {#ad1e9b6264fb11f3957f7fcbc9d2f91ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MutableArrayRef&lt;CounterMappingRegion&gt; llvm::coverage::CoverageMappingWriter::MappingRegions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingwriter-h">CoverageMappingWriter.h</a>.</p>

</div>
</div>

### VirtualFileMapping {#aedf2f72d4342689cba40e63479911031}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;unsigned&gt; llvm::coverage::CoverageMappingWriter::VirtualFileMapping</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingwriter-h">CoverageMappingWriter.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemappingwriter-h">CoverageMappingWriter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingwriter-cpp">CoverageMappingWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
