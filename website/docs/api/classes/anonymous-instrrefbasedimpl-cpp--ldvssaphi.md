---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssaphi
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LDVSSAPhi` Class Reference

<p>Represents an SSA PHI node for the SSA updater class. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{InstrRefBasedImpl.cpp}::LDVSSAPhi { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc62028e5727852a5a0ca16fe155518e">LDVSSAPhi</a> (BlockValueNum PHIValNum, LDVSSABlock *ParentBlock)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssablock">LDVSSABlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8abac7f4b7f3156874dae57c3a33cd2">getParent</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssablock">LDVSSABlock</a> *, <a href="/web-llvm/docs/api/namespaces/anonymous-instrrefbasedimpl-cpp-/#a8c63effba4b56132c365c02a07251561">BlockValueNum</a> &gt;, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0465847f732ea1597dd09f78b03eca7">IncomingValues</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssablock">LDVSSABlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0fa90a8f202bd36e2fe7fee6b03869d">ParentBlock</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-instrrefbasedimpl-cpp-/#a8c63effba4b56132c365c02a07251561">BlockValueNum</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b4c4f7702d50f17fb71b1e2dbc07509">PHIValNum</a></td>
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

<p>Represents an SSA PHI node for the SSA updater class.</p>


<p>Contains the block this PHI is in, the value number it would have, and the expected incoming values from parent blocks.</p>


<p>Definition at line 3882 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LDVSSAPhi() {#acc62028e5727852a5a0ca16fe155518e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InstrRefBasedImpl.cpp}::LDVSSAPhi::LDVSSAPhi (<a href="/web-llvm/docs/api/namespaces/anonymous-instrrefbasedimpl-cpp-/#a8c63effba4b56132c365c02a07251561">BlockValueNum</a> PHIValNum, <a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssablock">LDVSSABlock</a> * ParentBlock)</td>
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



<p>Definition at line 3887 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#af0fa90a8f202bd36e2fe7fee6b03869d">ParentBlock</a> and <a href="#a1b4c4f7702d50f17fb71b1e2dbc07509">PHIValNum</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getParent() {#af8abac7f4b7f3156874dae57c3a33cd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LDVSSABlock * anonymous{InstrRefBasedImpl.cpp}::LDVSSAPhi::getParent ()</td>
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



<p>Definition at line 3890 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Reference <a href="#af0fa90a8f202bd36e2fe7fee6b03869d">ParentBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IncomingValues {#ad0465847f732ea1597dd09f78b03eca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::pair&lt;LDVSSABlock *, BlockValueNum&gt;, 4&gt; anonymous{InstrRefBasedImpl.cpp}::LDVSSAPhi::IncomingValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3884 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### ParentBlock {#af0fa90a8f202bd36e2fe7fee6b03869d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LDVSSABlock* anonymous{InstrRefBasedImpl.cpp}::LDVSSAPhi::ParentBlock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3885 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#af8abac7f4b7f3156874dae57c3a33cd2">getParent</a> and <a href="#acc62028e5727852a5a0ca16fe155518e">LDVSSAPhi</a>.</p>

</div>
</div>

### PHIValNum {#a1b4c4f7702d50f17fb71b1e2dbc07509}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockValueNum anonymous{InstrRefBasedImpl.cpp}::LDVSSAPhi::PHIValNum</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3886 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#acc62028e5727852a5a0ca16fe155518e">LDVSSAPhi</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
