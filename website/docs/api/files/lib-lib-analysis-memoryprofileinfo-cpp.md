---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/memoryprofileinfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `MemoryProfileInfo.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">llvm/Analysis/MemoryProfileInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade3d002f2a3c1617aacaddf25e561833">addAllocTypeAttribute</a> (LLVMContext &amp;Ctx, CallBase *CI, AllocationType AllocType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cbecc17bbb64783431627bcf1f433c7">createMIBNode</a> (LLVMContext &amp;Ctx, ArrayRef&lt; uint64_t &gt; MIBCallStack, AllocationType AllocType, ArrayRef&lt; ContextTotalSize &gt; ContextSizeInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; float &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a074e496786909ea8b41285699df5084c">MemProfLifetimeAccessDensityColdThreshold</a>("memprof-lifetime-access-density-cold-threshold", cl::init(0.05), cl::Hidden, cl::desc("The threshold the lifetime access density (accesses per byte per " "lifetime sec) must be under to consider an allocation cold"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e58ba176f0b2036a0c1f33e8bca02b6">MemProfAveLifetimeColdThreshold</a>("memprof-ave-lifetime-cold-threshold", cl::init(200), cl::Hidden, cl::desc("The average lifetime (s) for an allocation to be considered " "cold"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a456eeb44ad87143664388b1ee37c6956">MemProfMinAveLifetimeAccessDensityHotThreshold</a>("memprof-min-ave-lifetime-access-density-hot-threshold", cl::init(1000), cl::Hidden, cl::desc("The minimum TotalLifetimeAccessDensity / AllocCount for an " "allocation to be considered hot"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e2723962f88e74e915f2b10f02780b8">MemProfUseHotHints</a>("memprof-use-hot-hints", cl::init(false), cl::Hidden, cl::desc("Enable use of hot hints (only supported for " "unambigously hot allocations)"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a696467f077d0e94dc6b3f171acc6be25">MemProfReportHintedSizes</a>("memprof-report-hinted-sizes", cl::init(false), cl::Hidden, cl::desc("Report total allocation sizes of hinted allocations"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"memory-profile-info"</td>
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

### addAllocTypeAttribute() {#ade3d002f2a3c1617aacaddf25e561833}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addAllocTypeAttribute (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CI, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27">AllocationType</a> AllocType)</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp">MemoryProfileInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a0f72a62efd0912aba72c6818c720023c">llvm::CallBase::addFnAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#aafd414cdb5967be7eccd7a6f0d1ca76e">llvm::memprof::getAllocTypeAttributeString</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memprof/callstacktrie/#a93eab9244b86ce5f52aa4f15a71741be">llvm::memprof::CallStackTrie::addSingleAllocTypeAttribute</a>.</p>

</div>
</div>

### createMIBNode() {#a7cbecc17bbb64783431627bcf1f433c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * createMIBNode (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; MIBCallStack, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27">AllocationType</a> AllocType, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/contexttotalsize">ContextTotalSize</a> &gt; ContextSizeInfo)</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp">MemoryProfileInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a1b412464f78908112e627ee7bc54f99d">llvm::memprof::buildCallstackMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a53fc78b63202142110d0e86dd1a71fbe">llvm::ValueAsMetadata::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#aafd414cdb5967be7eccd7a6f0d1ca76e">llvm::memprof::getAllocTypeAttributeString</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/mdtuple/#a80c832fdcf3f1a8c1e44275acbfc0df1">llvm::MDTuple::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### MemProfAveLifetimeColdThreshold {#a7e58ba176f0b2036a0c1f33e8bca02b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; MemProfAveLifetimeColdThreshold("memprof-ave-lifetime-cold-threshold", cl::init(200), cl::Hidden, cl::desc("The average lifetime (s) for an allocation to be considered " "cold"))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp">MemoryProfileInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a1e8a171cb61e4be7336e3beb7136e2dc">llvm::memprof::getAllocType</a>.</p>

</div>
</div>

### MemProfLifetimeAccessDensityColdThreshold {#a074e496786909ea8b41285699df5084c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; float &gt; MemProfLifetimeAccessDensityColdThreshold("memprof-lifetime-access-density-cold-threshold", cl::init(0.05), cl::Hidden, cl::desc("The threshold the lifetime access density (accesses per byte per " "lifetime sec) must be under to consider an allocation cold"))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp">MemoryProfileInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a1e8a171cb61e4be7336e3beb7136e2dc">llvm::memprof::getAllocType</a>.</p>

</div>
</div>

### MemProfMinAveLifetimeAccessDensityHotThreshold {#a456eeb44ad87143664388b1ee37c6956}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; MemProfMinAveLifetimeAccessDensityHotThreshold("memprof-min-ave-lifetime-access-density-hot-threshold", cl::init(1000), cl::Hidden, cl::desc("The minimum TotalLifetimeAccessDensity / AllocCount for an " "allocation to be considered hot"))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp">MemoryProfileInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a1e8a171cb61e4be7336e3beb7136e2dc">llvm::memprof::getAllocType</a>.</p>

</div>
</div>

### MemProfReportHintedSizes {#a696467f077d0e94dc6b3f171acc6be25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; MemProfReportHintedSizes("memprof-report-hinted-sizes", cl::init(false), cl::Hidden, cl::desc("Report total allocation sizes of hinted allocations"))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp">MemoryProfileInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#ae6c3c6c5044d97b7a9ec75b6105f68d8">addCallStack</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstacktrie/#a93eab9244b86ce5f52aa4f15a71741be">llvm::memprof::CallStackTrie::addSingleAllocTypeAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a9b06152b51259f884261bba3099e4fc6">computeFunctionSummary</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/indexcallsitecontextgraph/#aa4f54d80f1f0152753a9b60e3f5aea61">anonymous{MemProfContextDisambiguation.cpp}::IndexCallsiteContextGraph::IndexCallsiteContextGraph</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a4652a942c3bcd94d6540e3fb0238d356">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::process</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#ac7cd1bb8cb4a4e4e1ec44f5097cb071f">readMemprof</a>.</p>

</div>
</div>

### MemProfUseHotHints {#a5e2723962f88e74e915f2b10f02780b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; MemProfUseHotHints("memprof-use-hot-hints", cl::init(false), cl::Hidden, cl::desc("Enable use of hot hints (only supported for " "unambigously hot allocations)"))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp">MemoryProfileInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a1e8a171cb61e4be7336e3beb7136e2dc">llvm::memprof::getAllocType</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"memory-profile-info"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp">MemoryProfileInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
