---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/codegen/lazymachineblockfrequencyinfo-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `LazyMachineBlockFrequencyInfo.h` File Reference

<p>===- <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lazymachineblockfrequencyinfo-h">LazyMachineBlockFrequencyInfo.h</a> - Lazy Block Frequency -*- C++ -*–===// <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">llvm/CodeGen/MachineBlockFrequencyInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">llvm/CodeGen/MachineDominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">llvm/CodeGen/MachineLoopInfo.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazymachineblockfrequencyinfopass">LazyMachineBlockFrequencyInfoPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an alternative analysis pass to <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a>. <a href="/web-llvm/docs/api/classes/llvm/lazymachineblockfrequencyinfopass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>===- <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lazymachineblockfrequencyinfo-h">LazyMachineBlockFrequencyInfo.h</a> - Lazy Block Frequency -*- C++ -*–===//</p>


<p>Part of the LLVM Project, under the Apache License v2.0 with LLVM Exceptions. See <a href="https://llvm.org/LICENSE.txt">https://llvm.org/LICENSE.txt</a> for license information. SPDX-License-Identifier: Apache-2.0 WITH LLVM-exception</p>


<p>===------------------------------------------------------------------—===//</p>


<p>This is an alternative analysis pass to MachineBlockFrequencyInfo. The difference is that with this pass the block frequencies are not computed when the analysis pass is executed but rather when the BFI result is explicitly requested by the analysis client.</p>


<p>===------------------------------------------------------------------—===//</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
