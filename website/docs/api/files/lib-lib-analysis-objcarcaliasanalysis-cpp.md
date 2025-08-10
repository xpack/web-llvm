---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/objcarcaliasanalysis-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `ObjCARCAliasAnalysis.cpp` File

<p>This file defines a simple ARC-aware <a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> using special knowledge of Objective C to enhance other optimization passes which rely on the Alias Analysis infrastructure. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcaliasanalysis-h">llvm/Analysis/ObjCARCAliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcanalysisutils-h">llvm/Analysis/ObjCARCAnalysisUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
</div>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"objc-arc-aa"</td>
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

<p>This file defines a simple ARC-aware <a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> using special knowledge of Objective C to enhance other optimization passes which rely on the Alias Analysis infrastructure.</p>


<p>WARNING: This file knows about certain library functions. It recognizes them by name, and hardwires knowledge of their semantics.</p>


<p>WARNING: This file knows about how certain Objective-C library functions are used. Naive LLVM IR transformations which would otherwise be behavior-preserving may break these assumptions.</p>


<p>TODO: Theoretically we could check for dependencies between objc_* calls and FMRB_OnlyAccessesArgumentPointees calls or other well-behaved calls.</p>


<p>TODO: The calls here to <a href="/web-llvm/docs/api/classes/llvm/aaresultbase">AAResultBase</a> member functions are all effectively no-ops that just return a conservative result. The original intent was to chain to another analysis for a recursive query, but this was lost in a refactor. These should instead be rephrased in terms of queries to AAQI.AAR.</p>


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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"objc-arc-aa"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/objcarcaliasanalysis-cpp">ObjCARCAliasAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
