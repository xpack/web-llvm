---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/valueprofilecollector
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ValueProfileCollector` Class

<p>Utility analysis that determines what values are worth profiling. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ValueProfileCollector { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/valueprofilecollector-h">Transforms/Instrumentation/ValueProfileCollector.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50d7cc1c6703d27214c819133e2f1c2d">ValueProfileCollector</a> (Function &amp;Fn, TargetLibraryInfo &amp;TLI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab95bf7037940be7329308cfb90c0b724">ValueProfileCollector</a> (ValueProfileCollector &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fbfb13e2bd71b792b862ff8a84ec9e0">ValueProfileCollector</a> (const ValueProfileCollector &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0073f9fb1fa718484c55b00335021d99">~ValueProfileCollector</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valueprofilecollector">ValueProfileCollector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade9ce0d51f3ceee8fbd4179628c50d60">operator=</a> (ValueProfileCollector &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valueprofilecollector">ValueProfileCollector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f73ce8c3bf35e72afeab96ed9bcbc28">operator=</a> (const ValueProfileCollector &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/valueprofilecollector/candidateinfo">CandidateInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9051f7b5cb39eaecf1a333768670f72f">get</a> (InstrProfValueKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns a list of value profiling candidates of the given kind <a href="#a9051f7b5cb39eaecf1a333768670f72f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/valueprofilecollector/valueprofilecollectorimpl">ValueProfileCollectorImpl</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9e1eb306272e7159c228b796fdf2fdd">PImpl</a></td>
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

<p>Utility analysis that determines what values are worth profiling.</p>


<p>The actual logic is inside the <a href="/web-llvm/docs/api/classes/valueprofilecollector/valueprofilecollectorimpl">ValueProfileCollectorImpl</a>, whose job is to populate the Candidates vector.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> profiling an expression means to track the values that this expression takes at runtime and the frequency of each value. It is important to distinguish between two sets of value profiles for a particular expression: 1) The set of values at the point of evaluation. 2) The set of values at the point of use. In some cases, the two sets are identical, but it's not unusual for the two to differ.</p>


<p>To elaborate more, consider this C code, and focus on the expression <span class="doxyComputerOutput">nn</span>: void foo(int nn, bool b) { if (b) memcpy(x, y, nn); } The point of evaluation can be as early as the start of the function, and let's say the value profile for <span class="doxyComputerOutput">nn</span> is: total=100; (value,freq) set = {(8,10), (32,50)} The point of use is right before we call memcpy, and since we execute the memcpy conditionally, the value profile of <span class="doxyComputerOutput">nn</span> can be: total=15; (value,freq) set = {(8,10), (4,5)}</p>


<p>For this reason, a plugin is responsible for computing the insertion point for each value to be profiled. The <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/valueprofilecollector/candidateinfo">CandidateInfo</a></span> structure encapsulates all the information needed for each value profile site.</p>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/valueprofilecollector-h">ValueProfileCollector.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ValueProfileCollector() {#a50d7cc1c6703d27214c819133e2f1c2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueProfileCollector::ValueProfileCollector (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/valueprofilecollector-h">ValueProfileCollector.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/valueprofilecollector-cpp">ValueProfileCollector.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#a7f73ce8c3bf35e72afeab96ed9bcbc28">operator=</a>, <a href="#ade9ce0d51f3ceee8fbd4179628c50d60">operator=</a>, <a href="#a2fbfb13e2bd71b792b862ff8a84ec9e0">ValueProfileCollector</a> and <a href="#ab95bf7037940be7329308cfb90c0b724">ValueProfileCollector</a>.</p>

</div>
</div>

### ValueProfileCollector() {#ab95bf7037940be7329308cfb90c0b724}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ValueProfileCollector::ValueProfileCollector (<a href="/web-llvm/docs/api/classes/llvm/valueprofilecollector">ValueProfileCollector</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/valueprofilecollector-h">ValueProfileCollector.h</a>.</p>


<p>Reference <a href="#a50d7cc1c6703d27214c819133e2f1c2d">ValueProfileCollector</a>.</p>

</div>
</div>

### ValueProfileCollector() {#a2fbfb13e2bd71b792b862ff8a84ec9e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ValueProfileCollector::ValueProfileCollector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valueprofilecollector">ValueProfileCollector</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/valueprofilecollector-h">ValueProfileCollector.h</a>.</p>


<p>Reference <a href="#a50d7cc1c6703d27214c819133e2f1c2d">ValueProfileCollector</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ValueProfileCollector() {#a0073f9fb1fa718484c55b00335021d99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueProfileCollector::~ValueProfileCollector ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/valueprofilecollector-h">ValueProfileCollector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ade9ce0d51f3ceee8fbd4179628c50d60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueProfileCollector &amp; llvm::ValueProfileCollector::operator= (<a href="/web-llvm/docs/api/classes/llvm/valueprofilecollector">ValueProfileCollector</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/valueprofilecollector-h">ValueProfileCollector.h</a>.</p>


<p>Reference <a href="#a50d7cc1c6703d27214c819133e2f1c2d">ValueProfileCollector</a>.</p>

</div>
</div>

### operator=() {#a7f73ce8c3bf35e72afeab96ed9bcbc28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueProfileCollector &amp; llvm::ValueProfileCollector::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valueprofilecollector">ValueProfileCollector</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/valueprofilecollector-h">ValueProfileCollector.h</a>.</p>


<p>Reference <a href="#a50d7cc1c6703d27214c819133e2f1c2d">ValueProfileCollector</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### get() {#a9051f7b5cb39eaecf1a333768670f72f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; CandidateInfo &gt; ValueProfileCollector::get (<a href="/web-llvm/docs/api/namespaces/llvm/#aa3a544a0d0dd4971f6c79d9869a1ffee">InstrProfValueKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>returns a list of value profiling candidates of the given kind</p>

<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/valueprofilecollector-h">ValueProfileCollector.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/valueprofilecollector-cpp">ValueProfileCollector.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### PImpl {#af9e1eb306272e7159c228b796fdf2fdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ValueProfileCollectorImpl&gt; llvm::ValueProfileCollector::PImpl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/valueprofilecollector-h">ValueProfileCollector.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/valueprofilecollector-cpp">ValueProfileCollector.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/valueprofilecollector-h">ValueProfileCollector.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
