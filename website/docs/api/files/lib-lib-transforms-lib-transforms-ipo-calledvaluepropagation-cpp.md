---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `CalledValuePropagation.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/calledvaluepropagation-h">llvm/Transforms/IPO/CalledValuePropagation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/sparsepropagation-h">llvm/Analysis/SparsePropagation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelatticeutils-h">llvm/Analysis/ValueLatticeUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">llvm/IR/MDBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/ipo-h">llvm/Transforms/IPO.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-">anonymous{CalledValuePropagation.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The lattice value type used by our custom lattice function. <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-calledvaluepropagation-cpp-/cvplatticeval/compare">Compare</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Comparator for sorting the functions set. <a href="/web-llvm/docs/api/structs/anonymous-calledvaluepropagation-cpp-/cvplatticeval/compare/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticefunc">CVPLatticeFunc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The custom lattice function used by the generic sparse propagation solver. <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticefunc/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/latticekeyinfo-c7b4452532d4f9636f17e038bc48f1b5">LatticeKeyInfo&lt;CVPLatticeKey&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A specialization of <a href="/web-llvm/docs/api/structs/llvm/latticekeyinfo">LatticeKeyInfo</a> for CVPLatticeKeys. <a href="/web-llvm/docs/api/structs/llvm/latticekeyinfo-c7b4452532d4f9636f17e038bc48f1b5/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d2bce545ae26cccf351c2c0d35d64e4">runCVP</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c244e5ff5a1fb8c12ec6d8fe73d0ba0">MaxFunctionsPerValue</a>("cvp-max-functions-per-value", cl::Hidden, cl::init(4), cl::desc("The maximum number of functions to track per lattice value"))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The maximum number of functions to track per lattice value. <a href="#a0c244e5ff5a1fb8c12ec6d8fe73d0ba0">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"called-value-propagation"</td>
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

### runCVP() {#a1d2bce545ae26cccf351c2c0d35d64e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool runCVP (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af1d3deadf8d348b2329f4e7fa5386e5b">llvm::canTrackArgumentsInterprocedurally</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#aa81136ed319a6187cf349eb602da963a">llvm::MDBuilder::createCallees</a>, <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticefunc/#a2871c5f1c7d8fc5bcd439d7bcbb062f0">anonymous{CalledValuePropagation.cpp}::CVPLatticeFunc::CVPLatticeFunc</a>, <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval/#a7e695347fc29b8adcd616dc29eba9e39">anonymous{CalledValuePropagation.cpp}::CVPLatticeVal::CVPLatticeVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/sparsesolver/#abb4cb9c22c6fdf8bfd36864c92d5449c">llvm::SparseSolver&lt; LatticeKey, LatticeVal, KeyInfo &gt;::getExistingValueState</a>, <a href="/web-llvm/docs/api/classes/llvm/sparsesolver/#aa957a217201ee36323b4cd3c5d4c939a">llvm::SparseSolver&lt; LatticeKey, LatticeVal, KeyInfo &gt;::MarkBlockExecutable</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#a5f10072974ec01bdf70a2f2215f44b23a0ba7583639a274c434bbe6ef797115a4">anonymous{CalledValuePropagation.cpp}::Register</a> and <a href="/web-llvm/docs/api/classes/llvm/sparsesolver/#ab2eb802e84c2b0f592aee41ad6c2b729">llvm::SparseSolver&lt; LatticeKey, LatticeVal, KeyInfo &gt;::Solve</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/calledvaluepropagationpass/#a97d2795c46a61afbc87c4c88caac7124">llvm::CalledValuePropagationPass::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### MaxFunctionsPerValue {#a0c244e5ff5a1fb8c12ec6d8fe73d0ba0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; MaxFunctionsPerValue("cvp-max-functions-per-value", cl::Hidden, cl::init(4), cl::desc("The maximum number of functions to track per lattice value"))</td>
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

<p>The maximum number of functions to track per lattice value.</p>


<p>Once the number of functions a call site can possibly target exceeds this threshold, it's lattice value becomes overdefined. The number of possible lattice values is bounded by Ch(F, M), where F is the number of functions in the module and M is MaxFunctionsPerValue. As such, this value should be kept very small. We likely can't do anything useful for call sites with a large number of possible targets, anyway.</p>


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticefunc/#a0011b8df581b97747a420890826a7eeb">anonymous{CalledValuePropagation.cpp}::CVPLatticeFunc::MergeValues</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"called-value-propagation"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
