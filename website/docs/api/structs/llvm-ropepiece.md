---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/ropepiece
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RopePiece` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/ropepiece">RopePiece</a> - This class represents a view into a <a href="/web-llvm/docs/api/structs/llvm/roperefcountstring">RopeRefCountString</a> object. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::RopePiece { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewriterope-h">llvm/ADT/RewriteRope.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72cf6a44b0c63bd7c5c8758532612789">RopePiece</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba2543016e05479151e454c4550460cf">RopePiece</a> (llvm::IntrusiveRefCntPtr&lt; RopeRefCountString &gt; Str, unsigned Start, unsigned End)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9b6ed88e6afd22c7a0cc527a39fb1b2">operator[]</a> (unsigned Offset) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7456bae1a4b76f7945a78b6f106f5fe">operator[]</a> (unsigned Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae73820aec7ee77100f5b9af4443890aa">size</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">llvm::IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/roperefcountstring">RopeRefCountString</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb718544f967223a0c4f24d05ea48d4c">StrData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a761a31f9027cb44172b04dbed4da15f4">StartOffs</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0721b68dbad138b55dd1fc6e3b95afb0">EndOffs</a> = 0</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/ropepiece">RopePiece</a> - This class represents a view into a <a href="/web-llvm/docs/api/structs/llvm/roperefcountstring">RopeRefCountString</a> object.</p>


<p>This allows references to string data to be efficiently chopped up and moved around without having to push around the string data itself.</p>


<p>For example, we could have a 1M <a href="/web-llvm/docs/api/structs/llvm/ropepiece">RopePiece</a> and want to insert something into the middle of it. To do this, we split it into two <a href="/web-llvm/docs/api/structs/llvm/ropepiece">RopePiece</a> objects that both refer to the same underlying <a href="/web-llvm/docs/api/structs/llvm/roperefcountstring">RopeRefCountString</a> (just with different offsets) which is a nice constant time operation.</p>


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewriterope-h">RewriteRope.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RopePiece() {#a72cf6a44b0c63bd7c5c8758532612789}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RopePiece::RopePiece ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewriterope-h">RewriteRope.h</a>.</p>

</div>
</div>

### RopePiece() {#aba2543016e05479151e454c4550460cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RopePiece::RopePiece (<a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">llvm::IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/roperefcountstring">RopeRefCountString</a> &gt; Str, unsigned Start, unsigned End)</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewriterope-h">RewriteRope.h</a>.</p>


<p>References <a href="#a0721b68dbad138b55dd1fc6e3b95afb0">EndOffs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#a761a31f9027cb44172b04dbed4da15f4">StartOffs</a> and <a href="#afb718544f967223a0c4f24d05ea48d4c">StrData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#af9b6ed88e6afd22c7a0cc527a39fb1b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char &amp; llvm::RopePiece::operator[] (unsigned Offset)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewriterope-h">RewriteRope.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a761a31f9027cb44172b04dbed4da15f4">StartOffs</a> and <a href="#afb718544f967223a0c4f24d05ea48d4c">StrData</a>.</p>

</div>
</div>

### operator\[\]() {#ab7456bae1a4b76f7945a78b6f106f5fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char &amp; llvm::RopePiece::operator[] (unsigned Offset)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewriterope-h">RewriteRope.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a761a31f9027cb44172b04dbed4da15f4">StartOffs</a> and <a href="#afb718544f967223a0c4f24d05ea48d4c">StrData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### size() {#ae73820aec7ee77100f5b9af4443890aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RopePiece::size ()</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewriterope-h">RewriteRope.h</a>.</p>


<p>References <a href="#a0721b68dbad138b55dd1fc6e3b95afb0">EndOffs</a> and <a href="#a761a31f9027cb44172b04dbed4da15f4">StartOffs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#a838a0abe15a9d3a9a65575766ca82e07">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::erase</a> and <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#acf7193c4f9e38edd218457ecad2b11c8">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::insert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### EndOffs {#a0721b68dbad138b55dd1fc6e3b95afb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RopePiece::EndOffs = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewriterope-h">RewriteRope.h</a>.</p>


<p>Referenced by <a href="#aba2543016e05479151e454c4550460cf">RopePiece</a> and <a href="#ae73820aec7ee77100f5b9af4443890aa">size</a>.</p>

</div>
</div>

### StartOffs {#a761a31f9027cb44172b04dbed4da15f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RopePiece::StartOffs = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewriterope-h">RewriteRope.h</a>.</p>


<p>Referenced by <a href="#ab7456bae1a4b76f7945a78b6f106f5fe">operator[]</a>, <a href="#af9b6ed88e6afd22c7a0cc527a39fb1b2">operator[]</a>, <a href="#aba2543016e05479151e454c4550460cf">RopePiece</a> and <a href="#ae73820aec7ee77100f5b9af4443890aa">size</a>.</p>

</div>
</div>

### StrData {#afb718544f967223a0c4f24d05ea48d4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IntrusiveRefCntPtr&lt;RopeRefCountString&gt; llvm::RopePiece::StrData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewriterope-h">RewriteRope.h</a>.</p>


<p>Referenced by <a href="#ab7456bae1a4b76f7945a78b6f106f5fe">operator[]</a>, <a href="#af9b6ed88e6afd22c7a0cc527a39fb1b2">operator[]</a> and <a href="#aba2543016e05479151e454c4550460cf">RopePiece</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewriterope-h">RewriteRope.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
