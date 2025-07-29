---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/ir/printpasses-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `PrintPasses.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/printpasses-h">llvm/IR/PrintPasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errc-h">llvm/Support/Errc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">llvm/Support/MemoryBuffer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/program-h">llvm/Support/Program.h</a>"
#include &lt;unordered_set&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ce9c255a73b4db7c769afd2f52a943b">shouldPrintBeforeOrAfterPass</a> (StringRef PassID, ArrayRef&lt; std::string &gt; PassesToPrint)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea57e0fed9b4f4177386bf11ebb66299">cleanUpTempFilesImpl</a> (ArrayRef&lt; std::string &gt; FileName, unsigned N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/list">cl::list</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d4ac5a268f2927739f4a513c26b0dd0">PrintBefore</a>("print-before", llvm::cl::desc("Print IR before specified passes"), cl::CommaSeparated, cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/list">cl::list</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4400b62cb93d394582eaaad5838d42c">PrintAfter</a>("print-after", llvm::cl::desc("Print IR after specified passes"), cl::CommaSeparated, cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4805f9533c1f51b1ebb5cdbe9ecbf1fc">PrintBeforeAll</a>("print-before-all", llvm::cl::desc("Print IR before each pass"), cl::init(false), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf4d8a1840838fea70693679ec70f326">PrintAfterAll</a>("print-after-all", llvm::cl::desc("Print IR after each pass"), cl::init(false), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae96087bf17689d6d3c5f735eec183ce6">DiffBinary</a>("print-changed-diff-path", cl::Hidden, cl::init("diff"), cl::desc("system diff used by change reporters"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a487fe82dbe285ba4ca14e97d27ec7ded">PrintModuleScope</a>("print-module-scope", cl::desc("When printing IR for print-[before|after]{-all} " "always print a module IR"), cl::init(false), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5f25dbc2e9c1a02572c14cb1770a6c1">LoopPrintFuncScope</a>("print-loop-func-scope", cl::desc("When printing IR for print-[before|after]{-all} " "for a loop pass, always print function IR"), cl::init(false), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/list">cl::list</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8abf1cf8a3eac3a0008294bc1f18c9b0">FilterPasses</a>("filter-passes", cl::value_desc("pass names"), cl::desc("Only consider IR changes for passes whose names " "match the specified value. No-op without -print-changed"), cl::CommaSeparated, cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/list">cl::list</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefd665f9b9f4e35049eaf92f5152b90e">PrintFuncsList</a>("filter-print-funcs", cl::value_desc("function names"), cl::desc("Only print IR for functions whose name " "match this for all print-[before|after][-all] " "options"), cl::CommaSeparated, cl::Hidden)</td>
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

### cleanUpTempFilesImpl() {#aea57e0fed9b4f4177386bf11ebb66299}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code cleanUpTempFilesImpl (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt; FileName, unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/printpasses-cpp">PrintPasses.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a921e0b01f22f9a37012450f9b5f0ccb7">llvm::sys::fs::remove</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a9826d594303bc76fe0df7ab9face2d1a">llvm::cleanUpTempFiles</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0fa39647aed67bc62e126a8d8812900f">llvm::prepareTempFiles</a>.</p>

</div>
</div>

### shouldPrintBeforeOrAfterPass() {#a1ce9c255a73b4db7c769afd2f52a943b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool shouldPrintBeforeOrAfterPass (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt; PassesToPrint)</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/printpasses-cpp">PrintPasses.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad9249f0a4443bb33fb0789525d29cf01">llvm::shouldPrintAfterPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad5c2fb6b85448597174b4289f8678110">llvm::shouldPrintBeforePass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DiffBinary {#ae96087bf17689d6d3c5f735eec183ce6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; DiffBinary("print-changed-diff-path", cl::Hidden, cl::init("diff"), cl::desc("system diff used by change reporters"))</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/printpasses-cpp">PrintPasses.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab3a01ed22efa91390e377a44b45087d8">llvm::doSystemDiff</a>.</p>

</div>
</div>

### FilterPasses {#a8abf1cf8a3eac3a0008294bc1f18c9b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::list&lt; std::string &gt; FilterPasses("filter-passes", cl::value_desc("pass names"), cl::desc("Only consider IR changes for passes whose names " "match the specified value. No-op without -print-changed"), cl::CommaSeparated, cl::Hidden)</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/printpasses-cpp">PrintPasses.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#add75269484ef1ec2ace63681ea027ba4">llvm::isFilterPassesEmpty</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8059a29de9752b72c252ece47fdb42b0">llvm::isPassInPrintList</a>.</p>

</div>
</div>

### LoopPrintFuncScope {#ac5f25dbc2e9c1a02572c14cb1770a6c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; LoopPrintFuncScope("print-loop-func-scope", cl::desc("When printing IR for print-[before|after]{-all} " "for a loop pass, always print function IR"), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/printpasses-cpp">PrintPasses.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#afaa66ab3cd0ce3488b412cff59d0646c">llvm::forcePrintFuncIR</a>.</p>

</div>
</div>

### PrintAfter {#aa4400b62cb93d394582eaaad5838d42c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::list&lt; std::string &gt; PrintAfter("print-after", llvm::cl::desc("Print IR after specified passes"), cl::CommaSeparated, cl::Hidden)</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/printpasses-cpp">PrintPasses.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a22184222f029503b923d35db0140d2e1">llvm::printAfterPasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad9249f0a4443bb33fb0789525d29cf01">llvm::shouldPrintAfterPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a68dbdc030a00d3b34829df7542a7c729">llvm::shouldPrintAfterSomePass</a>.</p>

</div>
</div>

### PrintAfterAll {#adf4d8a1840838fea70693679ec70f326}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PrintAfterAll("print-after-all", llvm::cl::desc("Print IR after each pass"), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/printpasses-cpp">PrintPasses.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4ec431b3fd03106c43c081d83b16b581">llvm::shouldPrintAfterAll</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad9249f0a4443bb33fb0789525d29cf01">llvm::shouldPrintAfterPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a68dbdc030a00d3b34829df7542a7c729">llvm::shouldPrintAfterSomePass</a>.</p>

</div>
</div>

### PrintBefore {#a4d4ac5a268f2927739f4a513c26b0dd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::list&lt; std::string &gt; PrintBefore("print-before", llvm::cl::desc("Print IR before specified passes"), cl::CommaSeparated, cl::Hidden)</td>
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



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/printpasses-cpp">PrintPasses.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6209f466bcee5c56b70c8eb990ce26c9">llvm::printBeforePasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad5c2fb6b85448597174b4289f8678110">llvm::shouldPrintBeforePass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a62d926ab6d3edd52777b18019184c09c">llvm::shouldPrintBeforeSomePass</a>.</p>

</div>
</div>

### PrintBeforeAll {#a4805f9533c1f51b1ebb5cdbe9ecbf1fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PrintBeforeAll("print-before-all", llvm::cl::desc("Print IR before each pass"), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/printpasses-cpp">PrintPasses.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3b7089a3389d6a6e8dc35304538bf33d">llvm::shouldPrintBeforeAll</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad5c2fb6b85448597174b4289f8678110">llvm::shouldPrintBeforePass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a62d926ab6d3edd52777b18019184c09c">llvm::shouldPrintBeforeSomePass</a>.</p>

</div>
</div>

### PrintFuncsList {#aefd665f9b9f4e35049eaf92f5152b90e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::list&lt; std::string &gt; PrintFuncsList("filter-print-funcs", cl::value_desc("function names"), cl::desc("Only print IR for functions whose name " "match this for all print-[before|after][-all] " "options"), cl::CommaSeparated, cl::Hidden)</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/printpasses-cpp">PrintPasses.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7d104c3a6510178d34b2d3f0ae67b4d5">llvm::isFunctionInPrintList</a>.</p>

</div>
</div>

### PrintModuleScope {#a487fe82dbe285ba4ca14e97d27ec7ded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PrintModuleScope("print-module-scope", cl::desc("When printing IR for print-[before|after]{-all} " "always print a module IR"), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/printpasses-cpp">PrintPasses.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a14de763ca0235935ff458accc41d94d7">llvm::forcePrintModuleIR</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
