---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/indexedinstrprof/summary/entry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Entry` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::IndexedInstrProf::Summary::Entry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">llvm/ProfileData/InstrProf.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b27e0076cfcdc0735e9a009de7f8660">Cutoff</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The required percentile of total execution count. <a href="#a0b27e0076cfcdc0735e9a009de7f8660">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade0dca5da1913ecb0cd5755e665e640c">MinBlockCount</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The minimum execution count for this percentile. <a href="#ade0dca5da1913ecb0cd5755e665e640c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a557ad02d2944c671df2bfed9e9191ccd">NumBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of blocks &gt;= the minumum execution count. <a href="#a557ad02d2944c671df2bfed9e9191ccd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 1166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Cutoff {#a0b27e0076cfcdc0735e9a009de7f8660}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::IndexedInstrProf::Summary::Entry::Cutoff</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The required percentile of total execution count.</p>

<p>Definition at line 1167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/indexedinstrprof/summary/#a55a5013634d7fc600f627e0870a52511">llvm::IndexedInstrProf::Summary::setEntry</a>.</p>

</div>
</div>

### MinBlockCount {#ade0dca5da1913ecb0cd5755e665e640c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::IndexedInstrProf::Summary::Entry::MinBlockCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The minimum execution count for this percentile.</p>

<p>Definition at line 1169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/indexedinstrprof/summary/#a55a5013634d7fc600f627e0870a52511">llvm::IndexedInstrProf::Summary::setEntry</a>.</p>

</div>
</div>

### NumBlocks {#a557ad02d2944c671df2bfed9e9191ccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::IndexedInstrProf::Summary::Entry::NumBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of blocks &gt;= the minumum execution count.</p>

<p>Definition at line 1170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/indexedinstrprof/summary/#a55a5013634d7fc600f627e0870a52511">llvm::IndexedInstrProf::Summary::setEntry</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
