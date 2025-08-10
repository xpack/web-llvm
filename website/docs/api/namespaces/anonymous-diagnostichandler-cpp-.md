---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-diagnostichandler-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{DiagnosticHandler.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{DiagnosticHandler.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-diagnostichandler-cpp-/passremarksopt">PassRemarksOpt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Regular expression corresponding to the value given in one of the -pass-remarks* command line flags. <a href="/web-llvm/docs/api/structs/anonymous-diagnostichandler-cpp-/passremarksopt/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-diagnostichandler-cpp-/passremarksopt">PassRemarksOpt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5254ec65a771c21e4d495c449ad46494">PassRemarksPassedOptLoc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-diagnostichandler-cpp-/passremarksopt">PassRemarksOpt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1fc0f5b98c39b93570237b8e2647436">PassRemarksMissedOptLoc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-diagnostichandler-cpp-/passremarksopt">PassRemarksOpt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70179a1f59e6a2eb55a53eeb39ed1de9">PassRemarksAnalysisOptLoc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-diagnostichandler-cpp-/passremarksopt">PassRemarksOpt</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/parser">cl::parser</a>&lt; std::string &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5691336c128a06df078a59ffdb108a7">PassRemarks</a>("pass-remarks", cl::value_desc("pattern"), cl::desc("Enable optimization remarks from passes whose name match " "the given regular expression"), cl::Hidden, cl::location(PassRemarksPassedOptLoc), cl::ValueRequired)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-diagnostichandler-cpp-/passremarksopt">PassRemarksOpt</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/parser">cl::parser</a>&lt; std::string &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1122e37188b7f17f77cb04f8339e1580">PassRemarksMissed</a>("pass-remarks-missed", cl::value_desc("pattern"), cl::desc("Enable missed optimization remarks from passes whose name match " "the given regular expression"), cl::Hidden, cl::location(PassRemarksMissedOptLoc), cl::ValueRequired)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-diagnostichandler-cpp-/passremarksopt">PassRemarksOpt</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/parser">cl::parser</a>&lt; std::string &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa50946b40e4899bafdc1b259d760605e">PassRemarksAnalysis</a>("pass-remarks-analysis", cl::value_desc("pattern"), cl::desc("Enable optimization analysis remarks from passes whose name match " "the given regular expression"), cl::Hidden, cl::location(PassRemarksAnalysisOptLoc), cl::ValueRequired)</td>
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

## Variables

### PassRemarks {#ad5691336c128a06df078a59ffdb108a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; PassRemarksOpt, true, cl::parser&lt; std::string &gt; &gt; anonymous{DiagnosticHandler.cpp}::PassRemarks("pass-remarks", cl::value_desc("pattern"), cl::desc("Enable optimization remarks from passes whose name match " "the given regular expression"), cl::Hidden, cl::location(PassRemarksPassedOptLoc), cl::ValueRequired)</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnostichandler-cpp">DiagnosticHandler.cpp</a>.</p>

</div>
</div>

### PassRemarksAnalysis {#aa50946b40e4899bafdc1b259d760605e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; PassRemarksOpt, true, cl::parser&lt; std::string &gt; &gt; anonymous{DiagnosticHandler.cpp}::PassRemarksAnalysis("pass-remarks-analysis", cl::value_desc("pattern"), cl::desc( "Enable optimization analysis remarks from passes whose name match " "the given regular expression"), cl::Hidden, cl::location(PassRemarksAnalysisOptLoc), cl::ValueRequired)</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnostichandler-cpp">DiagnosticHandler.cpp</a>.</p>

</div>
</div>

### PassRemarksAnalysisOptLoc {#a70179a1f59e6a2eb55a53eeb39ed1de9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassRemarksOpt anonymous{DiagnosticHandler.cpp}::PassRemarksAnalysisOptLoc</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnostichandler-cpp">DiagnosticHandler.cpp</a>.</p>

</div>
</div>

### PassRemarksMissed {#a1122e37188b7f17f77cb04f8339e1580}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; PassRemarksOpt, true, cl::parser&lt; std::string &gt; &gt; anonymous{DiagnosticHandler.cpp}::PassRemarksMissed("pass-remarks-missed", cl::value_desc("pattern"), cl::desc("Enable missed optimization remarks from passes whose name match " "the given regular expression"), cl::Hidden, cl::location(PassRemarksMissedOptLoc), cl::ValueRequired)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnostichandler-cpp">DiagnosticHandler.cpp</a>.</p>

</div>
</div>

### PassRemarksMissedOptLoc {#af1fc0f5b98c39b93570237b8e2647436}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassRemarksOpt anonymous{DiagnosticHandler.cpp}::PassRemarksMissedOptLoc</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnostichandler-cpp">DiagnosticHandler.cpp</a>.</p>

</div>
</div>

### PassRemarksPassedOptLoc {#a5254ec65a771c21e4d495c449ad46494}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassRemarksOpt anonymous{DiagnosticHandler.cpp}::PassRemarksPassedOptLoc</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnostichandler-cpp">DiagnosticHandler.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/diagnostichandler-cpp">DiagnosticHandler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
