---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/lowertypetests/bitsetinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BitSetInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::lowertypetests::BitSetInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">llvm/Transforms/IPO/LowerTypeTests.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9173daff4c362200c69a3e77ab6aeaaf">isSingleOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad415eb27cc01864ba9d7cf3673cd9096">isAllOnes</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0986e6682520b5119e7aeea9e9bf908f">containsGlobalOffset</a> (uint64_t Offset) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ea6be22983452a3ada83dd719caf787">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::set&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9056d542f9c590c71d90c5b5d4c1ef06">Bits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f37c08c8a876745f75707df1462d463">ByteOffset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7c30a369762ee2247cebe8c310e52ef">BitSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ecb18819ffce351312accf16feea3b6">AlignLog2</a></td>
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


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### containsGlobalOffset() {#a0986e6682520b5119e7aeea9e9bf908f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BitSetInfo::containsGlobalOffset (uint64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a>, definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>


<p>References <a href="#a6ecb18819ffce351312accf16feea3b6">AlignLog2</a>, <a href="#a9056d542f9c590c71d90c5b5d4c1ef06">Bits</a>, <a href="#aa7c30a369762ee2247cebe8c310e52ef">BitSize</a>, <a href="#a8f37c08c8a876745f75707df1462d463">ByteOffset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### isAllOnes() {#ad415eb27cc01864ba9d7cf3673cd9096}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lowertypetests::BitSetInfo::isAllOnes ()</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a>.</p>


<p>References <a href="#a9056d542f9c590c71d90c5b5d4c1ef06">Bits</a> and <a href="#aa7c30a369762ee2247cebe8c310e52ef">BitSize</a>.</p>


<p>Referenced by <a href="#a2ea6be22983452a3ada83dd719caf787">print</a>.</p>

</div>
</div>

### isSingleOffset() {#a9173daff4c362200c69a3e77ab6aeaaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lowertypetests::BitSetInfo::isSingleOffset ()</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a>.</p>


<p>Reference <a href="#a9056d542f9c590c71d90c5b5d4c1ef06">Bits</a>.</p>

</div>
</div>

### print() {#a2ea6be22983452a3ada83dd719caf787}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitSetInfo::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>


<p>References <a href="#a6ecb18819ffce351312accf16feea3b6">AlignLog2</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a9056d542f9c590c71d90c5b5d4c1ef06">Bits</a>, <a href="#aa7c30a369762ee2247cebe8c310e52ef">BitSize</a>, <a href="#a8f37c08c8a876745f75707df1462d463">ByteOffset</a> and <a href="#ad415eb27cc01864ba9d7cf3673cd9096">isAllOnes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AlignLog2 {#a6ecb18819ffce351312accf16feea3b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::lowertypetests::BitSetInfo::AlignLog2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/lowertypetests/bitsetbuilder/#aa21d510ab0919fcc10fbbb02ead13dab">llvm::lowertypetests::BitSetBuilder::build</a>, <a href="#a0986e6682520b5119e7aeea9e9bf908f">containsGlobalOffset</a> and <a href="#a2ea6be22983452a3ada83dd719caf787">print</a>.</p>

</div>
</div>

### Bits {#a9056d542f9c590c71d90c5b5d4c1ef06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt;uint64_t&gt; llvm::lowertypetests::BitSetInfo::Bits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/lowertypetests/bitsetbuilder/#aa21d510ab0919fcc10fbbb02ead13dab">llvm::lowertypetests::BitSetBuilder::build</a>, <a href="#a0986e6682520b5119e7aeea9e9bf908f">containsGlobalOffset</a>, <a href="#ad415eb27cc01864ba9d7cf3673cd9096">isAllOnes</a>, <a href="#a9173daff4c362200c69a3e77ab6aeaaf">isSingleOffset</a> and <a href="#a2ea6be22983452a3ada83dd719caf787">print</a>.</p>

</div>
</div>

### BitSize {#aa7c30a369762ee2247cebe8c310e52ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::lowertypetests::BitSetInfo::BitSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/lowertypetests/bitsetbuilder/#aa21d510ab0919fcc10fbbb02ead13dab">llvm::lowertypetests::BitSetBuilder::build</a>, <a href="#a0986e6682520b5119e7aeea9e9bf908f">containsGlobalOffset</a>, <a href="#ad415eb27cc01864ba9d7cf3673cd9096">isAllOnes</a> and <a href="#a2ea6be22983452a3ada83dd719caf787">print</a>.</p>

</div>
</div>

### ByteOffset {#a8f37c08c8a876745f75707df1462d463}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::lowertypetests::BitSetInfo::ByteOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/lowertypetests/bitsetbuilder/#aa21d510ab0919fcc10fbbb02ead13dab">llvm::lowertypetests::BitSetBuilder::build</a>, <a href="#a0986e6682520b5119e7aeea9e9bf908f">containsGlobalOffset</a> and <a href="#a2ea6be22983452a3ada83dd719caf787">print</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
