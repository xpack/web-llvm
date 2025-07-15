---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/aliasanalysis-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `AliasAnalysis.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">llvm/Analysis/AliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/basicaliasanalysis-h">llvm/Analysis/BasicAliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/capturetracking-h">llvm/Analysis/CaptureTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/globalsmodref-h">llvm/Analysis/GlobalsModRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">llvm/Analysis/MemoryLocation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionaliasanalysis-h">llvm/Analysis/ScalarEvolutionAliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scopednoaliasaa-h">llvm/Analysis/ScopedNoAliasAA.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typebasedaliasanalysis-h">llvm/Analysis/TypeBasedAliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">llvm/IR/Argument.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/atomicordering-h">llvm/Support/AtomicOrdering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include &lt;cassert&gt;
#include &lt;functional&gt;
#include &lt;iterator&gt;
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abab6aab9d76a9a0c2c6e4328c9e2a0fb">STATISTIC</a> (NumNoAlias, "Number of NoAlias results")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea8ff8ee569c62e6c452073105b9be07">STATISTIC</a> (NumMayAlias, "Number of MayAlias results")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42792d57a1a4ca4f0124813ba9fab209">STATISTIC</a> (NumMustAlias, "Number of MustAlias results")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25a0004a37408852da56ee20c37e5a26">INITIALIZE_PASS</a> (ExternalAAWrapperPass, "external-aa", "External Alias Analysis", false, true) ImmutablePass *llvm</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a387f65094ae15ae3b17f54f9fec20492">INITIALIZE_PASS_BEGIN</a> (AAResultsWrapperPass, "aa", "Function Alias Analysis Results", false, true) INITIALIZE_PASS_END(AAResultsWrapperPass</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ebd744238038b0345b9033a3831dbbe">isNoAliasOrByValArgument</a> (const Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a501e4f9f6454fd6fe52d86f7d5df05bc">EnableAATrace</a>("aa-trace", cl::Hidden, cl::init(false))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print a trace of alias analysis queries and their results. <a href="#a501e4f9f6454fd6fe52d86f7d5df05bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74b87337454200d4d33f80c4663dc5e5">aa</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Alias <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e344cff0feadf0b02223fee63cc7475">Results</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Alias <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a479b1f65525d3585f951deced4db0e36">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"aa"</td>
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

### INITIALIZE\_PASS() {#a25a0004a37408852da56ee20c37e5a26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (<a href="/web-llvm/docs/api/structs/llvm/externalaawrapperpass">ExternalAAWrapperPass</a>, "external-aa", "External Alias Analysis", false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp">AliasAnalysis.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ad0000e11ad5a4d13f48c4498fbd9d18a">llvm::createExternalAAWrapperPass</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#a387f65094ae15ae3b17f54f9fec20492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (<a href="/web-llvm/docs/api/classes/llvm/aaresultswrapperpass">AAResultsWrapperPass</a>, "aa", "Function Alias <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a> Results", false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 722 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp">AliasAnalysis.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### isNoAliasOrByValArgument() {#a6ebd744238038b0345b9033a3831dbbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isNoAliasOrByValArgument (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 807 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp">AliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abe71bc4610a9dc7aa3a6c6e0e28fc14a">llvm::isIdentifiedFunctionLocal</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aed2c5dd2a303159f87771db83f54352b">llvm::isIdentifiedObject</a>.</p>

</div>
</div>

### STATISTIC() {#abab6aab9d76a9a0c2c6e4328c9e2a0fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumNoAlias, "Number of NoAlias results")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp">AliasAnalysis.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#aea8ff8ee569c62e6c452073105b9be07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumMayAlias, "Number of MayAlias results")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp">AliasAnalysis.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a42792d57a1a4ca4f0124813ba9fab209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumMustAlias, "Number of MustAlias results")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp">AliasAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### aa {#a74b87337454200d4d33f80c4663dc5e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">aa</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 730 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp">AliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#aadd87a22e72622eccf46ce5525d1976c">llvm::SelectionDAGBuilder::init</a>, <a href="/web-llvm/docs/api/classes/provenanceanalysis/#a76191600b1c369e6eb0b9176719cc87f">ProvenanceAnalysis::setAA</a> and <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a1535a24a0c1b6049bba8cce276f8033f">llvm::VLIWPacketizerList::VLIWPacketizerList</a>.</p>

</div>
</div>

### EnableAATrace {#a501e4f9f6454fd6fe52d86f7d5df05bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableAATrace("aa-trace", cl::Hidden, cl::init(false))</td>
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

<p>Print a trace of alias analysis queries and their results.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp">AliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aaresults/#a12e37baab16d8f80dd44998ea6df7b8d">llvm::AAResults::alias</a>.</p>

</div>
</div>

### false {#a479b1f65525d3585f951deced4db0e36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">hexagon widen Hexagon Store false hexagon widen Hexagon Load false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 731 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp">AliasAnalysis.cpp</a>.</p>

</div>
</div>

### Results {#a7e344cff0feadf0b02223fee63cc7475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function Alias Analysis Results</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 731 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp">AliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a41d7c53499da41b1739015f7036cf6da">llvm::MachineIRBuilder::buildIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a84f7ac7613ff133970f83e8531085353">llvm::MachineIRBuilder::buildIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aca03795fe4ea383d28dcf4433f994485">combineVectorCompare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e263b9cd2bdbbbaf3d78a2caba5cbf5">llvm::computeSignatureVTs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5aade91cf963bd6be461be24ff3a284c">createTblForTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a01509c23581fb688a399381319f6b1a3">CustomNonLegalBITCASTResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-cpp/#a6d50362e845dcbafcf632cb5b98b240f">emitConstantSizeRepmov</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-cpp/#ac6a86b853c0a0262731e7e8b084c0980">emitConstantSizeRepstos</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#aa29ca0ef805870463b1abf3171c5cf1c">llvm::WebAssemblyAsmPrinter::emitDecls</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a36eb02ea70b6f7df1795c2df0b297f16">emitErrorAndReplaceIntrinsicResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a53402f6e918f527e92ecdc700d88c472">expandIntrinsicWChainHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adaa729f57e0b62f0dd995c6f5e3df8b7">llvm::SelectionDAG::expandMultipleResultFPLibCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a399ea332dd7c5c88085dd03e09152545">ExpandREAD_REGISTER</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo/#a494857c857bfb2ff33cc151c34c200d1">llvm::gsym::MergedFunctionsInfo::getFuncsDataExtractors</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae020054e3ff6b34b048afacab677d69b">getReadTimeStampCounter</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a45f53ca8960cf7c5bf2f1ed24f18f717">llvm::R600TargetLowering::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp/#ae3341aa2a4a16c49b2be04002018a1a6">getVectorDeinterleaveFactor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a95851c48d68c2406ef12a7cca9c65f76">initializeUniqueCases</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5804b68ebc77c8751a9cb4e066735450">llvm::isOverflowIntrinsicNoWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a2aeed55e4456de4086b3592eb92dc2e2">llvm::ARMLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#afab544245beb837bd2fd89c12e060c3f">llvm::gsym::GsymReader::lookupAll</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a25a5e94166cf78354826b46e402ebcd9">LowerINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ab6b1675dcd59de9c26f2e5c51b6a9ee3">llvm::HexagonTargetLowering::LowerOperationWrapper</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aaa6982f8a2f398fab0881b8806c3ce3f">llvm::SystemZTargetLowering::LowerOperationWrapper</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a12431703c17466d24d4bf388ce467ea3">llvm::TargetLowering::LowerOperationWrapper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1b7e327f795df40244e9d4588012967e">LowerREADCYCLECOUNTER</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a2de15b0aa7d9e5739e7ba791d7516882">llvm::AMDGPUTargetLowering::LowerSTORE</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae54e04166dc3c7f87ac2d1393dbf2c1e">llvm::AMDGPUTargetLowering::LowerUDIVREM</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aec76b73c15365e949f7322e371e6471b">llvm::AMDGPUTargetLowering::LowerUDIVREM64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/dylibreader/#a1d593efec1083a71925949203aaf6d31">llvm::MachO::DylibReader::readFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ab7f8d142b901597abdf51e5e51a5605f">ReplaceAddWithADDP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae416c990e5945aed7ccfb70d4c7a5802">ReplaceATOMIC_LOAD_128Results</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a21436394be987d0b769cacc5d0476183">ReplaceBITCAST</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a9d18c51ca04dfa5c2b56ad650ab0d7d9">replaceBoolVectorBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a32739f322e03782811f33bc367f9bc3b">ReplaceCMP_SWAP_128Results</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a9edb7bbdf708d2f51e1cab727a105fdc">ReplaceCMP_SWAP_64Results</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ad7a2ce0778f9b0a95ac96bd8e3f9de78">replaceCMP_XCHG_128Results</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a3107ed4a76b88b6513e9009057b7ad9f">ReplaceCopyFromReg_128</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a43333bc4548cbb52de14105bc979c0e0">ReplaceINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ae9668c83a73c0b3d546522e1d9860cba">replaceINTRINSIC_WO_CHAINResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a1d84356309e55a4722a2739dd3c655e4">ReplaceLoadVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a663a00cee8894f834358261a64ea7c7e">ReplaceLongIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad968ecdcaf64b24df6515220e36bdb5d">llvm::AMDGPUTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a28af47b21a8953afd3568b40acf3424d">llvm::ARMTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a088c31366c990e0e055fbe65766e8d2e">llvm::AVRTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a9db6eb2b9e8f4c06455eb169c64e79b3">llvm::HexagonTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#ac83ceb8e67e1ee6ca693e3ff1ffbac0f">llvm::LoongArchTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a73afb942bbe9f13347f351f28ac2fe2c">llvm::MipsTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a49eedef79b249eb098470debb9601eb7">llvm::PPCTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#aa52bac1dc0a8f251721e5702c4f81a50">llvm::R600TargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abb4ac2d585a18a9b8db4ac7ffa41fc06">llvm::RISCVTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a697277613cca131c099969ca5d421041">llvm::SITargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a16e6c862a36871c4f388c826ad65b07c">llvm::SparcTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#ac8d6a0440d5c72783599e258a3db9e58">llvm::SystemZTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac37905796bf7d5a2582ea8f41e98c3f0">llvm::VETargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af77fd362607d101a7080481254ee2fe3">llvm::X86TargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetlowering/#a89e28b97fe160f32871560a32a350499">llvm::XCoreTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a953988fc960bc5ff29afff3ded965e9d">ReplaceREADCYCLECOUNTER</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4be0086aa7ffce797f40ad2eefd2ec1a">ReplaceReductionResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ab60a9c518b2a79a37b4cf83ec7fdeee8">replaceVecCondBranchResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a8685d453cbabec8c0826789a79879242">replaceVPICKVE2GRResults</a>, <a href="/web-llvm/docs/api/classes/llvm/debugassignmenttrackinganalysis/#a5bb8380db596f4d29d331b41ff23eddf">llvm::DebugAssignmentTrackingAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyiseldagtodag-cpp-/webassemblydagtodagisel/#ab80c137e562add63a0b2c3afbed31be2">anonymous{WebAssemblyISelDAGToDAG.cpp}::WebAssemblyDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/structs/llvm/hvxselector/#ae4d7d58593a9d0b5337f8089ee1946f6">llvm::HvxSelector::selectShuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace31823ee67c59988aaf81127a235372">llvm::signatureFromMVTs</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a40bdb7ed86f1fdb139eb9fd73b05405a">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::splitVectorElements</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"aa"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp">AliasAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
