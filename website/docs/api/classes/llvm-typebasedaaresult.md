---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/typebasedaaresult
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TypeBasedAAResult` Class

<p>A simple <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> result that uses TBAA metadata to answer queries. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::TypeBasedAAResult { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typebasedaliasanalysis-h">llvm/Analysis/TypeBasedAliasAnalysis.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3ba073eddbeb64f3b8c092a5113696c">TypeBasedAAResult</a> (bool UsingTypeSanitizer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa970b67b23371c644c85b738bddc011a">invalidate</a> (Function &amp;, const PreservedAnalyses &amp;, FunctionAnalysisManager::Invalidator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle invalidation events from the new pass manager. <a href="#aa970b67b23371c644c85b738bddc011a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aliasresult">AliasResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac92480fed6d1bffab7843f41e0a51c20">alias</a> (const MemoryLocation &amp;LocA, const MemoryLocation &amp;LocB, AAQueryInfo &amp;AAQI, const Instruction *CtxI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad493c2ada6839ee1efeee33b33aae027">getModRefInfoMask</a> (const MemoryLocation &amp;Loc, AAQueryInfo &amp;AAQI, bool IgnoreLocals)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a44ad2b29af9ebe3d12a99843a7594757">MemoryEffects</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb8a8e302536d23fe8f8959ab4e942f0">getMemoryEffects</a> (const CallBase *Call, AAQueryInfo &amp;AAQI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a44ad2b29af9ebe3d12a99843a7594757">MemoryEffects</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9351f4b27b4cc2e1af57c04b58d71a42">getMemoryEffects</a> (const Function *F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed09e169ce456605fb08f93235a24304">getModRefInfo</a> (const CallBase *Call, const MemoryLocation &amp;Loc, AAQueryInfo &amp;AAQI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a121ec6b783769a5612f6cc225a2838b2">getModRefInfo</a> (const CallBase *Call1, const CallBase *Call2, AAQueryInfo &amp;AAQI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0c9c9d2d4627482854455123ce23471">Aliases</a> (const MDNode *A, const MDNode *B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Aliases - Test whether the access represented by tag A may alias the access represented by tag B. <a href="#af0c9c9d2d4627482854455123ce23471">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b847d658ef34c458b6f4ae058cc047b">shouldUseTBAA</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if TBAA metadata should be used, that is if TBAA is enabled and type sanitizer is not used. <a href="#a0b847d658ef34c458b6f4ae058cc047b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a220b678b4b4009d36d58c64f1ad9b3aa">UsingTypeSanitizer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if type sanitizer is enabled. <a href="#a220b678b4b4009d36d58c64f1ad9b3aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A simple <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> result that uses TBAA metadata to answer queries.</p>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typebasedaliasanalysis-h">TypeBasedAliasAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TypeBasedAAResult() {#ab3ba073eddbeb64f3b8c092a5113696c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TypeBasedAAResult::TypeBasedAAResult (bool UsingTypeSanitizer)</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typebasedaliasanalysis-h">TypeBasedAliasAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### alias() {#ac92480fed6d1bffab7843f41e0a51c20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasResult TypeBasedAAResult::alias (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; LocA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; LocB, <a href="/web-llvm/docs/api/classes/llvm/aaqueryinfo">AAQueryInfo</a> &amp; AAQI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typebasedaliasanalysis-h">TypeBasedAliasAnalysis.h</a>, definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a926099ca5ca5db6ba2de398c2487b725">llvm::MemoryLocation::AATags</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57a0916b614598c673c1e6a59c7312a1409">llvm::AliasResult::MayAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57a863ee317b92588eb2d6878af9fc98922">llvm::AliasResult::NoAlias</a> and <a href="/web-llvm/docs/api/structs/llvm/aamdnodes/#a56188042f9dd6003cb8ed087e8ae654f">llvm::AAMDNodes::TBAA</a>.</p>

</div>
</div>

### getMemoryEffects() {#afb8a8e302536d23fe8f8959ab4e942f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffects TypeBasedAAResult::getMemoryEffects (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call, <a href="/web-llvm/docs/api/classes/llvm/aaqueryinfo">AAQueryInfo</a> &amp; AAQI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typebasedaliasanalysis-h">TypeBasedAliasAnalysis.h</a>, definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp/#a5e19d69f8c65d343b518e66bef56db58">isStructPathTBAA</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#af04065f3c729719471689b08089942f3">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::none</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#aff771abf487136aeebb6862871d5e715">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::unknown</a>.</p>

</div>
</div>

### getMemoryEffects() {#a9351f4b27b4cc2e1af57c04b58d71a42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffects TypeBasedAAResult::getMemoryEffects (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typebasedaliasanalysis-h">TypeBasedAliasAnalysis.h</a>, definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#aff771abf487136aeebb6862871d5e715">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::unknown</a>.</p>

</div>
</div>

### getModRefInfo() {#aed09e169ce456605fb08f93235a24304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModRefInfo TypeBasedAAResult::getModRefInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/aaqueryinfo">AAQueryInfo</a> &amp; AAQI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typebasedaliasanalysis-h">TypeBasedAliasAnalysis.h</a>, definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea6524b183b5cd0850f2cff6d30d581af9">llvm::ModRef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ead974636fce6d12e72054e61fb3c1e9a8">llvm::NoModRef</a>.</p>

</div>
</div>

### getModRefInfo() {#a121ec6b783769a5612f6cc225a2838b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModRefInfo TypeBasedAAResult::getModRefInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call2, <a href="/web-llvm/docs/api/classes/llvm/aaqueryinfo">AAQueryInfo</a> &amp; AAQI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typebasedaliasanalysis-h">TypeBasedAliasAnalysis.h</a>, definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6c09737e146b2d816c911a047ac67ba4">llvm::Instruction::getMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a58328e0582aabaf012bf9bc6f36c9e04">llvm::M1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea6524b183b5cd0850f2cff6d30d581af9">llvm::ModRef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ead974636fce6d12e72054e61fb3c1e9a8">llvm::NoModRef</a>.</p>

</div>
</div>

### getModRefInfoMask() {#ad493c2ada6839ee1efeee33b33aae027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModRefInfo TypeBasedAAResult::getModRefInfoMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/aaqueryinfo">AAQueryInfo</a> &amp; AAQI, bool IgnoreLocals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typebasedaliasanalysis-h">TypeBasedAliasAnalysis.h</a>, definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp/#a5e19d69f8c65d343b518e66bef56db58">isStructPathTBAA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea6524b183b5cd0850f2cff6d30d581af9">llvm::ModRef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ead974636fce6d12e72054e61fb3c1e9a8">llvm::NoModRef</a>.</p>

</div>
</div>

### invalidate() {#aa970b67b23371c644c85b738bddc011a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TypeBasedAAResult::invalidate (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp;, FunctionAnalysisManager::Invalidator &amp;)</td>
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


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typebasedaliasanalysis-h">TypeBasedAliasAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### Aliases() {#af0c9c9d2d4627482854455123ce23471}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TypeBasedAAResult::Aliases (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Aliases - Test whether the access represented by tag A may alias the access represented by tag B.</p>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typebasedaliasanalysis-h">TypeBasedAliasAnalysis.h</a>, definition at line 704 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>

</div>
</div>

### shouldUseTBAA() {#a0b847d658ef34c458b6f4ae058cc047b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TypeBasedAAResult::shouldUseTBAA ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if TBAA metadata should be used, that is if TBAA is enabled and type sanitizer is not used.</p>

<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typebasedaliasanalysis-h">TypeBasedAliasAnalysis.h</a>, definition at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### UsingTypeSanitizer {#a220b678b4b4009d36d58c64f1ad9b3aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TypeBasedAAResult::UsingTypeSanitizer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if type sanitizer is enabled.</p>


<p>When TypeSanitizer is used, don't use TBAA information for alias analysis as this might cause us to remove memory accesses that we need to verify at runtime.</p>


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typebasedaliasanalysis-h">TypeBasedAliasAnalysis.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typebasedaliasanalysis-h">TypeBasedAliasAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
