---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-wholeprogramdevirt-cpp-/callsiteinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CallSiteInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{WholeProgramDevirt.cpp}::CallSiteInfo { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd1a56d2f4d852e0d29acee4882cb321">isExported</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9237d4ff2a28a78a5fb6b285a776f620">addSummaryTypeCheckedLoadUser</a> (FunctionSummary *FS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fa4ee7f2260d0bb0406261ba802d76a">addSummaryTypeTestAssumeUser</a> (FunctionSummary *FS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af92dbd7f8b58ee509f6d50304aadf83b">markDevirt</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/virtualcallsite">VirtualCallSite</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c34f9725a50f48351c04484e7c151e0">CallSites</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of call sites for this slot. <a href="#a4c34f9725a50f48351c04484e7c151e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84d3e2451a78887146475d5f1e687b74">AllCallSitesDevirted</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether all call sites represented by this <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/callsiteinfo">CallSiteInfo</a>, including those in summaries, have been devirtualized. <a href="#a84d3e2451a78887146475d5f1e687b74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8caa5307b4dd65a69d3d7bb4be12491a">SummaryHasTypeTestAssumeUsers</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether any function summary contains an llvm.assume(llvm.type.test) for this slot. <a href="#a8caa5307b4dd65a69d3d7bb4be12491a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a048cde5a3dc1734d95364bb8bf08430b">SummaryTypeCheckedLoadUsers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CFI-specific: a vector containing the list of function summaries that use the llvm.type.checked.load intrinsic and therefore will require resolutions for llvm.type.test in order to implement CFI checks if devirtualization was unsuccessful. <a href="#a048cde5a3dc1734d95364bb8bf08430b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf2ae6a7ede47eba36231cfe92470cfe">SummaryTypeTestAssumeUsers</a></td>
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


<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### addSummaryTypeCheckedLoadUser() {#a9237d4ff2a28a78a5fb6b285a776f620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{WholeProgramDevirt.cpp}::CallSiteInfo::addSummaryTypeCheckedLoadUser (<a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> * FS)</td>
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



<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="#a84d3e2451a78887146475d5f1e687b74">AllCallSitesDevirted</a> and <a href="#a048cde5a3dc1734d95364bb8bf08430b">SummaryTypeCheckedLoadUsers</a>.</p>

</div>
</div>

### addSummaryTypeTestAssumeUser() {#a6fa4ee7f2260d0bb0406261ba802d76a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{WholeProgramDevirt.cpp}::CallSiteInfo::addSummaryTypeTestAssumeUser (<a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> * FS)</td>
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



<p>Definition at line 524 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="#a84d3e2451a78887146475d5f1e687b74">AllCallSitesDevirted</a>, <a href="#a8caa5307b4dd65a69d3d7bb4be12491a">SummaryHasTypeTestAssumeUsers</a> and <a href="#adf2ae6a7ede47eba36231cfe92470cfe">SummaryTypeTestAssumeUsers</a>.</p>

</div>
</div>

### isExported() {#afd1a56d2f4d852e0d29acee4882cb321}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{WholeProgramDevirt.cpp}::CallSiteInfo::isExported ()</td>
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



<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="#a8caa5307b4dd65a69d3d7bb4be12491a">SummaryHasTypeTestAssumeUsers</a> and <a href="#a048cde5a3dc1734d95364bb8bf08430b">SummaryTypeCheckedLoadUsers</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#ae1cb89e56d053bfe29124d830ef0ac94">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryUniformRetValOpt</a> and <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a4dc69b6c381a3b54539a9eff3e7d1d3f">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryUniqueRetValOpt</a>.</p>

</div>
</div>

### markDevirt() {#af92dbd7f8b58ee509f6d50304aadf83b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{WholeProgramDevirt.cpp}::CallSiteInfo::markDevirt ()</td>
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



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="#a84d3e2451a78887146475d5f1e687b74">AllCallSitesDevirted</a> and <a href="#a048cde5a3dc1734d95364bb8bf08430b">SummaryTypeCheckedLoadUsers</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a1ccdbdd6f0c159f0233236dca7125328">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyUniformRetValOpt</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a4f6dd5dcbaeca0d82159a5094b742672">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyUniqueRetValOpt</a> and <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a22eb17ec5325526a386b40274ca84b63">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyVirtualConstProp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AllCallSitesDevirted {#a84d3e2451a78887146475d5f1e687b74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{WholeProgramDevirt.cpp}::CallSiteInfo::AllCallSitesDevirted = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether all call sites represented by this <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/callsiteinfo">CallSiteInfo</a>, including those in summaries, have been devirtualized.</p>


<p>This starts off as true because a default constructed <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/callsiteinfo">CallSiteInfo</a> represents no call sites.</p>


<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#a9237d4ff2a28a78a5fb6b285a776f620">addSummaryTypeCheckedLoadUser</a>, <a href="#a6fa4ee7f2260d0bb0406261ba802d76a">addSummaryTypeTestAssumeUser</a>, <a href="#af92dbd7f8b58ee509f6d50304aadf83b">markDevirt</a> and <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#ad722656aa63d87c356ec659228865f65">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryICallBranchFunnel</a>.</p>

</div>
</div>

### CallSites {#a4c34f9725a50f48351c04484e7c151e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;VirtualCallSite&gt; anonymous{WholeProgramDevirt.cpp}::CallSiteInfo::CallSites</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of call sites for this slot.</p>


<p>Used during regular LTO and the import phase of ThinLTO (as well as the export phase of ThinLTO for any call sites that appear in the merged module itself); in each of these cases we are directly operating on the call sites at the IR level.</p>


<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a1ccdbdd6f0c159f0233236dca7125328">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyUniformRetValOpt</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a4f6dd5dcbaeca0d82159a5094b742672">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyUniqueRetValOpt</a> and <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a22eb17ec5325526a386b40274ca84b63">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyVirtualConstProp</a>.</p>

</div>
</div>

### SummaryHasTypeTestAssumeUsers {#a8caa5307b4dd65a69d3d7bb4be12491a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{WholeProgramDevirt.cpp}::CallSiteInfo::SummaryHasTypeTestAssumeUsers = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether any function summary contains an llvm.assume(llvm.type.test) for this slot.</p>

<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#a6fa4ee7f2260d0bb0406261ba802d76a">addSummaryTypeTestAssumeUser</a> and <a href="#afd1a56d2f4d852e0d29acee4882cb321">isExported</a>.</p>

</div>
</div>

### SummaryTypeCheckedLoadUsers {#a048cde5a3dc1734d95364bb8bf08430b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;FunctionSummary *&gt; anonymous{WholeProgramDevirt.cpp}::CallSiteInfo::SummaryTypeCheckedLoadUsers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CFI-specific: a vector containing the list of function summaries that use the llvm.type.checked.load intrinsic and therefore will require resolutions for llvm.type.test in order to implement CFI checks if devirtualization was unsuccessful.</p>


<p>If devirtualization was successful, the pass will clear this vector by calling <a href="#af92dbd7f8b58ee509f6d50304aadf83b">markDevirt()</a>. If at the end of the pass the vector is non-empty, we will need to add a use of llvm.type.test to each of the function summaries in the vector.</p>


<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#a9237d4ff2a28a78a5fb6b285a776f620">addSummaryTypeCheckedLoadUser</a>, <a href="#afd1a56d2f4d852e0d29acee4882cb321">isExported</a> and <a href="#af92dbd7f8b58ee509f6d50304aadf83b">markDevirt</a>.</p>

</div>
</div>

### SummaryTypeTestAssumeUsers {#adf2ae6a7ede47eba36231cfe92470cfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;FunctionSummary *&gt; anonymous{WholeProgramDevirt.cpp}::CallSiteInfo::SummaryTypeTestAssumeUsers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#a6fa4ee7f2260d0bb0406261ba802d76a">addSummaryTypeTestAssumeUser</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
