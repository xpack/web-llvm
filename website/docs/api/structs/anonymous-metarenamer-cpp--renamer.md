---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-metarenamer-cpp-/renamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Renamer` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{MetaRenamer.cpp}::Renamer { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1168d3f490a285377207b0c42a9f7494">Renamer</a> (unsigned int seed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8728150609ddac619b3d0806323fc027">newName</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-metarenamer-cpp-/prng">PRNG</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ee6d62ba42d6993fc06e24ce07c1d0d">prng</a></td>
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


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/metarenamer-cpp">MetaRenamer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Renamer() {#a1168d3f490a285377207b0c42a9f7494}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MetaRenamer.cpp}::Renamer::Renamer (unsigned int seed)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/metarenamer-cpp">MetaRenamer.cpp</a>.</p>


<p>Reference <a href="#a8ee6d62ba42d6993fc06e24ce07c1d0d">prng</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### newName() {#a8728150609ddac619b3d0806323fc027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * anonymous{MetaRenamer.cpp}::Renamer::newName ()</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/metarenamer-cpp">MetaRenamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/metarenamer-cpp/#ae47cae956b11645813ce1a570f373582">metaNames</a> and <a href="#a8ee6d62ba42d6993fc06e24ce07c1d0d">prng</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-metarenamer-cpp-/#a6cdcad2346e6e4bd46c9edc7059592cf">anonymous{MetaRenamer.cpp}::MetaRename</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### prng {#a8ee6d62ba42d6993fc06e24ce07c1d0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PRNG anonymous{MetaRenamer.cpp}::Renamer::prng</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/metarenamer-cpp">MetaRenamer.cpp</a>.</p>


<p>Referenced by <a href="#a8728150609ddac619b3d0806323fc027">newName</a> and <a href="#a1168d3f490a285377207b0c42a9f7494">Renamer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/metarenamer-cpp">MetaRenamer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
