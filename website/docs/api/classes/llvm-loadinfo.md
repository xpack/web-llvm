---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loadinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LoadInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::LoadInfo { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71393af12da8445387963cd6ba781d5f">insert</a> (LoadInst *Load, GVNPass::ValueTable &amp;VN)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a56ff7c7c0a1a28379835df7aebfc8668">VNtoInsns</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5106657776b5bdce0f768768056f9c69">getVNTable</a> () const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a56ff7c7c0a1a28379835df7aebfc8668">VNtoInsns</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8d5bef36934b421c989cda0d7b85831">VNtoLoads</a></td>
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


<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnhoist-cpp">GVNHoist.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getVNTable() {#a5106657776b5bdce0f768768056f9c69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VNtoInsns &amp; llvm::LoadInfo::getVNTable ()</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnhoist-cpp">GVNHoist.cpp</a>.</p>

</div>
</div>

### insert() {#a71393af12da8445387963cd6ba781d5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoadInfo::insert (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * Load, <a href="/web-llvm/docs/api/classes/llvm/gvnpass/valuetable">GVNPass::ValueTable</a> &amp; VN)</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnhoist-cpp">GVNHoist.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/gvnpass/valuetable/#a493be9f3a0a293d285393b0b8cb96819">llvm::GVNPass::ValueTable::lookupOrAdd</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### VNtoLoads {#af8d5bef36934b421c989cda0d7b85831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNtoInsns llvm::LoadInfo::VNtoLoads</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnhoist-cpp">GVNHoist.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnhoist-cpp">GVNHoist.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
