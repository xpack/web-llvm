---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/omp/gv
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `GV` Struct

<p>Defines various target-specific GPU grid values that must be consistent between host RTL (plugin), device RTL, and clang. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::omp::GV { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompgridvalues-h">llvm/Frontend/OpenMP/OMPGridValues.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b7087d8d3604af8163085885b47ff5b">warpSlotSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03b526999aac8c51ca01582c05d7df24">maxWarpNumber</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3382e977c39f5cca523c66e5c39819b8">GV_Slot_Size</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The size reserved for data in a shared memory slot. <a href="#a3382e977c39f5cca523c66e5c39819b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab03009604fe992e76c28719dae7b17bf">GV_Warp_Size</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The default value of maximum number of threads in a worker warp. <a href="#ab03009604fe992e76c28719dae7b17bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd17104f2b3e9251160c40c1d46a6901">GV_Max_Teams</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>the maximum number of teams. <a href="#afd17104f2b3e9251160c40c1d46a6901">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8069cfe4d5d95efa9fe71c245b59bf42">GV_Default_Num_Teams</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeab2bd06f53172bbb83ff3a405236549">GV_SimpleBufferSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff9a6e8168ef13b93b5ff49914e33c70">GV_Max_WG_Size</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5d84ee7def2e310c9a44e51b7165c89">GV_Default_WG_Size</a></td>
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

## Description {#details}

<p>Defines various target-specific GPU grid values that must be consistent between host RTL (plugin), device RTL, and clang.</p>


<p>We can change grid values for a "fat" binary so that different passes get the correct values when generating code for a multi-target binary. Both amdgcn and nvptx values are stored in this file. In the future, should there be differences between GPUs of the same architecture, then simply make a different array and use the new array name.</p>


<p>Example usage in clang: const unsigned slot_size = ctx.GetTargetInfo().<a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#ad52342fdd467389643191fdac7abcd40">getGridValue()</a>.GV_Warp_Size;</p>


<p>Example usage in libomptarget/deviceRTLs: #include "llvm/Frontend/OpenMP/OMPGridValues.h" #ifdef <b><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a></b> #define GRIDVAL AMDGPUGridValues <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a0544c3fe466e421738dae463968b70ba">else</a> #define GRIDVAL NVPTXGridValues #endif ... Then use this reference for GV_Warp_Size in the deviceRTL source. llvm::omp::GRIDVAL().GV_Warp_Size</p>


<p>Example usage in libomptarget hsa plugin: #include "llvm/Frontend/OpenMP/OMPGridValues.h" #define GRIDVAL AMDGPUGridValues ... Then use this reference to access GV_Warp_Size in the hsa plugin. llvm::omp::GRIDVAL().GV_Warp_Size</p>


<p>Example usage in libomptarget cuda plugin: #include "llvm/Frontend/OpenMP/OMPGridValues.h" #define GRIDVAL NVPTXGridValues ... Then use this reference to access GV_Warp_Size in the cuda plugin. llvm::omp::GRIDVAL().GV_Warp_Size</p>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompgridvalues-h">OMPGridValues.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### maxWarpNumber() {#a03b526999aac8c51ca01582c05d7df24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::omp::GV::maxWarpNumber ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompgridvalues-h">OMPGridValues.h</a>.</p>


<p>References <a href="#aff9a6e8168ef13b93b5ff49914e33c70">GV_Max_WG_Size</a> and <a href="#ab03009604fe992e76c28719dae7b17bf">GV_Warp_Size</a>.</p>

</div>
</div>

### warpSlotSize() {#a0b7087d8d3604af8163085885b47ff5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::omp::GV::warpSlotSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompgridvalues-h">OMPGridValues.h</a>.</p>


<p>References <a href="#a3382e977c39f5cca523c66e5c39819b8">GV_Slot_Size</a> and <a href="#ab03009604fe992e76c28719dae7b17bf">GV_Warp_Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### GV\_Default\_Num\_Teams {#a8069cfe4d5d95efa9fe71c245b59bf42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::omp::GV::GV_Default_Num_Teams</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompgridvalues-h">OMPGridValues.h</a>.</p>

</div>
</div>

### GV\_Default\_WG\_Size {#ac5d84ee7def2e310c9a44e51b7165c89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::omp::GV::GV_Default_WG_Size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompgridvalues-h">OMPGridValues.h</a>.</p>

</div>
</div>

### GV\_Max\_Teams {#afd17104f2b3e9251160c40c1d46a6901}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::omp::GV::GV_Max_Teams</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>the maximum number of teams.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompgridvalues-h">OMPGridValues.h</a>.</p>

</div>
</div>

### GV\_Max\_WG\_Size {#aff9a6e8168ef13b93b5ff49914e33c70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::omp::GV::GV_Max_WG_Size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompgridvalues-h">OMPGridValues.h</a>.</p>


<p>Referenced by <a href="#a03b526999aac8c51ca01582c05d7df24">maxWarpNumber</a>.</p>

</div>
</div>

### GV\_SimpleBufferSize {#aeab2bd06f53172bbb83ff3a405236549}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::omp::GV::GV_SimpleBufferSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompgridvalues-h">OMPGridValues.h</a>.</p>

</div>
</div>

### GV\_Slot\_Size {#a3382e977c39f5cca523c66e5c39819b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::omp::GV::GV_Slot_Size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The size reserved for data in a shared memory slot.</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompgridvalues-h">OMPGridValues.h</a>.</p>


<p>Referenced by <a href="#a0b7087d8d3604af8163085885b47ff5b">warpSlotSize</a>.</p>

</div>
</div>

### GV\_Warp\_Size {#ab03009604fe992e76c28719dae7b17bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::omp::GV::GV_Warp_Size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The default value of maximum number of threads in a worker warp.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompgridvalues-h">OMPGridValues.h</a>.</p>


<p>Referenced by <a href="#a03b526999aac8c51ca01582c05d7df24">maxWarpNumber</a> and <a href="#a0b7087d8d3604af8163085885b47ff5b">warpSlotSize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompgridvalues-h">OMPGridValues.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
