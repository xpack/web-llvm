---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codegencoverage
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CodeGenCoverage` Class



## Declaration

<div class="doxyDeclaration">
class llvm::CodeGenCoverage { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegencoverage-h">llvm/Support/CodeGenCoverage.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa14773f2f3151373cc761d73a1f86793">const_covered_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a99a6a1febf299d51eab9d14ce188afe5">BitVector::const_set_bits_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50ba1d371442303d1edf6410e2c45e0f">CodeGenCoverage</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69ad0fba8847b22164139f79219185a0">setCovered</a> (uint64_t RuleID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43502e038eb7c66f349b8fe579360305">isCovered</a> (uint64_t RuleID) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#aa14773f2f3151373cc761d73a1f86793">const_covered_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a889dc10635a4f2465e9cafdc38c6bbab">covered</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af03b9404e0ae4bd9abacbd8cf9221240">parse</a> (MemoryBuffer &amp;Buffer, StringRef BackendName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3df1d6092ed500be1f2e3ca76d3e844">emit</a> (StringRef FilePrefix, StringRef BackendName) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87e5c0336bfb2cf7df1395d5d652b023">reset</a> ()</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a637b274c4cf0c87e675f76fd72d1a0b6">RuleCoverage</a></td>
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


<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegencoverage-h">CodeGenCoverage.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_covered\_iterator {#aa14773f2f3151373cc761d73a1f86793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CodeGenCoverage::const_covered_iterator =  BitVector::const_set_bits_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegencoverage-h">CodeGenCoverage.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CodeGenCoverage() {#a50ba1d371442303d1edf6410e2c45e0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeGenCoverage::CodeGenCoverage ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegencoverage-h">CodeGenCoverage.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### covered() {#a889dc10635a4f2465e9cafdc38c6bbab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; CodeGenCoverage::const_covered_iterator &gt; CodeGenCoverage::covered ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegencoverage-h">CodeGenCoverage.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/support/codegencoverage-cpp">CodeGenCoverage.cpp</a>.</p>


<p>Reference <a href="#a637b274c4cf0c87e675f76fd72d1a0b6">RuleCoverage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a07f4133008c7c11a0154735071ffcc19">llvm::InstructionSelect::selectMachineFunction</a>.</p>

</div>
</div>

### emit() {#af3df1d6092ed500be1f2e3ca76d3e844}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenCoverage::emit (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FilePrefix, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> BackendName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegencoverage-h">CodeGenCoverage.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/support/codegencoverage-cpp">CodeGenCoverage.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/instructionselect-cpp/#ad7f1838fb35a2bd8c7a0d1e76706ea7e">CoveragePrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/process/#afee014293ce837f92658166fc36a2d15">llvm::sys::Process::getProcessId</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695ac999fafdcc991e61bbc2df56a4310083">llvm::sys::fs::OF_Append</a>, <a href="#a637b274c4cf0c87e675f76fd72d1a0b6">RuleCoverage</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a13c1b5a253da5da49ce33d03dc1efc07">llvm::to_string</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a07f4133008c7c11a0154735071ffcc19">llvm::InstructionSelect::selectMachineFunction</a>.</p>

</div>
</div>

### isCovered() {#a43502e038eb7c66f349b8fe579360305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenCoverage::isCovered (uint64_t RuleID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegencoverage-h">CodeGenCoverage.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/support/codegencoverage-cpp">CodeGenCoverage.cpp</a>.</p>


<p>Reference <a href="#a637b274c4cf0c87e675f76fd72d1a0b6">RuleCoverage</a>.</p>

</div>
</div>

### parse() {#af03b9404e0ae4bd9abacbd8cf9221240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenCoverage::parse (<a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &amp; Buffer, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> BackendName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegencoverage-h">CodeGenCoverage.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/support/codegencoverage-cpp">CodeGenCoverage.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#ae4604d3bedbb15e6c516f9357d3b773e">llvm::MemoryBuffer::getBufferEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#af1972b9a0324e0311ad641eac2de2b7f">llvm::MemoryBuffer::getBufferStart</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dba8e5f3adee38c8fccc13c1f3be0143796">llvm::native</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a7787225426474d5f50e2f0c4e3c16b1c">llvm::support::endian::read64</a> and <a href="#a69ad0fba8847b22164139f79219185a0">setCovered</a>.</p>

</div>
</div>

### reset() {#a87e5c0336bfb2cf7df1395d5d652b023}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeGenCoverage::reset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegencoverage-h">CodeGenCoverage.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/support/codegencoverage-cpp">CodeGenCoverage.cpp</a>.</p>


<p>Reference <a href="#a637b274c4cf0c87e675f76fd72d1a0b6">RuleCoverage</a>.</p>

</div>
</div>

### setCovered() {#a69ad0fba8847b22164139f79219185a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeGenCoverage::setCovered (uint64_t RuleID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegencoverage-h">CodeGenCoverage.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/support/codegencoverage-cpp">CodeGenCoverage.cpp</a>.</p>


<p>Reference <a href="#a637b274c4cf0c87e675f76fd72d1a0b6">RuleCoverage</a>.</p>


<p>Referenced by <a href="#af03b9404e0ae4bd9abacbd8cf9221240">parse</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### RuleCoverage {#a637b274c4cf0c87e675f76fd72d1a0b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::CodeGenCoverage::RuleCoverage</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegencoverage-h">CodeGenCoverage.h</a>.</p>


<p>Referenced by <a href="#a889dc10635a4f2465e9cafdc38c6bbab">covered</a>, <a href="#af3df1d6092ed500be1f2e3ca76d3e844">emit</a>, <a href="#a43502e038eb7c66f349b8fe579360305">isCovered</a>, <a href="#a87e5c0336bfb2cf7df1395d5d652b023">reset</a> and <a href="#a69ad0fba8847b22164139f79219185a0">setCovered</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegencoverage-h">CodeGenCoverage.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/codegencoverage-cpp">CodeGenCoverage.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
