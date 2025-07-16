---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/openmpirbuilder/targetkernelargs
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `TargetKernelArgs` Struct Reference

<p>Data structure that contains the needed information to construct the kernel args vector. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::OpenMPIRBuilder::TargetKernelArgs { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">llvm/Frontend/OpenMP/OMPIRBuilder.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2533a0b130e39dab9f0298b47abe8553">TargetKernelArgs</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23864b156465861c7a363bbca51dcca4">TargetKernelArgs</a> (unsigned NumTargetItems, TargetDataRTArgs RTArgs, Value *NumIterations, ArrayRef&lt; Value * &gt; NumTeams, ArrayRef&lt; Value * &gt; NumThreads, Value *DynCGGroupMem, bool HasNoWait)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab406e5f23f9a8061483e9d879708e58b">NumTargetItems</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of arguments passed to the runtime library. <a href="#ab406e5f23f9a8061483e9d879708e58b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs">TargetDataRTArgs</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a05e86ad780f78491ca53c7cade2629">RTArgs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Arguments passed to the runtime library. <a href="#a5a05e86ad780f78491ca53c7cade2629">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9289b4e3e6193c6848534421a1f6d325">NumIterations</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of iterations. <a href="#a9289b4e3e6193c6848534421a1f6d325">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5718af182d3976468a66ffef21caefd">NumTeams</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of teams. <a href="#ac5718af182d3976468a66ffef21caefd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a565226b20a62efa516b5f5b69af983dc">NumThreads</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of threads. <a href="#a565226b20a62efa516b5f5b69af983dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54507f6f762774d59326a2145ae440f9">DynCGGroupMem</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The size of the dynamic shared memory. <a href="#a54507f6f762774d59326a2145ae440f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb0aaa97617824c208f95e218b9fcf6c">HasNoWait</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the kernel has 'no wait' clause. <a href="#abb0aaa97617824c208f95e218b9fcf6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Data structure that contains the needed information to construct the kernel args vector.</p>

<p>Definition at line 2272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TargetKernelArgs() {#a2533a0b130e39dab9f0298b47abe8553}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OpenMPIRBuilder::TargetKernelArgs::TargetKernelArgs ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### TargetKernelArgs() {#a23864b156465861c7a363bbca51dcca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OpenMPIRBuilder::TargetKernelArgs::TargetKernelArgs (unsigned NumTargetItems, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/targetdatartargs">TargetDataRTArgs</a> RTArgs, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NumIterations, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; NumTeams, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; NumThreads, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * DynCGGroupMem, bool HasNoWait)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="#a54507f6f762774d59326a2145ae440f9">DynCGGroupMem</a>, <a href="#abb0aaa97617824c208f95e218b9fcf6c">HasNoWait</a>, <a href="#a9289b4e3e6193c6848534421a1f6d325">NumIterations</a>, <a href="#ab406e5f23f9a8061483e9d879708e58b">NumTargetItems</a>, <a href="#ac5718af182d3976468a66ffef21caefd">NumTeams</a>, <a href="#a565226b20a62efa516b5f5b69af983dc">NumThreads</a> and <a href="#a5a05e86ad780f78491ca53c7cade2629">RTArgs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DynCGGroupMem {#a54507f6f762774d59326a2145ae440f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::OpenMPIRBuilder::TargetKernelArgs::DynCGGroupMem = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The size of the dynamic shared memory.</p>

<p>Definition at line 2284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a49e1f0512e7d7b37dfcecc0b25dd875b">llvm::OpenMPIRBuilder::getKernelArgsVector</a> and <a href="#a23864b156465861c7a363bbca51dcca4">TargetKernelArgs</a>.</p>

</div>
</div>

### HasNoWait {#abb0aaa97617824c208f95e218b9fcf6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OpenMPIRBuilder::TargetKernelArgs::HasNoWait = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the kernel has 'no wait' clause.</p>

<p>Definition at line 2286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a49e1f0512e7d7b37dfcecc0b25dd875b">llvm::OpenMPIRBuilder::getKernelArgsVector</a> and <a href="#a23864b156465861c7a363bbca51dcca4">TargetKernelArgs</a>.</p>

</div>
</div>

### NumIterations {#a9289b4e3e6193c6848534421a1f6d325}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::OpenMPIRBuilder::TargetKernelArgs::NumIterations = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of iterations.</p>

<p>Definition at line 2278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a49e1f0512e7d7b37dfcecc0b25dd875b">llvm::OpenMPIRBuilder::getKernelArgsVector</a> and <a href="#a23864b156465861c7a363bbca51dcca4">TargetKernelArgs</a>.</p>

</div>
</div>

### NumTargetItems {#ab406e5f23f9a8061483e9d879708e58b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::OpenMPIRBuilder::TargetKernelArgs::NumTargetItems = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of arguments passed to the runtime library.</p>

<p>Definition at line 2274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a49e1f0512e7d7b37dfcecc0b25dd875b">llvm::OpenMPIRBuilder::getKernelArgsVector</a> and <a href="#a23864b156465861c7a363bbca51dcca4">TargetKernelArgs</a>.</p>

</div>
</div>

### NumTeams {#ac5718af182d3976468a66ffef21caefd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;Value *&gt; llvm::OpenMPIRBuilder::TargetKernelArgs::NumTeams</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of teams.</p>

<p>Definition at line 2280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a49e1f0512e7d7b37dfcecc0b25dd875b">llvm::OpenMPIRBuilder::getKernelArgsVector</a> and <a href="#a23864b156465861c7a363bbca51dcca4">TargetKernelArgs</a>.</p>

</div>
</div>

### NumThreads {#a565226b20a62efa516b5f5b69af983dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;Value *&gt; llvm::OpenMPIRBuilder::TargetKernelArgs::NumThreads</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of threads.</p>

<p>Definition at line 2282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a49e1f0512e7d7b37dfcecc0b25dd875b">llvm::OpenMPIRBuilder::getKernelArgsVector</a> and <a href="#a23864b156465861c7a363bbca51dcca4">TargetKernelArgs</a>.</p>

</div>
</div>

### RTArgs {#a5a05e86ad780f78491ca53c7cade2629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetDataRTArgs llvm::OpenMPIRBuilder::TargetKernelArgs::RTArgs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Arguments passed to the runtime library.</p>

<p>Definition at line 2276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a49e1f0512e7d7b37dfcecc0b25dd875b">llvm::OpenMPIRBuilder::getKernelArgsVector</a> and <a href="#a23864b156465861c7a363bbca51dcca4">TargetKernelArgs</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
