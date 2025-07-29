---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/regallocscore-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `RegAllocScore.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocscore-h">RegAllocScore.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">llvm/CodeGen/MachineBlockFrequencyInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">llvm/MC/MCInstrDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
</div>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; double &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25fab3b94c19a039b32fac4606a260ed">CopyWeight</a>("regalloc-copy-weight", cl::init(0.2), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; double &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa4037996bc026c98d9ac9bea2d43a5f">LoadWeight</a>("regalloc-load-weight", cl::init(4.0), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; double &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a149703b9ecece72af1ad9298d77c4760">StoreWeight</a>("regalloc-store-weight", cl::init(1.0), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; double &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a069d43f9b44a733a7cf8d151af99a7d5">CheapRematWeight</a>("regalloc-cheap-remat-weight", cl::init(0.2), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; double &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4528cf72b5325ab349ea227ea44d8cc4">ExpensiveRematWeight</a>("regalloc-expensive-remat-weight", cl::init(1.0), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"regalloc-score"</td>
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

## Variables

### CheapRematWeight {#a069d43f9b44a733a7cf8d151af99a7d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; double &gt; CheapRematWeight("regalloc-cheap-remat-weight", cl::init(0.2), cl::Hidden)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocscore-cpp">RegAllocScore.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regallocscore/#a96a14d5b9b697269c92d373e2887e3fa">llvm::RegAllocScore::getScore</a>.</p>

</div>
</div>

### CopyWeight {#a25fab3b94c19a039b32fac4606a260ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; double &gt; CopyWeight("regalloc-copy-weight", cl::init(0.2), cl::Hidden)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocscore-cpp">RegAllocScore.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regallocscore/#a96a14d5b9b697269c92d373e2887e3fa">llvm::RegAllocScore::getScore</a>.</p>

</div>
</div>

### ExpensiveRematWeight {#a4528cf72b5325ab349ea227ea44d8cc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; double &gt; ExpensiveRematWeight("regalloc-expensive-remat-weight", cl::init(1.0), cl::Hidden)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocscore-cpp">RegAllocScore.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regallocscore/#a96a14d5b9b697269c92d373e2887e3fa">llvm::RegAllocScore::getScore</a>.</p>

</div>
</div>

### LoadWeight {#aaa4037996bc026c98d9ac9bea2d43a5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; double &gt; LoadWeight("regalloc-load-weight", cl::init(4.0), cl::Hidden)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocscore-cpp">RegAllocScore.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regallocscore/#a96a14d5b9b697269c92d373e2887e3fa">llvm::RegAllocScore::getScore</a>.</p>

</div>
</div>

### StoreWeight {#a149703b9ecece72af1ad9298d77c4760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; double &gt; StoreWeight("regalloc-store-weight", cl::init(1.0), cl::Hidden)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocscore-cpp">RegAllocScore.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regallocscore/#a96a14d5b9b697269c92d373e2887e3fa">llvm::RegAllocScore::getScore</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"regalloc-score"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocscore-cpp">RegAllocScore.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
