---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/fastmathflags
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FastMathFlags` Class

<p>Convenience struct for specifying and reasoning about fast-math flags. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FastMathFlags { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">llvm/IR/FMF.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#aecfe0e0af01be66fdc3e9097d14e2e5a">...</a> }</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a203bf21939cd93b6539ca11553a18e8c">FPMathOperator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad816f120cbd67deb804a9bcdba5081b4">FastMathFlags</a> ()=default</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb0c3a5710b70d5475767daa891def98">FastMathFlags</a> (unsigned F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af62c50049b7453573dc2e37fdbf1390b">operator&amp;=</a> (const FastMathFlags &amp;OtherFlags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8163c377a7b38e392222b67fe983de94">operator|=</a> (const FastMathFlags &amp;OtherFlags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3950cd6293c063f041cbb2e848b56a2">operator!=</a> (const FastMathFlags &amp;OtherFlags) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a135bd29ee8880fcab4b368c14a52eee8">any</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c72e480015b1ffdcd0382fa46437806">none</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4258eaf196d94abb5589f808431e3423">all</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bb66319ce38ba87a30adcee8305f65e">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a871def72ec0294092d71c3370c70228e">set</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f3a7d3a575da12ac2fec17849b7b916">allowReassoc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag queries. <a href="#a9f3a7d3a575da12ac2fec17849b7b916">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1d140361490d7847edf0c7503e3188a">noNaNs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39b529fcda9ee90b17a3e1fed732a22a">noInfs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a278a2e29bf56f2e2109fd35ae454b050">noSignedZeros</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c66c6bd0bb552d9e58e20617dc83e5d">allowReciprocal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8c80fc37943fda4be56cf1e0b6cb145">allowContract</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab09348cff01cf13d237779776c4fb887">approxFunc</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed1348ff378c2e9eea9c91aea4f3c429">isFast</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>'Fast' means all bits are set. <a href="#aed1348ff378c2e9eea9c91aea4f3c429">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd093480248d834428a5e8f9ad5a22dd">setAllowReassoc</a> (bool B=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag setters. <a href="#abd093480248d834428a5e8f9ad5a22dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbceb1c6e5c4b49f53b381a8fad9e12a">setNoNaNs</a> (bool B=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5fb387bdc497f49b0f556ed9f900560">setNoInfs</a> (bool B=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b87b2b5c4b6b7d083212a0c93684f72">setNoSignedZeros</a> (bool B=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a449c5c7d9356857fe89132ab9223069a">setAllowReciprocal</a> (bool B=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17e649128903d9aec55cf75d3c14c545">setAllowContract</a> (bool B=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc2bf5d2312d38f951004a8900fc4f7f">setApproxFunc</a> (bool B=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04a94a2848616d79534531d56bb82bfb">setFast</a> (bool B=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82446fc88a017bf06a8e090573334b78">print</a> (raw_ostream &amp;O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print fast-math flags to <span class="doxyComputerOutput">O</span>. <a href="#a82446fc88a017bf06a8e090573334b78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c80a13b07a906cacaec552ecb5220bb">Flags</a> = 0</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd492b88eb98461e692085ed400db114">getFast</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d10164e5ad75a27ed45c28516a8213b">intersectRewrite</a> (FastMathFlags LHS, FastMathFlags RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Intersect rewrite-based flags. <a href="#a0d10164e5ad75a27ed45c28516a8213b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a925d0244fda2e64578baffd3ed36ec76">unionValue</a> (FastMathFlags LHS, FastMathFlags RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Union value flags. <a href="#a925d0244fda2e64578baffd3ed36ec76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Convenience struct for specifying and reasoning about fast-math flags.</p>

<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#aecfe0e0af01be66fdc3e9097d14e2e5a}

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
<td class="doxyEnumItemName">AllowReassoc<a id="aecfe0e0af01be66fdc3e9097d14e2e5aa0dcb723027d8e065575a8ebbd96f390e"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 0))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoNaNs<a id="aecfe0e0af01be66fdc3e9097d14e2e5aa7444c7e9d01093ec21714f3d0557e593"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 1))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoInfs<a id="aecfe0e0af01be66fdc3e9097d14e2e5aa94d85382e80e8c29ee348dd249e6c252"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 2))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoSignedZeros<a id="aecfe0e0af01be66fdc3e9097d14e2e5aa6bd663e923d3b794eaac9f5b29224776"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 3))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowReciprocal<a id="aecfe0e0af01be66fdc3e9097d14e2e5aacc34bbc1654fb098a8a9a550eaeabfd1"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 4))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllowContract<a id="aecfe0e0af01be66fdc3e9097d14e2e5aa39ea4202b84ac863d1758d9d09c332eb"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 5))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ApproxFunc<a id="aecfe0e0af01be66fdc3e9097d14e2e5aa3331f3726d22d6291aa71c17597ee43d"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 6))</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### FPMathOperator {#a203bf21939cd93b6539ca11553a18e8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator">FPMathOperator</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a203bf21939cd93b6539ca11553a18e8c">FPMathOperator</a>.</p>


<p>Referenced by <a href="#a203bf21939cd93b6539ca11553a18e8c">FPMathOperator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### FastMathFlags() {#ad816f120cbd67deb804a9bcdba5081b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FastMathFlags::FastMathFlags ()</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>Referenced by <a href="#a0d10164e5ad75a27ed45c28516a8213b">intersectRewrite</a> and <a href="#a925d0244fda2e64578baffd3ed36ec76">unionValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### FastMathFlags() {#aeb0c3a5710b70d5475767daa891def98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FastMathFlags::FastMathFlags (unsigned F)</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#ae3950cd6293c063f041cbb2e848b56a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastMathFlags::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> &amp; OtherFlags)</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>

</div>
</div>

### operator&amp;=() {#af62c50049b7453573dc2e37fdbf1390b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FastMathFlags::operator&amp;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> &amp; OtherFlags)</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>

</div>
</div>

### operator|=() {#a8163c377a7b38e392222b67fe983de94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FastMathFlags::operator|= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> &amp; OtherFlags)</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### all() {#a4258eaf196d94abb5589f808431e3423}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastMathFlags::all ()</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>Referenced by <a href="#aed1348ff378c2e9eea9c91aea4f3c429">isFast</a>, <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a> and <a href="#a82446fc88a017bf06a8e090573334b78">print</a>.</p>

</div>
</div>

### allowContract() {#ad8c80fc37943fda4be56cf1e0b6cb145}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastMathFlags::allowContract ()</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>Reference <a href="#aecfe0e0af01be66fdc3e9097d14e2e5aa39ea4202b84ac863d1758d9d09c332eb">AllowContract</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a1969a1585363ca3069e708b24d19fda4">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::canOptimizeWithRsq</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#ab04f9a9acf8cd97627dc9b522188b0e8">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::emitMatrixMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a052318a71439e8ffd109c713d19b5926">instCombineSVEVectorFuseMulAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a4ba477f3fed71af44c6f80bee48c177c">mapToLLVMFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae87e464933c41dbf0ad62bdf89905831">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::optimizeWithRsq</a> and <a href="#a82446fc88a017bf06a8e090573334b78">print</a>.</p>

</div>
</div>

### allowReassoc() {#a9f3a7d3a575da12ac2fec17849b7b916}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastMathFlags::allowReassoc ()</td>
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

<p>Flag queries.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>Reference <a href="#aecfe0e0af01be66fdc3e9097d14e2e5aa0dcb723027d8e065575a8ebbd96f390e">AllowReassoc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-expandreductions-cpp-/#ae32d63d2aee7169e45cf696b040ccb66">anonymous{ExpandReductions.cpp}::expandReductions</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac633a4c4d399457c76640f7dea5ebcd7">llvm::InstCombinerImpl::foldFMulReassoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a4d180adab34368b65e2a43f64c7de814">getISDForVPIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#ab3118e33ed28deca370645b8b909fa5a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::lowerDotProduct</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a4ba477f3fed71af44c6f80bee48c177c">mapToLLVMFastMathFlags</a>, <a href="#a82446fc88a017bf06a8e090573334b78">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a68091149082c7a34c2198012a0800d6d">simplifyFAddInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7ae2d2701ffe4abf529cd4fb1ca26049">simplifyFDivInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a5b47854a993004418cb56068fe2dd9dd">simplifyFMAFMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a9a357829c347a3ab1d10dced5dbeb27a">simplifyFSubInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### allowReciprocal() {#a5c66c6bd0bb552d9e58e20617dc83e5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastMathFlags::allowReciprocal ()</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>Reference <a href="#aecfe0e0af01be66fdc3e9097d14e2e5aacc34bbc1654fb098a8a9a550eaeabfd1">AllowReciprocal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a4ba477f3fed71af44c6f80bee48c177c">mapToLLVMFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#af1f9568f6a2469baf6e85a9dc7b6c588">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::optimizeWithRcp</a> and <a href="#a82446fc88a017bf06a8e090573334b78">print</a>.</p>

</div>
</div>

### any() {#a135bd29ee8880fcab4b368c14a52eee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastMathFlags::any ()</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>

</div>
</div>

### approxFunc() {#ab09348cff01cf13d237779776c4fb887}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastMathFlags::approxFunc ()</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>Reference <a href="#aecfe0e0af01be66fdc3e9097d14e2e5aa3331f3726d22d6291aa71c17597ee43d">ApproxFunc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a1969a1585363ca3069e708b24d19fda4">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::canOptimizeWithRsq</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#a615317b48f533b3087abb06d3a96319c">llvm::AMDGPULibCalls::fold</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a4ba477f3fed71af44c6f80bee48c177c">mapToLLVMFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#af1f9568f6a2469baf6e85a9dc7b6c588">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::optimizeWithRcp</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae87e464933c41dbf0ad62bdf89905831">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::optimizeWithRsq</a>, <a href="#a82446fc88a017bf06a8e090573334b78">print</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae534b46b7607eb604ddd8c66baa8d2d1">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitFDiv</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae42afee90ff90eb3b8fa78ad91d8858b">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitSqrt</a>.</p>

</div>
</div>

### clear() {#a2bb66319ce38ba87a30adcee8305f65e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FastMathFlags::clear ()</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>Referenced by <a href="#a04a94a2848616d79534531d56bb82bfb">setFast</a>.</p>

</div>
</div>

### isFast() {#aed1348ff378c2e9eea9c91aea4f3c429}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastMathFlags::isFast ()</td>
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

<p>'Fast' means all bits are set.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>Reference <a href="#a4258eaf196d94abb5589f808431e3423">all</a>.</p>

</div>
</div>

### noInfs() {#a39b529fcda9ee90b17a3e1fed732a22a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastMathFlags::noInfs ()</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>Reference <a href="#aecfe0e0af01be66fdc3e9097d14e2e5aa94d85382e80e8c29ee348dd249e6c252">NoInfs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#adeba6094bcb53d87616b5a00ce2abc5b">llvm::computeKnownFPClass</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a5ae11456f5955d8499a96c9ba872caaf">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::emitFrexpDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a27bba7d498620b1d330d2ef77362f04f">foldFNegIntoConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9eeb1caaa920e692849cb94d64b7d66f">llvm::InstCombinerImpl::foldSelectIntoOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#afdc0c60200d744fe53a7f48e3f7e4bb0">foldSelectWithFCmpToFabs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp/#a035312f0450b07253231a7a9a7153b74">isKnownIntegral</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a4ba477f3fed71af44c6f80bee48c177c">mapToLLVMFastMathFlags</a>, <a href="#a82446fc88a017bf06a8e090573334b78">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7ae2d2701ffe4abf529cd4fb1ca26049">simplifyFDivInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aa6498365e4fa2bc006fc4116b4b9b990">simplifyFPOp</a>.</p>

</div>
</div>

### noNaNs() {#ac1d140361490d7847edf0c7503e3188a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastMathFlags::noNaNs ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>Reference <a href="#aecfe0e0af01be66fdc3e9097d14e2e5aa7444c7e9d01093ec21714f3d0557e593">NoNaNs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aec4ff9b2beab5c962935042f5b5758dd">llvm::canIgnoreSNaN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adeba6094bcb53d87616b5a00ce2abc5b">llvm::computeKnownFPClass</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a5ae11456f5955d8499a96c9ba872caaf">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::emitFrexpDiv</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-expandreductions-cpp-/#ae32d63d2aee7169e45cf696b040ccb66">anonymous{ExpandReductions.cpp}::expandReductions</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9eeb1caaa920e692849cb94d64b7d66f">llvm::InstCombinerImpl::foldSelectIntoOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#afdc0c60200d744fe53a7f48e3f7e4bb0">foldSelectWithFCmpToFabs</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a712be2c47b7dea0b22073dde0cf48fdc">llvm::RISCVTTIImpl::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aae6d0ca240375dadee805136932283f8">llvm::getRecurrenceIdentity</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp/#a035312f0450b07253231a7a9a7153b74">isKnownIntegral</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aee3b6e902d9adf32ef9483480b726fad">isKnownNonNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#aa35caaec45d90bbc9c564181b77c109e">llvm::RecurrenceDescriptor::isRecurrenceInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a4ba477f3fed71af44c6f80bee48c177c">mapToLLVMFastMathFlags</a>, <a href="#a82446fc88a017bf06a8e090573334b78">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a68091149082c7a34c2198012a0800d6d">simplifyFAddInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7ae2d2701ffe4abf529cd4fb1ca26049">simplifyFDivInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a5b47854a993004418cb56068fe2dd9dd">simplifyFMAFMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aa6498365e4fa2bc006fc4116b4b9b990">simplifyFPOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a95596f2a72e57df0c710e3dc7b225597">simplifyFRemInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a9a357829c347a3ab1d10dced5dbeb27a">simplifyFSubInst</a>.</p>

</div>
</div>

### none() {#a3c72e480015b1ffdcd0382fa46437806}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastMathFlags::none ()</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#a615317b48f533b3087abb06d3a96319c">llvm::AMDGPULibCalls::fold</a> and <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>.</p>

</div>
</div>

### noSignedZeros() {#a278a2e29bf56f2e2109fd35ae454b050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastMathFlags::noSignedZeros ()</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>Reference <a href="#aecfe0e0af01be66fdc3e9097d14e2e5aa6bd663e923d3b794eaac9f5b29224776">NoSignedZeros</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a982e49c60a2c0180bce8a7f0914c9ce3">llvm::InstCombinerImpl::fmulByZeroIsZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a27bba7d498620b1d330d2ef77362f04f">foldFNegIntoConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9eeb1caaa920e692849cb94d64b7d66f">llvm::InstCombinerImpl::foldSelectIntoOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aae6d0ca240375dadee805136932283f8">llvm::getRecurrenceIdentity</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#aa35caaec45d90bbc9c564181b77c109e">llvm::RecurrenceDescriptor::isRecurrenceInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a4ba477f3fed71af44c6f80bee48c177c">mapToLLVMFastMathFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a59d23c7a219bf242360a0b2ef67bc3c8">matchSelectPattern</a>, <a href="#a82446fc88a017bf06a8e090573334b78">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a68091149082c7a34c2198012a0800d6d">simplifyFAddInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7ae2d2701ffe4abf529cd4fb1ca26049">simplifyFDivInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a5b47854a993004418cb56068fe2dd9dd">simplifyFMAFMul</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a9a357829c347a3ab1d10dced5dbeb27a">simplifyFSubInst</a>.</p>

</div>
</div>

### print() {#a82446fc88a017bf06a8e090573334b78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FastMathFlags::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print fast-math flags to <span class="doxyComputerOutput">O</span>.</p>

<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>, definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/operator-cpp">Operator.cpp</a>.</p>


<p>References <a href="#a4258eaf196d94abb5589f808431e3423">all</a>, <a href="#ad8c80fc37943fda4be56cf1e0b6cb145">allowContract</a>, <a href="#a9f3a7d3a575da12ac2fec17849b7b916">allowReassoc</a>, <a href="#a5c66c6bd0bb552d9e58e20617dc83e5d">allowReciprocal</a>, <a href="#ab09348cff01cf13d237779776c4fb887">approxFunc</a>, <a href="#a39b529fcda9ee90b17a3e1fed732a22a">noInfs</a>, <a href="#ac1d140361490d7847edf0c7503e3188a">noNaNs</a> and <a href="#a278a2e29bf56f2e2109fd35ae454b050">noSignedZeros</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab1aea1feb3c30bbe8e073e27229ffb5e">llvm::operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#ae6a91bbf1cfed2d6ba572ca974c94161">llvm::VPRecipeWithIRFlags::printFlags</a>.</p>

</div>
</div>

### set() {#a871def72ec0294092d71c3370c70228e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FastMathFlags::set ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>Referenced by <a href="#a04a94a2848616d79534531d56bb82bfb">setFast</a> and <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>.</p>

</div>
</div>

### setAllowContract() {#a17e649128903d9aec55cf75d3c14c545}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FastMathFlags::setAllowContract (bool B=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>References <a href="#aecfe0e0af01be66fdc3e9097d14e2e5aa39ea4202b84ac863d1758d9d09c332eb">AllowContract</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ab35a64e2f9201e7d20db1ff384218ab1">getDecodedFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#af44641b38a715b1326e5000ae611c9ea">llvm::VPRecipeWithIRFlags::getFastMathFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a52d76a2a202f5538638a0258cdd83872">mapFromLLVMFastMathFlags</a>.</p>

</div>
</div>

### setAllowReassoc() {#abd093480248d834428a5e8f9ad5a22dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FastMathFlags::setAllowReassoc (bool B=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Flag setters.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>References <a href="#aecfe0e0af01be66fdc3e9097d14e2e5aa0dcb723027d8e065575a8ebbd96f390e">AllowReassoc</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ab35a64e2f9201e7d20db1ff384218ab1">getDecodedFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#af44641b38a715b1326e5000ae611c9ea">llvm::VPRecipeWithIRFlags::getFastMathFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a52d76a2a202f5538638a0258cdd83872">mapFromLLVMFastMathFlags</a>.</p>

</div>
</div>

### setAllowReciprocal() {#a449c5c7d9356857fe89132ab9223069a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FastMathFlags::setAllowReciprocal (bool B=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>References <a href="#aecfe0e0af01be66fdc3e9097d14e2e5aacc34bbc1654fb098a8a9a550eaeabfd1">AllowReciprocal</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ab35a64e2f9201e7d20db1ff384218ab1">getDecodedFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#af44641b38a715b1326e5000ae611c9ea">llvm::VPRecipeWithIRFlags::getFastMathFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a52d76a2a202f5538638a0258cdd83872">mapFromLLVMFastMathFlags</a>.</p>

</div>
</div>

### setApproxFunc() {#acc2bf5d2312d38f951004a8900fc4f7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FastMathFlags::setApproxFunc (bool B=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>References <a href="#aecfe0e0af01be66fdc3e9097d14e2e5aa3331f3726d22d6291aa71c17597ee43d">ApproxFunc</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ab35a64e2f9201e7d20db1ff384218ab1">getDecodedFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#af44641b38a715b1326e5000ae611c9ea">llvm::VPRecipeWithIRFlags::getFastMathFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a52d76a2a202f5538638a0258cdd83872">mapFromLLVMFastMathFlags</a>.</p>

</div>
</div>

### setFast() {#a04a94a2848616d79534531d56bb82bfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FastMathFlags::setFast (bool B=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a2bb66319ce38ba87a30adcee8305f65e">clear</a> and <a href="#a871def72ec0294092d71c3370c70228e">set</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a23dda302945a17be7141fb6e3037f0e8">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::expandDivRem32</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ab35a64e2f9201e7d20db1ff384218ab1">getDecodedFastMathFlags</a> and <a href="#acd492b88eb98461e692085ed400db114">getFast</a>.</p>

</div>
</div>

### setNoInfs() {#ad5fb387bdc497f49b0f556ed9f900560}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FastMathFlags::setNoInfs (bool B=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#aecfe0e0af01be66fdc3e9097d14e2e5aa94d85382e80e8c29ee348dd249e6c252">NoInfs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ab35a64e2f9201e7d20db1ff384218ab1">getDecodedFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#af44641b38a715b1326e5000ae611c9ea">llvm::VPRecipeWithIRFlags::getFastMathFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a52d76a2a202f5538638a0258cdd83872">mapFromLLVMFastMathFlags</a>.</p>

</div>
</div>

### setNoNaNs() {#abbceb1c6e5c4b49f53b381a8fad9e12a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FastMathFlags::setNoNaNs (bool B=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#aecfe0e0af01be66fdc3e9097d14e2e5aa7444c7e9d01093ec21714f3d0557e593">NoNaNs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ab35a64e2f9201e7d20db1ff384218ab1">getDecodedFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#af44641b38a715b1326e5000ae611c9ea">llvm::VPRecipeWithIRFlags::getFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a484f974fc232e862a87a6380d3a7587d">llvm::RecurrenceDescriptor::isReductionPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a52d76a2a202f5538638a0258cdd83872">mapFromLLVMFastMathFlags</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a06396b4dd155b05f3faeb9dc674c3787">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitMinNum</a>.</p>

</div>
</div>

### setNoSignedZeros() {#a9b87b2b5c4b6b7d083212a0c93684f72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FastMathFlags::setNoSignedZeros (bool B=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#aecfe0e0af01be66fdc3e9097d14e2e5aa6bd663e923d3b794eaac9f5b29224776">NoSignedZeros</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ab35a64e2f9201e7d20db1ff384218ab1">getDecodedFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#af44641b38a715b1326e5000ae611c9ea">llvm::VPRecipeWithIRFlags::getFastMathFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a52d76a2a202f5538638a0258cdd83872">mapFromLLVMFastMathFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf62ca503c047621e9b9047c548f231f">llvm::matchDecomposedSelectPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ac8365a0b8aaec9be1cfb749a4a9526d6">matchFMulByZeroIfResultEqZero</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Flags {#a8c80a13b07a906cacaec552ecb5220bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FastMathFlags::Flags = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getFast() {#acd492b88eb98461e692085ed400db114}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastMathFlags llvm::FastMathFlags::getFast ()</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>Reference <a href="#a04a94a2848616d79534531d56bb82bfb">setFast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#ae3b1b80ef450d6706f42f3a929e51ce5">llvm::RecurrenceDescriptor::AddReductionVar</a>.</p>

</div>
</div>

### intersectRewrite() {#a0d10164e5ad75a27ed45c28516a8213b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastMathFlags llvm::FastMathFlags::intersectRewrite (<a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> RHS)</td>
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

<p>Intersect rewrite-based flags.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>References <a href="#aecfe0e0af01be66fdc3e9097d14e2e5aa39ea4202b84ac863d1758d9d09c332eb">AllowContract</a>, <a href="#aecfe0e0af01be66fdc3e9097d14e2e5aa0dcb723027d8e065575a8ebbd96f390e">AllowReassoc</a>, <a href="#aecfe0e0af01be66fdc3e9097d14e2e5aacc34bbc1654fb098a8a9a550eaeabfd1">AllowReciprocal</a>, <a href="#aecfe0e0af01be66fdc3e9097d14e2e5aa3331f3726d22d6291aa71c17597ee43d">ApproxFunc</a>, <a href="#ad816f120cbd67deb804a9bcdba5081b4">FastMathFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a0adb0a856adef09fd017379f4644ba4e">convertFSqrtDivIntoFMul</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#aadd274cfa4ae19782aa85d9f162925c6">foldSelectIntoAddConstant</a>.</p>

</div>
</div>

### unionValue() {#a925d0244fda2e64578baffd3ed36ec76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastMathFlags llvm::FastMathFlags::unionValue (<a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> RHS)</td>
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

<p>Union value flags.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a>.</p>


<p>References <a href="#ad816f120cbd67deb804a9bcdba5081b4">FastMathFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="#aecfe0e0af01be66fdc3e9097d14e2e5aa94d85382e80e8c29ee348dd249e6c252">NoInfs</a>, <a href="#aecfe0e0af01be66fdc3e9097d14e2e5aa7444c7e9d01093ec21714f3d0557e593">NoNaNs</a>, <a href="#aecfe0e0af01be66fdc3e9097d14e2e5aa6bd663e923d3b794eaac9f5b29224776">NoSignedZeros</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a0adb0a856adef09fd017379f4644ba4e">convertFSqrtDivIntoFMul</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#aadd274cfa4ae19782aa85d9f162925c6">foldSelectIntoAddConstant</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fmf-h">FMF.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/operator-cpp">Operator.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
