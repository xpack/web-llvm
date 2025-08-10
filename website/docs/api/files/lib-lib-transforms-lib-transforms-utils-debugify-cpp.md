---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `Debugify.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">llvm/Transforms/Utils/Debugify.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">llvm/ADT/BitVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">llvm/IR/DIBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">llvm/IR/DebugInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/institerator-h">llvm/IR/InstIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">llvm/IR/PassInstrumentation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">llvm/Support/JSON.h</a>"
#include &lt;optional&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-debugify-cpp-">anonymous{Debugify.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/debugifymodulepass">DebugifyModulePass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ModulePass for attaching synthetic debug info to everything, used with the legacy module pass manager. <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/debugifymodulepass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/debugifyfunctionpass">DebugifyFunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FunctionPass for attaching synthetic debug info to instructions within a single function, used with the legacy module pass manager. <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/debugifyfunctionpass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/checkdebugifymodulepass">CheckDebugifyModulePass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ModulePass for checking debug info inserted by -debugify, used with the legacy module pass manager. <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/checkdebugifymodulepass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/checkdebugifyfunctionpass">CheckDebugifyFunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FunctionPass for checking debug info inserted by -debugify-function, used with the legacy module pass manager. <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/checkdebugifyfunctionpass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66d4f6a60a7224a7e828e9c2cfc549d6">applyDebugify</a> (Function &amp;F, enum DebugifyMode Mode=DebugifyMode::SyntheticDebugInfo, DebugInfoPerPass *DebugInfoBeforePass=nullptr, StringRef NameOfWrappedPass="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbd6553c180df1ec067adf91c8cbc0da">applyDebugify</a> (Module &amp;M, enum DebugifyMode Mode=DebugifyMode::SyntheticDebugInfo, DebugInfoPerPass *DebugInfoBeforePass=nullptr, StringRef NameOfWrappedPass="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac398fa604fb57503d55fd556af91e41a">checkFunctions</a> (const DebugFnMap &amp;DIFunctionsBefore, const DebugFnMap &amp;DIFunctionsAfter, StringRef NameOfWrappedPass, StringRef FileNameFromCU, bool ShouldWriteIntoJSON, llvm::json::Array &amp;Bugs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af718a7db460e96f14b7c380d841cbcd8">checkInstructions</a> (const DebugInstMap &amp;DILocsBefore, const DebugInstMap &amp;DILocsAfter, const WeakInstValueMap &amp;InstToDelete, StringRef NameOfWrappedPass, StringRef FileNameFromCU, bool ShouldWriteIntoJSON, llvm::json::Array &amp;Bugs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae340f07c3f677f4518e4884b9043f5d8">checkVars</a> (const DebugVarMap &amp;DIVarsBefore, const DebugVarMap &amp;DIVarsAfter, StringRef NameOfWrappedPass, StringRef FileNameFromCU, bool ShouldWriteIntoJSON, llvm::json::Array &amp;Bugs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eb4d536e570cc08e82d91095b892ed2">writeJSON</a> (StringRef OrigDIVerifyBugsReportFilePath, StringRef FileNameFromCU, StringRef NameOfWrappedPass, llvm::json::Array &amp;Bugs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/modulepass">ModulePass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a114e4ad69f47e306f9c3887e94cd9b6f">createDebugifyModulePass</a> (enum DebugifyMode Mode, llvm::StringRef NameOfWrappedPass, DebugInfoPerPass *DebugInfoBeforePass)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c19c6c7952fb3fa9c2a19ed03a3d8af">createDebugifyFunctionPass</a> (enum DebugifyMode Mode, llvm::StringRef NameOfWrappedPass, DebugInfoPerPass *DebugInfoBeforePass)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/modulepass">ModulePass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cc2e17f81e4b3566d6ec738edbaa925">createCheckDebugifyModulePass</a> (bool Strip, StringRef NameOfWrappedPass, DebugifyStatsMap *StatsMap, enum DebugifyMode Mode, DebugInfoPerPass *DebugInfoBeforePass, StringRef OrigDIVerifyBugsReportFilePath)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade9c62d25f5d23d1273b4ad016c47d3c">createCheckDebugifyFunctionPass</a> (bool Strip, StringRef NameOfWrappedPass, DebugifyStatsMap *StatsMap, enum DebugifyMode Mode, DebugInfoPerPass *DebugInfoBeforePass, StringRef OrigDIVerifyBugsReportFilePath)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a231878fa1de6982e31d9e18283e70878">isIgnoredPass</a> (StringRef PassID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/registerpass">RegisterPass</a>&lt; DebugifyModulePass &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbb93ba85eff4d25fd4c3919fddd779c">DM</a>("debugify", "Attach debug info to everything")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/registerpass">RegisterPass</a>&lt; CheckDebugifyModulePass &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02386518d5de1a3c6e9431acbf912c5d">CDM</a>("check-debugify", "Check debug info from -debugify")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/registerpass">RegisterPass</a>&lt; DebugifyFunctionPass &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>("debugify-function", "Attach debug info to a function")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/registerpass">RegisterPass</a>&lt; CheckDebugifyFunctionPass &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3b958383e7c6b0df0ca98858b88c330">CDF</a>("check-debugify-function", "Check debug info from -debugify-function")</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"debugify"</td>
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

### applyDebugify() {#a66d4f6a60a7224a7e828e9c2cfc549d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool applyDebugify (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, enum <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a050aa76ace891cf5971722766fe14b1b">DebugifyMode</a> Mode=<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a050aa76ace891cf5971722766fe14b1ba190149ba9d0bdf2c7ceac37a3128952b">DebugifyMode::SyntheticDebugInfo</a>, <a href="/web-llvm/docs/api/structs/debuginfoperpass">DebugInfoPerPass</a> * DebugInfoBeforePass=nullptr, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> NameOfWrappedPass="")</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a27c57b81140fb6e76287d86c509023e7">llvm::applyDebugifyMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e556eb90cea56b01be517fbf549fd84">llvm::collectDebugInfoMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a050aa76ace891cf5971722766fe14b1ba190149ba9d0bdf2c7ceac37a3128952b">SyntheticDebugInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/debugifyeachinstrumentation/#ac08162972dd07f89c515c12aa05aa279">llvm::DebugifyEachInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/debugifyfunctionpass/#a44fd87d200d3186c3e7c299dbba4952d">anonymous{Debugify.cpp}::DebugifyFunctionPass::runOnFunction</a> and <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/debugifymodulepass/#af90af32a2be5cf81cd34b32a1f61c4b3">anonymous{Debugify.cpp}::DebugifyModulePass::runOnModule</a>.</p>

</div>
</div>

### applyDebugify() {#adbd6553c180df1ec067adf91c8cbc0da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool applyDebugify (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, enum <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a050aa76ace891cf5971722766fe14b1b">DebugifyMode</a> Mode=<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a050aa76ace891cf5971722766fe14b1ba190149ba9d0bdf2c7ceac37a3128952b">DebugifyMode::SyntheticDebugInfo</a>, <a href="/web-llvm/docs/api/structs/debuginfoperpass">DebugInfoPerPass</a> * DebugInfoBeforePass=nullptr, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> NameOfWrappedPass="")</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a27c57b81140fb6e76287d86c509023e7">llvm::applyDebugifyMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e556eb90cea56b01be517fbf549fd84">llvm::collectDebugInfoMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a050aa76ace891cf5971722766fe14b1ba190149ba9d0bdf2c7ceac37a3128952b">SyntheticDebugInfo</a>.</p>

</div>
</div>

### checkFunctions() {#ac398fa604fb57503d55fd556af91e41a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool checkFunctions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a4b96511d25a6961a44edfbfbf7868ba4">DebugFnMap</a> &amp; DIFunctionsBefore, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a4b96511d25a6961a44edfbfbf7868ba4">DebugFnMap</a> &amp; DIFunctionsAfter, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> NameOfWrappedPass, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileNameFromCU, bool ShouldWriteIntoJSON, <a href="/web-llvm/docs/api/classes/llvm/json/array">llvm::json::Array</a> &amp; Bugs)</td>
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



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-debugify-cpp-/#a3ff8e589a3e97b6b7900e3594c0f89be">anonymous{Debugify.cpp}::dbg</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a0881334358ff6ff7ff8cea5562c7988e">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a6b0c3e15c351ba9682837c29b0a141b6">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::find</a> and <a href="/web-llvm/docs/api/classes/llvm/json/array/#ad48bca6da17d659a87749a8bf543e35b">llvm::json::Array::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6b1daaa72630852c5b859e1410e69a55">llvm::checkDebugInfoMetadata</a>.</p>

</div>
</div>

### checkInstructions() {#af718a7db460e96f14b7c380d841cbcd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool checkInstructions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a73236f7f4b807ff6fbbb80d8783beb91">DebugInstMap</a> &amp; DILocsBefore, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a73236f7f4b807ff6fbbb80d8783beb91">DebugInstMap</a> &amp; DILocsAfter, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a837564d2ec7dc9b49a534242135e1997">WeakInstValueMap</a> &amp; InstToDelete, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> NameOfWrappedPass, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileNameFromCU, bool ShouldWriteIntoJSON, <a href="/web-llvm/docs/api/classes/llvm/json/array">llvm::json::Array</a> &amp; Bugs)</td>
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



<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-debugify-cpp-/#a3ff8e589a3e97b6b7900e3594c0f89be">anonymous{Debugify.cpp}::dbg</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a0881334358ff6ff7ff8cea5562c7988e">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a6b0c3e15c351ba9682837c29b0a141b6">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9affd129d19aae669647eb0d1c91f793">llvm::Instruction::getOpcodeName</a> and <a href="/web-llvm/docs/api/classes/llvm/json/array/#ad48bca6da17d659a87749a8bf543e35b">llvm::json::Array::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6b1daaa72630852c5b859e1410e69a55">llvm::checkDebugInfoMetadata</a>.</p>

</div>
</div>

### checkVars() {#ae340f07c3f677f4518e4884b9043f5d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool checkVars (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a88f4c7f22c84b7c35e08b9a633ce258d">DebugVarMap</a> &amp; DIVarsBefore, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a88f4c7f22c84b7c35e08b9a633ce258d">DebugVarMap</a> &amp; DIVarsAfter, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> NameOfWrappedPass, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileNameFromCU, bool ShouldWriteIntoJSON, <a href="/web-llvm/docs/api/classes/llvm/json/array">llvm::json::Array</a> &amp; Bugs)</td>
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



<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-debugify-cpp-/#a3ff8e589a3e97b6b7900e3594c0f89be">anonymous{Debugify.cpp}::dbg</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a0881334358ff6ff7ff8cea5562c7988e">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a6b0c3e15c351ba9682837c29b0a141b6">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::find</a> and <a href="/web-llvm/docs/api/classes/llvm/json/array/#ad48bca6da17d659a87749a8bf543e35b">llvm::json::Array::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6b1daaa72630852c5b859e1410e69a55">llvm::checkDebugInfoMetadata</a>.</p>

</div>
</div>

### createCheckDebugifyFunctionPass() {#ade9c62d25f5d23d1273b4ad016c47d3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * createCheckDebugifyFunctionPass (bool Strip, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> NameOfWrappedPass, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a71d63972eed599c71843cc4fe51df0e4">DebugifyStatsMap</a> * StatsMap, enum <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a050aa76ace891cf5971722766fe14b1b">DebugifyMode</a> Mode, <a href="/web-llvm/docs/api/structs/debuginfoperpass">DebugInfoPerPass</a> * DebugInfoBeforePass, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> OrigDIVerifyBugsReportFilePath)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1026 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/checkdebugifyfunctionpass/#a12c6f1b4a473dba4a357c2ecff32307d">anonymous{Debugify.cpp}::CheckDebugifyFunctionPass::CheckDebugifyFunctionPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a050aa76ace891cf5971722766fe14b1ba991e1027ad91114d5c5c28b14ca36637">OriginalDebugInfo</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a050aa76ace891cf5971722766fe14b1ba190149ba9d0bdf2c7ceac37a3128952b">SyntheticDebugInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/debugifycustompassmanager/#a3fcb5818d26eaf75c2b5a96903fd7cf4">llvm::DebugifyCustomPassManager::add</a>.</p>

</div>
</div>

### createCheckDebugifyModulePass() {#a8cc2e17f81e4b3566d6ec738edbaa925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModulePass * createCheckDebugifyModulePass (bool Strip, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> NameOfWrappedPass, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a71d63972eed599c71843cc4fe51df0e4">DebugifyStatsMap</a> * StatsMap, enum <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a050aa76ace891cf5971722766fe14b1b">DebugifyMode</a> Mode, <a href="/web-llvm/docs/api/structs/debuginfoperpass">DebugInfoPerPass</a> * DebugInfoBeforePass, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> OrigDIVerifyBugsReportFilePath)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1014 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/checkdebugifymodulepass/#abb2ac946e56f8a7d15204bb6abb6697a">anonymous{Debugify.cpp}::CheckDebugifyModulePass::CheckDebugifyModulePass</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a050aa76ace891cf5971722766fe14b1ba991e1027ad91114d5c5c28b14ca36637">OriginalDebugInfo</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a050aa76ace891cf5971722766fe14b1ba190149ba9d0bdf2c7ceac37a3128952b">SyntheticDebugInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/debugifycustompassmanager/#a3fcb5818d26eaf75c2b5a96903fd7cf4">llvm::DebugifyCustomPassManager::add</a>.</p>

</div>
</div>

### createDebugifyFunctionPass() {#a1c19c6c7952fb3fa9c2a19ed03a3d8af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * createDebugifyFunctionPass (enum <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a050aa76ace891cf5971722766fe14b1b">DebugifyMode</a> Mode, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> NameOfWrappedPass, <a href="/web-llvm/docs/api/structs/debuginfoperpass">DebugInfoPerPass</a> * DebugInfoBeforePass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 991 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/debugifyfunctionpass/#a0558468ab0facd9987e1b51dd9f6920b">anonymous{Debugify.cpp}::DebugifyFunctionPass::DebugifyFunctionPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a050aa76ace891cf5971722766fe14b1ba991e1027ad91114d5c5c28b14ca36637">OriginalDebugInfo</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a050aa76ace891cf5971722766fe14b1ba190149ba9d0bdf2c7ceac37a3128952b">SyntheticDebugInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/debugifycustompassmanager/#a3fcb5818d26eaf75c2b5a96903fd7cf4">llvm::DebugifyCustomPassManager::add</a>.</p>

</div>
</div>

### createDebugifyModulePass() {#a114e4ad69f47e306f9c3887e94cd9b6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModulePass * createDebugifyModulePass (enum <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a050aa76ace891cf5971722766fe14b1b">DebugifyMode</a> Mode, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> NameOfWrappedPass, <a href="/web-llvm/docs/api/structs/debuginfoperpass">DebugInfoPerPass</a> * DebugInfoBeforePass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 981 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-debugify-cpp-/debugifymodulepass/#a276d108dd34a0b135ec4d6e9de798f31">anonymous{Debugify.cpp}::DebugifyModulePass::DebugifyModulePass</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a050aa76ace891cf5971722766fe14b1ba991e1027ad91114d5c5c28b14ca36637">OriginalDebugInfo</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a050aa76ace891cf5971722766fe14b1ba190149ba9d0bdf2c7ceac37a3128952b">SyntheticDebugInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/debugifycustompassmanager/#a3fcb5818d26eaf75c2b5a96903fd7cf4">llvm::DebugifyCustomPassManager::add</a>.</p>

</div>
</div>

### isIgnoredPass() {#a231878fa1de6982e31d9e18283e70878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isIgnoredPass (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassID)</td>
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



<p>Definition at line 1052 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a88d6a2d221777b8376bde5d860a219d1">llvm::isSpecialPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/debugifyeachinstrumentation/#ac08162972dd07f89c515c12aa05aa279">llvm::DebugifyEachInstrumentation::registerCallbacks</a>.</p>

</div>
</div>

### writeJSON() {#a8eb4d536e570cc08e82d91095b892ed2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeJSON (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> OrigDIVerifyBugsReportFilePath, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileNameFromCU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> NameOfWrappedPass, <a href="/web-llvm/docs/api/classes/llvm/json/array">llvm::json::Array</a> &amp; Bugs)</td>
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



<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a293545f9b5864a8e1b33e57becbc5b3a">llvm::raw_fd_ostream::close</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a5a33d325e887c5cfa94e8abac79145b3">llvm::raw_fd_ostream::lock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695ac999fafdcc991e61bbc2df56a4310083">llvm::sys::fs::OF_Append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695ab505c2c79499fbe180989bffbf108a50">llvm::sys::fs::OF_TextWithCRLF</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6b1daaa72630852c5b859e1410e69a55">llvm::checkDebugInfoMetadata</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### CDF {#ad3b958383e7c6b0df0ca98858b88c330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterPass&lt; CheckDebugifyFunctionPass &gt; CDF("check-debugify-function", "Check debug info from -debugify-function")</td>
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



<p>Definition at line 1128 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>

</div>
</div>

### CDM {#a02386518d5de1a3c6e9431acbf912c5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterPass&lt; CheckDebugifyModulePass &gt; CDM("check-debugify", "Check debug info from -debugify")</td>
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



<p>Definition at line 1120 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>

</div>
</div>

### DF {#a9e8fa29f7cb6a03aa586afae7591f6cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterPass&lt; DebugifyFunctionPass &gt; DF("debugify-function", "Attach debug info to a function")</td>
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



<p>Definition at line 1123 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/cfgdeadness/#a9b52ca5c1374c43bc1800b838514562a">anonymous{SafepointIRVerifier.cpp}::CFGDeadness::addDeadBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvinsertvsetvli-cpp-/demandedfields/#a5b25eee520411a343380b9f847efea96">anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields::all</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp/#a3372eaf7daf5cd4032acb451ab70acdc">AttemptToFoldSymbolOffsetDifference</a>, <a href="/web-llvm/docs/api/classes/llvm/regionbase/#a0b14400bd55c60e1954249c86edabfd3">llvm::RegionBase&lt; RegionTraits&lt; MachineFunction &gt; &gt;::clearNodeCache</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation/#ae79e1d26012dca43293dea8a19fc002b">llvm::DILocation::cloneByMultiplyingDuplicationFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a839785a42c232b11d0e1b6b6c0ddba69">llvm::DILocation::cloneWithBaseDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a71afd3d2ac28f17a123c7a5e37822659">llvm::DILocation::decodeDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a872194924baf250829ba1b42a0b14105">llvm::DWARFContext::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#a73af1340aaefb3f64c1e4000ce6254e4">llvm::MCFragment::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a66d51c3585e4733b99bb8d3e3eb2bb81">llvm::MCObjectStreamer::emitBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a1b7e117c34782423f4cab2396b42b059">llvm::MCWinCOFFStreamer::emitCOFFImgRel32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#ab111e0970f34dbb0c62ace14e515819c">llvm::MCWinCOFFStreamer::emitCOFFSecNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a4231cebc046e4dba7b742b6d31bd1d01">llvm::MCWinCOFFStreamer::emitCOFFSecOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a6dbbe16f1a57144b250b2b3ba1243e93">llvm::MCWinCOFFStreamer::emitCOFFSecRel32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a0cce678ce28a97e39af6a60a52daac7f">llvm::MCWinCOFFStreamer::emitCOFFSectionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a64117626e72c6d42f4c970c4a8419fad">llvm::MCObjectStreamer::emitDTPRel32Value</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#af9ffc6b71a4df398a73b14eb57013b99">llvm::MCObjectStreamer::emitDTPRel64Value</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a941d139388690bb273865a4a89eb6841">llvm::MCObjectStreamer::emitGPRel32Value</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a83a13ea025b64786cb5e900f7a97af71">llvm::MCObjectStreamer::emitGPRel64Value</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#ad00d45f3edbea563746d2aaa61931efc">llvm::MCWinCOFFStreamer::emitInstToData</a>, <a href="/web-llvm/docs/api/classes/llvm/mcxcoffstreamer/#a4dc19532d6ff14ce17e330c87e60411d">llvm::MCXCOFFStreamer::emitInstToData</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a8dfc15625ed04fb03d221eaebf38fd56">llvm::MCObjectStreamer::emitRelocDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#ae04524e366e748f2f9cd204cbb3f7805">llvm::MCObjectStreamer::emitTPRel32Value</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#adae79862b47707b93f6d3af0eec9e633">llvm::MCObjectStreamer::emitTPRel64Value</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9ef24f653b777a160537ee3e1d824663">llvm::MCObjectStreamer::emitValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcxcoffstreamer/#a74f3eb9157be6847f5bf0f9cd228ad01">llvm::MCXCOFFStreamer::emitXCOFFRefDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a6878171e0bb76ddb464e30b5bad4952f">llvm::DILocation::encodeDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#ab3a34a70fe72eeb58c98a1e76dae9af4">llvm::MCAsmBackend::evaluateTargetFixup</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a5461102b304d92530e9a6e3afcd47b30">llvm::RISCVAsmBackend::evaluateTargetFixup</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#aabc01e9899fccd76ffd3a0c7da023fb5">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::fixupNeedsRelaxationAdvanced</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430asmbackend-cpp-/msp430asmbackend/#a6f390708a8bc13276757f775e4ffdcdb">anonymous{MSP430AsmBackend.cpp}::MSP430AsmBackend::fixupNeedsRelaxationAdvanced</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmbackend/#ae536aee2760cede7e1b8532bf821759e">llvm::CSKYAsmBackend::fixupNeedsRelaxationAdvanced</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a7512181881a347126c56fe3456e74f8f">llvm::MCAsmBackend::fixupNeedsRelaxationAdvanced</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a67f770e0c7076b7fc767f1aee60edcd3">llvm::RISCVAsmBackend::fixupNeedsRelaxationAdvanced</a>, <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#afa31bee239029c3abc70cd0b480cbdfd">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDebugFrame</a>, <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a759c4a9026418f467ca84e2b0009a1f0">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getEHFrame</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectstreamer-cpp/#ac26abdfac1cfc54efe4ffa6f5ca8bd17">getOffsetAndDataFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a4b6a90d8388aab90babe76b13765ddf6">llvm::RISCVMCExpr::getPCRelHiFixup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#aeece82f0c3a3f34f46484c8857eee3ed">llvm::MCInstrInfo::InitMCInstrInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp/#a3e3ecc5f07c46d1e37b8d7cff83982e6">isRightAfterData</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a4172c40c16e915c478ab94311e76e1a8">llvm::MCAssembler::layout</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a7fd3ef6690dbde3a5840707d439b5a22">llvm::MCAssembler::layoutBundle</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#acd2336f653b2f81347c494f77d2fe1ff">anonymous{RISCVInsertVSETVLI.cpp}::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#abd062e69c3b1b4a76b873edc1127443a">llvm::LoongArchAsmBackend::relaxDwarfCFA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a849bcec4f9b8950b6220a2db76e23b76">llvm::MCAsmBackend::relaxDwarfCFA</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a172850f33ba1afc4850ad347040d02a7">llvm::RISCVAsmBackend::relaxDwarfCFA</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a09963de4b3b90f89cf9f9b6f154af6bd">llvm::LoongArchAsmBackend::relaxDwarfLineAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a91dc95acaf63f9b174ab71e5080835c2">llvm::MCAsmBackend::relaxDwarfLineAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a056a7266fa88806c3f88ab217fac6e4e">llvm::RISCVAsmBackend::relaxDwarfLineAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/dominancefrontieranalysis/#a4216ac958d2e020933cafd0f0b43b712">llvm::DominanceFrontierAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/regioninfoanalysis/#aeb18bff655e7a0fdfbf8143b8beec782">llvm::RegionInfoAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/regioninfopass/#a0f190fc7ae16274a25436aef02eba40c">llvm::RegionInfoPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregioninfopass/#a4eb11177ec8af97bacb6cea7fd9fe9df">llvm::MachineRegionInfoPass::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a2a301492f7142fbc3744cc1c5a86f5ec">llvm::MCAssembler::writeSectionData</a>.</p>

</div>
</div>

### DM {#abbb93ba85eff4d25fd4c3919fddd779c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterPass&lt; DebugifyModulePass &gt; DM("debugify", "Attach debug info to everything")</td>
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



<p>Definition at line 1115 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#ab7c7120f48a91e5972592b16ee7fd81b">llvm::PMDataManager::add</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a0b52d2ebf631ded594b7311d1f2829e3">llvm::rdf::DataFlowGraph::build</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase/#ad34ca12f73439d9092237a6fc01fefa0">llvm::pdb::UDTLayoutBase::initializeChildren</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a8bbd98a4e85245f40c2ef2ea6f14e7c6">llvm::PPC::isXXPERMDIShuffleMask</a>, <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a5fb719fc8062d116b93091d9c9addd43">llvm::PMTopLevelManager::schedulePass</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a77bc2aad31cb4ad41441222b28c8080c">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::Select</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"debugify"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp">Debugify.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
