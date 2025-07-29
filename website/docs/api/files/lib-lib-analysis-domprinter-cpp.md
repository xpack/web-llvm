---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/domprinter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `DomPrinter.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domprinter-h">llvm/Analysis/DomPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">llvm/Analysis/DOTGraphTraitsPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/postdominators-h">llvm/Analysis/PostDominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-domprinter-cpp-">anonymous{DomPrinter.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-domprinter-cpp-/legacydominatortreewrapperpassanalysisgraphtraits">LegacyDominatorTreeWrapperPassAnalysisGraphTraits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-domprinter-cpp-/domviewerwrapperpass">DomViewerWrapperPass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-domprinter-cpp-/domonlyviewerwrapperpass">DomOnlyViewerWrapperPass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-domprinter-cpp-/legacypostdominatortreewrapperpassanalysisgraphtraits">LegacyPostDominatorTreeWrapperPassAnalysisGraphTraits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-domprinter-cpp-/postdomviewerwrapperpass">PostDomViewerWrapperPass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-domprinter-cpp-/postdomonlyviewerwrapperpass">PostDomOnlyViewerWrapperPass</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">INITIALIZE_PASS(DomViewerWrapperPass, "view-dom", "View dominance tree of function", false, false) char DomOnlyViewerWrapperPass INITIALIZE_PASS(DomOnlyViewerWrapperPass, "view-dom-only", "View dominance tree of <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> (with no <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> bodies)", false, false) char PostDomViewerWrapperPass INITIALIZE_PASS(PostDomViewerWrapperPass, "view-postdom", "View postdominance tree of function", false, false) char PostDomOnlyViewerWrapperPass</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b79a001d7887becdfe0ea8df40205da">INITIALIZE_PASS</a> (PostDomOnlyViewerWrapperPass, "view-postdom-only", "View postdominance tree of function " "(with no function bodies)", false, false) namespace</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">INITIALIZE_PASS(DomPrinterWrapperPass, "dot-dom", "Print dominance tree of <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> to 'dot' file", false, false) char DomOnlyPrinterWrapperPass INITIALIZE_PASS(DomOnlyPrinterWrapperPass, "dot-dom-only", "Print dominance tree of <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> to 'dot' <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a79dce2d3eafaf25bf0df59f56caf9712">file</a> " "(with no <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> bodies)", false, false) char PostDomPrinterWrapperPass INITIALIZE_PASS(PostDomPrinterWrapperPass, "dot-postdom", "Print postdominance tree of <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> to 'dot' file", false, false) char PostDomOnlyPrinterWrapperPass</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac540d6824c49864a93ce6470cbf184da">INITIALIZE_PASS</a> (PostDomOnlyPrinterWrapperPass, "dot-postdom-only", "Print postdominance tree of function to 'dot' file " "(with no function bodies)", false, false) FunctionPass *llvm</td>
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

### INITIALIZE\_PASS() {#a9b79a001d7887becdfe0ea8df40205da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS(DomViewerWrapperPass, "view-dom", "View dominance tree of function", false, false) char DomOnlyViewerWrapperPass INITIALIZE_PASS(DomOnlyViewerWrapperPass, "view-dom-only", "View dominance tree of function (with no function bodies)", false, false) char PostDomViewerWrapperPass INITIALIZE_PASS(PostDomViewerWrapperPass, "view-postdom", "View postdominance tree of function", false, false) char PostDomOnlyViewerWrapperPass INITIALIZE_PASS (PostDomOnlyViewerWrapperPass, "view-postdom-only", "View postdominance tree of <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> " "(with no <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> bodies)", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/domprinter-cpp">DomPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aacd9124913ed7d973786242879ab7717">llvm::initializeDomOnlyPrinterWrapperPassPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2788af3d4da6b8848d4294a98131f882">llvm::initializeDomPrinterWrapperPassPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90785122eca447c7afe978a305202124">llvm::initializePostDomOnlyPrinterWrapperPassPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acf7048908b2f000581360e6b44ec44f2">llvm::initializePostDomPrinterWrapperPassPass</a>.</p>

</div>
</div>

### INITIALIZE\_PASS() {#ac540d6824c49864a93ce6470cbf184da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS(DomPrinterWrapperPass, "dot-dom", "Print dominance tree of function to 'dot' file", false, false) char DomOnlyPrinterWrapperPass INITIALIZE_PASS(DomOnlyPrinterWrapperPass, "dot-dom-only", "Print dominance tree of function to 'dot' file " "(with no function bodies)", false, false) char PostDomPrinterWrapperPass INITIALIZE_PASS(PostDomPrinterWrapperPass, "dot-postdom", "Print postdominance tree of function to 'dot' file", false, false) char PostDomOnlyPrinterWrapperPass INITIALIZE_PASS (PostDomOnlyPrinterWrapperPass, "dot-postdom-only", "Print postdominance tree of <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> to 'dot' <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a79dce2d3eafaf25bf0df59f56caf9712">file</a> " "(with no <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> bodies)", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/domprinter-cpp">DomPrinter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ae6d8e6a6d9e45f2d0a9ba52c7425dc10">llvm::createDomPrinterWrapperPassPass</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
