---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/coverage/mcdcrecord/testvector
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TestVector` Class Reference

<p>Emulate <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;CondState&gt;</a> with a pair of <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::coverage::MCDCRecord::TestVector { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">llvm/ProfileData/Coverage/CoverageMapping.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaef697dad18728965b52f653af843e94">TestVector</a> (unsigned N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>~DontCare <a href="#aaef697dad18728965b52f653af843e94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/coverage/mcdcrecord/#abfea249cd51ba9478b1e85bbc3508418">CondState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e812775a9aa3bf1fa20fac1dbffa9b1">operator[]</a> (int I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emulate RHS <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aaaa3b341d046538bc32d1fa942c14dd0">SmallVector::operator[]</a>. <a href="#a3e812775a9aa3bf1fa20fac1dbffa9b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2635eb18be1bc5306d514cd0de368598">getIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Equivalent to buildTestVector's Index. <a href="#a2635eb18be1bc5306d514cd0de368598">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd19c8408dac3fe64ae2a37c37d643ae">set</a> (int I, CondState Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the condition <span class="doxyComputerOutput">Val</span> at position <span class="doxyComputerOutput">I</span>. <a href="#abd19c8408dac3fe64ae2a37c37d643ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedb849ca69c0d7d9a5bc6569f7097aab">push_back</a> (CondState Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emulate <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">SmallVector::push_back</a>. <a href="#aedb849ca69c0d7d9a5bc6569f7097aab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed7a4c94015e69c2f8b786c2fee0f953">getDifferences</a> (const TestVector &amp;B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For each element: <a href="#aed7a4c94015e69c2f8b786c2fee0f953">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab764bc2c9252128b931774cc05652f75">Values</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3562d1bae529839d22b3dfce85e67fb">Visited</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True/False (False when DontCare) <a href="#ad3562d1bae529839d22b3dfce85e67fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Emulate <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;CondState&gt;</a> with a pair of <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a>.</p>



<pre><code>     True  False DontCare (Impossible)
</code></pre>


<p>Values: True False False True Visited: True True False False</p>


<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TestVector() {#aaef697dad18728965b52f653af843e94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::MCDCRecord::TestVector::TestVector (unsigned N)</td>
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

<p>~DontCare</p>


<p>Default values are filled with DontCare.</p>


<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#aed7a4c94015e69c2f8b786c2fee0f953">getDifferences</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#a3e812775a9aa3bf1fa20fac1dbffa9b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CondState llvm::coverage::MCDCRecord::TestVector::operator[] (int I)</td>
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

<p>Emulate RHS <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aaaa3b341d046538bc32d1fa942c14dd0">SmallVector::operator[]</a>.</p>

<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/mcdcrecord/#abfea249cd51ba9478b1e85bbc3508418a174b6fce191ea66ffb1e674418d159f1">llvm::coverage::MCDCRecord::MCDC_DontCare</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/mcdcrecord/#abfea249cd51ba9478b1e85bbc3508418a653e0944fb44b406d675db307806460c">llvm::coverage::MCDCRecord::MCDC_False</a> and <a href="/web-llvm/docs/api/structs/llvm/coverage/mcdcrecord/#abfea249cd51ba9478b1e85bbc3508418a3b7b1235ae7885e1f859b0abc9c11988">llvm::coverage::MCDCRecord::MCDC_True</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getDifferences() {#aed7a4c94015e69c2f8b786c2fee0f953}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto llvm::coverage::MCDCRecord::TestVector::getDifferences (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/coverage/mcdcrecord/testvector">TestVector</a> &amp; B)</td>
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

<p>For each element:</p>


<ul class="doxyList ">
<li>False if either is DontCare</li>
<li>False if both have the same value</li>
<li>True if both have the opposite value ((A.Values ^ B.Values) &amp; A.Visited &amp; B.Visited) Dedicated to <a href="/web-llvm/docs/api/structs/llvm/coverage/mcdcrecord/#a75f33335df18ebee49fbe5b2d5b664a0">findIndependencePairs()</a>.</li>
</ul>

<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#aaef697dad18728965b52f653af843e94">TestVector</a>.</p>

</div>
</div>

### getIndex() {#a2635eb18be1bc5306d514cd0de368598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto llvm::coverage::MCDCRecord::TestVector::getIndex ()</td>
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

<p>Equivalent to buildTestVector's Index.</p>

<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### push\_back() {#aedb849ca69c0d7d9a5bc6569f7097aab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::coverage::MCDCRecord::TestVector::push_back (<a href="/web-llvm/docs/api/structs/llvm/coverage/mcdcrecord/#abfea249cd51ba9478b1e85bbc3508418">CondState</a> Val)</td>
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

<p>Emulate <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">SmallVector::push_back</a>.</p>

<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/mcdcrecord/#abfea249cd51ba9478b1e85bbc3508418a174b6fce191ea66ffb1e674418d159f1">llvm::coverage::MCDCRecord::MCDC_DontCare</a> and <a href="/web-llvm/docs/api/structs/llvm/coverage/mcdcrecord/#abfea249cd51ba9478b1e85bbc3508418a3b7b1235ae7885e1f859b0abc9c11988">llvm::coverage::MCDCRecord::MCDC_True</a>.</p>

</div>
</div>

### set() {#abd19c8408dac3fe64ae2a37c37d643ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::coverage::MCDCRecord::TestVector::set (int I, <a href="/web-llvm/docs/api/structs/llvm/coverage/mcdcrecord/#abfea249cd51ba9478b1e85bbc3508418">CondState</a> Val)</td>
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

<p>Set the condition <span class="doxyComputerOutput">Val</span> at position <span class="doxyComputerOutput">I</span>.</p>


<p>This emulates LHS <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aaaa3b341d046538bc32d1fa942c14dd0">SmallVector::operator[]</a>.</p>


<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/mcdcrecord/#abfea249cd51ba9478b1e85bbc3508418a174b6fce191ea66ffb1e674418d159f1">llvm::coverage::MCDCRecord::MCDC_DontCare</a> and <a href="/web-llvm/docs/api/structs/llvm/coverage/mcdcrecord/#abfea249cd51ba9478b1e85bbc3508418a3b7b1235ae7885e1f859b0abc9c11988">llvm::coverage::MCDCRecord::MCDC_True</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Values {#ab764bc2c9252128b931774cc05652f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::coverage::MCDCRecord::TestVector::Values</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### Visited {#ad3562d1bae529839d22b3dfce85e67fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::coverage::MCDCRecord::TestVector::Visited</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True/False (False when DontCare)</p>

<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
