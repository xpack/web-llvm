---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpu/regbanklegalizerules/rulesetinitializer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RuleSetInitializer` Class



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPU::RegBankLegalizeRules::RuleSetInitializer { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class AliasMap, class RulesMap&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a3592750163d0fa49fb8d38f39f1efa1e">RuleSetInitializer</a> (std::initializer_list&lt; unsigned &gt; OpcList, AliasMap &amp;RulesAlias, RulesMap &amp;Rules, FastRulesTypes FastTypes=NoFastRules)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6029f3f025fc9ceac3883bfb267597f7">RuleSetInitializer</a> (const RuleSetInitializer &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8cf3ba83fe356989d30ab6c2001c0be">RuleSetInitializer</a> (RuleSetInitializer &amp;&amp;)=delete</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a746dff28a36c16c4356e2b0ff85da4b7">~RuleSetInitializer</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RuleSetInitializer &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85f6c83d2410d5dfe5c330c490dc172d">operator=</a> (const RuleSetInitializer &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RuleSetInitializer &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae605ac35a0c47b08dfbe15705cde8e10">operator=</a> (RuleSetInitializer &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RuleSetInitializer &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47f8485cf0b53a865258100b2ce190a8">Div</a> (UniformityLLTOpPredicateID Ty, RegBankLLTMapping RuleApplyIDs, bool STPred=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RuleSetInitializer &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a726fe89c6e1d347c2e5e439b01f05a4b">Uni</a> (UniformityLLTOpPredicateID Ty, RegBankLLTMapping RuleApplyIDs, bool STPred=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RuleSetInitializer &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae64ce70720dec1bfa4e2bc9fe08f2ebb">Any</a> (RegBankLegalizeRule Init, bool STPred=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpu/setofrulesforopcode">SetOfRulesForOpcode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a711cdb84f27703ce8e75d50510cff536">RuleSet</a></td>
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


<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RuleSetInitializer() {#a3592750163d0fa49fb8d38f39f1efa1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class AliasMap, class RulesMap&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPU::RegBankLegalizeRules::RuleSetInitializer::RuleSetInitializer (std::initializer_list&lt; unsigned &gt; OpcList, AliasMap &amp; RulesAlias, RulesMap &amp; Rules, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad91da66ed72fcfebb39312cb9dea2262">FastRulesTypes</a> FastTypes=<a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad91da66ed72fcfebb39312cb9dea2262a5f6d4bc34de12684ca978bf780f01db6">NoFastRules</a>)</td>
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



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>

</div>
</div>

### RuleSetInitializer() {#a6029f3f025fc9ceac3883bfb267597f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPU::RegBankLegalizeRules::RuleSetInitializer::RuleSetInitializer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RuleSetInitializer &amp;)</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>

</div>
</div>

### RuleSetInitializer() {#ac8cf3ba83fe356989d30ab6c2001c0be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPU::RegBankLegalizeRules::RuleSetInitializer::RuleSetInitializer (RuleSetInitializer &amp;&amp;)</td>
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



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RuleSetInitializer() {#a746dff28a36c16c4356e2b0ff85da4b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPU::RegBankLegalizeRules::RuleSetInitializer::~RuleSetInitializer ()</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a85f6c83d2410d5dfe5c330c490dc172d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuleSetInitializer &amp; llvm::AMDGPU::RegBankLegalizeRules::RuleSetInitializer::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RuleSetInitializer &amp;)</td>
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



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>

</div>
</div>

### operator=() {#ae605ac35a0c47b08dfbe15705cde8e10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuleSetInitializer &amp; llvm::AMDGPU::RegBankLegalizeRules::RuleSetInitializer::operator= (RuleSetInitializer &amp;&amp;)</td>
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



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Any() {#ae64ce70720dec1bfa4e2bc9fe08f2ebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuleSetInitializer &amp; llvm::AMDGPU::RegBankLegalizeRules::RuleSetInitializer::Any (<a href="/web-llvm/docs/api/structs/llvm/amdgpu/regbanklegalizerule">RegBankLegalizeRule</a> Init, bool STPred=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>

</div>
</div>

### Div() {#a47f8485cf0b53a865258100b2ce190a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuleSetInitializer &amp; llvm::AMDGPU::RegBankLegalizeRules::RuleSetInitializer::Div (<a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420">UniformityLLTOpPredicateID</a> Ty, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/regbanklltmapping">RegBankLLTMapping</a> RuleApplyIDs, bool STPred=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>

</div>
</div>

### Uni() {#a726fe89c6e1d347c2e5e439b01f05a4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuleSetInitializer &amp; llvm::AMDGPU::RegBankLegalizeRules::RuleSetInitializer::Uni (<a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420">UniformityLLTOpPredicateID</a> Ty, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/regbanklltmapping">RegBankLLTMapping</a> RuleApplyIDs, bool STPred=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### RuleSet {#a711cdb84f27703ce8e75d50510cff536}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetOfRulesForOpcode* llvm::AMDGPU::RegBankLegalizeRules::RuleSetInitializer::RuleSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
