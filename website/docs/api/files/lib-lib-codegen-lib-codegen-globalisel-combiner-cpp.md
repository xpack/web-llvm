---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/lib/codegen/globalisel/combiner-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `Combiner.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combiner-h">llvm/CodeGen/GlobalISel/Combiner.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/postorderiterator-h">llvm/ADT/PostOrderIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/cseinfo-h">llvm/CodeGen/GlobalISel/CSEInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">llvm/CodeGen/GlobalISel/CSEMIRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerinfo-h">llvm/CodeGen/GlobalISel/CombinerInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselchangeobserver-h">llvm/CodeGen/GlobalISel/GISelChangeObserver.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselworklist-h">llvm/CodeGen/GlobalISel/GISelWorkList.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">llvm/CodeGen/GlobalISel/MachineIRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/utils-h">llvm/CodeGen/GlobalISel/Utils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoptimizationremarkemitter-h">llvm/CodeGen/MachineOptimizationRemarkEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/combiner/worklistmaintainer">WorkListMaintainer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class acts as the glue that joins the <a href="/web-llvm/docs/api/classes/llvm/combinerhelper">CombinerHelper</a> to the overall Combine algorithm. <a href="/web-llvm/docs/api/classes/combiner/worklistmaintainer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/combiner/worklistmaintainerimpl">WorkListMaintainerImpl&lt;Lvl&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A configurable <a href="/web-llvm/docs/api/classes/combiner/worklistmaintainer">WorkListMaintainer</a> implementation. <a href="/web-llvm/docs/api/classes/combiner/worklistmaintainerimpl/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6531727684f4aee04bb115319b8666e">STATISTIC</a> (NumOneIteration, "Number of functions with one iteration")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace247c3d1e258ace812aec8f664dc397">STATISTIC</a> (NumTwoIterations, "Number of functions with two iterations")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a474bfa61012ebebfb3e7752d162cda36">STATISTIC</a> (NumThreeOrMoreIterations, "Number of functions with three or more iterations")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"gi-combiner"</td>
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

### STATISTIC() {#ac6531727684f4aee04bb115319b8666e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumOneIteration, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> with one iteration")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combiner-cpp">Combiner.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#ace247c3d1e258ace812aec8f664dc397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumTwoIterations, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> with two iterations")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combiner-cpp">Combiner.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a474bfa61012ebebfb3e7752d162cda36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumThreeOrMoreIterations, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> with three or more iterations")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combiner-cpp">Combiner.cpp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"gi-combiner"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combiner-cpp">Combiner.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
