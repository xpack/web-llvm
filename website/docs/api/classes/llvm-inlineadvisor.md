---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/inlineadvisor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InlineAdvisor` Class Reference

<p>Interface for deciding whether to inline a call site or not. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::InlineAdvisor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">llvm/Analysis/InlineAdvisor.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/defaultinlineadvisor">DefaultInlineAdvisor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The default (manual heuristics) implementation of the <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a>. <a href="/web-llvm/docs/api/classes/llvm/defaultinlineadvisor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor">MLInlineAdvisor</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/replayinlineadvisor">ReplayInlineAdvisor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replay inline advisor that uses optimization remarks from inlining of previous build to guide current inlining. <a href="/web-llvm/docs/api/classes/llvm/replayinlineadvisor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MandatoryInliningKind { <a href="#a6659e9fe3450059147033d140cd8496e">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbde086aef4218c2a020cb269aac241e">InlineAdvice</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec021d6b460b139f3c1d570a0f2dd4b6">InlineAdvisor</a> (InlineAdvisor &amp;&amp;)=delete</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2597292ee23303a90df44b154837e28">InlineAdvisor</a> (Module &amp;M, FunctionAnalysisManager &amp;FAM, std::optional&lt; InlineContext &gt; IC=std::nullopt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3543a4a2c8269e927fade2133305fdd8">~InlineAdvisor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/inlineadvice">InlineAdvice</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af70fa833673e4ac07c323a4a94e7ba93">getAdvice</a> (CallBase &amp;CB, bool MandatoryOnly=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an <a href="/web-llvm/docs/api/classes/llvm/inlineadvice">InlineAdvice</a> containing a recommendation on whether to inline or not. <a href="#af70fa833673e4ac07c323a4a94e7ba93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2cc3a8b2ee3d65fd980f63923fa2880">onPassEntry</a> (LazyCallGraph::SCC *SCC=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This must be called when the Inliner pass is entered, to allow the <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a> update internal state, as result of function passes run between Inliner pass runs (for the same module). <a href="#ab2cc3a8b2ee3d65fd980f63923fa2880">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb8650aeef845449ba752a76a4237559">onPassExit</a> (LazyCallGraph::SCC *SCC=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This must be called when the Inliner pass is exited, as function passes may be run subsequently. <a href="#adb8650aeef845449ba752a76a4237559">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53b898ebf0d54b9247ef6dbb6d6c0a7e">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Support for printer pass. <a href="#a53b898ebf0d54b9247ef6dbb6d6c0a7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab32ca9cecc0266fccc75103624277d56">getAnnotatedInlinePassName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NOTE pass name is annotated only when inline advisor constructor provides <a href="/web-llvm/docs/api/structs/llvm/inlinecontext">InlineContext</a>. <a href="#ab32ca9cecc0266fccc75103624277d56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/inlineadvice">InlineAdvice</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4fe3470520ae693bbe4ae6a64fbe70a">getAdviceImpl</a> (CallBase &amp;CB)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/inlineadvice">InlineAdvice</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a688e531fec2777cc8370b1c0cd11b5">getMandatoryAdvice</a> (CallBase &amp;CB, bool Advice)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14528ae0117f755bc5a74a7683c0722d">getCallerORE</a> (CallBase &amp;CB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab63e90899ab78f60bf47256071c0a48b">M</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b1b99bc0fe39cbe400f49bbd65f01c3">FAM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/inlinecontext">InlineContext</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0253ac1349dcc28b1ff91eaa4230d173">IC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dd80870f80af29e0c096ccad6ebacc8">AnnotatedInlinePassName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/importedfunctionsinliningstatistics">ImportedFunctionsInliningStatistics</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a82a41ed5fbaafb6ad968a1650a656f">ImportedFunctionsStats</a></td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a6659e9fe3450059147033d140cd8496e">MandatoryInliningKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2610d24c389789284bb8c8b616ab5e43">getMandatoryKind</a> (CallBase &amp;CB, FunctionAnalysisManager &amp;FAM, OptimizationRemarkEmitter &amp;ORE)</td>
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

## Description {#details}

<p>Interface for deciding whether to inline a call site or not.</p>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### MandatoryInliningKind {#a6659e9fe3450059147033d140cd8496e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::InlineAdvisor::MandatoryInliningKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">NotMandatory<a id="a6659e9fe3450059147033d140cd8496eaa95ba7435d3065e30aee4f4f89237abb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Always<a id="a6659e9fe3450059147033d140cd8496ea68eec46437c384d8dad18d5464ebc35c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Never<a id="a6659e9fe3450059147033d140cd8496ea6e7b34fa59e1bd229b207892956dc41c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### InlineAdvice {#adbde086aef4218c2a020cb269aac241e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/inlineadvice">InlineAdvice</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Reference <a href="#adbde086aef4218c2a020cb269aac241e">InlineAdvice</a>.</p>


<p>Referenced by <a href="#adbde086aef4218c2a020cb269aac241e">InlineAdvice</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InlineAdvisor() {#aec021d6b460b139f3c1d570a0f2dd4b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InlineAdvisor::InlineAdvisor (<a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a> &amp;&amp;)</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Reference <a href="#aec021d6b460b139f3c1d570a0f2dd4b6">InlineAdvisor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/defaultinlineadvisor/#a5b40df01d9cb958784cdfee64bfce7f6">llvm::DefaultInlineAdvisor::DefaultInlineAdvisor</a>, <a href="#aec021d6b460b139f3c1d570a0f2dd4b6">InlineAdvisor</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#a721f6a9227830f0254a70a740f43f24f">llvm::MLInlineAdvisor::MLInlineAdvisor</a> and <a href="/web-llvm/docs/api/classes/llvm/replayinlineadvisor/#a2c5f266941c1a559e1e8152c4f274307">llvm::ReplayInlineAdvisor::ReplayInlineAdvisor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### InlineAdvisor() {#ae2597292ee23303a90df44b154837e28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineAdvisor::InlineAdvisor (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; FAM, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/inlinecontext">InlineContext</a> &gt; IC=std::nullopt)</td>
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



<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>, definition at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp">InlineAdvisor.cpp</a>.</p>


<p>References <a href="#a6dd80870f80af29e0c096ccad6ebacc8">AnnotatedInlinePassName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c2a5dcf016849f14d98c8bf8e01e659">llvm::AnnotateInlinePassName</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp/#a1aa87636b87005b17ec0cba1b7ddf3ac">AnnotateInlinePhase</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="#a1b1b99bc0fe39cbe400f49bbd65f01c3">FAM</a>, <a href="#a0253ac1349dcc28b1ff91eaa4230d173">IC</a>, <a href="#a9a82a41ed5fbaafb6ad968a1650a656f">ImportedFunctionsStats</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadbd3f8e31479a825eb9f2e0dcdd4bbf">llvm::InlinerFunctionImportStats</a>, <a href="#ab63e90899ab78f60bf47256071c0a48b">M</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adacba4cb06d1dd9232ee3d2d49a44d8fabafd7322c6e97d25b6299b5d6fe8920b">llvm::No</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~InlineAdvisor() {#a3543a4a2c8269e927fade2133305fdd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineAdvisor::~InlineAdvisor ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>, definition at line 536 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp">InlineAdvisor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9a82a41ed5fbaafb6ad968a1650a656f">ImportedFunctionsStats</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadbd3f8e31479a825eb9f2e0dcdd4bbf">llvm::InlinerFunctionImportStats</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adacba4cb06d1dd9232ee3d2d49a44d8fabafd7322c6e97d25b6299b5d6fe8920b">llvm::No</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adacba4cb06d1dd9232ee3d2d49a44d8fad4a9fa383ab700c5bdd6f31cf7df0faf">llvm::Verbose</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAdvice() {#af70fa833673e4ac07c323a4a94e7ba93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; InlineAdvice &gt; InlineAdvisor::getAdvice (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, bool MandatoryOnly=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get an <a href="/web-llvm/docs/api/classes/llvm/inlineadvice">InlineAdvice</a> containing a recommendation on whether to inline or not.</p>


<p><span class="doxyComputerOutput">CB</span> is assumed to be a direct call. <span class="doxyComputerOutput">FAM</span> is assumed to be up-to-date wrt previous inlining decisions. <span class="doxyComputerOutput">MandatoryOnly</span> indicates only mandatory (always-inline) call sites should be recommended - this allows the <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a> track such inlininings. Returns:</p>


<ul class="doxyList ">
<li>An <a href="/web-llvm/docs/api/classes/llvm/inlineadvice">InlineAdvice</a> with the inlining recommendation.</li>
<li>Null when no recommendation is made (<a href="https://reviews.llvm.org/D110658">https://reviews.llvm.org/D110658</a>). TODO: Consider removing the Null return scenario by incorporating the SampleProfile inliner into an <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a></li>
</ul>

<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>, definition at line 615 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp">InlineAdvisor.cpp</a>.</p>


<p>References <a href="#a6659e9fe3450059147033d140cd8496ea68eec46437c384d8dad18d5464ebc35c">Always</a>, <a href="#a1b1b99bc0fe39cbe400f49bbd65f01c3">FAM</a>, <a href="#af4fe3470520ae693bbe4ae6a64fbe70a">getAdviceImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#afac5b39bcbb90d660f83d9b4bd8c6d95">llvm::CallBase::getCaller</a>, <a href="#a14528ae0117f755bc5a74a7683c0722d">getCallerORE</a>, <a href="#a9a688e531fec2777cc8370b1c0cd11b5">getMandatoryAdvice</a> and <a href="#a2610d24c389789284bb8c8b616ab5e43">getMandatoryKind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerpass/#ab7155781c9a6aafef322de28d9bc4c86">llvm::ModuleInlinerPass::run</a>.</p>

</div>
</div>

### getAnnotatedInlinePassName() {#ab32ca9cecc0266fccc75103624277d56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::InlineAdvisor::getAnnotatedInlinePassName ()</td>
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

<p>NOTE pass name is annotated only when inline advisor constructor provides <a href="/web-llvm/docs/api/structs/llvm/inlinecontext">InlineContext</a>.</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Reference <a href="#a6dd80870f80af29e0c096ccad6ebacc8">AnnotatedInlinePassName</a>.</p>

</div>
</div>

### onPassEntry() {#ab2cc3a8b2ee3d65fd980f63923fa2880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::InlineAdvisor::onPassEntry (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">LazyCallGraph::SCC</a> * SCC=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This must be called when the Inliner pass is entered, to allow the <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a> update internal state, as result of function passes run between Inliner pass runs (for the same module).</p>

<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerpass/#ab7155781c9a6aafef322de28d9bc4c86">llvm::ModuleInlinerPass::run</a>.</p>

</div>
</div>

### onPassExit() {#adb8650aeef845449ba752a76a4237559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::InlineAdvisor::onPassExit (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">LazyCallGraph::SCC</a> * SCC=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This must be called when the Inliner pass is exited, as function passes may be run subsequently.</p>


<p>This allows an implementation of <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a> to prepare for a partial update, based on the optional SCC.</p>


<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerpass/#ab7155781c9a6aafef322de28d9bc4c86">llvm::ModuleInlinerPass::run</a>.</p>

</div>
</div>

### print() {#a53b898ebf0d54b9247ef6dbb6d6c0a7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::InlineAdvisor::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Support for printer pass.</p>

<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getAdviceImpl() {#af4fe3470520ae693bbe4ae6a64fbe70a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::unique_ptr&lt; InlineAdvice &gt; llvm::InlineAdvisor::getAdviceImpl (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Referenced by <a href="#af70fa833673e4ac07c323a4a94e7ba93">getAdvice</a>.</p>

</div>
</div>

### getCallerORE() {#a14528ae0117f755bc5a74a7683c0722d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter &amp; InlineAdvisor::getCallerORE (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
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



<p>Declaration at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>, definition at line 625 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp">InlineAdvisor.cpp</a>.</p>


<p>References <a href="#a1b1b99bc0fe39cbe400f49bbd65f01c3">FAM</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#afac5b39bcbb90d660f83d9b4bd8c6d95">llvm::CallBase::getCaller</a>.</p>


<p>Referenced by <a href="#af70fa833673e4ac07c323a4a94e7ba93">getAdvice</a>, <a href="#a9a688e531fec2777cc8370b1c0cd11b5">getMandatoryAdvice</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#adca0f8d16629001e04b5f4d1cbae214b">llvm::MLInlineAdvisor::getMandatoryAdvice</a> and <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#aa64517193ce5ce41b3a4902fcece379e">llvm::MLInlineAdvisor::getMandatoryAdviceImpl</a>.</p>

</div>
</div>

### getMandatoryAdvice() {#a9a688e531fec2777cc8370b1c0cd11b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; InlineAdvice &gt; InlineAdvisor::getMandatoryAdvice (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, bool Advice)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>, definition at line 544 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp">InlineAdvisor.cpp</a>.</p>


<p>Reference <a href="#a14528ae0117f755bc5a74a7683c0722d">getCallerORE</a>.</p>


<p>Referenced by <a href="#af70fa833673e4ac07c323a4a94e7ba93">getAdvice</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AnnotatedInlinePassName {#a6dd80870f80af29e0c096ccad6ebacc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string llvm::InlineAdvisor::AnnotatedInlinePassName</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Referenced by <a href="#ab32ca9cecc0266fccc75103624277d56">getAnnotatedInlinePassName</a> and <a href="#ae2597292ee23303a90df44b154837e28">InlineAdvisor</a>.</p>

</div>
</div>

### FAM {#a1b1b99bc0fe39cbe400f49bbd65f01c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAnalysisManager&amp; llvm::InlineAdvisor::FAM</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/defaultinlineadvisor/#a5b40df01d9cb958784cdfee64bfce7f6">llvm::DefaultInlineAdvisor::DefaultInlineAdvisor</a>, <a href="#af70fa833673e4ac07c323a4a94e7ba93">getAdvice</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#adb44b65867ce48eee9d2d49cbdc60333">llvm::MLInlineAdvisor::getAdviceImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/replayinlineadvisor/#a83088027da72950b627f9200965fb55b">llvm::ReplayInlineAdvisor::getAdviceImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#a3b7f1071fac3720a2f1d4bd7da91625d">llvm::MLInlineAdvisor::getCachedFPI</a>, <a href="#a14528ae0117f755bc5a74a7683c0722d">getCallerORE</a>, <a href="#a2610d24c389789284bb8c8b616ab5e43">getMandatoryKind</a>, <a href="#ae2597292ee23303a90df44b154837e28">InlineAdvisor</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#a8116ffdfb54f7d195eb185c8bf7c060c">llvm::MLInlineAdvisor::onSuccessfulInlining</a> and <a href="/web-llvm/docs/api/classes/llvm/replayinlineadvisor/#a2c5f266941c1a559e1e8152c4f274307">llvm::ReplayInlineAdvisor::ReplayInlineAdvisor</a>.</p>

</div>
</div>

### IC {#a0253ac1349dcc28b1ff91eaa4230d173}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::optional&lt;InlineContext&gt; llvm::InlineAdvisor::IC</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/defaultinlineadvisor/#a5b40df01d9cb958784cdfee64bfce7f6">llvm::DefaultInlineAdvisor::DefaultInlineAdvisor</a>, <a href="#ae2597292ee23303a90df44b154837e28">InlineAdvisor</a> and <a href="/web-llvm/docs/api/classes/llvm/replayinlineadvisor/#a2c5f266941c1a559e1e8152c4f274307">llvm::ReplayInlineAdvisor::ReplayInlineAdvisor</a>.</p>

</div>
</div>

### ImportedFunctionsStats {#a9a82a41ed5fbaafb6ad968a1650a656f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ImportedFunctionsInliningStatistics&gt; llvm::InlineAdvisor::ImportedFunctionsStats</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Referenced by <a href="#ae2597292ee23303a90df44b154837e28">InlineAdvisor</a> and <a href="#a3543a4a2c8269e927fade2133305fdd8">~InlineAdvisor</a>.</p>

</div>
</div>

### M {#ab63e90899ab78f60bf47256071c0a48b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module&amp; llvm::InlineAdvisor::M</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/defaultinlineadvisor/#a5b40df01d9cb958784cdfee64bfce7f6">llvm::DefaultInlineAdvisor::DefaultInlineAdvisor</a>, <a href="#ae2597292ee23303a90df44b154837e28">InlineAdvisor</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#a721f6a9227830f0254a70a740f43f24f">llvm::MLInlineAdvisor::MLInlineAdvisor</a> and <a href="/web-llvm/docs/api/classes/llvm/replayinlineadvisor/#a2c5f266941c1a559e1e8152c4f274307">llvm::ReplayInlineAdvisor::ReplayInlineAdvisor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### getMandatoryKind() {#a2610d24c389789284bb8c8b616ab5e43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineAdvisor::MandatoryInliningKind InlineAdvisor::getMandatoryKind (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; FAM, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>, definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp">InlineAdvisor.cpp</a>.</p>


<p>References <a href="#a6659e9fe3450059147033d140cd8496ea68eec46437c384d8dad18d5464ebc35c">Always</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a1b1b99bc0fe39cbe400f49bbd65f01c3">FAM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa41f9508130468035e0087f7cbdffa14">llvm::getAttributeBasedInliningDecision</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="#a6659e9fe3450059147033d140cd8496ea6e7b34fa59e1bd229b207892956dc41c">Never</a> and <a href="#a6659e9fe3450059147033d140cd8496eaa95ba7435d3065e30aee4f4f89237abb">NotMandatory</a>.</p>


<p>Referenced by <a href="#af70fa833673e4ac07c323a4a94e7ba93">getAdvice</a> and <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#adb44b65867ce48eee9d2d49cbdc60333">llvm::MLInlineAdvisor::getAdviceImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp">InlineAdvisor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
