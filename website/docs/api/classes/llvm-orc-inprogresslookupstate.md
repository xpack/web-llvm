---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/inprogresslookupstate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InProgressLookupState` Class



## Declaration

<div class="doxyDeclaration">
class llvm::orc::InProgressLookupState { ... }
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/inprogressfulllookupstate">InProgressFullLookupState</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/inprogresslookupflagsstate">InProgressLookupFlagsState</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a4b9e44ac291673bb5e53deff20f7194a">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2ef112a937cb6eb9bfc76ddeb5f14b7">InProgressLookupState</a> (LookupKind K, JITDylibSearchOrder SearchOrder, SymbolLookupSet LookupSet, SymbolState RequiredState)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030234862626fb450832fe23037bbbbb">~InProgressLookupState</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c027adb957c41a82d13bc26f3c330fd">complete</a> (std::unique_ptr&lt; InProgressLookupState &gt; IPLS)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abec29d92ce446df3a0dd3b0e6f319fc2">fail</a> (Error Err)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eb">LookupKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0503b098d8f706ceb3011e07018b1e20">K</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1a2b573da544cf233d62075a16146245">JITDylibSearchOrder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34a45b05b610fd64d9e88300a988d2f4">SearchOrder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67a1ee8aa73eb8d7753631bbb90cd4ff">LookupSet</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#adac25fca9fb14b1defe43d18a81c16e8">SymbolState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7827c12c8d1ab12601ed84b26bfb9ba">RequiredState</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eac187e1b6f23b2d1240be695469c56">CurSearchOrderIndex</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5034c282e435965e8496bd92e9d736f">NewJITDylib</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3475cb57627fd8b2fbad61e7ab365c35">DefGeneratorCandidates</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aade27bcee55482f6a8c4e850270d6a1c">DefGeneratorNonCandidates</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="/web-llvm/docs/api/classes/llvm/orc/inprogresslookupstate">llvm::orc::InProgressLookupState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae67f366751f50cb624ef56265520673c">GenState</a> = <a href="#a4b9e44ac291673bb5e53deff20f7194aaa7d762b792b32bc25c73caefe1d22ed1">NotInGenerator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::weak_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/definitiongenerator">DefinitionGenerator</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b7df08cf9b4b9cff708cbb006924066">CurDefGeneratorStack</a></td>
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


<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a4b9e44ac291673bb5e53deff20f7194a}

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
<td class="doxyEnumItemName">NotInGenerator<a id="a4b9e44ac291673bb5e53deff20f7194aaa7d762b792b32bc25c73caefe1d22ed1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ResumedForGenerator<a id="a4b9e44ac291673bb5e53deff20f7194aa6ddf41dd09199894c1c912011b3abc39"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InGenerator<a id="a4b9e44ac291673bb5e53deff20f7194aa95b489f3402078dd8b1d43ecdb790475"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InProgressLookupState() {#aa2ef112a937cb6eb9bfc76ddeb5f14b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::InProgressLookupState::InProgressLookupState (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eb">LookupKind</a> K, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1a2b573da544cf233d62075a16146245">JITDylibSearchOrder</a> SearchOrder, <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a> LookupSet, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adac25fca9fb14b1defe43d18a81c16e8">SymbolState</a> RequiredState)</td>
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



<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="#a3475cb57627fd8b2fbad61e7ab365c35">DefGeneratorCandidates</a>, <a href="#a0503b098d8f706ceb3011e07018b1e20">K</a>, <a href="#a67a1ee8aa73eb8d7753631bbb90cd4ff">LookupSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#aa7827c12c8d1ab12601ed84b26bfb9ba">RequiredState</a> and <a href="#a34a45b05b610fd64d9e88300a988d2f4">SearchOrder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/inprogressfulllookupstate/#a0b257d3ba2ff9d7ff38169bd8d35e0d8">llvm::orc::InProgressFullLookupState::InProgressFullLookupState</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/inprogresslookupflagsstate/#a6117ca26c78ca8333248b480fda8bb46">llvm::orc::InProgressLookupFlagsState::InProgressLookupFlagsState</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~InProgressLookupState() {#a030234862626fb450832fe23037bbbbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::orc::InProgressLookupState::~InProgressLookupState ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### complete() {#a6c027adb957c41a82d13bc26f3c330fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::orc::InProgressLookupState::complete (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/inprogresslookupstate">InProgressLookupState</a> &gt; IPLS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### fail() {#abec29d92ce446df3a0dd3b0e6f319fc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::orc::InProgressLookupState::fail (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 524 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CurDefGeneratorStack {#a3b7df08cf9b4b9cff708cbb006924066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::weak_ptr&lt;DefinitionGenerator&gt; &gt; llvm::orc::InProgressLookupState::CurDefGeneratorStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### CurSearchOrderIndex {#a5eac187e1b6f23b2d1240be695469c56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::InProgressLookupState::CurSearchOrderIndex = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### DefGeneratorCandidates {#a3475cb57627fd8b2fbad61e7ab365c35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolLookupSet llvm::orc::InProgressLookupState::DefGeneratorCandidates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>Referenced by <a href="#aa2ef112a937cb6eb9bfc76ddeb5f14b7">InProgressLookupState</a>.</p>

</div>
</div>

### DefGeneratorNonCandidates {#aade27bcee55482f6a8c4e850270d6a1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolLookupSet llvm::orc::InProgressLookupState::DefGeneratorNonCandidates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### GenState {#ae67f366751f50cb624ef56265520673c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::orc::InProgressLookupState llvm::orc::InProgressLookupState::GenState = <a href="#a4b9e44ac291673bb5e53deff20f7194aaa7d762b792b32bc25c73caefe1d22ed1">NotInGenerator</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### K {#a0503b098d8f706ceb3011e07018b1e20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LookupKind llvm::orc::InProgressLookupState::K</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/inprogressfulllookupstate/#a0b257d3ba2ff9d7ff38169bd8d35e0d8">llvm::orc::InProgressFullLookupState::InProgressFullLookupState</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprogresslookupflagsstate/#a6117ca26c78ca8333248b480fda8bb46">llvm::orc::InProgressLookupFlagsState::InProgressLookupFlagsState</a> and <a href="#aa2ef112a937cb6eb9bfc76ddeb5f14b7">InProgressLookupState</a>.</p>

</div>
</div>

### LookupSet {#a67a1ee8aa73eb8d7753631bbb90cd4ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolLookupSet llvm::orc::InProgressLookupState::LookupSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/inprogressfulllookupstate/#a0b257d3ba2ff9d7ff38169bd8d35e0d8">llvm::orc::InProgressFullLookupState::InProgressFullLookupState</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprogresslookupflagsstate/#a6117ca26c78ca8333248b480fda8bb46">llvm::orc::InProgressLookupFlagsState::InProgressLookupFlagsState</a> and <a href="#aa2ef112a937cb6eb9bfc76ddeb5f14b7">InProgressLookupState</a>.</p>

</div>
</div>

### NewJITDylib {#ae5034c282e435965e8496bd92e9d736f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::InProgressLookupState::NewJITDylib = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### RequiredState {#aa7827c12c8d1ab12601ed84b26bfb9ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolState llvm::orc::InProgressLookupState::RequiredState</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/inprogressfulllookupstate/#a0b257d3ba2ff9d7ff38169bd8d35e0d8">llvm::orc::InProgressFullLookupState::InProgressFullLookupState</a> and <a href="#aa2ef112a937cb6eb9bfc76ddeb5f14b7">InProgressLookupState</a>.</p>

</div>
</div>

### SearchOrder {#a34a45b05b610fd64d9e88300a988d2f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylibSearchOrder llvm::orc::InProgressLookupState::SearchOrder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/inprogressfulllookupstate/#a43d9a7a382ce864e1483f1d7587a5b28">llvm::orc::InProgressFullLookupState::complete</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprogresslookupflagsstate/#a08a9ea6aa70ed00ae1df670f081a3191">llvm::orc::InProgressLookupFlagsState::complete</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprogressfulllookupstate/#a0b257d3ba2ff9d7ff38169bd8d35e0d8">llvm::orc::InProgressFullLookupState::InProgressFullLookupState</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprogresslookupflagsstate/#a6117ca26c78ca8333248b480fda8bb46">llvm::orc::InProgressLookupFlagsState::InProgressLookupFlagsState</a> and <a href="#aa2ef112a937cb6eb9bfc76ddeb5f14b7">InProgressLookupState</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
