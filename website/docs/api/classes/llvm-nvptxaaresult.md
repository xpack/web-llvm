---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/nvptxaaresult
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `NVPTXAAResult` Class



## Declaration

<div class="doxyDeclaration">
class llvm::NVPTXAAResult { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-h">Target/NVPTX/NVPTXAliasAnalysis.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aaresultbase">AAResultBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A base class to help implement the function alias analysis results concept. <a href="/web-llvm/docs/api/classes/llvm/aaresultbase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0b8195c458b665da7803a8a37170028">NVPTXAAResult</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14b36bd54de00e5794e09ba57a4f6986">NVPTXAAResult</a> (NVPTXAAResult &amp;&amp;Arg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f084b0d0c3c11f2cced5117170e2946">invalidate</a> (Function &amp;, const PreservedAnalyses &amp;, FunctionAnalysisManager::Invalidator &amp;Inv)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle invalidation events from the new pass manager. <a href="#a7f084b0d0c3c11f2cced5117170e2946">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aliasresult">AliasResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c6e127da93ba9d67d0f1d42a0e9827b">alias</a> (const MemoryLocation &amp;LocA, const MemoryLocation &amp;LocB, AAQueryInfo &amp;AAQI, const Instruction *CtxI=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89e48d7cde834ecb75ae97735d23462e">getModRefInfoMask</a> (const MemoryLocation &amp;Loc, AAQueryInfo &amp;AAQI, bool IgnoreLocals)</td>
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


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-h">NVPTXAliasAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NVPTXAAResult() {#ae0b8195c458b665da7803a8a37170028}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::NVPTXAAResult::NVPTXAAResult ()</td>
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



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-h">NVPTXAliasAnalysis.h</a>.</p>


<p>Referenced by <a href="#a14b36bd54de00e5794e09ba57a4f6986">NVPTXAAResult</a>.</p>

</div>
</div>

### NVPTXAAResult() {#a14b36bd54de00e5794e09ba57a4f6986}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::NVPTXAAResult::NVPTXAAResult (<a href="/web-llvm/docs/api/classes/llvm/nvptxaaresult">NVPTXAAResult</a> &amp;&amp; Arg)</td>
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



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-h">NVPTXAliasAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/aaresultbase/#adda3309ea19cc0a7a0bcb090630bbfc4">llvm::AAResultBase::AAResultBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#ae0b8195c458b665da7803a8a37170028">NVPTXAAResult</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### alias() {#a3c6e127da93ba9d67d0f1d42a0e9827b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasResult NVPTXAAResult::alias (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; LocA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; LocB, <a href="/web-llvm/docs/api/classes/llvm/aaqueryinfo">AAQueryInfo</a> &amp; AAQI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-h">NVPTXAliasAnalysis.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp">NVPTXAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp/#af6ab6e89a7e272521d7641859805a0ba">getAddressSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp/#aa108193c2ff5ea46a3ada182dd7867e7">getAliasResult</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a9550ce4a179e46db37f653ce28feca7a">llvm::MemoryLocation::Ptr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp/#a0b2bb68cc2336782f7cf85bec893b2c8">TraverseAddressSpacesLimit</a>.</p>

</div>
</div>

### getModRefInfoMask() {#a89e48d7cde834ecb75ae97735d23462e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModRefInfo NVPTXAAResult::getModRefInfoMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/aaqueryinfo">AAQueryInfo</a> &amp; AAQI, bool IgnoreLocals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-h">NVPTXAliasAnalysis.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp">NVPTXAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp/#af6ab6e89a7e272521d7641859805a0ba">getAddressSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp/#ada8150e3a71552f9e815108aba570643">isConstOrParam</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea6524b183b5cd0850f2cff6d30d581af9">llvm::ModRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ead974636fce6d12e72054e61fb3c1e9a8">llvm::NoModRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp/#a0b2bb68cc2336782f7cf85bec893b2c8">TraverseAddressSpacesLimit</a>.</p>

</div>
</div>

### invalidate() {#a7f084b0d0c3c11f2cced5117170e2946}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::NVPTXAAResult::invalidate (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp;, FunctionAnalysisManager::Invalidator &amp; Inv)</td>
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

<p>Handle invalidation events from the new pass manager.</p>


<p>By definition, this result is stateless and so remains valid.</p>


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-h">NVPTXAliasAnalysis.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp">NVPTXAliasAnalysis.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-h">NVPTXAliasAnalysis.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
