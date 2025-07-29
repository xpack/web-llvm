---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/coverage/countermappingregion
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `CounterMappingRegion` Struct

<p>A <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> mapping region associates a source range with a specific counter. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::coverage::CounterMappingRegion { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">llvm/ProfileData/Coverage/CoverageMapping.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/coverage/countedregion">CountedRegion</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Associates a source range with an execution count. <a href="/web-llvm/docs/api/structs/llvm/coverage/countedregion/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">RegionKind { <a href="#aef1b165905dc77f7b575797c890e9493">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bcda64f911bd2bd33cce5728d3d8efb">CounterMappingRegion</a> (Counter Count, unsigned FileID, unsigned ExpandedFileID, unsigned LineStart, unsigned ColumnStart, unsigned LineEnd, unsigned ColumnEnd, RegionKind Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fc3f09a16e8f3be23fcede4b1634ac8">CounterMappingRegion</a> (Counter Count, Counter FalseCount, unsigned FileID, unsigned ExpandedFileID, unsigned LineStart, unsigned ColumnStart, unsigned LineEnd, unsigned ColumnEnd, RegionKind Kind, const mcdc::Parameters &amp;MCDCParams=std::monostate())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2024f965dadbe1b0f3c6ba80d9413d2f">CounterMappingRegion</a> (const mcdc::DecisionParameters &amp;MCDCParams, unsigned FileID, unsigned LineStart, unsigned ColumnStart, unsigned LineEnd, unsigned ColumnEnd, RegionKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> auto &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f65c7365a86f71000fb862c7f259223">getDecisionParams</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> auto &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf0c4b4226e115a0ad52d4ae87806243">getBranchParams</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01cce1018bae4889b2aa6b764f5dd2c5">isBranch</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/coverage/#a851320504101eab08260161f30355996">LineColPair</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4defb0015a143b8f393c537400153ec">startLoc</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/coverage/#a851320504101eab08260161f30355996">LineColPair</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d72303e63966eeeec120113fa0a0235">endLoc</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa77c2922ca094938ec101938d509723f">Count</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Primary <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> that is also used for Branch Regions (TrueCount). <a href="#aa77c2922ca094938ec101938d509723f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89fba034e57463dec3947f65afa08671">FalseCount</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Secondary <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> used for Branch Regions (FalseCount). <a href="#a89fba034e57463dec3947f65afa08671">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/coverage/mcdc/#a69d4b38eabe43090b46dd4256b0e58e5">mcdc::Parameters</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0714010bf7401f3ac8f7d0da65638ae">MCDCParams</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parameters used for Modified Condition/Decision Coverage. <a href="#ae0714010bf7401f3ac8f7d0da65638ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab8dc973b3d223db8a030b7d6e4385ec">FileID</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafa3db6cc3370280cc682b4a0974b6d2">ExpandedFileID</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad80883461d8feffbd3e462525396f7ca">LineStart</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab45f2830ff47c3602954652b3834ec86">ColumnStart</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac530127f0253ec7b901b341b2fe01e2c">LineEnd</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0db7d772272c3891e68bd972552324fb">ColumnEnd</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aef1b165905dc77f7b575797c890e9493">RegionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd8afc5a9996d26789c7ae82323b567d">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion">CounterMappingRegion</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ce3215ae14fc81d7f628f1c5a4d6a19">makeRegion</a> (Counter Count, unsigned FileID, unsigned LineStart, unsigned ColumnStart, unsigned LineEnd, unsigned ColumnEnd)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion">CounterMappingRegion</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a238390b5c1900c73f7d82d81afea36c5">makeExpansion</a> (unsigned FileID, unsigned ExpandedFileID, unsigned LineStart, unsigned ColumnStart, unsigned LineEnd, unsigned ColumnEnd)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion">CounterMappingRegion</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c152b70509800070c7c8bae35103d93">makeSkipped</a> (unsigned FileID, unsigned LineStart, unsigned ColumnStart, unsigned LineEnd, unsigned ColumnEnd)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion">CounterMappingRegion</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53de91e9193602fbb2c3440cb8274965">makeGapRegion</a> (Counter Count, unsigned FileID, unsigned LineStart, unsigned ColumnStart, unsigned LineEnd, unsigned ColumnEnd)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion">CounterMappingRegion</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad509630daf0abb6d67adffae197b5fd1">makeBranchRegion</a> (Counter Count, Counter FalseCount, unsigned FileID, unsigned LineStart, unsigned ColumnStart, unsigned LineEnd, unsigned ColumnEnd, const mcdc::Parameters &amp;MCDCParams=std::monostate())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion">CounterMappingRegion</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7825a13a454f7d3965eee6a9c7b88b94">makeDecisionRegion</a> (const mcdc::DecisionParameters &amp;MCDCParams, unsigned FileID, unsigned LineStart, unsigned ColumnStart, unsigned LineEnd, unsigned ColumnEnd)</td>
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

<p>A <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> mapping region associates a source range with a specific counter.</p>

<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### RegionKind {#aef1b165905dc77f7b575797c890e9493}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::coverage::CounterMappingRegion::RegionKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CodeRegion<a id="aef1b165905dc77f7b575797c890e9493ad1c0402f0bac0395dcc0cd8b0a5c43d4"></a></td>
<td class="doxyEnumItemDescription">A CodeRegion associates some code with a counter</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExpansionRegion<a id="aef1b165905dc77f7b575797c890e9493a185ca3ad8ff2f6fefd469d805a2657fc"></a></td>
<td class="doxyEnumItemDescription">An ExpansionRegion represents a file expansion region that associates a source range with the expansion of a virtual source file, such as for a macro instantiation or #include file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SkippedRegion<a id="aef1b165905dc77f7b575797c890e9493abbe924008d232ccec58896a8d143db42"></a></td>
<td class="doxyEnumItemDescription">A SkippedRegion represents a source range with code that was skipped by a preprocessor or similar means</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GapRegion<a id="aef1b165905dc77f7b575797c890e9493ac031257b3294c6d8ae4afab2dd9e6edf"></a></td>
<td class="doxyEnumItemDescription">A GapRegion is like a CodeRegion, but its count is only set as the line execution count when its the only region in the line</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BranchRegion<a id="aef1b165905dc77f7b575797c890e9493ac60b903b2cf9a177ae32a0fda7f2f84f"></a></td>
<td class="doxyEnumItemDescription">A BranchRegion represents leaf-level boolean expressions and is associated with two counters, each representing the number of times the expression evaluates to true or false</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MCDCDecisionRegion<a id="aef1b165905dc77f7b575797c890e9493a38dd41138c2bf6c5c260dd9eac4d19a8"></a></td>
<td class="doxyEnumItemDescription">A DecisionRegion represents a top-level boolean expression and is associated with a variable length bitmap index and condition number</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MCDCBranchRegion<a id="aef1b165905dc77f7b575797c890e9493a6b21d2e2f1eb9318cc7c562ac13639ca"></a></td>
<td class="doxyEnumItemDescription">A Branch <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> can be extended to include IDs to facilitate MC/DC</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CounterMappingRegion() {#a5bcda64f911bd2bd33cce5728d3d8efb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::CounterMappingRegion::CounterMappingRegion (<a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> Count, unsigned FileID, unsigned ExpandedFileID, unsigned LineStart, unsigned ColumnStart, unsigned LineEnd, unsigned ColumnEnd, <a href="#aef1b165905dc77f7b575797c890e9493">RegionKind</a> Kind)</td>
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



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>References <a href="#a0db7d772272c3891e68bd972552324fb">ColumnEnd</a>, <a href="#ab45f2830ff47c3602954652b3834ec86">ColumnStart</a>, <a href="#aa77c2922ca094938ec101938d509723f">Count</a>, <a href="#aafa3db6cc3370280cc682b4a0974b6d2">ExpandedFileID</a>, <a href="#aab8dc973b3d223db8a030b7d6e4385ec">FileID</a>, <a href="#acd8afc5a9996d26789c7ae82323b567d">Kind</a>, <a href="#ac530127f0253ec7b901b341b2fe01e2c">LineEnd</a> and <a href="#ad80883461d8feffbd3e462525396f7ca">LineStart</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/coverage/countedregion/#a646c15f9f114086b0a3d8d035b6bf81d">llvm::coverage::CountedRegion::CountedRegion</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/countedregion/#a62c99b7e871476e501c97e7a5f353b74">llvm::coverage::CountedRegion::CountedRegion</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/covmapfunctionrecordv1/#ad62a9b278fc0ad41d44334a23f787c05">llvm::coverage::CovMapFunctionRecordV1&lt; IntPtrT &gt;::COVINIT_FUNC</a>, <a href="#ad509630daf0abb6d67adffae197b5fd1">makeBranchRegion</a>, <a href="#a7825a13a454f7d3965eee6a9c7b88b94">makeDecisionRegion</a>, <a href="#a238390b5c1900c73f7d82d81afea36c5">makeExpansion</a>, <a href="#a53de91e9193602fbb2c3440cb8274965">makeGapRegion</a> and <a href="#a9c152b70509800070c7c8bae35103d93">makeSkipped</a>.</p>

</div>
</div>

### CounterMappingRegion() {#a5fc3f09a16e8f3be23fcede4b1634ac8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::CounterMappingRegion::CounterMappingRegion (<a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> Count, <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> FalseCount, unsigned FileID, unsigned ExpandedFileID, unsigned LineStart, unsigned ColumnStart, unsigned LineEnd, unsigned ColumnEnd, <a href="#aef1b165905dc77f7b575797c890e9493">RegionKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/coverage/mcdc/#a69d4b38eabe43090b46dd4256b0e58e5">mcdc::Parameters</a> &amp; MCDCParams=std::monostate())</td>
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



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>References <a href="#aa77c2922ca094938ec101938d509723f">Count</a>, <a href="#a89fba034e57463dec3947f65afa08671">FalseCount</a> and <a href="#aab8dc973b3d223db8a030b7d6e4385ec">FileID</a>.</p>

</div>
</div>

### CounterMappingRegion() {#a2024f965dadbe1b0f3c6ba80d9413d2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::CounterMappingRegion::CounterMappingRegion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/mcdc/decisionparameters">mcdc::DecisionParameters</a> &amp; MCDCParams, unsigned FileID, unsigned LineStart, unsigned ColumnStart, unsigned LineEnd, unsigned ColumnEnd, <a href="#aef1b165905dc77f7b575797c890e9493">RegionKind</a> Kind)</td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>References <a href="#a0db7d772272c3891e68bd972552324fb">ColumnEnd</a>, <a href="#ab45f2830ff47c3602954652b3834ec86">ColumnStart</a>, <a href="#aab8dc973b3d223db8a030b7d6e4385ec">FileID</a>, <a href="#acd8afc5a9996d26789c7ae82323b567d">Kind</a>, <a href="#ac530127f0253ec7b901b341b2fe01e2c">LineEnd</a>, <a href="#ad80883461d8feffbd3e462525396f7ca">LineStart</a> and <a href="#ae0714010bf7401f3ac8f7d0da65638ae">MCDCParams</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### endLoc() {#a0d72303e63966eeeec120113fa0a0235}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LineColPair llvm::coverage::CounterMappingRegion::endLoc ()</td>
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



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>References <a href="#a0db7d772272c3891e68bd972552324fb">ColumnEnd</a> and <a href="#ac530127f0253ec7b901b341b2fe01e2c">LineEnd</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coverage/coveragemappingwriter/#aeb6fdb4ef8ee00e2c8b013def460e864">llvm::coverage::CoverageMappingWriter::write</a>.</p>

</div>
</div>

### getBranchParams() {#abf0c4b4226e115a0ad52d4ae87806243}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const auto &amp; llvm::coverage::CounterMappingRegion::getBranchParams ()</td>
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



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### getDecisionParams() {#a1f65c7365a86f71000fb862c7f259223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const auto &amp; llvm::coverage::CounterMappingRegion::getDecisionParams ()</td>
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



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### isBranch() {#a01cce1018bae4889b2aa6b764f5dd2c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::coverage::CounterMappingRegion::isBranch ()</td>
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



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>References <a href="#aef1b165905dc77f7b575797c890e9493ac60b903b2cf9a177ae32a0fda7f2f84f">BranchRegion</a>, <a href="#acd8afc5a9996d26789c7ae82323b567d">Kind</a> and <a href="#aef1b165905dc77f7b575797c890e9493a6b21d2e2f1eb9318cc7c562ac13639ca">MCDCBranchRegion</a>.</p>

</div>
</div>

### startLoc() {#ab4defb0015a143b8f393c537400153ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LineColPair llvm::coverage::CounterMappingRegion::startLoc ()</td>
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



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>References <a href="#ab45f2830ff47c3602954652b3834ec86">ColumnStart</a> and <a href="#ad80883461d8feffbd3e462525396f7ca">LineStart</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coverage/coveragemappingwriter/#aeb6fdb4ef8ee00e2c8b013def460e864">llvm::coverage::CoverageMappingWriter::write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ColumnEnd {#a0db7d772272c3891e68bd972552324fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::coverage::CounterMappingRegion::ColumnEnd</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Referenced by <a href="#a2024f965dadbe1b0f3c6ba80d9413d2f">CounterMappingRegion</a>, <a href="#a5bcda64f911bd2bd33cce5728d3d8efb">CounterMappingRegion</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/covmapfunctionrecordv1/#ad62a9b278fc0ad41d44334a23f787c05">llvm::coverage::CovMapFunctionRecordV1&lt; IntPtrT &gt;::COVINIT_FUNC</a>, <a href="#a0d72303e63966eeeec120113fa0a0235">endLoc</a>, <a href="#ad509630daf0abb6d67adffae197b5fd1">makeBranchRegion</a>, <a href="#a7825a13a454f7d3965eee6a9c7b88b94">makeDecisionRegion</a>, <a href="#a238390b5c1900c73f7d82d81afea36c5">makeExpansion</a>, <a href="#a53de91e9193602fbb2c3440cb8274965">makeGapRegion</a> and <a href="#a9c152b70509800070c7c8bae35103d93">makeSkipped</a>.</p>

</div>
</div>

### ColumnStart {#ab45f2830ff47c3602954652b3834ec86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::coverage::CounterMappingRegion::ColumnStart</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Referenced by <a href="#a2024f965dadbe1b0f3c6ba80d9413d2f">CounterMappingRegion</a>, <a href="#a5bcda64f911bd2bd33cce5728d3d8efb">CounterMappingRegion</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/covmapfunctionrecordv1/#ad62a9b278fc0ad41d44334a23f787c05">llvm::coverage::CovMapFunctionRecordV1&lt; IntPtrT &gt;::COVINIT_FUNC</a>, <a href="#ad509630daf0abb6d67adffae197b5fd1">makeBranchRegion</a>, <a href="#a7825a13a454f7d3965eee6a9c7b88b94">makeDecisionRegion</a>, <a href="#a238390b5c1900c73f7d82d81afea36c5">makeExpansion</a>, <a href="#a53de91e9193602fbb2c3440cb8274965">makeGapRegion</a>, <a href="#a9c152b70509800070c7c8bae35103d93">makeSkipped</a> and <a href="#ab4defb0015a143b8f393c537400153ec">startLoc</a>.</p>

</div>
</div>

### Count {#aa77c2922ca094938ec101938d509723f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Counter llvm::coverage::CounterMappingRegion::Count</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Primary <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> that is also used for Branch Regions (TrueCount).</p>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Referenced by <a href="#a5fc3f09a16e8f3be23fcede4b1634ac8">CounterMappingRegion</a>, <a href="#a5bcda64f911bd2bd33cce5728d3d8efb">CounterMappingRegion</a>, <a href="#ad509630daf0abb6d67adffae197b5fd1">makeBranchRegion</a> and <a href="#a53de91e9193602fbb2c3440cb8274965">makeGapRegion</a>.</p>

</div>
</div>

### ExpandedFileID {#aafa3db6cc3370280cc682b4a0974b6d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::coverage::CounterMappingRegion::ExpandedFileID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Referenced by <a href="#a5bcda64f911bd2bd33cce5728d3d8efb">CounterMappingRegion</a> and <a href="#a238390b5c1900c73f7d82d81afea36c5">makeExpansion</a>.</p>

</div>
</div>

### FalseCount {#a89fba034e57463dec3947f65afa08671}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Counter llvm::coverage::CounterMappingRegion::FalseCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Secondary <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> used for Branch Regions (FalseCount).</p>

<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Referenced by <a href="#a5fc3f09a16e8f3be23fcede4b1634ac8">CounterMappingRegion</a> and <a href="#ad509630daf0abb6d67adffae197b5fd1">makeBranchRegion</a>.</p>

</div>
</div>

### FileID {#aab8dc973b3d223db8a030b7d6e4385ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::coverage::CounterMappingRegion::FileID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Referenced by <a href="#a2024f965dadbe1b0f3c6ba80d9413d2f">CounterMappingRegion</a>, <a href="#a5fc3f09a16e8f3be23fcede4b1634ac8">CounterMappingRegion</a>, <a href="#a5bcda64f911bd2bd33cce5728d3d8efb">CounterMappingRegion</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/covmapfunctionrecordv1/#ad62a9b278fc0ad41d44334a23f787c05">llvm::coverage::CovMapFunctionRecordV1&lt; IntPtrT &gt;::COVINIT_FUNC</a>, <a href="#ad509630daf0abb6d67adffae197b5fd1">makeBranchRegion</a>, <a href="#a7825a13a454f7d3965eee6a9c7b88b94">makeDecisionRegion</a>, <a href="#a238390b5c1900c73f7d82d81afea36c5">makeExpansion</a>, <a href="#a53de91e9193602fbb2c3440cb8274965">makeGapRegion</a> and <a href="#a9c152b70509800070c7c8bae35103d93">makeSkipped</a>.</p>

</div>
</div>

### Kind {#acd8afc5a9996d26789c7ae82323b567d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionKind llvm::coverage::CounterMappingRegion::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Referenced by <a href="#a2024f965dadbe1b0f3c6ba80d9413d2f">CounterMappingRegion</a>, <a href="#a5bcda64f911bd2bd33cce5728d3d8efb">CounterMappingRegion</a> and <a href="#a01cce1018bae4889b2aa6b764f5dd2c5">isBranch</a>.</p>

</div>
</div>

### LineEnd {#ac530127f0253ec7b901b341b2fe01e2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::coverage::CounterMappingRegion::LineEnd</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Referenced by <a href="#a2024f965dadbe1b0f3c6ba80d9413d2f">CounterMappingRegion</a>, <a href="#a5bcda64f911bd2bd33cce5728d3d8efb">CounterMappingRegion</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/covmapfunctionrecordv1/#ad62a9b278fc0ad41d44334a23f787c05">llvm::coverage::CovMapFunctionRecordV1&lt; IntPtrT &gt;::COVINIT_FUNC</a>, <a href="#a0d72303e63966eeeec120113fa0a0235">endLoc</a>, <a href="#ad509630daf0abb6d67adffae197b5fd1">makeBranchRegion</a>, <a href="#a7825a13a454f7d3965eee6a9c7b88b94">makeDecisionRegion</a>, <a href="#a238390b5c1900c73f7d82d81afea36c5">makeExpansion</a>, <a href="#a53de91e9193602fbb2c3440cb8274965">makeGapRegion</a> and <a href="#a9c152b70509800070c7c8bae35103d93">makeSkipped</a>.</p>

</div>
</div>

### LineStart {#ad80883461d8feffbd3e462525396f7ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::coverage::CounterMappingRegion::LineStart</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Referenced by <a href="#a2024f965dadbe1b0f3c6ba80d9413d2f">CounterMappingRegion</a>, <a href="#a5bcda64f911bd2bd33cce5728d3d8efb">CounterMappingRegion</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/covmapfunctionrecordv1/#ad62a9b278fc0ad41d44334a23f787c05">llvm::coverage::CovMapFunctionRecordV1&lt; IntPtrT &gt;::COVINIT_FUNC</a>, <a href="#ad509630daf0abb6d67adffae197b5fd1">makeBranchRegion</a>, <a href="#a7825a13a454f7d3965eee6a9c7b88b94">makeDecisionRegion</a>, <a href="#a238390b5c1900c73f7d82d81afea36c5">makeExpansion</a>, <a href="#a53de91e9193602fbb2c3440cb8274965">makeGapRegion</a>, <a href="#a9c152b70509800070c7c8bae35103d93">makeSkipped</a> and <a href="#ab4defb0015a143b8f393c537400153ec">startLoc</a>.</p>

</div>
</div>

### MCDCParams {#ae0714010bf7401f3ac8f7d0da65638ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mcdc::Parameters llvm::coverage::CounterMappingRegion::MCDCParams</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parameters used for Modified Condition/Decision Coverage.</p>

<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Referenced by <a href="#a2024f965dadbe1b0f3c6ba80d9413d2f">CounterMappingRegion</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/covmapfunctionrecordv1/#a2cd7e3ebab3ab6a5e71ba44f2f15f8ce">llvm::coverage::CovMapFunctionRecordV1&lt; IntPtrT &gt;::llvm::ConstantInt::get</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/covmapfunctionrecordv3/#a7df0a592066717b892253387fe3f418c">llvm::coverage::CovMapFunctionRecordV3::llvm::ConstantInt::get</a>, <a href="#ad509630daf0abb6d67adffae197b5fd1">makeBranchRegion</a> and <a href="#a7825a13a454f7d3965eee6a9c7b88b94">makeDecisionRegion</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### makeBranchRegion() {#ad509630daf0abb6d67adffae197b5fd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CounterMappingRegion llvm::coverage::CounterMappingRegion::makeBranchRegion (<a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> Count, <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> FalseCount, unsigned FileID, unsigned LineStart, unsigned ColumnStart, unsigned LineEnd, unsigned ColumnEnd, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/coverage/mcdc/#a69d4b38eabe43090b46dd4256b0e58e5">mcdc::Parameters</a> &amp; MCDCParams=std::monostate())</td>
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



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>References <a href="#aef1b165905dc77f7b575797c890e9493ac60b903b2cf9a177ae32a0fda7f2f84f">BranchRegion</a>, <a href="#a0db7d772272c3891e68bd972552324fb">ColumnEnd</a>, <a href="#ab45f2830ff47c3602954652b3834ec86">ColumnStart</a>, <a href="#aa77c2922ca094938ec101938d509723f">Count</a>, <a href="#a5bcda64f911bd2bd33cce5728d3d8efb">CounterMappingRegion</a>, <a href="#a89fba034e57463dec3947f65afa08671">FalseCount</a>, <a href="#aab8dc973b3d223db8a030b7d6e4385ec">FileID</a>, <a href="#ac530127f0253ec7b901b341b2fe01e2c">LineEnd</a>, <a href="#ad80883461d8feffbd3e462525396f7ca">LineStart</a>, <a href="#aef1b165905dc77f7b575797c890e9493a6b21d2e2f1eb9318cc7c562ac13639ca">MCDCBranchRegion</a> and <a href="#ae0714010bf7401f3ac8f7d0da65638ae">MCDCParams</a>.</p>

</div>
</div>

### makeDecisionRegion() {#a7825a13a454f7d3965eee6a9c7b88b94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CounterMappingRegion llvm::coverage::CounterMappingRegion::makeDecisionRegion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/mcdc/decisionparameters">mcdc::DecisionParameters</a> &amp; MCDCParams, unsigned FileID, unsigned LineStart, unsigned ColumnStart, unsigned LineEnd, unsigned ColumnEnd)</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>References <a href="#a0db7d772272c3891e68bd972552324fb">ColumnEnd</a>, <a href="#ab45f2830ff47c3602954652b3834ec86">ColumnStart</a>, <a href="#a5bcda64f911bd2bd33cce5728d3d8efb">CounterMappingRegion</a>, <a href="#aab8dc973b3d223db8a030b7d6e4385ec">FileID</a>, <a href="#ac530127f0253ec7b901b341b2fe01e2c">LineEnd</a>, <a href="#ad80883461d8feffbd3e462525396f7ca">LineStart</a>, <a href="#aef1b165905dc77f7b575797c890e9493a38dd41138c2bf6c5c260dd9eac4d19a8">MCDCDecisionRegion</a> and <a href="#ae0714010bf7401f3ac8f7d0da65638ae">MCDCParams</a>.</p>

</div>
</div>

### makeExpansion() {#a238390b5c1900c73f7d82d81afea36c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CounterMappingRegion llvm::coverage::CounterMappingRegion::makeExpansion (unsigned FileID, unsigned ExpandedFileID, unsigned LineStart, unsigned ColumnStart, unsigned LineEnd, unsigned ColumnEnd)</td>
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



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>References <a href="#a0db7d772272c3891e68bd972552324fb">ColumnEnd</a>, <a href="#ab45f2830ff47c3602954652b3834ec86">ColumnStart</a>, <a href="#a5bcda64f911bd2bd33cce5728d3d8efb">CounterMappingRegion</a>, <a href="#aafa3db6cc3370280cc682b4a0974b6d2">ExpandedFileID</a>, <a href="#aef1b165905dc77f7b575797c890e9493a185ca3ad8ff2f6fefd469d805a2657fc">ExpansionRegion</a>, <a href="#aab8dc973b3d223db8a030b7d6e4385ec">FileID</a>, <a href="#ac530127f0253ec7b901b341b2fe01e2c">LineEnd</a> and <a href="#ad80883461d8feffbd3e462525396f7ca">LineStart</a>.</p>

</div>
</div>

### makeGapRegion() {#a53de91e9193602fbb2c3440cb8274965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CounterMappingRegion llvm::coverage::CounterMappingRegion::makeGapRegion (<a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> Count, unsigned FileID, unsigned LineStart, unsigned ColumnStart, unsigned LineEnd, unsigned ColumnEnd)</td>
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



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>References <a href="#a0db7d772272c3891e68bd972552324fb">ColumnEnd</a>, <a href="#ab45f2830ff47c3602954652b3834ec86">ColumnStart</a>, <a href="#aa77c2922ca094938ec101938d509723f">Count</a>, <a href="#a5bcda64f911bd2bd33cce5728d3d8efb">CounterMappingRegion</a>, <a href="#aab8dc973b3d223db8a030b7d6e4385ec">FileID</a>, <a href="#aef1b165905dc77f7b575797c890e9493ac031257b3294c6d8ae4afab2dd9e6edf">GapRegion</a>, <a href="#ac530127f0253ec7b901b341b2fe01e2c">LineEnd</a> and <a href="#ad80883461d8feffbd3e462525396f7ca">LineStart</a>.</p>

</div>
</div>

### makeRegion() {#a6ce3215ae14fc81d7f628f1c5a4d6a19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CounterMappingRegion llvm::coverage::CounterMappingRegion::makeRegion (<a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> Count, unsigned FileID, unsigned LineStart, unsigned ColumnStart, unsigned LineEnd, unsigned ColumnEnd)</td>
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



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### makeSkipped() {#a9c152b70509800070c7c8bae35103d93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CounterMappingRegion llvm::coverage::CounterMappingRegion::makeSkipped (unsigned FileID, unsigned LineStart, unsigned ColumnStart, unsigned LineEnd, unsigned ColumnEnd)</td>
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



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>References <a href="#a0db7d772272c3891e68bd972552324fb">ColumnEnd</a>, <a href="#ab45f2830ff47c3602954652b3834ec86">ColumnStart</a>, <a href="#a5bcda64f911bd2bd33cce5728d3d8efb">CounterMappingRegion</a>, <a href="#aab8dc973b3d223db8a030b7d6e4385ec">FileID</a>, <a href="#ac530127f0253ec7b901b341b2fe01e2c">LineEnd</a>, <a href="#ad80883461d8feffbd3e462525396f7ca">LineStart</a> and <a href="#aef1b165905dc77f7b575797c890e9493abbe924008d232ccec58896a8d143db42">SkippedRegion</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
