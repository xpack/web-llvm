---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/lowertypetests/bytearraybuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ByteArrayBuilder` Struct

<p>This class is used to build a byte array containing overlapping bit sets. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::lowertypetests::ByteArrayBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">llvm/Transforms/IPO/LowerTypeTests.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a456d9afc9af28332a92e0a67cbbc7098">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e7d04e07fc7f640097f08663ec3ccee">ByteArrayBuilder</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefcc42b423b9473d155867e579682a9e">allocate</a> (const std::set&lt; uint64_t &gt; &amp;Bits, uint64_t BitSize, uint64_t &amp;AllocByteOffset, uint8_t &amp;AllocMask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate BitSize bits in the byte array where Bits contains the bits to set. <a href="#aefcc42b423b9473d155867e579682a9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9bf25f047271def1203635a5725eeff">Bytes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The byte array built so far. <a href="#ab9bf25f047271def1203635a5725eeff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49082c502ad79672b9f721424779a643">BitAllocs</a>[BitsPerByte]</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of bytes allocated so far for each of the bits. <a href="#a49082c502ad79672b9f721424779a643">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class is used to build a byte array containing overlapping bit sets.</p>


<p>By loading from indexed offsets into the byte array and applying a mask, a program can test bits from the bit set with a relatively short instruction sequence. For example, suppose we have 15 bit sets to lay out:</p>


<p>A (16 bits), B (15 bits), C (14 bits), D (13 bits), E (12 bits), F (11 bits), G (10 bits), H (9 bits), I (7 bits), J (6 bits), K (5 bits), L (4 bits), M (3 bits), N (2 bits), O (1 bit)</p>


<p>These bits can be laid out in a 16-byte array like this:</p>



<pre><code>  Byte Offset
0123456789ABCDEF
</code></pre>


<p>Bit 7 HHHHHHHHHIIIIIII 6 GGGGGGGGGGJJJJJJ 5 FFFFFFFFFFFKKKKK 4 EEEEEEEEEEEELLLL 3 DDDDDDDDDDDDDMMM 2 CCCCCCCCCCCCCCNN 1 BBBBBBBBBBBBBBBO 0 AAAAAAAAAAAAAAAA</p>


<p>For example, to test bit X of A, we evaluate ((bits[X] &amp; 1) != 0), or to test bit X of I, we evaluate ((bits[9 + X] &amp; 0x80) != 0). This can be done in 1-2 machine instructions on x86, or 4-6 instructions on <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a>.</p>


<p>This is a byte array, rather than (say) a 2-byte array or a 4-byte array, because for one thing it gives us better packing (the more bins there are, the less evenly they will be filled), and for another, the instruction sequences can be slightly shorter, both on x86 and <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a>.</p>


<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a456d9afc9af28332a92e0a67cbbc7098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BitsPerByte<a id="a456d9afc9af28332a92e0a67cbbc7098a961b1f972e23c16ecc4ddffe1ddfbdca"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ByteArrayBuilder() {#a7e7d04e07fc7f640097f08663ec3ccee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::lowertypetests::ByteArrayBuilder::ByteArrayBuilder ()</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a>.</p>


<p>Reference <a href="#a49082c502ad79672b9f721424779a643">BitAllocs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allocate() {#aefcc42b423b9473d155867e579682a9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ByteArrayBuilder::allocate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::set&lt; uint64_t &gt; &amp; Bits, uint64_t BitSize, uint64_t &amp; AllocByteOffset, uint8_t &amp; AllocMask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate BitSize bits in the byte array where Bits contains the bits to set.</p>


<p>AllocByteOffset is set to the offset within the byte array and AllocMask is set to the bitmask for those bits. This uses the LPT (Longest Processing Time) multiprocessor scheduling algorithm to lay out the bits efficiently; the pass allocates bit sets in decreasing size order.</p>


<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a>, definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a49082c502ad79672b9f721424779a643">BitAllocs</a>, <a href="#a456d9afc9af28332a92e0a67cbbc7098a961b1f972e23c16ecc4ddffe1ddfbdca">BitsPerByte</a>, <a href="#ab9bf25f047271def1203635a5725eeff">Bytes</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BitAllocs {#a49082c502ad79672b9f721424779a643}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::lowertypetests::ByteArrayBuilder::BitAllocs[BitsPerByte]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of bytes allocated so far for each of the bits.</p>

<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a>.</p>


<p>Referenced by <a href="#aefcc42b423b9473d155867e579682a9e">allocate</a> and <a href="#a7e7d04e07fc7f640097f08663ec3ccee">ByteArrayBuilder</a>.</p>

</div>
</div>

### Bytes {#ab9bf25f047271def1203635a5725eeff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint8_t&gt; llvm::lowertypetests::ByteArrayBuilder::Bytes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The byte array built so far.</p>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a>.</p>


<p>Referenced by <a href="#aefcc42b423b9473d155867e579682a9e">allocate</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
