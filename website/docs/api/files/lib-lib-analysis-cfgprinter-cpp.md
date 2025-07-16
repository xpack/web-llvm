---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/cfgprinter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `CFGPrinter.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfgprinter-h">llvm/Analysis/CFGPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/postorderiterator-h">llvm/ADT/PostOrderIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/graphwriter-h">llvm/Support/GraphWriter.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55448ee1f718ab6806a3c309f5ffccf2">writeCFGToDotFile</a> (Function &amp;F, BlockFrequencyInfo *BFI, BranchProbabilityInfo *BPI, uint64_t MaxFreq, bool CFGOnly=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5c6ea41f33d13cfc1cf8546c1a3ad60">viewCFG</a> (Function &amp;F, const BlockFrequencyInfo *BFI, const BranchProbabilityInfo *BPI, uint64_t MaxFreq, bool CFGOnly=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af39e0fda9ba4a4f0c817817e2c540b66">CFGFuncName</a>("cfg-func-name", cl::Hidden, cl::desc("The name of a function (or its substring)" " whose CFG is viewed/printed."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97d2e17087e84421a461e8a0ecf72cbf">CFGDotFilenamePrefix</a>("cfg-dot-filename-prefix", cl::Hidden, cl::desc("The prefix used for the CFG dot file names."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51063830a9f8bbf8b98f952fa7568fbb">HideUnreachablePaths</a>("cfg-hide-unreachable-paths", cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3ba3c3431e0a5cf442089a2622eb000">HideDeoptimizePaths</a>("cfg-hide-deoptimize-paths", cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad942ccc86bdfad94eb97f07a822028b5">HideColdPaths</a>("cfg-hide-cold-paths", cl::init(0.0), cl::desc("Hide blocks with relative frequency below the given value"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90ea5a5ba0d6826427b8146da341e256">ShowHeatColors</a>("cfg-heat-colors", cl::init(true), cl::Hidden, cl::desc("Show heat colors in CFG"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32602126342fcc016a7d8805adda2c1e">UseRawEdgeWeight</a>("cfg-raw-weights", cl::init(false), cl::Hidden, cl::desc("Use raw weights for labels. " "Use percentages as default."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af45bc203fa52af649ec1b99f237db822">ShowEdgeWeight</a>("cfg-weights", cl::init(false), cl::Hidden, cl::desc("Show edges labeled with weights"))</td>
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

### viewCFG() {#ad5c6ea41f33d13cfc1cf8546c1a3ad60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void viewCFG (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> * BPI, uint64_t MaxFreq, bool CFGOnly=false)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/cfgprinter-cpp">CFGPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecfgprinter-cpp/#af50584ae7dcdfb215af187e3e0ea8680">CFGOnly</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/dotfuncinfo/#a2a757729325ef944bc08880a87b42356">llvm::DOTFuncInfo::setEdgeWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/dotfuncinfo/#af503c0a790086f6341688e47638e04c1">llvm::DOTFuncInfo::setHeatColors</a>, <a href="/web-llvm/docs/api/classes/llvm/dotfuncinfo/#a18dc9beb2545dc39e8212b759f131dd4">llvm::DOTFuncInfo::setRawEdgeWeights</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp/#a44a2eac0197ea7e080d7ce088a5c3442">ShowEdgeWeight</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp/#a0518c4e7c33860ca41c619ec9efd8f67">ShowHeatColors</a>, <a href="#a32602126342fcc016a7d8805adda2c1e">UseRawEdgeWeight</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab8635363d4287c93f64c55ad5567fcf0">llvm::ViewGraph</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cfgonlyviewerpass/#a2c9830e7108892805b14bca50f644d0c">llvm::CFGOnlyViewerPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/cfgviewerpass/#a4ec76f0493f0ee9679e2a15343680ccf">llvm::CFGViewerPass::run</a>.</p>

</div>
</div>

### writeCFGToDotFile() {#a55448ee1f718ab6806a3c309f5ffccf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeCFGToDotFile (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> * BPI, uint64_t MaxFreq, bool CFGOnly=false)</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/cfgprinter-cpp">CFGPrinter.cpp</a>.</p>


<p>References <a href="#a97d2e17087e84421a461e8a0ecf72cbf">CFGDotFilenamePrefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecfgprinter-cpp/#af50584ae7dcdfb215af187e3e0ea8680">CFGOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a6118bd1b7164f1f8f02470a5cb6a538b">llvm::sys::fs::OF_Text</a>, <a href="/web-llvm/docs/api/classes/llvm/dotfuncinfo/#a2a757729325ef944bc08880a87b42356">llvm::DOTFuncInfo::setEdgeWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/dotfuncinfo/#af503c0a790086f6341688e47638e04c1">llvm::DOTFuncInfo::setHeatColors</a>, <a href="/web-llvm/docs/api/classes/llvm/dotfuncinfo/#a18dc9beb2545dc39e8212b759f131dd4">llvm::DOTFuncInfo::setRawEdgeWeights</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp/#a44a2eac0197ea7e080d7ce088a5c3442">ShowEdgeWeight</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp/#a0518c4e7c33860ca41c619ec9efd8f67">ShowHeatColors</a>, <a href="#a32602126342fcc016a7d8805adda2c1e">UseRawEdgeWeight</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a45fc498e695e5b2061ab5e6ec8e604a1">llvm::WriteGraph</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cfgonlyprinterpass/#af4633166ee31522ede36144c2cadde39">llvm::CFGOnlyPrinterPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/cfgprinterpass/#a4d6be8adf1d7c561f9a47831f910fd91">llvm::CFGPrinterPass::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### CFGDotFilenamePrefix {#a97d2e17087e84421a461e8a0ecf72cbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; CFGDotFilenamePrefix("cfg-dot-filename-prefix", cl::Hidden, cl::desc("The prefix used for the CFG dot file names."))</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/cfgprinter-cpp">CFGPrinter.cpp</a>.</p>


<p>Referenced by <a href="#a55448ee1f718ab6806a3c309f5ffccf2">writeCFGToDotFile</a>.</p>

</div>
</div>

### CFGFuncName {#af39e0fda9ba4a4f0c817817e2c540b66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; CFGFuncName("cfg-func-name", cl::Hidden, cl::desc("The name of a function (or its substring)" " whose CFG is viewed/printed."))</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/cfgprinter-cpp">CFGPrinter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cfgonlyprinterpass/#af4633166ee31522ede36144c2cadde39">llvm::CFGOnlyPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cfgonlyviewerpass/#a2c9830e7108892805b14bca50f644d0c">llvm::CFGOnlyViewerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cfgprinterpass/#a4d6be8adf1d7c561f9a47831f910fd91">llvm::CFGPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cfgviewerpass/#a4ec76f0493f0ee9679e2a15343680ccf">llvm::CFGViewerPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#aeac4ca2dcb29682747f7d637b47c8327">llvm::Function::viewCFG</a>.</p>

</div>
</div>

### HideColdPaths {#ad942ccc86bdfad94eb97f07a822028b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; double &gt; HideColdPaths("cfg-hide-cold-paths", cl::init(0.0), cl::desc("Hide blocks with relative frequency below the given value"))</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/cfgprinter-cpp">CFGPrinter.cpp</a>.</p>

</div>
</div>

### HideDeoptimizePaths {#ae3ba3c3431e0a5cf442089a2622eb000}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; HideDeoptimizePaths("cfg-hide-deoptimize-paths", cl::init(false))</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/cfgprinter-cpp">CFGPrinter.cpp</a>.</p>

</div>
</div>

### HideUnreachablePaths {#a51063830a9f8bbf8b98f952fa7568fbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; HideUnreachablePaths("cfg-hide-unreachable-paths", cl::init(false))</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/cfgprinter-cpp">CFGPrinter.cpp</a>.</p>

</div>
</div>

### ShowEdgeWeight {#af45bc203fa52af649ec1b99f237db822}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ShowEdgeWeight("cfg-weights", cl::init(false), cl::Hidden, cl::desc("Show edges labeled with weights"))</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/cfgprinter-cpp">CFGPrinter.cpp</a>.</p>

</div>
</div>

### ShowHeatColors {#a90ea5a5ba0d6826427b8146da341e256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ShowHeatColors("cfg-heat-colors", cl::init(true), cl::Hidden, cl::desc("Show heat colors in CFG"))</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/cfgprinter-cpp">CFGPrinter.cpp</a>.</p>

</div>
</div>

### UseRawEdgeWeight {#a32602126342fcc016a7d8805adda2c1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UseRawEdgeWeight("cfg-raw-weights", cl::init(false), cl::Hidden, cl::desc("Use raw weights for labels. " "Use percentages as default."))</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/cfgprinter-cpp">CFGPrinter.cpp</a>.</p>


<p>Referenced by <a href="#ad5c6ea41f33d13cfc1cf8546c1a3ad60">viewCFG</a> and <a href="#a55448ee1f718ab6806a3c309f5ffccf2">writeCFGToDotFile</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
