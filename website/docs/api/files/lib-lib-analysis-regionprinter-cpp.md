---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/regionprinter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `RegionPrinter.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionprinter-h">llvm/Analysis/RegionPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">llvm/Analysis/DOTGraphTraitsPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">llvm/Analysis/RegionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioniterator-h">llvm/Analysis/RegionIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">llvm/IR/LegacyPassManager.h</a>"
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-regionprinter-cpp-">anonymous{RegionPrinter.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-e5b50eb34ec0db639bdb467f977dace6">DOTGraphTraits&lt;RegionInfo *&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-regionprinter-cpp-/regioninfopassgraphtraits">RegionInfoPassGraphTraits</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-regionprinter-cpp-/regionprinter">RegionPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-regionprinter-cpp-/regiononlyprinter">RegionOnlyPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-regionprinter-cpp-/regionviewer">RegionViewer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-regionprinter-cpp-/regiononlyviewer">RegionOnlyViewer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab805811c7a9f3dd672169b9b444f6892">INITIALIZE_PASS</a> (RegionPrinter, "dot-regions", "Print regions of function to 'dot' file", true, true) INITIALIZE_PASS(RegionOnlyPrinter</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">dot <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp/#a60d9a9654bb13ef250022d9e3ee30f11">regions</a> Print <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp/#a60d9a9654bb13ef250022d9e3ee30f11">regions</a> of <a href="#aa37fbbce2360106772fd97ed06455d55">function</a> to dot</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79dce2d3eafaf25bf0df59f56caf9712">file</a> (with no function bodies)"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">dot <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp/#a60d9a9654bb13ef250022d9e3ee30f11">regions</a> Print <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp/#a60d9a9654bb13ef250022d9e3ee30f11">regions</a> of <a href="#aa37fbbce2360106772fd97ed06455d55">function</a> to dot <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3665d0519d66c7dcd9df0f43548f560e">INITIALIZE_PASS</a> (RegionViewer, "view-regions", "View regions of function", true, true) INITIALIZE_PASS(RegionOnlyViewer</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">dot <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp/#a60d9a9654bb13ef250022d9e3ee30f11">regions</a> Print <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp/#a60d9a9654bb13ef250022d9e3ee30f11">regions</a> of function to dot <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> view <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp/#a60d9a9654bb13ef250022d9e3ee30f11">regions</a> View <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp/#a60d9a9654bb13ef250022d9e3ee30f11">regions</a> of</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa37fbbce2360106772fd97ed06455d55">function</a> (with no function bodies)"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a8fd59d2460f638c7c5818f662fcfd0">viewRegionInfo</a> (RegionInfo *RI, bool ShortNames)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5e968db4987e612699b3957b125adf4">invokeFunctionPass</a> (const Function *F, FunctionPass *ViewerPass)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e3080da2954744c200327ca1575c882">onlySimpleRegions</a>("only-simple-regions", cl::desc("Show only simple regions in the graphviz viewer"), cl::Hidden, cl::init(false))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>onlySimpleRegion - Show only the simple regions in the <a href="/web-llvm/docs/api/structs/anonymous-regionprinter-cpp-/regionviewer">RegionViewer</a>. <a href="#a8e3080da2954744c200327ca1575c882">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">dot <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp/#a60d9a9654bb13ef250022d9e3ee30f11">regions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5782a8740ff1e91516b41b3726a3168c">only</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">dot <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp/#a60d9a9654bb13ef250022d9e3ee30f11">regions</a> Print <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp/#a60d9a9654bb13ef250022d9e3ee30f11">regions</a> of <a href="#aa37fbbce2360106772fd97ed06455d55">function</a> to dot</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1bff759151fc332f9c9021578b15be6">true</a></td>
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

### file() {#a79dce2d3eafaf25bf0df59f56caf9712}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dot regions Print regions of function to dot file (with no <a href="#aa37fbbce2360106772fd97ed06455d55">function</a> bodies)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp">RegionPrinter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acdb068ea3720578d8200249da0f953ca">llvm::gcovOneInput</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8cb1f2bd469f8a823857a1cf1447a0e3">llvm::llvm_unreachable_internal</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcov-cpp-/context/#af21fe9969dd2d37f96a144b9d7376ffa">anonymous{GCOV.cpp}::Context::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a759e72612fab78b1159ab7129a7f7e86">rpmalloc_dump_statistics</a> and <a href="/web-llvm/docs/api/classes/llvm/filecollectorbase/#a0c5974b22a34ca4c8c66dc0c134e21a5">llvm::FileCollectorBase::~FileCollectorBase</a>.</p>

</div>
</div>

### function() {#aa37fbbce2360106772fd97ed06455d55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dot regions Print regions of function to dot true view regions View regions of function (with no function bodies)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp">RegionPrinter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a08b0db116677d9d685f7a07e73a914af">llvm::createCFGSimplificationPass</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/diarawsymbol/#afc40184fefae68d8c008089f04a0a0bc">llvm::pdb::DIARawSymbol::dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2sizereduction-cpp/#a12eb51750eb0905d14d6437772638c1f">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/loadstoreopt/#a24597ce933b1850a13eee882d9335fc4">llvm::LoadStoreOpt::LoadStoreOpt</a>, <a href="/web-llvm/docs/api/classes/llvm/localizer/#a6ed62833729b6206b3bb80e3349ae642">llvm::Localizer::Localizer</a> and <a href="/web-llvm/docs/api/classes/anonymous-nvptxallocahoisting-cpp-/nvptxallocahoisting/#a3e0401219219142d6d4aa7cb0859afc7">anonymous{NVPTXAllocaHoisting.cpp}::NVPTXAllocaHoisting::runOnFunction</a>.</p>

</div>
</div>

### INITIALIZE\_PASS() {#ab805811c7a9f3dd672169b9b444f6892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (RegionPrinter, "dot-regions", "Print <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp/#a60d9a9654bb13ef250022d9e3ee30f11">regions</a> of <a href="#aa37fbbce2360106772fd97ed06455d55">function</a> to 'dot' file", <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp">RegionPrinter.cpp</a>.</p>

</div>
</div>

### INITIALIZE\_PASS() {#a3665d0519d66c7dcd9df0f43548f560e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dot regions Print regions of function to dot true INITIALIZE_PASS (RegionViewer, "view-regions", "View <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp/#a60d9a9654bb13ef250022d9e3ee30f11">regions</a> of function", <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp">RegionPrinter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

### invokeFunctionPass() {#aa5e968db4987e612699b3957b125adf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void invokeFunctionPass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> * ViewerPass)</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp">RegionPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanager/#a1bec72c759c38b748ff60434eb4d0c80">llvm::legacy::FunctionPassManager::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanager/#aabcf819b6866d85a9fc8f882ff0e9ead">llvm::legacy::FunctionPassManager::doFinalization</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanager/#a7cb64dd75fa1775aeb32cde0bc17b72a">llvm::legacy::FunctionPassManager::doInitialization</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanager/#a02e592cc8ca8a049fbe052f809514c73">llvm::legacy::FunctionPassManager::run</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a2cc2e9673f85c3bb09eb56957d74000a">llvm::viewRegion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8176d5d4309951001c26d78a1ea470b9">llvm::viewRegionOnly</a>.</p>

</div>
</div>

### viewRegionInfo() {#a1a8fd59d2460f638c7c5818f662fcfd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void viewRegionInfo (<a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a> * RI, bool ShortNames)</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp">RegionPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/regioninfobase/#a5e825c7a51956c5d602ebff45036b1a9">llvm::RegionInfoBase&lt; Tr &gt;::getTopLevelRegion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab8635363d4287c93f64c55ad5567fcf0">llvm::ViewGraph</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aee30bf714c0718589fd36f05351af330">llvm::viewRegion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af3316136f9709117681e6e8ec810955f">llvm::viewRegionOnly</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### only {#a5782a8740ff1e91516b41b3726a3168c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dot regions Print regions of function to dot true view regions only</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp">RegionPrinter.cpp</a>.</p>

</div>
</div>

### onlySimpleRegions {#a8e3080da2954744c200327ca1575c882}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; onlySimpleRegions("only-simple-regions", cl::desc("Show only simple regions in the graphviz viewer"), cl::Hidden, cl::init(false))</td>
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

<p>onlySimpleRegion - Show only the simple regions in the <a href="/web-llvm/docs/api/structs/anonymous-regionprinter-cpp-/regionviewer">RegionViewer</a>.</p>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp">RegionPrinter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-e5b50eb34ec0db639bdb467f977dace6/#ab3512588955bf7f5a4c5b088979022c0">llvm::DOTGraphTraits&lt; RegionInfo * &gt;::printRegionCluster</a>.</p>

</div>
</div>

### true {#af1bff759151fc332f9c9021578b15be6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dot regions Print regions of function to dot true view regions View regions of true</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp">RegionPrinter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
