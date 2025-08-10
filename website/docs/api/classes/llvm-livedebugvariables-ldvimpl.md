---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/livedebugvariables/ldvimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LDVImpl` Class



## Declaration

<div class="doxyDeclaration">
class llvm::LiveDebugVariables::LDVImpl { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacf5faad176ec3881ed0a6d7e02e3dd1">VRMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, UserValue * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map virtual register to eq class leader. <a href="#aacf5faad176ec3881ed0a6d7e02e3dd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a356af1b87d7bc95232f8a81298ebdfc8">UVMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a>, UserValue * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map to find existing UserValue instances. <a href="#a356af1b87d7bc95232f8a81298ebdfc8">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a145227c67f733ebe35e623831ac164ca">LDVImpl</a> (LiveIntervals *LIS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e5a4f513cd277250d246664b49e066b">runOnMachineFunction</a> (MachineFunction &amp;mf, bool InstrRef)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a846b1208f5a9a2c2a3dbbe56a809110a">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Release all memory. <a href="#a846b1208f5a9a2c2a3dbbe56a809110a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c8e1e68d0b79b7c31776fa78023d667">mapVirtReg</a> (Register VirtReg, UserValue *EC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map virtual register to an equivalence class. <a href="#a5c8e1e68d0b79b7c31776fa78023d667">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae012de319b29d9d8ef18bf3c2995f679">splitPHIRegister</a> (Register OldReg, ArrayRef&lt; Register &gt; NewRegs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace any PHI referring to OldReg with its corresponding NewReg, if present. <a href="#ae012de319b29d9d8ef18bf3c2995f679">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32778c6eeca26a018747653f3ea0112d">splitRegister</a> (Register OldReg, ArrayRef&lt; Register &gt; NewRegs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace all references to OldReg with NewRegs. <a href="#a32778c6eeca26a018747653f3ea0112d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe5a79d15b373804c482e1905df927ff">emitDebugValues</a> (VirtRegMap *VRM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recreate DBG_VALUE instruction from data structures. <a href="#abe5a79d15b373804c482e1905df927ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25eaa3c387bb2a7275c3deba11335d61">print</a> (raw_ostream &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">UserValue *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada413cece042dcbf14b653a67a7a0ae4">getUserValue</a> (const DILocalVariable *Var, std::optional&lt; DIExpression::FragmentInfo &gt; Fragment, const DebugLoc &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find or create a UserValue. <a href="#ada413cece042dcbf14b653a67a7a0ae4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">UserValue *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08291c511d5356f9a67ee67f313cffa6">lookupVirtReg</a> (Register VirtReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the EC leader for VirtReg or null. <a href="#a08291c511d5356f9a67ee67f313cffa6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c22606bdecf6199bac6964456be7825">handleDebugValue</a> (MachineInstr &amp;MI, SlotIndex Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add DBG_VALUE instruction to our maps. <a href="#a4c22606bdecf6199bac6964456be7825">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85bdfa4d7f68fdfd3d6c761729ccd778">handleDebugInstr</a> (MachineInstr &amp;MI, SlotIndex Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Track variable location debug instructions while using the instruction referencing implementation. <a href="#a85bdfa4d7f68fdfd3d6c761729ccd778">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81f8265e9c0662bda28d1cd5349fe94b">handleDebugLabel</a> (MachineInstr &amp;MI, SlotIndex Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add DBG_LABEL instruction to UserLabel. <a href="#a81f8265e9c0662bda28d1cd5349fe94b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4be5f038126109bb661828d2f22427b">collectDebugValues</a> (MachineFunction &amp;mf, bool InstrRef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect and erase all DBG_VALUE instructions, adding a UserValue def for each instruction. <a href="#ad4be5f038126109bb661828d2f22427b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae83b2a6a905c6ca8a370c613a385fe51">computeIntervals</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the live intervals of all user values after collecting all their def points. <a href="#ae83b2a6a905c6ca8a370c613a385fe51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap/#a6b645fcc5ae44b9a8e2fef275890ae4b">LocMap::Allocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a680712c642ee9e0ec22b8a6d1490c7f2">allocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc763128a93a782731d1c00e5bacf4be">MF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d0939def3d56a706c4495fdaf74023">LIS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4a02093c627ec9343e7815dae767936">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; unsigned, PHIValPos &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a762a8126615492b92aaf35316dae1f68">PHIValToPos</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from debug instruction number to PHI position during allocation. <a href="#a762a8126615492b92aaf35316dae1f68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, std::vector&lt; unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac73d43540db8c09eafec096e5c8df767">RegToPHIIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Index of, for each VReg, which debug instruction numbers and corresponding PHIs are sensitive to splitting. <a href="#ac73d43540db8c09eafec096e5c8df767">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; InstrPos, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73ef503c7cf1d9719f5a0fb5730a97f0">StashedDebugInstrs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection of stored debug instructions, preserved until after regalloc. <a href="#a73ef503c7cf1d9719f5a0fb5730a97f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dd9ac447839509fad63648d0ac0fe0e">EmitDone</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether emitDebugValues is called. <a href="#a5dd9ac447839509fad63648d0ac0fe0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f9905212c1c3a2227b1edbfefb6169b">ModifiedMF</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the machine function is modified during the pass. <a href="#a3f9905212c1c3a2227b1edbfefb6169b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; UserValue &gt;, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5887b68a18118db1c30834474779b27e">userValues</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All allocated UserValue instances. <a href="#a5887b68a18118db1c30834474779b27e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; UserLabel &gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0ec745ea443bd4c31a3a25daa98b083">userLabels</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All allocated UserLabel instances. <a href="#ac0ec745ea443bd4c31a3a25daa98b083">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">VRMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77a6ca38d40b06821b007aeb1189ba52">virtRegToEqClass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">UVMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee5244ca134be3a016b54d6b968ee8a4">userVarMap</a></td>
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


<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### UVMap {#a356af1b87d7bc95232f8a81298ebdfc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveDebugVariables::LDVImpl::UVMap =  DenseMap&lt;DebugVariable, UserValue *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map to find existing UserValue instances.</p>

<p>Definition at line 594 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### VRMap {#aacf5faad176ec3881ed0a6d7e02e3dd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveDebugVariables::LDVImpl::VRMap =  DenseMap&lt;unsigned, UserValue *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map virtual register to eq class leader.</p>

<p>Definition at line 590 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LDVImpl() {#a145227c67f733ebe35e623831ac164ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveDebugVariables::LDVImpl::LDVImpl (<a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LIS)</td>
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



<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#a846b1208f5a9a2c2a3dbbe56a809110a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveDebugVariables::LDVImpl::clear ()</td>
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

<p>Release all memory.</p>

<p>Definition at line 654 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a4e5a4f513cd277250d246664b49e066b">runOnMachineFunction</a>.</p>

</div>
</div>

### emitDebugValues() {#abe5a79d15b373804c482e1905df927ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugVariables::LDVImpl::emitDebugValues (<a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> * VRM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recreate DBG_VALUE instruction from data structures.</p>

<p>Definition at line 681 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adf4e7878fc0b3b8dcde545178564190d">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#a73c2c11c6c943efa25ec3a0802c4ac52">findInsertLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a785a4e2daf4e5bf3f0836adbc4fb7e65">llvm::VirtRegMap::getPhys</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a32846fd2d98022e7b336962f85411a42">llvm::VirtRegMap::getStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#ab28bf4ffd3e2223dab0527c9d7e18288">llvm::VirtRegMap::hasPhys</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#ad0df6033e4012261f7531e62274cf99c">llvm::VirtRegMap::isAssignedReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#ad2e99ae080aa934d64b0ff504dab0158">llvm::VirtRegMap::NO_STACK_SLOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5bacbbd03e9261f7b30dc174f26d680c">llvm::skipDebugInstructionsForward</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### mapVirtReg() {#a5c8e1e68d0b79b7c31776fa78023d667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugVariables::LDVImpl::mapVirtReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VirtReg, UserValue * EC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map virtual register to an equivalence class.</p>

<p>Definition at line 671 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a> and <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a92af0086d7d75d96d35ccc03ebc66b4d">anonymous{LiveDebugVariables.cpp}::UserValue::merge</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#aad49be349dc20188ea9201eddb54ad75">anonymous{LiveDebugVariables.cpp}::UserValue::mapVirtRegs</a> and <a href="#a32778c6eeca26a018747653f3ea0112d">splitRegister</a>.</p>

</div>
</div>

### print() {#a25eaa3c387bb2a7275c3deba11335d61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugVariables::LDVImpl::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 683 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a4e5a4f513cd277250d246664b49e066b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveDebugVariables::LDVImpl::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; mf, bool InstrRef)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>References <a href="#a846b1208f5a9a2c2a3dbbe56a809110a">clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#aaf0c07cc1cdb9c78c6dfdfdd5913420a">llvm::SlotIndexes::getMBBStartIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables/#a5cbf3e865e4410106fabce54174ef923">llvm::LiveDebugVariables::print</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>.</p>

</div>
</div>

### splitPHIRegister() {#ae012de319b29d9d8ef18bf3c2995f679}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugVariables::LDVImpl::splitPHIRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OldReg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; NewRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace any PHI referring to OldReg with its corresponding NewReg, if present.</p>

<p>Definition at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a757fd6afba0f531db70e78e057d147c6">llvm::LiveRange::end</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#afeb00b9049a2391c990df15692caef63">llvm::LiveRange::find</a>.</p>


<p>Referenced by <a href="#a32778c6eeca26a018747653f3ea0112d">splitRegister</a>.</p>

</div>
</div>

### splitRegister() {#a32778c6eeca26a018747653f3ea0112d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugVariables::LDVImpl::splitRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OldReg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; NewRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace all references to OldReg with NewRegs.</p>

<p>Definition at line 678 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>References <a href="#a5c8e1e68d0b79b7c31776fa78023d667">mapVirtReg</a> and <a href="#ae012de319b29d9d8ef18bf3c2995f679">splitPHIRegister</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### collectDebugValues() {#ad4be5f038126109bb661828d2f22427b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveDebugVariables::LDVImpl::collectDebugValues (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; mf, bool InstrRef)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect and erase all DBG_VALUE instructions, adding a UserValue def for each instruction.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">mf</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> to be scanned.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InstrRef</td>
<td class="doxyParamItemDescription"><p>Whether to operate in instruction referencing mode. If true, most of <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables">LiveDebugVariables</a> doesn't run.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if any debug values were found.</p></dd>
</dl>


<p>Definition at line 642 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### computeIntervals() {#ae83b2a6a905c6ca8a370c613a385fe51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugVariables::LDVImpl::computeIntervals ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the live intervals of all user values after collecting all their def points.</p>

<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### getUserValue() {#ada413cece042dcbf14b653a67a7a0ae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UserValue * LiveDebugVariables::LDVImpl::getUserValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * Var, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a2a09e6caba71ab15519f9e55ceb4d10d">DIExpression::FragmentInfo</a> &gt; Fragment, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find or create a UserValue.</p>

<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### handleDebugInstr() {#a85bdfa4d7f68fdfd3d6c761729ccd778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator LiveDebugVariables::LDVImpl::handleDebugInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Track variable location debug instructions while using the instruction referencing implementation.</p>


<p>Such debug instructions do not need to be updated during regalloc because they identify instructions rather than register locations. However, they needs to be removed from the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> during regalloc, then re-inserted later, to avoid disrupting the allocator.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MI</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> DBG_VALUE / DBG_INSTR_REF / DBG_PHI instruction</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Idx</td>
<td class="doxyParamItemDescription"><p>Last valid <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> before instruction</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Iterator to continue processing from after unlinking.</p></dd>
</dl>


<p>Definition at line 624 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### handleDebugLabel() {#a81f8265e9c0662bda28d1cd5349fe94b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveDebugVariables::LDVImpl::handleDebugLabel (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add DBG_LABEL instruction to UserLabel.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MI</td>
<td class="doxyParamItemDescription"><p>DBG_LABEL instruction</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Idx</td>
<td class="doxyParamItemDescription"><p>Last valid <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> before instruction.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the DBG_LABEL instruction should be deleted.</p></dd>
</dl>


<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### handleDebugValue() {#a4c22606bdecf6199bac6964456be7825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveDebugVariables::LDVImpl::handleDebugValue (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add DBG_VALUE instruction to our maps.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MI</td>
<td class="doxyParamItemDescription"><p>DBG_VALUE instruction</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Idx</td>
<td class="doxyParamItemDescription"><p>Last valid SLotIndex before instruction.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the DBG_VALUE instruction should be deleted.</p></dd>
</dl>


<p>Definition at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### lookupVirtReg() {#a08291c511d5356f9a67ee67f313cffa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UserValue * LiveDebugVariables::LDVImpl::lookupVirtReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VirtReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the EC leader for VirtReg or null.</p>

<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### allocator {#a680712c642ee9e0ec22b8a6d1490c7f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocMap::Allocator llvm::LiveDebugVariables::LDVImpl::allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### EmitDone {#a5dd9ac447839509fad63648d0ac0fe0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveDebugVariables::LDVImpl::EmitDone = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether emitDebugValues is called.</p>

<p>Definition at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### LIS {#af1d0939def3d56a706c4495fdaf74023}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals* llvm::LiveDebugVariables::LDVImpl::LIS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### MF {#acc763128a93a782731d1c00e5bacf4be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::LiveDebugVariables::LDVImpl::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### ModifiedMF {#a3f9905212c1c3a2227b1edbfefb6169b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveDebugVariables::LDVImpl::ModifiedMF = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether the machine function is modified during the pass.</p>

<p>Definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### PHIValToPos {#a762a8126615492b92aaf35316dae1f68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;unsigned, PHIValPos&gt; llvm::LiveDebugVariables::LDVImpl::PHIValToPos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from debug instruction number to PHI position during allocation.</p>

<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### RegToPHIIdx {#ac73d43540db8c09eafec096e5c8df767}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Register, std::vector&lt;unsigned&gt; &gt; llvm::LiveDebugVariables::LDVImpl::RegToPHIIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Index of, for each VReg, which debug instruction numbers and corresponding PHIs are sensitive to splitting.</p>


<p>Each VReg may have multiple PHI defs, at different positions.</p>


<p>Definition at line 563 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### StashedDebugInstrs {#a73ef503c7cf1d9719f5a0fb5730a97f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;InstrPos, 32&gt; llvm::LiveDebugVariables::LDVImpl::StashedDebugInstrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collection of stored debug instructions, preserved until after regalloc.</p>

<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### TRI {#ad4a02093c627ec9343e7815dae767936}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::LiveDebugVariables::LDVImpl::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### userLabels {#ac0ec745ea443bd4c31a3a25daa98b083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;UserLabel&gt;, 2&gt; llvm::LiveDebugVariables::LDVImpl::userLabels</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All allocated UserLabel instances.</p>

<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### userValues {#a5887b68a18118db1c30834474779b27e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;UserValue&gt;, 8&gt; llvm::LiveDebugVariables::LDVImpl::userValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All allocated UserValue instances.</p>

<p>Definition at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### userVarMap {#aee5244ca134be3a016b54d6b968ee8a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UVMap llvm::LiveDebugVariables::LDVImpl::userVarMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### virtRegToEqClass {#a77a6ca38d40b06821b007aeb1189ba52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VRMap llvm::LiveDebugVariables::LDVImpl::virtRegToEqClass</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 591 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
