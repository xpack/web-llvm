---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/lastruntrackinginfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LastRunTrackingInfo` Class

<p>This class is used to track the last run of a set of module/function passes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LastRunTrackingInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lastruntrackinganalysis-h">llvm/Analysis/LastRunTrackingAnalysis.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3d69914220ce815fe1b92211a19c8b8">PassID</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38630dd2b6eed4825a5e3268cba2fca9">OptionPtr</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1281cf99d3c6f0b17846366a860fcd08">CompatibilityCheckFn</a> = std::function&lt; bool(<a href="#a38630dd2b6eed4825a5e3268cba2fca9">OptionPtr</a>)&gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename OptionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aded782b55c320e0f6449d228e6e818e0">shouldSkip</a> (PassID ID, const OptionT &amp;Opt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if we should skip a pass. <a href="#aded782b55c320e0f6449d228e6e818e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66c3731b9ae84afae4f85f37d770612e">shouldSkip</a> (PassID ID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename OptionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac51ca3e00e7887dfe14d20deac3eac5d">update</a> (PassID ID, bool Changed, const OptionT &amp;Opt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the tracking info. <a href="#ac51ca3e00e7887dfe14d20deac3eac5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afab06b9c519eb5699fb4a4a9b8c6771a">update</a> (PassID ID, bool Changed)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35133535964934696bee8b32f2987f7d">shouldSkipImpl</a> (PassID ID, OptionPtr Ptr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af160a6f56452b3d8f4f6196e68d04400">updateImpl</a> (PassID ID, bool Changed, CompatibilityCheckFn CheckFn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="#ae3d69914220ce815fe1b92211a19c8b8">PassID</a>, <a href="#a1281cf99d3c6f0b17846366a860fcd08">CompatibilityCheckFn</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadb0b6649b02eeea86b5c4bad123ac0d">TrackedPasses</a></td>
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

<p>This class is used to track the last run of a set of module/function passes.</p>


<p>Invalidation are conservatively handled by the pass manager if a pass doesn't explicitly preserve the result. If we want to skip a pass, we should define a unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> <span class="doxyComputerOutput"><a href="#ae3d69914220ce815fe1b92211a19c8b8">PassID</a></span> to identify the pass, which is usually a pointer to a static member. If a pass has parameters, they should be stored in a struct <span class="doxyComputerOutput">OptionT</span> with a method bool isCompatibleWith(const OptionT&amp; LastOpt) const to check compatibility.</p>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lastruntrackinganalysis-h">LastRunTrackingAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### CompatibilityCheckFn {#a1281cf99d3c6f0b17846366a860fcd08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LastRunTrackingInfo::CompatibilityCheckFn =  std::function&lt;bool(OptionPtr)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lastruntrackinganalysis-h">LastRunTrackingAnalysis.h</a>.</p>

</div>
</div>

### OptionPtr {#a38630dd2b6eed4825a5e3268cba2fca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LastRunTrackingInfo::OptionPtr =  const void *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lastruntrackinganalysis-h">LastRunTrackingAnalysis.h</a>.</p>

</div>
</div>

### PassID {#ae3d69914220ce815fe1b92211a19c8b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LastRunTrackingInfo::PassID =  const void *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lastruntrackinganalysis-h">LastRunTrackingAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### shouldSkip() {#aded782b55c320e0f6449d228e6e818e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename OptionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LastRunTrackingInfo::shouldSkip (<a href="#ae3d69914220ce815fe1b92211a19c8b8">PassID</a> ID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> OptionT &amp; Opt)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if we should skip a pass.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed"&gt;ID&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the pass.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Opt</td>
<td class="doxyParamItemDescription"><p>The parameters of the pass. If the pass has no parameters, use shouldSkip(PassID ID) instead.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if we should skip the pass.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>shouldSkip(PassID ID)</p></dd>
</dl>


<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lastruntrackinganalysis-h">LastRunTrackingAnalysis.h</a>.</p>

</div>
</div>

### shouldSkip() {#a66c3731b9ae84afae4f85f37d770612e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LastRunTrackingInfo::shouldSkip (<a href="#ae3d69914220ce815fe1b92211a19c8b8">PassID</a> ID)</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lastruntrackinganalysis-h">LastRunTrackingAnalysis.h</a>.</p>

</div>
</div>

### update() {#ac51ca3e00e7887dfe14d20deac3eac5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename OptionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LastRunTrackingInfo::update (<a href="#ae3d69914220ce815fe1b92211a19c8b8">PassID</a> ID, bool Changed, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> OptionT &amp; Opt)</td>
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

<p>Update the tracking info.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed"&gt;ID&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the pass.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Changed</td>
<td class="doxyParamItemDescription"><p>Whether the pass makes changes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Opt</td>
<td class="doxyParamItemDescription"><p>The parameters of the pass. It must have the same type as the parameters of the last run. If the pass has no parameters, use <a href="#afab06b9c519eb5699fb4a4a9b8c6771a">update(PassID ID, bool Changed)</a> instead.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#afab06b9c519eb5699fb4a4a9b8c6771a">update(PassID ID, bool Changed)</a></p></dd>
</dl>


<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lastruntrackinganalysis-h">LastRunTrackingAnalysis.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### update() {#afab06b9c519eb5699fb4a4a9b8c6771a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LastRunTrackingInfo::update (<a href="#ae3d69914220ce815fe1b92211a19c8b8">PassID</a> ID, bool Changed)</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lastruntrackinganalysis-h">LastRunTrackingAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### shouldSkipImpl() {#a35133535964934696bee8b32f2987f7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LastRunTrackingInfo::shouldSkipImpl (<a href="#ae3d69914220ce815fe1b92211a19c8b8">PassID</a> ID, <a href="#a38630dd2b6eed4825a5e3268cba2fca9">OptionPtr</a> Ptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lastruntrackinganalysis-h">LastRunTrackingAnalysis.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lastruntrackinganalysis-cpp">LastRunTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### updateImpl() {#af160a6f56452b3d8f4f6196e68d04400}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LastRunTrackingInfo::updateImpl (<a href="#ae3d69914220ce815fe1b92211a19c8b8">PassID</a> ID, bool Changed, <a href="#a1281cf99d3c6f0b17846366a860fcd08">CompatibilityCheckFn</a> CheckFn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lastruntrackinganalysis-h">LastRunTrackingAnalysis.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lastruntrackinganalysis-cpp">LastRunTrackingAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### TrackedPasses {#aadb0b6649b02eeea86b5c4bad123ac0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;PassID, CompatibilityCheckFn&gt; llvm::LastRunTrackingInfo::TrackedPasses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lastruntrackinganalysis-h">LastRunTrackingAnalysis.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lastruntrackinganalysis-h">LastRunTrackingAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/lastruntrackinganalysis-cpp">LastRunTrackingAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
