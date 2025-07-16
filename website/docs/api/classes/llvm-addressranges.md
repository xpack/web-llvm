---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/addressranges
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AddressRanges` Class Reference

<p>The <a href="/web-llvm/docs/api/classes/llvm/addressranges">AddressRanges</a> class helps normalize address range collections. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AddressRanges { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">llvm/ADT/AddressRanges.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/addressrangesbase">AddressRangesBase&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/addressrangesbase">AddressRangesBase</a> class presents the base functionality for the normalized address ranges collection. <a href="/web-llvm/docs/api/classes/llvm/addressrangesbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a641b0782e0cc309372855bfc19fdfd97">Collection::const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8762c3c9799f1cf6d3ee0b86f0ceea5d">insert</a> (AddressRange Range)</td>
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

<p>The <a href="/web-llvm/docs/api/classes/llvm/addressranges">AddressRanges</a> class helps normalize address range collections.</p>


<p>This class keeps a sorted vector of <a href="/web-llvm/docs/api/classes/llvm/addressrange">AddressRange</a> objects and can perform insertions and searches efficiently. Intersecting([100,200), [150,300)) and adjacent([100,200), [200,300)) address ranges are combined during insertion.</p>


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">AddressRanges.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### insert() {#a8762c3c9799f1cf6d3ee0b86f0ceea5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Collection::const_iterator llvm::AddressRanges::insert (<a href="/web-llvm/docs/api/classes/llvm/addressrange">AddressRange</a> Range)</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">AddressRanges.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/classes/llvm/addressrangesbase/#a684c16e5f330278b24651bdd96ae172f">llvm::AddressRangesBase&lt; AddressRange &gt;::Ranges</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4b7d2ab11554bd10d15b6cb21b2c2787">llvm::upper_bound</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a67e7cb91f1de318011b4ad8f6453fa7a">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitRanges</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">AddressRanges.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
