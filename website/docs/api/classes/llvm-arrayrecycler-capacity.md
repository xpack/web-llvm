---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/arrayrecycler/capacity
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Capacity` Class

<p>The size of an allocated array is represented by a <a href="/web-llvm/docs/api/classes/llvm/arrayrecycler/capacity">Capacity</a> instance. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ArrayRecycler::Capacity { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/arrayrecycler-h">llvm/Support/ArrayRecycler.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af032fe5112f3705846dd6f1882986c80">Capacity</a> ()</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94bd25cad13d49cd5d904752864ea4de">Capacity</a> (uint8_t idx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43f20d00d7dda4241616ef78bad7b1d3">getSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of elements in an array with this capacity. <a href="#a43f20d00d7dda4241616ef78bad7b1d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad63c3215ad7810dd4f2b904a3f3ada98">getBucket</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the bucket number for this capacity. <a href="#ad63c3215ad7810dd4f2b904a3f3ada98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayrecycler/capacity">Capacity</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d916c19b79f38116c50c3f5a23c12ec">getNext</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the next larger capacity. <a href="#a1d916c19b79f38116c50c3f5a23c12ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad81e1b13a90b011651c22a7767bf5b48">Index</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/arrayrecycler/capacity">Capacity</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab52c84454e451fabe417985306501afb">get</a> (size_t N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the capacity of an array that can hold at least N elements. <a href="#ab52c84454e451fabe417985306501afb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The size of an allocated array is represented by a <a href="/web-llvm/docs/api/classes/llvm/arrayrecycler/capacity">Capacity</a> instance.</p>


<p>This class is much smaller than a size_t, and it provides methods to work with the set of legal array capacities.</p>


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/arrayrecycler-h">ArrayRecycler.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Capacity() {#af032fe5112f3705846dd6f1882986c80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ArrayRecycler&lt; T, Align &gt;::Capacity::Capacity ()</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/arrayrecycler-h">ArrayRecycler.h</a>.</p>


<p>Referenced by <a href="#ab52c84454e451fabe417985306501afb">llvm::ArrayRecycler&lt; T, Align &gt;::Capacity::get</a> and <a href="#a1d916c19b79f38116c50c3f5a23c12ec">llvm::ArrayRecycler&lt; T, Align &gt;::Capacity::getNext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### Capacity() {#a94bd25cad13d49cd5d904752864ea4de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ArrayRecycler&lt; T, Align &gt;::Capacity::Capacity (uint8_t idx)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/arrayrecycler-h">ArrayRecycler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBucket() {#ad63c3215ad7810dd4f2b904a3f3ada98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ArrayRecycler&lt; T, Align &gt;::Capacity::getBucket ()</td>
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

<p>Get the bucket number for this capacity.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/arrayrecycler-h">ArrayRecycler.h</a>.</p>

</div>
</div>

### getNext() {#a1d916c19b79f38116c50c3f5a23c12ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Capacity llvm::ArrayRecycler&lt; T, Align &gt;::Capacity::getNext ()</td>
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

<p>Get the next larger capacity.</p>


<p>Large capacities grow exponentially, so this function can be used to reallocate incrementally growing vectors in amortized linear time.</p>


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/arrayrecycler-h">ArrayRecycler.h</a>.</p>


<p>Reference <a href="#af032fe5112f3705846dd6f1882986c80">llvm::ArrayRecycler&lt; T, Align &gt;::Capacity::Capacity</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>.</p>

</div>
</div>

### getSize() {#a43f20d00d7dda4241616ef78bad7b1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::ArrayRecycler&lt; T, Align &gt;::Capacity::getSize ()</td>
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

<p>Get the number of elements in an array with this capacity.</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/arrayrecycler-h">ArrayRecycler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Index {#ad81e1b13a90b011651c22a7767bf5b48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::ArrayRecycler&lt; T, Align &gt;::Capacity::Index</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/arrayrecycler-h">ArrayRecycler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### get() {#ab52c84454e451fabe417985306501afb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Capacity llvm::ArrayRecycler&lt; T, Align &gt;::Capacity::get (size_t N)</td>
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

<p>Get the capacity of an array that can hold at least N elements.</p>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/arrayrecycler-h">ArrayRecycler.h</a>.</p>


<p>References <a href="#af032fe5112f3705846dd6f1882986c80">llvm::ArrayRecycler&lt; T, Align &gt;::Capacity::Capacity</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a238ef12f09938dac4efe5ca56dc125d9">llvm::Log2_64_Ceil</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/arrayrecycler-h">ArrayRecycler.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
