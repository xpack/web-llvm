---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/cgdata/stablefunctionmap-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `StableFunctionMap.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">llvm/CGData/StableFunctionMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">llvm/ADT/SmallSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
</div>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d678a6d2890674eac008fa6dd4482e4">ParamLocs</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aac5c174796045b79a15a2bd17ced0d6f">IndexPair</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a172ac12ba3705f1f1e519e50c874d406">removeIdenticalIndexPair</a> (SmallVector&lt; std::unique_ptr&lt; StableFunctionMap::StableFunctionEntry &gt; &gt; &amp;SFS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1429d1fad1503cf63298bd5441e0e04b">isProfitable</a> (const SmallVector&lt; std::unique_ptr&lt; StableFunctionMap::StableFunctionEntry &gt; &gt; &amp;SFS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81cd2e046a63983e9a6d0826916b818a">GlobalMergingMinMerges</a>("global-merging-min-merges", cl::desc("Minimum number of similar functions with " "the same hash required for merging."), cl::init(2), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add0ff57068287df33482b550bdc618cc">GlobalMergingMinInstrs</a>("global-merging-min-instrs", cl::desc("The minimum instruction count required when merging functions."), cl::init(1), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaee5c3d90c3329d67374ccdf791ff45">GlobalMergingMaxParams</a>("global-merging-max-params", cl::desc("The maximum number of parameters allowed when merging functions."), cl::init(std::numeric_limits< unsigned >::max()), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5103a95ce66abf42ece1574d6ed690cc">GlobalMergingSkipNoParams</a>("global-merging-skip-no-params", cl::desc("Skip merging functions with no parameters."), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96aa97b527b4668ffa04b00c18a62b6a">GlobalMergingInstOverhead</a>("global-merging-inst-overhead", cl::desc("The overhead cost associated with each instruction when lowering " "to machine instruction."), cl::init(1.2), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a094324167621f0444a0793364196a4">GlobalMergingParamOverhead</a>("global-merging-param-overhead", cl::desc("The overhead cost associated with each parameter when merging " "functions."), cl::init(2.0), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8cb79f3e15eda1ea7262170fd5e8f42">GlobalMergingCallOverhead</a>("global-merging-call-overhead", cl::desc("The overhead cost associated with each " "function call when merging functions."), cl::init(1.0), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affa688bf2f1952f02888dd0681ef11d6">GlobalMergingExtraThreshold</a>("global-merging-extra-threshold", cl::desc("An additional cost threshold that must be exceeded for merging " "to be considered beneficial."), cl::init(0.0), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"stable-<a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a>-map"</td>
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

## Typedefs

### ParamLocs {#a7d678a6d2890674eac008fa6dd4482e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using ParamLocs =  SmallVector&lt;IndexPair&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp">StableFunctionMap.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### isProfitable() {#a1429d1fad1503cf63298bd5441e0e04b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isProfitable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap/stablefunctionentry">StableFunctionMap::StableFunctionEntry</a> &gt; &gt; &amp; SFS)</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp">StableFunctionMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallset/#a76b3fc7c102561fb5210d5151531e409">llvm::SmallSet&lt; T, N, C &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#aa8cb79f3e15eda1ea7262170fd5e8f42">GlobalMergingCallOverhead</a>, <a href="#affa688bf2f1952f02888dd0681ef11d6">GlobalMergingExtraThreshold</a>, <a href="#a96aa97b527b4668ffa04b00c18a62b6a">GlobalMergingInstOverhead</a>, <a href="#adaee5c3d90c3329d67374ccdf791ff45">GlobalMergingMaxParams</a>, <a href="#add0ff57068287df33482b550bdc618cc">GlobalMergingMinInstrs</a>, <a href="#a81cd2e046a63983e9a6d0826916b818a">GlobalMergingMinMerges</a>, <a href="#a6a094324167621f0444a0793364196a4">GlobalMergingParamOverhead</a>, <a href="#a5103a95ce66abf42ece1574d6ed690cc">GlobalMergingSkipNoParams</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/smallset/#afd7c135e18f2d7253d4f8545cd7b1756">llvm::SmallSet&lt; T, N, C &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap/#a2ca2d718f999a38c14668dffda65cdb9">llvm::StableFunctionMap::finalize</a>.</p>

</div>
</div>

### removeIdenticalIndexPair() {#a172ac12ba3705f1f1e519e50c874d406}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void removeIdenticalIndexPair (<a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap/stablefunctionentry">StableFunctionMap::StableFunctionEntry</a> &gt; &gt; &amp; SFS)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp">StableFunctionMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a563ffc2ff61c499b3be2e00100cb72fa">llvm::SmallVectorImpl&lt; T &gt;::erase</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap/#a2ca2d718f999a38c14668dffda65cdb9">llvm::StableFunctionMap::finalize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### GlobalMergingCallOverhead {#aa8cb79f3e15eda1ea7262170fd5e8f42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; double &gt; GlobalMergingCallOverhead("global-merging-call-overhead", cl::desc("The overhead cost associated with each " "function call when merging functions."), cl::init(1.0), cl::Hidden)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp">StableFunctionMap.cpp</a>.</p>


<p>Referenced by <a href="#a1429d1fad1503cf63298bd5441e0e04b">isProfitable</a>.</p>

</div>
</div>

### GlobalMergingExtraThreshold {#affa688bf2f1952f02888dd0681ef11d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; double &gt; GlobalMergingExtraThreshold("global-merging-extra-threshold", cl::desc("An additional cost threshold that must be exceeded for merging " "to be considered beneficial."), cl::init(0.0), cl::Hidden)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp">StableFunctionMap.cpp</a>.</p>


<p>Referenced by <a href="#a1429d1fad1503cf63298bd5441e0e04b">isProfitable</a>.</p>

</div>
</div>

### GlobalMergingInstOverhead {#a96aa97b527b4668ffa04b00c18a62b6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; double &gt; GlobalMergingInstOverhead("global-merging-inst-overhead", cl::desc("The overhead cost associated with each instruction when lowering " "to machine instruction."), cl::init(1.2), cl::Hidden)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp">StableFunctionMap.cpp</a>.</p>


<p>Referenced by <a href="#a1429d1fad1503cf63298bd5441e0e04b">isProfitable</a>.</p>

</div>
</div>

### GlobalMergingMaxParams {#adaee5c3d90c3329d67374ccdf791ff45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; GlobalMergingMaxParams("global-merging-max-params", cl::desc( "The maximum number of parameters allowed when merging functions."), cl::init(std::numeric_limits&lt; unsigned &gt;::max()), cl::Hidden)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp">StableFunctionMap.cpp</a>.</p>


<p>Referenced by <a href="#a1429d1fad1503cf63298bd5441e0e04b">isProfitable</a>.</p>

</div>
</div>

### GlobalMergingMinInstrs {#add0ff57068287df33482b550bdc618cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; GlobalMergingMinInstrs("global-merging-min-instrs", cl::desc("The minimum instruction count required when merging functions."), cl::init(1), cl::Hidden)</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp">StableFunctionMap.cpp</a>.</p>


<p>Referenced by <a href="#a1429d1fad1503cf63298bd5441e0e04b">isProfitable</a>.</p>

</div>
</div>

### GlobalMergingMinMerges {#a81cd2e046a63983e9a6d0826916b818a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; GlobalMergingMinMerges("global-merging-min-merges", cl::desc("Minimum number of similar functions with " "the same hash required for merging."), cl::init(2), cl::Hidden)</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp">StableFunctionMap.cpp</a>.</p>


<p>Referenced by <a href="#a1429d1fad1503cf63298bd5441e0e04b">isProfitable</a>.</p>

</div>
</div>

### GlobalMergingParamOverhead {#a6a094324167621f0444a0793364196a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; double &gt; GlobalMergingParamOverhead("global-merging-param-overhead", cl::desc("The overhead cost associated with each parameter when merging " "functions."), cl::init(2.0), cl::Hidden)</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp">StableFunctionMap.cpp</a>.</p>


<p>Referenced by <a href="#a1429d1fad1503cf63298bd5441e0e04b">isProfitable</a>.</p>

</div>
</div>

### GlobalMergingSkipNoParams {#a5103a95ce66abf42ece1574d6ed690cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; GlobalMergingSkipNoParams("global-merging-skip-no-params", cl::desc("Skip merging functions with no parameters."), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp">StableFunctionMap.cpp</a>.</p>


<p>Referenced by <a href="#a1429d1fad1503cf63298bd5441e0e04b">isProfitable</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"stable-<a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a>-map"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp">StableFunctionMap.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
