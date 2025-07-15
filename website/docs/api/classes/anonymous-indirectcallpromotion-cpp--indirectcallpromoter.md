---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-indirectcallpromotion-cpp-/indirectcallpromoter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `IndirectCallPromoter` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{IndirectCallPromotion.cpp}::IndirectCallPromoter { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2cd233c921d980fa41c5dad7519b671">IndirectCallPromoter</a> (Function &amp;Func, Module &amp;M, InstrProfSymtab *Symtab, bool SamplePGO, const VirtualCallSiteTypeInfoMap &amp;VirtualCSInfo, VTableAddressPointOffsetValMap &amp;VTableAddressPointOffsetVal, const DenseSet&lt; StringRef &gt; &amp;IgnoredBaseTypes, OptimizationRemarkEmitter &amp;ORE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e40559cd22c89e1f75012bd82e6be2c">IndirectCallPromoter</a> (const IndirectCallPromoter &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-indirectcallpromotion-cpp-/indirectcallpromoter">IndirectCallPromoter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a584a68e6833e3e6a53a0de81630a5dbd">operator=</a> (const IndirectCallPromoter &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ee24b9cc3b8ee886c655caed7e6cb11">processFunction</a> (ProfileSummaryInfo *PSI)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; PromotionCandidate &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25a786fc9d7436174e9e166b71c067c8">getPromotionCandidatesForCallSite</a> (const CallBase &amp;CB, ArrayRef&lt; InstrProfValueData &gt; ValueDataRef, uint64_t TotalCount, uint32_t NumCandidates)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9db56cbb5ae6240d9bb965f6daaccdad">tryToPromoteWithFuncCmp</a> (CallBase &amp;CB, Instruction *VPtr, ArrayRef&lt; PromotionCandidate &gt; Candidates, uint64_t TotalCount, ArrayRef&lt; InstrProfValueData &gt; ICallProfDataRef, uint32_t NumCandidates, VTableGUIDCountsMap &amp;VTableGUIDCounts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9adc98b6079264e1b665210fd39a7e8b">tryToPromoteWithVTableCmp</a> (CallBase &amp;CB, Instruction *VPtr, ArrayRef&lt; PromotionCandidate &gt; Candidates, uint64_t TotalFuncCount, uint32_t NumCandidates, MutableArrayRef&lt; InstrProfValueData &gt; ICallProfDataRef, VTableGUIDCountsMap &amp;VTableGUIDCounts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30b83b7509ea85033fb7f70639f16664">isProfitableToCompareVTables</a> (const CallBase &amp;CB, ArrayRef&lt; PromotionCandidate &gt; Candidates)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac737e8a0c38eb6732914cb15c0434ec1">shouldSkipVTable</a> (uint64_t VTableGUID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a528f438b6f5919b12146b25f747b9d28">computeVTableInfos</a> (const CallBase *CB, VTableGUIDCountsMap &amp;VTableGUIDCounts, std::vector&lt; PromotionCandidate &gt; &amp;Candidates)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd75c12b2e9088244a015857f7b99ebd">getOrCreateVTableAddressPointVar</a> (GlobalVariable *GV, uint64_t AddressPointOffset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a204e0853ab6cd33bef0047d5f024bcd8">updateFuncValueProfiles</a> (CallBase &amp;CB, ArrayRef&lt; InstrProfValueData &gt; VDs, uint64_t Sum, uint32_t MaxMDCount)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cdb3ebcfcf9309648bb83ef56435364">updateVPtrValueProfiles</a> (Instruction *VPtr, VTableGUIDCountsMap &amp;VTableGUIDCounts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa13c536150fa4441baeb0b3e0785f0fb">F</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab99ca49a406375ab34dd59fa94631067">M</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa64dc2ea0b41752bfad85a754b4b5f56">Symtab</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc17ceae07e62369ebe4fcc653b1fd73">SamplePGO</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-indirectcallpromotion-cpp-/#a5dd111ff15cb848e2129e2a5edfb7100">VirtualCallSiteTypeInfoMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4313a94c7fa10af6d573eebcfa2af2a6">VirtualCSInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-indirectcallpromotion-cpp-/#a064d7f039f5901e892efdb296d304ede">VTableAddressPointOffsetValMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5acf61b4d7482be6f0ebf41c84a5993">VTableAddressPointOffsetVal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62a8540ce90fc087c1753326752b849e">ORE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfd8369eef024817182b22b6d22261db">IgnoredBaseTypes</a></td>
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


<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### IndirectCallPromoter() {#ac2cd233c921d980fa41c5dad7519b671}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{IndirectCallPromotion.cpp}::IndirectCallPromoter::IndirectCallPromoter (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Func, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> * Symtab, bool SamplePGO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-indirectcallpromotion-cpp-/#a5dd111ff15cb848e2129e2a5edfb7100">VirtualCallSiteTypeInfoMap</a> &amp; VirtualCSInfo, <a href="/web-llvm/docs/api/namespaces/anonymous-indirectcallpromotion-cpp-/#a064d7f039f5901e892efdb296d304ede">VTableAddressPointOffsetValMap</a> &amp; VTableAddressPointOffsetVal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; IgnoredBaseTypes, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE)</td>
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



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>


<p>Referenced by <a href="#a1e40559cd22c89e1f75012bd82e6be2c">IndirectCallPromoter</a>, <a href="#a584a68e6833e3e6a53a0de81630a5dbd">operator=</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp/#a42ff11c63c1a675d13cc97eaec48d621">promoteIndirectCalls</a>.</p>

</div>
</div>

### IndirectCallPromoter() {#a1e40559cd22c89e1f75012bd82e6be2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{IndirectCallPromotion.cpp}::IndirectCallPromoter::IndirectCallPromoter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-indirectcallpromotion-cpp-/indirectcallpromoter">IndirectCallPromoter</a> &amp;)</td>
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



<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>


<p>Reference <a href="#ac2cd233c921d980fa41c5dad7519b671">IndirectCallPromoter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a584a68e6833e3e6a53a0de81630a5dbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndirectCallPromoter &amp; anonymous{IndirectCallPromotion.cpp}::IndirectCallPromoter::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-indirectcallpromotion-cpp-/indirectcallpromoter">IndirectCallPromoter</a> &amp;)</td>
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



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>


<p>References <a href="#ac2cd233c921d980fa41c5dad7519b671">IndirectCallPromoter</a> and <a href="#a1ee24b9cc3b8ee886c655caed7e6cb11">processFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### processFunction() {#a1ee24b9cc3b8ee886c655caed7e6cb11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IndirectCallPromoter::processFunction (<a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a176c662ef638785a96bf45d8c269b471">llvm::findIndirectCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/icallpromotionanalysis/#ad7143519efbd492ef7ced88c6198e1ca">llvm::ICallPromotionAnalysis::getPromotionCandidatesForInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#a11d1c1af51bf81a6a9f8f5191b5e3cf2">llvm::ProfileSummaryInfo::hasProfileSummary</a> and <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#ac46d4d55dd867977ba88d57a170e31de">llvm::ProfileSummaryInfo::isHotCount</a>.</p>


<p>Referenced by <a href="#a584a68e6833e3e6a53a0de81630a5dbd">operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### computeVTableInfos() {#a528f438b6f5919b12146b25f747b9d28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * IndirectCallPromoter::computeVTableInfos (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB, <a href="/web-llvm/docs/api/namespaces/anonymous-indirectcallpromotion-cpp-/#a686d9143a6a437108d460d05ce976621">VTableGUIDCountsMap</a> &amp; VTableGUIDCounts, std::vector&lt; PromotionCandidate &gt; &amp; Candidates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>

</div>
</div>

### getOrCreateVTableAddressPointVar() {#afd75c12b2e9088244a015857f7b99ebd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * IndirectCallPromoter::getOrCreateVTableAddressPointVar (<a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV, uint64_t AddressPointOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>

</div>
</div>

### getPromotionCandidatesForCallSite() {#a25a786fc9d7436174e9e166b71c067c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; IndirectCallPromoter::PromotionCandidate &gt; IndirectCallPromoter::getPromotionCandidatesForCallSite (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; InstrProfValueData &gt; ValueDataRef, uint64_t TotalCount, uint32_t NumCandidates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>

</div>
</div>

### isProfitableToCompareVTables() {#a30b83b7509ea85033fb7f70639f16664}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IndirectCallPromoter::isProfitableToCompareVTables (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; PromotionCandidate &gt; Candidates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>

</div>
</div>

### shouldSkipVTable() {#ac737e8a0c38eb6732914cb15c0434ec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IndirectCallPromoter::shouldSkipVTable (uint64_t VTableGUID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>

</div>
</div>

### tryToPromoteWithFuncCmp() {#a9db56cbb5ae6240d9bb965f6daaccdad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IndirectCallPromoter::tryToPromoteWithFuncCmp (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * VPtr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; PromotionCandidate &gt; Candidates, uint64_t TotalCount, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; InstrProfValueData &gt; ICallProfDataRef, uint32_t NumCandidates, <a href="/web-llvm/docs/api/namespaces/anonymous-indirectcallpromotion-cpp-/#a686d9143a6a437108d460d05ce976621">VTableGUIDCountsMap</a> &amp; VTableGUIDCounts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>

</div>
</div>

### tryToPromoteWithVTableCmp() {#a9adc98b6079264e1b665210fd39a7e8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IndirectCallPromoter::tryToPromoteWithVTableCmp (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * VPtr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; PromotionCandidate &gt; Candidates, uint64_t TotalFuncCount, uint32_t NumCandidates, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; InstrProfValueData &gt; ICallProfDataRef, <a href="/web-llvm/docs/api/namespaces/anonymous-indirectcallpromotion-cpp-/#a686d9143a6a437108d460d05ce976621">VTableGUIDCountsMap</a> &amp; VTableGUIDCounts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>

</div>
</div>

### updateFuncValueProfiles() {#a204e0853ab6cd33bef0047d5f024bcd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IndirectCallPromoter::updateFuncValueProfiles (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; InstrProfValueData &gt; VDs, uint64_t Sum, uint32_t MaxMDCount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>

</div>
</div>

### updateVPtrValueProfiles() {#a9cdb3ebcfcf9309648bb83ef56435364}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IndirectCallPromoter::updateVPtrValueProfiles (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * VPtr, <a href="/web-llvm/docs/api/namespaces/anonymous-indirectcallpromotion-cpp-/#a686d9143a6a437108d460d05ce976621">VTableGUIDCountsMap</a> &amp; VTableGUIDCounts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### F {#aa13c536150fa4441baeb0b3e0785f0fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{IndirectCallPromotion.cpp}::IndirectCallPromoter::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>

</div>
</div>

### IgnoredBaseTypes {#abfd8369eef024817182b22b6d22261db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DenseSet&lt;StringRef&gt;&amp; anonymous{IndirectCallPromotion.cpp}::IndirectCallPromoter::IgnoredBaseTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>

</div>
</div>

### M {#ab99ca49a406375ab34dd59fa94631067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module&amp; anonymous{IndirectCallPromotion.cpp}::IndirectCallPromoter::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>

</div>
</div>

### ORE {#a62a8540ce90fc087c1753326752b849e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter&amp; anonymous{IndirectCallPromotion.cpp}::IndirectCallPromoter::ORE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>

</div>
</div>

### SamplePGO {#abc17ceae07e62369ebe4fcc653b1fd73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool anonymous{IndirectCallPromotion.cpp}::IndirectCallPromoter::SamplePGO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>

</div>
</div>

### Symtab {#aa64dc2ea0b41752bfad85a754b4b5f56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfSymtab* const anonymous{IndirectCallPromotion.cpp}::IndirectCallPromoter::Symtab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>

</div>
</div>

### VirtualCSInfo {#a4313a94c7fa10af6d573eebcfa2af2a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VirtualCallSiteTypeInfoMap&amp; anonymous{IndirectCallPromotion.cpp}::IndirectCallPromoter::VirtualCSInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>

</div>
</div>

### VTableAddressPointOffsetVal {#af5acf61b4d7482be6f0ebf41c84a5993}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VTableAddressPointOffsetValMap&amp; anonymous{IndirectCallPromotion.cpp}::IndirectCallPromoter::VTableAddressPointOffsetVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp">IndirectCallPromotion.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
