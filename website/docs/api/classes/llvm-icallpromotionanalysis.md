---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/icallpromotionanalysis
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ICallPromotionAnalysis` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::ICallPromotionAnalysis { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/indirectcallpromotionanalysis-h">llvm/Analysis/IndirectCallPromotionAnalysis.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a481935e295c3d91be945b1b859c3339e">ICallPromotionAnalysis</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4141e6c27058e9e3f4313674d40778e7">ICallPromotionAnalysis</a> (const ICallPromotionAnalysis &amp;other)=delete</td>
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

## Private Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/icallpromotionanalysis">ICallPromotionAnalysis</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e73aed8706e2c7f43736c7f2f33d60e">operator=</a> (const ICallPromotionAnalysis &amp;other)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; InstrProfValueData &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7143519efbd492ef7ced88c6198e1ca">getPromotionCandidatesForInstruction</a> (const Instruction *I, uint64_t &amp;TotalCount, uint32_t &amp;NumCandidates)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns reference to array of InstrProfValueData for the given instruction <span class="doxyComputerOutput">I</span>. <a href="#ad7143519efbd492ef7ced88c6198e1ca">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf754db1a01bdfced421a138da3c7ab0">isPromotionProfitable</a> (uint64_t Count, uint64_t TotalCount, uint64_t RemainingCount)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5fea04bde4c54ea47bab5c64cb425f4">getProfitablePromotionCandidates</a> (const Instruction *Inst, uint64_t TotalCount)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; InstrProfValueData, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad266d4fdbaba8897563b5550a585cf7a">ValueDataArray</a></td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/indirectcallpromotionanalysis-h">IndirectCallPromotionAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ICallPromotionAnalysis() {#a481935e295c3d91be945b1b859c3339e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ICallPromotionAnalysis::ICallPromotionAnalysis ()</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/indirectcallpromotionanalysis-h">IndirectCallPromotionAnalysis.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ICallPromotionAnalysis() {#a4141e6c27058e9e3f4313674d40778e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ICallPromotionAnalysis::ICallPromotionAnalysis (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/icallpromotionanalysis">ICallPromotionAnalysis</a> &amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/indirectcallpromotionanalysis-h">IndirectCallPromotionAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Operators

### operator=() {#a1e73aed8706e2c7f43736c7f2f33d60e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ICallPromotionAnalysis &amp; llvm::ICallPromotionAnalysis::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/icallpromotionanalysis">ICallPromotionAnalysis</a> &amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/indirectcallpromotionanalysis-h">IndirectCallPromotionAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getPromotionCandidatesForInstruction() {#ad7143519efbd492ef7ced88c6198e1ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MutableArrayRef&lt; InstrProfValueData &gt; ICallPromotionAnalysis::getPromotionCandidatesForInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, uint64_t &amp; TotalCount, uint32_t &amp; NumCandidates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns reference to array of InstrProfValueData for the given instruction <span class="doxyComputerOutput">I</span>.</p>


<p>The <span class="doxyComputerOutput">TotalCount</span> and <span class="doxyComputerOutput">NumCandidates</span> are set to the the total profile count of the indirect call <span class="doxyComputerOutput">I</span> and the number of profitable candidates in the given array (which is sorted in reverse order of profitability).</p>


<p>The returned array space is owned by this class, and overwritten on subsequent calls.</p>


<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/indirectcallpromotionanalysis-h">IndirectCallPromotionAnalysis.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/indirectcallpromotionanalysis-cpp">IndirectCallPromotionAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8f6ad5c1831928ee2c6c5058d9580edf">llvm::getValueProfDataFromInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/indirectcallpromotionanalysis-cpp/#a8d1c61a222911b42ad7dc30bc6519d81">MaxNumPromotions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a99416758c13252bef45320a6ba6aa09c">llvm::MutableArrayRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a9b06152b51259f884261bba3099e4fc6">computeFunctionSummary</a> and <a href="/web-llvm/docs/api/classes/anonymous-indirectcallpromotion-cpp-/indirectcallpromoter/#a1ee24b9cc3b8ee886c655caed7e6cb11">anonymous{IndirectCallPromotion.cpp}::IndirectCallPromoter::processFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getProfitablePromotionCandidates() {#ac5fea04bde4c54ea47bab5c64cb425f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t ICallPromotionAnalysis::getProfitablePromotionCandidates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst, uint64_t TotalCount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/indirectcallpromotionanalysis-h">IndirectCallPromotionAnalysis.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/indirectcallpromotionanalysis-cpp">IndirectCallPromotionAnalysis.cpp</a>.</p>

</div>
</div>

### isPromotionProfitable() {#abf754db1a01bdfced421a138da3c7ab0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ICallPromotionAnalysis::isPromotionProfitable (uint64_t Count, uint64_t TotalCount, uint64_t RemainingCount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/indirectcallpromotionanalysis-h">IndirectCallPromotionAnalysis.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/indirectcallpromotionanalysis-cpp">IndirectCallPromotionAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ValueDataArray {#ad266d4fdbaba8897563b5550a585cf7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;InstrProfValueData, 4&gt; llvm::ICallPromotionAnalysis::ValueDataArray</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/indirectcallpromotionanalysis-h">IndirectCallPromotionAnalysis.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/indirectcallpromotionanalysis-h">IndirectCallPromotionAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/indirectcallpromotionanalysis-cpp">IndirectCallPromotionAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
