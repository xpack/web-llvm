---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/scalednumberbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ScaledNumberBase` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::ScaledNumberBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">llvm/Support/ScaledNumber.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalednumber">ScaledNumber&lt;DigitsT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simple representation of a scaled number. <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalednumber">ScaledNumber&lt;DigitsT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simple representation of a scaled number. <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfd88036fbe0e4dffa9488df65cb7d79">dump</a> (uint64_t D, int16_t E, int Width)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa69813e836793123b14be88585fd29bc">print</a> (raw_ostream &amp;OS, uint64_t D, int16_t E, int Width, unsigned Precision)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac19c88b3b4cddc454681f6650e130733">toString</a> (uint64_t D, int16_t E, int Width, unsigned Precision)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e272c55d29857f950d2f777c5f2a3a4">countLeadingZeros32</a> (uint32_t N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b5e7c1354f6907638d72d82e6f70af9">countLeadingZeros64</a> (uint64_t N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa2af28321f8882ed9f3636b25ebe3e9">getHalf</a> (uint64_t N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; uint64_t, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe42176d3878695a8d7991af3439783f">splitSigned</a> (int64_t N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93c62a567080c027645eba55c74d9d03">joinSigned</a> (uint64_t U, bool IsNeg)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a688aa1569355f832c6963c66f1a1b9cd">DefaultPrecision</a> = 10</td>
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


<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### countLeadingZeros32() {#a5e272c55d29857f950d2f777c5f2a3a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ScaledNumberBase::countLeadingZeros32 (uint32_t N)</td>
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



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### countLeadingZeros64() {#a1b5e7c1354f6907638d72d82e6f70af9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ScaledNumberBase::countLeadingZeros64 (uint64_t N)</td>
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



<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#ac19c88b3b4cddc454681f6650e130733">toString</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp/#abbfb15ef66003a1f34d28fa4fb90ac93">toStringAPFloat</a>.</p>

</div>
</div>

### dump() {#adfd88036fbe0e4dffa9488df65cb7d79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScaledNumberBase::dump (uint64_t D, int16_t E, int Width)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>, definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp">ScaledNumber.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#aa69813e836793123b14be88585fd29bc">print</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#a63df9d69985a62179143297a3e19bfaa">llvm::ScaledNumber&lt; uint64_t &gt;::dump</a>.</p>

</div>
</div>

### getHalf() {#afa2af28321f8882ed9f3636b25ebe3e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::ScaledNumberBase::getHalf (uint64_t N)</td>
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



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### joinSigned() {#a93c62a567080c027645eba55c74d9d03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::ScaledNumberBase::joinSigned (uint64_t U, bool IsNeg)</td>
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



<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#ad0d744f05898e32d01f73f8af3cd2071">INT64_MAX</a> and <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#ab21f12f372f67b8ff0aa3432336ede67">INT64_MIN</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#af9c95ee1e042eab1ec9f028be9f5cf8c">llvm::ScaledNumber&lt; uint64_t &gt;::scale</a> and <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#aac4d59e63e8bb2995912168ea3b3d8e1">llvm::ScaledNumber&lt; uint64_t &gt;::scaleByInverse</a>.</p>

</div>
</div>

### print() {#aa69813e836793123b14be88585fd29bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; ScaledNumberBase::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, uint64_t D, int16_t E, int Width, unsigned Precision)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>, definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp">ScaledNumber.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> and <a href="#ac19c88b3b4cddc454681f6650e130733">toString</a>.</p>


<p>Referenced by <a href="#adfd88036fbe0e4dffa9488df65cb7d79">dump</a> and <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#a12e80c71e0aef35ac69abbd5ebe3ba83">llvm::ScaledNumber&lt; uint64_t &gt;::print</a>.</p>

</div>
</div>

### splitSigned() {#afe42176d3878695a8d7991af3439783f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint64_t, bool &gt; llvm::ScaledNumberBase::splitSigned (int64_t N)</td>
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



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#ab21f12f372f67b8ff0aa3432336ede67">INT64_MIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13fac837bff23a12c3735d463020f37979de">Unsigned</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#af9c95ee1e042eab1ec9f028be9f5cf8c">llvm::ScaledNumber&lt; uint64_t &gt;::scale</a> and <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#aac4d59e63e8bb2995912168ea3b3d8e1">llvm::ScaledNumber&lt; uint64_t &gt;::scaleByInverse</a>.</p>

</div>
</div>

### toString() {#ac19c88b3b4cddc454681f6650e130733}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string ScaledNumberBase::toString (uint64_t D, int16_t E, int Width, unsigned Precision)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>, definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp">ScaledNumber.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp/#abf81dbb4051f89c8232ef1956a0d4a6b">appendDigit</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp/#af9cfb5453e82e2e1cef9a73c6b239d96">appendNumber</a>, <a href="#a1b5e7c1354f6907638d72d82e6f70af9">countLeadingZeros64</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp/#aa5c1fb1c341f7878396560689928f758">doesRoundUp</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp/#ad0491dc671de29b0724fd9102a6e3b43">stripTrailingZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp/#abbfb15ef66003a1f34d28fa4fb90ac93">toStringAPFloat</a> and <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a>.</p>


<p>Referenced by <a href="#aa69813e836793123b14be88585fd29bc">print</a> and <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#a628cc55e3eb3abc28be11f6fb90b948a">llvm::ScaledNumber&lt; uint64_t &gt;::toString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### DefaultPrecision {#a688aa1569355f832c6963c66f1a1b9cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ScaledNumberBase::DefaultPrecision = 10</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#a12e80c71e0aef35ac69abbd5ebe3ba83">llvm::ScaledNumber&lt; uint64_t &gt;::print</a> and <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#a628cc55e3eb3abc28be11f6fb90b948a">llvm::ScaledNumber&lt; uint64_t &gt;::toString</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp">ScaledNumber.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
