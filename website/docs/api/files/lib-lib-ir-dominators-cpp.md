---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/ir/dominators-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `Dominators.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "llvm/Config/llvm-config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cfg-h">llvm/IR/CFG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">llvm/PassRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">llvm/Support/GenericDomTreeConstruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2180255e12b0a1061b66fda7197a06a6">llvm::DomTreeBuilder::Calculate&lt; DomTreeBuilder::BBDomTree &gt;</a> (DomTreeBuilder::BBDomTree &amp;DT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81522f9a7315b9e828a7d30e0fb4cf85">llvm::DomTreeBuilder::CalculateWithUpdates&lt; DomTreeBuilder::BBDomTree &gt;</a> (DomTreeBuilder::BBDomTree &amp;DT, BBUpdates U)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fac961cb4c1a6abcc9833a70e0da6bf">llvm::DomTreeBuilder::Calculate&lt; DomTreeBuilder::BBPostDomTree &gt;</a> (DomTreeBuilder::BBPostDomTree &amp;DT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6070220b820e82fc8aef505435e8f1e">llvm::DomTreeBuilder::InsertEdge&lt; DomTreeBuilder::BBDomTree &gt;</a> (DomTreeBuilder::BBDomTree &amp;DT, BasicBlock *From, BasicBlock *To)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37cb26c6ab42b3bba699c4c81272edbd">llvm::DomTreeBuilder::InsertEdge&lt; DomTreeBuilder::BBPostDomTree &gt;</a> (DomTreeBuilder::BBPostDomTree &amp;DT, BasicBlock *From, BasicBlock *To)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac78e40bd018a93040a8ff4cfc22994ea">llvm::DomTreeBuilder::DeleteEdge&lt; DomTreeBuilder::BBDomTree &gt;</a> (DomTreeBuilder::BBDomTree &amp;DT, BasicBlock *From, BasicBlock *To)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ebf7df7248c9593df45b80653d8164c">llvm::DomTreeBuilder::DeleteEdge&lt; DomTreeBuilder::BBPostDomTree &gt;</a> (DomTreeBuilder::BBPostDomTree &amp;DT, BasicBlock *From, BasicBlock *To)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f672fee6d2831cd0496eb0d2ea7662">llvm::DomTreeBuilder::ApplyUpdates&lt; DomTreeBuilder::BBDomTree &gt;</a> (DomTreeBuilder::BBDomTree &amp;DT, DomTreeBuilder::BBDomTreeGraphDiff &amp;, DomTreeBuilder::BBDomTreeGraphDiff *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add34b4af126da632596f57a404e78865">llvm::DomTreeBuilder::ApplyUpdates&lt; DomTreeBuilder::BBPostDomTree &gt;</a> (DomTreeBuilder::BBPostDomTree &amp;DT, DomTreeBuilder::BBPostDomTreeGraphDiff &amp;, DomTreeBuilder::BBPostDomTreeGraphDiff *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70b7d91571e3e5ac29d7ee116efa0fc8">llvm::DomTreeBuilder::Verify&lt; DomTreeBuilder::BBDomTree &gt;</a> (const DomTreeBuilder::BBDomTree &amp;DT, DomTreeBuilder::BBDomTree::VerificationLevel VL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5a5e7c5a7587a2023cb7f86ea90dc6d">llvm::DomTreeBuilder::Verify&lt; DomTreeBuilder::BBPostDomTree &gt;</a> (const DomTreeBuilder::BBPostDomTree &amp;DT, DomTreeBuilder::BBPostDomTree::VerificationLevel VL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacda2e232718d42c97e8714b26fd40a1">INITIALIZE_PASS</a> (DominatorTreeWrapperPass, "domtree", "Dominator Tree Construction", true, true) bool DominatorTreeWrapperPass</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9de4571c837a2a127682216b762e0b6d">VerifyDomInfoX</a>("verify-dom-info", cl::location(VerifyDomInfo), cl::Hidden, cl::desc("Verify dominator info (time consuming)"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c3fbeb73e85eeba7ca8170412f863a2">ExpensiveChecksEnabled</a> = false</td>
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

### INITIALIZE\_PASS() {#aacda2e232718d42c97e8714b26fd40a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (<a href="/web-llvm/docs/api/classes/llvm/dominatortreewrapperpass">DominatorTreeWrapperPass</a>, "domtree", "Dominator Tree Construction", <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/entryexitinstrumenter-cpp/#a3985f1f39349428d17f0d2b81ebc6349">runOnFunction</a>.</p>

</div>
</div>

### llvm::DomTreeBuilder::ApplyUpdates&lt; DomTreeBuilder::BBDomTree &gt;() {#a39f672fee6d2831cd0496eb0d2ea7662}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::ApplyUpdates&lt; DomTreeBuilder::BBDomTree &gt; (<a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#ae5476cfab53290776b8a0fbe98e391f2">DomTreeBuilder::BBDomTree</a> &amp; DT, <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a1ccc446b66a8994516d52174ebdc5997">DomTreeBuilder::BBDomTreeGraphDiff</a> &amp;, <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a1ccc446b66a8994516d52174ebdc5997">DomTreeBuilder::BBDomTreeGraphDiff</a> *)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a938230b97505e69266ab1f8ac0eb5db7">llvm::DomTreeBuilder::ApplyUpdates</a>.</p>

</div>
</div>

### llvm::DomTreeBuilder::ApplyUpdates&lt; DomTreeBuilder::BBPostDomTree &gt;() {#add34b4af126da632596f57a404e78865}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::ApplyUpdates&lt; DomTreeBuilder::BBPostDomTree &gt; (<a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a8731d7b756fd9c7b437d98139bd91d5f">DomTreeBuilder::BBPostDomTree</a> &amp; DT, <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a561eb121d8b2ba449558167d79017f66">DomTreeBuilder::BBPostDomTreeGraphDiff</a> &amp;, <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a561eb121d8b2ba449558167d79017f66">DomTreeBuilder::BBPostDomTreeGraphDiff</a> *)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a938230b97505e69266ab1f8ac0eb5db7">llvm::DomTreeBuilder::ApplyUpdates</a>.</p>

</div>
</div>

### llvm::DomTreeBuilder::Calculate&lt; DomTreeBuilder::BBDomTree &gt;() {#a2180255e12b0a1061b66fda7197a06a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::Calculate&lt; DomTreeBuilder::BBDomTree &gt; (<a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#ae5476cfab53290776b8a0fbe98e391f2">DomTreeBuilder::BBDomTree</a> &amp; DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a73e198fec8305bc64938bc784a8f0d1c">llvm::DomTreeBuilder::Calculate</a>.</p>

</div>
</div>

### llvm::DomTreeBuilder::Calculate&lt; DomTreeBuilder::BBPostDomTree &gt;() {#a7fac961cb4c1a6abcc9833a70e0da6bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::Calculate&lt; DomTreeBuilder::BBPostDomTree &gt; (<a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a8731d7b756fd9c7b437d98139bd91d5f">DomTreeBuilder::BBPostDomTree</a> &amp; DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a73e198fec8305bc64938bc784a8f0d1c">llvm::DomTreeBuilder::Calculate</a>.</p>

</div>
</div>

### llvm::DomTreeBuilder::CalculateWithUpdates&lt; DomTreeBuilder::BBDomTree &gt;() {#a81522f9a7315b9e828a7d30e0fb4cf85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::CalculateWithUpdates&lt; DomTreeBuilder::BBDomTree &gt; (<a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#ae5476cfab53290776b8a0fbe98e391f2">DomTreeBuilder::BBDomTree</a> &amp; DT, BBUpdates U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a21425ba1759b3e091d72ce8333be2ff1">llvm::DomTreeBuilder::CalculateWithUpdates</a>.</p>

</div>
</div>

### llvm::DomTreeBuilder::DeleteEdge&lt; DomTreeBuilder::BBDomTree &gt;() {#ac78e40bd018a93040a8ff4cfc22994ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::DeleteEdge&lt; DomTreeBuilder::BBDomTree &gt; (<a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#ae5476cfab53290776b8a0fbe98e391f2">DomTreeBuilder::BBDomTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * From, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a70aa6f22ccb403c6b716d03783275dfd">llvm::DomTreeBuilder::DeleteEdge</a>.</p>

</div>
</div>

### llvm::DomTreeBuilder::DeleteEdge&lt; DomTreeBuilder::BBPostDomTree &gt;() {#a0ebf7df7248c9593df45b80653d8164c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::DeleteEdge&lt; DomTreeBuilder::BBPostDomTree &gt; (<a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a8731d7b756fd9c7b437d98139bd91d5f">DomTreeBuilder::BBPostDomTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * From, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a70aa6f22ccb403c6b716d03783275dfd">llvm::DomTreeBuilder::DeleteEdge</a>.</p>

</div>
</div>

### llvm::DomTreeBuilder::InsertEdge&lt; DomTreeBuilder::BBDomTree &gt;() {#ac6070220b820e82fc8aef505435e8f1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::InsertEdge&lt; DomTreeBuilder::BBDomTree &gt; (<a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#ae5476cfab53290776b8a0fbe98e391f2">DomTreeBuilder::BBDomTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * From, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#ab5e2b97e90221527d92449f4ac5159f6">llvm::DomTreeBuilder::InsertEdge</a>.</p>

</div>
</div>

### llvm::DomTreeBuilder::InsertEdge&lt; DomTreeBuilder::BBPostDomTree &gt;() {#a37cb26c6ab42b3bba699c4c81272edbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::InsertEdge&lt; DomTreeBuilder::BBPostDomTree &gt; (<a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a8731d7b756fd9c7b437d98139bd91d5f">DomTreeBuilder::BBPostDomTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * From, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#ab5e2b97e90221527d92449f4ac5159f6">llvm::DomTreeBuilder::InsertEdge</a>.</p>

</div>
</div>

### llvm::DomTreeBuilder::Verify&lt; DomTreeBuilder::BBDomTree &gt;() {#a70b7d91571e3e5ac29d7ee116efa0fc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template bool llvm::DomTreeBuilder::Verify&lt; DomTreeBuilder::BBDomTree &gt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#ae5476cfab53290776b8a0fbe98e391f2">DomTreeBuilder::BBDomTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#aad6e57a3b7c184bded15b616e790781f">DomTreeBuilder::BBDomTree::VerificationLevel</a> VL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a1348bf219185f1a9896e890ab4c2061d">llvm::DomTreeBuilder::Verify</a>.</p>

</div>
</div>

### llvm::DomTreeBuilder::Verify&lt; DomTreeBuilder::BBPostDomTree &gt;() {#ad5a5e7c5a7587a2023cb7f86ea90dc6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template bool llvm::DomTreeBuilder::Verify&lt; DomTreeBuilder::BBPostDomTree &gt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a8731d7b756fd9c7b437d98139bd91d5f">DomTreeBuilder::BBPostDomTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#aad6e57a3b7c184bded15b616e790781f">DomTreeBuilder::BBPostDomTree::VerificationLevel</a> VL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a1348bf219185f1a9896e890ab4c2061d">llvm::DomTreeBuilder::Verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ExpensiveChecksEnabled {#a6c3fbeb73e85eeba7ca8170412f863a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ExpensiveChecksEnabled = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>

</div>
</div>

### VerifyDomInfoX {#a9de4571c837a2a127682216b762e0b6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool, true &gt; VerifyDomInfoX("verify-dom-info", cl::location(VerifyDomInfo), cl::Hidden, cl::desc("Verify dominator info (time consuming)"))</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
