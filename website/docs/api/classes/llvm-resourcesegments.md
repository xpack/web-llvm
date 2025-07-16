---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/resourcesegments
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ResourceSegments` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/resourcesegments">ResourceSegments</a> are a collection of intervals closed on the left and opened on the right: <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ResourceSegments { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">llvm/CodeGen/MachineScheduler.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::pair&lt; int64_t, int64_t &gt; <a href="#ac93528094c576c984aed5f8cd6923bc0">IntervalTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an interval of discrete integer values closed on the left and open on the right: [a, b). <a href="#ac93528094c576c984aed5f8cd6923bc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c0f046546e4f1a19ef1546cb4f0c813">operator==</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d6d29af031766f1b32ce8d496db7d25">operator&lt;&lt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1acb88064bee4429a66c43624abf0fad">ResourceSegments</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade0e5e61ec4d1af9caa7af68ceea9c4c">ResourceSegments</a> (const std::list&lt; IntervalTy &gt; &amp;Intervals)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a173bcdd8f59b31a810aead1000274448">add</a> (IntervalTy A, const unsigned CutOff=10)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds an interval [a, b) to the collection of the instance. <a href="#a173bcdd8f59b31a810aead1000274448">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed8869791acb35bc33a55d3ed1016f94">getFirstAvailableAtFromBottom</a> (unsigned CurrCycle, unsigned AcquireAtCycle, unsigned ReleaseAtCycle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFirstAvailableAtFromBottom and getFirstAvailableAtFromTop should be merged in a single function in which a function that creates the <span class="doxyComputerOutput">NewInterval</span> is passed as a parameter. <a href="#aed8869791acb35bc33a55d3ed1016f94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99e566d4dd4d552a9e38af4e047e4c1f">getFirstAvailableAtFromTop</a> (unsigned CurrCycle, unsigned AcquireAtCycle, unsigned ReleaseAtCycle) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dfd42064c0179ac5c5f90951bcdbbdf">empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6110abf43726025e099e715e1343864">getFirstAvailableAt</a> (unsigned CurrCycle, unsigned AcquireAtCycle, unsigned ReleaseAtCycle, std::function&lt; IntervalTy(unsigned, unsigned, unsigned)&gt; IntervalBuilder) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finds the first cycle in which a resource can be allocated. <a href="#af6110abf43726025e099e715e1343864">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2162c9490a6bd80892be4ea294043141">sortAndMerge</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge all adjacent intervals in the collection. <a href="#a2162c9490a6bd80892be4ea294043141">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::list&lt; <a href="#ac93528094c576c984aed5f8cd6923bc0">IntervalTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9d5e619b87a9aa6dabcec2d454add5e">_Intervals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fbb23b17b45652a8d28aadabbabf3c9">intersects</a> (IntervalTy A, IntervalTy B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks whether intervals intersect. <a href="#a7fbb23b17b45652a8d28aadabbabf3c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ac93528094c576c984aed5f8cd6923bc0">IntervalTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46315c932ddcacb368f78ecc39a96fe3">getResourceIntervalBottom</a> (unsigned C, unsigned AcquireAtCycle, unsigned ReleaseAtCycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These function return the interval used by a resource in bottom and top scheduling. <a href="#a46315c932ddcacb368f78ecc39a96fe3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ac93528094c576c984aed5f8cd6923bc0">IntervalTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0173019797b2f865e64a85377cb3bd5">getResourceIntervalTop</a> (unsigned C, unsigned AcquireAtCycle, unsigned ReleaseAtCycle)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/resourcesegments">ResourceSegments</a> are a collection of intervals closed on the left and opened on the right:</p>



<pre><code>list{ [a1, b1), [a2, b2), ..., [a_N, b_N) }
</code></pre>


<p>The collection has the following properties:</p>


<ol class="doxyList" type="1">
<li>The list is ordered: a_i &lt; b_i and b_i &lt; a_(i+1)</li>
<li>The intervals in the collection do not intersect each other.</li>
</ol>

<p>A <a href="/web-llvm/docs/api/classes/llvm/resourcesegments">ResourceSegments</a> instance represents the cycle reservation history of the instance of and individual resource.</p>


<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### IntervalTy {#ac93528094c576c984aed5f8cd6923bc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::pair&lt;int64_t, int64_t&gt; llvm::ResourceSegments::IntervalTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents an interval of discrete integer values closed on the left and open on the right: [a, b).</p>

<p>Definition at line 640 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### operator&lt;&lt; {#a9d6d29af031766f1b32ce8d496db7d25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp; os, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/resourcesegments">ResourceSegments</a> &amp; Segments</td>
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


<p>Definition at line 828 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#a1acb88064bee4429a66c43624abf0fad">ResourceSegments</a>.</p>

</div>
</div>

### operator== {#a6c0f046546e4f1a19ef1546cb4f0c813}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/resourcesegments">ResourceSegments</a> &amp; c1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/resourcesegments">ResourceSegments</a> &amp; c2</td>
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


<p>Definition at line 824 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#a1acb88064bee4429a66c43624abf0fad">ResourceSegments</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ResourceSegments() {#a1acb88064bee4429a66c43624abf0fad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ResourceSegments::ResourceSegments ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 817 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a9d6d29af031766f1b32ce8d496db7d25">operator&lt;&lt;</a> and <a href="#a6c0f046546e4f1a19ef1546cb4f0c813">operator==</a>.</p>

</div>
</div>

### ResourceSegments() {#ade0e5e61ec4d1af9caa7af68ceea9c4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ResourceSegments::ResourceSegments (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::list&lt; <a href="#ac93528094c576c984aed5f8cd6923bc0">IntervalTy</a> &gt; &amp; Intervals)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 819 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a173bcdd8f59b31a810aead1000274448}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ResourceSegments::add (<a href="#ac93528094c576c984aed5f8cd6923bc0">IntervalTy</a> A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned CutOff=10)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds an interval [a, b) to the collection of the instance.</p>


<p>When adding [a, b[ to the collection, the operation merges the adjacent intervals. For example</p>



<pre><code>  0  1  2  3  4  5  6  7  8  9  10
  [-----)  [--)     [--)
+       [--)
= [-----------)     [--)
</code></pre>


<p>To be able to debug duplicate resource usage, the function has assertion that checks that no interval should be added if it overlaps any of the intervals in the collection. We can require this because by definition a <a href="/web-llvm/docs/api/classes/llvm/resourcesegments">ResourceSegments</a> is attached only to an individual resource instance.</p>


<p>Declaration at line 657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 4505 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dbgentityhistorycalculator-cpp/#a0250c150e720772b7e0feac3d2f43e82">intersects</a>.</p>

</div>
</div>

### empty() {#a3dfd42064c0179ac5c5f90951bcdbbdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ResourceSegments::empty ()</td>
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



<p>Definition at line 818 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

### getFirstAvailableAtFromBottom() {#aed8869791acb35bc33a55d3ed1016f94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ResourceSegments::getFirstAvailableAtFromBottom (unsigned CurrCycle, unsigned AcquireAtCycle, unsigned ReleaseAtCycle)</td>
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

<p>getFirstAvailableAtFromBottom and getFirstAvailableAtFromTop should be merged in a single function in which a function that creates the <span class="doxyComputerOutput">NewInterval</span> is passed as a parameter.</p>

<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#a46315c932ddcacb368f78ecc39a96fe3">getResourceIntervalBottom</a>.</p>

</div>
</div>

### getFirstAvailableAtFromTop() {#a99e566d4dd4d552a9e38af4e047e4c1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ResourceSegments::getFirstAvailableAtFromTop (unsigned CurrCycle, unsigned AcquireAtCycle, unsigned ReleaseAtCycle)</td>
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



<p>Definition at line 799 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="#ad0173019797b2f865e64a85377cb3bd5">getResourceIntervalTop</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getFirstAvailableAt() {#af6110abf43726025e099e715e1343864}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ResourceSegments::getFirstAvailableAt (unsigned CurrCycle, unsigned AcquireAtCycle, unsigned ReleaseAtCycle, std::function&lt; <a href="#ac93528094c576c984aed5f8cd6923bc0">IntervalTy</a>(unsigned, unsigned, unsigned)&gt; IntervalBuilder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finds the first cycle in which a resource can be allocated.</p>


<p>The function uses the</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">IntervalBuider</td>
<td class="doxyParamItemDescription"><p>[*] to build a resource interval [a, b[ out of the input parameters</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CurrCycle</td>
<td class="doxyParamItemDescription"></td>
</tr>
</table>
</dd>
</dl>

<p>param AcquireAtCycle and</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReleaseAtCycle.</td>
<td class="doxyParamItemDescription"></td>
</tr>
</table>
</dd>
</dl>

<p>The function then loops through the intervals in the <a href="/web-llvm/docs/api/classes/llvm/resourcesegments">ResourceSegments</a> and shifts the interval [a, b[ and the ReturnCycle to the right until there is no intersection between the intervals of the <a href="/web-llvm/docs/api/classes/llvm/resourcesegments">ResourceSegments</a> instance and the new shifted [a, b[. When this condition is met, the ReturnCycle (which correspond to the cycle in which the resource can be allocated) is returned.</p>



<pre><code>          c = CurrCycle in input
          c   1   2   3   4   5   6   7   8   9   10 ... ---&gt; (time
          flow)
</code></pre>


<p><a href="/web-llvm/docs/api/classes/llvm/resourcesegments">ResourceSegments</a>... [—) [----—) [--------—) c [1 3[ -&gt; AcquireAtCycle=1, ReleaseAtCycle=3 ++c [1 3) ++c [1 3) ++c [1 3) ++c [1 3) ++c [1 3) ---&gt; returns c incremented by 5 (c+5)</p>


<p>Notice that for bottom-up scheduling the diagram is slightly different because the current cycle c is always on the right of the interval [a, b) (see <span class="doxyComputerOutput">getResourceIntervalBottom</span>). This is because the cycle increments for bottom-up scheduling moved in the direction opposite to the direction of time:</p>



<pre><code>--------&gt; direction of time.
XXYZZZ    (resource usage)
--------&gt; direction of top-down execution cycles.
&lt;-------- direction of bottom-up execution cycles.
</code></pre>


<p>Even though bottom-up scheduling moves against the flow of time, the algorithm used to find the first free slot in between intervals is the same as for top-down scheduling.</p>


<p>[*] See `getResourceIntervalTop` and `getResourceIntervalBottom` to see how such resource intervals are built.</p>


<p>Declaration at line 784 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 4475 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>

</div>
</div>

### sortAndMerge() {#a2162c9490a6bd80892be4ea294043141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ResourceSegments::sortAndMerge ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge all adjacent intervals in the collection.</p>


<p>For all pairs of adjacient intervals, it performs [a, b) + [b, c) -&gt; [a, c).</p>


<p>Before performing the merge operation, the intervals are sorted with sort_predicate.</p>


<p>Declaration at line 813 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 4559 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### \_Intervals {#ad9d5e619b87a9aa6dabcec2d454add5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::list&lt;IntervalTy&gt; llvm::ResourceSegments::_Intervals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 807 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getResourceIntervalBottom() {#a46315c932ddcacb368f78ecc39a96fe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntervalTy llvm::ResourceSegments::getResourceIntervalBottom (unsigned C, unsigned AcquireAtCycle, unsigned ReleaseAtCycle)</td>
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

<p>These function return the interval used by a resource in bottom and top scheduling.</p>


<p>Consider an instruction that uses resources X0, X1 and X2 as follows:</p>


<p>X0 X1 X1 X2 +-----—+----------—+-----------—+ |Resource|AcquireAtCycle|ReleaseAtCycle| +-----—+----------—+-----------—+ | X0 | 0 | 1 | +-----—+----------—+-----------—+ | X1 | 1 | 3 | +-----—+----------—+-----------—+ | X2 | 3 | 4 | +-----—+----------—+-----------—+</p>


<p>If we can schedule the instruction at cycle C, we need to compute the interval of the resource as follows:</p>


## TOP DOWN SCHEDULING {#autotoc_md24}


<p>Cycles scheduling flows to the <em>right</em>, in the same direction of time.</p>



<pre><code>  C      1      2      3      4      5  ...
</code></pre>


<p>---—|---—|---—|---—|---—|---—|-----&gt; X0 X1 X1 X2 ---&gt; direction of time X0 [C, C+1) X1 [C+1, C+3) X2 [C+3, C+4)</p>


<p>Therefore, the formula to compute the interval for a resource of an instruction that can be scheduled at cycle C in top-down scheduling is:</p>



<pre><code>  [C+AcquireAtCycle, C+ReleaseAtCycle)
</code></pre>


## BOTTOM UP SCHEDULING {#autotoc_md25}


<p>Cycles scheduling flows to the <em>left</em>, in opposite direction of time.</p>


<p>In bottom up scheduling, the scheduling happens in opposite direction to the execution of the cycles of the instruction. When the instruction is scheduled at cycle <span class="doxyComputerOutput">C</span>, the resources are allocated in the past relative to <span class="doxyComputerOutput">C</span>:</p>



<pre><code>  2      1      C     -1     -2     -3     -4     -5  ...
</code></pre>


<p>&lt;--—|---—|---—|---—|---—|---—|---—|---—|— X0 X1 X1 X2 ---&gt; direction of time X0 (C+1, C] X1 (C, C-2] X2 (C-2, C-3]</p>


<p>Therefore, the formula to compute the interval for a resource of an instruction that can be scheduled at cycle C in bottom-up scheduling is:</p>



<pre><code>  [C-ReleaseAtCycle+1, C-AcquireAtCycle+1)
</code></pre>


<p>NOTE: In both cases, the number of cycles booked by a resources is the value (ReleaseAtCycle - AcquireAtCycle).</p>


<p>Definition at line 726 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a6b1771cf492495f8f82727657c68e571">llvm::SchedBoundary::bumpNode</a> and <a href="#aed8869791acb35bc33a55d3ed1016f94">getFirstAvailableAtFromBottom</a>.</p>

</div>
</div>

### getResourceIntervalTop() {#ad0173019797b2f865e64a85377cb3bd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntervalTy llvm::ResourceSegments::getResourceIntervalTop (unsigned C, unsigned AcquireAtCycle, unsigned ReleaseAtCycle)</td>
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



<p>Definition at line 731 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a6b1771cf492495f8f82727657c68e571">llvm::SchedBoundary::bumpNode</a> and <a href="#a99e566d4dd4d552a9e38af4e047e4c1f">getFirstAvailableAtFromTop</a>.</p>

</div>
</div>

### intersects() {#a7fbb23b17b45652a8d28aadabbabf3c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ResourceSegments::intersects (<a href="#ac93528094c576c984aed5f8cd6923bc0">IntervalTy</a> A, <a href="#ac93528094c576c984aed5f8cd6923bc0">IntervalTy</a> B)</td>
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

<p>Checks whether intervals intersect.</p>

<p>Declaration at line 661 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a>, definition at line 4532 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">MachineScheduler.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
