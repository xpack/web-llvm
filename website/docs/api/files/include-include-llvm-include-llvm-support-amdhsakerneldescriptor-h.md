---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `AMDHSAKernelDescriptor.h` File Reference

<p>AMDHSA kernel descriptor definitions. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include &lt;cstddef&gt;
#include &lt;cstdint&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/amdhsa">amdhsa</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/amdhsa/kernel-descriptor-t">kernel_descriptor_t</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a276e8a32e0bbf024aadd9420b8f2d3b3">offsetof</a>(TYPE, MEMBER)&nbsp;&nbsp;&nbsp;((size_t)&amp;((TYPE*)0)-&gt;MEMBER)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a286f2813b785a6b1d7f9c688580c2dc4">AMDHSA_BITS_GET</a>(SRC, MSK)&nbsp;&nbsp;&nbsp;((SRC &amp; MSK) &gt;&gt; MSK ## _SHIFT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adce610366807c48cc27d759a245b20cd">AMDHSA_BITS_SET</a>(DST, MSK, VAL)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34bafff22e321250ea590779a90f0fab">COMPUTE_PGM_RSRC1</a>(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC1_ ## NAME, SHIFT, WIDTH)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a294abd8f350600173e1464529fde121f">COMPUTE_PGM_RSRC1_GFX6_GFX8</a>(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC1_GFX6_GFX8_ ## NAME, SHIFT, WIDTH)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a379c457eec09ec0c0dfc9a68da0bf70e">COMPUTE_PGM_RSRC1_GFX6_GFX9</a>(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC1_GFX6_GFX9_ ## NAME, SHIFT, WIDTH)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bf6b2f487ffe327838e8b6c40feb53c">COMPUTE_PGM_RSRC1_GFX6_GFX11</a>(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC1_GFX6_GFX11_##NAME, SHIFT, WIDTH)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab09234733d72a7d048314164b5ba978e">COMPUTE_PGM_RSRC1_GFX9_PLUS</a>(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC1_GFX9_PLUS_ ## NAME, SHIFT, WIDTH)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a651ba737a9dbdeffe26a230ed2d92183">COMPUTE_PGM_RSRC1_GFX10_PLUS</a>(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC1_GFX10_PLUS_ ## NAME, SHIFT, WIDTH)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a663a1bb128ffe2009e444dc3f94fbcea">COMPUTE_PGM_RSRC1_GFX12_PLUS</a>(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC1_GFX12_PLUS_##NAME, SHIFT, WIDTH)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e0a976b9d48db21751f62e812b4b588">COMPUTE_PGM_RSRC2</a>(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC2_ ## NAME, SHIFT, WIDTH)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f923902a4e261428080fd4c1f53884d">COMPUTE_PGM_RSRC2_GFX6_GFX11</a>(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC2_GFX6_GFX11_##NAME, SHIFT, WIDTH)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9800a1227813a73faed0e7b66f831bb">COMPUTE_PGM_RSRC2_GFX12_PLUS</a>(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC2_GFX12_PLUS_##NAME, SHIFT, WIDTH)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3b83c6117b9ca484569f88e2f472551">COMPUTE_PGM_RSRC3_GFX90A</a>(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC3_GFX90A_ ## NAME, SHIFT, WIDTH)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7aebc44cfcfdc2d81ddf83350a2ed037">COMPUTE_PGM_RSRC3_GFX10_PLUS</a>(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC3_GFX10_PLUS_ ## NAME, SHIFT, WIDTH)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf016b755265b6b5ade87a7b805fb504">COMPUTE_PGM_RSRC3_GFX10</a>(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC3_GFX10_##NAME, SHIFT, WIDTH)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36be1c869a825abb6ebd08428953917c">COMPUTE_PGM_RSRC3_GFX10_GFX11</a>(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC3_GFX10_GFX11_##NAME, SHIFT, WIDTH)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8f00fe9aacadd8bb90d679df6b7f303">COMPUTE_PGM_RSRC3_GFX11_PLUS</a>(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC3_GFX11_PLUS_ ## NAME, SHIFT, WIDTH)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab46e59088da199af557d2c122f75ebe2">COMPUTE_PGM_RSRC3_GFX11</a>(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC3_GFX11_##NAME, SHIFT, WIDTH)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fd902705cde97f389da97cf9205e4c4">COMPUTE_PGM_RSRC3_GFX12_PLUS</a>(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC3_GFX12_PLUS_##NAME, SHIFT, WIDTH)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae106ed3b538dc6930bd46ac24be124e0">KERNEL_CODE_PROPERTY</a>(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(KERNEL_CODE_PROPERTY_ ## NAME, SHIFT, WIDTH)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a205075873d30ea3223ff29f4af044a03">KERNARG_PRELOAD_SPEC</a>(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(KERNARG_PRELOAD_SPEC_##NAME, SHIFT, WIDTH)</td>
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

<p>AMDHSA kernel descriptor definitions.</p>


<p>For more information, visit <a href="https://llvm.org/docs/AMDGPUUsage.html#kernel-descriptor">https://llvm.org/docs/AMDGPUUsage.html#kernel-descriptor</a></p>



:::warning
<p>Any changes to this file should also be audited for corresponding changes needed in both the assembler and disassembler, namely:</p>


<ul class="doxyList ">
<li>AMDGPUAsmPrinter.{cpp,h}</li>
<li>AMDGPUTargetStreamer.{cpp,h}</li>
<li>AMDGPUDisassembler.{cpp,h}</li>
</ul>
:::


<div class="doxySectionDef">

## Macro Definitions

### AMDHSA\_BITS\_ENUM\_ENTRY {#ae6a45f3d61391e87ca72159b73bed5f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define AMDHSA_BITS_ENUM_ENTRY(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  NAME ## _SHIFT = (SHIFT),                        \
  NAME ## _WIDTH = (WIDTH),                        \
  NAME = (((1 &lt;&lt; (WIDTH)) - 1) &lt;&lt; (SHIFT))
</div>
</dd>
</dl>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>

</div>
</div>

### AMDHSA\_BITS\_GET {#a286f2813b785a6b1d7f9c688580c2dc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define AMDHSA_BITS_GET(SRC, MSK)&nbsp;&nbsp;&nbsp;((SRC &amp; MSK) &gt;&gt; MSK ## _SHIFT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a66aa742680260d77ebab20536c828c17">llvm::AMDGPUDisassembler::decodeKernelDescriptor</a>.</p>

</div>
</div>

### AMDHSA\_BITS\_SET {#adce610366807c48cc27d759a245b20cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define AMDHSA_BITS_SET(DST, MSK, VAL)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  do {                                                                         \
    auto local = VAL;                                                          \
    DST &amp;= ~MSK;                                                               \
    DST |= ((local &lt;&lt; MSK##_SHIFT) &amp; MSK);                                     \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (0)
</div>
</dd>
</dl>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>

</div>
</div>

### COMPUTE\_PGM\_RSRC1 {#a34bafff22e321250ea590779a90f0fab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMPUTE_PGM_RSRC1(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC1_ ## NAME, SHIFT, WIDTH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>

</div>
</div>

### COMPUTE\_PGM\_RSRC1\_GFX10\_PLUS {#a651ba737a9dbdeffe26a230ed2d92183}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMPUTE_PGM_RSRC1_GFX10_PLUS(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC1_GFX10_PLUS_ ## NAME, SHIFT, WIDTH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>

</div>
</div>

### COMPUTE\_PGM\_RSRC1\_GFX12\_PLUS {#a663a1bb128ffe2009e444dc3f94fbcea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMPUTE_PGM_RSRC1_GFX12_PLUS(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC1_GFX12_PLUS_##NAME, SHIFT, WIDTH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>

</div>
</div>

### COMPUTE\_PGM\_RSRC1\_GFX6\_GFX11 {#a4bf6b2f487ffe327838e8b6c40feb53c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMPUTE_PGM_RSRC1_GFX6_GFX11(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC1_GFX6_GFX11_##NAME, SHIFT, WIDTH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>

</div>
</div>

### COMPUTE\_PGM\_RSRC1\_GFX6\_GFX8 {#a294abd8f350600173e1464529fde121f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMPUTE_PGM_RSRC1_GFX6_GFX8(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC1_GFX6_GFX8_ ## NAME, SHIFT, WIDTH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>

</div>
</div>

### COMPUTE\_PGM\_RSRC1\_GFX6\_GFX9 {#a379c457eec09ec0c0dfc9a68da0bf70e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMPUTE_PGM_RSRC1_GFX6_GFX9(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC1_GFX6_GFX9_ ## NAME, SHIFT, WIDTH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>

</div>
</div>

### COMPUTE\_PGM\_RSRC1\_GFX9\_PLUS {#ab09234733d72a7d048314164b5ba978e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMPUTE_PGM_RSRC1_GFX9_PLUS(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC1_GFX9_PLUS_ ## NAME, SHIFT, WIDTH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>

</div>
</div>

### COMPUTE\_PGM\_RSRC2 {#a6e0a976b9d48db21751f62e812b4b588}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMPUTE_PGM_RSRC2(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC2_ ## NAME, SHIFT, WIDTH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>

</div>
</div>

### COMPUTE\_PGM\_RSRC2\_GFX12\_PLUS {#af9800a1227813a73faed0e7b66f831bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMPUTE_PGM_RSRC2_GFX12_PLUS(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC2_GFX12_PLUS_##NAME, SHIFT, WIDTH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>

</div>
</div>

### COMPUTE\_PGM\_RSRC2\_GFX6\_GFX11 {#a5f923902a4e261428080fd4c1f53884d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMPUTE_PGM_RSRC2_GFX6_GFX11(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC2_GFX6_GFX11_##NAME, SHIFT, WIDTH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>

</div>
</div>

### COMPUTE\_PGM\_RSRC3\_GFX10 {#acf016b755265b6b5ade87a7b805fb504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMPUTE_PGM_RSRC3_GFX10(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC3_GFX10_##NAME, SHIFT, WIDTH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>

</div>
</div>

### COMPUTE\_PGM\_RSRC3\_GFX10\_GFX11 {#a36be1c869a825abb6ebd08428953917c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMPUTE_PGM_RSRC3_GFX10_GFX11(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC3_GFX10_GFX11_##NAME, SHIFT, WIDTH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>

</div>
</div>

### COMPUTE\_PGM\_RSRC3\_GFX10\_PLUS {#a7aebc44cfcfdc2d81ddf83350a2ed037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMPUTE_PGM_RSRC3_GFX10_PLUS(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC3_GFX10_PLUS_ ## NAME, SHIFT, WIDTH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>

</div>
</div>

### COMPUTE\_PGM\_RSRC3\_GFX11 {#ab46e59088da199af557d2c122f75ebe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMPUTE_PGM_RSRC3_GFX11(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC3_GFX11_##NAME, SHIFT, WIDTH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>

</div>
</div>

### COMPUTE\_PGM\_RSRC3\_GFX11\_PLUS {#ae8f00fe9aacadd8bb90d679df6b7f303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMPUTE_PGM_RSRC3_GFX11_PLUS(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC3_GFX11_PLUS_ ## NAME, SHIFT, WIDTH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>

</div>
</div>

### COMPUTE\_PGM\_RSRC3\_GFX12\_PLUS {#a9fd902705cde97f389da97cf9205e4c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMPUTE_PGM_RSRC3_GFX12_PLUS(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC3_GFX12_PLUS_##NAME, SHIFT, WIDTH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>

</div>
</div>

### COMPUTE\_PGM\_RSRC3\_GFX90A {#ab3b83c6117b9ca484569f88e2f472551}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMPUTE_PGM_RSRC3_GFX90A(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(COMPUTE_PGM_RSRC3_GFX90A_ ## NAME, SHIFT, WIDTH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>

</div>
</div>

### KERNARG\_PRELOAD\_SPEC {#a205075873d30ea3223ff29f4af044a03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define KERNARG_PRELOAD_SPEC(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(KERNARG_PRELOAD_SPEC_##NAME, SHIFT, WIDTH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>

</div>
</div>

### KERNEL\_CODE\_PROPERTY {#ae106ed3b538dc6930bd46ac24be124e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define KERNEL_CODE_PROPERTY(NAME, SHIFT, WIDTH)&nbsp;&nbsp;&nbsp;  <a href="#ae6a45f3d61391e87ca72159b73bed5f4">AMDHSA_BITS_ENUM_ENTRY</a>(KERNEL_CODE_PROPERTY_ ## NAME, SHIFT, WIDTH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>

</div>
</div>

### offsetof {#a276e8a32e0bbf024aadd9420b8f2d3b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define offsetof(TYPE, MEMBER)&nbsp;&nbsp;&nbsp;((size_t)&amp;((TYPE*)0)-&gt;MEMBER)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h">AMDHSAKernelDescriptor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/anonymous-coffimportfile-cpp-/objectfactory/#a711507659368382a73cbb514ecdc53d0">llvm::object::anonymous{COFFImportFile.cpp}::ObjectFactory::createImportDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#a9ede3510dd3c4a79112fd4ff9048e04b">llvm::gsym::GsymCreator::encode</a>, <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/#a03c6ddff22ebc41466903c966d7e7655">llvm::AppleAcceleratorTable::extract</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a605d26c625db977423d136525feecb89">getAuxMaxAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a766c3350d64dde8af24ef7b600b11185">llvm::object::MachOObjectFile::getChainedFixupsSegments</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aff209a96323a14068980fd74f1fa53df">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::getFirstEl</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#a940c0b94e9bb9dfdb69961d456b47b60">llvm::object::ArchiveMemberHeader::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a99d3e689123b378a1d01ac234f9a6d3c">llvm::object::MachOObjectFile::getUuid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a00941e59a16ad6eb14e905557a612501">llvm::identify_magic</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a49e27b994f55512aa6b1fbf82d2c1fb0">llvm::DynamicAPInt::static_assert_layout</a> and <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a27e478bd5208561e8eb16ec550509761">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeObject</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
