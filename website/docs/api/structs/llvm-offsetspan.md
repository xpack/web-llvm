---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/offsetspan
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `OffsetSpan` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a> - Used internally by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor">ObjectSizeOffsetVisitor</a></span>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::OffsetSpan { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">llvm/Analysis/MemoryBuiltins.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e8b0a022fd228273c3b535a6c5fbf87">OffsetSpan</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of allocated bytes after this point. <a href="#a1e8b0a022fd228273c3b535a6c5fbf87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aece5e0368ec9b63d623caf1651e51a29">OffsetSpan</a> (APInt Before, APInt After)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae247e72f06f62f2ae8a60403defbeeab">operator==</a> (const OffsetSpan &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb518e8df7f0d9febee64829e71ab024">operator!=</a> (const OffsetSpan &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ec0d64d71c543e76d24244861390d7d">knownBefore</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee90d1ce6c5d290375e1c3e5abf11f2">knownAfter</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60b9c04d52616edd6dfbe013dc523fd1">anyKnown</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeff8d21fedad729dbb810e25ba724665">bothKnown</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff12e515f8229c427ccd973711c1e674">Before</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a570730bb165bed0db1f58575b0dd719a">After</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of allocated bytes before this point. <a href="#a570730bb165bed0db1f58575b0dd719a">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb29ecf5d88b1a460f8836201c0e72cc">known</a> (const APInt &amp;V)</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a> - Used internally by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor">ObjectSizeOffsetVisitor</a></span>.</p>


<p>Represents a point in memory as a pair of allocated bytes before and after it.</p>


<p><span class="doxyComputerOutput">Before</span> and <span class="doxyComputerOutput">After</span> fields are signed values. It makes it possible to represent out-of-bound access, e.g. as a result of a GEP, at the expense of not being able to represent very large allocation.</p>


<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OffsetSpan() {#a1e8b0a022fd228273c3b535a6c5fbf87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OffsetSpan::OffsetSpan ()</td>
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

<p>Number of allocated bytes after this point.</p>

<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<p>Referenced by <a href="#acb518e8df7f0d9febee64829e71ab024">operator!=</a> and <a href="#ae247e72f06f62f2ae8a60403defbeeab">operator==</a>.</p>

</div>
</div>

### OffsetSpan() {#aece5e0368ec9b63d623caf1651e51a29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OffsetSpan::OffsetSpan (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> Before, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> After)</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<p>References <a href="#a570730bb165bed0db1f58575b0dd719a">After</a> and <a href="#aff12e515f8229c427ccd973711c1e674">Before</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#acb518e8df7f0d9febee64829e71ab024}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OffsetSpan::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a> &amp; RHS)</td>
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



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<p>References <a href="#a1e8b0a022fd228273c3b535a6c5fbf87">OffsetSpan</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#ae247e72f06f62f2ae8a60403defbeeab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OffsetSpan::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/offsetspan">OffsetSpan</a> &amp; RHS)</td>
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



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<p>References <a href="#a570730bb165bed0db1f58575b0dd719a">After</a>, <a href="#aff12e515f8229c427ccd973711c1e674">Before</a>, <a href="#a1e8b0a022fd228273c3b535a6c5fbf87">OffsetSpan</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### anyKnown() {#a60b9c04d52616edd6dfbe013dc523fd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OffsetSpan::anyKnown ()</td>
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



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<p>References <a href="#a7ee90d1ce6c5d290375e1c3e5abf11f2">knownAfter</a> and <a href="#a2ec0d64d71c543e76d24244861390d7d">knownBefore</a>.</p>

</div>
</div>

### bothKnown() {#aeff8d21fedad729dbb810e25ba724665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OffsetSpan::bothKnown ()</td>
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



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<p>References <a href="#a7ee90d1ce6c5d290375e1c3e5abf11f2">knownAfter</a> and <a href="#a2ec0d64d71c543e76d24244861390d7d">knownBefore</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a8c0cefa2bf3b3199ab80b4b897c49e86">llvm::ObjectSizeOffsetVisitor::compute</a> and <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a59d2b338e83bb54392ec08fdc023b544">llvm::ObjectSizeOffsetVisitor::visitLoadInst</a>.</p>

</div>
</div>

### knownAfter() {#a7ee90d1ce6c5d290375e1c3e5abf11f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OffsetSpan::knownAfter ()</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<p>References <a href="#a570730bb165bed0db1f58575b0dd719a">After</a> and <a href="#abb29ecf5d88b1a460f8836201c0e72cc">known</a>.</p>


<p>Referenced by <a href="#a60b9c04d52616edd6dfbe013dc523fd1">anyKnown</a>, <a href="#aeff8d21fedad729dbb810e25ba724665">bothKnown</a> and <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a8c0cefa2bf3b3199ab80b4b897c49e86">llvm::ObjectSizeOffsetVisitor::compute</a>.</p>

</div>
</div>

### knownBefore() {#a2ec0d64d71c543e76d24244861390d7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OffsetSpan::knownBefore ()</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<p>References <a href="#aff12e515f8229c427ccd973711c1e674">Before</a> and <a href="#abb29ecf5d88b1a460f8836201c0e72cc">known</a>.</p>


<p>Referenced by <a href="#a60b9c04d52616edd6dfbe013dc523fd1">anyKnown</a>, <a href="#aeff8d21fedad729dbb810e25ba724665">bothKnown</a> and <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a8c0cefa2bf3b3199ab80b4b897c49e86">llvm::ObjectSizeOffsetVisitor::compute</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### After {#a570730bb165bed0db1f58575b0dd719a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::OffsetSpan::After</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of allocated bytes before this point.</p>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a8c0cefa2bf3b3199ab80b4b897c49e86">llvm::ObjectSizeOffsetVisitor::compute</a>, <a href="#a7ee90d1ce6c5d290375e1c3e5abf11f2">knownAfter</a>, <a href="#aece5e0368ec9b63d623caf1651e51a29">OffsetSpan</a> and <a href="#ae247e72f06f62f2ae8a60403defbeeab">operator==</a>.</p>

</div>
</div>

### Before {#aff12e515f8229c427ccd973711c1e674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::OffsetSpan::Before</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a8c0cefa2bf3b3199ab80b4b897c49e86">llvm::ObjectSizeOffsetVisitor::compute</a>, <a href="#a2ec0d64d71c543e76d24244861390d7d">knownBefore</a>, <a href="#aece5e0368ec9b63d623caf1651e51a29">OffsetSpan</a> and <a href="#ae247e72f06f62f2ae8a60403defbeeab">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### known() {#abb29ecf5d88b1a460f8836201c0e72cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OffsetSpan::known (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; V)</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<p>Referenced by <a href="#a7ee90d1ce6c5d290375e1c3e5abf11f2">knownAfter</a> and <a href="#a2ec0d64d71c543e76d24244861390d7d">knownBefore</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
