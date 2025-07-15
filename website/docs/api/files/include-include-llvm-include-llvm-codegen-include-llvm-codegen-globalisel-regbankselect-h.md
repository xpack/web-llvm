---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `RegBankSelect.h` File Reference

<p>This file describes the interface of the MachineFunctionPass responsible for assigning the generic virtual registers to register bank. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">llvm/CodeGen/GlobalISel/MachineIRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoptimizationremarkemitter-h">llvm/CodeGen/MachineOptimizationRemarkEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">llvm/CodeGen/RegisterBankInfo.h</a>"
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;memory&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regbankselect">RegBankSelect</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This pass implements the reg bank selector pass used in the GlobalISel pipeline. <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regbankselect/insertpoint">InsertPoint</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract class used to represent an insertion point in a CFG. <a href="/web-llvm/docs/api/classes/llvm/regbankselect/insertpoint/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regbankselect/instrinsertpoint">InstrInsertPoint</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insertion point before or after an instruction. <a href="/web-llvm/docs/api/classes/llvm/regbankselect/instrinsertpoint/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regbankselect/mbbinsertpoint">MBBInsertPoint</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insertion point at the beginning or end of a basic block. <a href="/web-llvm/docs/api/classes/llvm/regbankselect/mbbinsertpoint/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regbankselect/edgeinsertpoint">EdgeInsertPoint</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insertion point on an edge. <a href="/web-llvm/docs/api/classes/llvm/regbankselect/edgeinsertpoint/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement">RepairingPlacement</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Struct used to represent the placement of a repairing point for a given operand. <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regbankselect/mappingcost">MappingCost</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class used to represent the cost for mapping an instruction. <a href="/web-llvm/docs/api/classes/llvm/regbankselect/mappingcost/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This file describes the interface of the MachineFunctionPass responsible for assigning the generic virtual registers to register bank.</p>


<p>By default, the reg bank selector relies on local decisions to assign the register bank. In other words, it looks at one instruction at a time to decide where the operand of that instruction should live.</p>


<p>At higher optimization level, we could imagine that the reg bank selector would use more global analysis and do crazier thing like duplicating instructions and so on. This is future work.</p>


<p>For now, the pass uses a greedy algorithm to decide where the operand of an instruction should live. It asks the target which banks may be used for each operand of the instruction and what is the cost. Then, it chooses the solution which minimize the cost of the instruction plus the cost of any move that may be needed to the values into the right register bank. In other words, the cost for an instruction on a register bank RegBank is: Cost of I on RegBank plus the sum of the cost for bringing the input operands from their current register bank to RegBank. Thus, the following formula: cost(I, RegBank) = cost(I.Opcode, RegBank) + sum(for each arg in I.arguments: costCrossCopy(arg.RegBank, RegBank))</p>


<p>E.g., Let say we are assigning the register bank for the instruction defining v2. v0(A_REGBANK) = ... v1(A_REGBANK) = ... v2 = G_ADD i32 v0, v1 &lt;– MI</p>


<p>The target may say it can generate G_ADD i32 on register bank A and B with a cost of respectively 5 and 1. Then, let say the cost of a cross register bank copies from A to B is 1. The reg bank selector would compare the following two costs: cost(MI, A_REGBANK) = cost(G_ADD, A_REGBANK) + cost(v0.RegBank, A_REGBANK) + cost(v1.RegBank, A_REGBANK) = 5 + cost(A_REGBANK, A_REGBANK) + cost(A_REGBANK,
                                                            A_REGBANK) = 5 + 0 + 0 = 5 cost(MI, B_REGBANK) = cost(G_ADD, B_REGBANK) + cost(v0.RegBank, B_REGBANK) + cost(v1.RegBank, B_REGBANK) = 1 + cost(A_REGBANK, B_REGBANK) + cost(A_REGBANK,
                                                            B_REGBANK) = 1 + 1 + 1 = 3 Therefore, in this specific example, the reg bank selector would choose bank B for MI. v0(A_REGBANK) = ... v1(A_REGBANK) = ... tmp0(B_REGBANK) = COPY v0 tmp1(B_REGBANK) = COPY v1 v2(B_REGBANK) = G_ADD i32 tmp0, tmp1</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
