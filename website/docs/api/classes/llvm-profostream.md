---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/profostream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ProfOStream` Class



## Declaration

<div class="doxyDeclaration">
class llvm::ProfOStream { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af75ffd6173485c71c44b00cbd90d5b37">ProfOStream</a> (raw_fd_ostream &amp;FD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab5d31d08702b629633bfe8980c3a71b">ProfOStream</a> (raw_string_ostream &amp;STR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a191995415d5b2e7ca2709b6cd8dad00e">tell</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb709e9ed0068ee21ae3bc153f5bef68">write</a> (uint64_t V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2268681061e7755f52d4014f75071ce">write32</a> (uint32_t V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c9e4788ec643ac424ec9c67da737316">writeByte</a> (uint8_t V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52299b07451a31e9fc5a62e305d5fe21">patch</a> (ArrayRef&lt; PatchItem &gt; P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4b589bc309ad6d0c4f38f11bde18909">IsFDOStream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b9a2017697fb95a906f7d5259e3420d">OS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/support/endian/writer">support::endian::Writer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdd2c0f38bda96833bed279811c21737">LE</a></td>
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


<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ProfOStream() {#af75ffd6173485c71c44b00cbd90d5b37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ProfOStream::ProfOStream (<a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> &amp; FD)</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="#ac4b589bc309ad6d0c4f38f11bde18909">IsFDOStream</a>, <a href="#acdd2c0f38bda96833bed279811c21737">LE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="#a0b9a2017697fb95a906f7d5259e3420d">OS</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

### ProfOStream() {#aab5d31d08702b629633bfe8980c3a71b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ProfOStream::ProfOStream (<a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream">raw_string_ostream</a> &amp; STR)</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="#ac4b589bc309ad6d0c4f38f11bde18909">IsFDOStream</a>, <a href="#acdd2c0f38bda96833bed279811c21737">LE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a> and <a href="#a0b9a2017697fb95a906f7d5259e3420d">OS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### patch() {#a52299b07451a31e9fc5a62e305d5fe21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ProfOStream::patch (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/patchitem">PatchItem</a> &gt; P)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a108ca68c609b3e8c00918a68d26905fa">llvm::support::endian::byte_swap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac4b589bc309ad6d0c4f38f11bde18909">IsFDOStream</a>, <a href="#a0b9a2017697fb95a906f7d5259e3420d">OS</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a9e2a27de71f137279ac47e6edd4abc47">llvm::raw_fd_ostream::seek</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a> and <a href="#afb709e9ed0068ee21ae3bc153f5bef68">write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp/#ac9e41242e334c46de6b89a79135b8ca3">writeMemProfV2</a> and <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp/#a8cad3eb0bfb43723ba5976243ec78090">writeMemProfV3</a>.</p>

</div>
</div>

### tell() {#a191995415d5b2e7ca2709b6cd8dad00e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::ProfOStream::tell ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>Reference <a href="#a0b9a2017697fb95a906f7d5259e3420d">OS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp/#ac9e41242e334c46de6b89a79135b8ca3">writeMemProfV2</a> and <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp/#a8cad3eb0bfb43723ba5976243ec78090">writeMemProfV3</a>.</p>

</div>
</div>

### write() {#afb709e9ed0068ee21ae3bc153f5bef68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ProfOStream::write (uint64_t V)</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>Reference <a href="#acdd2c0f38bda96833bed279811c21737">LE</a>.</p>


<p>Referenced by <a href="#a52299b07451a31e9fc5a62e305d5fe21">patch</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp/#afe089e351de37cd105f3fae18a0bd13e">writeMemProfSchema</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp/#ac9e41242e334c46de6b89a79135b8ca3">writeMemProfV2</a> and <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp/#a8cad3eb0bfb43723ba5976243ec78090">writeMemProfV3</a>.</p>

</div>
</div>

### write32() {#aa2268681061e7755f52d4014f75071ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ProfOStream::write32 (uint32_t V)</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>Reference <a href="#acdd2c0f38bda96833bed279811c21737">LE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp/#ab055eb88701395ca69a88d4958bc2fda">writeMemProfCallStackArray</a>.</p>

</div>
</div>

### writeByte() {#a3c9e4788ec643ac424ec9c67da737316}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ProfOStream::writeByte (uint8_t V)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>Reference <a href="#acdd2c0f38bda96833bed279811c21737">LE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IsFDOStream {#ac4b589bc309ad6d0c4f38f11bde18909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ProfOStream::IsFDOStream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>Referenced by <a href="#a52299b07451a31e9fc5a62e305d5fe21">patch</a>, <a href="#af75ffd6173485c71c44b00cbd90d5b37">ProfOStream</a> and <a href="#aab5d31d08702b629633bfe8980c3a71b">ProfOStream</a>.</p>

</div>
</div>

### LE {#acdd2c0f38bda96833bed279811c21737}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::endian::Writer llvm::ProfOStream::LE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>Referenced by <a href="#af75ffd6173485c71c44b00cbd90d5b37">ProfOStream</a>, <a href="#aab5d31d08702b629633bfe8980c3a71b">ProfOStream</a>, <a href="#afb709e9ed0068ee21ae3bc153f5bef68">write</a>, <a href="#aa2268681061e7755f52d4014f75071ce">write32</a> and <a href="#a3c9e4788ec643ac424ec9c67da737316">writeByte</a>.</p>

</div>
</div>

### OS {#a0b9a2017697fb95a906f7d5259e3420d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream&amp; llvm::ProfOStream::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a>.</p>


<p>Referenced by <a href="#a52299b07451a31e9fc5a62e305d5fe21">patch</a>, <a href="#af75ffd6173485c71c44b00cbd90d5b37">ProfOStream</a>, <a href="#aab5d31d08702b629633bfe8980c3a71b">ProfOStream</a>, <a href="#a191995415d5b2e7ca2709b6cd8dad00e">tell</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp/#a433aa7814d2ec5eb3ff767522fcceef9">writeMemProfCallStacks</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp/#ae0bb182de61b858a03a99b3ea2662e1c">writeMemProfFrameArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp/#a953c955a410efd221c0a76d209891718">writeMemProfFrames</a> and <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp/#a38203c3ce4c256dc041166735c6e007e">writeMemProfRecords</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp">InstrProfWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
