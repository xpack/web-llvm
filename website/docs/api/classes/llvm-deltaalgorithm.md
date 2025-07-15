---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/deltaalgorithm
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DeltaAlgorithm` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/deltaalgorithm">DeltaAlgorithm</a> - Implements the delta debugging algorithm (A. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DeltaAlgorithm { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltaalgorithm-h">llvm/ADT/DeltaAlgorithm.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-dagdeltaalgorithm-cpp-/deltaactivesethelper">DeltaActiveSetHelper</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper object for minimizing an active set of changes. <a href="/web-llvm/docs/api/classes/anonymous-dagdeltaalgorithm-cpp-/deltaactivesethelper/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb9e4955bc1f21948d50a2deb67fb126">change_ty</a> = unsigned</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbeb2e02b90b33dba5a8b124fbda75d9">changeset_ty</a> = std::set&lt; <a href="#adb9e4955bc1f21948d50a2deb67fb126">change_ty</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeada9341c197ace7a6f1a43e4b26a146">changesetlist_ty</a> = std::vector&lt; <a href="#adbeb2e02b90b33dba5a8b124fbda75d9">changeset_ty</a> &gt;</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa00557f6b44542dd35644d92b3ccbf7c">~DeltaAlgorithm</a> ()</td>
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

## Protected Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/deltaalgorithm">DeltaAlgorithm</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff14a0466e1fddc926a74cf8a8a12f24">operator=</a> (const DeltaAlgorithm &amp;)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adbeb2e02b90b33dba5a8b124fbda75d9">changeset_ty</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac831b25db9dec0663d1d058f1a37329b">Run</a> (const changeset_ty &amp;Changes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run - Minimize the set <span class="doxyComputerOutput">Changes</span> by executing. <a href="#ac831b25db9dec0663d1d058f1a37329b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad33336a49a922268e9656bc2398f299">UpdatedSearchState</a> (const changeset_ty &amp;Changes, const changesetlist_ty &amp;Sets)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>UpdatedSearchState - Callback used when the search state changes. <a href="#aad33336a49a922268e9656bc2398f299">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17c6736f097dc721905d5b063a4e8bc3">ExecuteOneTest</a> (const changeset_ty &amp;S)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ExecuteOneTest - Execute a single test predicate on the change set <span class="doxyComputerOutput">S</span>. <a href="#a17c6736f097dc721905d5b063a4e8bc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab93fb2b54bca7311555d68435449c582">GetTestResult</a> (const changeset_ty &amp;Changes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetTestResult - Get the test result for the <span class="doxyComputerOutput">Changes</span> from the cache, executing the test if necessary. <a href="#ab93fb2b54bca7311555d68435449c582">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af75c494859f4554f063d454df3423443">Split</a> (const changeset_ty &amp;S, changesetlist_ty &amp;Res)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split - Partition a set of changes <span class="doxyComputerOutput">S</span> into one or two subsets. <a href="#af75c494859f4554f063d454df3423443">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adbeb2e02b90b33dba5a8b124fbda75d9">changeset_ty</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e5fa7e10cf3447a663c5d3f0c2415a3">Delta</a> (const changeset_ty &amp;Changes, const changesetlist_ty &amp;Sets)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Delta - Minimize a set of <span class="doxyComputerOutput">Changes</span> which has been partitioned into smaller sets, by attempting to remove individual subsets. <a href="#a9e5fa7e10cf3447a663c5d3f0c2415a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ec655e24da5d252d2e72f2ce113d360">Search</a> (const changeset_ty &amp;Changes, const changesetlist_ty &amp;Sets, changeset_ty &amp;Res)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search - Search for a subset (or subsets) in <span class="doxyComputerOutput">Sets</span> which can be removed from <span class="doxyComputerOutput">Changes</span> while still satisfying the predicate. <a href="#a7ec655e24da5d252d2e72f2ce113d360">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::set&lt; <a href="#adbeb2e02b90b33dba5a8b124fbda75d9">changeset_ty</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b4be4d615b9aa0a91554b2b1a8d27af">FailedTestsCache</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache of failed test results. <a href="#a8b4be4d615b9aa0a91554b2b1a8d27af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/deltaalgorithm">DeltaAlgorithm</a> - Implements the delta debugging algorithm (A.</p>


<p>Zeller '99) for minimizing arbitrary sets using a predicate function.</p>


<p>The result of the algorithm is a subset of the input change set which is guaranteed to satisfy the predicate, assuming that the input set did. For well formed predicates, the result set is guaranteed to be such that removing any single element would falsify the predicate.</p>


<p>For best results the predicate function <em>should</em> (but need not) satisfy certain properties, in particular: (1) The predicate should return false on an empty set and true on the full set. (2) If the predicate returns true for a set of changes, it should return true for all supersets of that set.</p>


<p>It is not an error to provide a predicate that does not satisfy these requirements, and the algorithm will generally produce reasonable results. However, it may run substantially more tests than with a good predicate.</p>


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltaalgorithm-h">DeltaAlgorithm.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### change\_ty {#adb9e4955bc1f21948d50a2deb67fb126}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DeltaAlgorithm::change_ty =  unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltaalgorithm-h">DeltaAlgorithm.h</a>.</p>

</div>
</div>

### changeset\_ty {#adbeb2e02b90b33dba5a8b124fbda75d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DeltaAlgorithm::changeset_ty =  std::set&lt;change_ty&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltaalgorithm-h">DeltaAlgorithm.h</a>.</p>

</div>
</div>

### changesetlist\_ty {#aeada9341c197ace7a6f1a43e4b26a146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DeltaAlgorithm::changesetlist_ty =  std::vector&lt;changeset_ty&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltaalgorithm-h">DeltaAlgorithm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DeltaAlgorithm() {#aa00557f6b44542dd35644d92b3ccbf7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DeltaAlgorithm::~DeltaAlgorithm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltaalgorithm-h">DeltaAlgorithm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Operators

### operator=() {#aff14a0466e1fddc926a74cf8a8a12f24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DeltaAlgorithm &amp; llvm::DeltaAlgorithm::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/deltaalgorithm">DeltaAlgorithm</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltaalgorithm-h">DeltaAlgorithm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Run() {#ac831b25db9dec0663d1d058f1a37329b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DeltaAlgorithm::changeset_ty DeltaAlgorithm::Run (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#adbeb2e02b90b33dba5a8b124fbda75d9">changeset_ty</a> &amp; Changes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run - Minimize the set <span class="doxyComputerOutput">Changes</span> by executing.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a17c6736f097dc721905d5b063a4e8bc3">ExecuteOneTest()</a> on subsets of changes and returning the smallest set which still satisfies the <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp/#a106e32122c569cdb42ddf61ecbb0aad1">test</a> predicate.</p></dd>
</dl>


<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltaalgorithm-h">DeltaAlgorithm.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltaalgorithm-cpp">DeltaAlgorithm.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### ExecuteOneTest() {#a17c6736f097dc721905d5b063a4e8bc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::DeltaAlgorithm::ExecuteOneTest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#adbeb2e02b90b33dba5a8b124fbda75d9">changeset_ty</a> &amp; S)</td>
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

<p>ExecuteOneTest - Execute a single test predicate on the change set <span class="doxyComputerOutput">S</span>.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltaalgorithm-h">DeltaAlgorithm.h</a>.</p>

</div>
</div>

### UpdatedSearchState() {#aad33336a49a922268e9656bc2398f299}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::DeltaAlgorithm::UpdatedSearchState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#adbeb2e02b90b33dba5a8b124fbda75d9">changeset_ty</a> &amp; Changes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aeada9341c197ace7a6f1a43e4b26a146">changesetlist_ty</a> &amp; Sets)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>UpdatedSearchState - Callback used when the search state changes.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltaalgorithm-h">DeltaAlgorithm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### Delta() {#a9e5fa7e10cf3447a663c5d3f0c2415a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DeltaAlgorithm::changeset_ty DeltaAlgorithm::Delta (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#adbeb2e02b90b33dba5a8b124fbda75d9">changeset_ty</a> &amp; Changes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aeada9341c197ace7a6f1a43e4b26a146">changesetlist_ty</a> &amp; Sets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Delta - Minimize a set of <span class="doxyComputerOutput">Changes</span> which has been partitioned into smaller sets, by attempting to remove individual subsets.</p>

<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltaalgorithm-h">DeltaAlgorithm.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltaalgorithm-cpp">DeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### GetTestResult() {#ab93fb2b54bca7311555d68435449c582}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DeltaAlgorithm::GetTestResult (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#adbeb2e02b90b33dba5a8b124fbda75d9">changeset_ty</a> &amp; Changes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GetTestResult - Get the test result for the <span class="doxyComputerOutput">Changes</span> from the cache, executing the test if necessary.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Changes</td>
<td class="doxyParamItemDescription"><p>- The change set to test.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- The test result.</p></dd>
</dl>


<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltaalgorithm-h">DeltaAlgorithm.h</a>, definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltaalgorithm-cpp">DeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### Search() {#a7ec655e24da5d252d2e72f2ce113d360}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DeltaAlgorithm::Search (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#adbeb2e02b90b33dba5a8b124fbda75d9">changeset_ty</a> &amp; Changes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aeada9341c197ace7a6f1a43e4b26a146">changesetlist_ty</a> &amp; Sets, <a href="#adbeb2e02b90b33dba5a8b124fbda75d9">changeset_ty</a> &amp; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Search - Search for a subset (or subsets) in <span class="doxyComputerOutput">Sets</span> which can be removed from <span class="doxyComputerOutput">Changes</span> while still satisfying the predicate.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Res</td>
<td class="doxyParamItemDescription"><p>- On success, a subset of Changes which satisfies the predicate.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- True on success.</p></dd>
</dl>


<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltaalgorithm-h">DeltaAlgorithm.h</a>, definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltaalgorithm-cpp">DeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### Split() {#af75c494859f4554f063d454df3423443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DeltaAlgorithm::Split (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#adbeb2e02b90b33dba5a8b124fbda75d9">changeset_ty</a> &amp; S, <a href="#aeada9341c197ace7a6f1a43e4b26a146">changesetlist_ty</a> &amp; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Split - Partition a set of changes <span class="doxyComputerOutput">S</span> into one or two subsets.</p>

<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltaalgorithm-h">DeltaAlgorithm.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltaalgorithm-cpp">DeltaAlgorithm.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FailedTestsCache {#a8b4be4d615b9aa0a91554b2b1a8d27af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt;changeset_ty&gt; llvm::DeltaAlgorithm::FailedTestsCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cache of failed test results.</p>


<p>Successful test results are never cached since we always reduce following a success.</p>


<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltaalgorithm-h">DeltaAlgorithm.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltaalgorithm-h">DeltaAlgorithm.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/deltaalgorithm-cpp">DeltaAlgorithm.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
