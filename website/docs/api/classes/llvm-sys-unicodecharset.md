---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sys/unicodecharset
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `UnicodeCharSet` Class Reference

<p>Holds a reference to an ordered array of <a href="/web-llvm/docs/api/structs/llvm/sys/unicodecharrange">UnicodeCharRange</a> and allows to quickly check if a code point is contained in the set represented by this array. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sys::UnicodeCharSet { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/unicodecharranges-h">llvm/Support/UnicodeCharRanges.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/sys/unicodecharrange">UnicodeCharRange</a> &gt; <a href="#a85ed61bb536a499e1544c955db93086d">CharRanges</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90c7be75d8be840b2eb855fb6767aef3">UnicodeCharSet</a> (CharRanges Ranges)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs a <a href="/web-llvm/docs/api/classes/llvm/sys/unicodecharset">UnicodeCharSet</a> instance from an array of UnicodeCharRanges. <a href="#a90c7be75d8be840b2eb855fb6767aef3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2920c37bba86099cb7bd7718c6288fac">contains</a> (uint32_t C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the character set contains the Unicode code point <span class="doxyComputerOutput">C</span>. <a href="#a2920c37bba86099cb7bd7718c6288fac">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85db505568e672c17101a628d17e7a59">rangesAreValid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if each of the ranges is a proper closed range [min, max], and if the ranges themselves are ordered and non-overlapping. <a href="#a85db505568e672c17101a628d17e7a59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a85ed61bb536a499e1544c955db93086d">CharRanges</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06921cb6c94912de3e473290998f5fac">Ranges</a></td>
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

<p>Holds a reference to an ordered array of <a href="/web-llvm/docs/api/structs/llvm/sys/unicodecharrange">UnicodeCharRange</a> and allows to quickly check if a code point is contained in the set represented by this array.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/unicodecharranges-h">UnicodeCharRanges.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### CharRanges {#a85ed61bb536a499e1544c955db93086d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef ArrayRef&lt;UnicodeCharRange&gt; llvm::sys::UnicodeCharSet::CharRanges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/unicodecharranges-h">UnicodeCharRanges.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### UnicodeCharSet() {#a90c7be75d8be840b2eb855fb6767aef3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::UnicodeCharSet::UnicodeCharSet (<a href="#a85ed61bb536a499e1544c955db93086d">CharRanges</a> Ranges)</td>
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

<p>Constructs a <a href="/web-llvm/docs/api/classes/llvm/sys/unicodecharset">UnicodeCharSet</a> instance from an array of UnicodeCharRanges.</p>


<p>Array pointed by <span class="doxyComputerOutput">Ranges</span> should have the lifetime at least as long as the <a href="/web-llvm/docs/api/classes/llvm/sys/unicodecharset">UnicodeCharSet</a> instance, and should not change. Array is validated by the constructor, so it makes sense to create as few <a href="/web-llvm/docs/api/classes/llvm/sys/unicodecharset">UnicodeCharSet</a> instances per each array of ranges, as possible.</p>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/unicodecharranges-h">UnicodeCharRanges.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### contains() {#a2920c37bba86099cb7bd7718c6288fac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::UnicodeCharSet::contains (uint32_t C)</td>
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

<p>Returns true if the character set contains the Unicode code point <span class="doxyComputerOutput">C</span>.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/unicodecharranges-h">UnicodeCharRanges.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/sys/unicode/#aa1dd06eeeda61a605655a2fab90dd6c4">llvm::sys::unicode::charWidth</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/unicode/#abdd3e84c33222ee387cf6a03d1a77400">llvm::sys::unicode::isPrintable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### rangesAreValid() {#a85db505568e672c17101a628d17e7a59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::UnicodeCharSet::rangesAreValid ()</td>
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

<p>Returns true if each of the ranges is a proper closed range [min, max], and if the ranges themselves are ordered and non-overlapping.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/unicodecharranges-h">UnicodeCharRanges.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Ranges {#a06921cb6c94912de3e473290998f5fac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CharRanges llvm::sys::UnicodeCharSet::Ranges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/unicodecharranges-h">UnicodeCharRanges.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/unicodecharranges-h">UnicodeCharRanges.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
