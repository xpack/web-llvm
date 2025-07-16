---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/profilesummaryinfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ProfileSummaryInfo.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">llvm/Analysis/ProfileSummaryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">llvm/Analysis/BlockFrequencyInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/profilesummary-h">llvm/IR/ProfileSummary.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">llvm/ProfileData/ProfileCommon.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include &lt;optional&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85b6c88c975bbd4d6dd24d0841154df9">INITIALIZE_PASS</a> (ProfileSummaryInfoWrapperPass, "profile-summary-info", "Profile summary info", false, true) ProfileSummaryInfoWrapperPass</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfe52f140629541dd4c5f79cde7e2bdd">PartialProfile</a>("partial-profile", cl::Hidden, cl::init(false), cl::desc("Specify the current profile is used as a partial profile."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5e8870147e3826db4c33aea7a48c6b7">ScalePartialSampleProfileWorkingSetSize</a>("scale-partial-sample-profile-working-set-size", cl::Hidden, cl::init(true), cl::desc("If true, scale the working set size of the partial sample profile " "by the partial profile ratio to reflect the size of the program " "being compiled."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; double &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae72e8c13b78cb76851c60afc23efa9dd">PartialSampleProfileWorkingSetSizeScaleFactor</a>("partial-sample-profile-working-set-size-scale-factor", cl::Hidden, cl::init(0.008), cl::desc("The scale factor used to scale the working set size of the " "partial sample profile along with the partial profile ratio. " "This includes the factor of the profile counter per block " "and the factor to scale the working set size to use the same " "shared thresholds as PGO."))</td>
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


<div class="doxySectionDef">

## Functions

### INITIALIZE\_PASS() {#a85b6c88c975bbd4d6dd24d0841154df9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (<a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfowrapperpass">ProfileSummaryInfoWrapperPass</a>, "profile-summary-info", "Profile summary info", false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab43da862910097fb3e6b4782105eccc4">llvm::initializeProfileSummaryInfoWrapperPassPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### PartialProfile {#abfe52f140629541dd4c5f79cde7e2bdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PartialProfile("partial-profile", cl::Hidden, cl::init(false), cl::desc("Specify the current profile is used as a partial profile."))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#a9610274171a85158779e7ee6031d2376">llvm::ProfileSummaryInfo::hasPartialSampleProfile</a>.</p>

</div>
</div>

### PartialSampleProfileWorkingSetSizeScaleFactor {#ae72e8c13b78cb76851c60afc23efa9dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; double &gt; PartialSampleProfileWorkingSetSizeScaleFactor("partial-sample-profile-working-set-size-scale-factor", cl::Hidden, cl::init(0.008), cl::desc("The scale factor used to scale the working set size of the " "partial sample profile along with the partial profile ratio. " "This includes the factor of the profile counter per block " "and the factor to scale the working set size to use the same " "shared thresholds as PGO."))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>

</div>
</div>

### ScalePartialSampleProfileWorkingSetSize {#af5e8870147e3826db4c33aea7a48c6b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ScalePartialSampleProfileWorkingSetSize("scale-partial-sample-profile-working-set-size", cl::Hidden, cl::init(true), cl::desc( "If true, scale the working set size of the partial sample profile " "by the partial profile ratio to reflect the size of the program " "being compiled."))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/profilesummaryinfo-cpp">ProfileSummaryInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
