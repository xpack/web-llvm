---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/objcarc/objcarcaaresult
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ObjCARCAAResult` Class

<p>This is a simple alias analysis implementation that uses knowledge of ARC constructs to answer queries. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::objcarc::ObjCARCAAResult { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcaliasanalysis-h">llvm/Analysis/ObjCARCAliasAnalysis.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa558df5adb4602540099fa2e41e5fae6">ObjCARCAAResult</a> (const DataLayout &amp;DL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0c6c4daf501873faf45452ae7ada993">ObjCARCAAResult</a> (ObjCARCAAResult &amp;&amp;Arg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad74d999404cc1c1beb3ae18fcad166e8">invalidate</a> (Function &amp;, const PreservedAnalyses &amp;, FunctionAnalysisManager::Invalidator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle invalidation events from the new pass manager. <a href="#ad74d999404cc1c1beb3ae18fcad166e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aliasresult">AliasResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfba8e1035be99ff311c1af58e624878">alias</a> (const MemoryLocation &amp;LocA, const MemoryLocation &amp;LocB, AAQueryInfo &amp;AAQI, const Instruction *CtxI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a846e0f39264857f2a44cbab95183b2a6">getModRefInfoMask</a> (const MemoryLocation &amp;Loc, AAQueryInfo &amp;AAQI, bool IgnoreLocals)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a071f909717c950fac24cc53e42ef4c86">getMemoryEffects</a> (const Function *F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab37ef2f706e7e7f64d0d3cd8e76d91bd">getModRefInfo</a> (const CallBase *Call, const MemoryLocation &amp;Loc, AAQueryInfo &amp;AAQI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a220014fc38f863e217586c7816db4b9c">getMemoryEffects</a> (const CallBase *Call, AAQueryInfo &amp;AAQI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a060af8328f0f6f2c815f92fbd9202f23">getModRefInfo</a> (const CallBase *Call1, const CallBase *Call2, AAQueryInfo &amp;AAQI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60a57ae56176a3929ab4373537fcb461">DL</a></td>
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

<p>This is a simple alias analysis implementation that uses knowledge of ARC constructs to answer queries.</p>


<p>TODO: This class could be generalized to know about other ObjC-specific tricks. Such as knowing that ivars in the non-fragile ABI are non-aliasing even though their offsets are dynamic.</p>


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcaliasanalysis-h">ObjCARCAliasAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ObjCARCAAResult() {#aa558df5adb4602540099fa2e41e5fae6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::objcarc::ObjCARCAAResult::ObjCARCAAResult (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcaliasanalysis-h">ObjCARCAliasAnalysis.h</a>.</p>


<p>Referenced by <a href="#aa0c6c4daf501873faf45452ae7ada993">ObjCARCAAResult</a>.</p>

</div>
</div>

### ObjCARCAAResult() {#aa0c6c4daf501873faf45452ae7ada993}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::objcarc::ObjCARCAAResult::ObjCARCAAResult (<a href="/web-llvm/docs/api/classes/llvm/objcarc/objcarcaaresult">ObjCARCAAResult</a> &amp;&amp; Arg)</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcaliasanalysis-h">ObjCARCAliasAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/aaresultbase/#adda3309ea19cc0a7a0bcb090630bbfc4">llvm::AAResultBase::AAResultBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#aa558df5adb4602540099fa2e41e5fae6">ObjCARCAAResult</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### alias() {#acfba8e1035be99ff311c1af58e624878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasResult ObjCARCAAResult::alias (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; LocA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; LocB, <a href="/web-llvm/docs/api/classes/llvm/aaqueryinfo">AAQueryInfo</a> &amp; AAQI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcaliasanalysis-h">ObjCARCAliasAnalysis.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/objcarcaliasanalysis-cpp">ObjCARCAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a926099ca5ca5db6ba2de398c2487b725">llvm::MemoryLocation::AATags</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresultbase/#aebc901269a6aa648319ad24cd43b6a1e">llvm::AAResultBase::alias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a6771e7364c5ab8a6354f744fe5bbc62b">llvm::objcarc::EnableARCOpts</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a46815b7f69bb96eddd2e1e01bec6120c">llvm::MemoryLocation::getBeforeOrAfter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#ac5d623f0353e96c824196d6f6abc2dca">llvm::objcarc::GetRCIdentityRoot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#ac420b82af0836c9c4312b413c8a0b6b4">llvm::objcarc::GetUnderlyingObjCPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57a0916b614598c673c1e6a59c7312a1409">llvm::AliasResult::MayAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57a863ee317b92588eb2d6878af9fc98922">llvm::AliasResult::NoAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a9550ce4a179e46db37f653ce28feca7a">llvm::MemoryLocation::Ptr</a> and <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a39f7ff959874bf38f3e14aa0b2622da0">llvm::MemoryLocation::Size</a>.</p>

</div>
</div>

### getMemoryEffects() {#a071f909717c950fac24cc53e42ef4c86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffects ObjCARCAAResult::getMemoryEffects (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcaliasanalysis-h">ObjCARCAliasAnalysis.h</a>, definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/objcarcaliasanalysis-cpp">ObjCARCAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a6771e7364c5ab8a6354f744fe5bbc62b">llvm::objcarc::EnableARCOpts</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a4e557a8b99ad5d09e3018b1f3e02a08f">llvm::objcarc::GetFunctionClass</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresultbase/#a220014fc38f863e217586c7816db4b9c">llvm::AAResultBase::getMemoryEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#af04065f3c729719471689b08089942f3">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::none</a> and <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2ad20eb2456d446869820a1e7e385fe99f">llvm::objcarc::NoopCast</a>.</p>

</div>
</div>

### getMemoryEffects() {#a220014fc38f863e217586c7816db4b9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffects llvm::AAResultBase::getMemoryEffects (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call, <a href="/web-llvm/docs/api/classes/llvm/aaqueryinfo">AAQueryInfo</a> &amp; AAQI)</td>
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



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcaliasanalysis-h">ObjCARCAliasAnalysis.h</a>, definition at line 846 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>

</div>
</div>

### getModRefInfo() {#ab37ef2f706e7e7f64d0d3cd8e76d91bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModRefInfo ObjCARCAAResult::getModRefInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/aaqueryinfo">AAQueryInfo</a> &amp; AAQI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcaliasanalysis-h">ObjCARCAliasAnalysis.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/objcarcaliasanalysis-cpp">ObjCARCAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2a61710f61a521b1544f5f7ab5abac843d">llvm::objcarc::Autorelease</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2a56a1f8ca583bf2a38d53b7e7825bd269">llvm::objcarc::AutoreleasepoolPush</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2ac1dbc9b59747323224171927c310917d">llvm::objcarc::AutoreleaseRV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2ac3755e61202abd74da5885d2e9c9160e">llvm::objcarc::Call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a6771e7364c5ab8a6354f744fe5bbc62b">llvm::objcarc::EnableARCOpts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2a044369e2f723153babfab4e7ba65dda4">llvm::objcarc::FusedRetainAutorelease</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2aae83ce7464791df134eac666ac62c9cd">llvm::objcarc::FusedRetainAutoreleaseRV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a86cdbdf3773be3c67bc193b473b75708">llvm::objcarc::GetBasicARCInstKind</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresultbase/#adb56d853930e9104a7d1b3b1e2e82af8">llvm::AAResultBase::getModRefInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ead974636fce6d12e72054e61fb3c1e9a8">llvm::NoModRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2ad20eb2456d446869820a1e7e385fe99f">llvm::objcarc::NoopCast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2aafece4245269582cb2f1009d4fb52047">llvm::objcarc::Retain</a> and <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2aa1226b5450384ce6ea5ed47c317303ee">llvm::objcarc::RetainRV</a>.</p>

</div>
</div>

### getModRefInfo() {#a060af8328f0f6f2c815f92fbd9202f23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModRefInfo llvm::AAResultBase::getModRefInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call2, <a href="/web-llvm/docs/api/classes/llvm/aaqueryinfo">AAQueryInfo</a> &amp; AAQI)</td>
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



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcaliasanalysis-h">ObjCARCAliasAnalysis.h</a>, definition at line 859 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>

</div>
</div>

### getModRefInfoMask() {#a846e0f39264857f2a44cbab95183b2a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModRefInfo ObjCARCAAResult::getModRefInfoMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/aaqueryinfo">AAQueryInfo</a> &amp; AAQI, bool IgnoreLocals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcaliasanalysis-h">ObjCARCAliasAnalysis.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/objcarcaliasanalysis-cpp">ObjCARCAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a6771e7364c5ab8a6354f744fe5bbc62b">llvm::objcarc::EnableARCOpts</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a46815b7f69bb96eddd2e1e01bec6120c">llvm::MemoryLocation::getBeforeOrAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresultbase/#a43487a55e1c14c5a2e4f83731d4eca00">llvm::AAResultBase::getModRefInfoMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#ac5d623f0353e96c824196d6f6abc2dca">llvm::objcarc::GetRCIdentityRoot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#ac420b82af0836c9c4312b413c8a0b6b4">llvm::objcarc::GetUnderlyingObjCPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae96dbd1485a431400525ca17896ec48e">llvm::isNoModRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea6524b183b5cd0850f2cff6d30d581af9">llvm::ModRef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ead974636fce6d12e72054e61fb3c1e9a8">llvm::NoModRef</a>.</p>

</div>
</div>

### invalidate() {#ad74d999404cc1c1beb3ae18fcad166e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcarc::ObjCARCAAResult::invalidate (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp;, FunctionAnalysisManager::Invalidator &amp;)</td>
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


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcaliasanalysis-h">ObjCARCAliasAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DL {#a60a57ae56176a3929ab4373537fcb461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; llvm::objcarc::ObjCARCAAResult::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcaliasanalysis-h">ObjCARCAliasAnalysis.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcaliasanalysis-h">ObjCARCAliasAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/objcarcaliasanalysis-cpp">ObjCARCAliasAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
