---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/lib/codegen/selectiondag/resourcepriorityqueue-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `ResourcePriorityQueue.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/resourcepriorityqueue-h">llvm/CodeGen/ResourcePriorityQueue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">llvm/CodeGen/DFAPacketizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagisel-h">llvm/CodeGen/SelectionDAGISel.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">llvm/CodeGen/SelectionDAGNodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fd9efbedcbd8af579647f70a9c35f65">numberCtrlDepsInSU</a> (SUnit *SU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ab96228908e98db52f1e1dd59bafbde">numberCtrlPredInSU</a> (SUnit *SU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51a9c7c5a9a8e47f6c5c3240e85d8ca6">DisableDFASched</a>("disable-dfa-sched", cl::Hidden, cl::desc("Disable use of DFA during scheduling"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0df822aea97e1eeadc0845521726bc19">RegPressureThreshold</a>("dfa-sched-reg-pressure-threshold", cl::Hidden, cl::init(5), cl::desc("Track reg pressure and switch priority to in-depth"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e12c3463c47765c7655cbb3e74b854b">PriorityOne</a> = 200</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05cbf54b10915334c7da67e47773f0c4">PriorityTwo</a> = 50</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c694e892c63ea2253587a07eb428601">PriorityThree</a> = 15</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abba8af881520ddbdd4284d9441e8db6b">PriorityFour</a> = 5</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c30998d0887fcc4f3134287c8e5fd7f">ScaleOne</a> = 20</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac23161046eaf1ee7b7a3d363291ec7bb">ScaleTwo</a> = 10</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9d9e3d964402bce3c531d7adfc89fb0">ScaleThree</a> = 5</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05e54c70e7a069ff7a57d93bda6a529b">FactorOne</a> = 2</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"scheduler"</td>
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

### numberCtrlDepsInSU() {#a4fd9efbedcbd8af579647f70a9c35f65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned numberCtrlDepsInSU (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/resourcepriorityqueue-cpp">ResourcePriorityQueue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdep/#a8b4768ef4b1a0a2e8d50714b07465075">llvm::SDep::isCtrl</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#aab4a86c51e6b126c9c6ef58dbb574431">llvm::SUnit::Succs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a0ad9cbe1a5bd1eb9d026fc0e91fab117">llvm::ResourcePriorityQueue::scheduledNode</a>.</p>

</div>
</div>

### numberCtrlPredInSU() {#a3ab96228908e98db52f1e1dd59bafbde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned numberCtrlPredInSU (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/resourcepriorityqueue-cpp">ResourcePriorityQueue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae2b43854b542de66eec6475adc48f56c">llvm::SUnit::Preds</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a0ad9cbe1a5bd1eb9d026fc0e91fab117">llvm::ResourcePriorityQueue::scheduledNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DisableDFASched {#a51a9c7c5a9a8e47f6c5c3240e85d8ca6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableDFASched("disable-dfa-sched", cl::Hidden, cl::desc("Disable use of DFA during scheduling"))</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/resourcepriorityqueue-cpp">ResourcePriorityQueue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a7720efbfc06e11a61338a3ab97142b62">llvm::ResourcePriorityQueue::pop</a>.</p>

</div>
</div>

### FactorOne {#a05e54c70e7a069ff7a57d93bda6a529b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned FactorOne = 2</td>
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



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/resourcepriorityqueue-cpp">ResourcePriorityQueue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae3f9d679010b93efcba0721c8714d029">llvm::ResourcePriorityQueue::SUSchedulingCost</a>.</p>

</div>
</div>

### PriorityFour {#abba8af881520ddbdd4284d9441e8db6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned PriorityFour = 5</td>
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



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/resourcepriorityqueue-cpp">ResourcePriorityQueue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae3f9d679010b93efcba0721c8714d029">llvm::ResourcePriorityQueue::SUSchedulingCost</a>.</p>

</div>
</div>

### PriorityOne {#a3e12c3463c47765c7655cbb3e74b854b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned PriorityOne = 200</td>
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



<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/resourcepriorityqueue-cpp">ResourcePriorityQueue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae3f9d679010b93efcba0721c8714d029">llvm::ResourcePriorityQueue::SUSchedulingCost</a>.</p>

</div>
</div>

### PriorityThree {#a0c694e892c63ea2253587a07eb428601}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned PriorityThree = 15</td>
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



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/resourcepriorityqueue-cpp">ResourcePriorityQueue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae3f9d679010b93efcba0721c8714d029">llvm::ResourcePriorityQueue::SUSchedulingCost</a>.</p>

</div>
</div>

### PriorityTwo {#a05cbf54b10915334c7da67e47773f0c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned PriorityTwo = 50</td>
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



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/resourcepriorityqueue-cpp">ResourcePriorityQueue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae3f9d679010b93efcba0721c8714d029">llvm::ResourcePriorityQueue::SUSchedulingCost</a>.</p>

</div>
</div>

### RegPressureThreshold {#a0df822aea97e1eeadc0845521726bc19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; RegPressureThreshold("dfa-sched-reg-pressure-threshold", cl::Hidden, cl::init(5), cl::desc("Track reg pressure and switch priority to in-depth"))</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/resourcepriorityqueue-cpp">ResourcePriorityQueue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae3f9d679010b93efcba0721c8714d029">llvm::ResourcePriorityQueue::SUSchedulingCost</a>.</p>

</div>
</div>

### ScaleOne {#a2c30998d0887fcc4f3134287c8e5fd7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned ScaleOne = 20</td>
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



<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/resourcepriorityqueue-cpp">ResourcePriorityQueue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae3f9d679010b93efcba0721c8714d029">llvm::ResourcePriorityQueue::SUSchedulingCost</a>.</p>

</div>
</div>

### ScaleThree {#ad9d9e3d964402bce3c531d7adfc89fb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned ScaleThree = 5</td>
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



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/resourcepriorityqueue-cpp">ResourcePriorityQueue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae3f9d679010b93efcba0721c8714d029">llvm::ResourcePriorityQueue::SUSchedulingCost</a>.</p>

</div>
</div>

### ScaleTwo {#ac23161046eaf1ee7b7a3d363291ec7bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned ScaleTwo = 10</td>
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



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/resourcepriorityqueue-cpp">ResourcePriorityQueue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae3f9d679010b93efcba0721c8714d029">llvm::ResourcePriorityQueue::SUSchedulingCost</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"scheduler"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/resourcepriorityqueue-cpp">ResourcePriorityQueue.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
