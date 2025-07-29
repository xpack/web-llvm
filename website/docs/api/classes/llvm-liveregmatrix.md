---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/liveregmatrix
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LiveRegMatrix` Class



## Declaration

<div class="doxyDeclaration">
class llvm::LiveRegMatrix { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">llvm/CodeGen/LiveRegMatrix.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">InterferenceKind { <a href="#ab317b81a1c575049207d5d9348d8635a">...</a> }</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dde01d9f410b6669c368256c19b177c">LiveRegMatrixWrapperLegacy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60bef7f4a836cd97f9704940f259a6ae">LiveRegMatrixAnalysis</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad35570d655e9aa2f22134465c80a8c5d">LiveRegMatrix</a> (LiveRegMatrix &amp;&amp;Other)=default</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a182b56e093854090d170ecdc7fee75cd">LiveRegMatrix</a> ()</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1907c90bcd96c06c880601406ce946c">init</a> (MachineFunction &amp;MF, LiveIntervals &amp;LIS, VirtRegMap &amp;VRM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a448841a51094959c1ca24de1ae55435f">invalidateVirtRegs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Invalidate cached interference queries after modifying virtual register live ranges. <a href="#a448841a51094959c1ca24de1ae55435f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab317b81a1c575049207d5d9348d8635a">InterferenceKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad064f1e4af82a7f4251434afde29b0b5">checkInterference</a> (const LiveInterval &amp;VirtReg, MCRegister PhysReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for interference before assigning VirtReg to PhysReg. <a href="#ad064f1e4af82a7f4251434afde29b0b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9e855199959852351ae2761ae4302be">checkInterference</a> (SlotIndex Start, SlotIndex End, MCRegister PhysReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for interference in the segment [Start, End) that may prevent assignment to PhysReg. <a href="#ab9e855199959852351ae2761ae4302be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc6ed60b40c5c63149c23ba327a77c23">checkInterferenceLanes</a> (SlotIndex Start, SlotIndex End, MCRegister PhysReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for interference in the segment [Start, End) that may prevent assignment to PhysReg, like checkInterference. <a href="#afc6ed60b40c5c63149c23ba327a77c23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca181a8107cd511dad6c6627fe9f6fae">assign</a> (const LiveInterval &amp;VirtReg, MCRegister PhysReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assign VirtReg to PhysReg. <a href="#aca181a8107cd511dad6c6627fe9f6fae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a128d0b27fb99ba10fc96a8c526129157">unassign</a> (const LiveInterval &amp;VirtReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unassign VirtReg from its PhysReg. <a href="#a128d0b27fb99ba10fc96a8c526129157">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28429b5d6afc4dc076b94527f2cb1de8">isPhysRegUsed</a> (MCRegister PhysReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the given <span class="doxyComputerOutput">PhysReg</span> has any live intervals assigned. <a href="#a28429b5d6afc4dc076b94527f2cb1de8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0afff12e511e93ff630cada967573162">checkRegMaskInterference</a> (const LiveInterval &amp;VirtReg, MCRegister PhysReg=MCRegister::NoRegister)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for regmask interference only. <a href="#a0afff12e511e93ff630cada967573162">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad08d47c88b8af3c45df94d19ccc6e679">checkRegUnitInterference</a> (const LiveInterval &amp;VirtReg, MCRegister PhysReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for regunit interference only. <a href="#ad08d47c88b8af3c45df94d19ccc6e679">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/query">LiveIntervalUnion::Query</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c79a2c92779f3c549dee89406ccdfc1">query</a> (const LiveRange &amp;LR, MCRegUnit RegUnit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Query a line of the assigned virtual register matrix directly. <a href="#a7c79a2c92779f3c549dee89406ccdfc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervalunion">LiveIntervalUnion</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee36714e41bf6584fb0eb5728ee55df5">getLiveUnions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Directly access the live interval unions per regunit. <a href="#aee36714e41bf6584fb0eb5728ee55df5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59599eeb1c2ffa96071e18dfee6febc2">getOneVReg</a> (unsigned PhysReg) const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c6decab5728e5fb4b1bfff4c45561de">releaseMemory</a> ()</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a264a590cf9f5dd9119ede69866c5dcef">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d2cf4754429afb915cc267aaeb54078">LIS</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a750b07161a4c234887b5c5b828864dda">VRM</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafa52dd8c45eeae467e627591e608733">UserTag</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/#aec9428cfe59ce0851615cef7e5527a01">LiveIntervalUnion::Allocator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b55219113fc5b05c9aa60fe6e225ce3">LIUAlloc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/array">LiveIntervalUnion::Array</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6f66f13845ab19b6e4a4405d38d9e06">Matrix</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/query">LiveIntervalUnion::Query</a>[]&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa96aeb98f7787032f2ed15c447dea0b6">Queries</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac29d584ff17dc912c8f0e9ceb18b2ad1">RegMaskTag</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a646918ffd3fbaa0d9343acd0d2af19ab">RegMaskVirtReg</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaecdef078e475b5b24673d6471576ab3">RegMaskUsable</a></td>
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


<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### InterferenceKind {#ab317b81a1c575049207d5d9348d8635a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LiveRegMatrix::InterferenceKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_Free<a id="ab317b81a1c575049207d5d9348d8635aa58056f4f8345af4ca8bd6e27f0ff8413"></a></td>
<td class="doxyEnumItemDescription">No interference, go ahead and assign (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_VirtReg<a id="ab317b81a1c575049207d5d9348d8635aa30186d61b40f517e8dc5d9e85076a91f"></a></td>
<td class="doxyEnumItemDescription">Virtual register interference</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_RegUnit<a id="ab317b81a1c575049207d5d9348d8635aa471b00a6595e7f400ef576512ccbcc31"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> unit interference</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_RegMask<a id="ab317b81a1c575049207d5d9348d8635aaa3c968c8898b0110e68e4933485c9042"></a></td>
<td class="doxyEnumItemDescription">RegMask interference</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### LiveRegMatrixAnalysis {#a60bef7f4a836cd97f9704940f259a6ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/liveregmatrixanalysis">LiveRegMatrixAnalysis</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp/#ad5d00e1d77644d95847b9bf8da12b759">Allocator</a> and <a href="#a60bef7f4a836cd97f9704940f259a6ae">LiveRegMatrixAnalysis</a>.</p>


<p>Referenced by <a href="#a60bef7f4a836cd97f9704940f259a6ae">LiveRegMatrixAnalysis</a>.</p>

</div>
</div>

### LiveRegMatrixWrapperLegacy {#a4dde01d9f410b6669c368256c19b177c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/liveregmatrixwrapperlegacy">LiveRegMatrixWrapperLegacy</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>.</p>


<p>Reference <a href="#a4dde01d9f410b6669c368256c19b177c">LiveRegMatrixWrapperLegacy</a>.</p>


<p>Referenced by <a href="#a4dde01d9f410b6669c368256c19b177c">LiveRegMatrixWrapperLegacy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LiveRegMatrix() {#ad35570d655e9aa2f22134465c80a8c5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveRegMatrix::LiveRegMatrix (<a href="/web-llvm/docs/api/classes/llvm/liveregmatrix">LiveRegMatrix</a> &amp;&amp; Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### LiveRegMatrix() {#a182b56e093854090d170ecdc7fee75cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveRegMatrix::LiveRegMatrix ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### assign() {#aca181a8107cd511dad6c6627fe9f6fae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRegMatrix::assign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assign VirtReg to PhysReg.</p>


<p>This will mark VirtReg's live range as occupied in the <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix">LiveRegMatrix</a> and update <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a>. The live range is expected to be available in PhysReg.</p>


<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp">LiveRegMatrix.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp/#aab2ae433d483c154d92c727cf7282996">foreachUnit</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a34302b557354b8a09796c30b9f7408ab">llvm::printRegUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a>.</p>

</div>
</div>

### checkInterference() {#ad064f1e4af82a7f4251434afde29b0b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRegMatrix::InterferenceKind LiveRegMatrix::checkInterference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for interference before assigning VirtReg to PhysReg.</p>


<p>If this function returns IK_Free, it is legal to assign(VirtReg, PhysReg). When there is more than one kind of interference, the <a href="#ab317b81a1c575049207d5d9348d8635a">InterferenceKind</a> with the highest enum value is returned.</p>


<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp">LiveRegMatrix.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/query/#ab7eacb4ff3e11e61bbe97acaf46d47d8">llvm::LiveIntervalUnion::Query::checkInterference</a>, <a href="#a0afff12e511e93ff630cada967573162">checkRegMaskInterference</a>, <a href="#ad08d47c88b8af3c45df94d19ccc6e679">checkRegUnitInterference</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a66ff664a97cd3c30de7e873335a0c075">llvm::LiveRange::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp/#aab2ae433d483c154d92c727cf7282996">foreachUnit</a>, <a href="#ab317b81a1c575049207d5d9348d8635aa58056f4f8345af4ca8bd6e27f0ff8413">IK_Free</a>, <a href="#ab317b81a1c575049207d5d9348d8635aaa3c968c8898b0110e68e4933485c9042">IK_RegMask</a>, <a href="#ab317b81a1c575049207d5d9348d8635aa471b00a6595e7f400ef576512ccbcc31">IK_RegUnit</a>, <a href="#ab317b81a1c575049207d5d9348d8635aa30186d61b40f517e8dc5d9e85076a91f">IK_VirtReg</a> and <a href="#a7c79a2c92779f3c549dee89406ccdfc1">query</a>.</p>

</div>
</div>

### checkInterference() {#ab9e855199959852351ae2761ae4302be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveRegMatrix::checkInterference (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Start, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> End, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for interference in the segment [Start, End) that may prevent assignment to PhysReg.</p>


<p>If this function returns true, there is interference in the segment [Start, End) of some other interval already assigned to PhysReg. If this function returns false, PhysReg is free at the segment [Start, End).</p>


<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>, definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp">LiveRegMatrix.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liverange/#a0b73c8d5ae32ca13dd02ddde86ffd0a2">llvm::LiveRange::addSegment</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/query/#ab7eacb4ff3e11e61bbe97acaf46d47d8">llvm::LiveIntervalUnion::Query::checkInterference</a> and <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/query/#ae8729ee921fdf522087d928c9bb38af4">llvm::LiveIntervalUnion::Query::reset</a>.</p>

</div>
</div>

### checkInterferenceLanes() {#afc6ed60b40c5c63149c23ba327a77c23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LaneBitmask LiveRegMatrix::checkInterferenceLanes (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Start, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> End, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for interference in the segment [Start, End) that may prevent assignment to PhysReg, like checkInterference.</p>


<p>Returns a lane mask of which lanes of the physical register interfere in the segment [Start, End) of some other interval already assigned to PhysReg.</p>


<p>If this function returns <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a9082b6aa4021114645045d9c5628eb26">LaneBitmask::getNone()</a>, PhysReg is completely free at the segment [Start, End).</p>


<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>, definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp">LiveRegMatrix.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liverange/#a0b73c8d5ae32ca13dd02ddde86ffd0a2">llvm::LiveRange::addSegment</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/query/#ab7eacb4ff3e11e61bbe97acaf46d47d8">llvm::LiveIntervalUnion::Query::checkInterference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregunitmaskiterator/#a73b0d1192402b944dbc7aac0db77258d">llvm::MCRegUnitMaskIterator::isValid</a> and <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/query/#ae8729ee921fdf522087d928c9bb38af4">llvm::LiveIntervalUnion::Query::reset</a>.</p>

</div>
</div>

### checkRegMaskInterference() {#a0afff12e511e93ff630cada967573162}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveRegMatrix::checkRegMaskInterference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg=<a href="/web-llvm/docs/api/classes/llvm/mcregister/#a4aa6aac0f36c1123df3686f7b4150d2c">MCRegister::NoRegister</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for regmask interference only.</p>


<p>Return true if VirtReg crosses a regmask operand that clobbers PhysReg. If PhysReg is null, check if VirtReg crosses any regmask operands.</p>


<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp">LiveRegMatrix.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcregister/#af8403cc977c65b910e618ebcb6a12c32">llvm::MCRegister::id</a> and <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a>.</p>


<p>Referenced by <a href="#ad064f1e4af82a7f4251434afde29b0b5">checkInterference</a>.</p>

</div>
</div>

### checkRegUnitInterference() {#ad08d47c88b8af3c45df94d19ccc6e679}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveRegMatrix::checkRegUnitInterference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for regunit interference only.</p>


<p>Return true if VirtReg overlaps a fixed assignment of one of PhysRegs's register units.</p>


<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>, definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp">LiveRegMatrix.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liverange/#a66ff664a97cd3c30de7e873335a0c075">llvm::LiveRange::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp/#aab2ae433d483c154d92c727cf7282996">foreachUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a>.</p>


<p>Referenced by <a href="#ad064f1e4af82a7f4251434afde29b0b5">checkInterference</a>.</p>

</div>
</div>

### getLiveUnions() {#aee36714e41bf6584fb0eb5728ee55df5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervalUnion * llvm::LiveRegMatrix::getLiveUnions ()</td>
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

<p>Directly access the live interval unions per regunit.</p>


<p>This returns an array indexed by the regunit number.</p>


<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>.</p>

</div>
</div>

### getOneVReg() {#a59599eeb1c2ffa96071e18dfee6febc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register LiveRegMatrix::getOneVReg (unsigned PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>, definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp">LiveRegMatrix.cpp</a>.</p>


<p>References <a href="#a59599eeb1c2ffa96071e18dfee6febc2">getOneVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregister/#a4aa6aac0f36c1123df3686f7b4150d2c">llvm::MCRegister::NoRegister</a> and <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a>.</p>


<p>Referenced by <a href="#a59599eeb1c2ffa96071e18dfee6febc2">getOneVReg</a>.</p>

</div>
</div>

### init() {#ac1907c90bcd96c06c880601406ce946c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRegMatrix::init (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS, <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> &amp; VRM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp">LiveRegMatrix.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a1a06f2509b5f901646c6498e9a0e8d4f">llvm::VirtRegMap::init</a> and <a href="#a448841a51094959c1ca24de1ae55435f">invalidateVirtRegs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveregmatrixanalysis/#a2b601beea6193fd88698584c85cdadcd">llvm::LiveRegMatrixAnalysis::run</a>.</p>

</div>
</div>

### invalidateVirtRegs() {#a448841a51094959c1ca24de1ae55435f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveRegMatrix::invalidateVirtRegs ()</td>
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

<p>Invalidate cached interference queries after modifying virtual register live ranges.</p>


<p>Interference checks may return stale information unless caches are invalidated.</p>


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>.</p>


<p>Referenced by <a href="#ac1907c90bcd96c06c880601406ce946c">init</a>.</p>

</div>
</div>

### isPhysRegUsed() {#a28429b5d6afc4dc076b94527f2cb1de8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveRegMatrix::isPhysRegUsed (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the given <span class="doxyComputerOutput">PhysReg</span> has any live intervals assigned.</p>

<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>, definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp">LiveRegMatrix.cpp</a>.</p>

</div>
</div>

### query() {#a7c79a2c92779f3c549dee89406ccdfc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervalUnion::Query &amp; LiveRegMatrix::query (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/namespaces/llvm/#a8adc81fee7f9e66260dd2b626660c9c9">MCRegUnit</a> RegUnit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Query a line of the assigned virtual register matrix directly.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <a href="/web-llvm/docs/api/classes/llvm/mcregunititerator">MCRegUnitIterator</a> to enumerate all regunits in the desired PhysReg. This returns a reference to an internal Query data structure that is only valid until the next <a href="#a7c79a2c92779f3c549dee89406ccdfc1">query()</a> call.</p>


<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>, definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp">LiveRegMatrix.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/query/#a5a7f80461ba4f83724785b271058e0f1">llvm::LiveIntervalUnion::Query::init</a>.</p>


<p>Referenced by <a href="#ad064f1e4af82a7f4251434afde29b0b5">checkInterference</a>.</p>

</div>
</div>

### unassign() {#a128d0b27fb99ba10fc96a8c526129157}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRegMatrix::unassign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unassign VirtReg from its PhysReg.</p>


<p>Assuming that VirtReg was previously assigned to a PhysReg, this undoes the assignment and updates <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> accordingly.</p>


<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>, definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp">LiveRegMatrix.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp/#aab2ae433d483c154d92c727cf7282996">foreachUnit</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a34302b557354b8a09796c30b9f7408ab">llvm::printRegUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### releaseMemory() {#a2c6decab5728e5fb4b1bfff4c45561de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRegMatrix::releaseMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp">LiveRegMatrix.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LIS {#a9d2cf4754429afb915cc267aaeb54078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals* llvm::LiveRegMatrix::LIS = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>.</p>

</div>
</div>

### LIUAlloc {#a3b55219113fc5b05c9aa60fe6e225ce3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;LiveIntervalUnion::Allocator&gt; llvm::LiveRegMatrix::LIUAlloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>.</p>

</div>
</div>

### Matrix {#ac6f66f13845ab19b6e4a4405d38d9e06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervalUnion::Array llvm::LiveRegMatrix::Matrix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>.</p>

</div>
</div>

### Queries {#aa96aeb98f7787032f2ed15c447dea0b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;LiveIntervalUnion::Query[]&gt; llvm::LiveRegMatrix::Queries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>.</p>

</div>
</div>

### RegMaskTag {#ac29d584ff17dc912c8f0e9ceb18b2ad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LiveRegMatrix::RegMaskTag = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>.</p>

</div>
</div>

### RegMaskUsable {#aaecdef078e475b5b24673d6471576ab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::LiveRegMatrix::RegMaskUsable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>.</p>

</div>
</div>

### RegMaskVirtReg {#a646918ffd3fbaa0d9343acd0d2af19ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LiveRegMatrix::RegMaskVirtReg = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>.</p>

</div>
</div>

### TRI {#a264a590cf9f5dd9119ede69866c5dcef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::LiveRegMatrix::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>.</p>

</div>
</div>

### UserTag {#aafa52dd8c45eeae467e627591e608733}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LiveRegMatrix::UserTag = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>.</p>

</div>
</div>

### VRM {#a750b07161a4c234887b5c5b828864dda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VirtRegMap* llvm::LiveRegMatrix::VRM = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">LiveRegMatrix.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp">LiveRegMatrix.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
