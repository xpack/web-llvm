---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/simplifyquery
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SimplifyQuery` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::SimplifyQuery { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/simplifyquery-h">llvm/Analysis/SimplifyQuery.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a343add975d940af757f1254276d93640">SimplifyQuery</a> (const DataLayout &amp;DL, const Instruction *CXTI=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6679427daa9fef9c45ae2ab6cd21b8c5">SimplifyQuery</a> (const DataLayout &amp;DL, const TargetLibraryInfo *TLI, const DominatorTree *DT=nullptr, AssumptionCache *AC=nullptr, const Instruction *CXTI=nullptr, bool UseInstrInfo=true, bool CanUseUndef=true, const DomConditionCache *DC=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eaf1831f1ac1f0490dd9996368d8591">SimplifyQuery</a> (const DataLayout &amp;DL, const DominatorTree *DT, AssumptionCache *AC=nullptr, const Instruction *CXTI=nullptr, bool UseInstrInfo=true, bool CanUseUndef=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a505cdf903e17bf9be677769bf0980adc">getWithInstruction</a> (const Instruction *I) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba451d2306d849c2ca6821dfe84587a9">getWithoutUndef</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8349c0152a8ece08ab63f6180baa7c8e">isUndefValue</a> (Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If CanUseUndef is true, returns whether <span class="doxyComputerOutput">V</span> is undef. <a href="#a8349c0152a8ece08ab63f6180baa7c8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfa0aaf0f26a6dce6e634abd5538860f">getWithoutDomCondCache</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49a6795732d904078549519543ce64b3">getWithCondContext</a> (const CondContext &amp;CC) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27f98ee6992ccceb87d07b9bbf144e8b">getWithoutCondContext</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ffb6d79f6befe2030328bd1d7110feb">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf09fd551f7b18f7c75c662a8a8ed040">TLI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4776fa0f5a726bd5a8a444981c283c69">DT</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a928ce56952772d0e0f43cab3a489a6fe">AC</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30647c42c8c40890c577ba5b4ab16468">CxtI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/domconditioncache">DomConditionCache</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e98bd8d2fcb558510c18f43f1611bc8">DC</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/condcontext">CondContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd186c7b45157be86bb148cd8347822a">CC</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instrinfoquery">InstrInfoQuery</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad029c8abde2f42c8d5837bd5515bb18e">IIQ</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b12da4ca5cd8514b068a30f8716db31">CanUseUndef</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Controls whether simplifications are allowed to constrain the range of possible values for uses of undef. <a href="#a3b12da4ca5cd8514b068a30f8716db31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/simplifyquery-h">SimplifyQuery.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SimplifyQuery() {#a343add975d940af757f1254276d93640}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SimplifyQuery::SimplifyQuery (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CXTI=nullptr)</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/simplifyquery-h">SimplifyQuery.h</a>.</p>


<p>References <a href="#a30647c42c8c40890c577ba5b4ab16468">CxtI</a> and <a href="#a0ffb6d79f6befe2030328bd1d7110feb">DL</a>.</p>


<p>Referenced by <a href="#a49a6795732d904078549519543ce64b3">getWithCondContext</a>, <a href="#a505cdf903e17bf9be677769bf0980adc">getWithInstruction</a>, <a href="#a27f98ee6992ccceb87d07b9bbf144e8b">getWithoutCondContext</a>, <a href="#adfa0aaf0f26a6dce6e634abd5538860f">getWithoutDomCondCache</a> and <a href="#aba451d2306d849c2ca6821dfe84587a9">getWithoutUndef</a>.</p>

</div>
</div>

### SimplifyQuery() {#a6679427daa9fef9c45ae2ab6cd21b8c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SimplifyQuery::SimplifyQuery (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT=nullptr, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CXTI=nullptr, bool UseInstrInfo=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool CanUseUndef=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/domconditioncache">DomConditionCache</a> * DC=nullptr)</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/simplifyquery-h">SimplifyQuery.h</a>.</p>


<p>References <a href="#a928ce56952772d0e0f43cab3a489a6fe">AC</a>, <a href="#a3b12da4ca5cd8514b068a30f8716db31">CanUseUndef</a>, <a href="#a30647c42c8c40890c577ba5b4ab16468">CxtI</a>, <a href="#a9e98bd8d2fcb558510c18f43f1611bc8">DC</a>, <a href="#a0ffb6d79f6befe2030328bd1d7110feb">DL</a>, <a href="#a4776fa0f5a726bd5a8a444981c283c69">DT</a>, <a href="#ad029c8abde2f42c8d5837bd5515bb18e">IIQ</a> and <a href="#aaf09fd551f7b18f7c75c662a8a8ed040">TLI</a>.</p>

</div>
</div>

### SimplifyQuery() {#a9eaf1831f1ac1f0490dd9996368d8591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SimplifyQuery::SimplifyQuery (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CXTI=nullptr, bool UseInstrInfo=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool CanUseUndef=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/simplifyquery-h">SimplifyQuery.h</a>.</p>


<p>References <a href="#a928ce56952772d0e0f43cab3a489a6fe">AC</a>, <a href="#a3b12da4ca5cd8514b068a30f8716db31">CanUseUndef</a>, <a href="#a30647c42c8c40890c577ba5b4ab16468">CxtI</a>, <a href="#a0ffb6d79f6befe2030328bd1d7110feb">DL</a>, <a href="#a4776fa0f5a726bd5a8a444981c283c69">DT</a> and <a href="#ad029c8abde2f42c8d5837bd5515bb18e">IIQ</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getWithCondContext() {#a49a6795732d904078549519543ce64b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SimplifyQuery llvm::SimplifyQuery::getWithCondContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/condcontext">CondContext</a> &amp; CC)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/simplifyquery-h">SimplifyQuery.h</a>.</p>


<p>References <a href="#afd186c7b45157be86bb148cd8347822a">CC</a> and <a href="#a343add975d940af757f1254276d93640">SimplifyQuery</a>.</p>

</div>
</div>

### getWithInstruction() {#a505cdf903e17bf9be677769bf0980adc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SimplifyQuery llvm::SimplifyQuery::getWithInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/simplifyquery-h">SimplifyQuery.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a343add975d940af757f1254276d93640">SimplifyQuery</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae5be25044bcd47e6c80f68c90159891f">llvm::GCNTTIImpl::canSimplifyLegacyMulToMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#abd2a207499b6fef021080fbe87fa61d6">foldCtpop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#ac6169fee4cf2c33a0c3abb46628bfefc">foldCttzCtlz</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a48239fe2dd570dc10b58a6a89ce6dd72">foldFCmpFSubIntoFCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a568e85197421e091a259bf80e19c6765">foldFPtoI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a25119a0e5bcc1f71c61c4acc02e3ff2b">foldICmpAndXX</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a917f93b85c9b8cfe9ad68ba6d49966ba">foldSelectBinOpIdentity</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#afdc0c60200d744fe53a7f48e3f7e4bb0">foldSelectWithFCmpToFabs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aaf025e558f9fe2914e3f8c52e046fb21">foldShiftIntoShiftInAnotherHandOfAndInICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a2a50775521fbb289313bb39964dabae3">simplifyAndOrWithOpReplaced</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a3ef524444504c738f1da4b4fb0b5a238">simplifyInstructionWithOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a45bde60377059fca310bb78e5d3a3ccb">simplifyInstructionWithPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinstsimplify-cpp/#ac7156f23f48b5eb96ead0522896d7574">simplifyLoopInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a914ac5681f80badb866f2aee44fc509a">threadBinOpOverPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a1ec7a76fbddf5983969def6e47c0f177">threadCmpOverPHI</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#ab952034edc23ad21ab312e0baaea0d7e">tryFactorization</a>.</p>

</div>
</div>

### getWithoutCondContext() {#a27f98ee6992ccceb87d07b9bbf144e8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SimplifyQuery llvm::SimplifyQuery::getWithoutCondContext ()</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/simplifyquery-h">SimplifyQuery.h</a>.</p>


<p>Reference <a href="#a343add975d940af757f1254276d93640">SimplifyQuery</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#add650fe201d4951c7146442a8969cc59">ComputeNumSignBitsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94e5917e7d2f3648965d7c69deb17ae6">llvm::isKnownToBeAPowerOfTwo</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a2422018885327baa9a1a4c493e17811c">isNonEqualPHIs</a>.</p>

</div>
</div>

### getWithoutDomCondCache() {#adfa0aaf0f26a6dce6e634abd5538860f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SimplifyQuery llvm::SimplifyQuery::getWithoutDomCondCache ()</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/simplifyquery-h">SimplifyQuery.h</a>.</p>


<p>Reference <a href="#a343add975d940af757f1254276d93640">SimplifyQuery</a>.</p>

</div>
</div>

### getWithoutUndef() {#aba451d2306d849c2ca6821dfe84587a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SimplifyQuery llvm::SimplifyQuery::getWithoutUndef ()</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/simplifyquery-h">SimplifyQuery.h</a>.</p>


<p>Reference <a href="#a343add975d940af757f1254276d93640">SimplifyQuery</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a6d9999d61310781a41074a967e885f12">expandBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae739737036faaf1bcaa66a0f4a8e1e63">simplifyAndOrWithICmpEq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab720ac4c86a5f16a755b1e5cd0d32c80">llvm::simplifyBinaryIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7bee73e1eef011ba0a15bcb696cb0971">simplifySelectWithEquivalence</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac2c120392853d2011de12503a12a16be">llvm::simplifyWithOpReplaced</a>.</p>

</div>
</div>

### isUndefValue() {#a8349c0152a8ece08ab63f6180baa7c8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SimplifyQuery::isUndefValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If CanUseUndef is true, returns whether <span class="doxyComputerOutput">V</span> is undef.</p>


<p>Otherwise always return false.</p>


<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/simplifyquery-h">SimplifyQuery.h</a>, definition at line 7352 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a>.</p>


<p>References <a href="#a3b12da4ca5cd8514b068a30f8716db31">CanUseUndef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#adea6dc2e42baa345b97be48b0370313d">llvm::PatternMatch::m_Undef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a587eab2c520053bb06fdc4afe5a57aa3">isPoisonShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a3a8f0d83fd0c16251206c0d0f3e78174">simplifyAddInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab720ac4c86a5f16a755b1e5cd0d32c80">llvm::simplifyBinaryIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a789b1341fc862e30623b200657911a4c">simplifyDivRem</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a48ebda753879b3d5d55fa0e1566b5439">simplifyExtractElementInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aa6498365e4fa2bc006fc4116b4b9b990">simplifyFPOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aab8aaa8e44e0609f7d3e9ae822f11f7e">simplifyGEPInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abdf4b5f9e1dc6887cac393ee643c10b6">llvm::simplifyInsertElementInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ac2e1b2bf5707da420c5d0578a227e34c">simplifyInsertValueInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a554988e4897106ec290097646fd1a84e">simplifyIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ab6fe80e6f4b357ca0fdc9eafa69c430f">simplifyLdexp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7f2df18bfd941b2e8d1cd78db5beb6f7">simplifyMulInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a845e93029e92776841aaf5e0ec4c812f">simplifyOrInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a308de6b87d4d431477642d086b268a7c">simplifyPHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a5bb5f4b5b2420a7f3950939b2de01330">simplifyRightShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a38dc339806a701c1f11ec31cf76936ff">simplifySelectInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a8e2f5715194e637f638fcd6e0851448b">simplifyShlInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a0bf04415ab72b83b24140635c6a7ea52">simplifyShuffleVectorInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a0e278bb318fd700a9c8d4f4a7c8caba9">simplifySubInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a9cfeea050198084d67109f0260e33970">simplifyXorInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ada3f0c65b41a26f74d332e974164ce55">threadBinOpOverSelect</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AC {#a928ce56952772d0e0f43cab3a489a6fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache* llvm::SimplifyQuery::AC = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/simplifyquery-h">SimplifyQuery.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6d830b26db3b7e76253b7d2afb906400">llvm::adjustKnownBitsForSelectArm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d8cb47f2535cdf5f9608baabfa78f4e">llvm::computeKnownBitsFromContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aac253731b80df3086dc617dc805f7dd5">computeKnownBitsMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a93cb45813945a1bb817bee6664d452be">computeKnownFPClassFromContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b72ea7b10ac690e8f1bcdf144c7e5d4">llvm::computeOverflowForSignedSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfdf10a69ac9839f2ae92515b969b77e">llvm::computeOverflowForUnsignedSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#ae1497784bc56d64f953026632a186005">foldAndOrOfICmpsWithPow2AndWithZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#ac1582713ab3ea01b71ad1cd559fbf4af">foldCtpopPow2Test</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a2dd853a202d939d273a51870f3fe2273">haveNoCommonBitsSetSpecialCases</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ad96e48bda36fb8540a3973cee993c5b3">isKnownNonZeroFromAssume</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94e5917e7d2f3648965d7c69deb17ae6">llvm::isKnownToBeAPowerOfTwo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a27b2d2bdaebf47dabb75e94f6c0f739f">isMaskOrZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a056e5a535ce9d93f9c20adcce79b519f">setShiftFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a3eefa98bc7f6c24b6f1fa0bb220a77a4">simplifyAndCommutative</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a29b4afe26752d50b7207bf4cd3f984f3">simplifyAShrInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a0160b3b9cc2d97a29656003dc77f189e">simplifyFreezeInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae9417447cf23234d645221bda42e00c4">simplifyICmpWithDominatingAssume</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a308de6b87d4d431477642d086b268a7c">simplifyPHINode</a>, <a href="#a9eaf1831f1ac1f0490dd9996368d8591">SimplifyQuery</a>, <a href="#a6679427daa9fef9c45ae2ab6cd21b8c5">SimplifyQuery</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#afd74672cec2bec4f18c103c4cb7823d4">simplifyUnaryIntrinsic</a>.</p>

</div>
</div>

### CanUseUndef {#a3b12da4ca5cd8514b068a30f8716db31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SimplifyQuery::CanUseUndef = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Controls whether simplifications are allowed to constrain the range of possible values for uses of undef.</p>


<p>If it is false, simplifications are not allowed to assume a particular value for a use of undef for example.</p>


<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/simplifyquery-h">SimplifyQuery.h</a>.</p>


<p>Referenced by <a href="#a8349c0152a8ece08ab63f6180baa7c8e">isUndefValue</a>, <a href="#a9eaf1831f1ac1f0490dd9996368d8591">SimplifyQuery</a>, <a href="#a6679427daa9fef9c45ae2ab6cd21b8c5">SimplifyQuery</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a4611905728c0ddaed9f8964ae8b074a2">simplifyWithOpsReplaced</a>.</p>

</div>
</div>

### CC {#afd186c7b45157be86bb148cd8347822a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CondContext* llvm::SimplifyQuery::CC = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/simplifyquery-h">SimplifyQuery.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4d8cb47f2535cdf5f9608baabfa78f4e">llvm::computeKnownBitsFromContext</a> and <a href="#a49a6795732d904078549519543ce64b3">getWithCondContext</a>.</p>

</div>
</div>

### CxtI {#a30647c42c8c40890c577ba5b4ab16468}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Instruction* llvm::SimplifyQuery::CxtI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/simplifyquery-h">SimplifyQuery.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6d830b26db3b7e76253b7d2afb906400">llvm::adjustKnownBitsForSelectArm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d8cb47f2535cdf5f9608baabfa78f4e">llvm::computeKnownBitsFromContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aac253731b80df3086dc617dc805f7dd5">computeKnownBitsMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a93cb45813945a1bb817bee6664d452be">computeKnownFPClassFromContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#add650fe201d4951c7146442a8969cc59">ComputeNumSignBitsImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b72ea7b10ac690e8f1bcdf144c7e5d4">llvm::computeOverflowForSignedSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfdf10a69ac9839f2ae92515b969b77e">llvm::computeOverflowForUnsignedSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#ae1497784bc56d64f953026632a186005">foldAndOrOfICmpsWithPow2AndWithZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#ac1582713ab3ea01b71ad1cd559fbf4af">foldCtpopPow2Test</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a15df887e1ad05e6c22a7c2e6492bde2d">foldOrCommuteConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a660c0e2a422273548d57b9573ee332f2">getKnownSign</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#aa3c7b3d44543dfa4c8f4a99456303be4">getKnownSignOrZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a2dd853a202d939d273a51870f3fe2273">haveNoCommonBitsSetSpecialCases</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a37947028558485b4526101a36f80dcc8">isKnownNonZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ad96e48bda36fb8540a3973cee993c5b3">isKnownNonZeroFromAssume</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94e5917e7d2f3648965d7c69deb17ae6">llvm::isKnownToBeAPowerOfTwo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a27b2d2bdaebf47dabb75e94f6c0f739f">isMaskOrZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a2422018885327baa9a1a4c493e17811c">isNonEqualPHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a50882a093546a573f3e879fc578f167d">isPowerOfTwoRecurrence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a056e5a535ce9d93f9c20adcce79b519f">setShiftFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a3eefa98bc7f6c24b6f1fa0bb220a77a4">simplifyAndCommutative</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a29b4afe26752d50b7207bf4cd3f984f3">simplifyAShrInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a6343e645572ce8783bbf5853d181479f">simplifyByDomEq</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a0160b3b9cc2d97a29656003dc77f189e">simplifyFreezeInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae9417447cf23234d645221bda42e00c4">simplifyICmpWithDominatingAssume</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a3ef524444504c738f1da4b4fb0b5a238">simplifyInstructionWithOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a308de6b87d4d431477642d086b268a7c">simplifyPHINode</a>, <a href="#a9eaf1831f1ac1f0490dd9996368d8591">SimplifyQuery</a>, <a href="#a343add975d940af757f1254276d93640">SimplifyQuery</a>, <a href="#a6679427daa9fef9c45ae2ab6cd21b8c5">SimplifyQuery</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a38dc339806a701c1f11ec31cf76936ff">simplifySelectInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a75fa36408fed5acf91329505b3419196">simplifySelectWithFCmp</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#afd74672cec2bec4f18c103c4cb7823d4">simplifyUnaryIntrinsic</a>.</p>

</div>
</div>

### DC {#a9e98bd8d2fcb558510c18f43f1611bc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DomConditionCache* llvm::SimplifyQuery::DC = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/simplifyquery-h">SimplifyQuery.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4d8cb47f2535cdf5f9608baabfa78f4e">llvm::computeKnownBitsFromContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a93cb45813945a1bb817bee6664d452be">computeKnownFPClassFromContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94e5917e7d2f3648965d7c69deb17ae6">llvm::isKnownToBeAPowerOfTwo</a> and <a href="#a6679427daa9fef9c45ae2ab6cd21b8c5">SimplifyQuery</a>.</p>

</div>
</div>

### DL {#a0ffb6d79f6befe2030328bd1d7110feb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; llvm::SimplifyQuery::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/simplifyquery-h">SimplifyQuery.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a903bd19e9d31beff55b22fe86111639e">computeKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f8863e632875491a72d02ccd27f0bd4">llvm::computeKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a42815741ca874c3ef51a58fb4dc67190">llvm::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aa730d6c2ddb52a05e3602c501e961629">computeKnownBitsForHorizontalOperation</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a76c547b25150612c3617877e2427e9fa">computeKnownBitsFromCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#add650fe201d4951c7146442a8969cc59">ComputeNumSignBitsImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfdf10a69ac9839f2ae92515b969b77e">llvm::computeOverflowForUnsignedSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aec29f5580509ec9a7592200e09b7aa27">computePointerICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a33e48dd73f38cb005f9a57fa3965879e">dropRedundantMaskingOfLeftShiftInput</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#ae1497784bc56d64f953026632a186005">foldAndOrOfICmpsWithPow2AndWithZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a1a6e468202ea1fafcd8163afbe034823">foldConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#ac1582713ab3ea01b71ad1cd559fbf4af">foldCtpopPow2Test</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a15df887e1ad05e6c22a7c2e6492bde2d">foldOrCommuteConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aaf025e558f9fe2914e3f8c52e046fb21">foldShiftIntoShiftInAnotherHandOfAndInICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a660c0e2a422273548d57b9573ee332f2">getKnownSign</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#aa3c7b3d44543dfa4c8f4a99456303be4">getKnownSignOrZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ab9ee1d3249435d1130a87d064d13857d">isGEPKnownNonNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a373d20116312d859aa88b46b48a8fd8c">isKnownNonEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a27b2d2bdaebf47dabb75e94f6c0f739f">isMaskOrZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a8133ee4dcc7f8903e9b582593c09bf28">isNonEqualPointersWithRecursiveGEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a056e5a535ce9d93f9c20adcce79b519f">setShiftFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a3eefa98bc7f6c24b6f1fa0bb220a77a4">simplifyAndCommutative</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ad4122a9286a8dd18458df1f47230e07f">simplifyAndOrOfCmps</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a29b4afe26752d50b7207bf4cd3f984f3">simplifyAShrInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab720ac4c86a5f16a755b1e5cd0d32c80">llvm::simplifyBinaryIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a6343e645572ce8783bbf5853d181479f">simplifyByDomEq</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#abfcd971ce6ccafa5489dd3bf313219af">simplifyCastInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aab8aaa8e44e0609f7d3e9ae822f11f7e">simplifyGEPInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a22aa6a5c92a8a6cbb5437123d7e069e6">simplifyICmpOfBools</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae9417447cf23234d645221bda42e00c4">simplifyICmpWithDominatingAssume</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a3ef524444504c738f1da4b4fb0b5a238">simplifyInstructionWithOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99fa28f2d78ae2ce889b621ab275a4ad">llvm::simplifyLoadInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a845e93029e92776841aaf5e0ec4c812f">simplifyOrInst</a>, <a href="#a9eaf1831f1ac1f0490dd9996368d8591">SimplifyQuery</a>, <a href="#a343add975d940af757f1254276d93640">SimplifyQuery</a>, <a href="#a6679427daa9fef9c45ae2ab6cd21b8c5">SimplifyQuery</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a38dc339806a701c1f11ec31cf76936ff">simplifySelectInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#afa1ff3254ee225171cb55d46b0eab145">simplifySelectWithICmpCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a0e278bb318fd700a9c8d4f4a7c8caba9">simplifySubInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#afd74672cec2bec4f18c103c4cb7823d4">simplifyUnaryIntrinsic</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a4611905728c0ddaed9f8964ae8b074a2">simplifyWithOpsReplaced</a>.</p>

</div>
</div>

### DT {#a4776fa0f5a726bd5a8a444981c283c69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DominatorTree* llvm::SimplifyQuery::DT = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/simplifyquery-h">SimplifyQuery.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6d830b26db3b7e76253b7d2afb906400">llvm::adjustKnownBitsForSelectArm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d8cb47f2535cdf5f9608baabfa78f4e">llvm::computeKnownBitsFromContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aac253731b80df3086dc617dc805f7dd5">computeKnownBitsMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a93cb45813945a1bb817bee6664d452be">computeKnownFPClassFromContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b72ea7b10ac690e8f1bcdf144c7e5d4">llvm::computeOverflowForSignedSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfdf10a69ac9839f2ae92515b969b77e">llvm::computeOverflowForUnsignedSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#ae1497784bc56d64f953026632a186005">foldAndOrOfICmpsWithPow2AndWithZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#ac1582713ab3ea01b71ad1cd559fbf4af">foldCtpopPow2Test</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a2dd853a202d939d273a51870f3fe2273">haveNoCommonBitsSetSpecialCases</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a37947028558485b4526101a36f80dcc8">isKnownNonZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ad96e48bda36fb8540a3973cee993c5b3">isKnownNonZeroFromAssume</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94e5917e7d2f3648965d7c69deb17ae6">llvm::isKnownToBeAPowerOfTwo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a27b2d2bdaebf47dabb75e94f6c0f739f">isMaskOrZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/instsimplifypass-cpp/#a49359723de1a046072e8cc931068d43f">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a056e5a535ce9d93f9c20adcce79b519f">setShiftFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a3eefa98bc7f6c24b6f1fa0bb220a77a4">simplifyAndCommutative</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a29b4afe26752d50b7207bf4cd3f984f3">simplifyAShrInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a0160b3b9cc2d97a29656003dc77f189e">simplifyFreezeInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae9417447cf23234d645221bda42e00c4">simplifyICmpWithDominatingAssume</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a308de6b87d4d431477642d086b268a7c">simplifyPHINode</a>, <a href="#a9eaf1831f1ac1f0490dd9996368d8591">SimplifyQuery</a>, <a href="#a6679427daa9fef9c45ae2ab6cd21b8c5">SimplifyQuery</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#afd74672cec2bec4f18c103c4cb7823d4">simplifyUnaryIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a914ac5681f80badb866f2aee44fc509a">threadBinOpOverPHI</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a1ec7a76fbddf5983969def6e47c0f177">threadCmpOverPHI</a>.</p>

</div>
</div>

### IIQ {#ad029c8abde2f42c8d5837bd5515bb18e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstrInfoQuery llvm::SimplifyQuery::IIQ</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/simplifyquery-h">SimplifyQuery.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab0eb8e591794bfc8e474a0a68c1135b0">llvm::computeConstantRangeIncludingKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94e5917e7d2f3648965d7c69deb17ae6">llvm::isKnownToBeAPowerOfTwo</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a50882a093546a573f3e879fc578f167d">isPowerOfTwoRecurrence</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ac1907d1fccfb9846bfd91b6b79c0acbc">simplifyAndOfICmps</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a29b4afe26752d50b7207bf4cd3f984f3">simplifyAShrInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a789b1341fc862e30623b200657911a4c">simplifyDivRem</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a64cb0c5ab10b63f22110e1b0183a648f">simplifyICmpWithBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a3ef524444504c738f1da4b4fb0b5a238">simplifyInstructionWithOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a0614870543ce4ba5b6f9c7030d6867e2">simplifyLShrInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7f2df18bfd941b2e8d1cd78db5beb6f7">simplifyMulInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a6b86bbc17cbb2be2b63a54fcdbcf4251">simplifyOrOfICmps</a>, <a href="#a9eaf1831f1ac1f0490dd9996368d8591">SimplifyQuery</a>, <a href="#a6679427daa9fef9c45ae2ab6cd21b8c5">SimplifyQuery</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aed163588354401b6679a39acad6fae2a">simplifyRem</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a8e2f5715194e637f638fcd6e0851448b">simplifyShlInst</a>.</p>

</div>
</div>

### TLI {#aaf09fd551f7b18f7c75c662a8a8ed040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLibraryInfo* llvm::SimplifyQuery::TLI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/simplifyquery-h">SimplifyQuery.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aec29f5580509ec9a7592200e09b7aa27">computePointerICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/instsimplifypass-cpp/#a49359723de1a046072e8cc931068d43f">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a3ef524444504c738f1da4b4fb0b5a238">simplifyInstructionWithOperands</a>, <a href="#a6679427daa9fef9c45ae2ab6cd21b8c5">SimplifyQuery</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a4611905728c0ddaed9f8964ae8b074a2">simplifyWithOpsReplaced</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a4394b9bd9afc3ae5f5477e8c265d8b0e">tryConstantFoldCall</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/simplifyquery-h">SimplifyQuery.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp">InstructionSimplify.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
